# Data.gov PMO

Please submit any questions as [an Issue](https://github.com/18F/tts-buy-datagov-pmo/issues) in this repository by *November XX, 2017 at 1:00pm EST*. The Contracting Officer will only be responding to questions submitted using the [Issue Template](ISSUE_TEMPLATE.md). Comments from other parties or in other formats will still be considered but we cannot commit to responding to them.

**Proposals are due by November XX, 2017 at 1:00pm EST.**

## Background

Data.gov is the home of the U.S. Government’s open data. Users can find Federal, state and local data, tools, and resources to conduct research, build applications, design data visualizations, and more. The Data.gov Program Management Office is part of the Data and Analytics Portfolio of the Office of Products and Programs, a component of the Technology Transformation Services (TTS), at the U.S. General Services Administration (GSA). 

Data.gov seeks technical services support to continuously develop the Data.gov application, expand Data.gov capabilities, modernize the Data.gov infrastructure and provide general development, operations, and infrastructure support required to maintain Data.gov’s website(s). 

**The main components of Data.gov are:**
Data.gov Homepage (WordPress)
- Catalog.Data.gov (CKAN) 
   - [CKAN](http://ckan.org/) is a python web application and is the leading open source, open data catalog platform. The Data.gov catalog harvests data inventories maintained by agencies in a data.json format and is updated on a daily basis. Harvest sources can be found at federal agency website /data.json (ex. https://gsa.gov/data.json)
- Inventory.data.gov (CKAN)
   - A separate, private CKAN instance used by several federal agencies to manage and update their metadata (i.e. data.json files) which are then downloaded and hosted on the websites of those agencies.
- Project Open Data Dashboard (PHP web application)
   - [Dashboard](https://labs.data.gov/dashboard) for measuring open data progress by agencies per Office of Management and Budget (OMB) Directive M-13-13. It also provides a number of lightweight converters and validators and serves as the location for support tools provided by Data.gov for agencies.
- Data.gov Help Desk (PHP Web Application)
   - Serves as a lightweight customer relationship management (CRM) tool to manage dataset problems and requests.
- Federation.data.gov (Jekyll based static website)
   - Code is hosted at http://github.com/GSA/us-data-federation, static web files are generated by Jekyll and Jekyll-rebuilder and hosted by a single webserver and served as pre-compiled html pages. 

Data.gov is currently hosted in the Amazon Web Services (AWS) Cloud Infrastructure managed by the Business Services Platform (BSP), a program within GSA’s Federal Acquisition Service (FAS). 

The system involves a variety of open source applications. Currently, the list of open source software components consists of an Ubuntu 14.04 Center for Internet Security (CIS) Hardened Baseline Image, Apache and Nginx, Wordpress (CMS for www.data.gov), MySQL RDS (database for Wordpress and PHP applications), CKAN (Comprehensive Knowledge Archive Network - web-based open source data management system for the storage and distribution of data), PostgreSQL RDS (back-end database for CKAN), OpenSSL and Let’s Encrypt (SSL and TLS protocol cryptographic functionality), PHP (custom CodeIgniter applications for the Dashboard and Help Desk), and Python (used for CKAN). 
 
**Additional background on Data.gov:**
- [Open Data Policy](https://project-open-data.cio.gov/policy-memo/) - requires agencies to maintain data inventories following specified metadata, that is harvested by the Data.gov catalog
- [Project Open Data](https://project-open-data.cio.gov/) - additional guidance and metadata standards
- [Data.gov Repository](https://github.com/GSA/data.gov) - for Data.gov software, issue tracker for Data.gov, open to the public. In addition, the following GitHub repositories represent current and future Data.gov work and list specific technologies required:

   - https://github.com/GSA/CKAN
   - https://github.com/GSA/ckanext-datagovtheme
   - https://github.com/GSA/ckanext-datajson
   - https://github.com/GSA/ckanext-geodatagov
   - https://github.com/GSA/datagov-custom
   - https://github.com/GSA/datagov-deploy
   - https://github.com/GSA/datagov-wp-boilerplate
   - https://github.com/GSA/enterprise-data-inventory
   - https://github.com/GSA/open311-simple-crm
   - https://github.com/GSA/sdg-indicators
   - https://github.com/GSA/us-data-federation

- [Guide](http://www.digitalgov.gov/resources/how-to-get-your-open-data-on-data-gov/) for agencies explaining how data gets added to Data.gov
- [Guide](http://www.digitalgov.gov/resources/inventory-data-gov-guide/) to inventory.data.gov, the separate instance of CKAN maintained by Data.gov to support metadata management needs of agencies
 
The prose content on Data.gov is managed using the WordPress CMS. Data.gov contains updates about the latest developments in open data; the impact of government open data, applications developed using open data, as well as a number of specific Topic pages with curated content and datasets. The Data.gov catalog (catalog.data.gov), based on CKAN, harvests the data inventories maintained by the Federal agencies pursuant to the Open Data Policy to provide a continuously updated, comprehensive metadata catalog of Federal open data assets.
 
The Data.gov catalog also has a significant relationship to geoplatform.gov and the federal geospatial community, as the same catalog powers both Data.gov and geoplatform.gov. There is substantial technical coordination with the Federal geospatial community, including working with geospatial-specific metadata standards to ensure proper harvesting into the Data.gov and geoplatform.gov of numerous geospatial data sources.

### What we're hoping to end up with

Additional information is provided in Sections 1, 3, and 4 of the RFQ, but in short:

> Data.gov seeks technical services support to continuously develop the Data.gov application, expand Data.gov capabilities, modernize the Data.gov infrastructure and provide general development, operations, and infrastructure support required to maintain Data.gov’s website(s). 

### How to respond

Additional information is provided in the Section of the RFQ titled `INSTRUCTIONS, CONDITIONS, AND NOTICES TO OFFERORS`:

> The following introductory information is required on the cover page of the RFQ response: 
> a. RFQ Number and Title, 
> b. Name and address of vendor, 
> c. DUNS and CAGE number, 
> d. GSA/FSS # and expiration date 
> e. Name, telephone number and e-mail address of main point-of-contact, 
> f. Total proposed price (including all options), 
> g. Date of submission, and 
> h. Name, title and signature of authorized representative.
> 
> Quotation shall be formatted for viewing/printing using 8.5 by 11-inch paper size, single sided, and in electronic pdf format. Information provided in the quotation shall be concise, specific, and complete. Quotation must be valid for at least 60 days after quotation response date. The technical quotation must be included in a separate document from the price quotation to facilitate an independent evaluation. 
> 
> Vendors shall direct all communications to the Contracting Officer (CO) identified in submission section. Communications with other officials may compromise the competitiveness of this acquisition and result in removal of the vendor from award consideration or cancellation of this requirement. 

### Period of performance

Additional information is provided in Section 8 of the RFQ, but in short:

> The task order period of performance shall be one base year from the date of award with two option periods of up to 12 months each. Work to complete the tasks will commence upon award with approval by the Data.gov PMO and the Contracting Officer.

## Contents

1. [Statement of Work (SOW)](solicitation_documents/SOW.pdf)

## Contributing

See [CONTRIBUTING](CONTRIBUTING.md) for additional information.

## Public domain

This project is in the worldwide [public domain](LICENSE.md). As stated in [CONTRIBUTING](CONTRIBUTING.md):

> This project is in the public domain within the United States, and copyright and related rights in the work worldwide are waived through the [CC0 1.0 Universal public domain dedication](https://creativecommons.org/publicdomain/zero/1.0/).
>
> All contributions to this project will be released under the CC0 dedication. By submitting a pull request, you are agreeing to comply with this waiver of copyright interest.
