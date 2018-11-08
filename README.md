# Installation de Jupyter sur Windows 10 (avec Miniconda)

## Installation de Miniconda

#### Ouvrez un navigateur web à l'adresse

 <https://conda.io/miniconda.html>

Téléchargez le programme d'installation de Miniconda pour Python 3.7 et Windows 64-bit

![](img/miniconda01.png)

#### Lancez le programme d'installation

Fichier `Miniconda3-latest-Windows-x86_64`

![](img/miniconda02.png)

#### Validez la licence d'utilisation

![](img/miniconda03.png)

#### N'installez Miniconda que pour vous

![](img/miniconda04.png)

#### Laissez le répertoire d'installation par défaut (tel que proposé par l'installateur)

![](img/miniconda05.png)

#### Laissez les autres paramètres par défaut

![](img/miniconda06.png)

#### L'installation de Miniconda va prendre quelques minutes

![](img/miniconda07.png)

Comptez 5 minutes

#### Validez la fin de l'installation

en décochant les deux cases

![](img/miniconda08.png)


## Installation de Jupyter

#### Lancez l'invite de commande Miniconda

depuis le menu Windows

![](img/miniconda09.png)

pour obtenir

![](img/miniconda10.png)

### Installez Jupyter

avec la commande :

```
conda install -y -c conda-forge jupyterlab
```

puis R pour que Jupyter puisse manipuler des notebooks R :

```
conda install -y -c r r-essentials
```


## Utilisation de Jupyter

#### Lancez l'invite de commande Miniconda

depuis le menu Windows

![](img/miniconda09.png)

pour obtenir

![](img/miniconda10.png)

#### Lancez les notebooks Jupyter

Tapez la commande :

```
jupyter notebook
```

Un nouvel onglet va s'ouvrir dans votre navigateur web.

![](img/jupyter01.png)

#### Lancez Jupyter lab

Tapez la commande :

```
jupyter lab
```

Un nouvel onglet va s'ouvrir dans votre navigateur web.

![](img/jupyter02.png)


## Arrêter / quitter Jupyter (notebook ou lab)

Revenez dans l'invite de commande Miniconda et appuyez deux fois sur la combinaison de touches `Ctrl + C`

![](img/jupyter03.png)
