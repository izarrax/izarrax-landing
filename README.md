# IzarraX — Landing Page

Official landing page for **IzarraX**, a suite of **Premium Android Solutions**  
focused on **Performance**, **Security** and **Design**.

🌐 Production: https://izarrax.fr

---

## ✨ About IzarraX

IzarraX is an independent software project building high-quality Android
applications and services, designed to integrate seamlessly in professional
and enterprise environments.

This repository contains the **public landing page** only.

---

## 🧱 Tech stack

- Static HTML / CSS
- Served via **Nginx**
- Reverse-proxied by **Traefik**
- HTTPS powered by **Let’s Encrypt**
- Docker-based deployment

---

## 🚀 Deployment

The landing page is deployed on a dedicated VPS and served through Docker.

Basic workflow:

```bash
git pull
docker restart izarrax-web