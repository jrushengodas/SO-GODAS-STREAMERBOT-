# 🔑 TWITCH IDS & TOKEN

Le système utilise :

```text
Client ID
Access Token
Broadcaster ID
Moderator ID
```

---

# 1. Générer un token Twitch

Aller sur :

```text
https://twitchtokengenerator.com/
```

---

## Scopes requis

```text
chat:read
chat:edit
moderator:manage:shoutouts
moderator:read:shoutouts
```

---

## Copier

```text
Client ID
Access Token
```

Puis configurer :

```text
godas_so_client_id
godas_so_access_token
```

---

# 2. Récupérer un Twitch ID

Aller sur :

```text
https://api.ivr.fi/v2/twitch/user?login=PSEUDO
```

Exemple :

```text
https://api.ivr.fi/v2/twitch/user?login=je_rush_en_godas
```

Réponse :

```json
{
  "id":"247012777"
}
```

L'ID Twitch est :

```text
247012777
```

---

# Streamer uniquement

Si vous utilisez uniquement votre compte streamer :

```text
Broadcaster ID = Streamer ID
Moderator ID = Streamer ID
```

Exemple :

```text
247012777
247012777
```

---

# Streamer + Bot

Si vous utilisez un bot :

```text
Broadcaster ID = Streamer ID
Moderator ID = Bot ID
```

⚠️ Le bot doit être modérateur.

---

# Important

Le compte ayant généré le token doit correspondre au :

```text
Moderator ID
```

Sinon Twitch retournera :

```text
403 Forbidden
```

---

## ✅ Configuration terminée