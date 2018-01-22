# [Thoughts On Governance and Network Effects](https://blog.aragon.one/thoughts-on-governance-and-network-effects-f40fda3e3f98)

_Author [Luke Duncan / @lkngtn](https://github.com/lkngtn)_

_This article was originally posted in the [Aragon Blog](https://blog.aragon.one/) on Dec 12 2017_

![](images/thoughts_on_governance01.png)

This post discusses governance and its impact on network effects and why both relate to how value flows and is captured within tokenized blockchain networks.

## Hardware, Software, and Data are commoditized by decentralization
The process of commoditization turns a good or service which is highly differentiated or even unique into a fungible resource, where differences between the commodity offered by sellers in a market are low. Commoditized markets are associated with declining prices and narrow profit margins, as competitors struggle to differentiate their offerings and instead rely on price-based competition.

- **Hardware**: Ethereum lets you pay for computation and storage on an as-needed basis by paying gas. Projects like Golem, Storj, Truebit, and others aim to further commoditize hardware through decentralized networks. Products that build on these technologies cannot rely on specialized hardware as a key differentiator.
- **Software**: Open source software is commoditized, there is no difference between one instance of public code versus another instance of the same code. Since the only applications that make sense to run on a blockchain are those that benefit from trust-minimization, public source code is the standard.
- **Data**: Decentralized applications rely on publicly available data sources, otherwise there is no way for the public to validate transactions. Privacy technology such as zk-Snarks may obscure public visibility, but the encrypted dataset that enables a shared state remains public.

Products or services offered in a market like this will either compete on price, quickly driving profit margins down or seek out new ways to differentiate themselves.

**One way to differentiate is to issue a token**, even if you don’t otherwise need one. Having a token allows you to create a network effect around your product, people who hold this token will have a vested interest and prefer your product over alternatives. They will be your biggest advocates, they will shill your product to all their friends, who will jump on the band wagon, and do the same to their friends… and on and on. Or maybe not…

If the market is commoditized and your competitors have at best an equivalent product to yours, issuing a token and requiring it to be used in order to access your product works (sort of like an API key). However, by forcing the use of a token when your application doesn’t require one you create a worse user experience because the user’s effective cost is unpredictable. Now if a competitor offers the same product without the restriction, it isn’t equivalent, it is objectively better. Therefore, differentiation in this way may work to some degree, but is not particularly defensible.

## Defensible tokenization
In a **defensible token model** you cannot remove the token or replace it with a different token and create a better user experience.

To help reason about the **defensibility** of different tokenization models, identifying a baseline that all defensible token models have in common is helpful:

- **A**: Fees are justified for **services provided**. The execution of arbitrary smart-contract code does not justify paying fees in excess of the gas used to validate/mine transactions.
- **B**: It is not defensible to force the usage of a token in such a way that the application would work **equally well or better using a different token**. (e.g. a stable coin, or ETH)
- **C**: Tokens which are uniquely **required** to incentivize or disincentivize behavior in order **to provide a service** accrue value relative to that services utility.

If we agree on these statements we can immediately throw out many tokenization strategies. For example **a token whose primary utility is to be the exclusive medium of exchange** for transactions within a network violates all three of these statements. **[A]** because having to convert to the native token is an **arbitrary fee** unrelated to a service. **[B]** because in a market that requires a medium of exchange, a stable token that **everyone already has** works far better than the application’s native token. **[C]** because the token is not inherently linked to the incentivization of agents **performing** a service.

We can also look at some models which do not violate any of these statements. Proof of Work, Proof of Stake, decentralized oracles, Token Curated Registries. Each instance of these mechanisms requires its own unique token to make the crypto-economic incentives align between multiple parties. Defensible tokenization exists at the blockchain protocol level (Proof of Work, Proof of Stake) and at the blockchain application layer (decentralized oracles, Token Curated Registries).

**The key difference is not whether the product is a protocol or an application, but whether the network effect driven by tokenization is defensible or not.**

However, having a defensible token model is not sufficient to maintain a strong **network effect**. Token balances can be copied by competitors, software and datasets can be forked, **how do you ensure that your token holders are loyal and will continue to prefer your service over that of competitors?**

## Loyalty is everything
Networks are anti-rival with network effects that push towards monopolistic competition, but commoditization driven by decentralization pushes the market towards perfect competition. Decentralized networks will either be wildly successful, or have minimal value, and the biggest factor is how well the network is able to nurture its network effect.

We can understand this effect from the perspective of an individual participant using **Albert Hirchman’s theory** of **Exit, Voice, and Loyalty**. The theory says that an individual who perceives a decline in the benefit of remaining within a group may respond by **Exit, leaving the group,** or **Voice, by proposing changes that would increase their benefit**.

In the context of networks built on blockchains the individual may exit by either selling their tokens, or by forking and creating a competitive product.

Someone who is considering quitting Facebook not only has to quit they have to start a new service from scratch without any user accounts or data. Blockchain networks are different, a fork can replicate not just the applications software, but also the state. Now the user can quit and move over to a perfect alternative, and they can more easily convince their friends to switch as well, there is **significantly less friction for exit in the context of blockchain-based networks**.

That’s not to say that there is no friction when exiting, network effects have inertia and most participants prefer to stay on whichever network the majority of their peers support. However, if we acknowledge that the biggest barrier to a fork is the desire to maintain a network effect, **than we come to the conclusion that we must maximize Voice of network participants**.

The best way to maximize voice is through effective governance.

## The Governance Imperative
Governance processes may be formal or informal, on-chain or off-chain, the exact details are less important so long as the process is effective and legitimate enough to maintain loyalty and attract more new network constituents over time.

Union Square Ventures pointed to governance as the new basis for competion nearly ten years ago. Fred Ehrsam’s recent post on governance suggests that blockchain networks will result in a Cambrian explosion of governance processes. In a tokenized ecosystem that enables rapid experimentation with governance processes, improving our governance processes is imperative. Anything that relies on a governance process today must be willing and able to rapidly adopt new processes or risk being left behind by the competition.

**The processes that are “effective and legitimate” enough today may not be as soon as it becomes common knowledge that a better alternative exists.**

In some cases our existing structures are complex, emergent, and not well documented and as Vlad Zamfir’s recent post against moving to on-chain governance for Ethereum points out replacing something you don’t fully understand with something you do is not necessarily wise. In other cases we are confident our current processes are problematic and need to be replaced as quickly as possible.

DApp developers face the challenge of writing applications that need to be future-proof despite being deployed in an environment still under development. They must decide between immutability and upgradeability. Despite their best efforts bugs may be found in production, and it would be good if fixes could be applied quickly. Even if they choose to write immutable contracts, if users typically access their contracts through a DNS and ENS pointer, then a governance process is needed to manage that change.

For a product to be decentralized, **it must be impossible for a single individual or small team to unilaterally** make changes. Current approaches to govern smart-contract upgradeability such as using a multi-sig are highly centralized. Whereas adopting tokenized governance transfers the authority of changes that impact the community to the community itself.

DApp developers will likely be the earliest and most successful adopters of tokenized governance models. At first this may simply be a way to securely update smart contracts, but it should expand to more abstract decisions that attract and maintain a community’s network effect both at the application and at the protocol layer.

## Governance as a Service (GaaS)
Governance as a Service (GaaS) is a tokenization model where the primary utility of a token is governance over the protocol, application, or network.

Token holders are the only party whose interest we can programmatically quantify. Other relevant parties exist, including users, developers, miners, and validators, but their interests in the network are not programatically quantifiable. By entrusting decisions which impact the network to token holders, they become the keepers of the network effect. The service they are providing is formal representation of the informal interests of all network participants.

![](images/thoughts_on_governance02.png)

The model is defensible because **[A]** fees can be justified for the service token holders provide (making decisions that ensure the long term sustainability and growth of the network). If token holders do a bad job, or charge excessive fees, the network will fail, but if they do a good job they will be able to adapt to changing market conditions and be more resilient to the effects of commoditization. **[B]** Properties like stability are not critical to participating in governance. **[C]** Using a unique token is required because it quantifies a users influence in order to align incentivizes to ensure the service provided is consistent.

The value of a governance token accrues relative to the importance of the decisions being made. The more people that use the product and rely on its functionality, the more important critical decisions become, the more value will flow to the governance token.

## Conclusion
If you’re building a product that relies on a network effect, creating a governance token or adding governance privileges to your existing token can be incredibly powerful. It increases voice for participants and makes the network effects more resilient.

There are many promising approaches to token based governance including quadratic voting, liquid democracy, futarchy, and many forms of meritocracy that warrant attention.

Each process has different strengths and weaknesses, some which are obvious and others which may require experimental implementations to uncover.

It’s unclear what the ideal governance mechanism is, or if there is even an effective one-size-fits all mechanism. It is clear, however, that **finding better mechanisms is extremely valuable**.

At Aragon we are building infrastructure to support these experiments. aragonOS allows for governance applications to be built and shared between organizations, and privileges can be set such that more experimental models can be tried in limited capacities at first and gradually given more authority. This will enable us to bring continuous improvement processes from the software world into the realm of economics and social sciences, while maintaining acceptable levels of risk.
