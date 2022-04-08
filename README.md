# tds_optimisation

Scripts for the article [Parametric optimisation based on TDS experiments for rapid and efficient identification of hydrogen transport materials properties. Nuclear Materials and Energy, 100984, (2021).](https://doi.org/10.1016/j.nme.2021.100984)

1. Run a FEniCS docker container

```
docker run -ti -v $(pwd):/home/fenics/shared quay.io/fenicsproject/stable:latest
```

2. Install FESTIM 0.2.1

```
pip install git+https://github.com/RemDelaporteMathurin/FESTIM@v0.2.1
```