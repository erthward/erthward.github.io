---
permalink: /
title: ""
author_profile: true
redirect_from: 
  - /about/
  - /about.html
---


**Landscapes are complex, both in space *and* in time.** In ecological science we can often get away with swallowing that temporal complexity into long-term averages and assumptions of stationarity (that is, assumptions that ecological conditions are static). We can often away with this -- but not always! Sometimes interesting and important dynamics hide behind our simplifying assumptions about time. I like to dive head-first into these blind spots, asking how complex space-time patterns in the environment structure the ecological and evolutionary processes that generate, distribute, and maintain biodiversity?

**Landscape are changing at an historic pace.** When viewed from a grand geological perspective, human activity has ramped up with mind-bending pace and extent. We have exploded onto the scence. The evidence of this accelerating change is mounting, even over recent decades. This is our undeniable new reality. And it raises important questions and complications for many of our field's fiindings and theories, based as they are on assumptions of stationarity. This requires us to do the hard work of updating our field: adopting non-stationarity as the new norm, determining whether and how this changes our understanding of how nature works, and improving our ability to manage and conserve nature on a rapidly changing planet. I am contributing to this effort through both theoretical work and a wide variety of applied science projects.

**I'm a... *`sigh`*... data scientist.** While I have no aversion to collecting data (in fact, I quite love it!), I have often found it unnecessary. This is because many of the sorts of questions I tend to wonder about can often be approached using the rich diversity of data that I already have at hand. This includes data that can be 'found' (i.e., public databases, remote sensing imagery, literature-locked measurements, and other open resources) as well as data that can 'made' (i.e., simulated -- which enables geographic and temporal coverage, biological complexity, and statistical replication *in silico* that far exceed what is practical *in carbone*). One of the big challenges in leveraging these data to answer important scientific questions lies in mastering the computational tools required to wrangle, process, analyze, and visualize them. Thus (to my occasional chagrin) I've wound up developing expertise in environmental data science. Lucky for me, I like playing with computers. :) Unlucky for me, computers don't like playing outside. :(

**Really though, I'm an intellectual nomad in a specialized world.** Throughout my life, I have pursued broad training and experience in ecology, evolutionary biology, genetics, conservation, geography, statistics, computer science, environmental policy, agriculture, and sustainable development. Nature and science are the unbroken themes. I try to read widely, think across disciplines, and use creative problem-solving to chase big, imaginitive, odd, and intriguingly complex ideas. Wherever they might lead me! My work is motivated, in equal parts, by a passion for natural history, an compulsion for abstract reasoning and theory, an ethical commitment to human-centered conservation, and an unavoidable desire to teach and share.

-------------------------------------

# my science

***NOTE: All PDFs available via the 'publications' tab.***

![global phenological diversity](images/global_phen_div.png)
*TODO: SIMPLIFY: Global LSP mapping reveals intercontinental convergence and complex regional gradients. Colors result from plotting the top three modes of the empirical orthogonal functions (EOF) analysis as an RGB (red-green-blue) composite. These modes, which explain >90% of the phenocycle variation in our global time series of near-infrared reflectance of vegetation (NIRV), were transformed across the intertropical convergence zone (ITCZ; dotted black line straddling the equator) before composition to facilitate inter-hemispheric comparison. Line plots (upper-right) depict annual phenocycles (January-January north of the ITCZ, July-July to the south) for nine clusters derived from the global set of fitted phenocycles, colored by each cluster’s median value in the RGB composite. Regional maps (A-D) are paired with phenocycle plots displaying regionally constrained clustering results. Complex regional gradients appear to reflect patterns of topoclimate, ecohydrology, and vegetation structure: A. In California and Arizona, USA, and Sonora and the Baja California peninsula, Mexico, a strong gradient aligns with the orographically driven division between Mediterranean winter-monsoon regions (colors 1 and 2) and summer-monsoon regions (3 and 4) 41. B. In the Great Basin region, USA, we recover a significant signal of the accelerated spring growth of cheatgrass (1) 42 relative to surrounding sagebrush (2) and montane (3) vegetation (one-way ANOVA P <5x10-324, with clusters of n = 4629, 904, and 4891 pixels; two-tailed Tukey’s Honest Significant Difference P =  5.71×10-12 in both cases, with family-wise error rate = 0.05). C. In Southern Florida, USA, we observe starkly contrasting phenologies between areas characterized by Everglades sawgrass marsh (1), wooded wetland (2), and remaining upland, drained, and mangrove ecosystems (3). D. In the Amazon Delta region, Brazil, we observe unimodal phenologies in non-forest areas (1) that are closely juxtaposed with bimodal phenologies in forest (2 and 3), whether non-forest is naturally occurring (e.g., the northwestern patch is Guianan savanna) or anthropogenic (e.g., the southern band lies within the ‘arc of deforestation’).*

## phenology

