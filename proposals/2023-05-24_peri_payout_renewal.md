## Synopsis

Renew payout to peri.eth

## Specification

- Continue US$6,250 payout for the next 12 funding cycles.

## Rationale

Since his last renewal, Peri has contributed to various areas:

### Subgraph
Peri has independently maintained the Juicebox Subgraph, creating changes necessary for feature improvements and compatibility with new protocol functionality, managing publication of new versions, as well as handling relevant UI changes.
- Created new Wallet entity pattern to enable Account page functionality
- Overhaul of ProjectEvent architecture to enable reliably filtering activity for specific wallets
- Support for JB721Delegate V2
- JB contracts v3.1 compatibility
- Sweeping improvements to organization of the codebase
- Addition of decoded fundingn cycle data in reconfigure events (with significant help from @filipviz)
- Various prompt bug fixes

### Database projects
Peri lead the addition of the projects table to the database, including designing the cron job update routine, allowing for projects to search by information included in a project's metadata.

### Project tags
Taking advantage of the database projects, Peri designed and implemented the project tags architecture and UI, creating more opportunity for project discovery on JBM.

### UI
Peri has also made various contributions to enhancing the JBM UI, including:
- V2 Pay modal overhaul, using design contributions from @tjl
- Adding wallet activity to the Account page
- Updating the ENS Resolver pattern to use the default resolver contract for a given ENS node, instead of the standard DefaultResolver contract
- In-app announcements feature
- Various style improvements for mobile, especially the ProjectCard layout

## Upcoming responsibilities

For the next 12 cycles, Peri's responsibilities will include:
- Design/dev support for new project page. Primary goal will be the stats page, especially including a new database cacheing architecture to make over-time graphs (like the current volume graph) much more performant.
- Continued Subgraph maintenance and development as needed
- Continued responsibility over the database projects architecture, and any future improvements
- Support for growth related efforts, especially working with Tim (@tjl) to research opportunities to drive JBM closer to product market fit
