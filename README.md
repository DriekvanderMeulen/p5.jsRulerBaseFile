# Created by Driek van der Meulen

# Creation date: 23/11/2022

# P5 base file with ruler libary installed

- In een readme file worden #, - en \_ gebruikt om tekst te kleuren, let op dat je dit niet meeneemt naar je code! -

- De ruler werkt alleen met een canvas met innerWidth en innerHeigt -
  _createCanvas(innerWidth, innerHeight)_
- Meeste MMT opdrachten werken met een canvas met bepaalde dimensies -
  _createCanvas(400, 400)_
- Deze waardes moeten dus aangepast worden voorafgaand aan het inleveren van een opdracht -
- Let op dat je de opdracht maakt binnen het canvas wat wordt angegeven -

- Met deze waarde kan je de ruler aan of uit zetten -
  _utils.enableRuler();_
- Zet deze waarde alleen aan waneer je de ruler wilt gebruiken en innerWidth, innerHeight gebruikt -

_fucntion met ruler;_

- function setup() {
  createCanvas(innerWidth, innerHeight);
  utils.enableRuler();
  }

_function zonder ruler_

- function setup() {
  createCanvas(400, 400);
  }
