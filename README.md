# Data-Driven Discovery of Partial Differential Equations
Partial Differential Equations (PDEs) play a pivotal role in understanding numerous natural phenomena. These equations describe how quantities change over space and time, and they are vital in fields ranging from physics to biology.

Traditionally, deriving these equations has required a comprehensive grasp of the phenomena in question. However, there are systems so intricate that deducing a PDE based solely on theoretical understanding becomes daunting.

This project investigates an alternative approach: the discovery of PDEs through data. Rather than theorizing, we use observed data to deduce the governing equations of a system. This data-centric method uses measurements taken at various intervals, both in time and space, to pinpoint the most fitting PDE.

Three particular types of PDEs were chosen for this exploration:

**1. The Advection Equation:** This equation describes the transportation of some quantity by a flow. Imagine a dye being spread by a moving fluid; the advection equation would help us understand how the dye moves with the fluid.

**2. The Diffusion Equation:** This pertains to how a certain quantity spreads out over time. Think of a drop of ink in water; the diffusion equation would capture how the ink disperses.

**3. The Burgers' Equation:** A combination of the advection and diffusion equations, the Burgers' equation has significance in fluid mechanics. It's a simplified model for studying phenomena like shock waves.

For this project, the [PDE-FIND](https://github.com/snagcliffs/PDE-FIND/blob/master/PDE_FIND.py) program was employed. This tool, developed by Samuel Rudy, aims at identifying PDEs based on data. It's rooted in the work documented his research paper ["Data Driven Discovery of Partial Differential Equations"](https://github.com/snagcliffs/PDE-FIND/blob/master/sci_adv.pdf) that delves into the data-driven discovery of differential equations.

This repository contains the code used in our investigation, along with visual representations in the form of graphs and relevant tables that detail our findings. By navigating through, you'll gain insights into our data-driven approach to discovering Partial Differential Equations.
