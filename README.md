# Helii-Arduboy

The classic side-scrolling tunnel game, ported to Arduboy.

Tap the B button to fly your helicopter through the tunnel without crashing into the floor or ceiling.

Use A to pause.

## TODO

- [x] Gameplay
- [x] Title screen
- [x] SFX
- [ ] Menu text
- [x] Fix left column flicker bug
- [ ] Music and better SFX
- [x] Scores
- [ ] Mute option

## Photos

![](http://i.imgur.com/IAjFicf.jpg)

## Video

[![](http://i.imgur.com/ZxPtocO.jpg)](https://www.youtube.com/watch?v=qRWQsEqT_yk)

## Origin

Helii was originally written as a Wii homebrew game ([source](https://github.com/BHSPitMonkey/bhspitmonkey-code/tree/master/wii/helii)), which was then ported to the 3DS ([source](https://github.com/BHSPitMonkey/Helii3DS)) before finally being ported (very messily!) to Arduboy.

## Compiling

1. Download the Arduino IDE
2. Open `Helii-Arduboy.ino`
3. Select Tools > Board > "Arduino Leonardo"
4. Go to Tools > Manage Libraries... and install "Arduboy"
5. Click "Verify" to compile the sketch
6. Click "Upload" to upload the sketch to a connected Arduboy device