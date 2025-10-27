**Standard Operating Procedure (SOP) for Managing Data**

 

Version: 1.0

Effective Date: \<Insert Date\>

Approved By: \<Approver Name / Position\>

 

Revision History

| Version | Date Approved | Revisions |
| :---- | :---- | :---- |
| 1.0 | YYYY-MM-DD | Initial Publication |
|   |   |   |

# **Purpose**

The purpose of this SOP is to provide clear and consistent procedures for managing research data across the lifecycle of a project. By following these instructions, researchers ensure that their data are collected, documented, stored, preserved, and shared according to best practices, as well as in compliance with institutional, funder, and ethical requirements.

# **Scope**

This SOP applies to all research projects carried out by \<Research Team Name or Department\>, regardless of funding source. It covers any activity involving the collection, creation, storage, preservation, or sharing of research data, including numeric data, text documents, images, audio, video, and code.

# **Responsibilities**

The Principal Investigator (\<Principal Investigator Name\>) holds ultimate responsibility for compliance with this SOP and for ensuring that the project’s Data Management Plan (DMP) is maintained. All research team members are required to follow the procedures outlined here in their assigned tasks.

 

The Principal Investigator has named \<Data Manager Name\> who will be responsible for maintaining project documentation, coordinating data backups, and preparing data for deposit in trusted repositories.

# **Procedures**

## **Data Collection**

Data should be created or exported into open, preservation-friendly file types whenever possible. Recommended formats include CSV for tabular data, TXT for text, and TIFF for images. If proprietary software is used, such as SPSS or MATLAB, an additional copy must be exported into a widely used open format to ensure long-term accessibility.

 

## **Data Analysis**

Scripted analysis provides benefits compared to point-and-click analysis by enhancing reproducibility, transparency, and efficiency in data workflows. Scripts can be rerun from the beginning, allowing researchers to adjust parameters, update datasets, and refine methods without manually repeating each step—ensuring consistent and traceable results.

 

All scripts for analysis will be versioned and stored in relevant folders associated with the project. Analysis scripts should also be uploaded to the projects GitHub Repository: \<GitHub repository\>

 

Consider following the [TIER protocol](https://www.projecttier.org/tier-protocol/protocol-4-0/) for analysis file structure.

 

## **File Naming and Organization**

Establish a clear and consistent file organization system for storing your data. Start by creating a main folder for the research project, and within it, create subfolders to categorize different types of data, such as raw data, processed data, experimental protocols, and analysis scripts. Include subfolders for relevant literature, presentations, and manuscripts.

 

Incorporate the following project 3 letter code(s) in naming all folders and files.

 

\<XXX\> \- \<Project name\>

\<XXX\> \- \<Project name\>

\<XXX\> \- \<Project name\>

…

 

Recommended file naming convention:

 

\<XXX\>*\_*\<YYYY-MM-DD\>*\_\<ResearcherInitials\>\_\<details\>\_*\<*version*\>

 

\<XXX\>: The project three letter code

\<YYYY-MM-DD\>: The date the file was created or updated, using the ISO standard year-month-day format.

\<ResearcherInitials\>: The initials of the person who created or modified the file.

\<details\>: optional, short, relevant information such as the experiment name, sample ID, instrument, variables etc.

\<version\> Optional version identifiers v01, v02 etc. if relevant.

 

### **Raw Data**

*Never write over your raw data with cleaned or analyzed data.*

All raw data collected during the project must remain untouched and stored in a dedicated folder. This folder should be clearly labeled: \<XXX\>\_\<YYYY-MM-DD\>\_\<*ResearcherInitials\>\_*RawData*\_\<details\>*. Subfolders may be created to separate data by source, instrument, or collection period, but the original files must never be modified, renamed, or deleted.

Researchers performing data analysis must make a copy of the raw data and place it in their own folder structure. All processing, cleaning, or transformations must be done only on these copies.

To ensure clarity and reproducibility:

\-          The raw data folder is the authoritative source and must remain unchanged.

\-          Analysis folders should include notes or a README file documenting any processing steps.

\-          All team members must follow this procedure to prevent accidental corruption or loss of the original dataset.

\-          This process preserves raw data in its original state while allowing team members to perform analyses safely.

### **Files that Cannot or Should not be Renamed**

 

Some research files are created automatically by instruments, machines, or specialized software, and these files often cannot be renamed without breaking compatibility or disrupting automated processing. When this occurs, files must be placed into clearly labeled project folders rather than being renamed individually. Project folders should follow the standard naming convention: \<XXX\>*\_*\<YYYY-MM-DD\>*\_\<ResearcherInitials\>\_\<details\>\_*\<*version*\>.

Subfolders may be created to separate files by instrument, experiment, or date of collection.

 

## **Documentation and Metadata**

### **Readme**

Where appropriate, add a readme file (\<XXX-readme.txt\>) to each folder which describes the content.  Write the readme file in plaintext and divide your readme into logical sections to help with navigation.

 

At a minimum include the following general information in your readme.txt

Title: \<Content/Data Title\>

Principal Investigator: \<Principal Investigator\>

Creator(s): \<Creator name\>

Date Created: \<YYYY-MM-DD or date range\>

Description: \<Brief description of folder contents and purpose\>

Licenses or limitations: \<Description of any limitations or licenses placed on the data\>

Location: \<Location\>

 

In addition, you may wish to include:

\-          A list of folder contents

\-          File types and associated programs

\-          References to lab books or other external related information

\-          Methodologies and instruments

\-          Related data schemas

\-          Definitions for any variables or abbreviations used

 

Maintaining a well-organized file structure and comprehensive documentation will save you time and effort in the long run. It enables efficient data retrieval, promotes collaboration, and enhances the reproducibility and integrity of your research.

 

### **Data Descriptions (Schemas)**

For tabular datasets create a data schema which describes features about each column of data. Machine- and human-readable schemas can be generated at [www.semanticengine.org](http://www.semanticengine.org).

Store data schemas in appropriate folders, either within the folders containing data or, when used by multiple experiments and researchers, in the shared lab data storage.

 

## **Storage and Backup**

During the duration of the project, active research data (raw and processed) will be stored following the 3-2-1 Backup method:

* 3 Copies of Data  
   Maintain three total copies of your data:  
  * One primary working copy used for active research.  
  * Two backup copies to safeguard against data loss.  
* 2 Different Storage Media  
   Store the data on at least two different types of media, such as:  
  * Local hard drive or institutional server.  
  * External hard drive, USB device, or cloud storage. This reduces the risk of simultaneous failure due to hardware or software issues.  
* 1 Off-Site Location  
   Ensure that at least one backup copy is stored off-site, outside your lab or institution.  
  * This protects against local disasters (e.g., fire, theft, flooding).  
  * Off-site options include secure cloud services or institutional backup systems.

Implementation Notes

* Backups should be updated regularly and verified for integrity.  
* Sensitive data must be encrypted before off-site or cloud storage.  
* Document the backup schedule and storage locations in your data management plan.

 

Following the completion of the project, or at significant points (such as publication) research data will be deposited in suitable archival repositories including:

 

Borealis (institutional repository)

FigShare

GenBank

\<Repository Name\>

…

 

which provides long-term preservation services. Data will be prepared for deposit by anonymizing sensitive information, converting to open formats (ex, CSV, TXT, TIFF), and verifying file integrity with checksums. Upon deposit, the repository will issue a persistent identifier (DOI), which will be cited in all publications and final reports.

