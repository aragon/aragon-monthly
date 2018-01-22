# [Thoughts On Governance and Network Effects](https://blog.aragon.one/thoughts-on-governance-and-network-effects-f40fda3e3f98)
2
​
3
_Author [Luke Duncan / @lkngtn](https://github.com/lkngtn)_
4
​
5
_This article was originally posted in the [Aragon Blog](https://blog.aragon.one/) on Dec 12 2017_
6
​
7
![](images/thoughts_on_governance01.png)
8
​
9
This post discusses governance and its impact on network effects and why both relate to how value flows and is captured within tokenized blockchain networks.
10
​
11
## Hardware, Software, and Data are commoditized by decentralization
12
The process of commoditization turns a good or service which is highly differentiated or even unique into a fungible resource, where differences between the commodity offered by sellers in a market are low. Commoditized markets are associated with declining prices and narrow profit margins, as competitors struggle to differentiate their offerings and instead rely on price-based competition.
13
​
14
- **Hardware**: Ethereum lets you pay for computation and storage on an as-needed basis by paying gas. Projects like Golem, Storj, Truebit, and others aim to further commoditize hardware through decentralized networks. Products that build on these technologies cannot rely on specialized hardware as a key differentiator.
15
- **Software**: Open source software is commoditized, there is no difference between one instance of public code versus another instance of the same code. Since the only applications that make sense to run on a blockchain are those that benefit from trust-minimization, public source code is the standard.
16
- **Data**: Decentralized applications rely on publicly available data sources, otherwise there is no way for the public to validate transactions. Privacy technology such as zk-Snarks may obscure public visibility, but the encrypted dataset that enables a shared state remains public.
17
​
18
Products or services offered in a market like this will either compete on price, quickly driving profit margins down or seek out new ways to differentiate themselves.
19
​
20
**One way to differentiate is to issue a token**, even if you don’t otherwise need one. Having a token allows you to create a network effect around your product, people who hold this token will have a vested interest and prefer your product over alternatives. They will be your biggest advocates, they will shill your product to all their friends, who will jump on the band wagon, and do the same to their friends… and on and on. Or maybe not…
21
​
22
If the market is commoditized and your competitors have at best an equivalent product to yours, issuing a token and requiring it to be used in order to access your product works (sort of like an API key). However, by forcing the use of a token when your application doesn’t require one you create a worse user experience because the user’s effective cost is unpredictable. Now if a competitor offers the same product without the restriction, it isn’t equivalent, it is objectively better. Therefore, differentiation in this way may work to some degree, but is not particularly defensible.
23
​
24
## Defensible tokenization
25
In a **defensible token model** you cannot remove the token or replace it with a different token and create a better user experience.
26
​
27
To help reason about the **defensibility** of different tokenization models, identifying a baseline that all defensible token models have in common is helpful:
28
​
29
- **A**: Fees are justified for **services provided**. The execution of arbitrary smart-contract code does not justify paying fees in excess of the gas used to validate/mine transactions.
30
- **B**: It is not defensible to force the usage of a token in such a way that the application would work **equally well or better using a different token**. (e.g. a stable coin, or ETH)
31
- **C**: Tokens which are uniquely **required** to incentivize or disincentivize behavior in order **to provide a service** accrue value relative to that services utility.
