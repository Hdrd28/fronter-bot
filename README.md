# fronter-bot
Fronter est un bot Discord conçu pour les systèmes pluriels.   Il permet à chaque utilisateur de créer son propre panneau de switch personnalisé, d'inscrire ses alters avec les informations qu'il choisit lui-même, et de signaler facilement qui est actuellement au front.  

Support : https://discord.gg/uawMaxCAq

# 📋 Changelog — Fronter

---

## 🔧 Version 1.2 — Vérifications des permissions
*27 juillet 2026*

### :sparkles: Nouveautés
- Vérifications des permissions — à chaque fois que vous ferez /panel, le bot checkera si il a toute les permissions; si il en manque une il vous répondra à la commande ou bien par MP.

![Exemples](https://media.discordapp.net/attachments/1527694678236069978/1531189453144723496/image.png?ex=6a684ecd&is=6a66fd4d&hm=7e5247c1d30ce8b67536cfe8af6c535b09ac91459da6f19f39580b9ebc205ce4&=&format=webp&quality=lossless)

## 🔧 Version 1.1 — Synchronisation multi-panels
*22 juillet 2026*

### ✨ Nouveautés
- **Synchronisation multi-panels** — lors d'un switch ou d'un switch out, tous les panneaux existants sur tous les serveurs sont maintenant mis à jour simultanément
- **Nettoyage automatique** — les panneaux supprimés ou introuvables sont automatiquement retirés de la liste

---

## 🚀 Version 1.0 — Lancement initial
*17 juillet 2026*

### ✨ Nouveautés
- **Panneau de switch personnalisé** — chaque utilisateur crée son propre panneau via `/panel`
- **Configuration guidée** — au premier `/panel`, un assistant guide la création des champs personnalisés
- **Champs personnalisables** — trois types disponibles : texte libre, boutons à choix fixes, et couleur d'embed
- **Switch** — signalez quel alter est au front en quelques clics
- **Switch Out** — indiquez qu'aucun alter n'est au front
- **Inscription Alter** — enregistrez un alter à l'avance sans déclencher de switch
- **Édition** — modifiez les informations d'un alter à tout moment, y compris son nom et son image
- **Suppression** — supprimez un alter avec confirmation obligatoire
- **Persistance du front** — l'alter au front est conservé même si le panneau est recréé

### 💬 Commandes disponibles
- `/panel` — Créer ou mettre à jour son panneau
- `/alters` — Lister ses alters enregistrés
- `/champs` — Gérer ses champs personnalisés
- `/aide` — Afficher le guide d'utilisation
- `/reset` — Réinitialiser toutes ses données

### 🔒 Confidentialité
- Données isolées par utilisateur
- Suppression complète via `/reset`
- Aucune donnée partagée entre utilisateurs
