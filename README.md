# COLMENA Framework

COLMENA (COLaboración entre dispositivos Mediante tecnología de ENjAmbre) aims to ease the development, deployment, operation and maintenance of extremely-high available, reliable and intelligent services running seamlessly across the device-edge-cloud continuum. It leverages a swarm approach organising a dynamic group of autonomous, collaborative nodes following an agile, fully-decentralised, robust, secure and trustworthy open architecture. This repository contains stable combinations of versions for the components of the Colmena framework included in the other repositories of the organization.

## Table of Contents
- [Release Information](#release-information)
- [Repository Structure](#repository-structure)
- [Getting Started](#getting-started)
- [License](#license)



## Release Information
The versions in this commit correspond to the the first version of the framework (0.0.1) released for the EuroPar 2024 conference.

## Repository Structure
The repository is organized into the following directories and files:

### Directories
- **service-tools**: Contains all the code necessary to deploy a COLMENA Agent.
    - **programming-model**: submodule containing all the files and software necessary to create COLMENA applications 
    - **deployment-tool**: submodule containing all the files and software necessary to deploy a COLMENA application on a platform
- **agent**: Contains all the necessary code construct a COLMENA platform on the underlying infrastructure.

### Files
- **.gitignore**: Specifies files and directories to be ignored by Git.
- **LICENSE**: License information for the repository.
- **README.md**: Overview of the repository, setup instructions, and basic usage examples.



## Getting Started
1. Clone this repository with its submodules using --recurse-submodules flag 
    ```bash
    git clone --recurse-submodules https://github.com/colmena-swarm/framework.git
    ```
    Alternatively, if you have already cloned the repository without submodules, initialize and update the submodules manually.
    ```bash
    git submodule update --init --recursive
    ```

2. Further instructions on how to use each of the components are provided within the README file in the root folder of the corresponding repository.

## License
The COLMENA programming model is released under the Apache 2.0 license.
Copyright © 2022-2024 Barcelona Supercomputing Center - Centro Nacional de Supercomputación. All rights reserved.
See the [LICENSE](LICENSE) file for more information.


<sub>
	This work is co-financed by the COLMENA project of the UNICO I+D Cloud program that has the Ministry for Digital Transformation and of Civil Service and the EU-Next Generation EU as financing entities, within the framework of the PRTR and the MRR. It has also been supported by the Spanish Government (PID2019-107255GB-C21), MCIN/AEI /10.13039/501100011033 (CEX2021-001148-S), and Generalitat de Catalunya (2021-SGR-00412).
</sub>
<p align="center">
	<img src="https://github.com/colmena-swarm/.github/blob/assets/images/funding_logos/Logos_entidades_OK.png?raw=true" width="600">
</p>

