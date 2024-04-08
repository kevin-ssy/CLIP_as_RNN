# CLIP as RNN: Segment Countless Visual Concepts without Training Endeavor

[Shuyang Sun*](https://kevin-ssy.github.io/), [Runjia Li*](https://runjiali-rl.github.io/), [Philip Torr](https://eng.ox.ac.uk/people/philip-torr/), [Xiuye Gu](https://laoreja.github.io/), [Siyang Li](https://siyangl.github.io/)

<div align="center">
  <img src="https://torrvision.com/images/images_for_pub/clip_as_rnn_teaser.png" width="100%" height="100%"/>
</div><br/>

The README doc is currently under development.

## Installation

### Requirements
- Anaconda 3
- PyTorch ≥ 1.7 and [torchvision](https://github.com/pytorch/vision/) that matches the PyTorch installation.
  Install them together at [pytorch.org](https://pytorch.org) to make sure of this.
- `conda env create --name ENV_NAME --file=car_env.yml`

## Getting Started

### Demo

We have set up an online demo. You can check it out at: [TODO](.)

### Run Demo Locally

If you want to test an image locally, you can simply run

`python3 demo.py --cfg-path=YOUR_CFG_PATH --output_path=SAVE_PATH`

### Evaluation with Benchmarks

- Data preparation: See [Preparing Datasets for CaR](DATA.md)
