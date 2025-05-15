# 🛠️ SanoFood – Version Symfony de l’Application de healthy food

## 📄 Description du Projet

Cette version Symfony de **SanoFood** a été développée dans le cadre de l’année universitaire **2024–2025** à **Esprit School of Engineering**.  
Elle offre une plateforme web de gestion des commandes, utilisateurs, livreurs, nutritionnistes et administrateurs, construite avec le framework **Symfony 6**.

---

## 🧭 Table des matières

- [Installation](#installation)
- [Utilisation](#utilisation)
- [Fonctionnalités](#fonctionnalités)
- [Technologies Utilisées](#technologies-utilisées)
- [Contribution](#contribution)
- [Licence](#licence)

---

## ⚙️ Installation

1. **Cloner le repository :**

```bash
git clone https://github.com/EvaBel/SanoFood.git
cd SanoFood
```

2. **Installer les dépendances Symfony :**

```bash
composer install
```

3. **Configurer les variables d’environnement :**

```bash
cp .env .env.local
# Modifier .env.local pour inclure votre DATABASE_URL
```

4. **Initialiser la base de données :**

```bash
php bin/console doctrine:database:create
php bin/console doctrine:migrations:migrate
```

5. **Démarrer le serveur Symfony :**

```bash
symfony server:start
```

---

## 🚀 Utilisation

Une fois le serveur lancé, accédez à l’application via :  
[http://localhost:8000](http://localhost:8000)

Fonctionnalités disponibles :
- Gestion des utilisateurs (clients, livreurs, nutritionnistes, admins)
- Commandes et livraisons
- Statistiques dynamiques
- Interface responsive

---

## ✅ Fonctionnalités

- 🔐 Authentification et rôles utilisateurs
- 🛒 Gestion des commandes
- 🚚 Suivi des livraisons
- 📊 Tableau de bord avec statistiques
- 📧 Notifications email
- 🖥️ Interface d’administration avec EasyAdmin (optionnel)

---

## 🧰 Technologies Utilisées

- Symfony 6
- PHP 8.2
- Composer
- Doctrine ORM
- Twig
- Bootstrap
- MySQL
- GitHub Education

---

## 🏷️ Topics (mots-clés GitHub)

`symfony`, `php`, `delivery-app`, `food-delivery`, `school-project`, `github-education`, `esprit-school-of-engineering`

---

## 🤝 Contribution

1. Forkez ce dépôt
2. Créez une branche (`feature/ma-fonction`)
3. Commitez vos changements (`git commit -m 'Nouvelle fonctionnalité'`)
4. Poussez vers GitHub (`git push origin feature/ma-fonction`)
5. Créez une Pull Request

---

## 📜 Licence

Ce projet est sous licence MIT – voir le fichier [LICENSE](LICENSE) pour plus d’informations.

---

## 🙏 Remerciements

Projet développé à **Esprit School of Engineering** dans le cadre du module *Technologies Web* 2024–2025.
