# Crowns and Tears - Covid-19 visualisation using a music box, punch cards and too much of spare time...
How are you? Hope you are doing well! Here you find everything I used to make a Covid-19 visualisation from my home country using a music box and punch cards. Feel free to contact me!  
Stay healthy!  
Simon  
[journalist.ch](https://www.journalist.sh)
## Crowns and Tears - How it sounds
[![See the visualisation](docs/origin_preview.png)](http://www.youtube.com/watch?v=DqfrOPs2pKM)

## Crowns and Tears - What it should have sounded like
[![See the (artificial) visualisation](docs/artificial_preview.png)](https://youtu.be/plj-s2xVi50)

## Here you will find:
* [The Sheet of Music](sheet/crowns_and_tears.pdf)
* [A sound file (mp3)](sheet/crowns_and_tears.mp3)
* [The punch card](sheet/crowns_and_tears_stripes.pdf)
* [The Source Code](python/create%20stripes.ipynb)
* And other stuff like the inDesign version, a musicxml-export, etc. 

## How it works
I used [Muse Score](https://musescore.org/de) to compose the song. The python script does this:
* Imports the sheets of music (it has to be saved as an uncompressed musicxml)
* Converts it to an array where the lowest note (C) = 0. Each Array item represents a bar.
* The array is now transformed into punch cards and saved as a SVG graphic.
* The script now creates a PDF to print. I did not used this, I opend the svg in inDesign and added text.

## What you should consider
* I used a music box from [Banggood](https://www.banggood.com/DIY-Hand-Cranked-Music-Box-15-Tone-Wooden-Box-With-Hole-Puncher-And-Paper-Tapes-Birthday-Gift-Present-p-1040359.html).
* I wrote it in C-Mayor but the music box is actually in A flat major (or something like this).
* If you like to play the same note twice, you need to leave some space between (at least a quarter, like the «days» in the video above). Otherwise the music box is not able to play it.
* I printed it on 160g paper and sticked it to another 80g paper.
* Ask your doctor if you get a typewriter's cramp from stamping out the cards...