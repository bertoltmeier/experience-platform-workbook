# Adobe I/O + Adobe Experience Platform Workshop

- Dates: Oct 30, 2018 - Nov 8, 2018 (Various Sites, EMEA), Dec 3-7, 2018 (NYC, Chicago)
- Participants: Adobe Solutions Consultants, Adobe Partners
- Instructors: Sarah Xu (saxu@adobe.com), Simon Mac Donald (smacdona@adobe.com), Ryan Dumlao (dumlao@adobe.com)

### Overview

This workshop is intended to cover the following topics

- Adobe Experience Platform overview and use cases
- Getting set up on and using Adobe Experience Platform
- XDM (Experience Data Model) data schema
- Data ingestion (APIs and UI)
- Data lookup, processing querying
- Dataset visualization in Experience Platform UI
- Unified Profile, Segment Builder, accessing profile points via API

### Story

A company running a business in Retail or Hospitality can use Adobe Experience Cloud products for a variety of reasons. One of those use cases applicable to these verticals is that of a customer loyalty program. This would include creating a "basis profile" for a specific company's customer, using identifiable information including full name, contact information, and other details. This profile would then serve as a base point to tie additional unique data including transaction history, loyalty program eligibility and status, as well as behavioral data such as online browsing habits to drive promotions and other actions.

Having this "basis profile" established in the Adobe Experience Platform, using a Unified Profile, will give the company the ability to tie multiple sources of data from Experience Cloud products as well as external products built with connections into the Adobe Experience Platform. This will help the company understand a full 360-degree view of each of their customers.

The scope of this Adobe I/O workshop covers a portion of this story, that of establishing a basis profile for a company's customers, either through batch ingestion or connector ingestion, in order to begin the foundation for a customer loyalty program built on Adobe Experience Platform.

### Scope

We will cover Profile XDM data ingestion, lookup and segmenting in the frame of a customer loyalty program.

### Goals

After completion of this workshop. you should be able to:

- Define and select an XDM Schema
- Ingest sample data in XDM format into Adobe Experience Platform
- Segment profiles created in the Unified Profile Service based off ingested data
- Understand what can be done with XDM data and Unified Profiles

#### Workshop info & Credentials

Please note that these credentials and IDs are only accessible for today

| Workshop info                    |               |
| -------------------------------- | ------------- |
| Workshop Organization            | xxxx          |
| Org ID                           | xxxx@AdobeOrg |
| Experience Platform access token | xxxx          |

#### Resources to download

- [Experience Platform API Postman Collection](/postman/ExperiencePlatform.postman_collection.json)
- [Experience Platform API Postman Environment](/postman/ExperiencePlatform.postman_environment.json)
- Sample Profile XDM Data
  - [ProfileData.parquet](/data/ProfileDataSample.parquet)
- [Link to Adobe Experience Platform sign-in page](https://platform.adobe.com)

#### Chapters

- Chapter 0 - [Before you start: Pre-Authorization](/chapters/chapter-0.md)
- Chapter 1 - [XDM and Experience Platform Overview](/chapters/chapter-1.md)
- Chapter 2 - [Login and Accessing with Postman](/chapters/chapter-2.md)
- Chapter 3 - [Define the Schema](/chapters/chapter-3.md)
- Chapter 4 - [Ingest the Data](/chapters/chapter-4.md)
- Chapter 5 - [Segment the Data](/chapters/chapter-5.md)
- Chapter 6 - [Integration and Connector Examples](/chapters/chapter-6.md)
