![logo](https://i.imgur.com/OrD1HpT.png)

# 🤖 SumBot (Discord Music Bot)
>SumBot est un joli bot de musique pour la discorde pour jouer des chansons youtube! [discordjs.guide](https://discordjs.guide)

## Requirements

1. Discord Bot Token **[Guide](https://discordjs.guide/preparations/setting-up-a-bot-application.html#creating-your-bot)**
2. YouTube Data API v3 Key **[Guide](https://developers.google.com/youtube/v3/getting-started)**  
2.1 **(Optional)** Soundcloud Client ID **[Guide](https://github.com/zackradisic/node-soundcloud-downloader#client-id)**
3. Node.js v14.0.0 or newer

## 🚀 c'est partie
```
git clone https://github.com/Qwiicks/SumBot.git
cd SumBot
npm install
```

une fois l'installation finit faite : `node index.js` pour lancé le bot.

## ⚙️ Configuration

copié `config.json.example` renomme `config.json` :

⚠️ **Note: Ne jamais valider ni partager votre jeton ou vos clés API publiquementy** ⚠️

```json
{
  "TOKEN": "",
  "YOUTUBE_API_KEY": "",
  "SOUNDCLOUD_CLIENT_ID": "",
  "MAX_PLAYLIST_SIZE": 10,
  "PREFIX": "sum.",
  "PRUNING": false,
  "LOCALE": "fr",
  "DEFAULT_VOLUME": 100,
  "STAY_TIME": 30
}
```

Currently available locales are:
- Anglais (en)
- Allemand (de)
- Francais (fr)
- Espagnol (es)
- Turque (tr)
- coréen (ko)
-Brasilien Portugais (pt_br)
- Chinois simplifié (zh_cn)
- Chinois traditionel (zh_tw)
- Check [Contributing](#-contributing) if you wish to help add more languages!

## 📝Fonctionnalités et commandes

> Note: Prefix par defaut 'sum.'

* 🎶 Écouter de la musique depuis YouTube via l'URL

`sum.play https://www.youtube.com/watch?v=GLvohMXgcBo`

* 🔎Écouter de la musique depuis YouTube via une requête de recherche

`sum.play under the bridge red hot chili peppers`

* 🎶 Écouter de la musique depuis Soundcloud via l'URL

`sum.play https://soundcloud.com/blackhorsebrigade/pearl-jam-alive`

* 🔎Recherchez et sélectionnez la musique à lire

`sum.search Pearl Jam`

Répondez avec le numéro de chanson ou les numéros séparés par une virgule que vous souhaitez écouter

Exemples: `1` or `1,2,3`

* 📃 Écouter des listes de lecture YouTube via l'URL

`sum.playlist https://www.youtube.com/watch?v=YlUKcNNmywk&list=PL5RNCwK3GIO13SR_o57bGJCEmqFAwq82c`

* 🔎 Les commandes

`Prefix: sum.

Toute les commandes de sumbot codé par JordanHrndz#2323:

sum.help (h)
Display all commands and descriptions

sum.loop (l)
Toggle music loop

sum.lyrics (ly)
Get lyrics for the currently playing song

sum.np
Show now playing song

sum.pause
Pause the currently playing music

sum.play §
Écoute de la musique depuis YouTube ou SoundCloud

sum.playlist (pl)
Écoute une playlist venant de YouTube


sum.pruning
Possibilité de supprimer les messages du bot

sum.queue (q)
Afficher la file d'attente et la musique en cours de lecture.

sum.remove
Supprimer la chanson de la file d'attente

sum.resume ®
Reprendre la lecture de la musique en cours

sum.search
Recherchez et sélectionnez des vidéos à écouter

sum.shuffle
Mélange la file d'attentre

sum.skip (s)
Skip la musique en cours de lecture

sum.skipto (st)
Passer au numéro de file d'attente sélectionné

sum.stop
Arrête la musique

sum.volume (v)
Changer le volume de la musique en cours de lecture

Invitez maintenant sur votre serveur!

faite sum.help pour voir liste complète de SumBot.

![reactions](https://i.imgur.com/OrD1HpT.png)

## 📝 Credits

JordanHrndz#2323
