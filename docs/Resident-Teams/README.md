---
layout: default
title: Teams and Lab Products
nav_order: 9
personas: 
  - Developer
  - Product Owner
  - Designer
tags:
  - tech
  - stack
  - current
  - graduated
  - teams
description: A list of current and graduated teams, including their tech stacks.
---

# Teams from Across the BC Public Service Learn to be Digital at the Exchange Lab

The Exchange Lab hosts Agile product delivery teams that learn to be digital through experience. Teams of
5-9 people deliver multiple iterative releases of high quality public value products within a year for lower cost
than traditional methods. These high performing teams then continue to support their home organizations
with digital delivery capacity and culture.

We also code in the open.

This is a brief overview of the teams that have come through the Exchange Lab to learn how to work with DevOps methods and tools and as Agile product teams.

<a href="/ExchangeLabOps/Resident-Teams/2019-10-09_2pager_About-Exchange-Lab-teams.pdf" download>Or, download a 2 page PDF version of this content</a>

## Current Teams

[BC Services Card](#bc-services-card) 

[Common Components](#common-components)

[Wildfire](#wildfire)

[Property Inventory Management System (PIMS)](#property-inventory-management-system-pims)

[Verifiable Organizations Network (VON)](#verifiable-organizations-network-von)

[BCDevExchange (Website)](#bcdevchange-website)

[BC Registries](#bc-registries)

[Invasive Species](#invasive-species)

[Greenhouse Gas Industrial Reporting & Control](#greenhouse-gas-industrial-reporting--control)

[Health Gateway](#health-gateway)

[Next Gen Application Security Project](#next-gen-application-security-project)

## Graduated Teams

[BCDevExchange (Procurement Site)](#bcdevexchange-procurement-site)

[Public Review and Comment](#public-review-and-comment)

[Environmental Assessment](#environmental-assessment)

[Mines Digital Service (MDS)](#mines-digital-service-mds)

[MSP Forms](#msp-forms)

[MyRangeBC](#myrangebc)

[Water](#water)

[Transportation Fuel Reporting System](#transportation-fuel-reporting-system)

## Current Teams

### BC Services Card 
Enabling BC Services Card Login. The vision is to make it easier for public organizations to offer the widely-used BC Services Card, a secure and verified government issued identity, as a simple easy-to-use login option for online services`

* [See the code on GitHub]( https://github.com/bcgov/BCSC-SS)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Node, Vue, Vuetify | Python, Flask  | Postgres | OpenShift | | Python, js |

### Common Components
The Common Components team is working on ways to reduce the time and cost of delivering digital products and services. The user-focused team plans to achieve this by making it easy to find, onboard to and use components like code and microservices that solve common problems. Several teams across the BC Public Service are creating reusable digital building blocks that can be used across government and the Common Components team is working to amplify these teams’ important work. Where gaps and unmet needs are found, the team will fill them, seeking wherever possible to reuse components from other jurisdictions or the open source community.

* [See the code on GitHub (wiki)](https://github.com/bcgov/common-components-wiki)
* [See the code on GitHub (openshift project)](https://github.com/bcgov/openshift-launchpad)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| React | Flask  | PostgresSQL | OpenShift command line | | Python, js |


### Wildfire
Wildfire Predictive Services to support decision making in prevention, preparedness, response and recovery.
* [See the code on GitHub](https://github.com/bcgov/wps)
* [See the code on GitHub (Frontend)](https://github.com/bcgov/wps-web)
* [See the code on GitHub (Backend)](https://github.com/bcgov/wps-api)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| React | FastAPI  | PostgresSQL PostGIS | Jenkins | | Python 3, js |

### Property Inventory Management System (PIMS)
The PIMS team is building a system to manage the inventory of BC Government’s titled properties. Including the ability to oversee compliance with Core Policy and Inventory Policies. The app will be based on a geo-spatial platform and will also act as an internal real estate website for re-purposing properties within the public sector.
* [See the code on GitHub](https://github.com/bcgov/pims)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| React Node  | .NET Core 3.1  | MSSQL | Jenkins |  | js, C#, Leaflet |

### Verifiable Organizations Network (VON)
OrgBook BC is a searchable public directory of open verifiable data about organizations legally
registered in BC. BC businesses are now empowered with a locally-issued trusted digital identity
that can be used globally. The Province of BC is leveraging open source decentralized identity
technology and collaborating with global experts to create this new capability.
* [View the app](https://orgbook.gov.bc.ca/en/home)
* [See the code on GitHub](https://github.com/bcgov/von)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Angular, Vue | Django, Node.js  | PostgresSQL | Jenkins | | Python, js |

### BCDevExchange (Website)
The team behind the static website of the Exchange Lab (formerly CSI Lab). 
* [See the code on GitHub](https://github.com/bcgov/bcdevexchange)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Razor ASP.NET | N/A  | N/A | Jenkins | N/A | C#, HTML |

### BC Registries
The ServiceBC team is developing a number of Registry products. The Names Examination
application verifies if a company name is available for use in BC. Cooperatives in B.C. will soon be
able to file reports securely online: a faster, simpler way than the previous paper mail-in process.
The new application will leverage the BC Services Card and PayBC for credit card payments.
* [View the app](https://www.bcregistry.ca/cooperatives)
* [Entity Repos on GitHub](https://github.com/bcgov/entity)
* [Entity Repos on GitHub](https://github.com/bcgov/lear)
* [Entity Repos on GitHub](https://github.com/bcgov/business-filings-ui)
* [Entity Repos on GitHub](https://github.com/bcgov/bcrs-business-create-ui)
* [Entity Repos on GitHub](https://github.com/bcgov/business-schemas)
* [Relationships Repos on GitHub](https://github.com/bcgov/sbc-common-components)
* [Relationships Repos on GitHub](https://github.com/bcgov/sbc-auth)
* [Relationships Repos on GitHub](https://github.com/bcgov/sbc-pay)
* [Name Request Repos on GitHub](https://github.com/bcgov/namerequest)
* [NameX Repos on GitHub](https://github.com/bcgov/namex)
* [NameX Repos on GitHub](https://github.com/bcgov/name-examination)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Vue | Flask, NameX, aiohttp  | PostgresSQL | Jenkins | Nightwatch | TypeScript, Python, js |

### Invasive Species
Conservation is a key outcome for this team building tools to support invasive species
management. The open source code will be a foundation for managing other types of species
and ecosystem data in the future.
* [View the app]()
* [See the code on GitHub](https://github.com/bcgov/lucy-web)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Angular 2, Swift | Express, Node.js  | PostgresSQL | Jenkins | | js, Swift |

### Greenhouse Gas Industrial Reporting & Control
This system is helping the Climate Action Secretariat to better understand the state of industrial
greenhouse gas emissions in the province. Easy data visualization and analysis using open source
tools will help create and support programs to track and reduce industrial emissions in BC. The
team is also building a better experience for industrial reporters to send and view their data.
* [See the code on GitHub](https://github.com/bcgov/cas-ggircs)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| React, Relay, Next.js  | Node.js, GraphQL  | PostgresSQL | CircleCI | | Typescript |

### Health Gateway
The Health Gateway product will empower citizens with access and control over their health
record. It enables a citizen to not only view and act on their health information, but also to
connect it safely and security with third-party health care applications.
* [See the code on GitHub](https://github.com/bcgov/healthgateway)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Vue  | .NETCore  | PostgresSQL | Azure Agent | Selenium | js, c# |

### Next Gen Application Security Project

The Next Gen Security project has an ambitious goal to turn the DevOps Openshift Platform into the most secure application deployment environment in the BC Government. It plans to achieve this by implementing a new ‘Cloud Native’ security model for Platform applications using leading edge technologies and testing it out with real-life application pilots run in collaboration with partner Ministries. The new security model is based on the emerging Zero-Trust model for network security and includes expanding the DevOps toolkit with new tools to increase security on the platform and to reduce the risk profile of Platform applications. Some of the new security capabilities will include real-time container scanning for vulnerabilities, secret management, real-time threat response, security posture dashboard and continuous STRA/PIA compliance check.

* View the project website (Coming Soon)
*  [See the code on GitHub](https://github.com/BCDevOps/platform-services/tree/master/security/aporeto)

## Graduated Teams

### BCDevExchange (Procurement Site)
The team behind the initial creation of the Exchange Lab (formerly CSI Lab), the BCDevExchange
modernizes how government delivers services. They created the flagship apps: "Code With Us" and "Sprint with Us."
This branch of the Office of the Chief Information Officer models a modern Public Service by building & supporting teams that apply the culture, processes, business models and technology of the digital era to solving public challenges.
* [View the app](https://bcdevexchange.org/)
* [See the code on GitHub](https://github.com/BCDevExchange/devex)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Angular | Express, Node.js  | Mongodb | Jenkins | | js, TypeScript |

### Public Review and Comment
Public review and comment is the way the government collects public input on proposed
activities on crown land as part of the decision-making process. The team created a service, now
called the "Application, Comment and Reason for Decision" (ACRFD) app that improved the way
people learn about and provide comments on proposed activities.
* [View the app](https://comment.nrs.gov.bc.ca/applications#splash)
* [See the code on GitHub](https://github.com/bcgov/nrts-prc-public)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Agular | Node.js  | MongoDB | Jenkins | | js, TypeScript |  

### Environmental Assessment
EPIC (EAO Project Information and Collaboration) provides citizens, Indigenous groups and
stakeholders access to centralized information and the ability to participate in and provide
feedback on environmental assessments. The tool also simplifies business processes for staff.
* [View the app](https://projects.eao.gov.bc.ca/)
* [See the code on GitHub](https://github.com/bcgov/eagle-public)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Angular | Express, Node.js  | MongoDB | Jenkins | | js |

### Mines Digital Service (MDS)
This dual team has built scalable, open source, data-driven systems, including a platform for
ministry staff that is intuitive and capable of providing meaningful data. They are also building
a public portal – Minespace – allows mines to self-report electronically.
* [View the BC Mine Information website](http://mines.nrs.gov.bc.ca/) ([github repository](https://github.com/bcgov/mem-mmti-public))
* [View the BC Mine Information website's administrative console](https://mines.empr.gov.bc.ca/) ([github repository](https://github.com/bcgov/mem-admin))
* [Learn about MDS](https://github.com/bcgov/mds)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| React Redux | Pyhton Flask | PostgreSQL | Jenkins | Groovy/GEB | js, Pyton, Groovy |

### MSP Forms
One of the first products to be supported by the BCDevExchange, the MSP application was a
simple solution to a costly problem: a 40% error rate in MSP forms. People seeking health care in
BC experience form errors less than 2% of the time now. The open code for this product was also
reused to produce an application that enables more efficient FOI process.
* [View the app](https://my.gov.bc.ca/msp/application)
* [See the code on GitHub](https://github.com/bcgov/MyGovBC-MSP)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Agular | Node.js  | | Jenkins | | js, TypeScript |

### MyRangeBC
The Range program built an app with the BCDevExchange's Mobile Pathfinder that enables
offline collection and management of data about crown lands used for livestock range. The open
source tool supports sustainable management of herds and the wild plants they rely on.
* [View the app](https://myrangebc.gov.bc.ca/)
* [See the code on GitHub](https://github.com/bcgov/range-web)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| React, Swift | Express, Node.js | PostgreSQL | Jenkins | | js, Swift |

### Water
This team first built Groundwater wells (GWELLS): a registry application for industry, academia,
governments and the general public who submit or use groundwater data and information. The
team is now onto their second product outside of the Exchange Lab: a water information data
visualization service that enables robust and defensible water resource decisions.
* [View the Groundwater Wells app](https://apps.nrs.gov.bc.ca/gwells/)
* [See the code for Groundwater Wells on GitHub](https://github.com/bcgov/gwells)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| Vue | Django REST | PostgreSQL | Jenkins | Groovy/GEB | js, Python, Groovy |

### Transportation Fuel Reporting System
The Transportation Fuels Reporting System facilitates online Fuel Reporting and Low Carbon
Fuel Credit Trading supporting BC’s market-based approach to avoiding lifecycle GHG
emissions from transportation fuel.
* [View the app](https://www2.gov.bc.ca/gov/content/industry/electricity-alternative-energy/transportation-energies/renewable-low-carbon-fuels/transportation-fuels-reporting-system)
* [See the code on GitHub](https://github.com/bcgov/tfrs)

| Frontend | Backend | Database  | Deployment Tool| Automation Tests | Languages|
|:-----------------:|:--------------:|:-----------------:|:---------------:|:---------------:|:---------------:|
| React Redux | Django | PostgreSQL | Jenkins | Groovy/GEB | js, Python, Groovy |

### 100+ Apps Using DevOps and Coding in the Open
While the BCDevExchange supports teams to deliver product in the Lab, we also make our DevOps platform available to teams outside of the Exchange lab. These teams are part of the development community helping to modernize the BC Public Service, including coding in the open. 
* [See Developer.gov.bc.ca - the DevHub - for how they make things happen, including our design system of reusable components.](https://developer.gov.bc.ca/)
