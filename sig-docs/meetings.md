# Jenkins X Docs SIG Meetings

## Logistics

* Meeting notes on HackMD.io: https://hackmd.io/@jx-docs-sig/HJYAmMyjL
* When: 15:30 UTC Mondays.
* Meeting Link: https://meet.google.com/uyd-estx-ffz
* Jenkins X Public Calendar: [here](https://jenkins-x.io/community/calendar/)

## Quick links

- [Agenda and Notes](#agenda-and-notes)
  - [2020-10-19 Meeting](#october-19-2020)
  - [2020-10-12 Meeting](#october-12-2020)
  - [2020-10-05 Meeting](#october-05-2020)
  - [2020-09-28 Meeting](#september-28-2020)
  - [2020-09-21 Meeting](#september-21-2020)
  - [2020-09-14 Meeting](#september-14-2020)
  - [2020-09-07 Meeting](#september-7-2020)
  - [2020-08-24 Meeting](#august-24-2020)
  - [2020-08-17 Meeting](#august-17-2020)
  - [2020-08-10 Meeting](#august-10-2020)
  - [2020-08-03 Meeting](#august-3-2020)
  - [2020-07-27 Meeting](#july-27-2020)
  - [2020-07-20 Meeting](#july-20-2020)
  - [2020-07-13 Meeting](#july-13-2020)
  - [2020-07-06 Meeting](#july-6-2020)
  - [2020-06-29 Meeting](#june-29-2020)
  - [2020-06-22 Meeting](#june-22-2020)
  - [2020-06-15 Meeting](#june-15-2020)
  - [2020-06-08 Meeting](#june-8-2020)
  - [2020-06-01 Meeting](#june-1-2020)
  - [2020-05-25 Meeting](#may-25-2020)
  - [2020-05-18 Meeting](#may-18-2020)
 
  
## Agenda and Notes

Meeting agenda and notes are kept on [HackMD.io](https://hackmd.io/@jx-docs-sig/HJYAmMyjL) where everyone can add new topics to the agenda for upcoming meetings or take notes during the meetings. Please click edit button to edit the document.

### October 19, 2020
#### Participants
 - Kara de la Marck
 - Nitin
 - James Strachan
 - James Rawlings
 - Ankit
 - \<addme\>

#### Agenda and Notes
 - Go over action items.
     - Kara: followed up with CDF, last week and today. Same answer: in principle yes, but don't have the resources yet. 
     - Nitin updates:
         - questions on which guides to focus on .
         - suggestion to improve subheadings, and heading on docs
    - JR: Go over website with fresh eyes
    - [Outline of v3 docs](https://docs.google.com/document/d/1d07vrnCare-ZcHBT3TSSrIr9WgZXTfA5d_vtWl1M-HE/edit).
    - 
#### Action Items
 - All: go over and add to [Outline of v3 docs](https://docs.google.com/document/d/1d07vrnCare-ZcHBT3TSSrIr9WgZXTfA5d_vtWl1M-HE/edit).
 - Ankit: create spike of branch for docs for v3
 - Kara: hmm, now opportunity to propose request for AWS resources to CDF ToC. This is a process, so we shouldn't expect the resources to be available from the CDF soon (if ever).


### October 12, 2020
#### Participants
 - Kara de la Marck
 - Nitin
 - James Strachan
 - James Rawlings
 - Ankit
 - \<addme\>

#### Agenda and Notes
 - Go over action items.
     - Kara hacktoberfest is a jx org wide label, but doesn't always show as available on all repos  ¯\_(ツ)_/¯ 
     - Consequently, have added the label to a number of jx repos
     - Have asked again at CDF for AWS resources for Nitin.
     - Issue about magnifying images: https://github.com/jenkins-x/jx-docs/issues/3089
     - Nitin: will have a look and see how this is done. Might implement.
     - Thoughts abt this: https://github.com/jenkins-x/jx-docs/issues/2935 (Not a bad thing to add imo)
         - JR: Might be useful on v 3 further along. Want to be feature complete with v3 and then more testing and then extend the guides, etc.
  - Ankit is Chair of Docs SIG  🎉
      - Apologies that I haven't done this yet: https://github.com/jenkins-x/jx-community/pull/14
 - Nitin: Updates. 
     - Second Matrix for future platforms is up
     - JX cluster on GKE is accomplished. Followed readme for Readme Terraform/GKE -- all correct
     - Will put PR for GCloud credentials
     - Next steps?
     - BDD tests? 
     - JR: Really great if we had more guides on creating quickstarts, how to get logs, do a promotion, etc.
         - Keeping it simple to start, and then build a library of guides
         - Nitin: OK, will build 
  - Let's respond to this: https://github.com/jenkins-x/jx-docs/pull/3083
      - Ankit has replied, encouraging focus on v 3
      - JR: we are going to be revamping v3 site. Given this until it settles down, maybe 
 - Nitin: questions on issues to work on:
     - https://github.com/jenkins-x/jx/issues/6659
    - Ankit: this is a good issue to address
    - https://github.com/jenkins-x/jx/issues/6565
    - Ankit: related - what about JFrog Artifactory support?
        - JR: the way v 3 is architected, plugins and how to use them for this would needs to be documented.
            - Ankit: I can pick that up, especially for JFrog, can write the guide.
    - https://github.com/jenkins-x/jx/issues/6563
        - JR: valid, once v3 working, we can start going through these issues.
        - JR: next week, would be great to do design session for v3 docs. So not just about untangling from v2 docs
        - Next docs sig meeting is design session.
    - https://github.com/jenkins-x/jx/issues/6565
        - Ankit, JR: very v 2 focused. Leave to the side for now.
        - Nitin: can we close issue?
        - JR: can soon start responding that we will be working on v3 docs over coming weeks.
        - This can start being announced over the next few weeks (not yet)
        - JR: when approaching beta for v3, can close saying addressed by v3, will be this asap when v3 beta
    - Nitin: conclusion that I don't need to focus on these issues. We wait until v3 to reply that should be solved by v3, for now leave to side.
    - JR: by end of week should have docs and even blog on kuberhealthy.
    - JS: tomorrow will be writing some docs. Loads of additions due to bug fixes.

#### Action Items
 - Ankit: Will pick up: https://github.com/jenkins-x/jx/issues/6547
 - Ankit: guide for supporting/using JFrog Artifactory
 - Kara: push on getting AWS resources for Nitin
 - JR: docs and blog on kuberhealthy
 - JS: docs additions
 - Ankit: might help more with the hacktoberfest volunteers, give help as needed.
 - \<addme\>


### October 5, 2020
#### Participants
 - Kara de la Marck
 - Nitin
 - James Strachan
 - James Rawlings
 - Ankit
 - \<addme\>

#### Agenda and Notes
 - Ankit: https://github.com/jenkins-x/jx-docs/pull/3085
 - Ankit: https://github.com/jenkins-x/jx-docs/pull/3083
 - JS: Working on docs for Tekton catalogue++ -- will also demo at Office Hours tomorrow
 - James R: We should have a few days in a week or two to create sreamlined docs version for JX 3.
 - Nitin: Matrix update, almost done
 - Nitin: have been spending time learning Terraform and going over JX 3 docs
 - Going over hacktoberfest PRs:
     - https://github.com/jenkins-x/jx-docs/pull/3083
 - JR: Let's move the plugin repos to the new org after infrastructure update next week. 
 - JS: Could do it before, as well. 
 - JS, TODO: Could create a plugin project, creating the basis, and then list issues to finish it off for hackatoberfest
    - Getting people to test the go-scm code on different scm providers, etc
    - Will provide about three meaty things for hacktoberfest people to work on.
- Kara to follow up again with Tracy re CDF support for an AWS cluster for Nitin
- JR: Would be great for JX project to also have some resources on AWS, as well.
- Kara: We should have a note in the docs, protecting beginners (and forgetful folks) to remember to tear down your clusters!

#### Action Items

- Kara: org wide hacktoberfest issues would be good. Make sure hacktoberfest issue on all good first issues.
- Kara to follow up again with Tracy re CDF support for an AWS cluster for Nitin
- JS: Could create a plugin project, creating the basis, and then list issues to finish it off for hackatoberfest
    - Getting people to test the go-scm code on different scm providers, etc
    - Will provide about three meaty things for hacktoberfest people to work on.
    
### September 28, 2020

#### Participants
  - Kara de la Marck
  - Nitin
  - James Strachan
  - James Rawlings
  - Ankit
  - \<addme\>

#### Agenda and Notes
- Go over action items from last week.
    - jx org wide labels: https://github.com/organizations/jenkins-x/settings/repository-defaults
    - Kara: contacted Tracy re cloud resources support and eventually hosting all JX resources. Yes, this is possible, Tracy is on it, knows that we are interested in AWS resources as a first step.
- Nitin: https://github.com/jenkins-x/jx-docs/pull/3079
- Nitin question on Open Shift:
    - JS: Let's leave Open Shift 3 on the matrix. Just mention 4
    - JR: Might be worth pointing out we won't ever support 3
- Nitin question on clouds mentioned, should we mention Alibaba, IBM Cloud, etc?
    - JR: Similar treatment to OS 3. Just want to be clear what isn't working. If people want to contribute they can do.
    - JS: PKS (VM Ware Kubernetes), not supporting yet, but should be high up the list.
    - JR: Digital Ocean
    - JS: Yes, we could do a hacktoberfest shoutout for Digital Ocean support
    - JR: More docs on contributing needed (and coming this week), to make it easier for people to contribute to the features/support they want to see.
    - JS: Would be great to encourage vendours to contribute, by having them on the matrix, but not yet supported.
- Nitin: question on Red, Orange, Green definitions:
    - JR: We are not mapping Red, Orange, Green to Alpha, Beta, GA. These traffic light colours are for Alpha.
    - JS: Might need two types of symbols.
    - JR: Do we need a capability matrix for Apha, Beta, GA.
    - JS: Depends on the matrix we are doing. For now, everything is alpha, because the entire matrix is for JX 3 Alpha.
    - JS: Lets keep it simple. For the matrix, everything is in the category of Alpha (then all Beta, etc). The traffic light system is to show a delta.
    - How to handle areas (ie, clouds, etc) that we have no intention of support at this stage, but would like to do so in the future?
    - JR: Leave blank?
    - K: use astrix, with key with info
    - JS: And can have call to action, ie, call to contribution. So, if want to see this sooner, can contribute...
    - Nitin: need to have difference between colours, astrix, etc
    - Could have a colour for future items? JS: Purple or grey.
- Nitin: will create a speadsheet with what we have discussed. Then will need help going over to ensure correct.
- All: Sounds great!
- JS: Would be nice to use matrix to build a roadmap
- JS: We could also use a project board
- Kara: Should we do triage session
- JS: I've got [a magic query](https://github.com/issues?q=is%3Aopen+is%3Aissue+repo%3Ajenkins-x%2Fjx-cli+repo%3Ajenkins-x%2Fjx-admin+repo%3Ajenkins-x%2Fjx-application+repo%3Ajenkins-x%2Fjx-apps+repo%3Ajenkins-x%2Fjx-helpers+repo%3Ajenkins-x%2Fjx-git-operator+repo%3Ajenkins-x%2Fjx-gitops+repo%3Ajenkins-x%2Fjx-pipeline+repo%3Ajenkins-x%2Fjx-project+repo%3Ajenkins-x%2Fjx-promote+repo%3Ajenkins-x%2Fjx-secret+repo%3Ajenkins-x%2Fjx-verify+repo%3Ajenkins-x%2F%2Fjx-secret+repo%3Ajenkins-x%2Foctant-jx+) to find the issues on all the projects that are plugins.
- JR: would be great to have the plugins org set up
- JS: Could create a project, creating the basis, and then list issues to finish it off for hackatoberfest
    - Getting people to test the go-scm code on different scm providers, etc

#### Action Items

- JS: Could create a plugin project, creating the basis, and then list issues to finish it off for hackatoberfest
    - Getting people to test the go-scm code on different scm providers, etc
    - Will provide about three meaty things for hacktoberfest people to work on.
- Kara: org wide hacktoberfest issues would be good. Make sure hacktoberfest issue on all good first issues.

### September 21, 2020

#### Participants
  - Kara de la Marck
  - Nitin
  - James Strachan
  - James Rawlings
  - Ankit

#### Agenda and Notes

 - Nitin has been reading over the docs for JX 3
 - Recap of Nitin's work this week:
    * [Submitted PR](https://github.com/jenkins-x/jx-docs/pull/3057) for having the copy button on Code snippet blocks in Jenkins X docs web pages. 
    * (Ongoing): Working on validating the docs and technical steps for running JX v3 on GKE. [Issue](https://github.com/jenkins-x/jx-docs/issues/3062)
    * (Ongoing): Designing the Maturity model / matrix on JX v3 for GKE platform. [Issue](https://github.com/jenkins-x/jx-docs/issues/3069)  
    * Also, Nitin has assigned the [Issue](https://github.com/jenkins-x/jx-docs/issues/3044) to himself and closed [Issue](https://github.com/jenkins-x/jx-docs/issues/2953) and [Issue](https://github.com/jenkins-x/jx-docs/issues/2924).
 - Nitin would like to have AWS resources.
     - JR: might be able to ask CDF
     - Kara: might be able to get AWS resources from Jenkins project
     - JR: CDF might be hosting all JX resources soon (fingers crossed)
     - JS: Starting with a small AWS account with the CDF might be a good first step to shifting resource hosting to the CDF
     - Kara: Actions items for this?
     - JR: Would be good to find out what the CDF can do for Jenkins X project. Do we qualify for any help with resources.
     - Kara: Should I ask Tracy? 
     - JR: Yes, to start the conversation.
     - JR: We are at the point to enable BDD testing with AWS and EKS
- JR: Good that Nitin is rocking along.
- Nitin: Was looking at maturity models and matrix. Seeing what other communities are doing.
- JR: might be good to do a traffic light: red, yellow, green
- Ankit demo on Mermaid.js
    - PR up: https://github.com/jenkins-x/jx-docs/pull/3071
    - Mermaid.js seems to be a well maintained, and well starred, project - which is good.
    - JR: Great to have this. The diagrams are good for explaining and communicating. These, plus whimsical, are great.
    - Ankit: I've showed the simpler things one can do with Mermaid.js, but there are more complex diagrams, etc.
    - Ankit, JR: might be good for the maturity model
    - Nitin: Can explore
    - JR: Would be good to have something simple up for the maturity model, then can play with the different diagraming tools and see what works best.
    - Ankit: Created issue listing possible tool choices: https://github.com/jenkins-x/jx-docs/issues/3040#issuecomment-696092463
    - JR: Key thing is to communicate with end users
    - Ankit: Mermaid.js has a playground: https://mermaid-js.github.io/mermaid-live-editor/#/edit/eyJjb2RlIjoiZ3JhcGggVERcbiAgQVtDaHJpc3RtYXNdIC0tPnxHZXQgbW9uZXl8IEIoR28gc2hvcHBpbmcpXG4gIEIgLS0-IEN7TGV0IG1lIHRoaW5rfVxuICBDIC0tPnxPbmV8IERbTGFwdG9wXVxuICBDIC0tPnxUd298IEVbaVBob25lXVxuICBDIC0tPnxUaHJlZXwgRltmYTpmYS1jYXIgQ2FyXVxuXHRcdCIsIm1lcm1haWQiOnsidGhlbWUiOiJkZWZhdWx0In19
    - Ankit: Plus Mermaid.js is completely open source.
- Kara: Hacktoberfest? If going to engage just need to add the Hacktoberfest label to good first issues.
    - JR: Great. Lets try and focus people on JX 3 for Hacktoberfest.
    - Kara: Yay! How will we triage the issues?
    - JR: TLS/DNS forward movement is important, but Kuberhealthly work might be a good place to enable new contributors.
    - JS: Lets focus the new contributors in areas, new stuff, maybe a new git organisation for JX plugins. Moving all CLI plugins there.
    - JS: Move people away from the traditional JX repository. The old one is too messy.
    - JS: If we want new people to contribute to JX, should point them to the plugins.
    - JR: We could create a new org. GH stars, though. 
    - Discussion on changing jx repo over to JX 3
    - JS: Lots of crusty issues on JX 2, which are outdated, won't be fixed, don't even want people putting their engery into them.
    - JS: If looking at JX repo, new contributors would have no idea where the source code is.
        - If focus people on plugins, smaller codebase, more focused, easier to wrap head around and start contributing.
    - JS: For closing old issues, would love to be able to say, 'This is fixed in JX 3!' Want to wait for beta, then go through the issues, and mark and close the old JX 2 issues this way.
    - JR: Would be great to say, We think this is fixed in JX 3, please try it out and give feedback.
    - JR: Lifecycle bot is on JX repo, would be good to disable, as it would be better to comment that issue fixed in v3 rather than have the issue closed by some bot.
    - JS: The message on issues will help people move to v 3. 
    - JS: Do we have a tool to add issue labels across the repos?
    - JR: I've had to do it by hand so far.
    - Kara: org wide labels would be good.
    - JS: Yes!
    - JS: Will look at labelling 'Good First Issues' for plugins.
    - Kara: will add Hacktoberfest issues
    - JS: Will write a doc on creating a plugin
    - Kara: Will write a blog post for Hacktoberfest, then leverage that through CDF so that they promote us as participating in Hacktoberfest
    - JR: meeting on Friday for Triage?
    - JS: We could do a back to back docs/triage next Monday.
    - JS: Anyone know anyone at Digital Ocean? Would be great to have resources to test on Digital Ocean.
    - JR: Might be able to ping the person we know at IBM cloud, possible to get resources.

#### Action Items
- ~~Kara: Kick off the conversation with Tracy re resources from CDF~~  ✅ 
- Nitin: to explore the tooling for the matrix: Whimsical or Mermaid.js. Think about having color.  ✅ 
- JS: Will look at labelling 'Good First Issues' for plugins.
- Kara: will add Hacktoberfest issues  ✅ 
- JS: Will write a doc on creating a plugin
- Kara: Will write a blog post for Hacktoberfest (linking to creating plugins doc and Hacktoberfest labels), then leverage that through CDF so that they promote us as participating in Hacktoberfest  ✅ 
  
### September 14, 2020

#### Participants
  - Kara de la Marck
  - Nitin
  - James Strachan
  - James Rawlings
  - Ankit

#### Agenda and Notes
 - Welcome Nitin 🎉 
     - Official Start to GSoD is today!! 😃
 - Go over action items from last week.
     - Cloud resources for Nitin -- Good news. A cluster will be created for Nitin on GCP tomorrow. This is confirmed.
     - Updates on Mermaid.js 
         - Ankit: will summarise at next week's docs meeting.
     - When next week should we meet for diagram brainstorm session?
         - Ankit: Next week's docs SIG meeting
 - Nitin priorities for GSoD:
     - Go over JX 3 docs, see where needs more info, raise Issues, start to address
     - JR: Matrix of capabilities for JX 3 and clarifying where not working. Similar to: https://www.jenkins.io/project/roadmap/
     - Initial focus will be GCP. 
     - Ankit: I can give some info on AWS etc
     - Nitin: should we delete the FAQs on docs site?
     - James S: Links might break if we delete the FAQs, so lets not delete for now.
 - Project Boards, for Nitin and Ankit
     - Ankit has one for his work in his own repo, which he will make public
     - There is a [Jenkins X Documentation](https://github.com/orgs/jenkins-x/projects/5) project already in jx org, Nitin is welcome to take that over and make it his own for GSoD
    

#### Action Items
 - ~~Kara to boost Nitin's permissions within jx org, so that he can move issues around on the Jenkins X Documentation board.~~
 - Next week's Docs SIG meeting will include architecture diagram brainstorm session. 
 - Ankit to present information on Mermaid.js

### September 7, 2020

#### Participants
  - Kara de la Marck
  - Ankit M
  - James Rawlings
  - \<addme\>

#### Agenda and Notes
 - Go over action items from last week.
 - Thank you to Nitin for adding [Issue templating to jx-docs repo](https://github.com/jenkins-x/jx-docs/issues/new/choose), as discussed during 24 August meeting. :)
 - During the last week, Andrew Bayer fixed how the docs were auto updating using cobra. All good now. 👍
 - KM: We should improve the docs around using Octant. Have at least one blog post on Octant and a couple demos, but need actual docs section.
     - JR: Will be doing work on Octant integration in the coming weeks and can add to Octant docs as that is done.
 - KM: Deprecating Addons: https://github.com/jenkins-x/jx/pull/7514  
     - What needs to change in the docs?  
     - JR: Not much as we will just have two separate versions of JX.
 - JR: To improve UX of docs for JX 3 we should have a meeting for design in 2 weeks time, when Nitin will have fully started. We have brainstorm and create wireframes and then we can use those designs to create better UX for docs site.
 - JR: Need to be very clear about maturity of JX 3 when discussing it anywhere. 
 - JR: We have should create a matrix for maturity for JX 3 and its features. 
     - KM: We have discussed this in Testing & Platform SIG and Nitin has agreed to work on this. Essentially a capability matrix for JX3, and Nitin's GSoD project has a large component of work focused on the JX capability matrix.
 - Ankit: Could work on having more diagrams on architecture using Mermaid.js
 - JR: Would be interesting to see what these look like. Important to have good looking diagrams.
 - Ankit: Working on EKS, and will add to the docs there
 - \<addme\>

#### Action Items
 - KM: In 2 weeks, have architecture diagram brainstorm session. So, should arrange the session next week, to be held the week after.
 - KM: Keep pushing on getting Nitin his GCP cluster.
 - Nitin: Starting GSoD officially next week. 🎉 Enjoy the Community bonding period. :)
 - Ankit: Look into Mermaid.js
 - \<addme\>

### August 24, 2020

#### Participants
 - Nitin 
 - Kara
 - Ankit

#### Agenda and Notes
* Nitin: Proposal to create the issue template in our Jenkins X [docs repo](https://github.com/jenkins-x/jx-docs/issues) similar to Kubernetes Website [docs](https://github.com/kubernetes/website/issues). Reference procedure to follow [here](https://docs.github.com/en/github/building-a-strong-community/configuring-issue-templates-for-your-repository) and [here](https://docs.github.com/en/github/building-a-strong-community/about-issue-and-pull-request-templates).
* KM: Excellent!
* Ankit: Can use what has been set up for jx repo. And port that to jx-docs repo. And can add a template for PRs as well.

 - Ankit: update on EKS integration and docs for that. Yay!
 - KM: https://github.com/jenkins-x/jx-docs/pull/3007
 - KM: https://github.com/jenkins-x/jx-docs/pull/3006 https://jenkins-x.io/commands/jx_step_git_close/
 - Ankit: James S is looking for people to try out Jenkins X 3 on minikube, while Nitin is waiting for his cloud resources, he could try this out and give feedback and work on those docs.
 - Nitin: have limitations on what can install on laptop, so would rather use cloud resources.
 - KM: announcement that testing & platform integration SIG launching soon -- both Ankit and Nitin enthusiastic about joining. :)
 - Discussion on https://github.com/jenkins-x/jx-docs/pull/3033. 
 - Ankit: Would be great to have strong clarity and separation between Jenkins X 2 and 3 docs. They should have separate sections and possibly with a banner at the top clarifying which version that docs page is for.

#### Action Items
 - Ankit: will take a look at fixing how cobra does the auto updates. (Thank you!)

### August 17, 2020

#### Participants
  - Nitin 
  - Kara
  - Ankit
  - James R
  - James S
  - \<addme\>

#### Agenda and Notes
 - Congratulations Nitin!! We are very excited to work with you during Google Season of Docs: https://developers.google.com/season-of-docs/docs/participants/project-jenkinsx-nitin
 - Go over action items from last week.
     - KM: Roadmap updated, but not moved. Where do we want the roadmap to be in the docs?
         - JS: do a page announcing roadmap and link to the roadmap in community section (so one source).
     - KM: In terms of updating contributor sections, we don't seem to require commits to be signed for the docs, [see example PR](https://github.com/jenkins-x/jx-docs/pull/3022). In which case, that doesn't need to be added to contributing to docs section (see former action item).
    - Ankit: We don't require DCO on the docs repo, but may be a good idea.
    - JS: We need better instructions on how to do DCO for code commits. 
    - KM: We can add in the simple way to do it as well.
 - KM: Deprecating Addons: https://github.com/jenkins-x/jx/pull/7514  
     - What needs to change in the docs? In addition to removing addon command info, how are we communicating the deprecation, do we have a timetable?
 - KM: The 'Feedback' info blurb on the homepage is odd. First that we don't mention ChatOps, but also how it is described doesn't make sense:
     - "Jenkins X automatically comments on your Commits, Issues and Pull Requests with feedback as code is ready to be previewed, is promoted to environments or if Pull Requests are generated automatically to upgrade versions."
     - would be good to fix => ""
 -  AM:
    - Create a v2 section for jx2 docs. When user goes to v2 docs, tell them, that this is only for v2, and they can visit v3 docs to 
      learn abt features in v3 (may be out a banner on the top)
    - KM: I believe hugo/docsy has a default way to do this
    - Do we need the eks/gke page in the docs (https://jenkins-x.io/docs/install-setup/create-cluster/eks/), it's just a copy 
      of the readme of the terraform repo. 
    - What's this: https://github.com/jenkins-x/jx-docs/deployments/activity_log?environment=github-pages (Should remove ...)
    - JR: Not used, can be removed (was a POC, no longer in use)
    - https://github.com/jenkins-x/jx-docs/issues/2906 and the corresponding pr-check issue: https://github.com/jenkins-x/jx-docs/issues/2912
    - Guidelines for opening PRs for new contributors (add information both to the docs and PR templates?)
    - JS: https://jenkins-x.io/community/documentation/style-guide/ Could always be added to.
    - For PR reviewers - Check for issues linked to PR (Not all PRs need issues, but for a bug fix or enhancement it should be a must) - Issues
      are shown in the changelogs for new releases, not PR descriptions
    - What about our policy on the number of commits per PR - When I started contributing, I was told one per PR (which makes sense). If a PR
      is too big, break it into multiple PRs, easy for reviewers
    - JR: We don't have a policy. He doesn't see it as a problem if there is more than one commit per PR, as long as it's not hundreds :) 
 - 
#### Action Items
 - Kara and Ankit (possibly Nitin) Go over JX 3 Alpha docs and make docs improvements and Issues to docs, but also jx repo
 - Ankit: Will set up DCO for docs repo
 - Kara: Will add DCO information, including extra easier ways to sign commits, to contributing to docs section. (Best to have link to single section between both contributor sections)
 - \<addme\>


### August 10, 2020

#### Participants
  - Kara de la Marck
  - Sahil
  - Ankit
  - James Rawlings
  - James Strachan
  - \<addme\>

#### Agenda and Notes
 - Go over action items from last week.
 - Discussion on Jenkins X 3 docs, James S is writing a docs version for Jenkins X 3. We can all work off his PR over the next week, ensuring JX3 docs clear, etc.
 - JS: some of our docs for JX3 will be in the repos depending on path end user chooses -- we have many permutations of possible paths. These paths and their pre-configurations will function a bit like quickstarts
 - JR: the ReadMes on different modules will be an important source of documentation
 - JS: in the docs site we will link to these resources (to start)
 - JS: one of goals of JX3 is that users should be able to to configure their cluster anyway they want and use JX3
 - KM: Demos on office hours can be trimmed to be focused and then used on website.
 - JR: Good, but only hitch is they go out of date quickly, so that needs to be managed.
 - KM: where to put the roadmap in addition to community section?
 - JS: Perhaps use shortcodes (or in worst case copy and paste, but better to avoid), put in Docs section, under Guides and Resources
 - KM: autogenerating docs might need a nudge as https://jenkins-x.io/commands/jx_step_git_close/ has not updated (and should have with example change)
 - JS: will take a look and ensure auto-updating of docs working.

#### Action Items
 - KM: Fix contributing sections 
 - KM: add the additional page on Roadmap in Docs section
 - AM: re links in jx repo ReadMe, Ankit will add the links at the top.

### August 3, 2020

#### Participants
  - Kara de la Marck
  - Sahil
  - Ankit
  - James Rawlings
  - \<addme\>

#### Agenda and Notes
 - Go over action items from last week.
     - KM: responded to Buildpack naming issue: https://github.com/jenkins-x/jx/issues/7343
     - KM: Discourse site populated with more FAQs, and getting traction/responses. Has everyone joined? 
     - KM: updates to community pages still needed, SIGs and Discourse
         - For Discourse, who here is informed when people comment on issues?
         - Answer (Ankit, James): there is a weekly summary sent by email, both receive it.
- Is this information on secret management in FAQs up to date? https://jenkins-x.io/docs/resources/faq/using/#how-do-i-manage-secrets-in-each-environment
    - No. Needs update, see below.
      
 - DCO information not in Contribute to Docs sections, needs to be added: https://github.com/jenkins-x/jx-docs/issues/3004
     - KM: Actually, the entire section on contributing to docs needs an update, and reorg. There are long pages of text and we should break it into sections. With links depending on what user needs -- not everyone needs to scroll past sections on creating branch, etc. It's good to have lots of info and context, but each section should be on its own, for more depth/context/info for those that need it.
 - Should we start putting in place documentation on GitOps SIG?
     - JR: server set up for creating cluster to import JX 3 repos and work on them and present JX3
     - Once that's done (possibly next week), then we launch GitOps SIG
 - AM: Look at all issues (open and closed), and select the ones which talk about auditing docs, and work on them (the ones from John are good - https://github.com/jenkins-x/jx-docs/issues?q=is%3Aissue+author%3Ajha-cloudbees+audit)
 - AM: Put the link to the discourse link in the readme section of the jx repo (similar to terraform: https://github.com/hashicorp/terraform)
 - AM: https://github.com/jenkins-x/jx-docs/issues/2993
 - AM: https://github.com/jenkins-x/jx-docs/issues/2934
     - Yes. JR: Would be good to start in FAQ section. Then we build up section on contributing.
#### Action Items
 - KM: reorg contributing sections
 - KM: add to community section
 - AM: re links in jx repo ReadMe, Ankit will add the links at the top. 
 - KM: Fix info in [FAQ on secrets](https://jenkins-x.io/docs/resources/faq/using/#how-do-i-manage-secrets-in-each-environment): Link to Hardy's Vault work and external secrets repo as an option. 
 - JR: review the secrets update and add info on where we are going.
 - KM: update roadmap with enhancements links
 - KM: Rewrite Contribution to docs, then code sections important, 
     - JR note: then how to highlight how people can get involved -- will be easier when we have more SIGs, can point people to the SIGs.
 - \<addme\>

### July 27, 2020

#### Participants
  - James Rawlings
  - Kara de la Marck
  - James Strachan
  - Ankit

#### Agenda and Notes
 - Go over action items from last week:
     - PR on Jenkins X course has been merged.
     - Update: the Testing and Release SIG has been postponed as we would like to focus on GitOps SIG that will be launched asap.
     - Similarly, issue on Alpha, Beta, GA postponed as we focus on initial release of Jenkins X 3. 
     - JS: Once there is a better understanding of what clients need for each of these quality gates, then we should outline what these terms mean for the Jenkins X project. Conversations to determine what is needed for quality gates are ongoing atm.
- JS: FAQ are all over the website now we’ve refactored the docs; so here is a spike at consolidating all the FAQ’s together in a single place https://github.com/jenkins-x/jx-docs/pull/2981 what do folks think? http://jx-docs.jx-jenkins-x-jx-docs-pr-2981.jenkins-x.live/docs/resources/faq/
    - KM: Excellent! Even with the new Discourse. https://jenkinsx.discourse.group/
    - JS: The FAQs still need to be edited and checked if not outdated.
    - Once updated we can use them to populate JX discourse.
    
- JS: We should enhance the JX Roadmap with links to Enhancement Proposals
     - JS: And move roadmap to Docs (out of community section)
     - JR: We should clarify enhancement process
     - JS: Longterm FAQ is Discourse. Enhancement proposals are Issues
     - JR: Enhancement proposal process => issue is closed 1) when it is complete and the ending action is to summarize the proposal in one page 2) or enhancement proposal closed as not moving forward
     - JS: each enhancement proposal should have its own project board in jx org
  
 - KM: Proposal: We should consider our use of terminology that does not reflect the values of our community, and is increasingly dated and viewed as technically inaccurate.
     - This isn't just a docs issue; however, this is a place to start the discussion. The outcome will need to be documented, in our style guide and perhaps our CoC.
     - Terms to consider replacing:
     - Master / slave  
         - Note the `jx` repo does not contain the term "slave", however we should consider and state in our style guide what is our preferred term. We do already use "agent" a lot in `jx`.
         - Master. This appears a lot in `jx` and will be the most work to change. Proposal that its replacement is "main".
    - Whitelist/Blacklist
        - Proposal to replace with Allowlist / Denylist
 - Discussion of terminology proposal:
     - JR: Jenkins X itself doesn't have a great need for a master / worker pairing. We mostly refer to these, if/when needed, in theterms of the projects we incorporate or extend. In these cases, we likely should use the terminology of those projects.
     - JS: we do use master a lot, main is a good option. In docs we should switch to main. 
     - JS: easier to change docs, the docs can change. 
     - AM: codebase complicated to change: https://github.com/pmmmwh/react-refresh-webpack-plugin/issues/113
     - KM: We could acknowledging our preferred terms and create a style guide for JX3. 
     - JR: Good to have the acknowledgement and change the docs.
     - In code it'll be more work to take it out. Because getting GH to default to main is more complicated.
     - AM: GH has announced that they are switching to using main, but there isn't a timeline yet.
     - JS: It would be nice for new quickstarts to use main.
     - JR: postcommit config could check for this.
 
 - AM: Should this be discussed in the office hours? https://github.com/jenkins-x/jx/issues/7343 -> this would also mean updating the docs ...
     - JR: Will be addressed by using Tekton catalogue.
     - JR: We should update and comment on the issue.
 - AM: should we have SLA on PR reviews (just give a timeline on how long it will take to review PRs). Put in the docs, so people don't expect instantaneous reviews.
     - JR: very good idea, but for the moment we need to focus on JX3 direction. Encouraging development on JX3 work by community. JX2 work should be mostly maintenance. 
     - As part of our effect to encourage contributors to JX3 we will develop these docs. 
     - JS: docs on reviews on docs site would be good.
     -  - AM: We should have this as part of the PR review docs: https://github.com/golang/go/wiki/CodeReviewComments
 - JS: need to ensure we are checking all repos for PRs, some sometimes are not seen.
     - KM: triage party will pull in many repos, so great for bringing PRs all together, if set up correctly.

  

#### Action Items

 - Kara to go over FAQs and start populating the Discourse site
 - Kara to add to FAQs as needed.
 - How to get involved: more information on enhancement process and how to get involved and page on SIGs
 - More on community home page on how to get involved, enhancement process, etc
 - Kara to create section on existing community home page on Discourse.
 - Kara to launch GitOps SIG as soon as infra set up (maybe end of week, or soon)
 - JR to comment on Buildpack issue
 

### July 20, 2020

#### Participants
  - Kara de la Marck
  - Nitin
  - Sahil
  - Ankit

#### Agenda and Notes
  - Discussion on alpha, beta, GA, stable, etc.
  - Nitin suggests following closely Kubernetes definition and use of those terms.
  - Discussion on upcoming SIGs.
  - The next SIG will likely be a Testing and Release SIG.
  - Ankit interested in being involved in T & R SIG. 
  - Kara suggests Ankit could chair or co-chair SIG.
  - Ankit: SIG needs to decide on testing coventions.
  - Go mock? mocks vs fakes? naming conventions on functions? what should we test? Focus on unit tests important, as well as integration tests. Unit tests will likely be first focus. Testing framework to use?
  - Friday (1pm UK time) is a good meeting time to propose.
  - Sahil: Function tests are good as well. 
  - Ankit: Yes, would generally group them with integrations/e2e tests and they should be initial focus for testing SIG.
  - Sahil: discussion on his proposal for GSoD
  - Which sections of the docs to work on first for ascii cinema. 
  - plural sight course link:
      - approved, but PR build failed. 
      - Ankit to add note on course cost.
  - jx ui open source:
      - Ankit working on new open source UI
      - Docs need to announce the UI change.
  - cloudbees jx future:
      - Need to remove sections in docs on CJXD and SaaS
  - Ankit: Dark mode on docs site. 
      - Sahil working on PR.
  
#### Action Items
  - Ankit to add note on course cost.
  - Kara to shephard PR on Jenkins X course to be merged.
  - Kara to create section in Docs on the SIGs and how to get involved.
  - Kara to create issue for defining what Alpha, Beta, GA, stable, experimental means for Jenkins X components/modules.
  - Kara to create Testing and Release SIG for Fridays. ⛩️

### July 13, 2020

#### Participants
  - Kara de la Marck
  - Ankit
  - James Rawlings
  - James Strachan
  - Sahil

#### Agenda and Notes
- https://github.com/jenkins-x/jx-docs/pull/2957
- https://github.com/jenkins-x/jx-docs/pull/2958
- https://github.com/jenkins-x/jx-docs/issues/2954
- Discussion on creating section in Docs on the SIGs and how to get involved. Should be in Community section of the Docs.
- Documentation needed on how we define Alpha, Beta, GA, stable, experimental. Standards on code coverage, etc. This needs to be thought about now and applied to the Jenkins X components as we move to a more modular Jenkins X

#### Action Items
  - Kara to create section in Docs on the SIGs and how to get involved.
  - Kara to create issue for defining what Alpha, Beta, GA, stable, experimental means for Jenkins X components/modules. 
  - ~~Kara to update meeting link 😅~~  Done ✅ 

### July 6, 2020

#### Participants
  - James Rawlings
  - Ankit
  - Sahil Yerawar
  - John Ha
  - Nitin

#### Agenda and Notes

- discussed https://github.com/jenkins-x/jx-docs/pull/2950, let's wait for Kara to see, maybe there should be a comment on the website link to highlight this is a paid for course?  It might still be nice to include books and paid for tutorials as a list of resources to help people learn more about Jenkins X?
- discussed Sahill's idea of using Asciicinema to record longer codeblocks and command-line animated demos to show readers how a command or longer code block works. The proposal is [here](https://docs.google.com/document/d/1oBtrRxv6ECv_EOozdQ4IkX8soC9QMUaJaKSmVkIHtIE/edit?pli=1#heading=h.m2ikibwgxno6) and an asciicinema example is [here](https://asciinema.org/a/7HZIUVt6g4NvE9Mk4HwXBzNbu).
- discussed https://github.com/jenkins-x/jx-docs/issues/2943 Ankit is offering to take a look at it this
- Sahil might take a look at https://github.com/jenkins-x/jx-docs/issues/2877 - very cool :)

### June 29, 2020

#### Participants
  - Kara de la Marck
  - Hartmut Ferentschik
  - Ankit
  - Nitin
  - Deane Smith
  - Sahil
  - John Ha

#### Agenda and Notes
  - https://github.com/jenkins-x/jx-docs/issues/2934
  - https://github.com/jenkins-x/jx-docs/issues/2941  
  - https://github.com/jenkins-x/jx-docs/issues/2852
  - https://github.com/jenkins-x/jx-docs/issues/2803:
      - on hold for now, first verify security information/process
  - https://github.com/jenkins-x/jx-docs/issues/2935

#### Action Items


### June 22, 2020

#### Participants
  - Ethan Jones
  - Kara de la Marck
  - Hartmut Ferentschik
  - Ankit
  - John Ha
  - Deane Smith

#### Agenda and Notes
  - Review action items from last week
      - Style guide discussed (see below)
      - Triage added to agenda as discussed last week
  - There was confusion last week on the purpose/goals of this SIG. Please take a look at the [README on the repo](https://github.com/jenkins-x/jx-community/tree/master/sig-docs). Do we want to add to that? 
      - Did not cover this
  - Docs style guide update from John
      - John is working on a PR now with a lightweight style guide, demo'd on the meeting
          - One sentence per line 🎉
          - Lots of other good stuff, will be added to the docs contributor guide
  - 20 minutes triage on [jx-docs issues](https://github.com/jenkins-x/jx-docs/issues)
      - We did not get around to triage this week
  - Two of these meetings are recorded, but haven't been uploaded to YouTube. Do we want these on Jenkins X YouTube channel? Would it be better to have a link on README of repo to the recordings stored in Google Drive?
      - Kara will create a Youtube playlist for the recording and update the readme to link to the playlist and the meeting notes
 - There are 2 environment variables (JX_BOOT_START_STEP and JX_BOOT_END_STEP) which are incredibly useful for debugging boot issues quickly, which probably can be part of the docs.
     - Question about if the commands should be better documented and if so, where
     - Need to differentiate between `jx boot` and `jx install`, especially if not deprecating `jx install` asap. Current docs are confusing for users.
     - Ethan suggestion: Deprecated docs section, that is suggested is sections with new commands. So main docs would focus on `jx boot`, and there would be a statement that previously `jx install` was used and give a link to `js install` instructions that would be located in deprecated section of docs.
     - This is a good improvement to the docs to do now. 
  - Copy to clipboard functionality for commands in the doc?
      - Everyone agrees this is a good idea, just how to get it done 
  - Docs are not very clear about minikube/minishift being deprecated.
      - Ankit has done a PR on this that needs review and approval
- Due to the amount of churn recently with documentation updates, a good amount of the translated content needs updating.
    - Deane suggested that a high priority issue be created to address the most vital content first - Getting Started.

#### Action Items
  - :collision: :checkered_flag: The docs site currenly contains content that has been dumped into folders called **old**  Since they are not being used I (Oscar medina), recommend we delete the content as it is making it difficult to run HTMLProofer for new content.
- Hardy/Deane/Oscar to review Ankit's PR on removing / deprecating minikube
- Ethan will get rid of duplicate child in install section and just have four children



### June 15, 2020

#### Participants
  - Kara de la Marck
  - Ankit Mohapatra
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
  - Kara: What do we want the goal/purpose of this board to be?
  - Oscar: Should the board take more control over what is merged in Jenkins X docs?
  - Kara: Should we do triage in this meeting? Spend 20 minutes each meeting? Are we willing to spend an hour on this meeting?
      - general response: not an hour. Need more efficiency and can maybe do 40 min meetings
      - Kara: Need more pre-meeting additions to this Hack.MD by all so we know the focus discussions for the meeting. Links to issues are good, so people can have context for the discussion and it can continue after the meeting(s) on the issues.
      - Kara: in addition, for future meetings, we can have 15-20 minutes reserved for triage.
  - Discussion of Docs navigation Issue created by Viktor during Day of Docs.
  - Viktor: Improvments in structure are all well and good, but we need to ensure the content is improving substantially.

#### Action Items
  - John to draft (PR) an initial style guide.
  - Kara to add 15 min set time to the agenda for this meeting. And we will see how this process goes.
  - All of us: Think about Triage process and how we want to label the issues.
  

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

### May 25, 2020
 - Docs SiG meeting on 25 May cancelled due to public holidays in both US and Europe. 

#### Action Items
 - Enjoy the long weekend everyone! ☀️

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

 



