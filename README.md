# PhoneTech Accessories

## 1. Présentation

**PhoneTech Accessories** est un site vitrine d'accessoires téléphoniques réalisé avec **WordPress** dans le cadre du module **Développement Full Stack et Microservices**.

Le site présente des accessoires tels que les coques, chargeurs, écouteurs, power banks et supports de téléphone.

## 2. Technologies utilisées

* **WordPress** : CMS
* **WooCommerce** : gestion du catalogue et des produits
* **Contact Form 7** : formulaire de contact
* **SaleCraft Ecommerce V2** : thème
* **MySQL / phpMyAdmin** : base de données
* **XAMPP** : environnement local

## 3. Structure du site

Le site contient les pages suivantes :

* **Accueil** : présentation de l'entreprise et produits phares
* **Catalogue** : catalogue de plus de 10 accessoires
* **À propos** : présentation et mission de l'entreprise
* **Blog** : au moins 3 articles sur les accessoires et les nouvelles technologies
* **Contact** : formulaire et coordonnées

## 4. Étapes de réalisation

1. Installation de XAMPP et WordPress.
2. Configuration du site et du thème.
3. Création des pages principales.
4. Installation et configuration de WooCommerce.
5. Ajout et organisation des produits.
6. Création des articles du Blog.
7. Création du formulaire avec Contact Form 7.
8. Personnalisation et test du site.

## 5. Architecture de WordPress

WordPress est un **CMS monolithique**. Les principales fonctionnalités sont regroupées dans une même application.

```text
Utilisateur
    ↓
Navigateur
    ↓
Apache / WordPress
    ↓
Thème + Plugins
    ↓
Base de données MySQL
```

Le **Core WordPress** fournit les fonctionnalités principales, le **thème** gère l'apparence et les **plugins** ajoutent des fonctionnalités comme WooCommerce.

## 6. Monolithique vs Microservices

| Critère         | Monolithique        | Microservices       |
| --------------- | ------------------- | ------------------- |
| Structure       | Une application     | Plusieurs services  |
| Déploiement     | Global              | Service par service |
| Complexité      | Plus simple         | Plus complexe       |
| Base de données | Souvent centralisée | Peut être séparée   |
| Scalabilité     | Globale             | Par service         |

### Architecture monolithique

Elle regroupe les fonctionnalités dans une seule application. Elle est plus simple à développer et à déployer pour les petits projets, mais les composants sont davantage liés entre eux.

### Architecture microservices

Elle divise l'application en plusieurs services indépendants communiquant généralement via des API. Elle offre davantage de flexibilité et de scalabilité, mais demande une gestion plus complexe.

## 7. Conclusion

La réalisation de **PhoneTech Accessories** a permis de découvrir le fonctionnement d'un **CMS monolithique** avec WordPress, ainsi que la gestion des pages, produits, articles, plugins et base de données.

Le projet a également permis de comprendre les principales différences entre une architecture **monolithique** et une architecture **microservices**.
