# TubeSaver

Application Windows gratuite pour télécharger des vidéos autorisées et les convertir en **MOV ProRes** ou **MOV H.264**, prêtes pour le montage.

**Version actuelle : 1.0.0** · Taille indicative : 120 Mo · Windows 10/11 64 bits

## Télécharger

➡️ [Télécharger TubeSaver 1.0.0](https://github.com/kps-prodz/tubesaver/releases/latest)

Aucune installation de Python, yt-dlp ou FFmpeg n'est nécessaire : tout est embarqué.

## Fonctionnalités

- Analyse d'URL (titre, durée, résolution, taille estimée)
- Choix de la résolution : meilleure qualité, 4K, 1440p, 1080p, 720p
- Conversion FFmpeg avec progression, vitesse et temps restant
- Annulation à tout moment
- Historique local
- Fonctionnement 100 % local, sans télémétrie

## Formats proposés

| Format | Usage |
|---|---|
| MOV ProRes 422 | Recommandé pour le montage |
| MOV ProRes 422 HQ | Débit plus élevé, plus de marge en étalonnage |
| MOV H.264 | Fichiers plus compacts |
| Source originale | Fichier tel que fourni, sans conversion |

> ProRes produit des fichiers très volumineux. Une conversion ne recrée pas les détails absents de la source.

## Avertissement SmartScreen

L'application n'est pas signée numériquement. Windows peut afficher un avertissement SmartScreen : cliquez sur **Informations complémentaires**, puis sur **Exécuter quand même**.

Pour vérifier votre téléchargement, comparez l'empreinte SHA-256 du fichier avec celle indiquée dans la page de la release :

```powershell
Get-FileHash .\TubeSaver.exe -Algorithm SHA256
```

## Usage responsable

TubeSaver doit être utilisé uniquement avec des contenus que vous êtes autorisé à télécharger. Respectez les conditions d'utilisation des plateformes et les droits d'auteur. TubeSaver n'est ni affilié à, ni approuvé par YouTube ou Google.

## Licence

Logiciel gratuit (freeware), voir le fichier [LICENSE](LICENSE). TubeSaver embarque [yt-dlp](https://github.com/yt-dlp/yt-dlp) et [FFmpeg](https://ffmpeg.org), soumis à leurs propres licences.

## Créateur

Créé par **kps.prodz**. Pour soutenir le projet et suivre ses évolutions : [TikTok @kps.ae](https://www.tiktok.com/@kps.ae)
