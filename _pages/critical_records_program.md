---
layout: page
title:  "Critical Records Program"
---

Concern regarding data loss from the data inventories inspired the Critical Records Program component of this product. The large number of expected datasets with different update dates and update frequencies will be very difficult to maintain manually. The _Critical Records Program_ is designed to alleviate this concern by discovering data inventory records that are overdue, due, or due soon for updates or that have missing, invalid, or illogical data.

<img src="https://lisaover.github.io/DataGovHealthStatusChecks/Images/Critical_Records_Report_Description.png" width="700" height="371" alt="Important data inventory records" />

<a href="https://lisaover.github.io/DataGovHealthStatusChecks/Documents/User_Guide_Critical_Records_Program.pdf" target="_blank">User Guide: Critical Records Program</a>

The <a href="https://lisaover.github.io/DataGovHealthStatusChecks/Documents/User_Guide_Newsletter.pdf" target="_blank">User Guide: Newsletter </a> provides information on interpreting the critical records report tables.

The _Critical Records Program_ reads data inventory records from multiple data inventory files to discover and write critical records to a report. See section 5.4.3.3 Field Descriptions for a summary of each field in the critical records report. Critical records are records that have one or more of the following health status notifications:

*  Records are &lsquo;Public&rsquo; but &lsquo;Not yet open&rsquo;
*  Restricted or Private records that do not have a &lsquo;Public&rsquo; record in the data inventory
*  Records are overdue for updates
*  Records are due for updates
*  Records should be updated soon
*  Missing or invalid data in one or more of the following critical fields:
  * Date Created/Imported
  * Internal Priority
  * Update Frequency
  * Date Updated <sup>&#8224;</sup>
  * Data Classification
  * Sensitivity Rating
  * Public Status

Invalid values include any values that do not match one of the values accepted for a given field or that are not dates in a date field, and this includes values with minor typographical errors or inconsistent capitalization. 

Any data inventory record could appear more than once as a record in the critical records report. For example, a dataset that is overdue for updates and that is missing data in the Data Classification column will have two entries in the critical records report. The Critical Records Program assigns a health status to each critical record to alert users about what needs to be done to maintain the data inventory record and resolve the health status notifications for it. See section 5.4.3.2 Health Status Descriptions for more information on the health status classifications assigned by the program.

<sup>&#8224;</sup> The Date Updated column in the data inventory is validated for valid date format only, not missingness; this field may be missing if the record has not been updated since it was created/imported.

The critical records report is for reference only. All errors should be resolved directly in the data inventory files. To assist data coordinators in locating the correct data inventory record, the critical records report includes the filename and row number of the record in the Source Filename and Source Row Number columns, respectively. 

### Mission Critical Records

<img src="https://lisaover.github.io/DataGovHealthStatusChecks/Images/Mission_Critical.png" width="700" height="293" alt="Mission critical data inventory records" />

### Vital Records

<img src="https://lisaover.github.io/DataGovHealthStatusChecks/Images/Vital.png" width="700" height="294" alt="Vital data inventory records" />

### Important Records

<img src="https://lisaover.github.io/DataGovHealthStatusChecks/Images/Important.png" width="700" height="289" alt="Important data inventory records" />