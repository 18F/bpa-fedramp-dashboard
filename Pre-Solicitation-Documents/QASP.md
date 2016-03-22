# Performance Based Quality Assurance Surveillance Plan For FedRAMP Dashboard Platform Support
### Client Order ID Number: ID09160019

## INTRODUCTION

This Quality Assurance Surveillance Plan (QASP) has been developed to evaluate contractor actions while implementing the Performance Work Statement (PWS). It is designed to provide an effective surveillance method of monitoring contractor performance for each listed objective on the Performance Requirements Matrix in the task order. The QASP provides a systematic method to evaluate the services the contractor is required to furnish.

The contractor, and not the Government, is responsible for management and quality control actions to meet the terms of the task order. The role of the Government is quality assurance to ensure task order standards are achieved.

## ROLES AND RESPONSIBILITIES

Refer to PWS Attachment 2 for Government Roles and Responsibilities.

## PERFORMANCE REQUIREMENTS MATRIX

**Note that the performance requirements listed below are required for the final deliverable.  However, the sprints and incremental delivery of code will be assessed by the Government to ensure that the contractor is on a path to successful final delivery.**

Deliverable or Required Services | Performance Standard(s) | Acceptable Quality Level (AQL)| Method of Surveillance
------------------------|-------------------------------|-----------------------|-------------------
Tested Code	| Code delivered under the order must have substantial test code coverage and a clean code base	| Minimum 90% test coverage and Code Climate of 3	| https://codeclimate.com
Accessible |	Client-side rendering must comply with section 508 standards	| Meets 508 Standards |	http://squizlabs.github.io/HTML_CodeSniffer/
Deployed	| Code must successfully build and deploy into staging environment.	| Successful build | CloudFoundry logs
Documented |	All dependencies (and licenses for dependencies) are listed and all major functions are documented. | All Javascript libraries are listed and the licenses are documented. Software/source code is documented.| Combination of manual review and automatic testing

## SURVEILLANCE

The Government will evaluate the performance objectives through surveillance as reflected above by reviews and acceptance of work products and services.  As indicated, the Government will assess progress towards the final delivered software code.

## STANDARD

The Contractor shall perform all work required in a satisfactory manner in accordance with the requirements of the PWS. The COR shall notify the CO for appropriate action if it is likely that the contractor will not achieve successful final delivery of the software code in accordance with the performance objectives and acceptable AQLs identified above.

## PROCEDURES

The COR will inspect all tasks required by the task order to ensure Contractor compliance with the task order requirements every two (2) weeks. Inspection results will be recorded in a via GitHub issue, noting the date, time, and result of inspection or verification.  

At the conclusion of each sprint, the COR, along with the 18F Product Manager, will review the completed user stories and related functionality. Incomplete or inadequate code and user stories will be flagged via GitHub issue, and links to each issue shared with the Procurement PM and CO. Contractor may respond via Github issue as appropriate, addressing the accuracy and validity of the defect, planned corrective action (if not already noted). The vendor team will discuss and document actions to prevent recurrence in their bi-weekly sprint retrospectives.

At the conclusion of the period of performance, a similar procedure will be followed to document discrepancies and to assess overall performance.

If any of the services do not conform to the task order requirements, the Government may require the Contractor to perform the services again in conformity with task order requirements. The Contractor must correct the defect(s) within the timeframes established in the PWS. The COR shall not certify satisfactory performance for the task order until all defects have been corrected.

When the defects in services cannot be corrected by re-performance, the Government may:

1)	Require the Contractor to take necessary action to ensure that future performance conforms to task order requirements; and,

2)	Reduce the task order price to reflect the reduced value of the services performed.

The COR shall, in addition to providing documentation to the Procurement PM/CO, maintain a complete quality assurance file. The file will contain copies of all reports, evaluations, recommendations, and any actions relating to the Government’s performance of the quality assurance function, including originals of all surveillance activity checklists. All such records will be retained for the life of the task order. The COR shall forward these records to the Procurement PM/CO at completion or termination of the task order.

## ACCEPTANCE OF SERVICES

Acceptance of services shall be based upon compliance with performance standards described in the PWS and surveillance procedures described in this QASP. Before approving/certifying any Contractor invoices, the COR will verify that all invoiced services have been performed in compliance with task order requirements. The COR shall not certify satisfactory performance for the task order until all defects have been corrected.
