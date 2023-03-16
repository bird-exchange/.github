## This is web application for using CycleGan network.
The neural network used is taken from <a href="https://github.com/vladimirprotsenko/DLS_project_2022">DLS_2022</a>, and it turns sparrows into tits and vice versa.

home page|main page
:-:|:-:
![Alt-текст](https://github.com/bird-exchange/.github/blob/main/profile/background.png?raw=true) | ![Alt-текст](https://github.com/bird-exchange/.github/blob/main/profile/example.png?raw=true)

## Technical stack
Flask, Minio, PostgreSQL

## Project structure

The service consists on three parts: backend, frontend, and worker. For running on localhost all need to be cloned:

```bash
git clone https://github.com/bird-exchange/backend.git
git clone https://github.com/bird-exchange/frontend.git
git clone https://github.com/bird-exchange/worker.git
```
Checpoints arxiv from <a href="https://disk.yandex.ru/d/0_wNLkkyLIRdJA">here</a> need to be saved in \worker\worker\handler\checkpoints\.

### Start up
