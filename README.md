# stochastic-biophysics-lab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/YOUR_GITHUB_ID/stochastic-biophysics-lab/blob/main/stochastic_biophysics_practice.ipynb)

이 repository는 2026 서울대학교 여름학기 `생물물리학입문` 특강을 위한 교육자료입니다.
NumPy와 Matplotlib 기초부터 확률분포, random walk, Markov chain, birth-death model, Gillespie SSA까지 한 노트북에서 실습합니다.

## Topics

- NumPy arrays, random numbers, Matplotlib plots
- Mean, variance, standard deviation, histogram
- Bernoulli, Binomial, Poisson, Gaussian distributions
- Random walk, diffusion, Markov chain
- Poisson process, waiting time
- Birth-death model, Gillespie stochastic simulation algorithm
- Simple stochastic chemical reaction examples
- Stochastic paths, mean-field heatmap, Allee effect extinction/survival
- Simple curve fitting with SciPy

## Local Run

macOS / Linux:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
```

Windows PowerShell:

```powershell
py -m venv .venv
.\.venv\Scripts\Activate.ps1
py -m pip install -r requirements.txt
```

`py` 명령이 없으면 Windows에서도 `python`으로 바꿔 실행합니다.

설치 후 Colab, VS Code, JupyterLab, 또는 Jupyter Notebook에서 `stochastic_biophysics_practice.ipynb`를 열어 순서대로 실행합니다.

## License

MIT License
