# Generators

## Random Graphs

*LightGraphs.jl* implements some common random graph generators:

```@autodocs
Modules = [LightGraphs]
Pages   = [
    "generators/randgraphs.jl"
]
Private = false
```


## Static Graphs

*LightGraphs.jl* also implements a collection of classic graph generators:

```@autodocs
Modules = [LightGraphs]
Pages   = [ "generators/staticgraphs.jl"]
Private = false
```

## Small Graphs

Other classical graphs can be generated by the following function:

```@autodocs
Modules = [LightGraphs]
Pages   = [ "generators/smallgraphs.jl"]
Private = false
```

## Euclidean Graphs
Generation of random and static graphs embedded in Euclidean space.

```@autodocs
Modules = [LightGraphs]
Pages   = [ "generators/euclideangraphs.jl"]
Private = false
```

## Datasets

Other notorious graphs and integration with the `MatrixDepot.jl` package are available in the `Datasets` submodule of the companion package
*LightGraphsExtras.jl*
```
