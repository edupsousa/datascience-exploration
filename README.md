# Data Science Explorations and Toy Projects

This repository contains some toy projects used by me to learn data science and machine learning topics.

You can run the notebooks using docker-compose, but it's configured by default to use the nvidia runtime of docker, and gpu based tensorflow package.

If you intend to use it on a CPU only machine you must remove the `runtime: nvidia` line from _docker-compose.yml_ and change the tensorflow base image to `tensorflow/tensorflow:latest-cpu-py3` on _jupyter-gpu/Dockerfile_.

Disclaimer: The solely objective of the projects on this repository is to learn data science and machine leaning topics. Take all data and plots presented by those projects with a grain of salt.

## Projects

### ./eleicoes2018

This project analyzes data gathered from brazilian 2018 national elections. The main data was gathered from the public repository [_DivulgaCand_](http://www.tse.jus.br/eleicoes/estatisticas/repositorio-de-dados-eleitorais-1/repositorio-de-dados-eleitorais).