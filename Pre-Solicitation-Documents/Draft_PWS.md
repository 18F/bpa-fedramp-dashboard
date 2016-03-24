# 1.0 BACKGROUND

The Federal Risk and Authorization Management Program, or FedRAMP, is a government-wide program that provides a standardized approach to security assessment, authorization, and continuous monitoring for cloud hosting products and services.

The objective of FedRAMP is to standardize and streamline the process for Cloud Service Providers (CSPs) to become compliant with government IT rules and regulations, and thereby make it easier for individual agencies to acquire secure, compliant cloud services. This certification process ultimately saves time, money, and effort, as agencies no longer need to individually go through the arduous process of security-certifying these solutions.

There are a number of different user groups connected to and invested in the FedRAMP process, including the FedRAMP team itself, CSPs, Federal Agencies, and Office of Management and Budget (OMB).  Currently, it is difficult for the external users (CSPs, agencies, OMB) to understand what stage CSPs are in the certification process, making it difficult to plan, make decisions, and check compliance. Additionally, the private information increases the FedRAMP team’s burden to manually respond and field these inquiries.

The Government believes that building a publicly available, web-based dashboard that provides greater visibility and up to date status for vendors going through the FedRAMP certification process, will yield a variety of positive outcomes, including increased transparency and monitoring, improved decision-making and prioritization abilities, reduced effort in compliance activities, among others.  The prioritized target users that should benefit from a dashboard include agencies (specific roles within agencies), the FedRAMP team, and OMB, and to a lesser extent the CSPs themselves.

# 2.0	OBJECTIVES

FedRAMP’s business goals for the dashboard include:
* Decreased customer service burden on FedRAMP: decreased user contacts/status checks, increased self-service
* Ability to perform data-driven planning, prioritizing, decision-making
* Provide FedRAMP and OMB with a better overall view of agency compliance and vendor status in the certification pipeline
* Reduced effort in reporting compliance and status to other parties (e.g. OMB, IGs, other agencies)
The anticipated benefits of a dashboard for other users (e.g. Agencies, OMB) should include:
* Easier monitoring of certification compliance
* Increased visibility and comprehension of  where CSPs are in the certification process (more specific, obvious and up to date status)
* Facilitate decision-making for agencies about what services to pursue, and when to pursue them.
* Easier for agencies to see which vendors are coming through the pipeline
* Easier to discover which vendors are available to buy from
* Easier to understand what services vendors are offering
* Easier to understand and compare what services/vendors are being used by other agencies
* Easier to contact vendors who are in the certification process
* Increased discoverability of information about the FedRAMP program
* Ability to download and work with the FedRAMP data
* Easier auditing and compliance self-checking

# 3.0	SCOPE

The scope of this task order is for the Contractor to deliver the public beta launch of the FedRAMP dashboard. The backend data and script will be provided.
The following 4 sections of the PWS describe the technical and administrative components of the requirement:
* Tasks the vendor must perform (Section 4).
* Task requirements that describe to the vendor specifics about how the vendor performs the tasks in Section 4 (Section 5).
* Other/Administrative requirements such as type of contract, period of performance, etc. that are more contract-orientated as opposed to requirement focused (Section 6).
* Invoicing Instructions (Section 7).

# 4.0	REQUIREMENTS

The Contractor shall provide the following services:
* Contractor shall build a static public site, that will provide client-side rendering of the dashboard (preferably via JavaScript), based on a flat file (csv/json) accessible through the GitHub Application Program Interface (API).  A template of the data format of the data can be found in this Github Repository and sample data is available here. The static-site must be deployable through a single bash command. All files will be stored statically (server-side) and all dynamic interaction will be enabled in the browser (client-side).
* Contractor shall build print friendly layout of pages for reporting of FedRAMP process and participants.
* Contractor shall review user research and conduct additional user research in order to provide data views that are most useful.

Additional requirements:
* Contractor shall use US Web Design Standards.
* All software code delivered under this order shall comply with the 18F open-source policy in effect as of the date of award: https://github.com/18F/open-source-policy.
* All software code delivered under this order shall comply with the 18F accessibility guidelines in effect as of the date of award: https://pages.18f.gov/accessibility/.
* As part of this being purchased off of the Agile Blanket Purchase Agreement (BPA), work will be conducted in two week sprints and reviewed at the end of each sprint for acceptability before moving on.

