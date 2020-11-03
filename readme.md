```py
# update conda
conda update -n base -c defaults conda

# create new env
conda create -n name_of_my_env python
# location
environment location: /usr/local/Caskroom/miniconda/base/envs/name_of_my_env
# activate
conda activate name_of_my_env
# deactivate
conda deactivate
```

```py
conda config --add channels conda-forge

conda install panda
conda install ipykernel
conda install matplotlib

# OpenCV
conda install open
```

```py
# python formatter
pip install --upgrade --user autopep8
```