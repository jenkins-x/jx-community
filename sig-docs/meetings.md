# Jenkins X Docs SIG Meetings

## Quick links

- [Logistics](#logistics)
- Meeting Recordings: [Jenkins X Youtube Channel](https://www.youtube.com/channel/UCN2kblPjXKMcjjVYmwvquvg)
- [Agenda and Notes](#agenda-and-notes)
  - [2020-05-18 Meeting](#may-18-2020)
  - [2020-05-25 Meeting](#may-25-2020)
  - [2020-06-01 Meeting](#june-1-2020)
  - [2020-06-08 Meeting](#june-8-2020)
  - [2020-06-15 Meeting](#june-15-2020)
  
## Logistics

* Meeting notes on HackMD.io: https://hackmd.io/@jx-docs-sig/HJYAmMyjL
* When: We are still working out the optimal time for this SIG to meet. First Docs SIG meeting will be at 16:30 UTC Monday, 18 May.
* Zoom Link:  https://cloudbees.zoom.us/j/93384187996
* Meeting Recordings: [Jenkins X Youtube Channel](https://www.youtube.com/channel/UCN2kblPjXKMcjjVYmwvquvg)
* Jenkins X Public Calendar: [here](https://jenkins-x.io/community/calendar/)

## Agenda and Notes

Meeting agenda and notes are kept on [HackMD.io](https://hackmd.io/@jx-docs-sig/HJYAmMyjL) where everyone can add new topics to the agenda for upcoming meetings or take notes during the meetings. Please click edit button to edit the document.

### May 18, 2020

#### Participants
  - Ethan Jones
  - Kara de la Marck
  - John Ha
  - Oscar Medina
  
#### Agenda and Notes
  - Left nav structure PR aiming to ship by end of week
  - Day of docs for Distribution team next week, will work inside new structure
  - GSoD: Interested candidate, has contacted us through jenkins-x-dev slack. Would be great to invite him to collaborate on Lighthouse docs work that is getting started now. Introduce John Ha to him in Kubernetes slack. 
  - Admin: Are we OK with these being our meeting notes? Can we find a better time for this meeting? Or how should we handle keeping this SIG open and welcoming to individuals from China? Should we have an APAC time slot once a month? Issue has been discussed [here](https://github.com/jenkins-x/steering/issues/4) and [here](https://github.com/jenkins-x/jx-docs/issues/2675).
  - We should go through issues on docs repo and triage them. Label the issues, such as the audit work, issues with the docs site itself (404s, code snippets, etc), GSoD, etc
  - Search functionality on the docs site is off, and many search results are returning 404s, even when the material is in the docs. The search results are not linking or pathing to the correct place in the documentation.
  - Pop up on site is displaying  "Weekly updates from the Jenkins X community!" Do we send weekly updates to subscribers? Could we be more clear on what people are signing up for here? 
  - Also, we have chosen to put our main contributing information for code & docs in community section. I am OK with this, but wanted to make sure this was what we all thought was best.
  - There are pages that have fallen into Community section that are a bit out of place: Security, Apps Framework. They should be moved out to main documentation section.


#### Action Items
  - Re meeting times: Set up APAC a separate friendly meeting time and cadence
  - John Ha, Kara, Oscar: Triage and label issues
  - Ethan: Within Mailchimp itself fix the wording on popup on the site. Done!
  - John Ha to join dev slack channel and Kara to introduce to GSoD candidate.
  - Kara to move Apps Framework to main documentation.
  - Discuss search issue at next week's meeting.

### May 25, 2020
 - Docs SiG meeting on 25 May cancelled due to public holidays in both US and Europe. 

#### Action Items
 - Enjoy the long weekend everyone! ☀️
 
### June 1, 2020

#### Participants
  - Ethan Jones
  - Deane Smith
  - Kara de la Marck
  - Oscar Medina
  - Ankit Mohapatra
  - AJ
  - Jacqueline Binya
  - Nitin Agarwal

#### Agenda and Notes
  - Action Item Review, All
      - [APAC friendly meeting time issue](https://github.com/jenkins-x/jx-community/issues/3), to discuss and find resolution
      - [Apps Framework moved to main documentation](https://github.com/jenkins-x/jx-docs/pull/2800)
      - John Ha joined jenkins-x-dev slack and has been introduced to interested GSoD candidates 👍
  - Do we have access to Algolia account? 
  - Search functionality on the docs site is off, and many search results are returning 404s, even when the material is in the docs. The search results are not linking or pathing to the correct place in the documentation.
  - Are we ready for a "Day of docs" from the CB engineering team? What priorities should they work on? Decided we'd focus on JX boot but also let the engineers pick and choose what they want to work on. "Day of docs" is good to go 🚀
  - Discuss with GSoD applicants potential projects for them. Lighthouse is a good candidate and John can help.
  - Lots of discussion of cloud providers, what we support, how we show platform and k8s version support in the docs. General agreement that we need to show what works on what platforms, what verions, etc. Make it clear what platforms have great support vs limited support and what doesn't work on some platforms.
  - Creating a matrix of what features work on which platforms, could be an interesting GSoD proposal.
  - An additional proposal could be on writing user stories as specific articles such as 'Running Jenkins X as efficiently or inexpensively as possible', ie, how to run Jenkins X with the minimum resources. We should think of other articles we would like in that vein, and altogether could make an interesting GSoD project.
  - Consider how and when we address triaging the docs issues. We may want to dedicate a time during this SIG meeting when we address triage. Alternatively, or in addition, we could have a dedicated session to triage as we have a lot of issues to go through. Engineering may need to go through a number of issues and see which are out of date.
  

#### Action Items
  - Need to add docs PR to the PR template for the main JX repo (@Deane)
  - Ethan to set up hosting and Kara will update link on calendar.
  - Ethan and Deane to discuss cloude credits for docs contributors
  - Keep brainstorming with potential applicants different proposals. For example, we should think of  articles re using Jenkins X: with minimal resources, etc.

### June 8, 2020

#### Participants
  - Ethan Jones
  - Kara de la Marck
  - Oscar Medina
  - Ankit Mohapatra
  - John Ha
  - Nitin Agarwal
  - Deane Smith

#### Agenda and Notes
  - GSoD discussion -- support propospective applicants, feedback, etc
  - Deane: Capability Matrix, not supportability matrix ;) Will be worked on during Day of Docs (happening tomorrow): https://github.com/jenkins-x/jx-docs/issues/2824  
  - Matrix will be focused on big 3 cloud providers, mainly.
  - Definite interest on matrix for GSoD
  - Question from Ankit: Is this this still relevant? https://jenkins-x.io/blog/2019/04/03/terraform-jenkins-x/#step-1---create-terraform-plan Also should there be a dark mode? :)
      - Oscar says to unpublish this article, no longer relevant
      - Ankit to create issue to remove. 👍
  - Cloud credits coming soon for docs contributors, hopefully next week
  - Discussion on left-nav restructuring. Discussion focused on improvements under Creating Projects. 
      - Ankit noticed some mentions of Jenkinsfile: https://jenkins-x.io/docs/create-project/build-packs/#creating-new-build-packs 
  - Buildpacks has some out of date info
  - Would be nice to enable dark mode for the docs site. This should be created as an issue.

#### Action Items
  - Unpublish https://jenkins-x.io/blog/2019/04/03/terraform-jenkins-x/#step-1---create-terraform-plan (@Oscar)
  - Split quickstarts and imports into two articles, removing "creating" from quickstarts and move build parts to bottom of the left nav (@John). Also, make sure Creating Apps information is pathed to and thus can be navigated to on live site (currently it is not visible in nav structure).
  - Add message at the top of import and quickstart pages letting users know to visit the other page if they're new / existing (@John)
  - @Deane to get Kara information on Day of Docs. @Kara will add this to Jenkins X Calendar. Good to message this as well on social channels.


### June 15, 2020

#### Participants
  - Kara de la Marck
  - \<addme\>
  - 

#### Agenda and Notes
  - Discussions on an official Jenkins X Docs "Style Guide". Some kickoff issues:
    * One sentence per line
    * Weighting by x10
    * backticks `` vs italics *
    * code blocks use triple backticks + designator like ```sh
    * commands should NOT use prompts $ or >
    * No full HTML pages -- use Hugo well, shortcodes, partials, markdown, etc
  - Oscar: Discussion on Jenkins X structure: who decides, should the SIG be taking a directional role?
  - Kara: What is the goal/purpose of this board?
  - Oscar: Should the board take more control over what is merged in Jenkins X docs?
  - Kara: Should we do triage in this meeting? Spend 20 minutes each meeting? Are we willing to spend an hour on this meeting?
      - general response: not an hour. Need more efficiency and can maybe do 40 min meetings
      - Kara: Need more pre-meeting additions to this Hack.MD by all so we know the focus discussions for the meeting. Links to issues are good, so people can have context for the discussion and it can continue after the meeting(s) on the issues.
      - Kara: in addition, for future meetings, we can have 15-20 minutes reserved for triage.
  - Discussion of Docs navigation Issue raised by Viktor during Day of Docs.
  - Improvments in structure are all well and good, but we need to ensure the content is improving substantially.
  - \<addme\>

#### Action Items
  - John to draft (PR) an initial style guide.
  - Kara to add 15 min set time to the agenda for this meeting. And we will see how this process goes.
  - All of us: Think about Triage process and how we want to label the issues.
  