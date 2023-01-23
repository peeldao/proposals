## Summary

Give juice-interface maintainers authority to delist projects on juicebox.money.

## Specification

Delisting a project means the following:
- not shown on homepage activity
- not shown in homepage trending projects
- not shown on /projects page
- Show "delisted" banner on their project page.
- Disable the `pay` button on their project page.

### Delisting procedure

1. Contributor creates a PR in `juice-interface` repository.
  - There is a new file called `blocklist.json`.
  - Contributor adds an entry to this file for project they want to delist. The entry will have (not limited to) the following data:
    - Date of delist.
    - 1-sentence reason why.
    - Link to any discussions (discord, twitter).
2. Someone merges this PR.

### Appeal procedure

If someone wants to appeal, they can get in contact with us however they want (Discord preferred). This is a temp-check process.

To formally propose a re-listing, create a proposal to Peel as per https://github.com/peeldao/proposals.

If this proposal passes (meets the given governance criteria at the time of creation), Peel commits to re-listing.

To re-list, reverse the steps of the **Delisting procedure**

## Action items

- [ ] Update `juice-interface` to support delisting as per specification.
- [ ] Document delisting and appeal process in that repo.
- [ ] Link to this repo from `juice-interface` README.
