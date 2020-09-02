# Cookiecutter template for basic packaging of PyTorch models

```
pip install cookiecutter
cookiecutter https://github.com/ml-illustrated/cookiecutter-pytorch-basic
# fill in your project info

cd <name_of_your_project>
# add your model definition into <name_of_your_project>/model.py, etc.
# ...

# build your python package
python setup.py bdist_wheel
```
