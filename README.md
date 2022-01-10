# 🧬 DNA Sequence Compression

## 🎯 Goal

Our goal : compress genome DNA sequence efficiently in the disk.

We would like to :
- compare ZIP VS BWT compression methods
- improve our algorithm and achieve a better compression ratio than general purpose ZIP

## 🛠️ Setup

Download and extract [COVID genome](https://www.ncbi.nlm.nih.gov/nuccore/NC_045512).

### Install miniconda :

```wget https://repo.anaconda.com/miniconda/Miniconda3-latest-Linux-x86_64.sh -O ~/miniconda.sh```

```bash ~/miniconda.sh -b -p $HOME/miniconda```

```conda init``` or ```conda init zsh``` (for zsh shell)

### Install the dependencies :

```conda create -n data-compression```

```conda activate data-compression```

```conda install ipython jupyter```

```conda install -c conda-forge numpy matplotlib```

(check [this](https://exerror.com/solving-environment-failed-with-initial-frozen-solve-retrying-with-flexible-solve/) if `Solving environment: failed with initial frozen solve. Retrying with flexible solve` throws)

## 🚀 Launch the notebook :

```conda activate data-compression```

```jupyter notebook```
