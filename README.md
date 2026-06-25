# ggsashimi Hands-On
This repository documents the completion of the ggsashimi Docker hands-on exercise.

The exercise consisted of:
* Pulling the official Docker image from DockerHub.
* Running the example provided in the official repository.
* Successfully generating a sashimi plot (sashimi.pdf).

The original ggsashimi software is developed and maintained by Guigo Lab.

Official GitHub repository:
https://github.com/guigolab/ggsashimi

Official Docker image:
```bash
docker pull guigolab/ggsashimi
```

Example command used:
```bash
docker run --rm \
-w $PWD \
-v $PWD:$PWD \
guigolab/ggsashimi \
-b examples/input_bams.tsv \
-c chr10:27040584-27048100
```

Output generated:
* sashimi.pdf

This repository only contains the output generated during the exercise and does not redistribute the original source code.
