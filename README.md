# CordChord

## About

![CordChord thumbnail image](/assets/cordchord_thumbnail.png)

CordChord is an two-voice digital string instrument built for MCT4054 - Interactive Music Systems as part of the [Masters in Music, Communication & Technology program](https://www.uio.no/english/studies/programmes/mct-master/) at the University of Oslo.

The instrument is built using the [Bela platform](https://bela.io/).

Read more about how it works here on the MCT blog [here](https://mct-master.github.io/interactive-music/2023/12/01/jackeh-cordchord.html).

Watch a performance below:

<iframe width="560" height="315" src="https://www.youtube-nocookie.com/embed/ySrjSWU_Mf8?si=xgdRcHQOZv3tWTWr&amp;start=1053" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" allowfullscreen></iframe>

## In this Repo

- bela_files: contains files to be loaded into your Bela project
- dataset_collection: contains patches and files for creating the dataset for the regression model, and a Jupyter notebook for interpreting the collected dataset
- model_training: contains patches for training a regression model in the [Neuralnet](https://github.com/alexdrymonitis/neuralnet) external using the collected dataset
- technical_documents: contains design files, circuit diagrams, & perfboard images
- assets: images for this README