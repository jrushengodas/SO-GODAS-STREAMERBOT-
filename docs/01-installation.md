# ⚡ INSTALLATION - GODAS TWITCH SHOUTOUT

⚠️ IMPORTANT :

Suivre les étapes dans l'ordre.

---

## 1. Importer Streamer.bot

Importer :

```text
streamerbot/GODAS_SO.sb
```

---

## 2. Créer la commande

Créer une commande Twitch :

```text
!so
```

Argument :

```text
input0
Auto Type
Required = Yes
```

---

## 3. Ajouter les arguments

Créer les arguments suivants :

```text
godas_so_client_id
godas_so_access_token
godas_so_broadcaster_id
godas_so_moderator_id
```

---

## 4. Importer le code

Coller :

```text
GodasShoutout.cs
```

dans l'action Streamer.bot.

---

## 5. Ordre recommandé

```text
Set Argument godas_so_client_id
Set Argument godas_so_access_token
Set Argument godas_so_broadcaster_id
Set Argument godas_so_moderator_id
Execute Code
```

---

## 6. Tester

```text
!so jungpoo97
```

---

## ✅ Installation terminée