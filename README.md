**Note: A French version of this README is available right after this section.**

# Connector Odoo - Societe.com

There is currently no Odoo - Societe.com connector. Yet, such autocompletion would make life much easier for many people. I don't currently have the time to develop this connector, but I'm creating this repo to remind me soon, and in the hope that someone will pass by and want to start developments with me!

Naturally, the connector would be developed in python as a module to be downloaded from Odoo, probably open-source. 

However, I don't yet know what direction my career will take after I finish my studies in September 2025, but I don't rule out making the creation and marketing of this kind of microservice my profession, as a self-employed entrepreneur.

In any case, I'm open to all the opportunities that come my way, so don't hesitate to contact me. I only work with committed and passionate people!

---

### Best Practices on Branching

- `main`: Main branch of the project. It is protected and can only be modified through pull requests. It is automatically deployed to Heroku.
- `develop`: Development branch. It is protected and can only be modified through pull requests. It can be considered as a pre-production branch, and deployed to Heroku if needed.
- `feature/<ticket_number>`: Feature branch. Created from `develop` and merged back into `develop` through a pull request.
- `hotfix/<ticket_number>`: Hotfix branch. Created from `main` and merged back into `main` through a pull request.

### Best Practices on Commits

- Commit messages should be written in English, in the present tense.
- Commit messages should be written using the [Conventional Commits](https://www.conventionalcommits.org/) convention, i.e., following the format: `<type>[optional scope]: <description> [optional issue]`.
- Adhering to these conventions allows for automated version management and package publishing.

### Best Practices on Pull Requests

- Pull requests should be written in English, in the present tense.
- A pull request template is available in the `.github/PULL_REQUEST_TEMPLATE/pull_request_template.md` directory.
- Pull requests should be assigned to a reviewer.

---

## NPM Scripts
- `semantic-release`: To automate version management and package publishing. It is configured to run only on the `main` branch. The initial setup on version numbers is as follows: `1.0.0` for the first release, then `1.0.1` for bug fixes, `1.1.0` for new features, and `2.0.0` for major changes. For more information, consult the [semantic-release](https://semantic-release.gitbook.io/semantic-release/) documentation.

---

## License
This project is under the MIT license - see the [LICENSE](LICENSE) file for more details.
    
---

# 

# 

# Connecteur Odoo - Societe.com

Naturellement, le connecteur serait développé en python comme un module à télécharger sur Odoo, probablement open-source. 

Cependant, je ne connais pas encore l'orientation que prendra ma carrière après la fin de mes études en septembre 2025, mais je n'exclue pas de faire de la création de ce genre de micro-service et leur commercialisation, mon métier, en autoentrepreneur.

Quoi qu'il en soit, je suis ouvert à toutes les opportunités qu'on me propose, donc n'hésitez pas à me contacter, je travaille exclusivement avec des personnes engagées et passionnées !


---

### Bonnes pratiques sur les branches

- `main` : Branche principale du projet. Elle est protégée et ne peut être modifiée que par le biais de pull requests. Elle est automatiquement déployée sur Heroku.
- `develop` : Branche de développement. Elle est protégée et ne peut être modifiée que par le biais de pull requests. Elle peut être considérée comme une branche de pré-production, et déployée si besoin sur Heroku.
- `feature/<numéro du ticket associé à la tache>` : Branche de fonctionnalité. Elle est créée à partir de `develop` et fusionnée dans `develop` par le biais d'une pull request.
- `hotfix/<numéro du ticket associé à la tache>` : Branche de correction. Elle est créée à partir de `main` et fusionnée dans `main` par le biais d'une pull request.

### Bonnes pratiques sur les commits

- Les messages de commit doivent être rédigés en anglais, au présent.
- Les messages de commit doivent être rédigés en utilisant la convention [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/), c'est-à-dire en respectant le format suivant : `<type>[optional scope]: <description> [optional issue]`.
- Le respect de ces conventions permet d'automatiser la gestion des versions et la publication du package.

### Bonnes pratiques sur les pull requests

- Les pull requests doivent être rédigées en anglais, au présent.
- Un template de pull request est disponible dans le dossier `.github/PULL_REQUEST_TEMPLATE/pull_request_template.md`.
- Les pull requests doivent être assignées à un reviewer.

---

## Scripts NPM

- `semantic-release`: Pour automatiser la gestion des versions et la publication du package. Il est configuré pour être exécuté sur la branche `main` uniquement. La configuration initiale sur les numéros de version est la suivante : `1.0.0` pour la première version, puis `1.0.1` pour les corrections de bugs, `1.1.0` pour les nouvelles fonctionnalités, et `2.0.0` pour les changements majeurs. Pour plus d'informations, consultez la documentation de [semantic-release](https://semantic-release.gitbook.io/semantic-release/).

---

## Licence

Ce projet est sous licence MIT - voir le fichier [LICENSE](LICENSE) pour plus de détails.
