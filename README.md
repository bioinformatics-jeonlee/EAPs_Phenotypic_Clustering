<!-- TABLE OF CONTENTS -->
## Table of Contents

* [About the Project](#about-the-project)
* [Uploaded Files](#uploaded-files)
* [Getting Started](#getting-started)
* [Contributing](#contributing)
* [License](#license)
* [Contact](#contact)
* [Acknowledgements](#acknowledgements)



<!-- ABOUT THE PROJECT -->
## About The Project

This EAPs (endocytic accessory proteins) phenotypic clustering project is a part of a 'EAPs Functional Characterization' study, 
of which results were submitted to PNAS under the title 
"Functional characterization of 67 endocytic accessory proteins using multi-parametric quantitative analysis of CCP dynamics" 
in September, 2020

The goal of this project is, in a robust computational way, to cluster 67 EAPs based on their phenotypic characteristics. 


<!-- UPLOADED FILES -->
## Uploaded Files
There are three files uploaded here. Please find the file names and their descriptions below:
* 'EAP_Phenotype_Data.csv' : phenotypic data consisting of 67 EAPs and their 4 phenotype parameters, that is, 'CCP initiation', 'CLS initiations',	
'mean lifetimes', and	'pctCCP'
* 'EAPs_Phenotypic_Clustering.Rmd' : R markdown file containing all the R commands used for the EAPs' phenotypic clustering
* 'EAPs_Phenotypic_Clustering.html' : R markdown output file showing all the steps to cluster the EAPs and each step's results


<!-- GETTING STARTED -->
## Getting Started

To run the R markdown or R script, 'EAP_Phenotype_Data.csv' has to be located in the same folder and several R packages have to be installed in advance. 
These packages are: `data.table`; `factoextra`; `ggplot2`; `ggfortify`; `apcluster`; `Biobase`; `knitr`; `kableExtra`.




<!-- CONTRIBUTING -->
## Contributing

Contributions are what make the open source community such an amazing place to be learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request



<!-- LICENSE -->
## License

Distributed under the MIT License. See `LICENSE` for more information.



<!-- CONTACT -->
## Contact

If you have any questions or comments, please contact any of us:

Jeon Lee - Jeon.Lee@UTSouthwestern.edu

Marcel Mettlen - Marcel.Mettlen@UTSouthwestern.edu

Xinxin Wang - Xinxin.Wang@UTSouthwestern.edu

Project Link: [https://github.com/bioinformatics-jeonlee/EAPs_Phenotypic_Clustering](https://github.com/bioinformatics-jeonlee/EAPs_Phenotypic_Clustering)



<!-- ACKNOWLEDGEMENTS -->
## Acknowledgements
* Jeon Lee was supported by the Cancer Prevention Research Institute of Texas (CPRIT, RP150596). 
* This work was supported by NIH grant MH61345 to Sandra L. Schmid.
* This work was supported by NIH grant GM73165 to Sandra L. Schmid, Gaudenz Danuser and Marcel Mettlen.
