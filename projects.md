---
title: Projects
---

## Tareek: Configuration-Driven Agent-Based Traffic Simulation for Any US Metro Area

<a href="/assets/img/projects/Tareek/tareek_system.jpg" target="_blank">
<img src="/assets/img/projects/Tareek/tareek_system.jpg" alt="Tareek System Architecture" style="width: 100%; cursor: zoom-in;">
</a>

<p style="text-align: center;">
<a href="https://github.com/jalal1/Tareek" target="_blank">[GitHub]</a> <a href="https://www.youtube.com/watch?v=Vlc4IO8HXN4" target="_blank">[TareeK-Web Demo]</a> <a href="#" target="_blank">[Paper] (coming soon)</a>
</p>

Tareek is an open-source traffic simulation framework that generates synthetic populations and activity schedules for MATSim, a widely-used agent-based transportation modeling platform. Given US county identifiers, the system constructs complete simulations by integrating census demographics, household travel surveys, public transit data, and road networks.

**Key Features:**
- **Population Synthesis** -- Creating artificial households matching actual census demographics
- **Activity Plan Generation** -- Scheduling realistic daily activities (work, shopping, school, etc.) based on survey data
- **Mode Choice Modeling** -- Assigning transportation modes (car, transit, walking, cycling)
- **Network Integration** -- Incorporating real road networks and transit systems
- **Traffic Count Calibration** -- Using FHWA/TMAS national traffic station data for validation
- **Web Configuration Wizard** -- Interactive interface for selecting counties on a map and exporting ready-to-run configurations
- **Multi-Survey Blending** -- Combines NHTS with regional surveys via a plugin architecture

<!-- <div style="text-align: center;">
<iframe width="560" height="315" src="https://www.youtube.com/embed/Vlc4IO8HXN4" title="Tareek Web Demo" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
</div> -->

-----------

## TAREEK-Vis: Interactive Desktop Visualization of City-Scale Agent-Based Traffic Simulations

<a href="/assets/img/projects/Tareek-Vis/tareek_vis.PNG" target="_blank">
<img src="/assets/img/projects/Tareek-Vis/tareek_vis.PNG" alt="TAREEK-Vis" style="width: 100%; cursor: zoom-in;">
</a>

<p style="text-align: center;">
<a href="https://www.youtube.com/watch?v=Q7_H5vv58Go" target="_blank">[Demo Video]</a> <a href="#" target="_blank">[Paper] (coming soon)</a>
</p>

Agent-based traffic simulators such as MATSim produce massive event logs -- often several gigabytes of timestamped vehicle movements for a single metropolitan day -- that are difficult to inspect, validate, and communicate. Existing visualization tools are either commercial and capped to a few hundred agents in their free tier, or web-based dashboards better suited to aggregate charts than to fluid, frame-accurate animation of every vehicle. TAREEK-Vis is a desktop application that replays an entire simulation day at interactive frame rates on commodity hardware. A one-time binary preprocessing step, a compact per-vehicle index, spatial indexing, and GPU-based rendering let the system animate hundreds of thousands of moving agents over the road network while overlaying public-transit lines and stops, background map tiles, and a side-by-side comparison of simulated versus observed link counts.

**Key Features:**
- **City-Scale Animation** -- Replays hundreds of thousands of moving agents at interactive frame rates on commodity hardware
- **GPU-Based Rendering** -- Fluid, frame-accurate animation backed by binary preprocessing, a compact per-vehicle index, and spatial indexing
- **Interactive Exploration** -- Pan, zoom, seek to any moment in time, track individual vehicles, and inspect stops and routes
- **Transit & Map Overlays** -- Public-transit lines and stops layered over background map tiles
- **Calibration View** -- Side-by-side comparison of simulated versus observed link counts
- **Reporting Tools** -- Export figures and videos for reporting

TAREEK-Vis is the visualization companion to [Tareek](https://github.com/jalal1/Tareek), an automated pipeline our group develops for building MATSim scenarios of arbitrary U.S. metropolitan areas, and it consumes standard MATSim files from any source. We illustrate its use on real MATSim scenarios for four U.S. metropolitan areas, interactively exploring congestion, transit operations, and calibration quality. We will release the source code under an open-source license upon publication.

-----------

## Birmingham Mobility Research Portal

<a href="/assets/img/projects/BMRP/bmrp_main_page_2.png" target="_blank">
<img src="/assets/img/projects/BMRP/bmrp_main_page_2.png" alt="Birmingham Mobility Research Portal Main Page" style="width: 100%; cursor: zoom-in;">
</a>

<p style="text-align: center;">
<a href="https://almt0.github.io/" target="_blank">[Portal]</a> <a href="https://doi.org/10.13140/RG.2.2.26881.01127" target="_blank">[Paper]</a>
</p>

The Birmingham Mobility Research Portal makes comprehensive multimodal trip datasets for the city of Birmingham, Alabama, publicly available to researchers. It provides plans for various modes of transportation -- including private vehicles, public transit, micro-mobility, and ride-hailing services -- to support work in traffic simulation, crime prediction, epidemiological studies, and disaster response planning. Beyond the actual survey data, the portal offers synthetic datasets generated through a novel simulation system, enabling the exploration of diverse scenarios and scales, and provides access to datasets of different sizes through its website.

-----------