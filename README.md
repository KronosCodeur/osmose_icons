# Osmose Icons

Osmose Icons est un package Flutter open source fournissant une collection d'icônes personnalisées créées à partir de fichiers SVG et transformées en police d'icônes. Ce package facilite l'utilisation d'icônes uniques dans vos projets Flutter.

## Installation

Ajoutez Osmose Icons à votre fichier `pubspec.yaml` :

```yaml
dependencies:
  osmose_icons: ^1.0.0
```

Exécutez la commande suivante pour installer le package :

```bash
flutter pub get
```

## Utilisation

Importez la classe `OsmoseIcons` et utilisez les icônes personnalisées dans vos widgets Flutter comme suit :

```dart
import 'package:osmose_icons/osmose_icons.dart';
import 'package:flutter/material.dart';

class MyHomePage extends StatelessWidget {
  @override
  Widget build(BuildContext context) {
    return Scaffold(
      appBar: AppBar(title: Text('Osmose Icons Example')),
      body: Center(
        child: Icon(
          OsmoseIcons.bars_sort,
          size: 50,
          color: Colors.blue,
        ),
      ),
    );
  }
}
```

## Liste des icônes disponibles

- **bars_sort** : `OsmoseIcons.bars_sort`
- **book** : `OsmoseIcons.book`
- **books** : `OsmoseIcons.books`
- **home** : `OsmoseIcons.home`
- **profile** : `OsmoseIcons.profile`
- **voice** : `OsmoseIcons.voice`

## Contribution

Les contributions sont les bienvenues ! Si vous souhaitez ajouter de nouvelles icônes ou améliorer le package, vous pouvez ouvrir une pull request sur [GitHub](https://github.com/username/osmose_icons).

### Comment contribuer ?

1. Forkez le dépôt.
2. Créez une nouvelle branche pour vos modifications :
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Effectuez vos modifications et ajoutez-les :
   ```bash
   git add .
   git commit -m "Description de votre modification"
   ```
4. Poussez vos modifications :
   ```bash
   git push origin feature/your-feature-name
   ```
5. Ouvrez une pull request.

## Licence

Ce projet est sous licence MIT. Consultez le fichier [LICENSE](./LICENSE) pour plus d'informations.

---

## Pourquoi open source ?

Nous croyons que partager des outils et des ressources avec la communauté Flutter peut améliorer l'expérience de développement pour tout le monde. Osmose Icons est libre d'utilisation, modifiable et accessible à tous.

