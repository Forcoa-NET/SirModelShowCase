# Sir Model applied on Karate Club

Wellcome to ✨**SirModelShowCase**✨. This repository was created for purpose of presentation "spreading in network" to the high school students. Example contains simple Python code that loads network, runs SIR model in multiple iterations and outputs of this iterations exports to images.

## SIR

The SIR model was introduced in 1927 by Kermack [1].

In this model, during the course of an epidemics, a node is allowed to change its status from **Susceptible (S)** to **Infected (I)**, then to **Removed (R)**.

The model is instantiated on a graph having a **non-empty** set of infected nodes.

SIR assumes that if, during a generic iteration, a susceptible node comes into contact with an infected one, it becomes infected with probability beta, than it can be switch to removed with probability gamma (the only transition allowed are S→I→R).

We used **ndlib** implementation of SIR model. For more information follow [doccumentation](https://ndlib.readthedocs.io/en/latest/reference/models/epidemics/SIR.html).

## Requirements

- Python 3.8 🐍
- Visual Studio Code (Highly recomended)

## How to run

Install all required dependencies

```bash
pip install networkx
pip install matplotlib
pip install ndlib
pip install fa2l
```

Then run the script through terminal or VS Code.

## VS Code and Jupyter

With VS Code you can open **jupyter.ipnb** whitch opens jupyter dashboard. In thin dashboard you can directly see output of plots. Jupyter provides much more then just terminal. For more informations check [https://jupyter.org/](https://jupyter.org/)

## References

[1] Kermack and A. McKendrick, “A Contribution to the Mathematical Theory of Epidemics,” Proceedings of the Royal Society of London. Series A, Containing Papers of a Mathematical and Physical Character, vol. 115, no. 772, pp. 700–721, Aug. 1927
