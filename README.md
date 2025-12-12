# OpenHosta Documentation

Documentation officielle pour OpenHosta - Extension Python pour l'émulation de fonctions avec IA.

## 🚀 Installation

### Prérequis

- Node.js (v18 ou supérieur)
- npm ou yarn

### Installation de Mintlify CLI

```bash
npm install -g mintlify
```

## 📖 Lancer la documentation en local

```bash
# Se placer dans le dossier docs
cd docs

# Lancer le serveur de développement
mintlify dev
```

La documentation sera accessible sur **http://localhost:3000**

## 📁 Structure

```
docs/
├── index.mdx                    # Page d'accueil
├── docs.json                    # Configuration Mintlify
├── OpenHostaDocs/               # Documentation OpenHosta
│   ├── quickstart.mdx
│   ├── installation.mdx
│   ├── core-concepts/           # Fonctions principales
│   ├── advanced/                # Fonctionnalités avancées
│   ├── theory/                  # Théorie PMAC
│   └── examples/                # Exemples pratiques
└── Old_docs/                    # Archive ancienne doc Mintlify
```

## 🎨 Thème

- **Couleurs** : Violet (`#8B5CF6`) et noir
- **Composants** : Mintlify MDX (Cards, Tabs, Notes, etc.)

## 📝 Modifier la documentation

1. Éditez les fichiers `.mdx` dans `OpenHostaDocs/`
2. Les changements sont automatiquement reflétés sur localhost
3. Commit et push vers GitHub

## 🔗 Liens utiles

- [Documentation Mintlify](https://mintlify.com/docs)
- [OpenHosta GitHub](https://github.com/hand-e-fr/OpenHosta)
- [Syntaxe MDX](https://mdxjs.com/)

## 🛠️ Commandes utiles

```bash
# Lancer en mode développement
mintlify dev

# Builder pour production (optionnel)
mintlify build

# Vérifier les erreurs
mintlify doctor
```

## ⚠️ Note

Le dossier `Old_docs/` contient l'ancienne documentation Mintlify starter kit et peut être ignoré.
