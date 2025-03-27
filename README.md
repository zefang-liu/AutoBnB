# AutoBnB: Backdoors & Breaches with AutoGen

This project investigates the use of large language models (LLMs) for enhancing collaboration and decision-making in cybersecurity incident response scenarios. Built on the *[AutoGen](https://microsoft.github.io/autogen/)* framework for multi-agent system simulation, it uses the *[Backdoors & Breaches](https://www.blackhillsinfosec.com/projects/backdoorsandbreaches/)* tabletop game as a simulation platform to explore how LLM-based multi-agent systems perform under various team structures. Through these simulations, the project provides insights into optimizing team dynamics and strategies to counter cyber threats effectively.

## Installation

Set up the environment by installing the required dependencies:
```bash
pip install -r requirements.txt
```

## Usage

Launch the simulation using the Jupyter notebook:
```bash
jupyter notebook notebooks/autobnb_core.ipynb
```
or
```bash
jupyter notebook notebooks/autobnb_expansion.ipynb
```

## Paper

If you found this repository useful, please cite our [paper](https://arxiv.org/abs/2412.00652) as follows:
```bibtex
@article{liu2024multi,
  title={Multi-Agent Collaboration in Incident Response with Large Language Models},
  author={Liu, Zefang},
  journal={arXiv preprint arXiv:2412.00652},
  year={2024}
}
```

## License

This repository is available under the [MIT license](LICENSE).

## Acknowledgement

This project utilizes *[Backdoors & Breaches](https://www.blackhillsinfosec.com/projects/backdoorsandbreaches/)* cards, which are the intellectual property of [Black Hills Information Security](https://www.blackhillsinfosec.com/) and [Active Countermeasures](https://www.activecountermeasures.com/). We acknowledge their invaluable contribution to cybersecurity research. These cards are used solely for research purposes in this study.
