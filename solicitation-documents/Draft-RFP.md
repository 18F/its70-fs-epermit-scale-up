# Forest Service Online Permitting, Special Use Scale-Up 

## Schedule 70  
**SIN 132-51**

# DRAFT Request for Proposals (“RFP”)

## 1.0 Background

The U.S. Forest Service is engaged in an ongoing effort to modernize and simplify their permitting processes. One facet of this effort is to make them available to obtain and purchase online. GSA's 18F Acquisition is working with the Forest Service to plan and build out this platform.

For the past year, the Forest Service and partners developed a cloud-based application to support the migration of permit applications and issuance online. The team developed this application using open source and user-centered principles for several pilot National Forests.

As the first two-way interaction-focused Forest Service online application, ePermits will strengthen the connection between the public and the National Forests.

The application will broaden and increase the public’s responsible access to public lands through online availability; a predictable, responsive and friendly experience; and reduce administrative burden.

These enhancements will drive increased customer satisfaction and quality of public engagement.

This task order seeks to expand the capabilities of the platform by ensuring that the product can better support these initial forests, and allow for the onboarding of additional high-priority forests identified by the U.S Forest Service.

## 2.0 Statement of Objectives (SOO)

To fulfill the objectives for performance of this task order, the Vendor must expand the platform through functionality and content that meets the needs described in the epics in the following subsections. Please note that, in subsequent sprints, we may refine these objectives to ensure we’re continually meeting user needs. In agreement with the product owner, we may modify, add, retract, or re-prioritize user stories to reflect additional research findings.

In general, this award will support the onboarding of additional forests to issue permits and receive applications electronically.