## Note the following tasks are not required:
Vendor will not be required to handle any of the following tasks:
* Provide or configure hosting of the data or the site
* Provide form functionality for data-entry of FedRAMP data
* Directly create, update, or delete the data

# 5.0	OPERATIONAL REQUIREMENTS

## 5.1 	Project Management

The contractor shall provide a Project Manager point of contact for the government’s program office for problem resolution, Program Management reporting in accordance with Program Management methodologies, and staffing requirements. Sprint plans will be developed collaboratively with the Product Owner and 18F.

As per Agile Development requirements, the Contracting Officer’s Representative (COR) and contractor will be expected to work with the Product Owner (as determined by 18F and FedRAMP), and an 18F Product Manager. Refer to Attachment 2, for Government Roles and Responsibilities.

## 5.2	Impact Reports

The contractor shall be responsible for providing notification to the COR, 18F Product Manager, and Product Owner when activities or issues outside of the contractor’s control, which directly impact the contractor’s performance.  This notification shall be provided in writing or via email within 24 hours of the anticipated or known impact.

## 5.3	Status Reports

In lieu of a typical status report, the following are required to document progress over the course of the period of performance for each sprint:

*	Links to the Github branch
*	Screenshots of any available visualization (as appropriate)
*	Screenshot, links, or other documentation from the contractor’s project management system reflecting completed features, including number and percentage of completed sprint tasks (e.g. percentage of tasks completed)
*	Access to the contractor’s project management tool to view development status

## 5.4	Daily Operations

Daily operations will be managed by the Contractor’s Project Manager, but coordinated to and communicated with the 18F Product Manager. They may include:

*	Daily standup via video
*	Chat operations via Slack
*	Manage and update user stories + workflow tasks in shared project management platform

## 5.5 	Transition

### 5.5.1	Transition Plan

The Contractor shall:

a)	Ensure and agree that all deliverables, products, licenses, designs, data, documentation, tests, user research notes, source code, configuration settings and files, and materials developed throughout this task order will be the property of the U.S. Government and in the public domain.

b)	Two weeks prior to task order conclusion, provide a brief Transition Plan for all deliverables, products, and materials in coordination with the COR, 18F Product Manager and Product Owner from GSA.

c)	Coordinate with the COR and potentially another vendor, and implement the Transition Plan according to the COR’s direction.

d)	Provide assistance to the COR, 18F Product Manager, and potentially other Government staff to stand-up the application.

### 5.5.2	Transition Activities

During the transition to the Government and/or a new contractor, the Contractor shall perform all necessary transition activities, including, but not limited to, continued full services to 18F and other customers; participation, at discretion of COR, meetings with the Government or new contractor to effect a smooth transition and provide detailed information on the operation of all deliverables; training of new personnel (contractor or Government) during transition period, appropriate close-out of outstanding technical and related work.

Final report shall include list of sprint tasks completed, documentation, and link to code repository developed for 18F. Should the Contractor be terminated prior to the end of the period of performance, the Contractor shall transfer all project materials to the COR within two weeks of the COR’s request.

## 5.6 	Deliverables

Table 1 List of Deliverables

Required Deliverables/Reports	Required | Due Date | Description of Deliverable Content
---------------------------------------|----------|------------------------------------
Status Report | 1 business day after every sprint	| A report of progress throughout the sprint
Code repository for product | End of task order | Version controlled open source repository of code that comprises dashboard
Development Prototype | End of second sprint, and every sprint thereafter	| In-progress development prototype, accessible on the web via a staging/development server
Working Dashboard of FedRamp Cloud Service Providers | End of task order | 	
Transition Plan	| 3 business days after conclusion of the second-to-last sprint	| See 5.5.1

### 5.6.1	Delivery Instructions

Code deliverables shall be submitted via the Github repository. A copy of any document deliverables shall be submitted to the COR, Product Owner, and 18F Product Manager, and uploaded to the AASBS (Assisted Acquisition Services Business System) web portal. Refer to Section 6.11 for additional information on the AASBS web portal.

