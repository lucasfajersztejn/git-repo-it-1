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

Fast-Fodward (No hay ningun cambio que se solape con lo que esta en la otra rama)

Fast-Fodward - Unión automáticas (No hay ningun cambio que se solape con lo que esta en la otra rama)

Recursiva -  Uniones automáticas (No hay colisiones de cambios)

Manual - Conflictos (ocure cuando hay modificaciones en las mismas líneas)

### Abortar Merge

```sh
git merge --abort
```

### TAREAS: Agrego cosas que quiero tener en consideración.

* Tener en cuenta subir una rama al remoto
* Ver Clone
* Ver Fork

### Agrego algo para luego hacer un merge con conflicto

