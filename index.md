---
---
layout: default
title: "Accueil"
---

# 🗝️ Projet Moul Dar (مشروع مول الدار)

Bienvenue sur le laboratoire de la nouvelle conscience algérienne. Fini le statut de locataire, reprenons les clés de notre maison.

---

## 📝 Nos derniers articles :

<ul>
  {% for post in site.posts %}
    <li>
      <strong><a href="{{ post.url | relative_url }}">{{ post.title }}</a></strong>
      <br>
      <small>Publié le : {{ post.date | date: "%d/%m/%Y" }}</small>
    </li>
  {% endfor %}
</ul>

---
[En savoir plus sur nous...](/about.html)
