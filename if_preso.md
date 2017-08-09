---
title: You’re Likely to be Eaten by a Grue
subtitle: foo
author: Jeremy Austin Clewell
patat:
    wrap: true
    theme:
        codeBlock: [dullRed]
...

```






          _-_,         ,                      ,                    
            //        ||                _    ||   ' ;              
            || \\/\\ =||=  _-_  ,._-_  < \, =||= \\ \\/\  _-_      
           ~|| || ||  ||  || \\  ||    /-||  ||  || || | || \\     
            || || ||  ||  ||/    ||   (( ||  ||  || || | ||/       
          _-_, \\ \\  \\, \\,/   \\,   \/\\  \\, \\ \\/  \\,/      

                       _ ,                            
                     ,- -           ,                 
                   _||_   '       ||   '             
                  ' ||   \\  _-_ =||= \\  /'\\ \\/\\
                    ||   || ||    ||  || || || || ||
                    |,   || ||    ||  || || || || ||
                  _-/    \\ \\,/  \\, \\ \\,/  \\ \\

```

---

## Interactive Fiction

> Often abbreviated **IF**, interactive fiction is software simulating environments in which players use text commands to _control characters_ and _influence the environment_.

Part of a larger family of "**Text Adventure**" games, variants include:

* Interactive Fiction
* CYOA / Hyper-text fiction
* Rogue-likes
* MUD

---

```

 _____         _                          _     _____                      
/  __ \       | |                        | |   /  __ \                     
| /  \/  ___  | |  ___   ___  ___   __ _ | |   | /  \/  __ _ __   __  ___  
| |     / _ \ | | / _ \ / __|/ __| / _` || |   | |     / _` |\ \ / / / _ \
| \__/\| (_) || || (_) |\__ \\__ \| (_| || |   | \__/\| (_| | \ V / |  __/
 \____/ \___/ |_| \___/ |___/|___/ \__,_||_|    \____/ \__,_|  \_/   \___|

          ___       _                      _                      
         / _ \     | |                    | |                     
        / /_\ \  __| |__   __  ___  _ __  | |_  _   _  _ __   ___
        |  _  | / _` |\ \ / / / _ \| '_ \ | __|| | | || '__| / _ \
        | | | || (_| | \ V / |  __/| | | || |_ | |_| || |   |  __/
        \_| |_/ \__,_|  \_/   \___||_| |_| \__| \__,_||_|    \___|


                  _..-'(                       )`-.._
               ./'. '||\\.       (\_/)       .//||` .`\.
            ./'.|'.'||||\\|..    )O O(    ..|//||||`.`|.`\.
         ./'..|'.|| |||||\`````` '`"'` ''''''/||||| ||.`|..`\.
       ./'.||'.|||| ||||||||||||.     .|||||||||||| |||||.`||.`\.
      /'|||'.|||||| ||||||||||||{     }|||||||||||| ||||||.`|||`\
     '.|||'.||||||| ||||||||||||{     }|||||||||||| |||||||.`|||.`
    '.||| ||||||||| |/'   ``\||``     ''||/''   `\| ||||||||| |||.`
    |/' \./'     `\./         \!|\   /|!/         \./'     `\./ `\|
    V    V         V          }' `\ /' `{          V         V    V
    `    `         `               V               '         '    '


```

---

## Colossal Cave Adventure (Advent)

#### Will Crowther - 1976

> "You are in a maze of twisty little passages, all alike"

Written by _Will Crowther_ (who helped develop _ARPANET_) in 75-76. 700 lines of FORTRAN for the PDP-10 mainframe. With a 300kB memory footprint, it consumed almost 50% of the mainframe's resources.

Filename “**ADVENT**” due to a char length restriction.

* a treasure hunt

* 2 word commands, i.e. “get lamp” or "hit troll"

* 78 map locations, 193 vocabulary words

* **XYZZY** - a magic word that makes it's way into geek culture

---

### Advent's origins

* Will Crowther had played D&D with Dave Lebling, one of the later founders of **Infocom**.

* Crowther and wife avid spelunkers, helped survey _Bedquilt Cave_ (an entrance to Mammoth cave in Kentucky).

* Following their divorce, Crowther looked for a method to better connect with his daughters.

* Bedquilt contains 10 lineal miles of passages within one square mile of land (_twisty little passages_).

* Passages in _ADVENT_ map directly to their Bedquilt counterparts.

* Unbeknownst to Crowther, distributed over _ARPANET_ while on vacation, the game's acceptance was a surprise.

* _Don Woods_, a grad student studying in _Stanford’s AI Lab_ discovered _ADVENT_ on _ARPANET_ and connected Will to ask if he could expand upon the game.
  * 700 >> 2300 - lines of FORTRAN
  * 78 >> 140 - location count
  * 193 >> 293 - vocabulary words
  * ...ran in only 2/3rds the memory footprint

---

### Linear map structure in Advent

```





                             +-----------+
                             |           |
                             |  Room B   |
                             |           |
                             +-----^-----+
                                   |
              +-----------+  +-----v-----+  +-----------+
              |           |  |           |  |           |
              |  Room E   <-->  Room A   <-->  Room C   |
              |           |  |           |  |           |
              +-----------+  +-----^-----+  +-----------+
                                   |
                             +-----v-----+
                             |           |
                             |  Room D   |
                             |           |
                             +-----------+
