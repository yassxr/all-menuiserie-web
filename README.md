# All Menuiserie — Site Web

Website for **All Menuiserie**, a carpentry and timber-frame company based in Drargua, Agadir, Morocco. Built with HTML, CSS, JavaScript, Bootstrap 4, and PHP.

## Pages

| Page | Description |
|---|---|
| `index.html` | Main page — Home, About, Services, Team, Contact, FAQ |
| `galerie.html` | Photo gallery of completed projects |

## Sections

- **Accueil** — Hero banner with animated waves
- **À Propos** — Company overview
- **Services** — Timber framing, doors & windows, interior joinery
- **Réalisations** — Portfolio highlights (villas, commercial, renovation)
- **Équipe** — Team cards with social links
- **Contact** — Google Maps embed + contact form (PHPMailer)
- **FAQ** — Accordion with common questions
- **Footer** — Links, coordinates, social links, newsletter form

## Tech Stack

- HTML5 / CSS3
- Bootstrap 4
- jQuery + Owl Carousel (testimonials slider)
- Font Awesome 5 (icons)
- Ionicons 2 (footer/nav icons)
- PHP + [PHPMailer](https://github.com/PHPMailer/PHPMailer) (contact form)

## Running Locally

**Static preview (no contact form):**

```bash
python3 -m http.server 8080
```

Then open [http://localhost:8080](http://localhost:8080).

**Full PHP server (contact form enabled):**

```bash
php -S localhost:8080
```

## Contact Form Setup

The contact form (`contactme.php`) uses PHPMailer. Before deploying:

1. Install dependencies:
   ```bash
   composer install
   ```
2. Set SMTP credentials in `mailing/mailingvariables.php`
3. Set the recipient email in `contactme.php`

## License

MIT