### 5.6.2	Inspection and Acceptance of Services

All periodic reports and task deliverables shall be inspected, tested (where applicable), reviewed, and accepted by the Government within 10 days of the conclusion of each sprint.

Only the COR, and their designated alternate, has the authority to inspect, accept, or reject all deliverables. Final acceptance of all deliverables will be provided in writing, or in electronic format, to the contractor, from COR, within 30 days from the end of the task order.

Performance by the Contractor to correct defects found by the Government as a result of quality assurance surveillance and by the Contractor as a result of quality control, shall be in accordance with FAR 52.246-4, Inspection – Firm Fixed Price. The COR will monitor compliance and report to the Procurement Project Manager.

### 5.6.3	System Documentation

The Contractor shall consult with the COR to determine what is appropriate, effective, and essential for system documentation. The Government requires, at a minimum, that the contractor will generate comprehensive and complete documentation, both within the code itself, within the source code version control system (e.g., through proper use of descriptive commit messages, issue tracking, pull requests, etc.), and as appropriate, in separate documentation, provide artifacts, and create new user stories based on each sprint.

### 5.6.4. Quality Assurance

The Government intends to utilize the attached Quality Assurance Surveillance Plan (QASP) to monitor the quality of the Contractor’s performance.  The oversight provided for in the QASP will help to ensure that service levels reach and maintain the required levels throughout the contract term.  Further, the QASP provides the COR with a proactive way to avoid unacceptable or deficient performance, and provides verifiable input for the required Past Performance Information Assessments.  The QASP is a living document and may be updated by the Government as necessary. Any updates to the QASP will be provided to the Contractor.

## 5.7	Personnel

### 5.7.1. Desired Skills and Knowledge

The contractor shall provide personnel at the skill levels with the requisite knowledge and experience commensurate with the description in the applicable Government Contract to accomplish the tasks as delineated in this PWS.  

Contractor personnel shall have:

*	A strong technical background in the following:
	- Building a static site that can be deployed with a single run script.
- Using one or more front-end JavaScript frameworks to build a front-end of a website.
- Incorporating data from a publically hosted JSON or CSV flat file into a website front-end via a client-side request.
*	Ability to utilize existing design and user experience assets from US Web Design Standards.
*	Programming fluency in JavaScript, Hypertext Text Markdown Language (HTML), Cascading Style Sheets (CSS) or HTML and/or JavaScript templating language.

### 5.7.2 Key Personnel

The following requirements related to personnel must be met:

a)	The Contractor shall assign to perform this task order those persons whose résumés are submitted with its quotation and who are identified in the Contractor’s quotation as Key Personnel. All contractor employees assigned to perform this task order will be Key Personnel.

b)	If an individual proposed as Key Personnel becomes unavailable during the course of the source selection process, the Offeror will notify the Contracting Officer immediately and provide a substitute and their résumé. The proposal of any Key Personnel not currently employed by the Offeror shall be accompanied by letters of intent signed by the proposed Key Personnel indicating their intent to be employed by the Offeror team if the Offeror is awarded a task order under this RFQ.

c)	The Contractor agrees that during the duration of the task order performance, no Key Personnel substitutions will be made unless necessitated by an individual’s sudden illness, death, or termination of employment. In any of these events, the Contractor shall promptly notify the COR and provide the information required by paragraph (e) below on the proposed replacement for Government approval. No substitutions of Key Personnel shall be made except in accordance with this provision.

d)	All requests for substitutions/additions of Key Personnel must include a detailed explanation of the circumstances necessitating the proposed substitution or addition, a complete résumé for the proposed substitute or addition including skills, experience, education, training, and security level. As determined by the Contracting Officer, all proposed substitutes/additions must have qualifications that meet or exceed the qualifications of the person to be replaced.

e)	The Contracting Officer or his/her COR will evaluate the request(s) for substitutions/additions of Key Personnel and the Contracting Officer will notify the Contractor, in writing, of approval or disapproval. Disapproval of the proposed individual(s) shall not provide grounds for nonperformance by the Contractor or form the basis of any claim for monies, delivery schedule extension, or any other equitable adjustment.

