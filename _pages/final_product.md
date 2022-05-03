---
layout: page
title:  "Final Product"
---

### The Final Design

In response to the Data Services Team request for assistance, DataTrackers created a product that will assist the city of Pittsburgh&rsquo;s Data Services Team as well as city departments in meeting compliance guidelines. DataTrackers produced a Visual Basic macro, a newsletter template and accompanying procedures for Data Services and Data Coordinators. These products will address the problem of non-compliance by creating an easy method for departments to evaluate and publish a data inventory as it pertains to the city's Open Data Ordinance.  
Other deliverables DataTrackers considered for production were procedures outlining the publication of open data on the Western PA Regional Data Center (WPRDC). We decided against that because the Data Services Team assumes that responsibility and did not need guidance for that task. DataTrackers also considered creating a website application for entering and updating data inventories and sharing datasets.  However, we discovered during our meetings that the Data Services Team already has a SharePoint site where they house this information, and a website would be redundant.

Our final product consists of the following major components:

**Data Services Procedures**

The Data Services Procedures provide step-by-step instructions for conducting Data Governance Health Status Checks. Users of this document should have a basic understanding of Pittsburgh&rsquo;s Open Data Ordinance. These procedures provide a detailed breakdown of the steps involved in tracking progress toward compliance with the Open Data Ordinance, identifying data inventory records that need attention, and conducting Health Status Checks meetings.

**Tracking and Summary Tables**

The _Tracking and Summary Tables_ reflect Pittsburgh city departments&rsquo; overall compliance with the Open Data Ordinance. They summarize city-wide and departmental participation in needs assessments and brainstorming sessions, progress with data inventorying and identifying top 10 Right to Know (RTK) requests, and other key metrics of the Open Data Ordinance. This component is accompanied by user documentation for the Data Services Team: _User Guide: Tracking and Summary Tables_, which describes the structure, variables, and values of each table and which tables and values to update. 

**Critical Records Program**

The _Critical Records Program_ is a Visual Basic macro designed to prevent data loss from data inventories. The macro discovers data inventory records that are overdue, due, or due soon for updates or that have missing, invalid, or illogical data. Reports will be shared by the Data Services Team at Data Governance Health Status Checks meetings. Basic computer skills are all that is required to run the program. Familiarity with Visual Basic for Applications or a reasonable comfort level with programming in general is required to modify the program. This component is accompanied by user documentation for the Data Services Team: _User Guide: Critical Records Program_.

**Data Coordinator Procedures**

The _Data Coordinators Procedures_ describe the process of preparing for and participating in Data Governance Health Status Checks. This document is a summary of the steps necessary for data coordinators to complete and update data inventories and follow good data management practices, which are required for compliance with the Open Data Ordinance. 

**Prioritizing Data Publication**

The _Prioritizing Data Publication_ document provides information to assist data coordinators in establishing initial priorities for selecting datasets to add to the data inventory as well as for open data publication.

**Health Status Checks Newsletter Template**

The _Health Status Checks Newsletter Template_ is a PowerPoint file with space for reporting progress to data coordinators and other stakeholders. The file can be edited as needed. This component is accompanied by user documentation for data coordinators: _User Guide: Newsletter_. The document provides an overview of the newsletter structure and describes the four major sections: &lsquo;News,&rsquo; &lsquo;Featured Department,&rsquo; &lsquo;Summary Tables,&rsquo; and &lsquo;Critical Records Tables.&rsquo; The subsequent components of the guide go into further detail for each newsletter section, including detailed descriptions of what the summary table values represent and how to interpret the critical records tables. A description for how Data Services selects a &lsquo;Featured Department&rsquo; is also provided.

All documents listed above&ndash;Data Services Procedures, Data Coordinator Procedures, and Prioritizing Data Publication&ndash;and the user guides that accompany the other components are included in the Data Governance Health Status Checks Handbook, which is organized as follows:

