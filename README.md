# 🏡 Le Relais de Chaumeré - Site Vitrine

Bienvenue sur le dépôt du site internet officiel du gîte **Le Relais de Chaumeré**.  
Le site est hébergé via GitHub Pages et configuré avec un nom de domaine personnalisé sécurisé par Cloudflare.

---

## 🚧 État du Projet (Juin 2026)
* **Statut :** En cours de construction / Sortie de terre prévue pour **2027**.
* **Objectif actuel du site :** Commencer le référencement (SEO), présenter la région, les activités locales et partager l'avancement des travaux via la section Blog. Les réservations ne sont pas encore ouvertes.

---

## 🛠️ Stack Technique & Outils

* **Frontend :** HTML5 / CSS3 / JavaScript (Site ultra-léger et rapide).
* **Hébergement :** [GitHub Pages](https://pages.github.com/) (Déploiement automatique depuis la branche principale).
* **Gestion DNS & Sécurité (SSL) :** [Cloudflare](https://www.cloudflare.com/) (Nom de domaine : `le-relais-de-chaumere.fr`).
* **Formulaire de contact :** [Web3Forms](https://web3forms.com/) (Gestion des mails sans backend avec hCaptcha intégré automatiquement).

---

## ⚙️ Rappel de la Configuration DNS (Pense-bête)

Si le domaine doit être reconfiguré un jour, voici les paramètres essentiels actuellement en place :

### 1. CNAME sur Cloudflare (ou o2switch) :
* `www` redirige vers `freelancebzh.github.io` (en mode *Proxied* 🟧 sur Cloudflare).

### 2. Redirection HTTPS :
* Le chiffrement SSL/TLS sur Cloudflare est réglé sur le mode **Flexible**.
* L'option **Always Use HTTPS** est activée dans l'onglet *Edge Certificates* de Cloudflare pour forcer le cadenas de sécurité et permettre le bon fonctionnement du Captcha anti-spam.

---

## 📝 Modifications futures

Pour mettre à jour le site :
1. Modifier les fichiers locaux (HTML, images, articles de blog).
2. Effectuer un `git commit` et `git push` sur la branche principale.
3. GitHub Pages mettra à jour le site en ligne automatiquement en moins d'une minute.
