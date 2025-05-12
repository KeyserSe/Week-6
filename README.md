
# Notary by Sean M. Keyser

## 📘 Summary / Purpose of the Site

The “**Notary by Sean M. Keyser**” website is a mobile-friendly professional platform designed to promote mobile and remote notary services in Florida. It allows visitors to:

- Browse available services
- Learn more about the notary
- Search for specific services
- Contact the notary or send messages via a form

Built with **HTML5, CSS3, JavaScript, jQuery Mobile**, and a custom mobile theme.

---

## 📁 Website Structure / Site Map

| Page               | Description |
|--------------------|-------------|
| `index.html`       | Home page with Services and About sections |
| `find_service.html`| Service filtering and searching |
| `contact.html`     | Contact information and form submission |
| Shared Elements    | Header, Side Navigation Panel, Footer |

```
📂 Root
├── index.html
├── find_service.html
├── contact.html
├── themes/
│   ├── my-custom-theme.min.css
│   └── jquery.mobile.icons.min.css
└── assets/
    └── favicon.ico, logo.png, etc.
```

---

## 🧭 Button & Link Descriptions

| Button / Link | Location | Action | Result |
|---------------|----------|--------|--------|
| ☰ Menu        | Header   | Opens side navigation | Quick access to all sections |
| **Services**  | Menu     | Scrolls to or links to services section/page |
| **About**     | Menu     | Scrolls to About section |
| **Find a Service** | Menu/Page | Filters available services |
| **Contact**   | Menu     | Opens the Contact page |
| **Submit**    | Contact Form | Sends input (front-end only) | Confirmation/future backend |

---

## 🌐 Sample / Production Site URL

If deployed via GitHub Pages:

```
https://<your-username>.github.io/<repository-name>/
```

Example:

```
https://seankeyser.github.io/notary-website/
```

---

> 💡 Make sure GitHub Pages is set to publish from the `main` branch (or `docs/` folder if structured that way).
