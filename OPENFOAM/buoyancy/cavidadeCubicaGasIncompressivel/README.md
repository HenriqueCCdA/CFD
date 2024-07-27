# Cavidade cúbica

Nesse exemplo foi utilizado a aproximação de `gas imcompressivel`. O gradiente de temperatuda horizontal é de `20 kelvin`. O dimensão da aresta do cubo é de 0.1 metros.

# Comandos

Gerar a Malha:

```bash
blockMesh
```

Rodar:

```bash
buoyantFoam
```

Escreve os arquivos no formato `VTK`:

```bash
foamToVTK -fields '(T U)'
```
