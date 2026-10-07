---
title: ""
author_profile: true
redirect_from: 
  - /projects/
  - /projects.html
---

{% include base_path %}



# seasonality, phenology, and evolutionary biogeography

Seasonality is a fundamental feature of Earth. It controls the annual rhythms, or 'phenologies', of countless species and ecological processes, so is a basic concept across many discplines. Thus, it can be surprising how poorly we understand seasonal phenology across much of the planet.

I am working to change this. I developed a simple, globally consistent method for modeling the average seasonal phenology of terrestrial ecosystems worldwide. The results paint an unprecedented portrait of the global diversity of seasonality (shown below; you can explore this map using this [data viewer](https://lyrical-ring-231401.projects.earthengine.app/view/globalphenologicaldiversityandasynchronyterasakihart2024)!). This reveals global regions where seasonality can be quite out of sync between nearby sites -- mainly in tropical mountains and across Mediterranean climates and their neighboring deserts. Across these regions, I find that the global phenology map predicts asynchronous breeding time in various plant and animal species, and even the patterns of genetic diversity that likely result from reduced gene flow between out-of-sync breeding populations.

 This work was featured on the cover of [Nature](https://www.nature.com/articles/s41586-025-09410-3). It suggests promising avenues to insight across various fields of study -- many of which form the backbone of my current research program.


![global phenological diversity](/images/global_phen_div.png)

<small>*Global phenology map, derived from MODIS satellite imagery, showing intercontinental convergence in complex regional patterns. The more different the colors between any two spots on the globe, the more different the shape and timing of their average seasonal phenological cycles. Clusters 1 to 9 show the seasonal cycles associated with the most common colors in the global map. Inlaid maps give a closer look at the complex geographic variation in seasonal timing within regions of interest. For more detail, see the [paper](https://erthward.github.io/files/terasaki_hart_2025_global_phenology_maps.pdf))*</small>


------------------------------------------------------------------------------


# landscape genetics, global change, and simulation

The future of biodiversity depends, in part, on the dynamics and effectiveness of evolutionary responses to global change. Predicting these responses is quite challenging, as it requires understanding the population genomics of species that are often continuously distributed across unevenly changing landscapes. Simulations are critical for insight into such complex systems, but options for landscape genomics are limited.

To address this, I developed [`Geonomics`](https://geonomics.readthedocs.io/en/latest/), a user-friendly Python package for simulating landscape genomics on complex and dynamic landscapes.
I published a paper in [Molecular Biology and Evolution](https://academic.oup.com/mbe/article/38/10/4634/6297222) that describes, validates, and demonstrates how it works. The conceptual diagram below gives a quick overview, and this [talk from the 2022 Evolution conference](https://youtu.be/XZNYGJEZNnA?si=-elzwREOPqt4w59h) offers a quick tutorial. (** *NOTE*: If you're interested in using Geonomics and would like help getting statrted, please reach out!)


![simple conceptual diagram showing how Geonomics operates](/images/gnx_conceptual_diagram.png)

<small>*Conceptual diagram showing how Geonomics is strucutred and what it does. The model simulates individuals (here shown as spheres) of a species, distributed across a landscape, and each carrying its own genome. The landscape is defined as a stack of raster grids representing important environmental factors. Some environmental factors can exert natural selection on individuals' traits, such as the top landscape grid shown here. Others can influence the carrying capacity (i.e., local population size) and/or movement behavior of the species, such as the bottom grid shown here. The model simulates any number of time steps, during which individuals can move (shown here in the top left corner); individuals can find mates, combine their genes and reproduce, and disperse offspring (top right); individuals can die from natural selection and/or density dependence (bottom right); then the environment could be programmed to change (bottom left). After enough time steps of a model, spatial patterns of genetic diversity build up. We can use those patterns to explore how landscape genetics likely works on real landscapes and to make inferences about the processes likely driving patterns we observe in real-world data.*</small>


I built `Geonomics` to study an previously intractable question: How do species' evolutionary responses to climate change depend on the 'genomic architecture' of climate-adapted traits -- that is, the number and organization of the genes involved in adaptation? Climate change can change the geographic patterns of different environmental factors (e.g., temperature versus precipitation) in different ways, shifting the optimum trait combinations that occur across a landscape (as shown in the conceptual diagram below) and thus driving complex evolutionary dynamics.
My work in [Global Change Biology](https://onlinelibrary.wiley.com/doi/10.1111/gcb.17179) shows that these dynamics are contingent on genomic architecture, in ways that are important for determining the effectiveness of management efforts.

![conceptual diagram of the shifting adaptive landscapes under climate change](/images/genarch_and_climate_change_conceptual_diagram.png)

<small>*Our conceptual framework for simulation of adaptation to climate change. Between times t1 and t2, one environmental gradient (e1) on the physical landscape (left) shifts at a different rate than does the other (e2). This causes novel environments to emerge at various geographic locations (x1,2,3), shifting adaptive peaks across the fitness landscape (right).*</small>



------------------------------------------------------------------------------


# land use, biodiversity, and conservation
Conservation and land management strategies and outcomes are often dependent on spatiotemporal context. I am heavily involved in applied research to help understand this. Some of this work has focused on refining our understanding of [agroforestry as a potential climate solution](https://www.nature.com/articles/s41558-023-01810-5). (The conceptual diagram below derives from this work.) which helps frame out a definition of agroforestry as an NCS). 
Other work addresses topics ranging from reforestation and avoiding deforestation to estimating the biodiversity benefits of restoration activities, understanding loss of genetic diversity under habitat loss, and monitoring biodiversity loss using massive datasets of opportunistic species observations. For a full list, see the [papers tab](https://erthward.github.io/publications) for more.

![conceptual diagram of agroforestry as a natural climate solution](/images/AF_as_NCS_diagram.png)

<small>*A first-approximation framework for determining when agroforestry is a climate solution. Agroforestry is an NCS when it is adopted after a carbon-accounting baseline and does not have net-negative biodiversity impact (left), when a change in management increases its spatially or temporally averaged carbon storage (center), or when action is taken to preserve it despite risk of clearance (right). (Graphic design by me, production by Vin Reed.)*</small>

