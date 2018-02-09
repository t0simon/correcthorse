# Korrektes Pferd (Correcthorse)

Generates **secure**, **easy to type**, **easy to remember** passphrases and use a german wordlist

## Install

```
sudo wget -O /usr/local/bin/correcthorse https://raw.githubusercontent.com/t0simon/korrektespferd/master/correcthorse
sudo chmod +x /usr/local/bin/correcthorse
```

## Examples

```
$ correcthorse
dichtefunktion wiesentalstraße Gratislieferung Leseranteil
```
```
$ correcthorse 6
blutspendezentrale Festungsstädte inbetriebnahmezeit Befrachten Präsentationszweck bürokratendeutsch
```
```
$ correcthorse 5 '-'
authentizitätsanspruch-detailversessen-feuchtfläche-Farnprärie-zusammenhanglos
```
```
$ correcthorse 5 '+'
zeitschriftenregal+ausgekocht+klan+Urne+aufwascheimer
```
```
$ correcthorse 5 '*'
kaschmirpullover*Postenturm*Verbarrikadieren*interferieren*koaxial
```

## Links

https://xkcd.com/936/

http://world.std.com/~reinhold/diceware.html

https://cgit.freedesktop.org/libreoffice/dictionaries/plain/de/de_DE_frami.dic
