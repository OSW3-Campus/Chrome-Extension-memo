# Le manifest

## Description

Le manifest est le fichier qui décrit et configure l'extension.

[https://developer.chrome.com/extensions/manifest](https://developer.chrome.com/extensions/manifest)


## Emplacement

Le manifest doit impérativement se trouver à la racine de l'extension.

```
/manifest.json
```


## Paramètres

### `default_locale`

- Type : `string`
- Obligatoire : recommandé - requis si l'extension possède le répertoire `_locales`
- Description : Langue par défaut de l'extension
- [Documentation](https://developer.chrome.com/extensions/manifest/default_locale)

```json
{
    "default_locale": "fr",
}
```


###`description`

- Type : `string`
- Obligatoire : recommandé
- Longueur Max : 132 caractères
- Description : description de l'extension
- [Documentation](https://developer.chrome.com/extensions/manifest/description)

```json
{
    "description": "Création d'une extension Chrome avec OSW3-Campus !",
}
```


### `name`

- Type : `string`
- Obligatoire : oui
- Longueur Max : 45 caractères
- Description : Nom de l'extension
- [Documentation](https://developer.chrome.com/extensions/manifest/name)

```json
{
    "name": "Exemple d'extension Chrome.",
}
```


###  `manifest_version`

- Type : `integer`
- Obligatoire : oui
- Valeur : 2
- Description : Version du format du manifest
- [Documentation](https://developer.chrome.com/extensions/manifest/manifest_version)

```json
{
    "manifest_version": 2,
}
```


### `version`

- Type : `string`
- Obligatoire : oui
- Description : Numéro de version de l'extension
- [Documentation](https://developer.chrome.com/extensions/manifest/version)

```json
{
    "version": "1.0",
}
```