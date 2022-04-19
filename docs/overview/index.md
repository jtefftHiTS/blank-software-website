---
layout: default
title: Overview
nav_order: 2
has_children: true
last_modified_date: 2022-02-18
---

[//]: # The goal of this page is to give a simplified overview of your software. 
[//]: # You can probably pull a lot of this from your manuscript, but you probably do not want to show entire figures. Think about which components of which figures are necessary to give readers an overview of the software, isolate those components, and insert them here?
[//]: # Ideally, this will description will rely on images more than text
[//]: # See [ASHLAR](https://labsyspharm.github.io/ashlar/overview/overview-land.html) for an example of this.

[//]: # Reach out to Juliann if you want help with this page!!

# Overview 

{:.no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
  - TOC
{:toc}
</details>

# What's MY SOFTWARE?
1-2 sentence description

# Why?

What was the current need in the field that motivated the development? Start out by setting the scene. End by describing how your software fills this gap.

# How does it work?
The software runs three main steps
>1.  Does this first, 
>2. then uses that to do this next step, 
>3. then finally generates this output

{: .fw-300 }
MY SOFTWARE is written in ABC and is available under the MIT License. It can be downloaded at: [https://github.com/labsyspharm/blank-software-website](https://github.com/labsyspharm/blank-software-website).


## Step 1: Title 

``![Figure describing this first step]({{ site.baseurl }}/assets/images/Step1.png)``


Figure caption describing this first step.

{: .fs-3 }
{: .fw-300 }
> **Note:** *You may want to look at this [background material]() if you want to know more about this step*

## Step 2: Title

``![Figure describing this second step]({{ site.baseurl }}/assets/images/Step2.png)``


Figure caption describing this second step

<br>



# Learn More
**View the [detailed computational methods](./detailed-methods.html) for more information on how each step is performed.**

*For more details, read the preprint manuscript here: [https://doi.org/](https://doi.org/).*

## Integration with MCMICRO Pipeline
**The Multiple-choice microscopy pipeline (MCMICRO)** is an end-to-end processing pipeline to transform large, multi-channel whole slide images into single-cell data. See [https://mcmicro.org/](https://mcmicro.org/) for more information on the MCMICRO pipeline documentation, implementation, troubleshooting, and more.

![Visual overview of the MC MICRO pipeline components: Basic for illumination correction, Ashlar for alignment and stitching, Coreograph for TMA Core detection, UnMicst or S3 segmenter for segmentation, MC Quant for image quantification.]({{ site.baseurl }}/assets/images/pipeline-no-microscope.png)
