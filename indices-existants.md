# Indices de sécurité / vie privée

L'objectif de cette page est d'observer les systèmes existants pour voir comment ils informent l'utilisateur du niveau de sécurité.

## Signal / silence
Les interfaces de signal et de silence sont assez similaires.

![signal](img/signal-view.png)

- signal prévient à chaque fois que la clé de sécurité change
- signal affiche un double "check" pour les messages sécurisés

![secure](img/non-securise.png)
- À l'envoi du message signal propose "texto non sécurisé" (SMS) et message signal
- couleurs différentes gris = neutre, bleu = positif
- l'icône "appel" a un petit cadenas
![qr](img/qr-signal.png)

- Signal propose de "vérifier le numéro de sécurité". Les chiffres défilent lorsqu'on arrive sur la page, c'est un effet "folklore".
- Un lien "en savoir plus" est proposé, il renvoie vers la question adaptée dans la FAQ de signal.


## Telegram
Je n'ai pas réussi à prendre de capture d'écran d'une conversation sécurisée avec Telegram, mais quand on initialise une conversation sécurisée, il explique en bullet points à l'utilisateur en quoi consiste une conversation chiffrée bout-à-bout.

## Whatsapp / Google Allo / Messenger
Je n'ai pas ça sur mon téléphone, si quelqu'un veut bien jeter un coup d'oeil...

## Firefox
![https](img/firefox-https.png)
![https](img/firefox-https2.png)
![https](img/firefox-https3.png)
Firefox affiche un verrou vert pour les connections http + ssl et donne la possibilité d'en savoir plus. Les informations supplémentaires sont organisées en plusieurs niveaux.
- niveau 0 : cadenas vert
- niveau 1 : logo vert / bouclier / permissions
- niveau 2 : informations sur le certificat
- niveau 3 : informations complètes et détaillées

![private](img/firefox-private.png)
- firefox nous accueille avec une ambiance "sécurité" (couleur différente, logo masque...)
- firefox nous explique ce que la navigation privée permet, ce qu'elle ne permet pas
![private](img/chrome-private.png)
- beaucoup de ressemblances avec firefox
- choix de couleur sombre (gris)
- lunettes de l'espion

##TOSDR
L'extension "terms of service didn't read" prévient l'utilisateur par une pop-up lorsqu'il consulte un site qui a une mauvaise note de protection des données. Voici un example avec Youtube, qui est de classe 'D'.

![tosdr](img/tosdr.png)

Au contraire, duckduckgo est classé 'A', et aucune popup requérant une intervention de l'utilisateur ne s'affiche (on peut toutefois l'afficher comme montré ici.

![ddg](img/tosdr-ddg.png)

