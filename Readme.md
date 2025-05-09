# Trabajando en vscode
Si usan vscode recuerden instalar la extensión [Jupyter](https://marketplace.visualstudio.com/items/?itemName=ms-toolsai.jupyter).

Instalar las librerías (como pandas) con el comando

```powershell
PS C:\> pip install nombre_modulo
```
## Ramas en git

Trabajen en sus propias ramas, para esto:

```powershell
PS C:\Repositorio\> git checkout -b nombre_de_rama
PS C:\Repositorio\> git push -u origin nombre_de_rama
```

Esto crea su propia rama (después de haber clonado el repositorio) y les permite hacer push al repositorio en github con

```powershell
PS C:\Repositorio\> git push
```

### Commits útiles

Al hacer commit, asignen nombres útiles, con los que sea fácil reconocer el propósito del commit o la naturaleza del cambio

```powershell
PS C:\Repositorio\> git commit -m 'Update tuition histogram'
PS C:\Repositorio\> git commit -m 'Remove correlation matrix'
PS C:\Repositorio\> git commit -m 'Add scatterplots'
```

No hagan commit por cualquier cambio mínimo (como modificar colores o agregar comentarios), haganlo cuando haya un cambio significativo, pero tampoco esperen a hacer demasiados cambios antes de hacer un commit. Recuerden que el historial de commits es para nuestro beneficio.