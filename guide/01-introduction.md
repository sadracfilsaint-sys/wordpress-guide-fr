# Chapitre 1 : Introduction à WordPress

## Objectifs

À la fin de ce chapitre, vous saurez :
- ce qu'est WordPress et à quoi il sert ;
- la différence entre WordPress.org et WordPress.com ;
- les notions de base : thème, plugin, article, page ;
- comment installer WordPress sur votre ordinateur, sans connexion permanente.

## 1. Qu'est-ce que WordPress ?

WordPress est un **système de gestion de contenu (CMS)** libre et gratuit. Il permet de créer et gérer un site web (blog, site d'école, boutique, portfolio) sans tout programmer à la main. Il est publié sous licence **GPL** : vous pouvez l'utiliser, le modifier et le partager.

## 2. WordPress.org ou WordPress.com ?

| | WordPress.org | WordPress.com |
|---|---|---|
| Type | Logiciel à installer vous-même | Service d'hébergement clé en main |
| Coût du logiciel | Gratuit | Offre gratuite limitée, options payantes |
| Liberté (thèmes, plugins, code) | Totale | Selon l'offre choisie |
| Pour apprendre le développement | **Recommandé** | Moins adapté |

## 3. Les notions de base

| Terme | Définition simple |
|---|---|
| **Article** | Contenu daté, affiché dans le blog |
| **Page** | Contenu fixe (Accueil, Contact) |
| **Thème** | Définit l'apparence du site |
| **Plugin** | Ajoute une fonction (formulaire, sécurité, etc.) |
| **Tableau de bord** | Interface d'administration (`/wp-admin`) |
| **Thème enfant** | Thème qui hérite d'un autre, pour le modifier sans casser les mises à jour |

## 4. Comment ça fonctionne

WordPress est écrit en **PHP** et stocke ses données dans une base **MySQL ou MariaDB**. Le navigateur demande une page, PHP lit la base, assemble le contenu avec le thème, puis renvoie du HTML.

## 5. Installer WordPress en local

Travailler en local évite d'avoir besoin d'internet en continu.

1. Téléchargez un outil local : **Local** (localwp.com) ou **XAMPP**.
2. Créez un nouveau site, choisissez un nom et un identifiant.
3. Ouvrez le tableau de bord : `http://nom-du-site.local/wp-admin`.
4. Connectez-vous et explorez : **Apparence**, **Extensions**, **Articles**.

## À retenir

- WordPress est un CMS libre, écrit en PHP, avec une base de données.
- Pour apprendre le développement, utilisez **WordPress.org** en local.
- Un site = un **thème** (apparence) + des **plugins** (fonctions) + du **contenu**.

## Exercice

1. Installez WordPress en local.
2. Créez une page « À propos » et un article.
3. Changez de thème, puis notez ce qui change.

**Chapitre suivant :** [Structure d'un thème WordPress](02-structure-theme.md)