f)	At a minimum, a Project Manager must be identified and designated as Key Personnel. The Project Manager will be a direct liaison to the COR, 18F’s Project Manager, and the FedRAMP Product Owner.  The Project Manager is responsible for the supervision and management of the Contractor’s personnel, technical assistance, and interface. Desired skills/experience for the Project Manager include:

*	Experience in technical leadership.
*	Ability to rapidly prioritize competing requirements.
*	Ability to understand and simplify customer requirements.
*	Ability to communicate end user feedback to technical and design leads.
*	Strong communication skills.
*	Proven knowledge of industry standards.

### 5.7.3 Estimated Level Of Effort

The Government estimates this project will require no more than 4-5 personnel - though not all will be needed on a full time basis. Contractors are encouraged to use their own estimating methodology to determine the skill mix and level of effort necessary to complete this work.

## 5.8	Travel

No travel is anticipated or will be required as part of this task order.

## 5.9	Additional Considerations

## 5.9.1	Potential Organizational Conflicts of Interest

Offerors shall provide a signed Organizational Conflict of Interest statement with their quotation submission, if applicable, which describes concisely all relevant facts concerning any past, present, or planned interest (financial, contractual, organizational, or otherwise) relating to the work to be performed under the proposed task order and bearing on whether the Offeror has a possible organizational or personnel conflict of interest with respect to:

1.	Being able to render impartial, technically sound, and objective assistance or advice, or
2.	Being given an unfair competitive advantage.

The Offeror may also provide relevant facts that show how its organizational structure and/or management systems limit its knowledge of possible organizational conflicts of interest relating to other divisions or sections of the organization and how that structure or system would avoid or mitigate such organizational conflict.

No task order award shall be made until any potential conflict of interest has been neutralized or mitigated to the satisfaction of the Contracting Officer. The contractor shall notify the Contracting Officer in writing as soon as any conflict of interest is identified and will propose steps for mitigating the conflict.

Refusal to provide the requested information or the willful misrepresentation of any relevant information by an Offeror shall disqualify the Offeror from further consideration for award of a task order under this solicitation.

If the Contracting Officer determines that a potential conflict can be avoided, effectively mitigated, or otherwise resolved through the inclusion of a special contract clause, the terms of the clause will be subject to negotiation.

# 6.0	OTHER REQUIREMENTS

## 6.1	Type of Contract

This is a Firm Fixed Price order using the Agile BPA terms and conditions.  

## 6.2	Period of Performance (POP)

The period performance for this task order is delivery of the final product 60 calendar days after the Post Award Conference. The Period of Performance begins on the date of the Post Award Conference and ends 60 calendar days after the Post Award Conference.

## 6.3	Place and Hours of Performance

The primary place of performance will be at the contractor’s facility. Work may be performed at GSA Headquarters at 1800 F St. NW, Washington, DC, and Alternate Sites.  18F is a distributed team.

Business core hours shall be 0900 to 1800 local time, Monday – Friday on Government scheduled work days. The contractor may set its own work hours except that the contractor shall be available for technical contact by the Government between the hours of 0900 and 1800 local time on Government work days.

## 6.4	Special Terms and Conditions

### 6.4.1	Section 508 Compliance Requirements

The contractor shall support the Government in its conformance with Section 508 throughout the development and implementation of the work to be performed. Section 508 of the Rehabilitation Act of 1973, as amended (29 U.S.C. 794d) requires that when Federal agencies develop, procure, maintain, or use electronic information technology, Federal employees with disabilities have access to and use of information and data that is comparable to the access and use by Federal employees who do not have disabilities, unless an undue burden would be imposed on the agency. Section 508 also requires that individuals with disabilities, who are members of the public seeking information or services from a Federal agency, have access to and use of information and data that is comparable to that provided to the public who are not individuals with disabilities, unless an undue burden would be imposed on the agency.  The following standard is applicable for compliance: 1194.22 Web-based Intranet and Internet Information and Applications.

The contractor should review the following websites for additional 508 information: http://www.section508.gov/index.cfm?FuseAction=Content&ID=12
http://www.access-board.gov/508.htm

http://www.w3.org/WAI/Resources

