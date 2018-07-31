# Chess-Engines-for-Raspberry-Pi-by-Al
Alan Cooper aka "Ben Dover" has worked hard to compile these chess engines for use with Raspberry Pi (and PicoChess).  

For PicoChess - copy the files to the corresponding folder(s) in /opt/picochess/engines

Arm6l = raspberry pi zerp

Arm7l = raspberry 3b*


PicoChess Engines
January 01, 2018


1. STOCKFISH
===========================
Authors: T. Romstad, M. Costalba, J. Kiiski, G. Linscott
Version: 8
Date: October 2017
Elo: 3360
Levels: yes
Chess960: yes
License: GPLv3
Source: https://stockfishchess.org/
Description: Stockfish is universally recognized as the strongest open source engine
in the world. Even on the modest hardware of a Raspberry Pi 3 it easily beats every
super grandmaster. The vast amount of chess knowledge programmed into Stockfish makes
it an ideal engine to analyze your games. You can set the engine at a lower skill
level to have a chance of winning. Stockfish also supports Chess960 ('Fischer Random
Chess').


2. TEXEL
===========================
Author: Peter Österlund
Version: 1.07
Date: September 2017
Elo: 3050
Levels: yes
Chess960: no
License: GPLv3
Source: http://web.comhem.se/petero2home/javachess/index.html#texel
Description: Texel is the successor to CuckooChess. It is a very strong engine that
will beat every human GM. But thanks to its different skill levels, Texel will
appeal to chess players of every strength. For absolute beginners there is even
a level 0, which lets the engine play random legal moves.


3. ARASAN
===========================
Author: Jon Dart
Version: 20.3
Date: November 2017
Elo: 2980
Levels: yes
Chess960: no
License: MIT
Source: http://arasanchess.org/
Description: Arasan, or 'king' in the Tamil language, is a chess engine that has been
around since 1994 – much longer than most other engines. It has evolved a lot over
the years and is now a very attractive GM level engine. Arasan has a lot of features,
including skill levels to make it an attractive opponent for players of every strength.


4. RODENT III
===========================
Author: Paweł Kozioł
Version: 0.233
Date: November 2017
Elo: 2920
Levels: 'Personalities'
Chess960: no
License: GPLv3
Source: https://github.com/nescitus/Rodent_III/
Description: RodentIII is one of the few chess engines in the world that can adopt
'personalities': it offers different playing styles rather than strength levels.
RodentIII can just as easily be turned into a strong GM as into a beginning kid.
It has both serious and funny personalities, like the positional defender and the
crazy attacker.


5. ZURICHESS
=========================
Author: Alexandru Moșoi
Version: neuchatel
Date: October 2017
Elo: 2790
Levels: yes ('Handicaps')
Chess960: no
License: BSD
Source: http://www.zurichess.xyz/
Description: Zurichess is a relatively young engine. Unlike most other engines
it is not written in C++ but in the Go computer language. And unlike other
engines, its versions are not numbered but named after the cantons of
Switzerland. New versions of Zurichess are rapidly following up each other.
The current version plays at GM level. Weaker opponents may like to set its
handicap level a little higher.


6. WyldChess
===========================
Author: Manik Charan
Version: 1.5
Date: September 2017
Elo: 2630
Levels: 'Personalities'
Chess960: yes
License: GPLv3
Source: https://github.com/Mk-Chan/WyldChess
Description: WyldChess offers something similar to RodentIII with personalities (needs to create more Personae)
and also supports Chess960 ('Fischer Random Chess'). The evaluation is compared to the other top chess
engines not as detailed, but its tactics is very strong.


7. GALJOEN
===========================
Author: Werner Taelemans
Version: 0.37.2
Date: December 2017
Elo: 2150
Levels: yes
Chess960: yes
License: GPLv3
Source: http://www.goudengaljoen.be/
Description: Galjoen is a chess engine that plays at (stronger) club level. It has
an active playing style. Together with its support for strength levels and Chess960
('Fischer Random Chess') this makes Galjoen an ideal opponent for club players
to practice their tactical and strategical skills. The program has its own graphical
user interface, which is, of course, not used by PicoChess.


8. SAYURI
===========================
Author: Hironori Ishibashi
Version: 2017.12.16
Date: December 2017
Elo: 1840
Levels: no
Chess960: no
License: MIT
Source: https://github.com/MetalPhaeton/sayuri
Description: Sayuri is a weaker chess engine than the other famous engines.
Sayuri is a customizable UCI chess engine with Sayulisp (=Scheme-like Lisp interpreter)
which allows you to customize the search algorithm or adjust the evaluation weights.
For details please take a look at the sayuri webpage.
If you are looking for a beatable engine that can teach you a thing or two about chess,
then Sayuri is a good choice.


DGT PI WITH 60 ENGINES
The DGT Pi chess computer offers a nice mix of different chess engines. With Stockfish, Texel, Arasan, Rodent II, Zurichess, Floyd, Cinnamon and Claudia the right game partners are on board for beginners as well as professionals.

Even more variety now offers our engine package , which extends the gaming experience to 60 engines. In addition to updated versions of existing engines, such as Stockfish 9, the following engines are included in the package:

Leela Chess Zero
We've already honored this engine with a post and step by step tutorial that will allow anyone with some Linux experience to get this engine running on their DGT Pi. In our package, the installation steps are already done and you can start right away. The setting of the game strength takes place via a so-called Weights file. This file contains the chess "knowledge". In our package, we decided on a Weights file, which provides a game strength of about 1800 to 2100 ELO. The playing style of Leela can be described as extremely inhumane human. Far away from clinically pure chess, Leela marvels with a creativity in which one will shake his head in amazement.

Stockfish 9
We do not need to talk about this engine. At the highest level, an excellent analyst and, on the lower levels, a gracious judge giving opportunities.

Texel 1.08a8 32-bit
Texel is one of the stronger engines. Especially in lightning and rapid chess games, these engines show their untamed potential. If you want to let yourself get carried away in a blitz game, you'll get the well-deserved attrition from this engine🙂

Arasan TCEC12-74-g345b401
This original engine has been improved over the years. While it can not compete with the top engines, the style of play is a lot of fun. Already in the 90s, this engine was included in almost every chess program interface. At the online chess client BlitzIn of  the ICC there were also some cheaters who had this engine for themselves. Varied games are in the foreground here.

Rodent II 0.9.66
Incredible many settings via a configuration file provides this engine. Instead of individual game levels, you can choose the level of play through a large selection of characters. From Karpov to Tal to the Drunken Master and the scaredy hare, there is just about every chess character you can imagine. If there is an engine that offers pure variety, then it is by far this engine.

Rodent III 0.250 32-bit / GCC 6.3.0 20170516
The successor to Rodent II offers even more "tuning" options and leaves game characters even more detailed replicas.

Defenchess 1.2x64
This engine, developed by two Turkish programmers, is also great for analyzing chess games. Other than the name suggests, the part in his games goes neatly forward.

Zurichess Neuchatel
With each new version, the Zurichess engine receives a new name addition. Also, this engine is not one of the top ten, although with an estimated ELO of about 2500, it already knows exactly how to set a dull opponent. The gameplay can be controlled down wonderfully, which is a good training tool for beginners. The style of play is very positional and strategic.

Emblatrunk
For the ambitious club player the perfect engine. Not too strong, but definitely a fighter. Especially in the middlegame, this engine can be a tempo here and there, which you can quickly exploit as an attentive chess player.

WyldChess
Also a beatable engine, where you should not lose patience here. If this engine is on the trigger, it can not take the full point.

Fruit reloaded 17/12/08
Just about every one of today's top ten engines is based on ideas of evaluation that originated in this engine. Fruit is open-source and the engine Stockfish would not be on top today if it had not Fruit. Even today, this engine is incredibly strong and an unconquerable mountain for the average Joe chess player. Fortunately, you can also regulate the game down here. Fruit is an enthralling game and it is the game of the jumpers that makes the human opponent more than once in despair.

Galjoen 0.38
If you like Chess960, you will love this engine. Because exactly in this chess variant makes the part really much fun. The style of play can be described as perfectly balanced. The aggressiveness is limited and so you can give this engine in any case the seal "solid".

Glaze 2.2
Incredibly strong and a serious opponent in Rybka's time. This engine is perfect for both analysis and low level training games.

Sayuri 2018.05.23
A chess engine, which was completely designed for the game against humans. The adjustment possibilities range from the evaluation of individual figures to the evaluation of exact positional characteristics. When playing, you always have the good feeling of being in the game and having chances to the end. To get the full point, you have to be one of the better club players.

Floyd 0.9
With well over 2000 ELO, this engine is also a very good sparring partner. Tactically always very good at altitude, this opponent, however, often does not really know about the positional area.

Marvin 3.0.0
Always in the direction of the king! This engine wants to put dull and goes as good as any peaceful point division out of the way. The strength of the game against people I would estimate at about 2500 ELO. The goal is almost always very tactical positions in which human opponents very quickly lose track. The engine is also not too bad to invest some material for an attack.

K2 v.0.91
the mountain calls! However, only up to a height of about 2300 ELO meters. Again, we have a good sparring partner for better club players. What makes this engine so interesting are the opening ideas. With the book off or 5-8 moves, this engine often finds refreshing new ideas in the opening area. If you need new food for lightning, you will love it here.

Laser 1.6 beta
An engine from which we will hear / read a lot in the future. This is where ideas from Engines such as Fruit and Texel come together and the result is an extremely strong opponent that is also wonderfully suited for analysis.

Cinnamon 2.0-20160502
It's fun to play chess against this not too strong engine. As soon as the game finishes, Cinnamon begins to falter. Even in the middle game, the part likes to overlook concrete profit transactions.

McBrain 9.2
Study turns and sacrifices are the specialty of this engine. Here you will be surprised even in blitz games. Incredibly strong and imaginative chess!

DanaSah 6.5
And another nice opponent for amateur and club players. On the lower levels you get good opportunities to test his favorite opening. Matt attacks with character victims make this engine a lot of fun.

Nemorino
Although some techniques have been taken over by Stockfish, it has not brought this engine very far. Too much of this opponent is stuck to a plan already set and can be, although in some cases wrong, convince only by a matte-pull of the opposite.

Amoeba 2.4.1.l32a
Also this engine belongs to the weaker of the guild. With about 2300 ELO a strikeable opponent, which has deficits especially in the positional area. Especially in blitz games, this engine quickly reaches its limits. She just needs more time to get going.

Dragontooth 0.1 Azazel 1CPU
This engine means well with its opponent. The solid playing style can be cracked quite well by acting directly towards the king. Even openings such as the King's Gambit bring the part quickly out of rhythm.

OpenTal 1.1 32-bit / GCC 6.3.0 20170516
A beautiful positional style paired with punchy tactics make this engine a valuable game partner. Almost in the style of Karpov, the games are relentlessly led towards the full point.

Pedone 1.7
In the first versions rather an engine that has been laughed at. Easy to dub and no chances in the final. Bit by bit, this engine has been improved and even as a good 2000s one has to solve very big problems, before you can claim the full point for yourself.

Demolito 2017-08-26
and again a very powerful engine where every human opponent will despair at the highest level. The consistent attacking game leaves little room for a decent defense and even the most solid position is taken apart by this engine.

Robocide 0.4
For a change, it may also give something lighter fare again. This engine plays at a level of about 1900 ELO. With a little skill you can create a positional advantage in a material advantage. The full point is still not given and as a club player you can definitely tap on the shoulder, if you can record a victory.

Zevra 180318
As the best engine announced by the authors, the program lingers rather in the middle of his existence. That is not bad, because stockfish are already enough. Good plays the part and on the lower levels also with a wonderfully naive creativity.

SCTR 1.1f x64 fix
At the Grandmaster level, this engine is also scratching. But only when it comes to tactical positions. Positionally, this engine has too little patience. Another sparring partner that is fun.

Senpai 2.0
Strong play in all areas distinguishes this engine. In the lower levels an interesting opponent and with full playing ability a good analysis partner. Here, the engine sometimes finds ways that the top ten engines are not on the screen.

MateFinder 150618
Here is the king attack in the foreground. No other engine works so hard on matt attack right from the start as this engine. Repeat repetitions can be virtually ruled out.

Shallow Blue 1.1.0
The average club player will be pleased. With about 1500 ELO, this engine is one of the simpler tasks. After the opening, it is worthwhile to attack directly. But alas, your own king is uncertain! Then the engine pulls out to the counter-stroke.

Snowy 0.2-2-gcd8622e
About 1800 ELO can book this engine in their account. Once again, it's the positional aspects that are fatal to this engine. But tactically, this engine is sometimes overzealous.

Sting SF 9.99
Based on stockfish, this engine was developed. With a playing power of about 2700 ELO, however, it does not approach the original. Nevertheless, this engine offers interesting ideas in both analysis and gaming.

Stockfish 1.9.1 to Stockfish 8
The entire Stockfish series shows pretty well how a rather mediocre engine quickly became the best engine in the world. With each new version existing errors were eliminated and already existing good ideas further improved. A collection that should not be missing on any DGT Pi.

SugaR_XPrO 150618 x32
Another engine based on stockfish. However, interesting ideas in the search algorithm make this engine something special. You also notice this in the game and in the analysis.

The rest of the engines in this package are also largely stockfish derivatives, in which programmers have immortalized their handwriting with their own ideas. This is very well done in most cases.

The DGT Pi really offers everything the chess heart needs with this engine package.
