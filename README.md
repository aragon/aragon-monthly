# [Aragon Monthly](https://monthly.aragon.one/)

Aragon Monthly is **a community curated monthly digital newspaper about Decentralized Autonomous Organizations** and the Aragon ecosystem.

## How does it work?

- Community members and Editors create [Issues](https://github.com/aragon/aragon-monthly/issues) for News, Articles and Classifieds
- Issues that get "upvoted" by the community get added a [bounty label](https://github.com/aragon/aragon-monthly/labels/bounty) and that bounty will be funded to incentivise fulfillment of that piece
- Anyone can contribute to creating the requested piece on Issues
  - By creating a new Pull Request that `Closes issue #x` anyone is free to claim the bounty on that Issue
  - Editors are members who are frequent high quality contributors and have priority over other contributors, they can assign themselves to Issues to signal their intent to fulfill that Issue
- At the end of the month the [Editor-in-chief](#contributors) makes sure that all completed [Pull Requests](https://github.com/aragon/aragon-monthly/pulls) are merged, compiles the Front Page and ensures that everything is working fine, publishes the Monthly to https://monthly.aragon.one/ and sends out the Aragon Monthly Newsletter

## How can I contribute?

If you have a topic that you would like to either read or write about, create a [New Issue](https://github.com/aragon/aragon-monthly/issues/new) with a descriptive Title and a clear description of the type of content you would want to see in Aragon Monthly following the [Issue Creation Guide](coming_soon)

Or if you feel like writing on a topic that someone else has requested to read about in [Issues](https://github.com/aragon/aragon-monthly/issues), create the content, [submit a Pull Request](https://github.com/aragon/aragon-monthly/pulls) to close the Issue and wait for it to be reviewed and merged!

## How do i run a local version of the page for editing?

- Install [MkDocs](http://www.mkdocs.org/)
  - Install mkdocs-material using Python, `pip install mkdocs-material`
- In the `aragon-monthly` directory, run `mkdocs serve`
- Open [http://localhost:8000/](http://localhost:8000/) in your browser

## Contributors
> Editor-in-chief is the publication's editorial leader who has final responsibility for its operations and policies.

- Editor-in-chief - [@Smokyish](https://github.com/Smokyish)

> Editors are people that regularly provide content to the publication and make sure that the content is always high quality. They write articles, review Pull Requests and are generally active in the creation of this publication.

- Editor - [@john-light](https://github.com/john-light)

> Reviewers are people who contribute by helping review new content submitted via Pull Requests

- Reviewer: [@lkngtn](https://github.com/lkngtn)
- Reviewer: [@izqui](https://github.com/izqui)

- Editor - _Get your name here by contributing!_

## Future goals

- Make Aragon Monthly so successful that there's a demand for Aragon Weekly
- Turn Aragon Monthly into a DAO that fully governs the project
