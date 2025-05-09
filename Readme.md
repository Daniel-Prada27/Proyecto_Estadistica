Si usan vscode recuerden instalar la extensión [Jupyter](https://marketplace.visualstudio.com/items/?itemName=ms-toolsai.jupyter).

Instalar las librerías (como pandas) con el comando

```powershell
PS C:\> pip install <modulo>
```
## Ramas en git

Trabajen en sus propias ramas, para esto:

```powershell
PS C:\Repositorio\> git checkout -b nombre_de_rama
PS C:\Repositorio\> git push -u origin nombre_de_rama
```

Esto crea su propia rama y les permite hacer push al repositorio en github con

```powershell
PS C:\Repositorio\> git push
```