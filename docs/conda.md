# How to Conda

Conda helps you manage python environments
- source compatible libraries with your cpu architecture/os from diferent upstreams
- export/import environment setups
- install instructions [here](https://docs.conda.io/en/latest/miniconda.html)
- cheat sheet [here](https://docs.conda.io/projects/conda/en/latest/_downloads/843d9e0198f2a193a3484886fa28163c/conda-cheatsheet.pdf)


## Examples

- Export environment into a file
```bash
conda env export > environment.yml
```

- Import environment from a file

```bash
conda env create -f environment.yml
```

- Activate an environment, works like stack insert

```bash
conda activate -n myenvironmentname
```

- Deactivate an environment, works like stack pop

```bash
conda deactivate
```