## 6.5	Post Award Orientation Conference

The FedRAMP team, Contracting Officer, and COR shall hold a Kick-Off meeting/Post-Award Conference in Washington, DC or virtually with contractor’s team and other relevant Government staff to review and clarify the project’s objectives, expectations from the Government, and address any questions the Contractor may have.  Discussion topics shall include, but not be limited to: introduction of the Contractor and Government Staff; understanding of the workflow; project management expectations; agreement on communication methods; and discussion of specific needs.

The Kick-Off meeting/Post-Award Conference will take place within 10 days from award.

## 6.6	Non-Personal Services

This task order is not being used to procure personal services prohibited by FAR 37.104, Personal services contract.

To counter the circumstances that infer personal services and to preserve the non-personal nature of the contract, the contractor shall adhere to the following guidelines in the performance of the task:

*	Contractor provides for direct supervision of all contract employees assigned to the task.
*	Refrain from discussing the issues such as skill levels and hours, salaries, cost and funding data, or administrative and personnel matters affecting contractor employees with the client.
*	Ensure close communication/coordination with the Procurement Project Manager, reporting problems to the Procurement Project Manager as they occur (not waiting for a monthly meeting).
*	Do not permit government officials to interview potential contractor employees, discuss individual performance, approve leave or work scheduling of contractor employees, terminate contractor employees, assist contractor employees in doing their jobs or obtain assistance from the contractor in doing Government job.
*	Do not assign contractor personnel to work under direct government supervision.
*	Maintain a professional distance from government employees.
*	Provide contractor employees with badges, if appropriate, identifying them as contractors.
*	Ensure proper communications with the government (technical discussion and government surveillance is okay, but the Government cannot tell the contractor how to do the job).
*	Assign a task leader to the task order. The task leader or alternate should be the only one who accepts tasking from the assigned Government point of contact or alternative.
*	The government has the right to reject the finished product or result and this does not constitute personal services.
*	When travel is required for the performance on a task, the contractor personnel are only to travel as directed by their contract management.

## 6.7	Privacy Act

Work on this project may require that personnel have access to Privacy Information. Personnel shall adhere to the Privacy Act, Title 5 of the U.S. Code, Section 552a and applicable agency rules and regulations.

## 6.8	Government Furnished Items

The Government will furnish the data and scripts needed at time of award. No other hardware or software will be provided by the Government.

## 6.9	18F Transparency Policy

Vendors are advised that 18F will publish on a publicly available website documents associated with this requirement, including any Requests for Quotation (including amendments), Question and Answer exchanges with vendors (source-identifying information removed), and other relevant information that is not confidential/proprietary in nature or source selection sensitive information that would otherwise implicate procurement integrity concerns. Upon award, 18F will publish the total price of the selected proposal and certain non-source-identifying data (e.g., the number of bids, the mean price, median, and standard deviation of price). During the performance of this task order, 18F will similarly publish source code, data related to project management (e.g., user stories, milestones, and performance metrics), and top-line spending data.

## 6.10  Data Rights and Ownership of Deliverables

It is 18F's intent that any data or deliverable created as a result of the work performed under the task order be committed to the public domain.

It is the intention of 18F to commit the following, but not limited to, items to the public domain: all data, documents, graphics and code created under this task order including but not limited to, plans, reports, schedules, schemas, metadata, architecture designs, and the like; new open source software created by the contractor and forks or branches of current open source software where the contractor has made a modification; new tooling, scripting configuration management, infrastructure as code, or any other final changes or edits to successfully deploy or operate the software.

The contractor shall use open source technologies wherever possible, in support of the 18F Source Code Policy. All licenses must be expressly listed in the deliverable. Regardless of license(s) used (e.g., MIT, GPL, Creative Commons 0) the license(s) shall be clearly listed in the documentation.

If the contractor needs to use work that does not have an open source license, the contractor is required to request permission from 18F, in writing, before utilizing that work in any way in connection with the order. If approved, all licenses shall be clearly set forth in a conspicuous place when work is delivered to 18F.

If an open source license provides implementation guidance, the contractor shall ensure compliance with that guidance. If implementation guidance is not available, the contractor shall attach or include the license within the work itself. Examples of this include code comments at the beginning of a file or contained in a license file within a software repository.

