# Open OnDemand batch connect app to run Jupyter Notebook

References:
* [ood\_rstudio\_apptainer](https://github.com/uwsph/ood_rstudio_apptainer)
* [bc\_osc\_rstudio\_server](https://github.com/OSC/bc_osc_rstudio_server)
* [ood\-bih\-rstudio\-server](https://github.com/bihealth/ood-bih-rstudio-server)
* [bc\_osc\_example\_jupyter](https://github.com/OSC/bc_example_jupyter)

## License
- MIT (see `LICENSE` file)

## Usage
Designed to utilize [Continuum](https://hub.docker.com/u/continuumio/) images (or similar), converted to Singularity containers.
For example:
```bash
singularity pull docker://continuumio/anaconda3:latest
```
