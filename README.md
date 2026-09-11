# Awesome-Research-Computing-Platform

## Top Research Computing Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Interactive Computing, Notebooks, HPC Access, Collaborative Data Science & Research Workspaces*

**Last updated: September 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** for **Research Computing**. These systems provide researchers and data scientists with interactive environments (Jupyter, RStudio, VS Code, etc.), scalable compute, collaboration features, and simplified access to HPC or cloud resources.



**Examples** include Posit Workbench, Domino Data Lab, Open OnDemand, Saturn Cloud, CoCalc, JetBrains Datalore, Hex, Deepnote, Anaconda Notebooks, and Databricks (the category leaders).



**Open-source emphasis**: Research computing has excellent open foundations. **Open OnDemand** is the leading open-source web portal for HPC access; **JupyterHub / Jupyter** ecosystems, **CoCalc**, and related tools power many institutional deployments. This section is heavily expanded with these projects.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Posit Workbench](https://posit.co/products/enterprise/workbench/)**  

  Enterprise platform for centralized Python and R data science development with support for Positron, RStudio, VS Code, Jupyter, and strong governance features.



- **[Domino Data Lab](https://www.dominodatalab.com/)**  

  Enterprise MLOps and data science platform providing collaborative workspaces, experiment tracking, and scalable compute for research and production teams.



- **[Saturn Cloud](https://saturncloud.io/)**  

  Cloud platform for data science and ML offering managed Jupyter, Dask, and scalable computing environments.



- **[CoCalc](https://cocalc.com/)**  

  Collaborative calculation platform with Jupyter, Sage, LaTeX, and real-time collaboration (open-source core with hosted offerings).



- **[JetBrains Datalore](https://www.jetbrains.com/datalore/)**  

  Collaborative data science notebook platform with smart coding assistance and team features from JetBrains.



- **[Hex](https://hex.tech/)**  

  Modern collaborative data workspace combining notebooks, apps, and data apps for analytics and research teams.



- **[Deepnote](https://deepnote.com/)**  

  Collaborative data science notebook platform focused on real-time teamwork and easy sharing.



- **[Anaconda Notebooks](https://www.anaconda.com/)**  

  Hosted notebook environments and package management from the Anaconda ecosystem for data science workflows.



- **[Databricks](https://www.databricks.com/)**  

  Unified analytics and AI platform built on Apache Spark, widely used for large-scale research and data science workloads.



- **[Other managed research & data science workspaces](https://github.com/)**  

  Additional cloud notebook and research computing services offering Jupyter-centric or multi-language environments.



## Open-Source GitHub Projects

- **[Open OnDemand](https://openondemand.org/)**  

  Leading open-source web portal (MIT) that gives researchers browser-based access to HPC resources — file management, job submission, interactive apps (Jupyter, RStudio, VS Code, desktops), and terminal access without complex client setup.



- **[JupyterHub](https://github.com/jupyterhub/jupyterhub)**  

  Multi-user Hub for spawning, managing, and proxying multiple instances of the single-user Jupyter notebook server — the foundation of many institutional research computing environments.



- **[JupyterLab / Jupyter Notebook](https://github.com/jupyterlab/jupyterlab)**  

  Core open-source interactive computing interface used worldwide for research, education, and data science.



- **[CoCalc (open-source)](https://github.com/sagemathinc/cocalc)**  

  Open-source collaborative platform supporting Jupyter, SageMath, LaTeX, terminals, and real-time collaboration; can be self-hosted.



- **[RStudio Server / Posit open components](https://github.com/rstudio)**  

  Open-source server components that power many R-focused research computing deployments (commercial Workbench builds on these foundations).



- **[Binder / repo2docker](https://github.com/jupyterhub/binderhub)**  

  Open tools for turning Git repositories into shareable, executable research environments.



- **[The Littlest JupyterHub (TLJH) and Zero to JupyterHub](https://github.com/)**  

  Simplified deployment projects for running JupyterHub on single servers or Kubernetes for research groups.



- **[Interactive HPC app frameworks for Open OnDemand](https://github.com/)**  

  Community apps that launch Jupyter, RStudio, MATLAB, and other tools as interactive sessions on cluster compute nodes.



- **[Dask, Ray, and open scalable computing frameworks](https://github.com/)**  

  Libraries frequently deployed inside research computing platforms for parallel and distributed workloads.



- **[Custom research portals built on JupyterHub + Identity providers](https://github.com/)**  

  Institutional deployments that combine open authentication, storage, and scheduling with Jupyter-based interfaces.



### Additional Strong Open-Source Options

- Deploying **Open OnDemand** as the primary web gateway to institutional HPC clusters.

- Running **JupyterHub** (with TLJH or Kubernetes) for departmental or lab-scale interactive computing.

- Self-hosting **CoCalc** for collaborative teaching and research environments.

- Combining open notebook servers with institutional identity, storage, and job schedulers (Slurm, etc.).

- Accepting that polished enterprise governance, commercial support, advanced collaboration features, and fully managed cloud scale still favor platforms like Posit Workbench, Domino, Databricks, and Saturn Cloud for many organizations.



**Frameworks for building custom systems**: Deploy Open OnDemand or JupyterHub → integrate with cluster scheduler and shared storage → offer JupyterLab, RStudio, and VS Code as interactive apps → add authentication and resource quotas → monitor usage. This stack is the standard open approach at many research computing centers. Commercial platforms (Posit Workbench, Domino Data Lab, Saturn Cloud, Hex, Deepnote, Databricks, etc.) remain attractive when institutions want managed services, tighter collaboration features, or reduced operational overhead.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Research computing platforms often handle sensitive data, proprietary code, and regulated workloads. Proper authentication, authorization, data isolation, audit logging, and compliance controls are essential. Self-hosted open-source deployments require ongoing security maintenance, resource management, and user support. Always align with institutional IT and research data policies. This list is not security or research computing architecture advice.



---

**Made for research computing centers, data science teams, and academic IT groups who want accessible, powerful interactive environments.**

Let's keep research computing open, scalable, and researcher-friendly.
