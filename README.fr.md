# Laboratoire d'installation d'un agent de codage IA : installer opencode et le relier à un modèle, sur un petit projet avec tests

[English](README.md) | [Français](README.fr.md) | [Español](README.es.md) | [日本語](README.ja.md) | [Deutsch](README.de.md)

[![check](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml/badge.svg)](https://github.com/mitsurutech/lab-ai-agent-install/actions/workflows/check.yml)

Un laboratoire prêt à l'emploi pour la classe, proposé par la [MitsuruTech Learning Platform](https://mitsurutech.co.uk/learning), où écoles, lycées, établissements supérieurs et universités donnent à chaque étudiant ses propres bases de données, conteneurs et terminal dans le navigateur. C'est un labo où rien n'est installé : vous installez opencode, un agent IA open source, vous lui indiquez où se trouve son modèle, puis vous l'utilisez sur un petit projet avec tests.

## Utilisation sur la plateforme

**Ce labo ne fonctionne que sur la plateforme.** Son agent joint un modèle et un proxy de paquets que la plateforme fournit à côté de la copie de chaque étudiant ; `compose.yaml` ne démarre donc pas seul sur votre machine. Chaque étudiant dispose d'une copie privée sans aucun accès à internet.

**Pour l'essayer :** ouvrez la [page des conteneurs](https://mitsurutech.co.uk/container), trouvez ce labo dans **Sample labs** et appuyez sur Start. Un compte gratuit est nécessaire.

**Pour le donner comme travail à une classe :**

1. Dans votre module, créez une tâche de type **Lab** et choisissez **In a GitHub repository**.
2. Indiquez `https://github.com/mitsurutech/lab-ai-agent-install` avec la branche `main`. Le fichier compose par défaut est `compose.yaml`. Faites d'abord un fork du dépôt si vous voulez le modifier.
3. Publiez. La copie de chaque étudiant part du commit que vous avez publié : une modification ultérieure ici ne change donc pas un labo déjà donné.

La [page de ce labo](https://mitsurutech.co.uk/help/lab-ai-agent-install) du manuel d'aide et son [guide des labos de conteneurs](https://mitsurutech.co.uk/help/labs) disent le reste. La leçon de base associée s'intitule **AI Coding Agent Basics**. Pas encore de compte d'établissement ? [La première année est gratuite](https://mitsurutech.co.uk/pricing) jusqu'à 50 étudiants, et [l'inscription](https://mitsurutech.co.uk/signup) ne demande qu'une adresse e-mail.

## À savoir

Le commentaire en tête de `compose.yaml` explique comment démarrer et ce que l'agent a le droit de faire. L'agent demande l'autorisation avant de modifier un fichier ou d'exécuter une commande : lisez ce qu'il veut faire et ne dites oui que si vous le comprenez. **Rien n'est enregistré** : arrêter le labo fait oublier tous les fichiers, l'étudiant télécharge donc son travail avant de l'arrêter. Les réponses d'un assistant diffèrent d'une exécution à l'autre : aucun résultat n'est donc promis ici.

## Licence

Cette œuvre est placée sous licence [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/). Vous pouvez la partager et l'adapter pour l'apprentissage et l'enseignement, à condition de citer Mitsuru Technologies Ltd, de ne pas l'utiliser à des fins commerciales et de partager ce que vous en tirez sous la même licence. Le texte complet se trouve dans le fichier `LICENSE`.

## À propos

Réalisé par [Mitsuru Technologies](https://mitsurutech.co.uk) pour la [MitsuruTech Learning Platform](https://mitsurutech.co.uk/learning) : Python, Java, Go, Node, SQL et Linux dans le navigateur pour les écoles et les établissements, avec des labos de conteneurs, des applications web déployées depuis GitHub et des quiz qui se corrigent eux-mêmes. Essayez du code sans compte dans le [playground](https://mitsurutech.co.uk/playground).

D'autres labos du même éditeur : [lab-ai-agent](https://github.com/mitsurutech/lab-ai-agent), [lab-quantum-sim](https://github.com/mitsurutech/lab-quantum-sim), [lab-jupyter-data](https://github.com/mitsurutech/lab-jupyter-data) et [lab-git-gitea](https://github.com/mitsurutech/lab-git-gitea).