* Data Services Procedures
* <a href="https://lisaover.github.io/DataGovHealthStatusChecks/Documents/User_Guide_Tracking_and_Summary_Tables.pdf" target="_blank">User Guide: Tracking and Summary Tables</a>
* <a href="https://lisaover.github.io/DataGovHealthStatusChecks/Documents/User_Guide_Critical_Records_Program.pdf" target="_blank">User Guide: Critical Records Program</a>
* Data Coordinator Artifacts:

  * Data Coordinator Procedures
  * <a href="https://lisaover.github.io/DataGovHealthStatusChecks/Documents/Prioritizing_Data_Publication.pdf" target="_blank">Prioritizing Data Publication</a>
  * <a href="https://lisaover.github.io/DataGovHealthStatusChecks/Documents/User_Guide_Newsletter.pdf" target="_blank">User Guide: Newsletter </a>

 The complete handbook is not available to review at this time. The City of Pittsburgh has not yet publicized the Data Services or Data Coordinator procedures.

### Transition Plan

**Data Services Procedures**

The first major component of our documentation is the Data Services Procedures. This document provides a high-level overview of the five major steps necessary for the Data Services team to carry out Data Governance Health Status Checks. The document begins with a brief overview of its scope and a description of the checks followed by detailed descriptions of or instructions for each step. Users from the Data Services team should at least have a basic understanding of Pittsburgh&lsquo;s Open Data Ordinance, as well as a familiarity with related Data Services open data documentation and engagement sessions to perform these procedures. 

**Tracking and Summary Tables**

The _Tracking and Summary Tables_ represent a snapshot of the city&lsquo;s overall compliance with the Open Data Ordinance and will be updated by the Data Services Team and shared with department data coordinators in the newsletter. Data Services should consult this guide when inputting and updating tracking and summary data and data steward information. Users from the Data Services Team should at least have a basic understanding of Pittsburgh&lsquo;s Open Data Ordinance, as well as a familiarity with related Data Services open data documentation and engagement sessions. A basic grasp of Microsoft Excel is also helpful for understanding the summary calculations. Overall, the guide should deliver the necessary support for Data Services to update tracking and summary data.

The _User Guide: Tracking and Summary Tables_ begins with a brief description of the purpose and scope of the tables and the guide itself. The guide also provides a table that describes the four primary sheets in the _Tracking and Summary.xlsx_ file: &rsquo;City,&lsquo; &rsquo;Department,&lsquo; &rsquo;Data,&lsquo; and &rsquo;Data Stewards.&lsquo; The &rsquo;City&lsquo; and &rsquo;Department&lsquo; sheets are composed of variables that automatically summarize the information in the &rsquo;Data&lsquo; and &rsquo;Data Stewards&lsquo; sheets.
The next two sections of the guide include instructions for updating the two sheets which require manual data entry by the Data Services Team: &rsquo;Data&lsquo; and &rsquo;Data Stewards.&lsquo;  The section for updating the &rsquo;Data&lsquo; sheet includes a table that defines each variable in the sheet and designates the variables as a particular Type: user populated text, user populated count, and calculated, which are also defined. The final section of this guide is a brief description of the &rsquo;Data Stewards&lsquo; sheet, and instructions for updating the variables.

**Critical Records Program**

Concern regarding data loss from the data inventories inspired the _Critical Records Program_ component of this product. The large number of expected datasets with different update dates and update frequencies will be very difficult to maintain manually. The Critical Records Program is designed to alleviate this concern by discovering data inventory records that are overdue, due, or due soon for updates or that have missing, invalid, or illogical data. 

The _Critical Records Program_ reads data inventory records from multiple data inventory files to discover and write critical records to a report. Critical records are records that have one or more of the following health status notifications:

* Records are &rsquo;Public&lsquo; but &rsquo;Not yet open&lsquo;
* Restricted or Private records that do not have a &rsquo;Public&lsquo; record in the data inventory
* Records are overdue for updates
* Records are due for updates
* Records should be updated soon
* Missing or invalid data in one or more of the following critical fields:

  * Date Created/Imported
  * Internal Priority
  * Update Frequency
  * Date Updated
  * Data Classification
  * Sensitivity Rating
  * Public Status

