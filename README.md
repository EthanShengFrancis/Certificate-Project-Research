# Certificate-Project-Research
To look into Certificate promoted on Instagram and gain insights on what is most popular


Tasks to complete:
1) Initiate a master list of certificates to look into based off instagram reels recommendation
2) Store accounts and certificates into a google sheet
3) Update google sheet in repo for version control
4) Establish a format for each table and update accordingly


1. Data Gathering/Research (20 people)
- Use instagram reels that specifically had a message feature that returns a link/resource. The resource should lead to a collection of certificates that the reel recommends.
- If a person does not give any resource on it, the reel will be disregarded as many resources given as handed through automation. Therefore, resources that are given appear to be too long for automation to be included anymore.

2. Data Formatting (Format the names and links)
- Formatted the main ceritficate track record list to reference to a table for Accounts and a table for Certificates.
- The Certificates should have details on Fees, Length and Standarised Naming of Certificates and Links.
- The decision was done to allow for easier linking between tables and reduce cluster on the eye as multiple records of the same certificates will be found present in the Master Table.
- Modularity can be done by checking if a new entry is compared with an existing certificates in the Certificate table. Link checking can be done and will allow for easier excess.

3. Data Cleaning (Clean any data that may be wrong or NA)
- Data Cleaning was done by checking each link to a standarised link that leads to the certificate.
- Multiple rows were deleted due to lack of information or misleading links.
- Data checking will be done with the new format in order to keep links or names from being misleading.

4. Data Normalisation
- The data was organised into separate tables for Master records, Accounts and Certificates. The Master table records individual certificate discoveries, while the Certificates table stores the standardised information of each unique certificate. The Accounts table maintains information about the sources from which the resources were collected.

- Repeated certificates discovered through different Instagram accounts were linked to a single record in the Certificates table instead of duplicating details such as the standardised name, provider, fee and duration across multiple records. This reduces unnecessary repetition while preserving each individual discovery in the Master table.

- Each certificate was assigned a unique Certificate ID, which acts as a reference between the Master and Certificates tables. This allows multiple discoveries of the same certificate to be associated with one standardised record, while retaining their original names, source accounts and discovered links.

- Standardised certificate names, links and categories were maintained in the Certificates table to minimise inconsistencies caused by different naming conventions. When a certificate's verified details need to be updated, the centralised record can be revised without manually changing every associated discovery.

- Certificate IDs and lookup formulas were used to connect related records and retrieve standardised information, such as certificate focus areas. Unmatched IDs and uncertain duplicates can be flagged for manual review to reduce incorrect associations between records.

5. Data Visualisation