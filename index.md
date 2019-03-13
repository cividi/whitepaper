
![](cividii.png)
Consensus building with open city data
-----------------

_

**Whitepaper** | v1.0 | SmartUse GmbH, April 2019

- [Abstract](#abstract)
- [Team](#team)
- [3x Theses](#theses)
- [Design](#design)
- [Principles](#guiding-principles)
- [Solution](#solution)
- [Architecture](#technology-architecture)
- [Infrastructure](#infrastructure)
- [References](#references)

# Abstract

The heart of Cividi is a team of city and software architects creating a rich, up-to-date, high quality collection of data for urban planning purposes. When different data sources are connected, the datasets are cleaned, normalized, validated, combined and analyzed, we aim to create an extensive repository of _Responsive cities_, starting in Switzerland.

Our data is collected in manual and automated ways from authoritative public sources, standardized to allow it to be queried, analyzed, and combined with other data. Factors crucial to critical understanding of the urban landscape, such as finding matches, commonalities and connections between functional areas, are made possible with access to the information as structured data.

We believe that an ideal analytics environment for future cities is one where the differences of perspective between the planner, architect, data scientist, civic activist are no longer a deciding factor in determining the outcome of projects. By eliminating friction in technical components and motivating collaboration between user of diverse skills, our platform increases productivity and brings cost benefits.

Cividi users are not only website visitors who consult the information: they are able to do their own analysis, find connections between local neighbourhoods and influential city projects, and run data-mining algorithms themselves - or collaborate with groups to whom this work is contracted through the Cividi marketplace.

## Team

A world class, diverse, connected urban science team headed by a smart project manager and savvy data scientist, backed by three founders with extensive backgrounds and network.

### Viktoria

### Thorben

### Markus

### Joris

### Oleg

.

.

.

.

.

# Theses

We are working on three theses relevant to the technical architecture of this project, which help us to identify key stakeholders and challenges on the longer roadmap.

### Big Architecture is facing Big Changes

Just as with other professional services businesses, the connection between those who provide a service and those who purchase it has transformed, creating demand for a more collaborative and open relationship. From the customer’s perspective there is a heightened sense that their relationship with their urban planning firms should be more like their relationships with other vendors: transparent, open, cooperative, actively managed and predictable.

These trends are pushing leading architecture firms to realize that, if they want to stay competitive, they must change. This reflects the shifting dynamics of modern city politics, which in the age of eGovernment and dropping poll counts, is concerned with ensuring citizen participation through ancillary means. Our overarching goal is to enable the architects, planners, engineers and policymakers to work together with the citizenry through shared insights into the data of what makes a city tick.

### Civic Innovation takes Practice

Borrowed from the late night engineering culture of pioneering technical campuses in the 60s, the term “hackathon” is a blend of the words “hack” and “marathon,” and refers to an intensive collaboration of people working on a project or exploring solutions to a difficult problem within strict time constraints (usually 24 or 48 hours).

Encouraged by the ideas, outcomes and learning opportunities that have come out of hackathons, we are putting it to the test in this project by organizing an urban analytics hackathon in early 2020 to invite developers to hack on our platform. In the meantime we are actively supporting and participating in a variety of external hackathons to get early exposure to the community. If our platform works for these kinds of events and audiences, we believe it will have a chance to have viral potential and scale beyond the initial applications while accelerating our development.

### Algorithmic planning needs Trust models

Going from a smart city to a responsive city means putting more minute-to-minute decisions into the hands of technological processes, which orchestrate algorithms that need to be proven both for their effective and ethical qualities. We have been working on embedding transparency into the analytical process from day one, learning to work with a variety of communication channels to let not only data scientists and engineers understand the system, but to be able to respond to the question of "are you building a black box?" with evidence of how our system is both tamper-proof and self-explainable on a variety of levels.

In all of our work we are standing on the shoulders of giants, but in this case in particular we are relying on the work of visionary projects from the Electronic Frontier Foundation, Open Knowledge International, the Swiss government, prominent scientists, and digital literacy advocates to make sure that the result is a puzzle piece helping to construct a digital society, and not just a digital bazaar.

# Design

Our design is based on following core principles:

- User experience comes first.
- Performance matters.
- We build on open standards.

## Developing the design

Our team has a vested interested and has already been testing the water over the past year with a number of approaches to iterating the design and UX that goes into successful information products. We have a basic workflow set up to go from sketches to wireframes to prototypes, and will continue to ensure that investments into technical solutions are backed up by solid design reasoning.

Partnering with experienced people and local agencies, we will use current methods of design thinking facilitation, A/B testing and focus groups, standard to a user experience engineering practice. We will evaluate and decide on the use of a widely accessible user experience/user interface framework such as [Material Design](https://material.io/) to develop our solution.

# Guiding principles

At the launch of a new initiative it is important to put share a set of principles clarifying the vision of management. The following is a list of key starting points.

**Let us get it right**

Every day we have the opportunity to create something that has the potential to be the ethical compass for someone making a key decision that will influence the development of institutions or neighbourhoods around the world. Our platform for participative governance may play a pivotal role in the way digitally enhanced discussions of urban planning run in 2020 and beyond - if we let it. Efficiency and profitability are a means to an end, not the goal.

**Crowd-based**

Our vision for the scope of the project is ambitious, and we cannot hope to achieve these goals within a reasonable time with hired hands alone. We will pursue a crowdsourced approach at all levels of operations, in research and in development, and aim to grow into the form of a crowd-based, distributed organization - such as a Cooperative - in the near future.

**Open platform**

Specific mechanisms to incentivize open contributions of source code or data or content will be prioritized as a pillar of the crowd-based approach. This system will initially built upon utility tokens of value (points) to motivate the community contribute and exchange reusable components (e.g. datasets, dataflows, visualizations). At a next stage, these will be enhanced with tenders and bounties supported by cryptographically traceable records (also known as "Smart Contracts").

**Automated spatial analysis**

The use of Geographic Information Systems (GIS) is a foundational area of our platform. Developments in remote sensing, in particular the proliferation of wide-scale, high resolution, and near-time satellite imagery, have led to notable developments in automating the analysis of land use patterns from crop yields to parking lot occupancy. Online marketplaces and data exchanges are already a key instrument to improve and widen the reach of automated spatial analysis (ASA) technology. Yet few are able to take into account the speed at which Machine Learning and Open Data are advancing the state of the art. This will be our competitive edge.

**Consumer choice**

As the cost efficiency and reliability of this technology continuing to increase,  will become a feature of all commercial and open source GIS tools. At this point, platforms like ours will clearly be needed to a widening range of users who are seeking improved accessibility and comparability of the outputs of such techniques. We will provide a central point of comparison and strive to establish guidelines and quality metrics into a comprehensive set of criteria for consumers to benefit from.

**Governance of the people**

We are acutely aware of the fact that governance plays a central role in our idea, and are following closely the developments of new ethical, philosophic and regulatory frameworks around the idea of 'humane' or _responsible_ technology. We are a Civic Tech initiative that strives to provoke and complement developments in the legal and political field. Details are presented in the following section.

# Responsible technology

Our thesis that "Algorithmic planning needs Trust models" is a central tenet of our solution for participative governance, and it needs serious commitment to develop indicators of trust. The idea of *Responsible tech* centers on concerns around the opacity of the processes and algorithms that are put to use in large scale data-driven projects, and proposes instruments for critical analysis, detection and intervention which can be implemented by individual developers or whole communities.

> _The tools currently available to policymakers, legislators, and courts were developed to oversee human decisionmakers and often fail when applied to computers instead. For example, how do you judge the intent of a piece of software? [...] We challenge the dominant position in the legal literature that transparency will solve these problems. Disclosure of source code is often neither necessary (because of alternative techniques from computer science) nor sufficient (because of the issues analyzing code) to demonstrate the fairness of a process._

-- Excerpted from [Accountable Algorithms](https://scholarship.law.upenn.edu/penn_law_review/vol165/iss3/3/) (Joshua A. Kroll et al. 2017)

See [Open Rights Group](https://wiki.openrightsgroup.org/wiki/Regulating_for_Responsible_Technology) for a discussion of the arguments of Responsible Technology from a policymaking standpoint. We see these principles come to life and be supported through initiatives like [Better IoT](https://betteriot.wordpress.com/), and similar projects that we would like to be able to champion and advocate through our platform. In this way we will be developing Trust models on the basis of rigorously evaluated formal criteria created together with inputs from academia, civil society, and practitioners in the field..

# Solution

The diagram below shows a high-level view of the platform architecture that is being developed on the basis of the SmartUse project. Detailed descriptions of some of the core components appear in the following sections.

The following sections describe key concepts of our solution. In the next chapter (Frameworks) we will document more specific platform components.

## Data aggregation

In order to get that data, we have an extensive set of downloaders and scrapers which get the data from government publications and other web-sites. The fetched data is then processed and combined, and eventually saved to disk (so that people can download the raw data without hassle), loaded to a relational database (so that analysts can do in-depths queries of the data) and pushed to a key-store value (search engine) which serves our main website (cividi.ch).

The building blocks that we are using to accomplish all of this are called dataflows, based on the Data Package Pipelines developed at Open Knowledge. These frameworks allow us to write simple 'pipelines', each consisting of a set of predefined processing steps. Most of the pipelines use of a set of common building-blocks, and some custom processors - mainly custom scrapers for exotic sources.

While we prefer open source environments like Python and open standards like CSV for data aggregation, it is important to us that the sources of data can be as diverse as the tools that we connect to our process. We therefore group these on a project-by-project basis into Factories.

## Factories

The factory is a core service responsible for running the flows for datasets that are frequently updated and maintained by us at Cividi. We are basing this on the [factory](https://github.com/datopian/factory) project at DataHub that uses Datapackage Pipelines, a framework for declarative stream-processing of tabular data, and DataFlows to run the flows through pipelines to process the datasets. We see this is a basic building block for next generation platforms like ours.

In a wider sense, we also see our technical infrastructure grouped around such factories, which are operating on various levels. Initially we will have singular customer engagements, and factories of various sophistication processing data for them. In the future, a factory-of-factories will aggregate the resulting data into the basis for new products and services.

Our goal is to co-design an open factory-building process that can be repurposed for various community and 3rd party solutions.

## Data portals

As our primary basis we wish to build on the efforts to deploy central open data portals around the worlds. Closest to us are those of the Swiss federal government, [opendata.swiss](https://opendata.swiss), the Swiss cantons which are also represented there, the City of Zürich [data.stadt-zuerich.ch](https://data.stadt-zuerich.ch) and other forward-thinking communes. Many of these portals are based on the [CKAN software](https://ckan.org) from Open Knowledge that is the forerunner and important basis for Frictionless Data.

## Frictionless Data

Our overall design principles are based on those of the [Frictionless Data](http://frictionlessdata.io/specs/) project, excerpted here:

1.  **Focused**: We have a sharp focus on one part of the data chain, one specific feature – packaging – and a few specific types of data (e.g. tabular).
2.  **Web Oriented**: We build for the web using formats that are web "native" such as JSON, work naturally with HTTP such as plain text CSVs (which stream).
3.  **Distributed**: we design for a distributed ecosystem with no centralized, single point of failure or dependence.
4.  **Open**: Anyone should be able to freely and openly use and reuse what we build. Our community is open to everyone.
5.  **Existing Software**: Integrate as easily as possible with existing software both by building integrations and designing for direct use – for example we like CSV because everyone has a tool that can access CSV.
6.  **Simple, Lightweight**: Add the minimum, do the least required, keep it simple. For example, use the most basic formats, require only the most essential metadata, data should have nothing extraneous.

From the beginning, the data exchange capabilities of the SmartUse platform are based on standards for metadata exchange such as the [Data Package](http://frictionlessdata.io/specs/data-package/), explained below. We are also already involved in [contributing back](https://frictionlessdata.io/articles/oleg-lavrovsky/) to this community. The main distinguishing features of this approach are:

- containerization formats for any kind of data to enable simple data publication, transport, and consumption.
- platform agnostic interoperability of these data packages with various existing tools
- cutting costs through easier integration and more consistent interpretation of data schema and sourcing

For a more detailed introduction, visit the [Field Guide](https://frictionlessdata.io/field-guide/).

## Geospatial Data Packages

A Data Package is a simple way of “packaging” up and describing data so that it can be easily shared and used. You can imagine as collection of data and and it's meta-data (datapackage.json), usually covering some concrete topic Eg: "Gold Prices" or "Population Growth Rate In My country" etc. Each Data Package may have zero or more resources and one or more versions.

Last year a [research project](https://research.okfn.org/spatial-data-package-investigation/) took place in the Open Knowledge community into the whether there is a need for a "Spatial Data Package" specification within the Frictionless Data ecosystem - or whether such specification should be a core part of the Data Package schema. The authors concluded that:

*   There is significant friction in the uptake of spatial data by non-GIS-expert users. This problem can be addressed by two adding a small amount of metadata, and some data processing conventions to existing Data Package standards.

    *   Tabular Data Package, with "location" resource attribute, for datasets consisting of points (or rather, rows with point locations).

    *   Data Package containing GeoJSON files, with "location" resource attribute, for vector datasets of line and polygon data.

*   There is no good solution for a common kind of semi-spatial data, that of tabular data that links to standard boundaries such as administrative or statistical regions. We propose:

    *   Tabular Data Package, with "location" resource attribute linking boundary identifiers to yet-to-be-defined standard codelists.


*   For cases where the above solutions do not meet the package creator's need, including raster data or data that is not under the package creator's direct control, we propose improvements to the emerging Spatial Data Package format already under way.

We are supporting and implementing these approaches, doing our own evaluations, and hosting regular exchanges with this group and the geographical information systems (GIS) community in general.

By exploiting and developing standards like the Data Package, our platform will be compliant with a rapidly growing ecosystem of data manipulation and verification tools, ensuring that data consistency, provenance and quality can be tested and assured through an open choice of channels and with diverse vendors.


# Architecture

Open technology is in the DNA of this project. Open source has revolutionized the way that computer technology is developed, making the Internet as we know it today possible.

Urban design is evolving to become a field accessible and usable by people around the world, contributing to the desire and initiatives to standardize city planning around the world. We see this as an extension of the open technology to the way we shape the physical world.

> _"People understand spaces whether they are experts or not."_ --Joris

In Cividi, open source is married to the DNA of urban systems design, that is bringing it's own revolution to the way that architecture is conducted, how cities evolve through a constantly reshaped landscape of human and machine transactions. Our architecture reflects the meeting of these worlds.

## Cities by design

At Cividi, the data-sharing and data-technology landscape is seen as a virtual manifestation of the physical city landscape, and we intend to develop and deliver software as expressive and scalable as it will need to be to work with the multiplatform and multilateral smart city of the future.

## Software by design

The initial architecture of the project had to quickly evolve through several development phases. The only constant was the web-facing user interface. It was not a priority for the alpha release to have role-based security or highly scalable implementation: these will be the goals of future phases as the project becomes operational. We are focusing on data publication standards in the next phase, APIs and search capabilities will follow soon after.

## Leading by following

In order to evaluate leading-edge approaches to the technical requirements - and potentially make valuable contributions back to the community we are evaluating and implementing modern software stacks which have achieved a certain maturity level.

In this light, our project aims for integration with next-generation open data portals, such as the new [datahub.io](https://datahub.io) site, while retaining compatibility with current platforms like CKAN. We implement the emerging standards of distributed publication like Frictionless Data, while providing workflows and tutorials for users of monolithic databases.

Continuing to build upon our architectural foundation and working through requirements gathering and team-building phases to determine how the platform will be supported long term will be key to making the right decisions here.

# Frameworks

Like the DataHub platform that we are inspired by, our project follows a service oriented architecture. It is built from a set of loosely coupled components, each performing distinct functions related to the platform as a whole.

In this chapter we describe some specific libraries and platforms that we plan to use to implement our solution.

## Data aggregation

### Geospatial analytics

PostGIS, QGIS, ..

### Data science

Jupyter, Pandas, ..

### Geodata visualization

Mapbox, Kepler, ..

## Online platform

To implement our initial, REST-compliant architecture, we used the Python Flask microframework and [Flask API](https://www.flaskapi.org/), to generate multi-format routes and Web accessible views of our Frictionless Data-compatible API for developers to use. During an earlier phase, we implemented a _Serverless_ architecture coupled to a Node.js environment. In the future, this project could move to another framework, or even another development environment. For example, the Python based [Django](https://www.djangoproject.com/) and it's [Django REST Framework](http://www.django-rest-framework.org/) offers comprehensive support for "data model"-based applications, provides deep integration with advanced database management systems such as PostgreSQL, and a wealth of out-of-box service and backend components to build on.

## Infrastructure

TBD: discussion on how our cloud dependencies are evaluated and managed.

# References

Literature list for further reading.

- Open Knowlege
- Frictionless Data
- CKAN, Open-DAI, Pelias, Geoplatform, Stae ...
- ...
