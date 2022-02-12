# systemtwo
A framework for developing artificial intelligence (AI)-enabled clinical decision support systems (CDSS) and administering usability tests.

## Get Started Now

 - Req 1: [Docker Desktop](https://www.docker.com/products/docker-desktop)

Navigate to the directory you wish to store systemtwo and run the following command:

```
gh repo clone LeRicNet/systemtwo && systemtwo/launch
```

Afterwards, open your web browser and go to https://localhost.

*NOTE*: the initial launch of systemtwo will take additional time to download the necessary dependencies and compose the docker containers. After the first launch, this startup sequence is much faster.

## About


## Advanced Usage
Mac: If you wish to point your server to a new domain name (e.g., https://systemtwo.co), you can add the following line to `/etc/hosts`.

```
127.0.0.1	systemtwo.co
```

### Backend/Frontend Interface
PHP and JavaScript backend provided by [Laravel](https://laravel.com/). Bootstrap theme template provided by [Start Bootstrap](https://startbootstrap.com/theme/sb-admin-2). Medical image viewing capabilities provided by the [Open Health Imaging Foundation (OHIF) Viewer](https://github.com/OHIF/Viewers). AI functionality developed using the [TensorFlow (TF) framework](https://www.tensorflow.org/) and associated ecosystem (i.e., [TFX](https://www.tensorflow.org/tfx), [TF.js](https://www.tensorflow.org/j)).

## Troubleshooting
Please report any issues, comments, or questions to Eric Prince via email Eric.Prince@CUAnschutz.edu, or [file an issue](https://github.com/LeRicNet/systemtwo/issues).

## Acknowledgements
This work was funded by the [Morgan Adams Foundation for Pediatric Brain Tumor Research](https://www.morganadamsfoundation.org/?gclid=Cj0KCQiA0p2QBhDvARIsAACSOOMVd2YC_hwbaZ_9JnfqNG5_gkrmuNT3id6ygwikIaISFkod13PyJsgaAi85EALw_wcB).