# Multi-Agent System for Metrology for Factory of the Future (Met4FoF) Code
This is supported by European Metrology Programme for Innovation and Research (EMPIR) under the project Metrology for the Factory of the Future (Met4FoF), project number 17IND12. (https://www.ptb.de/empir2018/met4fof/home/)

About
---
 - How can metrological input be incorporated into an agent-based system for addressing uncertainty of machine learning in future manufacturing?
 - Includes agent-based simulation and implementation

Get started
---
First clone the repository to your local machine as described
[here](https://help.github.com/en/articles/cloning-a-repository). To get started
with your present *Anaconda* installation just go to *Anaconda
prompt*, navigate to your local clone
```
cd /your/local/folder/agentMet4FoF
```
and execute
```
conda env create --name agentMet4FoF --file environment.yml 
```
This will create an *Anaconda* virtual environment with all dependencies
satisfied. If you don't have *Anaconda* installed already follow [this guide
](https://docs.conda.io/projects/continuumio-conda/en/latest/user-guide/install/download.html)
first, then create the virtual environment as stated above and then proceed.

First take a look at the [tutorials](./tutorials/) or start hacking the
[main_agents.py](main_agents.py) if you already are familiar with agentMet4FoF
and want to customize your agents' network.

Updates
---
 - Implemented Sensor Agent, Aggregator Agent, Predictor Agent, DecisionMaker Agent, Sensor Network Agent
 - Able to handle multiple Sensor Agents & Predictor Agents (each equipped with a different model)
 - Implemented with ZEMA condition monitoring of hydraulic system data set as use case [![DOI](https://zenodo.org/badge/DOI/10.5281/zenodo.1323611.svg)](https://doi.org/10.5281/zenodo.1323611)
 - Implemented web visualization with user interface

## Screenshot of web visualization
![Web Screenshot](https://github.com/bangxiangyong/agentMet4FoF/blob/master/screenshot_met4fof.png)

Note
---
 - In the event of agents not terminating cleanly, run ```taskkill /f /im python.exe /t``` in Windows Command Prompt to terminate all background python processes.