Phenology is the study of the timing of ecological processes (think flowering, leaf-fall, migratory movements, and so forth). I first became interested in phenology when I was working in Central American cloud forests and I noticed that nearby sites within 'the same forest type' had populations of the same plant species that were at very different points in the life cycles (perhaps because of different seasonal timing of the complex cloud-immersion regimes that are so important in these regions?). I became totally fascinated with phenology when I learned about the intriguing but little-tested [Asynchrony of Seasons Hypothesis](https://ojs.library.queensu.ca/index.php/IEE/article/view/2148), which I summarize as follows:
 - 1.) the timing of seasonal patterns could vary across complex landscapes (e.g., different timing of the rainy season on different sides of a tropical mountain range);
 - 2.) this could cause the phenologies of the species that cue into those patterns to also vary across the landscape;
 - 3.) such 'phenological asynchrony' would cause populations of a species to be reproductively and thus genetically isolated (because any migrants between populations would typically have out-of-sync breeding schedules, so would fail to transfer their genes);
 - 4.) regions where such 'allochrony by allopatry' is more common should have quicker rates of population genetic differentiation, and thus higher rates of formation of new species (potentially explaining global patterns of species diversity that have fascinated biogeographers for centuries -- e.g., why is species diversity so crazy in tropical mountains!?).

