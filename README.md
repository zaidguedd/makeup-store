# GHAZAL ROSE • makeup-store (Static Pro)

This is a **static** (no npm) store with:
- Shop (products, packs, categories, cart, reviews)
- WhatsApp checkout + order history
- Admin dashboard (login + CRUD: categories/products/packs + branding uploads)
- Settings page (theme, whatsapp, content, social links, backup/restore)
- LocalStorage persistence + default data loaded from /data/*.json on first run

## Run (recommended)
Use VS Code Live Server or any local server (because ES Modules):

### VS Code Live Server
Right click `index.html` → **Open with Live Server**

### Python
```bash
cd GHAZAL_ROSE_makeup-store
python -m http.server 5500
```
Open:
- Shop: http://localhost:5500/index.html
- Login: http://localhost:5500/login.html
- Admin: http://localhost:5500/admin.html
- Settings: http://localhost:5500/settings.html

## Admin Login
- Default password: **admin123**
- You can change it in `localStorage` later (V2 can add UI to change password).
