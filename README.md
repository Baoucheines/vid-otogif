# vid-otogif
Convertir une vidéo en GIF en python
Ce projet contient un script Python simple pour convertir une vidéo en GIF en utilisant la bibliothèque moviepy.

## Exigences :

- Python 3.x
- moviepy

## Commencer :

### Créer le répertoire du projet

```bash
mkdir video-to-gif
cd video-to-gif
```
### Ajouter un fichier convert_to_gif.py
``` python
from moviepy.editor import VideoFileClip
```
```
# Chemin de la vidéo d'entrée
input_video = r"C:\Users\BAOUCHE\Downloads\Ines.mp4"

# Charger la vidéo
video = VideoFileClip(input_video)

# Chemin de sortie pour le GIF
output_path = "X:\\RH\\KIT NOUVEAUX ARRIVANTS\\PUB Youtube Corporate.gif"

# Convertir la vidéo en GIF
video.write_gif(output_path)

print("Conversion terminée. Le GIF a été sauvegardé à l'emplacement :", output_path)
```
### Installation 
```bash
pip install moviepy
```
- Cloner le pojet
```bash
git clone https://github.com/votre_nom_utilisateur/video-to-gif.git
cd video-to-gif
```
***Assurez-vous de remplacer "C:\Users\BAOUCHE\Downloads\Ines.mp4" par le chemin de votre propre vidéo d'entrée et "X:\\RH\\KIT NOUVEAUX ARRIVANTS\\PUB Youtube Corporate.gif" par le chemin de sortie souhaité pour votre GIF***
### Exécuter le script :
***Sauvegardez le script sous un nom de fichier, par exemple convert_to_gif.py***
```sh
python convert_to_gif.py
```