I dove into the deep end in the third chapter of my PhD. Using 20 years of global satellite imagery of ecosystem function (essentially, space-based daily photos of plant growth across the Earth's surface), I devised a method for calculating average seasonal phenologies around the world. This produces an intimate and unprecedented portrait of Earth's terrestrial phenological diversity (shown above; you can explore this map in detail using this [data viewer](https://lyrical-ring-231401.projects.earthengine.app/view/globalphenologicaldiversityandasynchronyterasakihart2024)).
I then map the global pattern and drivers of phenological asynchrony (finding hotspots predominantly clustered in tropical montane regions and Mediterranean climates, predominantly driven by seasonal asynchrony in precipitation and minimum temperatures); document a latitudinal gradient in 'isoclimatic phenological asynchrony' (i.e., climatically similar sites are more likely to be out-of-sync in the tropics, increasing the likelihood that the same species could be found in both and thus could be evolutionarily affected); and show that our space-based maps predict on-the-ground patterns of allochrony by allopatry and genetic divergence across a range of species and across global hotspots of phenological asynchrony. This work is forthcoming in [Nature](https://www.nature.com/articles/s41586-025-09410-3), and presents numerous promising avenues for future research that I am excited to explore. (***NOTE:*** *If you're interested in pursuing any of those then please reach out!*)

-------------------------


## landscape genomics
Landcape genomics seeks to understand the geographic patterns of genetic diversity that occur in nature and the natural processes that produce those patterns, with the ultimate goal of using the patterns to make inference about the processes. I find this whole frame of thought deeply captivating.

![simple conceptual diagram showing how Geonomics operates](images/gnx_conceptual_diagram.png)
*TODO: SIMPLIFY: Operations during the main phase of a Geonomics model run. In the center is a species on a multilayer landscape that includes a selection layer (above) and a layer for movement and carrying capacity (below). Surrounding the landscape is a flow-diagram of the major operations during a time step. Operations in dashed boxes are optional. During the movement stages (top-left), individuals move along movement vectors drawn from various distribution options (shown is an example of a cell-specific von Mises mixture distribution). During the mating stage (top-right), each mating individual (black circle) randomly chooses a mate (white circle) from all potential mates within its mating radius (dashed circle). The resulting offspring (half-black, half-white circle) disperses from its parents' midpoint along a randomly drawn dispersal vector. During the mortality stage (bottom-right), deaths are modeled as a Bernoulli process, with the probability of mortality a product of density-dependence and selection on all traits. During the changes stage (bottom-left), environmental and demographic change events, which can be represented by a series of change rasters corresponding to scheduled time steps, take place.*

### Geonomics

For the first chapter of my PhD I developed [`Geonomics`](https://geonomics.readthedocs.io/en/latest/), a flexible, user-friendly Python package for simulating landscape genomics. (Think of a simulator as a video game, but without all the fun bits.) We published a methods paper in [Molecular Biology and Evolution](https://academic.oup.com/mbe/article/38/10/4634/6297222) describing, validating, and demonstrating the software. The conceptual diagram above gives a high-level sense of how the software works, and [this talk from the 2022 Evolution conference](https://youtu.be/XZNYGJEZNnA?si=-elzwREOPqt4w59h) offers a quick tutorial.

***NOTE:*** *I'm always happy to chat with and support potential users, so do get in touch!*


![conceptual diagram of the shifting adaptive landscapes under climate change](images/genarch_and_climate_change_conceptual_diagram.png)
*TODO: SIMPLIFY: Conceptual model of adaptation to climate change. The top panel depicts the two-layered physical landscape used in our simulations, showing the shifting environmental gradient (e1) in a blue–red color ramp and the stable gradient (e2) in a white–black color ramp. The landscape is shown both before climate change (t1) and after (t2). The bottom panel depicts a fitness landscape for two traits adapted to the shifting (e1) and stable gradients (e2). Three example positions on the physical landscape (x1, x2, x3) are shown as boxes delineated y-axis cross-sections, both before climate change (gray) and after (yellow), and their corresponding fitness peaks are shown as color-matched kernels on the fitness landscape. The gray and yellow lines on the fitness landscape indicate the fitness optima defined by the environments that exist before (t1) and after climate change (t2). Shifts in local fitness peaks are shown as labeled arrows (x2, x3); the environment at the far left of the physical landscape does not change, so x1's fitness peaks are overlapping and have no shift.*

### Genomic architecture and adaptation to environmental change

The second chapter of my PhD uses `Geonomics` to explore how species' responses to climate change could depend on the number and organization of the genes controlling their environmentally adapted traits (i.e. their 'genomic architecture'). Climate change can change the geographic patterns of different environmental factors (e.g., temperature versus precipitation) in different ways, shifting the optimum trait combinations that occur across a landscape (as shown in the conceptual diagram above) and thus driving complex evolutionary changes that software such as `Geonomics` are ideally suited to understand. Myfindings suggest that genomic architecture could control adaptation to climate change in management-relevant ways, posing the challenging question of how best to determine or predict the genomic architecture of relevant traits in real species of conservation concern. This work is published in [Global Change Biology](https://onlinelibrary.wiley.com/doi/10.1111/gcb.17179).


### ADD OTHER PROJECTS HERE?


--------------------

## conservation
We really like to test the patience of the hand that feeds us. We just can't get enough of stuff, it seems. It's not in nature's nature to tolerate that for too long. Things, frankly, aren't looking good. What does one person do with that? I wonder about this literally daily. What does a good life even look like when things are so unstable and unfair and uncertain? Well, hermetic martyrdom really ain't a good sell, and every commitment has an opportunity cost... Anyhow, if my other research is primarily a pursuit of beauty then this research is my humble pursuit of what's good and right -- my attempt to somehow making something better for people and all the other beings:



![conceptual diagram of agroforestry as a natural climate solution](images/AF_as_NCS_diagram.png)
*TODO: SIMPLIFY: If agroforestry does not exist before the baseline, then agroforestry adoption serves as an NCS when it increases woody and soil carbon storage without impacting biodiversity (left). If agroforestry exists at the time of baseline establishment, changing agroforestry management can serve as an NCS if it increases tree biomass or proportional tree cover in static or rotational agroforestry systems, thus increasing carbon storage (middle). Alternatively, conservation of some or all trees can serve as an NCS if those trees would have been removed under business-as-usual conditions, such that their maintenance leads to avoided emissions (right). Figure adapted from image by Vin Reed.*

### Agroforestry as a climate solution

Agroforestry, in short, is the practice of growing trees and non-tree agricultural products on the same piece of land. It's really just a highfalutin term for how much of agriculture has probably looked in most places and societies, for thousandsof years. But tree cover has become less common across much of the world's agricultural lands, not least because of the tendency of modern agricultural practices to plow 'fencerow to fencerow' in their manic, one-track pursuit of productivity and profit. The environmental costs of this approach to making food and fiber, though still largely economically externalized, will be news to nobody -- soil erosion, biodiversity loss, food insecurity, water pollution, climate change, and the like. The good news is that adoption and expansion of agroforestry could work to counter these trends. Agroforestry systems are multifunctional ecosystems that can often provide numerous environmental and economic benefits (though not always! context is key!). 

The potential benefits of agroforesty expansion include the potential to increase the sequestration, storage, and protection of carbon on agricultural land -- that is, to serve as a ['natural climate solution'](https://www.pnas.org/doi/10.1073/pnas.1710465114) (NCS). This is an area of growing interest in policy and practice, but one that has received relatively less attention in prior agroforestry science work. Thus, my colleagues at The Nature Conservancy and elsewhere have initiated a global effort to gather, organize, and analyze all of the available data on carbon in agroforestry systems, to better understand the quantity and context of the potential of agroforestry as an NCS. The first step in this process was a global pulse-check on the state of the science, which we published in [Nature Climate Change](https://www.nature.com/articles/s41558-023-01810-5) (including the above conceptual diagram of agroforestry as an NCS). This a major and ongoing effort with numerous avenues of forthcoming work.


### Reforestation and restoration

With my former TNC colleagues I've also worked on a number of other projects aimed at providing global-scale insight into the risks to native ecosystems and the potential for and knock-on effects of reforestation. 


------------------------------------------------

-------------------------------------------------

##### Acknowledgements:

This site is derived from the [academicpages.github.io](https://github.com/academicpages/academicpages.github.io) template.

