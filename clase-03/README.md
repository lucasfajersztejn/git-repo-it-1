# Clase 03 - GIT

## Repaso de Branch

### Listo ramas

```sh
git branch
```

### Creo una rama

```sh
git branch <nombreRama>
```

### Cambio entre ramas

```sh
git switch <nombreRama>
```

## Git Merge

### Tipos de Merge

Fast-Fodward - Unión automáticas (No hay ningun cambio que se solape con lo que esta en la otra rama)

Recursiva -  Uniones automáticas (No hay coliciones de cambios)

Manul - Conflictos (ocure cuando hay modificaciones en las mismas líneas)