Invalid values include any values that do not match one of the values accepted for a given field or that are not dates in a date field, and this includes values with minor typographical errors or inconsistent capitalization. The _Critical Records Program_ assigns a health status to each critical record to alert users about what needs to be done to maintain the data inventory record and resolve the health status notifications for it.

The Data Services Team will run the Critical Records Program before each Data Governance Health Status Checks meeting. They will be able to compare the current report to past reports to verify that past health status notifications were resolved, and they will distribute new or unresolved health status notifications to data coordinators for resolution.

The _User Guide: Critical Records Program_ provides instructions for running and modifying certain aspects of the program. Basic computer skills are all that is required to run the program. The only necessary change to the code is the source path and target path constants, which need to be values that reference the user&lsquo;s computer or network. Other modifications require familiarity with Visual Basic for Applications or a reasonable comfort level with programming in general, but these modifications are not required to run and benefit from the program. The program code is also extensively documented for reference. The program code is extensively documented for reference. 
The user guide provides the following information about the program:

* ***Data Inventory*** This section describes the features of the data inventory that were implemented both to assist users in data entry and to minimize the number of critical records that arise due to invalid data. It also describes the protocol for naming datasets and explains how the program references data inventory columns in case these specifications need to be changed.
* ***Prepare to Run the Critical Records Program*** This section describes the steps that need to be taken or considered before running the program.
* ***Run the Critical Records Program*** This section provides steps for running the program and accessing the critical records report.
* ***Due Dates, Update Windows, and Level of Criticality Assignment*** This section explains how the program calculates the date update is due and the update due windows, which are used to distinguish between records that are due versus due soon for updating. It also describes the level of criticality assignments and what data inventory record characteristics are used to assign a record to a particular level. Finally, this section provides instructions for modifying how the program calculates the update due date, update due windows, and level of criticality assignment.
* ***Modify the Program Code*** This section provides steps for opening the Visual Basic Editor and outlines the changes that might be necessary. This step requires familiarity with Visual Basic for Applications or a reasonable comfort level with programming.

**Data Coordinator Procedures**

The Data Coordinator Procedures is a summary of the major steps necessary for City of Pittsburgh department data coordinators to prepare for and participate in Data Governance Health Status Checks. These procedures outline what each Pittsburgh department must do to comply with the city&lsquo;s Open Data Ordinance and to follow good data management practices by completing a data inventory of all datasets used by the department. Meaningful engagement with these procedures requires data coordinators to first have a good understanding of the Open Data Ordinance and to attend the City of Pittsburgh Data Governance Engagement Sessions. The Data Coordinator Procedures is critical to the success of the Data Governance Health Status Checks and Open Data Ordinance project. This document should be updated to reflect changes in the project with respect to completing and submitting data inventories or to resolve any confusion that might arise when data coordinators start to use it. There are no technical functions or specifications to maintain or update this document, so there are no transitional instructions to provide other than to review and update this document as needed. 

**Prioritizing Data Publication**

The Prioritizing Data Publication document will assist data coordinators in establishing initial priorities for selecting datasets for the data inventory and for open data publication. To benefit from the guidance this document provides, data coordinators must first have a good understanding of the Open Data Ordinance and attend the City of Pittsburgh Data Governance Engagement Sessions. The Prioritizing Data Publication is the first resource data coordinators are given to help them determine which datasets are high priority and which are low priority with respect to adding them to the data inventory. This document should be updated to reflect changes in the project with respect to prioritizing datasets or to resolve any confusion that might arise when data coordinators start to use it. There are no technical functions or specifications to maintain or update this document, so there are no transitional instructions to provide other than to review and update this document as needed. These guidelines were developed in accordance with the open data guidelines from the Sunlight Foundation.

**Health Status Checks Newsletter Template**

