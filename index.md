
![](civiidiii.png)


Consensus building with city data
-----------------

**Whitepaper** | SmartUse GmbH, February 2019

# Abstract

The heart of the SmartUse project is creating a rich, up-to-date, high quality data for urban planning purposes. When different data sources are connected, the datasets are cleaned, normalized, validated, combined and analyzed, we aim to create the most extensive repository of responsive city data in Switzerland.

Our data is collected in manual and automated ways from authoritative public sources, standardized to allow it to be queried, analyzed, and combined with other data. Factors crucial to critical understanding of the urban landscape, such as finding matches, commonalities and connections between functional areas, are made possible with access to the information as structured data.

We believe that an ideal analytics environment for city planning is one where the differences of perspective between the architect, data scientist, civic activist are no longer a deciding factor in determining the outcome of projects. By eliminating friction in technical components and motivating collaboration between user of diverse skills, our platform increases productivity and brings cost benefits.

Civiidiii users are not only website visitors who consult the information, but are able to do their own analysis, find connections between local neighbourhoods and influential city projects, and run data-mining algorithms themselves - or collaborate with groups to whom this work is contracted through our marketplace.

## Team

A world class, diverse, connected urban science team headed by a smart project manager and savvy data scientist, backed by three founders with extensive backgrounds and network.

Viktoria

Thorben

Markus

Joris

Oleg

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

# Technical solution

The following chapters present an outlook on the technical architecture being developed on the basis of the SmartUse project.

## Data aggregation

In order to get that data, we have an extensive set of downloaders and scrapers which get the data from government publications and other web-sites. The fetched data is then processed and combined, and eventually saved to disk (so that people can download the raw data without hassle), loaded to a relational database (so that analysts can do in-depths queries of the data) and pushed to a key-store value (search engine) which serves our main website (cividi.ch).

The building blocks that we are using to accomplish all of this are called dataflows, based on the Data Package Pipelines developed at Open Knowledge. These frameworks allow us to write simple 'pipelines', each consisting of a set of predefined processing steps. Most of the pipelines use of a set of common building-blocks, and some custom processors - mainly custom scrapers for exotic sources.

## Data portals

Despite wishing to include "exotic sources" as mentioned in the previous section, as our primary basis we wish to build on the efforts to deploy central open data portals of the Swiss federal government, [opendata.swiss](https://opendata.swiss), and that of the City of Zürich, [data.stadt-zuerich.ch](https://data.stadt-zuerich.ch) - and evaluated the [CKAN software](https://ckan.org) that they both implement.

Nevertheless, we chose to use a newer technology stack for the project, in order to evaluate leading-edge approaches to the technical requirements - and potentially make valuable contributions back to the community. In this light, our project aims for integration with next-generation open data portals, such as the new [datahub.io](https://datahub.io) site, while retaining compatibility with current platforms like CKAN. It implements the emerging and upcoming standards of Frictionless Data.

## Frictionless Data

The data exchange capabilities of the SmartUse platform are based on the [Frictionless Data Standards](https://frictionlessdata.io/specs/) for metadata exchange, in the development of which our tech lead has [been involved](https://frictionlessdata.io/articles/oleg-lavrovsky/). For an introduction, visit the [Field Guide](https://frictionlessdata.io/field-guide/). The main distinguishing features of this approach are:

- containerization formats for any kind of data to enable simple data publication, transport, and consumption.
- platform agnostic interoperability of these data packages with various existing tools
- cutting costs through easier integration and more consistent interpretation of data schema and sourcing

By exploiting and developing standards like the Data Package, our platform will be compliant with a rapidly growing ecosystem of data manipulation and verification tools, ensuring that data consistency, provenance and quality can be tested and assured through an open choice of channels and with diverse vendors.

## Design process

We will use current methods of design thinking facilitation, A/B testing and focus groups, standard to a user experience engineering practice. We will evaluate and decide on the use of a widely accessible user experience/user interface framework such as [Material Design](https://material.io/) to develop our solution.

## Software architecture

Open source is in the DNA of this project.

The initial architecture of the project had to quickly evolve through several development phases. The only constant was the web-facing user interface. It was not a priority for the alpha release to have role-based security or highly scalable implementation: these will be the goals of future phases as the project becomes operational.
