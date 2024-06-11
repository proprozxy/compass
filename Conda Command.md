# Conda Command

**Env**

```bash
conda env list
```

```bash
conda create --name env_name python=3.8
```

```bash
conda activate env_name
```

```bash
conda deactivate
```

```bash
conda remove --name env_name --all
```

```bash
conda remove --name env_name package_name
```

```bash
conda env export --name myenv > myenv.yml
```

```bash
conda env create -f myenv.yml
```

```bash
conda list --explicit > spec-file.txt
```

```bash
conda create --name myenv --file spec-file.txt
```

**Package**

```bash
conda list
```

```bash
conda install package_name
```

```bash
conda install package_name -c conda_forge
```

```bash
conda update package_name
```

```bash
conda uninstall package_name
```

```bash
conda clean -p
conda clean -t
conda clean -y
```

go to `conda clean -h`

 
