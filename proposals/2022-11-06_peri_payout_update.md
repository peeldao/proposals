# Peri payout proposal
Proposal to update Peri's responsibilities and payout.

## Updated responsibilities
- Maintain Juicebox subgraph & JBM integration (current)
- Implement & maintain Sepana database & JBM integration
- Dev and creative support for UI work related to the goals listed below

## Goals
### Priority
- Subgraph development & maintenance
- Sepana-powered search
- Project discovery updates using Sepana database, such as:
	- "related projects"
	- project tags
   - etc.
### Secondary
- Better project/terminal versioning UX in JBM
- Assist in development of other features as needed

## New payout amount
US$6,250/fc

## Rationale
I've continued development and maintenance of the juicebox subgraph, including:
- Handling migrations without incident (aside from graph infrastructure issues)
- Keeping our API key funded
- Making sweeping improvements to the subgraph repo to minimize errors and facilitate external access to the codebase
- Upgrading CV pattern to PV pattern
- Feature upgrades:
	- Trending project stats
	- NFTRewards + DeFifa
	- USD equivalents for ETH volume amounts and Pay/Tap/Distribute event ETH amounts, using JB Prices contracts
	- New events and properties like AddToBalanceEvents, Project.deployer, and FC Configure/Init events (using research by filipv)
- Handling all UI updates required for subgraph compatibility, including project activity and CV -> PV
- Making URLs available to Peel team and others as needed, including via the subgraph docs + resources channel

I've gotten familiar with the Sepana / elastic search architecture, and prototyped a JBM integration to depend on Sepana for project search instead of the subgraph. I've also helped drive discussion on how else we can make use of a database, including features like user bookmarks and project tags.

I've been involved in tasks falling outside my current responsibilities:
- Adding persistent transaction history/progress to UI https://github.com/jbx-protocol/juice-interface/pull/1816
- Sweeping refactor of project activity UI elements (continued work started by wraeth) [FC Project events by peripheralist · Pull Request #2586 · jbx-protocol/juice-interface · GitHub](https://github.com/jbx-protocol/juice-interface/pull/2586)
- Improved UX for when wallet is connected to wrong network
- Hotkey quick project search UI [Don't force network-switching modal when wrong network is connected by peripheralist · Pull Request #1675 · jbx-protocol/juice-interface · GitHub](https://github.com/jbx-protocol/juice-interface/pull/1675)
- Small upgrade to UI error notifications [Error notification improvements + cleanup by peripheralist · Pull Request #2683 · jbx-protocol/juice-interface · GitHub](https://github.com/jbx-protocol/juice-interface/pull/2683)
- Peel governance + censorship discussions (ongoing)
- Quick response and continued damage control after unexpected Infura billing issues (noting this, but I imagine anyone else here would have handled it as well if they were online at the right time)
