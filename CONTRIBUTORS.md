# Outline

1. Overview
2. Developing a Contribution
3. Pre-screening a Contribution
4. Submitting a Contribution
5. Acceptance Criteria
6. From Contribution to Commit
7. Rationale

# Overview

The life-cycle of a contribution is as follows:

1. Contributor improves or expands the code-base and wants to contribute the change to the community project.
2. Contributor pre-screens the contribution against the Acceptance Criteria.
3. Contributor submits the contribution to the Community for review.
4. The Community reviews the contribution against Acceptance Criteria.
5. The Contributor works with the Community to update the contribution until it meets all criteria.
6. The Committers sign-off on the contribution and merge it into the code-base.

Note: The term 'Community' is intentionally used to highlight that Contributors, Committers, PMC, or anyone else, can be a part of the process. 

# Developing a Contribution

If you are a complete beginner to Apache NuttX, please refer to our Getting Started Guide [Add link]. This will help you get up and running with the stock project.

If you are interested in contributing to the project, but are unsure how to help, please check out our Issues [Add link] page, or reach out on the mailing list (dev@nuttx.apache.org).

If you have your own work that has led to a bug-fix, improvement, or feature, and you would like to submit it to the community, please follow the rest of this guide to get your Contribution integrated into the project

# Pre-screening a Contribution

Before a contribution is accepted it must pass all Acceptance Criteria. We urge Contributors to make best effort into bringing their contributions into compliance. This helps the community grow in the Apache Way. But the Community is here to help! Reach out on the dev list and someone will assist!

[PUT LIST OF PRE-SCREENING STEPS HERE THAT HELP THE CONTRIBUTOR CHECK FOR COMPLIANCE WITH THE ACCEPTANCE CRITERIA. For example, nxstyle checks]


# Submitting a Contribution

## Methods of Initial Contribution

Contributions can be submitted in the following ways:

1. A patch file sent to the mailing list
2. A Pull Request on Github

### Patch Files

**How to Create a Patch File**

**How to Submit a Patch File**

**From Patch File to PR**

### Pull Requests

**How to create a Pull Request**

# Acceptance Criteria

1. Does the contribution violate any of the Inviolables? [Add link]
2. Does the contribution follow the Coding Standard? [Add link]
3. Does the contribution follow the Licencing Requirements [Add link]?
3. Does the contribution follow Good Architectural Principles? [Add link]
4. Does the contribution build and pass testing?
5. Does the contribution meet all Area Specific Criteria? [Add link] 

# From Contribution to Commit

1. Triage
2. Review
3. Revise
4. Merge

## Triage

When a contribution is first submitted to the project, it must go through triage. Triage allows for a contribution to be "tagged" in ways that help direct the contribution through the rest of the process.

First, the contribution should be tagged as a particular type:

- Bug Fix
- Typo/Trivial
- Improvement
- New feature or driver

Next, the contribution should be tagged based on the area(s) modified:

- Core OS
- Build System
- Networking
- Wireless
- Boards
- Arch
- Drivers

Lastly, contributions need to be assigned to certain Committers for review. The assignment should be based on the type of change and the affected area. Please see our Subject Matter Experts page [ADD LINK] to identify the correct reviewers. See below for details about how many reviewers are required for different types of contributions. 

## Review

Once the contribution has been triaged, the Reviewers and anyone else in the community must check the contribution against the Acceptance Criteria. 

## Revise

If the Reviewers or anyone else in the community, determines that the contribution is not in compliance with the Acceptance Criteria, then the contribution must be updated. While Committers and other community members may help get the contribution into compliance with the Acceptance Criteria, it is up to the Contributor to make adjustments to the contribution if they wish to have the contribution committed.

The Contibutor can either re-submit a new patch file, or work through the PR mechanism to update the contribution. 

## Merge

# Rationale