## 6.11	GSA AAS Business Systems (AASBS) Web Portal

The GSA AASBS (Assisted Acquisition Services Business Systems also known as IT Solutions Shop (ITSS)) web portal will be accessible to the contractor during the performance of the task order and be used in the administration of the task order. This web-based system at https://portal.fas.gsa.gov/web/guest shall be used by the contractor to upload status reports, deliverables, invoices, and to respond to inquiries. The contractor shall maintain a current account on this system.

## 6.12	Contract Administration

The following Points of Contact (POC) are applicable to this order:

Contracting Officer Representative (COR):
Esther Kim
GSA, Office of Citizen Services and Innovative Technologies (OCSIT) - 18F
esther.kim@gsa.gov
(202) 826-7232

Alternative Contracting Officer Representative (ACOR):
Joshua Bailes
GSA, Office of Citizen Services and Innovative Technologies (OCSIT) - 18F
joshua.bailes@gsa.gov
(202) 550-6659

18F Product Manager
Jessie Posilkin
GSA, Office of Citizen Services and Innovative Technologies (OCSIT) - 18F
jessie.posilkin@gsa.gov
(202) 406-4689

GSA FedRamp Product Owner:

To Be Determined

GSA Procurement Project Manager:
Kit Lee
GSA, Assisted Acquisition Services (AAS)
kit.lee@gsa.gov
(415) 436-8730

GSA Contracting Officer:
Lynda Luo
GSA, Acquisition Operations Division
lynda.luo@gsa.gov
(415) 522-4633

# 7.0	INVOICING/ PROCEDURES FOR PAYMENT

The period of performance for each invoice shall be for one calendar month. The contractor shall submit only one invoice per month per order/contract.

NOTE: The Government reserves the right to audit, thus; the contractor shall keep on file all backup support documentation for travels as applicable.

## 7.1	Content of Invoice

The contractor’s invoice will be submitted monthly for work performed the prior month. The contractor may invoice only for the hours, travel and unique services used in direct support of the task order. The invoice shall be submitted on official letterhead and shall include the following information at a minimum.

*	Client Order ID Number
*	ACT Number
*	Prompt Payment Discount
*	Remittance Address
*	Period of Performance for Billing Period
*	Point of Contact and Phone Number
*	Invoice Amount
*	Skill Level Name and Associated Skill Level Number (for T&M or Labor Hour)
*	Actual Hours Worked During the Billing Period (for T&M or Labor Hour)
*	Clearly indicate both the current invoice’s monthly “burn rate” and the total average monthly “burn rate” (for T&M or Labor Hour)
*	Travel Itemized by Individual and Trip (if applicable)
*	Supporting documentation for travel including travel approval and receipts (if applicable)

## 7.2	Invoice Submission

All invoicing shall be done electronically. Password and electronic invoice access may be obtained through the AASBS web portal. The Invoice and the Status Reports for the applicable billing period shall be entered into the AASBS portal within 5 to 10 calendar days after the end of the month. The contractor shall submit invoices electronically by logging into the AASBS portal (https://portal.fas.gsa.gov), navigating to the appropriate order, and creating the invoice for that order and attach a copy of invoice, status reports with all required back-up documentation as applicable. The contractor shall NOT submit any invoices directly to the GSA Finance Center (neither by mail nor via electronic submission). If the invoices are acceptable, then the Procurement Project Manager and COR will approve them for payment and complete the information in the AASBS portal.

## 7.3	Final Invoice

Invoices for final payment must be so identified and submitted within 60 calendar days from task completion and no further charges are to be billed. A copy of the written acceptance of task completion must be attached to final invoices. The contractor shall request for an extension from the COR for final invoices that may exceed the 60-day time frame.

The Government reserves the right to require certification by a COR before payment is processed, if necessary.

## 7.4	Close-out Procedures

The contractor shall submit a final invoice within 60 calendar days after the end of the performance period. After the final invoice has been paid the contractor shall furnish a completed and signed Release of Claims (GSA Form 1142) to the Contracting Officer. This release of claims is due within 15 calendar days of final payment.


 Attachment: QASP
