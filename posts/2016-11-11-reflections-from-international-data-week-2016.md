---
slug: reflections-from-international-data-week-2016
date: 2016-11-11T16:56
tags:
  - Conferences
  - Science
author: joehand
title: Reflections from International Data Week 2016
excerpt: |
  International Data Week in September 2016 brought together three events, SciDataCon, the International Data Forum, and the Research Data Alliance 8th plenary. Joe Hand from the Dat team attended the conference.
---

International Data Week in September 2016 brought together three events, SciDataCon, the International Data Forum, and the Research Data Alliance 8th plenary. Joe Hand from the Dat team attended the conference.

[International Data Week](http://internationaldataweek.org) featured sessions on the wide topic of using data in science. I attended on sessions focused on scientific data publishing, an emerging and urgently needed field. Dat entered this field alongside established organizations such as publishers, research institutions, and non-profits. Data publishing enables citation of data and improves reproducibility. The conference showcased a huge range of approaches to this problem.

Data citation models parallel current academic publishing and reputation models. In academia, grants, funding, and career advancement all depend on citations. Standardized metadata improves the ability to cite data. It also enables journal publishers to connect datasets to papers in their journals.

Reproducibility overlaps with, but does not require data citation. Researchers can reproduce papers without data citations or even without public data. Current reproducibility efforts favor short term reproducibility by using existing web infrastructure. This sacrifices long term preservation by using infrastructure not built for archiving.

In the long tail of research data, data types are more unique and fewer people use each dataset. Few centralized data publishing services appeal to this long tail of researchers. Citation and reproducibility become more difficult in the long tail without new infrastructure.

Data publishing organizations use existing web infrastructure to create data citation and reproducibility services. This infrastructure does not support data publishing needs by default. Building data publishing services on top of the web may threaten long term sustainability. Data sharing, discovery, and preservation are the primary design ideas behind the Dat infrastructure. By embedding these needs into infrastructure, data publishers can provide services without endangering data.

## Metadata Standards and Data Publishing

The treatment of publishing of academic papers is informing the discussion around data publishing. Researchers livelihoods often rely on proper citation for their work. Citations allow them to get more grants and secure tenure. Some data publishing organizations are creating data publishing structures that mirror those of journals. To support this idea, there was a large focus on standard metadata and a common data citation process.

Data publishing systems showcased throughout the week had similar goals:

* A researcher should be able to publish their data.
* Another research should be able to find, download, and use the data.
* Any published work should cite the data used, crediting the researcher that originally published the data.

As data publishing exists today, there are no standard ways to cite data. Unlike papers, data may change before other researchers use it. Citing data requires the ability to cite versions of data, subsets of data, or forks of data. Organizations are trying to solve the citation problem in parallel. This is leading to the standards problem:

![xkcd standards](http://imgs.xkcd.com/comics/standards.png)
*Source: [xkcd 927](https://xkcd.com/927/)*

## Reproducibility and Long Term Preservation

Reproducibility was another major theme of the week. When researchers publish papers, other researchers should be able to independently verify the results. Reproducing results is currently impossible for many papers involving data or software. Researchers do not always publish data or software to their papers. If they do publish data, they may not publish it in a manner that other researchers can re-run analysis.

With the explosion in data repositories, science may be making headway as more researchers publish data. The [re3data registry](http://re3data.org) has over 1,500 data repositories registered. Unfortunately, repositories have their own metadata formats, publishing processes, and varying underlying software.

Dissimilarity in data publishing has major implications for long term reproducibility. In the fast-moving era of the web, we see online services start up and shut down daily. Websites that were there one day are gone the next. Data powering these sites can disappear as users lose countless hours they have contributed.

We may lose of troves of data if organizations build repositories with a similar approach to web services. This could have with potentially disastrous results for reproducibility and science in general. Rising research costs and aging web infrastructure point to a stark future for published data.

### The Cascading Costs of Data Publishing

As academic institutions face rising costs, we could lose the progress in data publishing. Libraries are already pushing back against rising journal prices. During the week, librarians expressed concern over paying the costs of data repositories. Each data repository has their own funding and revenue model. Yet, many rely on libraries or researchers to pay at some point, either to get data or to publish data.

Many research institutions already have servers to backup and archive data for researchers. Few repositories make it possible for institutions to leverage their existing infrastructure. Universities may have to pay twice to backup the same data. Data will exist on their institutional servers and on a common data repository platform. Because of reliance on web infrastructure, data published in many places will be invisible to each other. If a platform shuts down, external researchers may not be able to access the data even if it is archived on a university's server.

## The Long Tail of Data and the Reproducibility Crisis

The long tail of research data exacerbates the citation and reproducibility problems. Online distribution makes it much easier for users to share and discover long tails. For example, Amazon made the long tail of books available – each book interests only a few people but there are many of them. Demand for items in long tail exceeds the demand for the most popular items. There is a parallel long tail in research data.

Like rare books on Amazon, there is a long tail of research data. These datasets only have a few downloads but in total they have more demand than popular datasets. More importantly, there is a long tail of researchers needing to publish data. Their data does not fit within existing metadata, standards, or data repositories. To ensure reproducibility, we need to have a place for these researchers to publish their data without significant overhead.

Unfortunately, publishing long tail data can be a challenge. Researchers have to decide on which, if any, general access repository fits their needs. Often these repositories have restrictions on sizes or types of data. Additionally, they encourage publishing completed data, making the process an afterthought instead of a central part of the workflow. Researchers will publish their data only if they have a strong incentive or requirement to.

We have to understand how long tail data will fit if we want to succeed in ensuring reproducibility and common data citation. Otherwise, we will lose the majority of data that does not fit in existing platforms. The difficulty of using the tools must not outweigh the benefit researchers receive for publishing.

## Building Publishing Services on Data-First Infrastructure

Creating a common data sharing infrastructure is essential, as the long-tail issues make clear. Existing general-purpose data publishing services exist. But they do not integrate into scientific workflow and have other constraints from using web technologies. Organizations need to focus on wide adoption and long term data archiving, regardless of the metadata. It will not matter what data citation standards exist if the data is lost.

Dat integrates directly into the workflow of any researchers that use file-based data. Data remains on their local computers instead of creating unlinked or duplicate copies on cloud services. Dat enables efficient and long-term storage of data by using decentralized infrastructure. This means that data does not need to exist in one location. Instead, institutions collaborate on data preservation, reducing potential points of failure. Researchers can download data from anywhere without needing to know who archived the data.

Accurate and future-proof citation requires identifiers for specific versions or subsets of data. If data changes over time, other researchers should be able to the history enabling full reproducibility. Infrastructure allowing scientists to collaborate on data while retaining citation and history is essential.

Dat provides live and persistent identifiers. Researchers can update data without changing the know identifier. This allows continuous archiving of data while research is occurring, not only after publishing. Append-only logs, common in blockchain technologies, allow data citations that point to specific versions of data. Change history is automatically tracked allowing complete reproducibility throughout the data analysis process.

Building data publishing services on existing infrastructure has a low upfront cost. But using these dated technologies may have a high cost to reproducibility. Improving the underlying technologies will allow us to make data a primary citizen. If we do not publish data on data-first infrastructure then data citation, reproducibility, and archiving of data will be issues that continue to plague science.

