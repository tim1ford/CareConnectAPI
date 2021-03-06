---
title: Release Notes
keywords: development, versioning
tags: [development]
sidebar: overview_sidebar
permalink: overview_release_notes.html
summary: Summary release notes of the versions released in Care Connect API Implementation Guide
---

{% include important.html content="This site is under active development by NHS Digital on behalf of INTEROPen and is intended to provide all the technical resources you need to successfully develop the Care Connect APIs. This project is being developed using an agile methodology so iterative updates to content will be added on a regular basis." %}

## 2.1.0-alpha.0 ##

Added
  - New Design/Reference Implementation/Security Quickstart 

Changed
  - Redesigned Design/Reference Implementation/Security to be clearer
  - Case Study/UHS with latest input from UHS on continued development
  

## 2.0.0-alpha.1 ##

Changed
  - Corrected hover states in enagement approach image

## 2.0.0-alpha.0 ##

Added
  - Design & Build / Design / Get Record

Changed
  - Design & Build - story and linking to reflect current structure of pages
  - Minor updates throughout the pages for spelling and improvements
  - Corrections to engagement image hove states
  
## 1.9.0-alpha.0 ##

Changed
  - Removed code search option from MedicationRequest
  - Added medication search option to medicationRequest
  - code search option in Medication changed from MAY to SHALL
  - medication search option in MedicationRequest changed from MAY to SHALL
  - Medication links to Care Connect Reference Implementation changed to code search.
  - Links for updated for new STU3 profiled resources.
  - Links for other CareConnect profiles moved from test server to HL7 UK DSTU2.

## 1.8.0-alpha.0 ##

Added
  - Reference Implementation / Security
  - Reference Implementation / Security Scopes

Changed
  - Release to 4 from 3 throughout
  - Design / Access with RI links and description of use
  - Design / Security with RI links and description of use
  - Design / Exchange patterns with RI links
  - Design / Patterns / Topology with RI links and description of example of pattern
  - R4 diagram from R3
  - Fixed security challenges
  - Updated tables for correct formatting throughout


## 1.7.0-alpha.0 ##

Added
  - Reference Implementation / develop
  - Reference Implementation / install
  - Reference Implementation / install glossary
  - Images to explain Reference Implementation

Changed
  - Links to apilabs@nhs.uk for contact information
  - Version to Release for consistency of message
  - Release 3 for Reference Implementation
  - External links for Reference Implementation


## 1.6.0-alpha.0 ##

Added
  - Practioner Role
  - Reference Implementation section describing the RI

Changed
  - Updated explore or resources section to STU3.
  - Took snapshot of STU3 profiles and added them to the build and referenced them
  - Updated UI where found inconsistencies
  - Added placeholder for RI
  - Updated way that STU3 links are updated to be consistent amongst profiles and easier to extend

## 1.5.0-alpha.0 ##

Changed
  - Minor changes

## 1.4.0-alpha.0 ##

Changed
  - Minor changes

## 1.3.0-alpha.0 ##

Added
  - UHS Proof of Concept - Workflow (Orders)

Updated
  - Updated UHS Proof of Concept - Diagnostics
  - Updated Exchange Patterns

## 1.2.0-alpha.0 ##

Updated
  - Improved links to GP Connect sites from Exchange Patterns page.
  - Improved links to GP Connect sites from Exchange Patterns page.

## 1.1.0-alpha.0 ##

Updated
  - Added developer notes on University Hospital Southampton use case.

Changed
  - FAQ as a inconsistency was spotted

## 1.0.0-alpha.0 ##

Updated
  - Profile section to engage
  - Change of page titles under explore section and page names. Now reflect purpose rather than design stage.
  - Removed lower level headings from the table of contents on the profiles page

## 0.9.0-alpha.0 ##

Updated
  - Explore section renamed Resources
  - Profile references to Resources
  - Engage section renamed Case Studies

## 0.8.0-alpha.0 ##

Updated
  - Altered search parameters page
  - Corrected section for observations
  - Updated Bristol POC with most recent content
  - Corrected typos

## 0.7.0-alpha.0 ##

Updated
  - Spelling mistakes and general checking throughout the site
  - Links in navigation menu's
  - Consistency of styles
  - Menu structure to be easier to see and clearer
  - Styles to fix accessibility and viewability issues found in the the guide


## 0.6.0-alpha.0 ##

Added
  - Initial sections of University Hospital Southampton POC included
  - Added section on how [search parameters](search_parameters.html) were selected
  - Added core Care Connect API [prerequisites](explore.html)

Updated
  - Updates to Bristol Connecting Care POC (user stories)
  - Corrections to the glossary
  - Corrected broken links in the engagement approach
  - Removed national NHS Number guidance
  - Corrected menu linking
  - Provide APIs diagrams throughout
  - Colour scheme of diagrams from feedback
  - Altered Accept http header notes
  - Moved xml and code examples to gitHub gist
  - Converted markdown to html tables for better display of parameters
  - Updated API search combinations (conformance requirements)

## 0.5.0-alpha.0 ##

Added
- Community and FHIR Tools sections to Help & Support sections
- Diagram to support the engagement process
- Foundation API definitions
- Profile links to HL7 UK FHIR Reference Server (test version)

Updated
- Communication Channels (Help & Support) revised to reference the Care Connect Inbox and the INTEROpen website.
- Clinical API definitions
- Individuals and Entities API definitions
- Workflow API definitions
- All Explore section pages to similar layout
- Communication Channels (Help & Support) revised to reference the Care Connect Inbox and the INTEROpen website
- Corrected some styling issues
- Design & Build section template added as a process
- Test section example added of end to end process
- Assure section added to provide overview of end to end process
- Deploy section added to provide overview of end to end process
- Major changes to underlying folder structure to support use and updating of information
- Conformance profile updates to current alpha state
- Glossary
- Provide APIs with a clickable diagram used throughout later stages
- Linking to developer.nhs.uk
- Engagement approach with look and feel and linking


## 0.4.0-alpha.0 ##

Added
- Description of providing an API process
- Standard definition of a API definition
- Started Test explanation section
- Engagement Process
- Bristol Connecting Care Case Study

Defined Patient definition adding :
- References section - starting to link to user stories
- HTTP headers
- Response codes - Also added a non exhaustive API Codes page to describe all of the codes
- Search parameters - added section to include guidance on how a search can happen in practice localised on the NHS

Multiple updates to glossary

Restructured 'Engage' navigation to rationalise content showing the engagement process and case studies. Pages explaining what user stories are and how we use them have been moved off the sidebar to be accessed within the pages as necessary.

## 0.3.0-alpha.0 ##

Examples resources conforming to the CareConnect Profiles

Mandatory and optional API Parameters defined for the following resources
  - Clinical    
   - AllergyIntollerance
    - Condition
    - Immunization
    - Medication
    - MediationOrder
    - MedicationStatement
    - Observation
- Identification
    - Location
    - Organization
    - Patient
    - Practitioner
- Workflow
    - Encounter
(please comment via https://interopen.ryver.com or email careconnect@interopen.org)

Engage
- Added Overview explanation
- Added Michael's Stories showing the example user stories
- Linked Michael's Stories to APIs currently available and defined above