```

---

```
                       _________________ _   ___
                       |___  / _ \| ___ \ | / / |
                         / /| | | | |_/ / |/ /| |
                        / / | | | |    /|    \| |
                      ./ /__\ \_/ / |\ \| |\  \_|
                      \_____/\___/\_| \_\_| \_(_)
  _____________________________________________________________________
  |.._|      | `-.  | `.  -_-_ _-_  _-  _- -_ -  .'|   |.'|     |  _..|
  |   `-.._  |    |`!  |`.  -_ -__ -_ _- _-_-  .'  |.;'   |   _.!-'|  |
  |      | `-!._  |  `;!  ;. _______________ ,'| .-' |   _!.i'     |  |
  |..__  |     |`-!._ | `.| |_______________||."'|  _!.;'   |     _|..|
  |   |``"..__ |    |`";.| !|_|MMMMMMMMMMM|_|'| _!-|   |   _|..-|'    |
  |   |      |``--..|_ | `;!| |MMoMMMMoMMM| |.'j   |_..!-'|     |     |
  |   |      |    |   |`-,!_|_|MMMMP'YMMMM|_||.!-;'  |    |     |     |
  |___|______|____!.,.!,.!,!| |MMMo * loMM| |,!,.!.,.!..__|_____|_____|
  |      |     |    |  |  | |_|MMMMb,dMMMM|_|| |   |   |    |      |  |
  |      |     |    |..!-;'i| |MPYMoMMMMoM| | |`-..|   |    |      |  |
  |      |    _!.-j'  | _!,"|_|M()MMMMoMMM|_||!._|  `i-!.._ |      |  |
  |     _!.-'|    | _."|  !;| |MbdMMoMMMMM| |`.| `-._|    |``-.._  |  |
  |..-i'     |  _.''|  !-| !|_|MMMoMMMMoMM|_|.|`-. | ``._ |     |``"..|
  |   |      |.|    |.|  !| | |MoMMMMoMMMM| ||`. |`!   | `".    |     |
  |   |  _.-'  |  .'  |.' |/|_|MMMMoMMMMoM|_|! |`!  `,.|    |-._|     |
  |  _!"'|     !.'|  .'| .'|[@]MMMMMMMMMMM[@] \|  `. | `._  |   `-._  |
  |-'    |   .'   |.|  |/| /                 \|`.  |`!    |.|      |`-|
  |      |_.'|   .' | .' |/                   \  \ |  `.  | `._    |  |
  |     .'   | .'   |/|  /                     \ |`!   |`.|    `.  |  |
  |  _.'     !'|   .' | /                       \|  `  |  `.    |`.|  |
  |___________________________________________________________________|

```

---

## Zork
#### MIT - 1978

* Initially written by Tim Anderson, Marc Blank, Bruce Daniels, and Dave Lebling.
    * All members of MIT's _Dynamic Modeling Group_.
    * Those writing the program referred to themselves as **Imp**lementers.
* Designed in _MDL_ (“_Muddle_”, the _MIT Design Language_), a descendant of LISP.
* Ran on _PDP-10_ mainframe running on the _ITS_ (Incompatible Timesharing System) OS.
* Parser not limited to 2 word commands as in _Advent_.
* Prepositions and conjunctions recognized.

**Advent:**

> “Hit Troll”

**Zork:**

> “Hit the troll with the Elvish sword”

---

## Zork (continued)

* patched version of ITS hid the source dir.

* _somebody?_ patched the patched OS and gained access to the dir.

* Bob Supnik successfully ported from _MDL_ to _FORTRAN IV_ port >> _PDP-11_

#### What’s in a name…_Zork_?

Zork was MIT slang for an unfinished piece of software.

#### Copyright infringement
In 1978, after it’s completion, the “_Imps_” renamed _Zork_ to “_Dungeon_”...however they received notice from _Tactical Studies Rules (TSR)_, developers of “_Dungeons & Dragons_” claimed the name violated their copyrights. The  developers promptly renamed the game to _Zork_!

---

### Nonlinear map structure in Zork

```



                      +----------------------------+
                      |     +-----------+          |
                      |     |           |          |
                      |  +-->  Room B   <-+        |
                      |  |  |           | |        |
                      |  |  +-----------+ |        |
                      |  |                |        |
        +-------------+  |        +-------+        |
        |                |        |                |
        |  +-----------+ |  +-----+-----+    +-----v-----+
        |  |           | |  |           |    |           |
        +-->  Room E   | |  |  Room A   +---->  Room C   <-+
           |           | |  |           |    |           | |
           +-----^-----+ |  +-----^-----+    +-----^-----+ |
                 |       |        |                |       |
                 +---------------------------------+       |
                         |        |                        |
                         |  +-----v-----+                  |
                         |  |           |                  |
                         +-->  Room D   <------------------+
                            |           |
                            +-----------+
