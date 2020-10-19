---
layout: post
title: Project Description
date: 2020-10-13 13:32:20 +0300
description: Main objectives and Workpackages. # Add post description (optional)
img: strategie.jpg # Add image post (optional)
fig-caption: How to turn EO images to land-cover maps# Add figcaption (optional)
tags: [Holidays, Hawaii]
---
The MAESTRIA project (Multi-modAl Earth obServaTion Image Analysis) aims to solve the methodological challenges related to the fully automatic analysis of the massive amount of images acquired by Earth Observation (EO) platforms.

## Context
In the last years, the advent of Earth Observation (EO) satellite missions with short revisit time and increased spatial resolutions has led to an unprecedented amount of remote sensing images of heterogeneous physical nature. These images are freely available through dedicated infrastructures. They are designed to foster the use of EO images and offer a unique and long-term capacity to extract knowledge over large temporal and spatial scales and with a high temporal
rate (up to 5 days).
Such data abundance brings new opportunities in particular for generating land-cover and land-use maps at the scale of a country, and at least on a yearly basis. However, such
data proliferation raises new challenges in multi-modal high-dimensional image processing so as to be able to exploit the complementary information provided by images acquired from different sensors with various resolutions in the spatial, spectral or temporal domains.

One critical application of EO data is the production of <b>land-cover databases (LCDB)</b>, the observed (bio-) physical cover on the Earth surface. In practice, LCDB documents all types of objects/surfaces. These objects and surfaces are segmented into categories that are
called <i>classes</i>. The number, types, and definitions of these classes (nomenclature) vary with the application
and the geographical scale.
Land-cover and land-use description of the Earth surface and their changes over time are the core information layers for a large variety of interdisciplinary scientific and environmental studies. Accurate and up-to-date maps over large areas are mandatory baseline datasets and became, in the last decades, an irreplaceable observation feature. A large number of environmental policies, in particular in the European Union, are driven by such knowledge: strategic areas of intervention and challenges related to climate change impacts, the conservation of natural resources, reduction of risks and threats, sustainability of urban and rural development, etc.


## Challenges
The underlying mathematical process for automatic land-cover generation using such large volume of multi-modal EO data is <b>supervised classification in high dimensional space</b>. Given the large volume of multi-modal data and the above-mentioned requirements, novel critical challenges need to be addressed:
* <i>How to combine very high spatial resolution (VHR) images (SPOT6, 1.5-2 m; 1-3 images/year) with high resolution optical time series images or radar data (Sentinel-1/2/3, 10 m, 1 image/5 days) </i>?
* <i>How to learn with noisy big data?</i> Indeed, the learning method has to cope with noisy information in the image data (clouds, shadows, low resolution, speckle) as well as in the training and ground truth data (human errors, imperfect class delineation or cover changes since the survey). Furthermore, the size of the reference data is usually small for some particular classes, resulting in a reference data badly balanced in terms of number of samples per classes.
* <i>How to derive meaningful products, semantically consistent at many spatial scales?</i>

## Objectives
The MAESTRIA project aims to develop automatic methods for the analysis of the large amount of available heterogeneous EO satellite images. It therefore exhibits two main strategic objectives:
* <b> From a method-driven point of view </b>, it targets to integrate information extracted from all available data sources (both satellite images and existing land-cover maps), so as to alleviate current limitations. In practice, it will improve both the semantic and spatial accuracies of the current product (10m to 2-5m, meeting most of environmental monitoring needs). A generic full map of France with homogeneous quality, at different times of the year, will be proposed. We will therefore develop new methods for the combination of multisource and multiscale imagery. The huge amounts of data available will have to be analysed and reduced in order to derive the pertinent information for the problem at hand, finding the trade-off between accuracy of the results and scalability of the methods. A particular effort will have to be done in terms of optimization methods and dimensionality reduction approaches, based on recent advances in large scale (deep based) machine learning.
* <b>In an application-driven flavour </b>, it targets to extend the framework to a variety of innovating services (land-use mapping, derivation of coarse-scale products, consistent with existing continental and global datasets). Each of them is related to fundamental methodological issues and linked to requirements of various end-users at local, regional, and national scales. It will offer a full processing chain with high flexibility and high impact for the adoption of remote
sensing data and LC maps.
