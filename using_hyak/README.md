These materials accompany the "Using Hyak, Linux Operating System" workshop held on June 25, 2024. The walk-through tutorial is available on Hyak's documentation website (hyak.uw.edu). Files here are used in the tutorial.

* locator_NN_job.slurm - template single job SLURM submission script. 
* locator_NN_array.slurm - template array job SLURM submission script.
* data sub-directory - Our adaptation of *Populus trichocarpa* genotype data and locations are licensed under a CC0 1.0 Universal (CC0 1.0) Public Domain Dedication license. Original genotyping results available on DRYAD https://doi.org/10.5061/dryad.1051d. Data were published as part of a study https://doi.org/10.1111/1755-0998.12056.
    * potr_genotypes.txt - sample genotype data used for the SLURM demonstration 
    * potr_m_pred0.txt - sample location data (set 0) used for the SLURM demonstration. 
    * potr_m_pred1.txt - sample location data (set 0) used for the SLURM demonstration.
    * potr_m_pred2.txt - sample location data (set 0) used for the SLURM demonstration.
    * potr_m_pred3.txt - sample location data (set 0) used for the SLURM demonstration.
    * potr_m_pred4.txt - sample location data (set 0) used for the SLURM demonstration.

Additional publicly available resources: 
* Locator Neural Network from https://elifesciences.org/articles/54507. Locator Neural Network code is available on GitHub: https://github.com/kr-colab/locator.git 
* The Dockerfile for the containerized version of Locator Neural Network: https://github.com/finchnSNPs/Docker_kr-colab_locator
* The Docker container to run Locator Neural Network is available on DockerHub: https://hub.docker.com/repository/docker/finchnsnps/locator/general

License information: 
* Locator Neural Network is a copyright 2019 of C. J. Battey and released under a Non-Profit Open Software License 3.0 (NPOSL-3.0).
* Our adaptation of *Populus trichocarpa* genotype data and locations are licensed under a CC0 1.0 Universal (CC0 1.0) Public Domain Dedication license.