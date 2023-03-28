# French Bins

`french-bins` est une bibliothèque Python qui fournit des informations sur les Bins (Bank Identification Numbers) des principales banques françaises, telles que BNP Paribas, Société Générale, LCL, AXA, Crédit Mutuel et Crédit Agricole.

## Installation

Vous pouvez installer `french-bins` en utilisant `pip` :

```bash
pip install french-bins
```

## Utilisation

Pour utiliser french-bins dans votre projet, importez simplement la variable FRENCH_BANK_BINS :

```python
from french_bins import FRENCH_BANK_BINS
```
FRENCH_BANK_BINS est un dictionnaire contenant les informations sur les Bins des banques françaises. Voici un exemple d'utilisation :

```python
print(FRENCH_BANK_BINS["BNP_Paribas"]["gold"][0])
```

Cela affichera les informations suivantes :

```arduino
{
    'bin': '497462',
    'type': 'Crédit',
    'bank': 'BNP Paribas',
    'level': 'Gold'
}
```

## Contribuer

Si vous souhaitez contribuer au projet, veuillez soumettre une pull request sur [https://github.com/toomanylog/french-bins](https://github.com/toomanylog/french-bins).

## Licence

french-bins est publié sous la licence MIT. Voir le fichier LICENSE pour plus de détails.
