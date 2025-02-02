---
type: Resource
bpmn: lifecycle.bpmn
---

# Codebase stewardship lifecycle

How we deliver codebase stewardship is based around the lifecycle of stewardship.

## Assessment

In order to decide on if and how we can perform incubating stewardship [we assess](../codebase-stewardship-assessment/index.md) the codebase and its community together with the community. If it is an [existing codebase](for-existing-projects.md) we look at the [stewardship feasibility](../codebase-stewardship-assessment/criteria-for-codebase-stewardship.md) first.

If codebase stewardship is feasible, or if it is a new codebase, we then do a [Standard for Public Code](https://standard.publiccode.net/) gap analysis.

At the end of assessment, the community:

* knows what work will be required to make the codebase compliant with the Standard
* can meaningfully decide whether to commit to becoming fully stewarded by the Foundation for Public Code

## Incubating stewardship

Codebases that are in incubation do not yet have the maturity of code and community that we require in the [Standard for Public Code](https://standard.publiccode.net/) and that might be required in the codebase governance.

During incubation, the community works to make the codebase fully Standard compliant (supported by the Foundation for Public Code).

Repositories of codebases in incubation will have clear indicators that the codebase and community are not yet mature, displayed in prominent places.

## Full stewardship

As an organization we deem this codebase, its ecosystem and its community to be mature according to the [Standard for Public Code](https://standard.publiccode.net/).

## Attic

Codebases that have been mature at one point but whose community has lost interest are moved to the attic.
In the attic codebases and communities are no longer stewarded.
The code will stay available.

Codebases can come out of the attic with renewed community interest.
Since the codebases might adhere to outdated standards it will need to go back into incubation before it can be returned to full stewardship.

## Tools

To track where in the lifecycle a codebase is, we use a project in Odoo.
The process for that is detailed in [codebases in Odoo](odoo-codebases.md).

## Public list

A public list of the codebases we work with, by lifecycle status, can be [viewed at our website](https://publiccode.net/codebases/).
