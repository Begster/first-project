# Changelog Template Guide - Rob

## Disclaimer

The target audience for this version of the Changelog Template Guide - and the accompanying Changelog Template - is the Open Source Software (OSS) domain. However, closed source or proprietary software environments can also use these documents, either as is or with modifications based on need.
The end users referred to in this document, and the accompanying template, may belong to one of the following OSS domain subgroups:

- OSS developers and team members of the OSS companies.
- OSS programmers / co-developers and team members of the OSS software user community.

NOTE: any other roles to include?

// QUESTION this is a question anchor
// TODO this is a todo anchor
// REVIEW This is a REVIEW anchor
// FIXME This is a FIXME anchor

QUESTIONS:
Paragraphs or lists?
Next steps?

## What is a changelog and what is its purpose?

A changelog is a reverse-chronological, comprehensive listing of all significant and noteworthy changes to a software or technology project's versioned release from the initial release to its current state.

Changelogs keep track of all technology-related changes to a software application. Created to help software developers and open source contributors track all significant codebase changes between releases. It lets the developers know what changed, when it changed, and whom, providing a context for past changes and decisions.

Changelog history can offer a view into the direction and progression of the software product, guiding the teams to strive and create code and use tools consistent with the company vision and goals and make corrections, if needed.

## What information do they contain?

Changelogs currently do not have a formal standard or format in the OSS domain. There are some “best practice” approaches. These recommend including the following in a changelog:

- Version number for the release
  - Semantic Versioning

- Date 
  - ISO format

- Types of changes
  - Added, changed, deprecated, removed, fixed, etc.

- Who made them and Why
  - Dev name, email

- Links to additional relevant details:
  - Specific issues, feature requests, Git tag, issue #, etc.

## What are the benefits and uses of Changelogs, (Why create them, and Who can benefit from them?)

- For issue resolution, developers can narrow the bug-fixing focus between two releases to identify the codebase change that may have caused the bug.
- Changelogs provide actionable metrics and insight into the software product through collecting bugs-to-feature ratios and can help in strategic planning.
- Helpful in the QA process by providing additional resources to explain changes to the application.
Tracking and eliminating conceptual inconsistencies. Ensuring alignment with project scope and vision.
- A clear and consistent record of application changes can help identify and correct conceptual inconsistencies in the codebase.
Tracks various changes: additions, deletions, new features or enhancements, deprecations, etc. Similar types of changes are grouped with links to additional documentation.
- Benefits OSS developers and the larger open source development community of what changed, when (date), why (context), and by whom (dev name/email).
- It can help re-learn and understand code logic and onboarding new developers to the project.
- Developers can track software changes, when made and by whom, understand which parts of the software team members are working on, and understand the overall software product progression and direction.
  - Without a well-maintained changelog, developers would have to look through various documents or different source code versions to understand what changed and why.
  - Developers can see software change history consistently in one place instead of wasting time digging source code, comments, commit messages, or other documentation.
- In the absence of a traditional help desk in the OSS domain, OSS co-developers/users depend on the changelogs and other technical documentation to find answers to their issues or ask for help.
- Changelogs mention individual developers by name, thus acknowledging their contributions to the project and increasing project buy-in and commitment.
- Changelogs can keep product users in the loop, engaged, and excited about software updates and new functionality that can increase customer loyalty and product use.
- Product power-users who are some of the avid fans of changelogs and read them keenly can influence product choices based on their experience with the product and the evolution of the product.
- It has the potential to attract future customers and employees through social media and other industry-specific organizations and conferences.
- Up to date project documentation, including Changelogs, can increase the adoption of new development standards and tools and build developer loyalty through empowerment and a sense of ownership of the end product.

## Changelogs vs. Release Notes

- Changelogs and release notes are considered to change documentation in a software application environment.
- Release notes content is:
  - In a customer-centric language - plain, succinct, and jargon-free.
  - They are used by companies to specifically communicate new application changes to their consumers and application users.
  - It can be internal or external focused.
- Changelog content is:
  - In a developer-centric technical language.
  - Informs software developers of specific and time-based changes to the codebase over time.
  - It can be internal or external focused.

## What are the guiding principles for creating Changelogs?