```

---

## Rise of Incofom

#### 1979, dawn of the _Personal Computer_

A few MIT staffers and students founded _Infocom_ with the intent of monetizing Zork, but _MDL_ and _FORTRAN_ were not available on the newly arrived "_PCs_".

Solution: _Z-machine_ - running the _Zork Implementation Language_ - “_ZIL_”

VM Ported to various platforms in shells known as “_Z-machine Interpreter Program_”, or _ZIP_ for short

* Floppys: 180 kB
* Zork > 1mb.

_Zork_ was eventually released in thirds due to this restriction.

* Zork I: The Great Underground Empire (1980)
* Zork II: The Wizard of Frobozz (1981)
* Zork III: The Dungeon Master (1982)

---

## Feelies!



---

```

    ____     __                         __     ______            __    __
   / __ \   / /  ____ _   ____   ___   / /_   / ____/  ____ _   / /   / /
  / /_/ /  / /  / __ `/  / __ \ / _ \ / __/  / /_     / __ `/  / /   / /
 / ____/  / /  / /_/ /  / / / //  __// /_   / __/    / /_/ /  / /   / /  
/_/      /_/   \__,_/  /_/ /_/ \___/ \__/  /_/       \__,_/  /_/   /_/   
      .                                                   +
              +                            .                           +
  .                           +  
             .           	                        _.oo.       +
                             _.u[[/;:,.         .odMMMMMM'
    +                 +   .o888UU[[[/;:-.  .o@P^    MMM^
                         oN88888UU[[[/;::-.        dP^
              _         dNMMNN888UU[[[/;:--.   .o@P^       .
             (_)       ,MMMMMMN888UU[[/;::-. o@^
                       NNMMMNN888UU[[[/~.o@P^             :  
               +       888888888UU[[[/o@^-..     .      --+--
         +            oI8888UU[[[/o@P^:--..               !
                   .@^  YUU[[[/o@^;::---..	    _
   .             oMP     ^/o@P^;:::---..       (_)
              .dMMM    .o@^ ^;::---...
             dMMMMMMM@^`       `^^^^       .
            YMMMUP^                                   .:      +
  +       . ^^        .
          +                   .       .            :      .

```

---

## PlanetFall
#### Infocom 1983

* One of _Infocom_’s most successful works.
* "**Floyd**", a robot companion within the game became one of the first NPCs ever to draw deep emotional responses from players.
  ** _spoiler: Floyd might die?_
* Possibly inspired Sierra's "Space Quest" (how many space comedies with mop-wielding protagonists can there be?)

---

```


     _______                                        __            __
    |     __|.--.--..-----..-----..-----..-----..--|  |.-----..--|  |
    |__     ||  |  ||__ --||  _  ||  -__||     ||  _  ||  -__||  _  |
    |_______||_____||_____||   __||_____||__|__||_____||_____||_____|
                           |__|  
                                 _____
                                |     |
                                |_____|
                          ____ ___|_|___ ____
                         ()___)         ()___)
                         // /|           |\ \\
                        // / |           | \ \\
                       (___) |___________| (___)
                       (___)   (_______)   (___)
                       (___)     (___)     (___)
                       (___)  ___/___\___   | |
                        | |  |___________| /___\
                       /___\  |||     ||| //   \\
                      //   \\ |||     ||| \\   //
                      \\   // |||     |||  \\ //
                       \\ // ()__)   (__()
                             ///       \\\
                          _///___     ___\\\_
                         |_______|   |_______|
```

---

## Suspended
#### Infocom - 1984

The player take the role of a "**Central Mentality**", a body cryogenically suspended but mentally aware that controls systems supporting an inhabited planet.
The player is only able to interact with the world through a number of robot surrogates, each with their own strengths ands weaknesses.

* _Auda_ - audio sensors
* _Iris_ - visual sensors
* _Poet_ - electrical sensors
* _Sensa_ - magnetic sensors
* _Waldo_ - physical manipulation (from Robert A. Heinlein's short story describing teleoperated robots)
* _Whiz_ - retrieving library data

* _Fred_ - all-purpose repair robot who spends the entire game broken

---

```

             _____ __   _ _______ _____ ______  _______       
               |   | \  | |______   |   |     \ |______ |     
             __|__ |  \_| |       __|__ |_____/ |______ |_____


            _                                                      
        /     __   \                                               
          /   _ -    |                                             
      | '  | (_)  |                        _L/L                    
         |  __  /   /                    _LT/l_L_                  
        \ \  __  /                     _LLl/L_T_lL_                
            -      _T/L              _LT|L/_|__L_|_L_              
                 _Ll/l_L_          _TL|_T/_L_|__T__|_l_            
               _TLl/T_l|_L_      _LL|_Tl/_|__l___L__L_|L_          
             _LT_L/L_|_L_l_L_  _'|_|_|T/_L_l__T _ l__|__|L_        
           _Tl_L|/_|__|_|__T _LlT_|_Ll/_l_ _|__[ ]__|__|_l_L_      
   _ ___ _LT_l_l/|__|__l_T _T_L|_|_|l/___|_ _|__l__|__|__|_T_l_  __
        . ";;:;.;;:;.;;;;_Ll_|__|_l_/__|___l__|__|___l__L_|_l_LL_  
          .  .:::.:::..:::.";;;;:;;:.;.;;;;,;;:,;;;.;:,;;,;::;:".'
                 . .:.:::.:::.:::: .::.::. :::.::::..::..:.::. . .
                       .:. ..   . ::.. .: ::. ::::.:: ::::::.   .  
             nn_r   nn_r  .           .:. :.. :::. ::..: :.       
            /l(\   /l)\      nn_r          . ::. :. : : ..         
            `'"``  ``"``    /\(\                 . :.
                            ' "``                   .          
```

---

## Infidel
#### Infocom - 1983

* Patterned after _Indiana Jones: Raiders of the Lost Ark_
* Main character greedy and prideful 
* The game had an unhappy ending

Incredibly polarizing:

*  PC Magazine rated it a _12_ out of _12_
*  _Scorpia_ (popular video game journalist for Computer Gaming World), normally an Infocom fan, so disliked Infidel she _refused to even mention it_ in CGM articles.

---

```


    _   _  _  _          _      _      _  _                 _      
   | | | |(_)| |        | |    | |    (_)| |               ( )     
   | |_| | _ | |_   ___ | |__  | |__   _ | | __  ___  _ __ |/  ___
   |  _  || || __| / __|| '_ \ | '_ \ | || |/ / / _ \| '__|   / __|
   | | | || || |_ | (__ | | | || | | || ||   < |  __/| |      \__ \
   \_| |_/|_| \__| \___||_| |_||_| |_||_||_|\_\ \___||_|      |___/
                   _____         _      _
      .           |  __ \       (_)    | |            *
                  | |  \/ _   _  _   __| |  ___              *
               *  | | __ | | | || | / _` | / _ \   .
                  | |_\ \| |_| || || (_| ||  __/            .
 *         |       \____/ \__,_||_| \__,_| \___|
         -(o)-                                    
           |                  _.-----._                    _
                      \)|)_ ,'         `. _))|)        ,--(_)  
   *                   );-'/             \`-:(        /.    \     *
                      //  :               :  \\       \:.   /  
             *       //_,'; ,.         ,. |___\\       `---'   
                     `---':(  `-.___.-'  );----'
                   .       \`. `'-'-'' ,'/           *
   .         ,-.            `.`-.,-.-.','      
            (///)             ``---\` :                           .
             `-'      *             `.'       *’
     .                      .                    .         *
```

---

## The Hitchhiker's Guide to the Galaxy
#### Infocom 1984

Designed by _Douglas Adams_ and Infocom's _Steve Meretzky_

_Computer Gaming World_ ranked it at **42/150** greatest games of all time

* Second place in sales only to Zork 1

* Noted for its difficult puzzles

---

```
       .%%%%%%..%%%%%...%%%%%%..%%..%%..%%%%%%..%%%%%%..%%..%%.
       ...%%....%%..%%....%%....%%%.%%....%%......%%.....%%%%..
       ...%%....%%%%%.....%%....%%.%%%....%%......%%......%%...
       ...%%....%%..%%....%%....%%..%%....%%......%%......%%...
       ...%%....%%..%%..%%%%%%..%%..%%..%%%%%%....%%......%%...
                           ________________
                      ____/ (  (    )   )  \___
                     /( (  (  )   _    ))  )   )\
                   ((     (   )(    )  )   (   )  )
                 ((/  ( _(   )   (   _) ) (  () )  )
                ( (  ( (_)   ((    (   )  .((_ ) .  )_
               ( (  )    (      (  )    )   ) . ) (   )
              (  (   (  (   ) (  _  ( _) ).  ) . ) ) ( )
              ( (  (   ) (  )   (  ))     ) _)(   )  )  )
             ( (  ( (  (  )     (_  )  ) )  _)   ) _( ( )
              ((  (   )(    (     _    )   _) _(_ (  (_ )
               (_((__(_(__(( ( ( |  ) ) ) )_))__))_)___)
               ((__)        \\||lll|l||///          \_))
                            /(/ (  )  ) )\    
                           ( ( ( | | ) ) )\    
                           /(| / ( )) ) ) ))  
                           ( ((((_(|)_)))))      
                             ||\(|(|)|/||      
                             |(||(||)||||         
                            //|/l|||)|\\ \      
                    (/ / //  /|//||||\\  \ \  \ _)
-----------------------------------------------------------------------

```

---

## Trinity
#### Infocom - 1986

* Moving through time playing witness to a number of nuclear disasters
* Actual _historic incidents_ and fictional _future events_.
* Computer Gaming Wold called it "a tense, ethical tightrope walk through the Cold War"
* _Infocom’s 20th work_, their last before they were acquired by _Activision_

After authoring the game, _Brian Moriarty_ stated:

> writing it wasn't a pleasant experience, I can tell you that. It's not easy to sit down and write that stuff ... It was hard to live with that game for a year

_[Scorpia (November 1986). "Designer Profiles: Brian Moriarty" (PDF). Computer Gaming World. No. 32. pp. 16–18. Retrieved 2017-08-01]_

---

```


                    ____ _  _ _  _ ____ ____ _ ____
                    |__| |\/| |\ | |___ [__  | |__|
                    |  | |  | | \| |___ ___] | |  |

                          (
                         (_)
                         ###
                         (#c     _\|/_
                          #\     wWWWw
                          \ \-. (/. .\)
                          /\ /`\/\   /\
                          |\/   \_) (_|
                          `\.' ; ;    ;`\
                            `\;  ;    .  ;/\
                              `\;    ;  ;|  \
                               ;   .' '  ;  /
                               |_.'   ;  | /)
                               (     ''._;'`
                               (  .'  : |
                               | ,-'  .;|
                              _/___,_.:_\_
                             [I_I_I_I_I_I_]
                             | __________ |
                            _| ||_|__|_|| |_
                           /=--------------=\
```

---

## Amnesia
#### Electronic Arts - 1986

A full simulation of Manhattan from _110th Street_ south to _Battery Park_

* _4000_ locations.
* _650_ streets.
* Stores opened and closed at set times
* Street lights came on at night.
* People moved about the city in realistic patterns.

---

# Death of Infocom

_Activision_ promotes _Bruce Davis_ to CEO who was against the acquisition of Infocom from the beginning. He began putting policies in place that were damaging to the success of Infocom.

_David Crane_, Activision co-founder and programmer stated that:

> "_Bruce Davis’s_ biggest mistake was treating video games as commodities, rather than creative products.”

_[ Cifaldi, Frank (December 6, 2005). "Playing Catch-Up: 'A Boy And His Job: Activision's David Crane'". Gamasutra. Retrieved 2017-08-01.]_

Many Inform employee’s believed that he was willfully acting against them.

**Activision closed Infocom in 1989.**

---

# Infocom’s legacy

By the late 80’s early 90’s there was a growing online community of interactive fiction enthusiasts. 

Usenet news groups:
* [rec.arts.int-fiction](http://www.ifarchive.org/indexes/if-archiveXrec.arts.int-fiction.html)
* [rec.games.int-fiction](http://www.ifarchive.org/indexes/if-archiveXrec.games.int-fiction.html)

In 1987 a group of Infocom enthusiasts, the "**InfoTaskForce**" reverse engineered Infocom's Z-Code format and the Z-Machine virtual machine.

**Shortly afterwards a Z-Code interpreter written in C was released.**

---

## Modern (sort-of) development tools

### T.A.D.S. (Text Adventure Development System)

#### Michael J. Roberts - 1988

Initial release was shareware, by the early 90's it was the _dominate IF platform_

Tads Version 3, released in 2006, uses a C++ based syntax with many modern language features:

* Garbage collection
* UTF-8
* Structured exceptions, etc...

Compiler and interpreter ported to _DOS_, _Macintosh_ and _Unix_ platforms.

### The INFORM Design System
#### Graham Nelson - 1993

_INFORM 6_ was rewritten from first principles in 1996

* Procedural, OOP

_INFORM 7_ was released in 2006 featuring a natural language approach to writing

* Declarative, High-level DSL

---

### INFORM 6

```
Constant Story "Hello Deductible";
Constant Headline "^An Interactive Example^";

Object Kitchen "Kitchen";
Object Front_Door "Front Door";

 Object Living_Room "Living Room"
     with
         description "A comfortably furnished living room.",
         n_to Kitchen,
         s_to Front_Door,
     has light;

 Object -> Salesman "insurance salesman"
     with
         name 'insurance' 'salesman' 'man',
         description "An insurance salesman in a tacky polyester
               suit.  He seems eager to speak to you.",
         before [;
             Listen:
                 move Insurance_Paperwork to player;
                 "The salesman bores you with a discussion
                  of life insurance policies.  From his
                  briefcase he pulls some paperwork which he
                  hands to you.";
         ];
```

---

### INFORM 7

```
"Hello Deductible" by "I.F. Author"
The story headline is "An Interactive Example".
The Living Room is a room. "A comfortably furnished living room."
The Kitchen is north of the Living Room.
The Front Door is south of the Living Room.
The Front Door is a door. The Front Door is closed and locked.
The insurance salesman is a man in the Living Room. The description is "An insurance salesman in a tacky polyester suit. He seems eager to speak to you." Understand "man" as the insurance salesman.
```

---

# Notable People in IF

## Graham Nelson

* British mathematician and poet.
* A fellow in pure mathematics at St Anne's College, Oxford.
* Married to _Emily Short_
* Created the _INFORM_ design system.
* Authored one the first published essays of interactive fiction theory, "_The Craft of Adventure_".
* Is one of the few individuals celebrated for both _creative_ and _technical_ contributions.

> He is also one of the more _ornately literate_ creators of interactive fiction. ... And any player who manages to solve its problems will find untranslated Latin mottos and puzzles involving Proust and Lenin.

_[Rothstein, Edward (1998-04-06). "TECHNOLOGY: CONNECTIONS; In the intricacy of a text game, no object is superfluous, no formulation too strange.". New York Times. The New York Times Company.  Retrieved 2017-08-01.]_

---

## Emily Short

* Multi-award winning author with over _35 works to her name_.
* Married to _Graham Nelson_
* Has written the majority of the programming examples for the _INFORM 7 documentation_ as well as two full-length demo games to be released with INFORM
* Hosts a very popular [blog on the subject](emshort.wordpress.com)


## Andrew Plotkin, a.k.a. "Zarf"

* Like Nelson, acclaimed for both _artistic_ and _technical_ contributions.
* In an effort to surmount some of z-machines limitations he developed:
  1. Blorb archive format
  2. Glk I/O platform
  3.  Glulx virtual machine
* Holds records for most "**XYZZYs**" won in a single year (5) and most "**XYZZYs**" won in total (18)
* Was featured in J. Robinson Wheeler's IF entitled "_Being Andrew Plotkin_"

In 1997 Plotkin re-themed the social deduction game "_Mafia_" as "_Werewolf_". There have been numerous spin-offs to date.

---

```
                                            
                       +                     _||_
                      /^\----------][-------/ JL \
                    /     \      //__\\    | /__\ |
                  /         \    ||==||   |  |==|  |
               __/___________\ _ ||__|| _ |__|__|__|__
              ';===============,==========,==========;'
                \[]-[]-[]-[]-[]/-[]-[]-[]-|-[]-[]-[]/
                 |____________|-----------\_..--.._/
                 || |='--'=| ||^^_^^_^^_^^| = _   =|
                 || | .--. | ||===.---.===|._.__._.|
                 || | |__| | ||   |___|  =||| || |||
                 ||_|_|--|_|_|| = |---|   ||| || |||
                _/!!!!!!!!!!!!|  _|___|_- |||_||_|||
               ':""__""_"""__"| '-------' |'-'--'-'|
                 ||__________||=_  ___-  _| =  _ = |
                 ||----------||   .---.=  |._.__._.|
                 |||.-_---_-.||   |___|  =||| || |||
                         [_]||| = |---|   ||| || |||
                  ,- _~.    |||,,,|,,,|,,,||| || |||
                (' /|                  &&&&&'-'--'-'
               ((  ||   \\ \\ ,._-_  _-_,  _-_   _-_,     
               ((  ||   || ||  ||   ||_.  || \\ ||_.  
                ( / |   || ||  ||      || ||/      ||
                  -____- \\/\\  \\, ,-_-  \\,/  ,-_-  

```
---

## Curses
####  Graham Nelson - 1993

* First _non-test_ game written in INFORM
* One of the first published amateur IFs
* Introduced many player conveniences such as _inventory management_ and _world inspection_.

---

```

              __ \    |   |    \  |    \  |   ____|  __ __|
              |   |   |   |     \ |     \ |   __|       |   
              |   |   |   |   |\  |   |\  |   |         |   
              ____/   \___/  _| \_|  _| \_|  _____|    _|
                               __________
                      ________|          |________
                     |       /   ||||||   \       |
                     |     ,'              `.     |
                     |   ,'                  `.   |
                     | ,'   ||||||||||||||||   `. |
                     ,'  /____________________\  `.
                    /______________________________\
                   |                                |
                   |                                |
                   |                                |
                   |________________________________|
                     |____________________------__|

         ,----------------------------------------------------,
         | [][][][][]  [][][][][]  [][][][]  [][__]  [][][][] |
         |                                                    |
         |  [][][][][][][][][][][][][][_]    [][][]  [][][][] |
         |  [_][][][][][][][][][][][][][ |   [][][]  [][][][] |
         | [][_][][][][][][][][][][][][]||     []    [][][][] |
         | [__][][][][][][][][][][][][__]    [][][]  [][][]|| |
         |   [__][________________][__]              [__][]|| |
         `----------------------------------------------------'
```

---

## Dunnet
#### Ron Schnell - 1983, 1992

* Based on a game Schnell developed in 1982
* Name is derived from **Dun**geon + Arpa**net**
* First written in _MACLisp_ in '83, ported to _eLisp_ in '92
* Included in GNU Emacs since 1994
* _Dunnet_ was used as a benchmark for porting _Emacs Lisp_ to _Guile_ (GNU extension system)

> `emacs -batch -l dunnet`

---

```

      ___                                                         
     -   -_,            ,,                ,,                 |\   
    (  ~/||             ||                ||            _     \\  
    (  / ||  \\/\\  _-_ ||/\\  /'\\ ,._-_ ||/\\  _-_   < \,  / \\
     \/==||  || || ||   || || || ||  ||   || || || \\  /-|| || ||
     /_ _||  || || ||   || || || ||  ||   || || ||/   (( || || ||
    (  - \\, \\ \\ \\,/ \\ |/ \\,/   \\,  \\ |/ \\,/   \/\\  \\/  
                          _/                _/                    
                                  ___
                                .-'   `'.
                               /         \
                               |         ;
                               |\     /  |
                               |0) ~ (0) |
                               \    '--. \
                              /./;   ;, '.|
                     .---.__.' / |   |\   \
                   .'.''-._.-'`_./  /\ '.  \
                   | |  .' _.-' |  |\ \  \  '.
                    \ \/ .'  / /\  \ ) '. '-._)
                     \/ /   ( (  \  \( ( `=.__`~-.
                     / /\    '.'  `) )\ \ / / `"".`\
               , _.-'.'\ \    ) ) / /  ) ( (     / /
                `--~`   ) )  -'.-'.' .-'.''.'.  | (
                       (/`    ( (`          ) )  '-;
                        `      '-;         (-'


```

---

## Anchorhead
#### Michael S. Gentry - 1998

A Lovecraftian horror game leaning heavily the **Cthulhu Mythos**.
Most notably borrows from:

* The Shadow Over Innsmouth
* The Dunwich Horror
* The Music of Erich Zann
* The Festival

_["Interview: Mike Gentry". Game Couch. December 14, 2006.  Retrieved 2017-08-01.]_

Written in _INFORM 6_
Ported to _INFORM 7_ in 2006

Praise:

> "the most intelligent, polished and captivating piece of interactive fiction I have played to date."

_[Kulczycki, Gregory W. (September 17, 1999). "Anchorhead review". Brass Lantern.]_

> "masterful build-up of setting and mood unparalleled by almost every other game I have ever played," _calling the environment_ "oppressively real."

_[Short, Emily. "Aweighing an Anchorhead". IF-Review.]_

---

```
                     ,---.      .      .             
                     |  -'  ,-. |  ,-. |- ,-. ,-.    
                     |  ,-' ,-| |  ,-| |  |-' ,-|    
                     `---|  `-^ `' `-^ `' `-' `-^    
                      ,-.|      %%%
                      `-+'     =====
                              &%&%%%&
                              %& < <%   
                               &\__/
                                \ |____
                               .', ,  ()
                              / -.  _)|
                             |_(_.    |
                             '-'\  )  |
                                 )    |
                                /  .  ).
                              /    _. |
                             /'---':.-'|
                            (__.' /    /
                             \   ( /  /
                              \ /  _  |
                               \  |  '|
                               | . \  |
                               |(     |
                               |  \ \ |
                                \  )\ |
                               __)/ / \
                            --"--(_.Ooo'----             

```

---

## Galatea
#### Emily Short - 2000

Based upon the _Greek myth_ of **Galatea**.

* Took "Best of Show" in the 2000 _IF Art Show_
* Won a _XYZZY_ Award for Best Non-Player Character

The game takes place _entirely in one room_, with almost all interactions being focused on a converation with the statue.

---

```
                 +-+ +-+ +-+ +-+ +-+ +-+ +-+ +-+ +-+
                 |S| |l| |o| |u| |c| |h| |i| |n| |g|
                 +-+ +-+ +-+ +-+ +-+ +-+ +-+ +-+ +-+

         +-+ +-+ +-+ +-+ +-+ +-+ +-+   +-+ +-+ +-+ +-+ +-+ +-+
         |T| |o| |w| |a| |r| |d| |s|   |B| |e| |d| |l| |a| |m|
         +-+ +-+ +-+ +-+ +-+ +-+ +-+   +-+ +-+ +-+ +-+ +-+ +-+
          .
       .                           |~~             .
                                ___|___      .
                               ((((())))
           .                  (((((()))))         .
                            |-------------|
      +               +    I_I_I_I_I_I_I_I_I    +               +   
     (()             (()   |---------------|   (()             (()  
    |---|           |---|  ||-| |-| |-| |-||  |---|           |---|
   |-----|_________|-----|_|---------------|_|-----|_________|-----|
   |I_I_I_I_I_I_I_I_I_I_I|I_I_I_I_I_I_I_I_I_I|I_I_I_I_I_I_I_I_I_I_I|
   |------|-------|------|-------------------|------|-------|------|
   | |-|  ||-| |-||  |-| ||-| |-| |-| |-| |-|| |-|  ||-| |-||  |-| |
   |------|-------|------|-------------------|------|-------|------|
   | |_|  |  |_|  |  |_| |::::: ------- :::::| |_|  |  |_|  |  |_| |
   | |_|  |  |_|  |  |_| | |_| |_.-"-._| |_| | |_|  |  |_|  |  |_| |
   |------|-------|------| |_| | | | | | |_| |------|-------|------|
  |@@@@@@@@@@@@@@@@@@@@@@|-----|_|_|_|_|-----|@@@@@@@@@@@@@@@@@@@@@@|
                        @@@@/=============\@@@@
                               /       \
```

---

## Slouching Towards Bedlam
#### Daniel Ravipinto, Star Foster - 2003

A Steampunk/Victorian story set in London.

Arthors **Ravipinto** and **Foster** both lived and worked in _Philadelphia_.

* Took _first place_ in the 2003 _Interactive Fiction Competition_.
* Won _Best Game, Setting, Story, and Individual NPC XYZZYs_ in 2003

---

```
                                    _          
                |    _    _  _|_    |_)  o   _  
                |_  (_)  _>   |_    |    |  (_|
                                             _|

         ___
         ',_`""\        .---,
            \   :-""``/`    |
             `;'     //`\   /
             /   __     |   ('.
            |_ ./O)\     \  `) \
       .-=; `              "   /   `-.
      /o o \   ,_,           .        '.
      L._._;_.-'           .            `'-.
        `'-.`             '                 `'-
              '-._. -'                         '.
                 \                               `\
                  |    |                            ;   _.
                  \    |           |                |-.((
                   ;.  \           /    /           |-.`\)
                   | '. ;         /    |            |(_) )
                   |   \ \       /`    |            ;'--'
                    \   '.\    /`      |           /
                     |   /`|  ;        \          /
                     |  |  |  |-._      '.      .'
                     /  |  |  |__.`'---"_;'-.  '
                    //__/  /  |    .-'``     _.
                          //__/   //___.--''`
```

---

## Lost Pig
#### Admiral Jota - 2007

* Pronounced **HO-ta**
* Took first place in the 2007 _Interactive Fiction Competition_
* Won _best game, writing, individual non-player character, and individual player character_ in the 2007 _XYZZY_ awards.

Admiral Jota:
> I do have a real name, but I don't usually use it on the Internet. Too many weirdos out there.

_[http://grunk.org/, Retrieved 2017-08-01]_


---

```


             ______  ______   _____
            |  __  ||      | |     \ .---.-..--.--..-----.
            |  __  ||  --  | |  --  ||  _  ||  |  ||__ --|
            |______||______| |_____/ |___._||___  ||_____|
                                            |_____|
                               ,~-.
                              (  ' )-.          ,~'`-.
                           ,~' `  ' ) )       _(   _) )    
                          ( ( .--.===.--.    (  `    ' )
                           `.%%.;::|888.#`.   `-'`~~=~'
                           /%%/::::|8888\##\          
                          |%%/:::::|88888\##|        
                          |%%|:::::|88888|##|.,-.   
                          \%%|:::::|88888|##/    )_
                           \%\:::::|88888/#/ ( `'  )
                            \%\::::|8888/#/(  ,  -'`-.
        ____                 `%\:::|888/#'(  (     ') )
         `. ````.---...__      `\__|__/'   `~-~=--~~='
           \_    ;   \`.-```--..[VVVVV]             
           ,'_,-' _,-'           \|_|/-._          
           -'  ,-'               [XXX]   `-._     
            ,-'                  `"""'      ,`-.  
           '--.     _ _.._`-.  `-._        |   `_
            ;  ,' ' _  `._`._   `.      `,-''  `-.
             ,-'   \    `;.   `. ;`   `._  _/\___     `.
```

---

## 80 Days
#### Inkle - 2014

Based loosely on Jules Verne's "_Around the World in Eighty Days_"

Initially released on _iOS_ and _Android_ in 2014, later released for _Windows_ and _OSX_ in 2015

More of a _branching narrative_ than traditional _IF_.

Average novel word-count _80,000-100,000_. 80 days contains over **750,000 words**.

*  TIME's 2014 _Game of the Year_
*  Telegraph newspaper named it as "_one of the best novels of 2014_"
*  Lead writer Meg Jayanth, received a _UK Writer's Guild award_ for her work

> set an exciting bar for what mainstream interactive fiction could look like... without sacrificing sophistication and depth for accessibility

_["The Top 10 Game Developers of 2014". Gamesutra. Retrieved 2017-08-01]_

---

```

     .|'''.|                                                   .|.
     ||..  '    ...   ... ..    ....    ....  ... ..  .... ... |||
      ''|||.  .|  '|.  ||' '' .|   '' .|...||  ||' ''  '|.  |  '|'
    .     '|| ||   ||  ||     ||      ||       ||       '|.|    |  
    |'....|'   '|..|' .||.     '|...'  '|...' .||.       '|     .  
                                                      .. |     '|'
                                    ____              ''          
                                  .'* *.'
                               __/_*_*(_
                              / _______ \
                             _\_)/___\(_/_
                            / _((\- -/))_ \
                            \ \())(-)(()/ /
                             ' \(((()))/ '
                            / ' \)).))/ ' \
                           / _ \ - | - /_  \
                          (   ( .;''';. .'  )
                          _\"__ /    )\ __"/_
                            \/  \   ' /  \/
                             .'  '...' ' )
                              / /  |  \ \
                             / .   .   . \
                           /   /   |   \   \
                         .'   /    b    '.  '.
                     _.-'    /     Bb     '-. '-._
                 _.-'       |      BBb       '-.  '-.
                (___________\____.dBBBb.________)____)
```

---

## Sorcery! (1, 2, 3 & 4)
#### Inkle 2013

Initially a series of _gamebooks_ published by UK game developer **Steve Jackson** from _1983-85_.

Inkle re-implemented as a _branching narrative_ game with original art and extended content for _iOS_, _Android_, _OSX_ and _Windows_.

> a prime example of what can happen when traditional storytelling gets along with contemporary game design.

_["Sorcery! Review". IGN. Retrieved 2017-08-01.]_

---

## IF design tools

* [Inform](http://inform7.com/)
* [Tads](http://www.tads.org/)
* [Inklewriter](http://www.inklestudios.com/inklewriter/)


---

## IF Interpreters

* [Frotz](https://github.com/DavidGriffith/frotz/)
* [Zoom](http://www.logicalshift.co.uk/unix/zoom/)

_electron based:_

* [Parchment](https://github.com/curiousdannii/parchment)

---

# Resources

[Documentary on IF](http://www.getlamp.com/)

[The Interactive Fiction Database](http://ifdb.tads.org/)

[The Interactive Fiction Archive](http://www.ifarchive.org/)

[The Treaty of Babel](http://babel.ifarchive.org/)

[Emily Short's Blog](https://emshort.blog)

[Twisty Little Passages](https://mitpress.mit.edu/books/twisty-little-passages)

[Interactive Fiction Wiki](http://ifwiki.org/)

[Article on Colossal Cave Adventure](http://www.digitalhumanities.org/dhq/vol/001/2/000009/000009.html)

[The Digital Antiquarian](http://www.filfre.net/)

[Formums](http://www.intfiction.org/)

ASCII art:
* http://ascii.co.uk/art
* htt://www.chris.com/ascii/joan/www.geocities.com/SoHo/7373/index-3.html#home
