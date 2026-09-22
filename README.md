# Large Deviation Stochastic Optimisation (LDSTOP)

Companion code for the article **Stochastic optimisation method for estimating large deviations**, implementing a stochastic optimisation method to estimate the rate function, scaled cumulant generating function (SCGF), and driven process for general observables of Markov processes.

## Contents

```
.
├── README.md
├── LICENSE
├── requirements.txt             # pinned package versions
├── runtime.txt                  # Python version used
└── notebooks/
    └── ldstop_IID.ipynb         # notebook for IID random variable sample means
    └── ldstop_Chain.ipynb       # notebook for Markov chain observables
    └── ldstop_Jump.ipynb        # notebook for Markov jump process observables
    └── ldstop_Diffusion.ipynb   # notebook for Markov diffusion observables
```

## Setup

1. Clone the repo:
   ```bash
   git clone https://github.com/DanielWHCloete/ldstop.git
   cd ldstop
   ```

2. Create a virtual environment (see `runtime.txt` for the exact Python version used):
   ```bash
   python -m venv venv
   source venv/bin/activate   # Windows: venv\Scripts\activate
   ```

3. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

4. Launch Jupyter and open the notebook:
   ```bash
   jupyter notebook notebooks/ldstop_IID.ipynb
   ```

## Citation

If you use this code, please cite:

> Daniël W. H. Cloete and Hugo Touchette. (2026). *Stochastic optimisation method for estimating large deviations*. arXiv preprint arXiv:2609.24473. https://doi.org/10.48550/arXiv.2609.24473

```bibtex
@misc{cloete2026stochastic,
    title={Stochastic optimisation method for estimating large deviations}, 
    author={Dani{\"e}l W. H. Cloete and Hugo Touchette},
    year={2026},
    eprint={2609.24473},
    archivePrefix={arXiv},
    primaryClass={cond-mat.stat-mech},
    url={https://arxiv.org/abs/2609.24473}, 
}
```


## License

MIT — see [LICENSE](LICENSE) for details.