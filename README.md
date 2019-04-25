# Local Storage

## Commandes

### Ecrire une valeur

```javascript
localStorage.setItem('key','This is a test');
```

### Lire une valeur

```javascript
var item = localStorage.getItem('key');
var key = localStorage.key(n);
```

### Supprimer une valeur

```javascript
localStorage.removeItem('key');
```

### Vider l'espace de stockage

```javascript
localStorage.clear();
```

### Nombre de clef de l'espace de stockage

```javascript
localStorage.length();
```


## Permissions

Ajouter la permission `unlimitedStorage` au `manifest.json` pour obtenir plus d'espace de stockage

```json
{
    "permissions": ["unlimitedStorage"],
}
```