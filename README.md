# ACQM-Net: dataset access index

This page lists the third-party image-quality datasets used in the manuscript *Adapting pretrained blind image quality predictors through continuous quality modeling and image-dependent correction*. The linked datasets remain with their original providers; this repository does not redistribute their images.

| Dataset | Role in the manuscript | Source |
| --- | --- | --- |
| Blurred Image Database (BID) | Target evaluation | [BID download links in the UNIQUE repository](https://github.com/zwx8981/UNIQUE#link-to-download-the-bid-dataset) |
| LIVE In the Wild Image Quality Challenge Database (CLIVE/LIVEC) | Target evaluation | [University of Texas at Austin](https://live.ece.utexas.edu/research/ChallengeDB/) |
| KonIQ-10K | Target evaluation | [DaRUS dataset record](https://darus.uni-stuttgart.de/dataset.xhtml?persistentId=doi:10.18419/darus-2435) |
| LIVE Image Quality Assessment Database | Target evaluation | [University of Texas at Austin](https://live.ece.utexas.edu/research/Quality/subjective.htm) |
| Categorical Subjective Image Quality (CSIQ) database | Target evaluation | [Southern Methodist University](https://s2.smu.edu/~eclarson/csiq.html) |
| KADID-10K | Target evaluation | [University of Konstanz](https://database.mmsp-kn.de/kadid-10k-database.html) |
| SPAQ | Source pretraining for the source-disjoint control | [Official SPAQ repository](https://github.com/h4nwei/SPAQ) |

The manuscript describes the evaluation protocols, including target split seeds 20–29 for the main comparison and seeds 20–24 for the SPAQ-pretrained control. This page is a dataset access index, not a complete replication package. The image-level partitions, additional predictions, and training code should be linked here if and when the authors make them available.

Dataset access and reuse remain subject to each provider's terms. Please cite the original dataset publications listed in the manuscript.
