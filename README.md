# FCSC 2022 Daddy Morse

es télégraphes Morse permettaient d'échanger des messages de texte à longue distance, en encodant un message sous forme d'impulsions électriques. Le serveur se comporte comme un mini-télégraphe et décode les données que vous lui envoyez.

Vous devez envoyer **CAN I GET THE FLAG**.

Vous avez le code du serveur ainsi qu'un exemple de message à disposition.

Les paramètres de transmission sont les suivants :

fréquence d'échantillonnage : 24kHz,
durée d'un . : 1 milliseconde,
durée d'un - : 5 millisecondes,
espacement entre deux lettres : 5 millisecondes,
espacement entre deux mots : 20 millisecondes.

Fichiers :
- [daddy-morse.py](daddy-morse.py)
- [client.py](client.py)
- [signal.iq](signal.iq)


Cette épreuve a été découpée en trois étapes :

- Baby Morse.
- **Daddy Morse**.
- Mommy Morse.

Auteur : ElyKar

Origine : [Daddy Morse](https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-daddy-morse/)

-----------

## Connectez vous en WEBSSH
> http://localhost

#### tentez 
> nc daddy-morse.cyrhades.fr:4000

-----------

## Ou directement avec netcat
> nc localhost:4000


-----------

## Installation manuel
Vous n'utilisez pas l'application **les CTFs de Cyrhades** ? C'est dommage !
Mais voici comment installer ce CTF manuellement :

> git clone https://github.com/Hack-Oeil/fcsc2022-hardware-daddy-morse.git

> cd fcsc2022-hardware-daddy-morse


-----------

## Sur le site officiel hackropole.fr
> https://hackropole.fr/fr/challenges/hardware/fcsc2022-hardware-daddy-morse/