# JSS 2022 - Replication Package

This is the replication package of the paper entitled "An Architecture for Mission Coordination of Heterogeneous Robots" submitted to the Internation Journal of Systems and Software.

This study has been conducted by the following investigators:

- [Gabriel Rodrigues](https://github.com/gabrielsr/) (University of Brasília, Brazil)
- [Ricardo Caldas](https://github.com/rdinizcal/) (Chalmers University of Technology, Sweden)
- [Gabriel Araujo](https://github.com/Gastd/) (University of Brasília, Brazil)
- [Vicente de Moraes](https://github.com/VicenteMoraes/) (University of Brasília, Brazil)
- [Genaína Rodrigues](https://genaina.github.io/) (University of Brasília, Brazil)
- [Patrizio Pellicione](http://www.patriziopelliccione.com/) (Gran Sasso Scientific Institute (GSSI), Italy)

### Overview of the replication package

├── <a href="/architecture_inspection/">architecture_inspection</a>: Artifacts for reproducing the architecture inspection process of Section 6.2<br>
&nbsp;&nbsp;&nbsp;├── <a href="/architecture_inspection/integrability/">integrability</a>: Contains the working model for answering "How integrable is MissionControl?"<br>
&nbsp;&nbsp;&nbsp;└── <a href="/architecture_inspection/modifiability/">modifiability</a>: Contains the working model for answering "How modifiable is MissionControl?"<br>
├── <a href="/controlled_experiment/">controlled_experiment</a>: Artifacts for repeating the controlled experiments of Section 6.1<br>
&nbsp;&nbsp;&nbsp;├── <a href="/controlled_experiment/analysis_scripts/">analysis_scripts</a>: Jupyter scripts for analysis of the datasets<br>
&nbsp;&nbsp;&nbsp;├── <a href="/controlled_experiment/dataset/">dataset</a>: Dataset generated from running the simulations<br>
&nbsp;&nbsp;&nbsp;├── <a href="https://github.com/lesunb/morse_simulation/tree/831ced7632fbcb6970709463ebd39666647766d4">morse_simulation</a>: Tooling for executing the controlled experiments<br>
&nbsp;&nbsp;&nbsp;└── <a href="/controlled_experiment/results/">results</a>: Graphs and plots<br>
└── <a href="https://github.com/gabrielsr/hmrs_mission_control/tree/87d11ba214925c0a6ac618cd4f2ac73d97eb0424">hmrs_mission_control</a>: Implementation of MissionControl<br>
