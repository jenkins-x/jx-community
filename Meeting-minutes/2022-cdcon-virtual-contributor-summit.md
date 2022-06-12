# Meeting notes from the first virtual contributor summit at cdcon 2022

## Participants

- Ankit
- Christoffer
- Mårten
- Terry
- Ted
- Brian
- Hays
- Kara
- Gerd
- Osama
- Rajat

## Intro words, summit overview

## State of Jenkins X

- CDF Incubating project
- Four (4) maintainers
  - Ankit Mohapatra
  - Christoffer Vig
  - Mårten Svantesson
  - Tom Hobson
- Two (2) students from [Google Summer of Code (GSoC)](https://summerofcode.withgoogle.com/)
  - Osama Magdy
  - Rajat Gupta
- Public adopters (and many more): https://jenkins-x.io/#users
- Infrastructure:
  - Google Compute Platform (GCP) for build/test

## Agenda

### New name for Jenkins X

Survey to suggest names, Second survey to select a name

### New logo for Jenkins X (after new name is approved)

Discuss with CDF on the specifics of the contest
Winner to get tshirts with new name

### Technical Oversight Committee (TOC)

Responsibilbities of the TOC:

- Coordinate with CDF TOC, and pick a representative to the CDF TOC
- Pick maintainers from regular contributors
- Handle costs and budgets - Do we need a finance team for this in the future?
- Elect chairman and referee for the TOC (use bot for random selection each time?)
- Set up LF open collective if someone wants to donate to Jenkins X maintainers
- Should have Maintainers + representatives from the end user community
- Biweekly meeting, anyone can join
  Start the process of becoming a graduated project (no ETA, but hopefully by end of the next year): toc/PROJECT_LIFECYCLE.md at master · cdfoundation/toc · GitHub

### Structure to Jenkins X office hours

- Public bug scrub for 10 minutes, if you cant be in the office, remember to update the office hours agenda with a github link and ur name.
- End users to vote on issues which gets prioritized in the project board
- Create a Public Roadmap with some timeline so end users know what to expect
  - During office hours, spend 10 mins updating the board.

### Release process

- Should we have LTS? It’s hard to maintain 2 variants of JX instead focus more on testing improvements? End users need stability!
- Better release notes. Look at tekton/terraform (or any other open source project) for inspiration! The problem is with auto bumps not creating good release notes!
  - How about manually pushing a tag, and creating better release notes? Atm end users are blindly updating Jenkins X
  - May be make pre-release automated, but make release manual (gives us chance to update release notes)

### Integrations with other CD Foundation projects/SIG

- Ankit - Supply chain security SIG
- Maintainers - CDF TOC meetings (rotation policy to better manage time)
- Other maintainers to pick one SIG of their choice

### Internal SIG updates.

- SIG UI
- Other Sigs to be formed once the community becomes bigger
  - Documentation
  - Testing (Plumbing)
  - Security

### Outreach

#### Current

##### GSoc

- New Jenkins X UI
- Supply chain security

#### Future

- LFX (if we are selected) https://lfx.linuxfoundation.org/
- OutReachy https://www.outreachy.org/

#### Process improvement

- TOC to maintain a list of ideas (with prospective mentors) which can be used for internships
- TOC to maintain a list of internship programs with their deadlines
- Template for each internship project (starting with GSoC)
- Maintainers to take turn in organizing the internship
- Project mentors to write a short blog on the challenges they faced when running the internship

### Future of Jenkins X

- Testing improvements
- UI
- Supply chain security
- Cloud and CD Events
- Improve gitops
  - Should we use a third party for Continuous Delivery or improve our existing codebase? Needs a Key enhancement proposal - (JXEP?)
- Multi-tenancy (install Jenkins X in existing cluster/multiple instances)
- Implement best practices

### Action items
