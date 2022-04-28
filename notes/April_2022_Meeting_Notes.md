# April 28, 2022

- Welcome to the 1st Hiro Monthly Developer Meeting!

- Big thanks to the April 2022 community contributors. Many of the contributors actively engage on the various Hiro product backlogs, and we appreciate all the interest, time, and effort.

- Joe presented the "smart contract of the month" segment with an NFT-focused theme, which involved him digging into the smart contracts, mainly what would entail building and promoting an NFT project using Clarity smart contracts. A lot of great related developer resources and online literature were included in the slides, which you can find [here](https://github.com/hirosystems/community-meeting/blob/main/slides/04.28.2022%20-%20Hiro%20Developer%20Community%20Meeting.pdf).

- [Q1 2022 Product Releases](https://www.hiro.so/blog/hiros-focus-for-q2-2022#accomplishments-in-q1): lot's of incremental updates to API, Stacks.js, Clarinet, Blockchain, Wallet and Exlporer.

- A brief look into [Q2 2022 Product Focus](https://www.hiro.so/blog/hiros-focus-for-q2-2022#what-we%E2%80%99re-focused-on-in-q2).

- Product backlogs, roadmap, and timelines:
  - [Stacks Blockchain API](https://github.com/hirosystems/stacks-blockchain-api/milestone/31)
  - [Stacks.js](https://github.com/hirosystems/stacks.js/milestone/57)
  - [Clarinet](https://github.com/hirosystems/clarinet/milestone/1)
  - [Hyperchains](https://github.com/hirosystems/stacks-hyperchains/milestones)
  - [Web-wallet](https://github.com/hirosystems/stacks-wallet-web/milestone/43)
  - [Explorer](https://github.com/hirosystems/explorer/milestone/31)

- Questions
  1. John: Explorer is not entirely supported in Clarinet.
  
        - This has been addressed as of last week; please try it out and let us know what you find out.

  2. Merrick: Arbitrary message signing: What is it? Can this help with authentication that is outside of Stacks.js-based application? A desktop app or a game, even for that matter.

        - More details at [stacks-wallet-web/pull/2350](https://github.com/hirosystems/stacks-wallet-web/pull/2350) (related [stacks-wallet-web/issues/2387](https://github.com/hirosystems/stacks-wallet-web/issues/2387))
  
  3. Merrick: Arbitrary message signing: Can this help with native authentication and help also propagate that authentication to other apps/services? Is it avaialble? 

        - This would be a great topic to discuss live on the next monthly call—the best practices, the design patterns, and how to solve these for different use-cases.
