---
title: PySyft
description: PySyft decouples private data from model training, using Federated Learning, Differential Privacy, and Encrypted Computation (like Multi-Party Computation (MPC) and Homomorphic Encryption (HE) within the main Deep Learning frameworks like PyTorch and TensorFlow.
layout: template
filename: index
--- 

<h1 align="center">
  <br>
  <a href="http://duet.openmined.org/"><img src="https://raw.githubusercontent.com/OpenMined/PySyft/dev/docs/img/logo_big.png" alt="PySyft" width="200"></a>
  <br>
  A library for computing on data<br /> you do not own and cannot see
  <br>
</h1>
<div align="center">
  <a href=""><img src="https://github.com/OpenMined/PySyft/workflows/Tests/badge.svg?branch=master" /></a> <a href=""><img src="https://github.com/OpenMined/PySyft/workflows/Tutorials/badge.svg" /></a> <a href="https://openmined.slack.com/messages/lib_pysyft"><img src="https://img.shields.io/badge/chat-on%20slack-7A5979.svg" /></a> <a href="https://mybinder.org/v2/gh/OpenMined/PySyft/master"><img src="https://mybinder.org/badge.svg" /></a> <a href="http://colab.research.google.com/github/OpenMined/PySyft/blob/master"><img src="https://colab.research.google.com/assets/colab-badge.svg" /></a><br /><br />
</div>

PySyft is a Python library for secure and private Deep Learning. PySyft decouples
private data from model training, using
[Federated Learning](https://ai.googleblog.com/2017/04/federated-learning-collaborative.html),
[Differential Privacy](https://en.wikipedia.org/wiki/Differential_privacy),
and Encrypted Computation (like
[Multi-Party Computation (MPC)](https://en.wikipedia.org/wiki/Secure_multi-party_computation)
and  [Homomorphic Encryption (HE)](https://en.wikipedia.org/wiki/Homomorphic_encryption)
within the main Deep Learning frameworks like PyTorch and TensorFlow. Join the movement on
[Slack](http://slack.openmined.org/).

## FAQ 0.2.x ➡️ 0.3.x
We have compiled a list of [FAQs](docs/FAQ_0.2.x.md) relating to the change from 0.2.x to 0.3.x+ [here](docs/FAQ_0.2.x.md).

_**Important note about PySyft 0.2.x:** The PySyft 0.2.x codebase is now in its own branch [here](https://github.com/OpenMined/PySyft/tree/syft_0.2.x), but OpenMined will not offer official support for this version range. If you're getting started with PySyft for the first time, please ignore this message and read on!_

## PySyft in Detail

A more detailed explanation of PySyft can be found in the
[white paper on Arxiv](https://arxiv.org/abs/1811.04017).

PySyft has also been explained in videos on YouTube:
 - [PriCon Sep 2020 Duet Demo](https://www.youtube.com/watch?v=DppXfA6C8L8&ab_channel=OpenMined)
 - [Introduction to Privacy-Preserving AI using PySyft by @iamtrask](https://www.youtube.com/watch?v=NJBBE_SN90A)
 - [Introduction to PySyft codebase by @andreiliphd](https://www.youtube.com/watch?v=1Zw08_4ufHw)
 - [Differential Privacy & Federated Learning explained using PySyft by Jordan Harrod](https://www.youtube.com/watch?v=MOcTGM_UteM)

## Pre-Installation

PySyft is available on PyPI and Conda.

We recommend that you install PySyft within a virtual environment like
[Conda](https://docs.conda.io/projects/conda/en/latest/user-guide/overview.html),
due to its ease of use. If you are using Windows, we suggest installing
[Anaconda and using the Anaconda
Prompt](https://docs.anaconda.com/anaconda/user-guide/getting-started/) to
work from the command line.

```bash
$ conda create -n pysyft python=3.8
$ conda activate pysyft
$ conda install jupyter notebook
```

## Version Support

We support **Linux**, **MacOS** and **Windows** and the following Python and Torch versions.

Python | Torch 1.5 | Torch 1.6 | Torch 1.7
--- | --- | --- | ---
3.6 | ✅ | ✅ | ✅
3.7 | ✅ | ✅ | ✅
3.8 | ✅ | ✅ | ✅

## Installation

### Pip
```bash
$ pip install syft
```

This will auto-install PyTorch and other dependencies as required, to run the
examples and tutorials. For more information on building from source see the contribution guide [here](https://github.com/OpenMined/PySyft/tree/master/CONTRIBUTING.md).

## Documentation
The latest official documentation is hosted here: [https://pysyft.readthedocs.io/](https://pysyft.readthedocs.io/en/latest/index.html#)

## Duet Examples

All the examples can be played with by launching Jupyter Notebook and navigating to
the examples/duet folder.

```bash
$ jupyter notebook
```

## WebRTC Signaling Server
To facilitate peer-to-peer connections through firewalls we utilise WebRTC and a
signaling server. After connection, no traffic is sent to this server.

If you want to run your own signaling server simply run the command:
```
$ syft-network
```

Then update your duet notebooks to use the new `network_url=http://localhost:5000`

## Try out the Tutorials

A comprehensive list of Duet Examples can be found
[here](https://github.com/OpenMined/PySyft/tree/master/examples/duet)

These tutorials cover how to operate common network types over the Duet API.

## Start Contributing

The guide for contributors can be found [here](https://github.com/OpenMined/PySyft/tree/master/CONTRIBUTING.md).
It covers all that you need to know to start contributing code to PySyft today.

Also, join the rapidly growing community of 7000+ on [Slack](http://slack.openmined.org).
The slack community is very friendly and great about quickly answering questions about the use and development of PySyft!

## Troubleshooting

The latest version of PySyft is 0.3.0 however this software is still Beta. If you find
a bug please file it in the GitHub issues.

## Organizational Contributions
We are very grateful for contributions to PySyft from the following organizations!
[<img src="https://github.com/udacity/private-ai/blob/master/udacity-logo-vert-white.png?raw=true" alt="Udacity" width="200"/>](https://udacity.com/) | [<img src="https://raw.githubusercontent.com/coMindOrg/federated-averaging-tutorials/master/images/comindorg_logo.png" alt="coMind" width="200" height="130"/>](https://github.com/coMindOrg/federated-averaging-tutorials) | [<img src="https://i.ibb.co/vYwcG9N/arkhn-logo.png" alt="Arkhn" width="200" height="150"/>](http://ark.hn) | [<img src="https://raw.githubusercontent.com/dropoutlabs/files/master/dropout-labs-logo-white-2500.png" alt="Dropout Labs" width="200"/>](https://dropoutlabs.com/)

## Support
For support in using this library, please join the **#lib_pysyft** Slack channel. [Click here to join our Slack community!](https://slack.openmined.org)

## Disclaimer
This software is in early beta. Use at your own risk.

## License
[Apache License 2.0](https://github.com/OpenMined/PySyft/blob/master/LICENSE)
[![FOSSA Status](https://app.fossa.io/api/projects/git%2Bgithub.com%2Fmatthew-mcateer%2FPySyft.svg?type=large)](https://app.fossa.io/projects/git%2Bgithub.com%2Fmatthew-mcateer%2FPySyft?ref=badge_large)

## For more details, check [PySyft](https://github.com/OpenMined/PySyft) on GitHub

## Want to Use PySyft?
If you would like to become a user of PySyft, please progress to our User Documentation.

## Want to Develop PySyft?
If you would like to become a developer of PySyft, please see our
[Contributor Documentation](CONTRIBUTING.md).
This documentation will help you set up your development environment, give you a roadmap
for learning the codebase, and help you find your first project to contribute.