- Humans read changelogs, so they need to be in a human-readable text.
- It should communicate the impact of the changes, such as bug fixes, new/updated features, deprecation, removals, security updates, etc.
- Sort contents by importance; more critical changes on top followed by less important ones.
- Do not include less critical changes, such as code refactoring, efficiency changes, etc.
- Link each change to further information - git commits, issue number/tracker, etc.
- Changelog updating and publishing cadence should coincide with each new software release.
- Create an “Unreleased” section at the top of the changelog file to track current release work and change the unreleased tag with the next release date and version.
- Good practice to review the changelog file for accuracy and completeness before publishing.

## What are the consequences of not using Changelogs?

TODO: is this section needed?

Not documenting significant software changes and associated details in a  consistent format and delivery cadence could have negative impacts on the project and may lead to:

- Product growth issues - short- and long-term.
  - Co-developers and users not maximally engaged.
- Project success issues - short- and long-term.
  - Co-developers not engaging.
  - Users not engaging.
- Codebase inconsistency.
  - Hard to understand what changed, when, and why leading to miscommunication and misunderstandings.
- Product design issues.
  - Code inconsistencies.
- Lower customer engagement and loyalty.
  - Customer not engaging because of unavailability of up to date docs.
- Lower communication with dev and co-devs.
  - Team miscommunication.

## Why (or when) not to use a changelog?

TODO: I'm not sure if this section is needed. Seems I'm comparing changelogs and release notes, whereas in the OSS domain, I think (and I could be wrong) most folks refer to changelogs and release notes interchangeably…

A changelog may not be the best tool for end user communication in a traditional a recommended document to share with traditional software application end users for the below reasons:

- Changelog language and details are technical by definition and thus may not be quite as beneficial as release notes for non-technical application end users.
- It may be difficult for non-technical end users, should they be expected to understand and implement application-level changes or incorporate new changes into their workflow, and may discourage user engagement with the software.

## Who writes (or creates) Changelogs?

TODO: finalize below verbiage.

- Changelogs are generally created and maintained by the software developers as they have the most current knowledge of what changed (functions, methods, etc.) why it changed (CR, TR, RFC, etc.), and when it changed (date, release number, etc.) and who made the change (name, email).
- It can also be written by other technical team members, such as architects, project managers, software designers, tech writers/documentation team, etc.

## Who benefits from a changelog and what are the benefits?

NOTE: See “What are the benefits and uses of Changelogs, Why create them, and Who can benefit from them” in above sections.

## Who uses changelogs and how is it used?

NOTE: See “What are the benefits and uses of Changelogs, Why create them, and Who can benefit from them” in above sections.

## Who/What: Negative impacts of not maintaining well-formatted and up to date changelogs?

TODO: do we need this section?

- End users (OSS devs and co-devs) not aware of deprecations, removals, and security updates.
- End users in the dark about bug fixes, new features, and other updates.
- Risks of mistakes and misunderstandings.
- Productivity and collaboration issues and confusion among project team and OSS development community
Loss of credibility for the company.
- Versioning conflicts .
- Security issues.
- Compliance issues.
- Customer & shareholder relationships are negatively impacted.

## Where will users find the changelog?

- Blog posts; as Markdown (.md) files in a github repo; changelog section of a software or its website; on “what’s new” in android and apple apps stores.

## File names

- Changelog Names: Changelog, CHANGELOG.md, CHANGES.md, HISTORY.txt, NEWS.txt, etc.

## Format

No standard or formal format as of the writing of this doc.Some good advice on:

- What a format should be?
  - For version #, use Semantic Versioning.
  - For date, use ISO date format.
  - Include name and email of the dev.
  - Include reason for change.
  - Use links for additional info related to a change, such as git commit, issue #, etc.
- What should be included?
  - Types of changes: bug fixes, additions, new features, deprecations, removals, security changes.
- What types of tags to use?
  - Added, Changed, Deprecated, Security, etc.
  - Combine similar changes under one tag.

## When is a changelog created?

- Changelog is a historical file and is recommended to be continuously updated during software development up until the code is ready to be deployed in a new release.

## When will the changelog be available to the end users?

- Changelog cadence should coincide with each new software release.
