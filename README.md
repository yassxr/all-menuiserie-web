# All Menuiserie — Site Web

Site vitrine pour **All Menuiserie**, une entreprise spécialisée dans la charpente en bois et la menuiserie, implantée à Drargua, Agadir, Maroc. Développé en HTML, CSS, JavaScript, Bootstrap 4 et PHP.

## Pages

| Page | Description |
|---|---|
| `index.html` | Page principale — Accueil, À Propos, Services, Équipe, Contact, FAQ |
| `galerie.html` | Galerie photos des réalisations |

## Sections

- **Accueil** — Bannière hero avec vagues animées
- **À Propos** — Présentation de l'entreprise
- **Services** — Charpente, portes & fenêtres, menuiserie intérieure
- **Réalisations** — Portfolio (villas, locaux commerciaux, rénovation)
- **Équipe** — Fiches équipe avec liens réseaux sociaux
- **Contact** — Carte Google Maps + formulaire de contact (PHPMailer)
- **FAQ** — Accordéon avec les questions fréquentes
- **Pied de page** — Liens, coordonnées, réseaux sociaux, newsletter

## Technologies utilisées

- HTML5 / CSS3
- Bootstrap 4
- jQuery + Owl Carousel (carrousel de témoignages)
- Font Awesome 5 (icônes)
- Ionicons 2 (icônes footer/nav)
- PHP + [PHPMailer](https://github.com/PHPMailer/PHPMailer) (formulaire de contact)

## Lancer le projet en local

**Aperçu statique (sans formulaire de contact) :**

```bash
python3 -m http.server 8080
```

Puis ouvrir [http://localhost:8080](http://localhost:8080).

**Serveur PHP complet (formulaire de contact activé) :**

```bash
php -S localhost:8080
```

## Configuration du formulaire de contact

Le formulaire (`contactme.php`) utilise PHPMailer. Avant de déployer :

1. Installer les dépendances :
   ```bash
   composer install
   ```
2. Renseigner les identifiants SMTP dans `mailing/mailingvariables.php`
3. Définir l'adresse e-mail destinataire dans `contactme.php`

## Licence

MIT