The Vendor must build a custom software extend the [<span class="underline">existing online permitting platform</span>](https://github.com/18f/fs-intake-module) using agile methods that fulfill the following user stories, or new user stories as the client and the vendor work together to incrementally develop the software:

## Epics

### The contractor shall build or adapt the permit platform functionality to allow for:

  - More forests to be added to the Special Use permit applications system 

  - User group and role management 

  - A system that is production ready from a compliance perspective  
    Note: the goal of this objective is to harden our system so that we can get an [<span class="underline">Authority to Operate (ATO)</span>](https://before-you-ship.18f.gov/security/)

  - Applicants to submit complete applications with valid data to the internal USFS permit management system 

  - More transparency in the special use application process

  - An improved user experience across permit types

  - Special Use Administrators’ ePermit reporting needs to be met

  - Additional special use permit types if user research suggests this could be highly valuable

Some of the user stories that may be included as part of this work are included in the Appendix.

Please note: additional epics and stories will result from onboarding new forests, user research, usability tests, and feedback from real end-users once the system is in production.

### 2.1 Additional requirements

**2.1.1 Product requirements**

  - **Build as part of the existing [<span class="underline">permitting platform</span>](https://github.com/18F/fs-permit-platform) and as needed the [<span class="underline">special use middlelayer api</span>](https://github.com/18f/fs-middlelayer-api). Any changes affecting special use must ensure that existing functionality is maintained unless removed or adapted per emerging user needs **

  - All software code delivered under this order shall comply with the [<span class="underline">18F open source policy</span>](https://github.com/18F/open-source-policy/blob/master/policy.md) in effect as of the date of award.

  - All software code delivered under this order shall comply with the [<span class="underline">18F Accessibility Guidelines</span>](https://accessibility.18f.gov/) in effect as of the date of award.

  - The contractor will use the USFS adaptation of the [*<span class="underline">US Web Design System.</span>*](https://playbook.cio.gov/designstandards/)

  - All dependencies (and licenses for dependencies) must be listed within the repository.

  - All major functions must be documented inline.

  - Code must be stored in a version-controlled, open-source repositories supplied by 18F, with all code needed to run the application available in those repositories.

**2.1.2 Process requirements**

  - Work will be conducted in two-week sprints and reviewed at the end of each sprint for acceptability per the Quality Assurance Surveillance Plan (“QASP”) before moving on. The Vendor and Government may mutually agree to alter sprint length as needed.

  - Usability testing and other user research methods must be conducted at regular intervals throughout the development process (not just at the beginning or end), with all artifacts from usability testing and/or other research methods with end-users being made available at the end of every applicable sprint.

  - Recruit members of the public to participate in usability testing throughout the development process.

  - All Contractor Key Personnel, employees, agents, subcontractors, and subcontractor personnel who will have access to documents or data during the performance of their duties under the contract shall execute the attached Non-Disclosure Agreement and return it to the CO within 5 calendar days of award and before being given access to such information or documents.

### 2.2 Government Furnished Property

In order to assist the vendor in fulfilling the deliverables, the Government will provide:

  - A cloud.gov staging environment with vendor access to the environment logs and credentials for continuous deployment. Note: direct push rights will not be given unless the 18F and Forest Service team determines that it is necessary.

  - Multi-channel guest access to the GSA-TTS Slack for team collaboration.

### 2.3 Post Award Orientation Conference

The Government’s team and the Contractor’s team will hold a Post Award Orientation Conference (“Vendor Kickoff”) within 10 calendar days of Award. The Government’s team will include the Contracting Officer (“CO”), the Contracting Officer’s Representative (“COR”), the TTS Product Lead, and the Product Owner (“PO”).

This will likely be done virtually. The purpose will be to review and clarify the project’s objectives and the Government’s expectations. Additionally, the Government will address any questions the Contractor may have. Discussion topics shall include, but not be limited to:

  - Introduction of the Contractor and Government staff

  - Understanding of the workflow

  - Project management expectations

  - Agreement on communication methods

  - Discussion of any other relevant specific concerns

  - Finalizing Contractor Teaming Arrangements (CTAs)/Subcontractor arrangements

### 2.4 Daily Operations

The Contractor’s Project Manager serving in their capacity as ScrumMaster shall be responsible for daily operations as well as coordinating and communicating with the Forest Service Product Owner. Daily operations may include:

  - Daily standup via Google Hangouts, Zoom, appear.in, or other web-based video chat software

  - Chat operations via Slack

  - Manage and update user stories and workflow tasks in a shared project management system, such as Trello or Github.

  - Sprint ceremonies including sprint review, retro, planning and backlog refinement

### 2.5 Frequency of Invoices

The Contractor must provide invoices on a monthly basis.

### 2.6 Transition Plan

Ensure and agree that all deliverables, products, licenses, designs, data, documentation, tests, user research notes, source code, configuration settings and files, and materials developed throughout this call order will be the property of the U.S. Government and in the public domain. One weeks prior to task order conclusion, all deliverables, products, will be incorporated into the **project repository**. Exclusion of project artifacts may be allowed in coordination with the TTS Product Owner and COR. Provide any other reasonable assistance to the Government to deploy the latest version application.

### 2.7 Transition Activities

During the transition to the Government or a new contractor, the Contractor shall perform all necessary transition activities. Expected transition activities may include, but not be limited to:

  - Continuation of full services to TTS and other customers

  - Participation in meetings with the Government or a new contractor to effect a smooth transition and provide detailed information on the operation of all deliverables, at COR and the TTS Product Lead's discretion

  - Training of new personnel, either Government or a new contractor, during transition period Appropriate close-out of any outstanding technical and related performance elements for this task

## Should the Contractor be terminated prior to the end of the period of performance, the Contractor shall transfer all project materials to the COR and the TTS Product Lead within two weeks of the COR and the TTS Product Lead’s request.

## 3.0 Scope and List of deliverables

### 3.1 Scope

This application will extend the Forest Service online permitting system to include the onboarding of additional National Forests. To satisfy the needs of members of the public, and Forest Service special use administrators, the vendor will provide the following deliverables by the conclusion of performance.

### 3.2 List of deliverables

| **DELIVERABLES**                            | **DUE DATES**                        | **CONTENT DESCRIPTION**                                                                                                                  |
| ------------------------------------------- | ------------------------------------ | ---------------------------------------------------------------------------------------------------------------------------------------- |
| Code repository of product                  | Ongoing with every applicable sprint | Version-controlled open source code repository that comprises product that will remain in the public domain                              |
| Issues in repository from usability testing | Ongoing with applicable sprint       | Usability or other issues discovered via usability testing and documented in the project’s source control system                         |
| Design deliverables                         | Ongoing with every applicable sprint | Mock-ups and/or design files if applicable, or design changes reflected in the development product                                       |
| Development product                         | Ongoing with applicable sprint       | In-progress development product, accessible on the web via staging server / development server (that will likely be hosted on cloud.gov) |

## 4.0 Personnel

### 4.1 Required skills and knowledge

The Vendor must provide a team of qualified personnel — people whose knowledge and experience allows them to successfully perform the work outlined in this task.

Proposed personnel must have a strong technical experience base in the following:

  - Technology stack referenced in the repositories linked Section 2.1.1.

  - Iterative development practices, as well as specific methodologies such as Scrum

  - Automated (unit/integration/end-to-end) testing experience

  - Continuous Integration and Continuous Deployment

  - Refactoring to minimize technical debt

  - Application Protocol Interface (API) development and documentation

  - Open-source software development

  - Cloud deployment - for demonstration hosting

  - Open-source login/authentication services

  - Mobile-first approaches, performance budgeting, and progressive enhancement

Using human-centered design methods to build and test form-driven, web-based applications. Human-centered design practices include:

  - Usability research, such as (but not limited to) contextual inquiry, stakeholder interviews, and usability testing

  - User experience design

  - Sketching, wireframing, and/or prototyping, and user-task flow development.

  - Visual design

  - Content design and copywriting

  - Building and testing public facing sites and tools

### 4.2 Key Personnel

#### 4.2.1 Categories

For this task the following Key Personnel are necessary (as detailed at [<span class="underline">https://agile-labor-categories.18f.gov</span>](https://agile-labor-categories.18f.gov/))

  - **Scrum master** will serve to facilitate a self-organizing team and ensure the daily operations in Section 2.4

  - **Senior full stack developer** - must be comfortable with both Node.js and AngularJS and will contribute to the production code of the online permitting platform.

  - **User Researcher -** conducts usability tests, develops research plans, and translates end-user feedback into additional user stories.

#### 4.2.2 Key Personnel substitution

In the event a Key Personnel member becomes unavailable during the course of the solicitation and evaluation process, the Contractor shall immediately notify the Government and provide a substitute individual with resume that fits within all the guidelines outlined in Section 5.0.

In the event a Key Personnel member will be substituted, the Contractor shall provide complete resumes for proposed substitutes, and any additional information requested by the Contracting Officer no later than 5 business days after notifying the Government of the need for a substitution. Proposed substitutes should have comparable qualifications to those of the persons being replaced. The Contracting Officer will notify the Contractor within 15 business days after receipt of all required information of the consent on substitutes. No change in fixed unit prices may occur as a result of Key Personnel substitution.

## 5.0 Milestones

The following milestones are provided for this solicitation.

| **No.** | **Due Dates**    | **Acquisition Event**            |
| ------- | ---------------- | -------------------------------- |
| 1       | TBD              | Solicitation Released            |
| 2       | TBD in Final RFQ | Questions about Solicitation Due |
| 3       | TBD in Final RFQ | Written Quote Submissions Due    |

If you’d like to ask questions or comments about this RFQ, you must submit them as [issues in this GitHub repository](https://github.com/18F/its70-fs-epermit-scale-up/issues).

Quotes must be valid for at least 90 calendar days after the quotation response date. Information provided in the quotation must be concise, specific, and complete.

During this process, Offeror(s) shall direct all written or verbal communications to the contract specialist. Communications with other officials may compromise the competitiveness of this acquisition and, for this reason, aren’t allowed.

Offerors are required to submit a Potential Organizational Conflict of Interest Statement (COI). If the Offeror has any potential organizational conflicts of interest, they must provide a statement describing the potential or actual COI with their quote. The information in this statement must be accurate and complete so that a CO can assess the nature of the potential conflict of interest.

Finally, Offerors must provide their COI responses in the appropriate field of the provided Google Form in order to be considered for award.

### 5.1 Written quote submission

#### 5.1.1 Technical quote

To make the process easier for potential Offerors, we have provided a Google Form for the written technical quote portion of submissions. Please note that each Offeror can enter only one submission (no alternate quotes will be allowed). **All offers must be received no later than the due date indicated on the SF1449.**

**Written technical quotes will only be accepted via the provided Google Form.**

Offerors must provide price-related information separately via the eBuy system (in other words, not as part of the written technical quote).

**5.1.1.1 Technical understanding and approach**

Offerors should describe their understanding of the performance objectives for the requirements (described in full in Section 2). Offerors must provide an overview of their approach to user research methods, end-user recruitment strategy, and continuous improvement in the agile software development process. They must provide a justification of the proposed labor categories and skill mix - and how that will help achieve the module objectives of scaling the application to more forests.

**5.1.1.2 Key personnel**

The offeror must provide a list of key personnel. This list will include each team member’s name, title, contact information, and proposed duties and roles, along with resumes for each proposed key personnel member in accordance with Section 4.2 of this solicitation.

Each proposed team member’s resume should include the following:

  - A summary of the person’s experience and capabilities

  - A summary of the person’s technical background

  - Work experience

  - Accomplishments relevant to the solicitation

  - For technical architects, backend developers, frontend developers, and user researchers, a link to the person’s GitHub repository.

  - For writers, content strategists, and designers a writing sample and/or usability research artifact.

If an offeror or teaming partner would like to include, as part of their key group of personnel, someone they’re not currently employing, they’ll need to include a letter of intent signed by that person (in accordance with Section 4.2 of this solicitation).

  - Please make sure all resumes are no longer than one page.

**5.1.1.3 Similar experience - code repository submission**

To be considered for award, offerors must provide links to the relevant version controlled repositories (public or credentialed) in the proper field in the Google Form.

Code repositories submitted must meet the following requirements: They must be for projects completed within the last three (3) calendar years. They must have staffing profiles of at least three full-time equivalent (FTE) personnel. They can cover performance periods of no more than eighteen (18) months. The projects must have been delivered by one of the following:

  - The Offeror

  - A teaming partner (proposed in response to this solicitation)

  - Proposed key personnel

In addition, we will express a strong preference for Offerors who submit code repositories that are:

  - Version controlled the same runtime language as proposed as the existing online permitting platform (AngularJS and Node.js).

  - If not publicly available, demonstrates security practices that are appropriate for source code release (i.e. no hard-coded passwords).

  - Indication of how source-code is built and deployed via configuration as code.

  - Proposed key personnel were involved

  - Include design artifacts and the results of user research

  - Feature projects that are roughly similar in terms of size, scope, and complexity.

When you submit repositories, please describe how the offeror’s team was involved in the development.

**5.1.1.4 Similar experience - usability research results**

Summary of usability research and research plan including methods used delivered by one of the following:

  - The Offeror

  - A teaming partner (proposed in response to this solicitation)

  - Proposed key personnel

**Written technical quotes that fail to include any of the items required above will not be considered for award.**

If potential offerors plan to use any Contractor Teaming Arrangements (CTAs) or subcontractor arrangements, then they must provide a description of these arrangements. These descriptions should list company names, personnel, and the parts of performance to be provided. Because CTAs and subcontractor arrangements are not the same, offerors must clearly state whether they’re proposing a CTA or subcontractor arrangement. If the offeror is not proposing any such arrangements, they don’t need to take any additional steps here.

#### 5.2. Written price quote

Offerors should complete both tabs of the pricing template. The first tab is for the base period of six months and the second tab is for the option period of three months. For purposes of pricing the option period, the offeror should assume continued performance by all members of the proposed team at full operating capacity for the duration of the three month option period.

Offerors must submit a separate price quotation using the provided worksheet template in the eBuy system. The price quotation must be received no later than the due date indicated above.

All proposed labor rates must be consistent with the terms, conditions, and rates of your aBPA. Proposed labor rates must be fully burdened and include profit, fringe benefits, salary, indirect rates, and the GSA Industrial Funding Fee (IFF).

#### 5.3 Verbal presentations agenda

| **No.** | **AGENDA ITEM**                                | **MAXIMUM TIME**        |
| ------- | ---------------------------------------------- | ----------------------- |
| 1       | Introductions                                  | Approximately 5 minutes |
| 2       | Open Technical Session                         | 40 minutes              |
| 3       | Closing Remarks and Frequently Asked Questions | 5 minutes               |

##### Rules

No part of these verbal presentations - for example, discussions and negotiations - constitutes a procedure in FAR Part 15. For this reason, the Government is not obligated to and does not intend to determine a competitive range, conduct discussions, and request quote revisions.

The verbal presentation consists of an unstructured question and answer session on technical factors. The entire verbal presentation will take place remotely via video chat and/or teleconference.

Offerors will not be able to use or present slides, graphs, charts or any other written presentation materials, including handouts.

##### Content

During the Open Technical Session, the Offeror will respond to Government’s questions related to the technical aspects of the Offeror’s proposal.

Introductions will be used solely for introducing team members’ names and roles on both the Government and vendor teams. Time for introductions will not be allocated to business development purposes.

Although the technical factors are identified in the RFQ, the core questions are not listed there. Offerors must be prepared to answer questions about the technical aspects of their respective quotes. The goal of these presentations is to assess the technical abilities of the proposed Key Personnel and further elaborate on their proposed technical approach to accomplish the objectives of this task.

This part of the verbal presentations will not exceed 40 minutes. The Contracting Officer will strictly enforce this time limit on all presentations. There will be no follow-up session for further questions after this part of the presentation.

The session will conclude with closing remarks and responses to frequently asked questions for Offerors.

##### Presentation location

Verbal Presentations will take place via video chat, though audio may be substituted as needed. The Government will coordinate and set up the meeting space accordingly (providing dial-in information or links using a tool such as Zoom or Appear.in).

##### Presentation date and time

The Government will schedule the date and time of the verbal presentations with each Offeror after the solicitation closing date and receiving each Offeror’s quote submission. The Government reserves the right to reschedule any Offeror’s verbal presentations date at the discretion of the contracting officer.

##### Presentation participants

Proposed Key Personnel must participate in the verbal presentation. Otherwise, the Offeror will be considered non-responsive and excluded from further consideration.

Offerors may include as many participants as are necessary. Offerors should note that the Government will be asking technical questions during the verbal presentation, so non-technical personnel may not need to attend.

All proposed Key Personnel currently employed by the Offeror or its teaming partners must attend the session - the Government is most interested in hearing from staff who will have a direct role in completing the task.

After the presentations, vendors must email the meeting organizers the names of everyone who attended.

## 6.0 Evaluation

### 6.1 Technical Evaluation

The following will be used to evaluate technical quotes:

### Composition of the team

The government will review the materials supplied via the responses to the Google Form and conversations in the verbal presentation, including GitHub profiles, example projects, and resumes for proposed personnel for strength of experience in the required skills and knowledge outlined in Section 4 above. **The composition of the proposed team is the most important consideration in the government's selection.**

### Understanding of the proposed requirements

We will review the responses to the questions in the Technical Quote and clarification questions in the verbal presentation to ensure they demonstrate an understanding of the requirements outlined in the PWS and the strength of the proposed Agile development practices, strong technical approach, and staffing plan.

**Approach to usability research experience**

We will review the responses to the questions in the Technical Quote and clarification questions in the verbal presentation to ensure they demonstrate an understanding of the requirements outlined in the PWS and the strength of the proposed user-research.

### 6.2 Price evaluation

A reasonable price that is consistent with industry standards and the vendor’s proposed approach, but not necessarily the lowest. We intend to pick the vendor that has the best technical factors rather than the lowest price. If we have to choose between the two, technical will significantly outweigh price.

### 6.3 Evaluation process

We will review the responses to the questions in the Technical Quote to ensure they demonstrate an understanding of the requirements outlined in the PWS, particularly section 2.1 (the ability to work with the existing tech stack here will be important), and the strength of their proposed user-research and Agile and development practices.

We will also review company and personnel GitHub profiles, example projects, and resumes for proposed personnel for strength of experience in relevant projects.

We will review of Google Form responses for the strength and feasibility of the proposed technical approach, the level of knowledge in the specified technical stack in section 2.1 that is possessed by the personnel put forward by the vendor and within the repositories provided as examples, and the ability of the team to get along with one another and the Government’s team.

We will assess the verbal presentation to validate the technical approach put forward in the written presentation and verify how the proposed team will accomplish it. The verbal presentation will also evaluate how effectively the proposed team communicates and whether there are any intangibles (such as corporate culture and individual personality factors) about the team that may not come out in a written document.

## 7.0 Basis for award

We intend to select a vendor that puts forward the most sensible (“best”) technical approach, Key Personnel that can fulfill the objectives, a reasonable price (not necessarily the lowest), the ability to not only work the way we want (open source, user-centered design, agile, etc.) and work well together, but also the ability to work well with the particular personalities that exist on the Government’s team (based on interactions during the verbal presentation).

## 8.0 Awarded task

### 8.1 Task details

#### 8.1.1 Type of contract

This contract is Time and Materials for the services offered on the schedule priced at hourly rates.

### 8.1.2 Period, place, and hours of performance

The period of performance is six month base period and a three month option period.

Option for Increased Quantity—Separately Priced Items

The Government may require the delivery of the services herein for an optional period of three months, in the quantities and at the prices stated in the offeror’s schedule. The Contracting Officer may exercise the option by written notice to the Contractor at award or within the performance period of the order.

The primary place of performance will be at the Contractor’s facility.

#### 8.1.3 Points of contact

The following Points of Contact (POC) applicable to this order will be identified during the Vendor Kickoff meeting.

Contracting Officer (CO) Contract Specialist (CS) Contracting Officer Representative (COR) Technical Point of Contact (TPOC) Product Owner

### 8.2 Roles and responsibilities

Please refer to the roles and responsibilities listed on our [<span class="underline">18F Assisted Acquisition Roles and Responsibilities Page.</span>](https://agile-bpa.18f.gov/working-with-us/our-project-team/)

## 9.0 Additional Provisions/Clauses Applicable to this Order

### 9.1 TTS Transparency Policy

Vendors are advised that TTS will publish documents associated with this requirement on a publicly-available website, including any Requests for Quotation (including amendments), Question and Answer exchanges with vendors (source-identifying information removed), and other relevant information that is not confidential or proprietary in nature or source selection sensitive information that would otherwise implicate procurement integrity concerns.

Upon award, TTS will publish the total price of the selected proposal and certain non-source-identifying data (for example, the number of offers, the mean price, median, and standard deviation of price). During the performance of this call order, TTS will similarly publish source code, data related to project management (for example, user stories, milestones, and performance metrics), and top-line spending data.

### 9.2 Data Rights and Ownership of Deliverables

It is 18F's intent that any data or deliverable created as a result of the work performed under the task order be committed to the public domain.

It is the intention of 18F to commit the following, but not limited to, items to the public domain: all data, documents, graphics and code created under this task order including but not limited to, plans, reports, schedules, schemas, metadata, architecture designs, and the like; new open source software created by the contractor and forks or branches of current open source software where the contractor has made a modification; new tooling, scripting configuration management, infrastructure as code, or any other final changes or edits to successfully deploy or operate the software.

The contractor shall use open source technologies wherever possible, in support of the 18F Source Code Policy. All licenses must be expressly listed in the deliverable. Regardless of license(s) used (e.g., MIT, GPL, Creative Commons 0) the license(s) shall be clearly listed in the documentation.

If the contractor needs to use work that does not have an open source license, the contractor is required to request permission from 18F, in writing, before utilizing that work in any way in connection with the order. If approved, all licenses shall be clearly set forth in a conspicuous place when work is delivered to 18F.

If an open source license provides implementation guidance, the contractor shall ensure compliance with that guidance. If implementation guidance is not available, the contractor shall attach or include the license within the work itself. Examples of this include code comments at the beginning of a file or contained in a license file within a software repository.

### 9.3 Additional FAR Provisions/Clauses Applicable to this Order

FAR 52.203-18 Prohibition on Contracting with Entities that Require Certain Internal Confidentiality Agreements or Statements-Representation (JAN 2017)

FAR 52.203-19 Prohibition on Requiring Certain Internal Confidentiality Agreements or Statements (JAN 2017)

## Attachments to this Solicitation

1. Pricing Template

2. Proposed Quality Assurance Surveillance Plan (QASP)

3. Non-Disclosure Agreement

4. SF1449

 

# APPENDIX

## Potential User stories

### Epic: Allow for more forests to be added to the Special Use permit applications system 

  - As a forest staff member, I want to enter my forest information to enable special use permitting for my forest.

  - As a forest staff member, I want to be able to add and easily edit content so applicants can learn how to and apply to permits on my forest.

  - As a member of the public, I want to easily find the special use permit application for forest(s) I’m interested in, so that I can apply quickly.

  - As a member of the public, I should be able to discover the variety of online permit types available from my preferred forest, so that I understand the range of services provided by the forest I am interested in.

  - As a potential applicant, I would like to know which information is necessary for me to complete for the forest and permit type I'm applying for.

### Epic: User group management 

  - As a forest staff member, I should be able to get appropriate admin privileges to manage my forest’s presence in the ePermit app, so that I can make necessary content changes myself.

  - As a forest administrator, I should be able to enable and revoke special use or special forest product privileges for active Forest Service Employees.

Epic: Ensure modules are production ready from a compliance perspective  
Note: the goal of this epic is to harden our system so that we can get an [<span class="underline">Authority to Operate (ATO)</span>](https://before-you-ship.18f.gov/security/)

  - As a user, I would like to be assured that this system will not compromise my information or data.

  - As a user, I would like my information to be recoverable in the event of a system failure, so that I do not have to restart the application process.

### Epic: Help users submit complete applications with valid data 

  - As a special use admin, I would like to make sure that data is properly displayed in the USFS’s internal and separate special use permit issuing system: the Special Use Data System (SUDS).

  - As an applicant, I would like to ensure that all field types have the proper validation to complete an application.

### Epic: Make application activity transparent to applicants and Special Use Administrators

  - As an applicant, I want to be automatically notified when my permit application is approved, so that I don’t need to contact the Special Use Administrator to know the status of my application.

  - As an applicant, I want to receive a confirmation email after submitting an application, so that I know it’s been submitted successfully.

### Epic: Improve User Experience

Stories will emerge from Forest onboarding and user testing, and may include items like:

  - As an applicant, I want to be able to submit multiple applications without having to retype in my basic info, so that I can save time.

  - As an applicant, I would like to know what personally identifiable information is being collected from me before I submit my application, so that I understand the potential risks.

  - As a temporary outfitter applicant I would like to understand more clearly whose name and email should be entered in the temp outfitter permit application, so that I can log back in to retrieve my application.

### Epic: Ensure that Special Use Administrators’ ePermit reporting needs are met

  - This includes generative research to discover what unique ePermit reporting needs exist and whether we can meet them using existing reporting capabilities (i.e. SUDS).

  - Research findings will inform additional stories

Please note: additional epics and stories will result from onboarding new forests, user research, usability tests, and feedback from real end-users once the system is in production.