Data Services will distribute newsletters to department data coordinators on a regular basis that feature news relating to Pittsburgh&lsquo;s open data efforts, as well as department and city-wide progress towards compliance. The _User Guide: Newsletter_ includes descriptions for each segment of the newsletter and its associated tables. Like the other user guides, a basic understanding of the Open Data Ordinance is required to use this guide.

The document begins with an overview of the newsletter structure, describing the four major sections: &rsquo;News,&lsquo; &rsquo;Featured Department,&lsquo; &rsquo;Summary Tables,&lsquo; and &rsquo;Critical Records Tables.&lsquo; The subsequent components of the guide go into further detail for each newsletter section. The &rsquo;News and Featured Department&lsquo; component provides descriptions for the type of information that is highlighted in the first page of the newsletter, such as announcements and events regarding Open Data in the city. A description for how Data Services should select a &rsquo;Featured Department&lsquo; are also provided.

The &rsquo;Summary Tables&lsquo; and &rsquo;Critical Records Tables&lsquo; components of the guide describe the scope, purpose, and variables for each table to assist data coordinators and other users with interpreting the information on the tables. The &rsquo;Summary Tables&lsquo; are broken down by &rsquo;City&lsquo; and &rsquo;Department&lsquo; tables, which have unique summary information relating to overall open data progress. The &rsquo;Critical Records Tables&lsquo; provide definitions for headings relating to the Critical Records, which help inform data coordinators about the health of the datasets in their data inventories.

### Conclusion

Throughout the design process, our group strived to create a process and tools that would promote sustained effort in updating data inventories. The scope of the product from the prototype to the final release has not changed, however, some additions and adjustments have been made to meet the needs and expectations of our partner. All documentation is now accessible in one handbook with a section for data coordinators that can be printed to PDF and distributed to them by the Data Services Team. The names of city departments were added to the Tracking and Summary Tables, and formulas were adjusted to account for the additional rows. Data validation for departments was incorporated into the Tracking and Summary Tables and additional data validation was added to the data inventory. The update overdue, due, and due soon calculations in the Critical Records Program were adjusted to be more understandable from a human perspective and the new functionality was documented in the respective user guide.

Challenges that our partner may encounter as they implement the Data Governance Health Status Checks include resistance by data coordinators to engage with the process and problems with the technical components of the product, the _Tracking and Summary Tables_ and _Critical Records Program_, when real data is used or when changes in the process require changes to the formulas or Visual Basic code. To mitigate data coordinator resistance, we recommend setting reasonable goals for the number of datasets a department must identify and document between Data Governance Health Status Checks meetings. To resolve problems that arise with the Tracking and Summary Tables, the Data Services Team should involve people who have familiarity with Excel tables and formulas. Our understanding is that the team has sufficient access to people who know Excel. To resolve problems with or change functionality of the _Critical Records Program_, the Data Services Team should involve people who are familiar with Visual Basic for Applications (VBA) or who are comfortable with programming in general. Our understanding is that there is at least one person on the team who is familiar with VBA. The user guides that accompany these technical components will be helpful in interpreting their outputs as well as in understanding their purpose and functionality. The User Guide: Critical Records Program provides detailed explanations of different features of the program that will help anyone tasked with modifying the code. The VBA macro is also well documented.

Our partner is pleased with our work and has already started using the Tracking and Summary Tables. They mentioned that the Data Coordinator Procedures will be an important document as data coordinators work toward compliance with the Open Data Ordinance. They also answered the question posed at the beginning of this project, &ldquo;Where are the dog licenses?&rdquo; Dog licenses are managed by the Finance Department. The idea behind this question was that without good data management practices and open data, the city and stakeholders do not know what data they have, where data are located, or who manages the data. We trust that the process and tools we developed will serve as a foundation for the city to achieve their goal of consistent updating of data inventories that will lead to knowing where all the data are. As they move forward and become informed by their experiences, they can build on what we started to improve the process and tools to meet their needs.