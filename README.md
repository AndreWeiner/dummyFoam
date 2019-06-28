# dummyFoam

dummyFoam is a very basic OpenFOAM&reg; solver created with [OpenFOAM-v1906](https://openfoam.com/releases/openfoam-v1906/) by running

```
foamNewApp dummyFoam
```

Its sole purpose is to demonstrate how to containerize a single OpenFOAM solver using the OpenFOAM-v1906 Docker image, Github, and Docker multistage-builds. Such a workflow has some advantages:

- the executable **and** its dependencies are isolated in a Docker image (Docker remains as the only dependency)
- the solver is nearly platform independent and will always produce the same results
- the solver can be easily and quickly distributed
- the solver can run on cloud platforms
- the image size is minimal (and hence the traffic for distributing the solver)

More information can be found in the accompanying article (to be linked here).
