# api documentation for  [mocha (v3.2.0)](https://mochajs.org)  [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mocha.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mocha)
#### simple, flexible, fun test framework

[![NPM](https://nodei.co/npm/mocha.png?downloads=true)](https://www.npmjs.com/package/mocha)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mocha/build/screen-capture.buildNpmdoc.browser._2Fhome_2Ftravis_2Fbuild_2Fnpmdoc_2Fnode-npmdoc-mocha_2Ftmp_2Fbuild_2Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mocha/build..beta..travis-ci.org/apidoc.html)

![package-listing](https://npmdoc.github.io/node-npmdoc-mocha/build/screen-capture.npmPackageListing.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk",
        "email": "tj@vision-media.ca"
    },
    "bin": {
        "mocha": "./bin/mocha",
        "_mocha": "./bin/_mocha"
    },
    "browser": {
        "debug": "./lib/browser/debug.js",
        "events": "./lib/browser/events.js",
        "tty": "./lib/browser/tty.js",
        "./index.js": "./browser-entry.js",
        "fs": false,
        "glob": false,
        "path": false,
        "supports-color": false
    },
    "bugs": {
        "url": "https://github.com/mochajs/mocha/issues"
    },
    "contributors": [
        {
            "name": "aaroncrows",
            "url": "https://github.com/aaroncrows"
        },
        {
            "name": "Aaron Hamid",
            "email": "aaron@incsw.com",
            "url": "https://github.com/ahamid"
        },
        {
            "name": "Aaron Heckmann",
            "email": "aaron.heckmann+github@gmail.com",
            "url": "https://github.com/aheckmann"
        },
        {
            "name": "Adam Crabtree",
            "url": "CrabDude's alias"
        },
        {
            "name": "Adam Gruber",
            "url": "https://github.com/adamgruber"
        },
        {
            "name": "Adrian Ludwig",
            "url": "https://github.com/adrian-ludwig"
        },
        {
            "name": "Ainthe Kitchen",
            "email": "a.in.the.k@gmail.com",
            "url": "https://github.com/ainthek"
        },
        {
            "name": "ajaykodali",
            "url": "https://github.com/ajaykodali"
        },
        {
            "name": "Alex Early",
            "url": "https://github.com/aearly"
        },
        {
            "name": "Alex Pham",
            "email": "thedark1337@thedark1337.com",
            "url": "https://github.com/thedark1337"
        },
        {
            "name": "amsul",
            "url": "https://github.com/amsul"
        },
        {
            "name": "Andreas Brekken",
            "email": "andreas@brekken.com",
            "url": "https://github.com/abrkn"
        },
        {
            "name": "Andreas Lind",
            "email": "andreas@one.com",
            "url": "https://github.com/papandreou"
        },
        {
            "name": "Andrew Miller",
            "email": "vnikitin@live.com",
            "url": "https://github.com/vnikiti"
        },
        {
            "name": "Andrew Nesbitt",
            "email": "andrewnez@gmail.com",
            "url": "https://github.com/andrew"
        },
        {
            "name": "Andrey Popp",
            "email": "8mayday@gmail.com",
            "url": "https://github.com/andreypopp"
        },
        {
            "name": "Andrii Shumada",
            "email": "eagleeyes91@gmail.com",
            "url": "https://github.com/eagleeye"
        },
        {
            "name": "Anis Safine",
            "url": "https://github.com/anis"
        },
        {
            "name": "Arian Stolwijk",
            "email": "stolwijk.arian@gmail.com",
            "url": "https://github.com/arian"
        },
        {
            "name": "Ariel Mashraki",
            "email": "ariel@mashraki.co.il",
            "url": "https://github.com/a8m"
        },
        {
            "name": "Arnaud Brousseau",
            "url": "https://github.com/ArnaudBrousseau"
        },
        {
            "name": "Atsuya Takagi",
            "email": "atsuya.takagi@gmail.com",
            "url": "https://github.com/atsuya"
        },
        {
            "name": "Attila Domokos",
            "url": "https://github.com/adomokos"
        },
        {
            "name": "Austin Birch",
            "url": "https://github.com/austinbirch"
        },
        {
            "name": "Avi Vahl",
            "url": "https://github.com/AviVahl"
        },
        {
            "name": "Ben Bradley",
            "url": "https://github.com/ben-bradley"
        },
        {
            "name": "beneidel",
            "url": "https://github.com/beneidel"
        },
        {
            "name": "Benjie Gillam",
            "url": "https://github.com/benjie"
        },
        {
            "name": "Ben Noordhuis",
            "email": "info@bnoordhuis.nl",
            "url": "https://github.com/bnoordhuis"
        },
        {
            "name": "Benoit Larroque",
            "url": "https://github.com/zetaben"
        },
        {
            "name": "Benoît Zugmeyer",
            "url": "https://github.com/BenoitZugmeyer"
        },
        {
            "name": "Ben Vinegar",
            "url": "https://github.com/benvinegar"
        },
        {
            "name": "Berker Peksag",
            "email": "berker.peksag@gmail.com",
            "url": "https://github.com/berkerpeksag"
        },
        {
            "name": "Bjørge Næss",
            "url": "https://github.com/bjoerge"
        },
        {
            "name": "Brendan Nee",
            "email": "brendan@blinktag.com",
            "url": "https://github.com/brendannee"
        },
        {
            "name": "Brian Beck",
            "email": "exogen@gmail.com",
            "url": "https://github.com/exogen"
        },
        {
            "name": "Brian C",
            "email": "brian.m.carlson@gmail.com",
            "url": "https://github.com/brianc"
        },
        {
            "name": "Brian Lalor",
            "email": "blalor@bravo5.org",
            "url": "https://github.com/blalor"
        },
        {
            "name": "Brian Moore",
            "url": "https://github.com/bionicbrian"
        },
        {
            "name": "Bryan Donovan",
            "url": "https://github.com/BryanDonovan"
        },
        {
            "name": "Buck Doyle",
            "url": "https://github.com/backspace"
        },
        {
            "name": "C. Scott Ananian",
            "email": "cscott@cscott.net",
            "url": "https://github.com/cscott"
        },
        {
            "name": "Casey Foster",
            "url": "https://github.com/caseywebdev"
        },
        {
            "name": "Charles Lowell",
            "email": "cowboyd@frontside.io",
            "url": "https://github.com/cowboyd"
        },
        {
            "name": "Chris Buckley",
            "email": "chris@cmbuckley.co.uk",
            "url": "https://github.com/cmbuckley"
        },
        {
            "name": "Christopher Hiller",
            "email": "boneskull@boneskull.com",
            "url": "https://github.com/boneskull"
        },
        {
            "name": "Chris Wren",
            "email": "chriswrendev@gmail.com",
            "url": "https://github.com/ChrisWren"
        },
        {
            "name": "Clemens Stolle",
            "url": "https://github.com/klaemo"
        },
        {
            "name": "Connor Dunn",
            "url": "https://github.com/Connorhd"
        },
        {
            "name": "Corey Butler",
            "url": "https://github.com/coreybutler"
        },
        {
            "name": "Cory Thomas",
            "url": "https://github.com/dump247"
        },
        {
            "name": "cybertk",
            "url": "https://github.com/cybertk"
        },
        {
            "name": "Daniel Ericsson",
            "url": "https://github.com/monowerker"
        },
        {
            "name": "Daniel St. Jules",
            "email": "danielst.jules@gmail.com",
            "url": "https://github.com/danielstjules"
        },
        {
            "name": "Daniel Stockman",
            "email": "daniel.stockman@gmail.com",
            "url": "https://github.com/evocateur"
        },
        {
            "name": "Dave McKenna",
            "email": "davemckenna01@gmail.com",
            "url": "https://github.com/davemckenna01"
        },
        {
            "name": "David da Silva",
            "email": "yo@dasilvacont.in",
            "url": "https://github.com/dasilvacontin"
        },
        {
            "name": "David Henderson",
            "url": "https://github.com/dhendo"
        },
        {
            "name": "Denis Bardadym",
            "email": "bardadymchik@gmail.com",
            "url": "https://github.com/btd"
        },
        {
            "name": "Devin Weaver",
            "email": "suki@tritarget.org",
            "url": "https://github.com/sukima"
        },
        {
            "name": "Diogo Monteiro",
            "email": "diogo.gmt@gmail.com",
            "url": "https://github.com/diogogmt"
        },
        {
            "name": "Dmitry Shirokov",
            "email": "deadrunk@gmail.com",
            "url": "https://github.com/runk"
        },
        {
            "name": "Domenic Denicola",
            "email": "d@domenic.me",
            "url": "https://github.com/domenic"
        },
        {
            "name": "Dominic Barnes",
            "email": "dominic@dbarnes.info",
            "url": "https://github.com/dominicbarnes"
        },
        {
            "name": "domq",
            "url": "https://github.com/domq"
        },
        {
            "name": "Douglas Wilson",
            "email": "doug@somethingdoug.com",
            "url": "https://github.com/dougwilson"
        },
        {
            "name": "Duncan Beevers",
            "email": "duncan@dweebd.com",
            "url": "https://github.com/duncanbeevers"
        },
        {
            "name": "Duncan Wong",
            "url": "https://github.com/badunk"
        },
        {
            "name": "eiji.ienaga",
            "url": "https://github.com/haru01"
        },
        {
            "name": "Fabio Crisci",
            "email": "piuccio@gmail.com",
            "url": "https://github.com/piuccio"
        },
        {
            "name": "Fede Ramirez",
            "email": "i@2fd.me",
            "url": "https://github.com/2fd"
        },
        {
            "name": "Fedor Indutny",
            "email": "fedor@indutny.com",
            "url": "https://github.com/indutny"
        },
        {
            "name": "fengmk2",
            "email": "m@fengmk2.com",
            "url": "https://github.com/fengmk2"
        },
        {
            "name": "Florian Margaine",
            "email": "florian@margaine.com",
            "url": "https://github.com/ralt"
        },
        {
            "name": "Forbes Lindesay",
            "url": "https://github.com/ForbesLindesay"
        },
        {
            "name": "Frederico Silva",
            "url": "https://github.com/fredericosilva"
        },
        {
            "name": "Fredrik Enestad",
            "email": "fredrik.enestad@soundtrackyourbrand.com",
            "url": "https://github.com/fredr"
        },
        {
            "name": "Fredrik Lindin",
            "url": "https://github.com/Cowboy-coder"
        },
        {
            "name": "Gabriel Silk",
            "url": "https://github.com/gsilk"
        },
        {
            "name": "Gareth Aye",
            "email": "gareth.aye@gmail.com",
            "url": "https://github.com/gaye"
        },
        {
            "name": "Gavin Mogan",
            "email": "gavin@gavinmogan.com",
            "url": "https://github.com/halkeye"
        },
        {
            "name": "gigadude",
            "url": "https://github.com/gigadude"
        },
        {
            "name": "Giovanni Bassi",
            "url": "https://github.com/giggio"
        },
        {
            "name": "Glen Huang",
            "email": "curvedmark@gmail.com",
            "url": "https://github.com/curvedmark"
        },
        {
            "name": "Glen Mailer",
            "email": "glen@stainlessed.co.uk",
            "url": "https://github.com/glenjamin"
        },
        {
            "name": "Greg Perkins",
            "email": "gregperkins@alum.mit.edu",
            "url": "https://github.com/gregrperkins"
        },
        {
            "name": "Guillermo Rauch",
            "email": "rauchg@gmail.com",
            "url": "https://github.com/rauchg"
        },
        {
            "name": "Guy Arye",
            "url": "https://github.com/aryeguy"
        },
        {
            "name": "Gyandeep Singh",
            "email": "gyandeeps@gmail.com",
            "url": "https://github.com/gyandeeps"
        },
        {
            "name": "Harish",
            "email": "hyeluri@gmail.com",
            "url": "https://github.com/hyeluri"
        },
        {
            "name": "Harry Brundage",
            "email": "harry.brundage@gmail.com",
            "url": "https://github.com/airhorns"
        },
        {
            "name": "Ian Remmel",
            "email": "design@ianwremmel.com",
            "url": "https://github.com/ianwremmel"
        },
        {
            "name": "Ian Storm Taylor",
            "url": "https://github.com/ianstormtaylor"
        },
        {
            "name": "Ian Young",
            "email": "ian@iangreenleaf.com",
            "url": "https://github.com/iangreenleaf"
        },
        {
            "name": "Ivan",
            "url": "https://github.com/ivanstoyanov"
        },
        {
            "name": "Jaakko Salonen",
            "url": "https://github.com/jsalonen"
        },
        {
            "name": "Jacob Wejendorp",
            "email": "jacob@wejendorp.dk",
            "url": "https://github.com/wejendorp"
        },
        {
            "name": "Jake Craige",
            "url": "https://github.com/jakecraige"
        },
        {
            "name": "Jake Marsh",
            "url": "https://github.com/jakemmarsh"
        },
        {
            "name": "Jake Mc",
            "email": "jake.mc@icloud.com",
            "url": "https://github.com/startswithaj"
        },
        {
            "name": "Jake Verbaten",
            "email": "raynos2@gmail.com",
            "url": "https://github.com/Raynos"
        },
        {
            "name": "Jakub Nešetřil",
            "email": "jakub@apiary.io",
            "url": "https://github.com/zzen"
        },
        {
            "name": "James Bowes",
            "url": "https://github.com/jbowes"
        },
        {
            "name": "James Carr",
            "email": "james.r.carr@gmail.com",
            "url": "https://github.com/jamescarr"
        },
        {
            "name": "James G. Kim",
            "email": "jgkim@jayg.org",
            "url": "https://github.com/jgkim"
        },
        {
            "name": "James Lal",
            "email": "james@lightsofapollo.com",
            "url": "https://github.com/lightsofapollo"
        },
        {
            "name": "James Nylen",
            "email": "jnylen@gmail.com",
            "url": "https://github.com/nylen"
        },
        {
            "name": "Jason",
            "url": "https://github.com/jlai"
        },
        {
            "name": "Jason Barry",
            "email": "jay@jcbarry.com",
            "url": "https://github.com/JCBarry"
        },
        {
            "name": "Javier Aranda",
            "email": "javier.aranda.varo@gmail.com",
            "url": "https://github.com/javierav"
        },
        {
            "name": "jcreamer898",
            "url": "https://github.com/jcreamer898"
        },
        {
            "name": "Jean Ponchon",
            "url": "https://github.com/nopnop"
        },
        {
            "name": "Jeff Kunkle",
            "url": "https://github.com/kunklejr"
        },
        {
            "name": "Jeff Schilling",
            "email": "jeff@manicwave.com",
            "url": "https://github.com/jschilli"
        },
        {
            "name": "JeongHoon Byun",
            "email": "outsideris@gmail.com",
            "url": "aka Outsider"
        },
        {
            "name": "Jeremy Martin",
            "url": "https://github.com/jmar777"
        },
        {
            "name": "jimenglish81",
            "url": "https://github.com/jimenglish81"
        },
        {
            "name": "Jimmy Cuadra",
            "url": "https://github.com/jimmycuadra"
        },
        {
            "name": "jldailey",
            "url": "https://github.com/jldailey"
        },
        {
            "name": "jleyba",
            "url": "https://github.com/jleyba"
        },
        {
            "name": "Joey Cozza",
            "email": "joeycozza@gmail.com",
            "url": "https://github.com/joeycozza"
        },
        {
            "name": "Johnathon Sanders",
            "url": "https://github.com/outdooricon"
        },
        {
            "name": "John Doty",
            "email": "jrhdoty@gmail.com",
            "url": "https://github.com/jrhdoty"
        },
        {
            "name": "John Firebaugh",
            "email": "john.firebaugh@gmail.com",
            "url": "https://github.com/jfirebaugh"
        },
        {
            "name": "John Reeves",
            "url": "https://github.com/jonnyreeves"
        },
        {
            "name": "Jo Liss",
            "email": "joliss42@gmail.com",
            "url": "https://github.com/joliss"
        },
        {
            "name": "Jonas Dohse",
            "url": "https://github.com/dohse"
        },
        {
            "name": "Jonathan Kim",
            "email": "hello@jkimbo.co.uk",
            "url": "https://github.com/jkimbo"
        },
        {
            "name": "Jonathan Park",
            "email": "jonathan.daniel.park@gmail.com",
            "url": "https://github.com/park9140"
        },
        {
            "name": "jongleberry",
            "email": "me@jongleberry.com",
            "url": "https://github.com/jonathanong"
        },
        {
            "name": "Jordan Sexton",
            "email": "jordan@jordansexton.com",
            "url": "https://github.com/jordansexton"
        },
        {
            "name": "Joseph Spencer",
            "url": "https://github.com/jsdevel"
        },
        {
            "name": "Josh Lory",
            "url": "https://github.com/joshlory"
        },
        {
            "name": "Joshua Appelman",
            "email": "joshua@jbna.nl",
            "url": "https://github.com/jbnicolai"
        },
        {
            "name": "Joshua Krall",
            "email": "joshuakrall@pobox.com",
            "url": "https://github.com/jkrall"
        },
        {
            "name": "João Moreno",
            "url": "https://github.com/joaomoreno"
        },
        {
            "name": "João Paulo Bochi",
            "email": "jpbochi@gmail.com",
            "url": "https://github.com/jpbochi"
        },
        {
            "name": "jugglinmike",
            "url": "https://github.com/jugglinmike"
        },
        {
            "name": "Julien Wajsberg",
            "url": "https://github.com/julienw"
        },
        {
            "name": "Jussi Virtanen",
            "email": "contact@jvirtanen.org",
            "url": "https://github.com/jvirtanen"
        },
        {
            "name": "Justin DuJardin",
            "url": "https://github.com/justindujardin"
        },
        {
            "name": "Juzer Ali",
            "email": "juzerali@live.com",
            "url": "https://github.com/juzerali"
        },
        {
            "name": "Jérémie Astori",
            "url": "https://github.com/astorije"
        },
        {
            "name": "Katie Gengler",
            "url": "https://github.com/kategengler"
        },
        {
            "name": "Kazuhito Hokamura",
            "url": "https://github.com/hokaccha"
        },
        {
            "name": "Keith Cirkel",
            "url": "https://github.com/keithamus"
        },
        {
            "name": "Kent C. Dodds",
            "email": "kent+github@doddsfamily.us",
            "url": "https://github.com/kentcdodds"
        },
        {
            "name": "Kevin Burke",
            "email": "kev@inburke.com",
            "url": "https://github.com/kevinburke"
        },
        {
            "name": "Kevin Conway",
            "email": "kevinjacobconway@gmail.com",
            "url": "https://github.com/kevinconway"
        },
        {
            "name": "Kevin Kirsche",
            "email": "Kev.Kirsche@gmail.com",
            "url": "https://github.com/kkirsche"
        },
        {
            "name": "Kirill Korolyov",
            "email": "kirill.korolyov@gmail.com",
            "url": "https://github.com/Dremora"
        },
        {
            "name": "Koen Punt",
            "email": "mail@koen.pt",
            "url": "https://github.com/koenpunt"
        },
        {
            "name": "Konstantin Käfer",
            "email": "mail@kkaefer.com",
            "url": "https://github.com/kkaefer"
        },
        {
            "name": "Kris Rasmussen",
            "url": "https://github.com/krisr"
        },
        {
            "name": "Kyle Mitchell",
            "email": "kyle@kemitchell.com",
            "url": "https://github.com/kemitchell"
        },
        {
            "name": "lakmeer",
            "url": "https://github.com/lakmeer"
        },
        {
            "name": "Liam Newman",
            "email": "bitwiseman@gmail.com",
            "url": "https://github.com/bitwiseman"
        },
        {
            "name": "Linus Unnebäck",
            "email": "linus@folkdatorn.se",
            "url": "https://github.com/LinusU"
        },
        {
            "name": "Long Ho",
            "email": "holevietlong@gmail.com",
            "url": "https://github.com/longlho"
        },
        {
            "name": "László Bácsi",
            "email": "lackac@lackac.hu",
            "url": "https://github.com/lackac"
        },
        {
            "name": "Maciej Małecki",
            "email": "me@mmalecki.com",
            "url": "https://github.com/mmalecki"
        },
        {
            "name": "Mal Graty",
            "url": "https://github.com/mal"
        },
        {
            "name": "Marcello Bastéa-Forte",
            "email": "marcello@cellosoft.com",
            "url": "https://github.com/marcello3d"
        },
        {
            "name": "Marc Kuo",
            "email": "marc@routific.com",
            "url": "https://github.com/mck-"
        },
        {
            "name": "Mark Banner",
            "url": "https://github.com/Standard8"
        },
        {
            "name": "Matija Marohnić",
            "email": "matija.marohnic@gmail.com",
            "url": "https://github.com/silvenon"
        },
        {
            "name": "Matthew Shanley",
            "email": "matthewshanley@littlesecretsrecords.com",
            "url": "https://github.com/arkadyan"
        },
        {
            "name": "mattias-lw",
            "url": "https://github.com/mattias-lw"
        },
        {
            "name": "Matt Robenolt",
            "email": "m@robenolt.com",
            "url": "https://github.com/mattrobenolt"
        },
        {
            "name": "Matt Smith",
            "email": "matt@twobitfool.com",
            "url": "https://github.com/twobitfool"
        },
        {
            "name": "Max Goodman",
            "email": "c@chromako.de",
            "url": "https://github.com/chromakode"
        },
        {
            "name": "Maximilian Antoni",
            "email": "mail@maxantoni.de",
            "url": "https://github.com/mantoni"
        },
        {
            "name": "Merrick Christensen",
            "email": "merrick.christensen@gmail.com",
            "url": "https://github.com/iammerrick"
        },
        {
            "name": "michael-adsk",
            "url": "https://github.com/michael-adsk"
        },
        {
            "name": "Michael Demmer",
            "url": "https://github.com/demmer"
        },
        {
            "name": "Michael Jackson",
            "email": "mjijackson@gmail.com",
            "url": "https://github.com/mjackson"
        },
        {
            "name": "Michael Schoonmaker",
            "email": "michael.r.schoonmaker@gmail.com",
            "url": "https://github.com/Schoonology"
        },
        {
            "name": "Michal Charemza",
            "url": "https://github.com/michalc"
        },
        {
            "name": "Mike Olson",
            "url": "https://github.com/mwolson"
        },
        {
            "name": "Mislav Marohnić",
            "email": "mislav.marohnic@gmail.com",
            "url": "https://github.com/mislav"
        },
        {
            "name": "mrShturman",
            "url": "https://github.com/mrShturman"
        },
        {
            "name": "Nathan Alderson",
            "email": "nathan@nathanalderson.com",
            "url": "https://github.com/nathanalderson"
        },
        {
            "name": "Nathan Black",
            "email": "nathan@nathanblack.org",
            "url": "https://github.com/nathanboktae"
        },
        {
            "name": "Nathan Bowser",
            "email": "nbowser@gmail.com",
            "url": "https://github.com/nathanbowser"
        },
        {
            "name": "Nathan Houle",
            "email": "nathan+github@nathanhoule.com",
            "url": "https://github.com/ndhoule"
        },
        {
            "name": "Nathan Rajlich",
            "email": "nathan@tootallnate.net",
            "url": "https://github.com/TooTallNate"
        },
        {
            "name": "Nick Fitzgerald",
            "url": "https://github.com/fitzgen"
        },
        {
            "name": "noirlab",
            "url": "https://github.com/noirlab"
        },
        {
            "name": "Noshir Patel",
            "email": "nosh@blackpiano.com",
            "url": "https://github.com/noshir-patel"
        },
        {
            "name": "OlegTsyba",
            "email": "oleg.tsyba.ua@gmail.com",
            "url": "https://github.com/OlegTsyba"
        },
        {
            "name": "omar",
            "url": "https://github.com/omardelarosa"
        },
        {
            "name": "Panu Horsmalahti",
            "email": "panu.horsmalahti@iki.fi",
            "url": "https://github.com/panuhorsmalahti"
        },
        {
            "name": "Parker Moore",
            "email": "email@byparker.com",
            "url": "https://github.com/parkr"
        },
        {
            "name": "Paul Armstrong",
            "url": "https://github.com/paularmstrong"
        },
        {
            "name": "Paul Miller",
            "email": "paul+gh@paulmillr.com",
            "url": "https://github.com/paulmillr"
        },
        {
            "name": "Pavel Zubkou",
            "url": "https://github.com/irnc"
        },
        {
            "name": "Pete Hawkins",
            "url": "https://github.com/phawk"
        },
        {
            "name": "Phil Sung",
            "email": "philbert@gmail.com",
            "url": "https://github.com/psung"
        },
        {
            "name": "Prayag Verma",
            "email": "prayag.verma@gmail.com",
            "url": "https://github.com/pra85"
        },
        {
            "name": "qiu zuhui",
            "email": "qiuzuhui@gmail.com",
            "url": "https://github.com/qiuzuhui"
        },
        {
            "name": "Quang Van",
            "email": "quang@boldapps.io",
            "url": "https://github.com/quangv"
        },
        {
            "name": "Rauno",
            "url": "https://github.com/Rauno56"
        },
        {
            "name": "Refael Ackermann",
            "email": "me@refack.com",
            "url": "https://github.com/refack"
        },
        {
            "name": "Richard Dingwall",
            "email": "rdingwall@gmail.com",
            "url": "https://github.com/rdingwall"
        },
        {
            "name": "Richard Knop",
            "url": "https://github.com/RichardKnop"
        },
        {
            "name": "Rico Sta. Cruz",
            "email": "hi@ricostacruz.com",
            "url": "https://github.com/rstacruz"
        },
        {
            "name": "Robert Rossmann",
            "url": "https://github.com/Alaneor"
        },
        {
            "name": "Rob Wu",
            "email": "rob@robwu.nl",
            "url": "https://github.com/Rob--W"
        },
        {
            "name": "Romain",
            "url": "https://github.com/rprieto"
        },
        {
            "name": "Roman Neuhauser",
            "email": "rneuhauser@sigpipe.cz",
            "url": "https://github.com/roman-neuhauser"
        },
        {
            "name": "Roman Shtylman",
            "url": "https://github.com/defunctzombie"
        },
        {
            "name": "Russ Bradberry",
            "email": "devdazed@me.com",
            "url": "https://github.com/devdazed"
        },
        {
            "name": "Russell Munson",
            "url": "https://github.com/rmunson"
        },
        {
            "name": "Ryan",
            "email": "ryan.shaw@min.vc",
            "url": "https://github.com/ryan-shaw"
        },
        {
            "name": "Ryan Hubbard",
            "url": "https://github.com/ryedog"
        },
        {
            "name": "Ryunosuke Sato",
            "email": "tricknotes.rs@gmail.com",
            "url": "https://github.com/tricknotes"
        },
        {
            "name": "ryym",
            "url": "https://github.com/ryym"
        },
        {
            "name": "Salehen Shovon Rahman",
            "email": "sal@linux.com",
            "url": "https://github.com/shovon"
        },
        {
            "name": "Salvador de la Puente González",
            "email": "salva@unoyunodiez.com",
            "url": "https://github.com/delapuente"
        },
        {
            "name": "Sam Mussell",
            "url": "https://github.com/smussell"
        },
        {
            "name": "Samuel Goldszmidt",
            "email": "samuel.goldszmidt@gmail.com",
            "url": "https://github.com/ouhouhsami"
        },
        {
            "name": "Sasha Koss",
            "email": "kossnocorp@gmail.com",
            "url": "https://github.com/kossnocorp"
        },
        {
            "name": "Scott Santucci",
            "email": "ScottFreeCode@gmail.com",
            "url": "https://github.com/ScottFreeCode"
        },
        {
            "name": "Sean Lang",
            "email": "slang800@gmail.com",
            "url": "https://github.com/slang800"
        },
        {
            "name": "seb vincent",
            "email": "seb.vincent@gmail.com",
            "url": "https://github.com/sebv"
        },
        {
            "name": "Seiya Konno",
            "email": "nulltask@gmail.com",
            "url": "https://github.com/nulltask"
        },
        {
            "name": "Sergey Simonchik",
            "url": "https://github.com/segrey"
        },
        {
            "name": "Sergio Santoro",
            "url": "https://github.com/taueres"
        },
        {
            "name": "Shahar Soel",
            "url": "https://github.com/bd82"
        },
        {
            "name": "Shaine Hatch",
            "url": "https://github.com/shaine"
        },
        {
            "name": "Shiwei Wang",
            "url": "https://github.com/wsw0108"
        },
        {
            "name": "Simon Gaeremynck",
            "url": "https://github.com/simong"
        },
        {
            "name": "Simon Goumaz",
            "url": "https://github.com/sgoumaz"
        },
        {
            "name": "Sindre Sorhus",
            "email": "sindresorhus@gmail.com",
            "url": "https://github.com/sindresorhus"
        },
        {
            "name": "slientcloud",
            "email": "rjmuqiang@gmail.com",
            "url": "https://github.com/silentcloud"
        },
        {
            "name": "Sorin Iclanzan",
            "url": "https://github.com/iclanzan"
        },
        {
            "name": "Standa Opichal",
            "email": "opichals@gmail.com",
            "url": "https://github.com/opichals"
        },
        {
            "name": "Stephen Mathieson",
            "email": "me@stephenmathieson.com",
            "url": "https://github.com/stephenmathieson"
        },
        {
            "name": "Steve Mason",
            "url": "https://github.com/spmason"
        },
        {
            "name": "Stewart Taylor",
            "email": "stewart@taylore.net",
            "url": "https://github.com/Stewart-Taylor"
        },
        {
            "name": "Sune Simonsen",
            "email": "sune@we-knowhow.dk",
            "url": "https://github.com/sunesimonsen"
        },
        {
            "name": "Sylvain Faucherand",
            "url": "https://github.com/slyg"
        },
        {
            "name": "Takuya Nishigori",
            "email": "nishigori.tak@gmail.com",
            "url": "https://github.com/nishigori"
        },
        {
            "name": "Taylor Gautier",
            "url": "https://github.com/tsgautier"
        },
        {
            "name": "Teddy Zeenny",
            "url": "https://github.com/teddyzeenny"
        },
        {
            "name": "Thomas Grainger",
            "email": "https//@graingert.co.uk",
            "url": "https://github.com/graingert"
        },
        {
            "name": "Tim Ehat",
            "url": "https://github.com/timehat"
        },
        {
            "name": "Timothy Gu",
            "email": "timothygu99@gmail.com",
            "url": "https://github.com/TimothyGu"
        },
        {
            "name": "Timo Tijhof",
            "email": "krinklemail@gmail.com",
            "url": "https://github.com/Krinkle"
        },
        {
            "name": "Tingan Ho",
            "email": "tingan87@gmail.com",
            "url": "https://github.com/tinganho"
        },
        {
            "name": "TJ Holowaychuk",
            "email": "tj@vision-media.ca",
            "url": "https://github.com/tj"
        },
        {
            "name": "Tobias Bieniek",
            "email": "tobias.bieniek@gmail.com",
            "url": "https://github.com/Turbo87"
        },
        {
            "name": "Toby Ho",
            "email": "airportyh@gmail.com",
            "url": "https://github.com/airportyh"
        },
        {
            "name": "Todd Agulnick",
            "url": "https://github.com/tawdle"
        },
        {
            "name": "Tom Hughes",
            "url": "https://github.com/tomhughes"
        },
        {
            "name": "Tommy Montgomery",
            "url": "https://github.com/tmont"
        },
        {
            "name": "traleig1",
            "url": "https://github.com/traleig1"
        },
        {
            "name": "Travis Jeffery",
            "email": "tj@travisjeffery.com",
            "url": "https://github.com/travisjeffery"
        },
        {
            "name": "Tyson Tate",
            "email": "tyson@tysontate.com",
            "url": "https://github.com/tysontate"
        },
        {
            "name": "Valentin Agachi",
            "url": "https://github.com/avaly"
        },
        {
            "name": "Victor Costan",
            "email": "victor@costan.us",
            "url": "https://github.com/pwnall"
        },
        {
            "name": "Vladimir Chernis",
            "url": "https://github.com/vlazzle"
        },
        {
            "name": "Vlad Magdalin",
            "email": "vlad@webflow.com",
            "url": "https://github.com/callmevlad"
        },
        {
            "name": "Will Langstroth",
            "url": "https://github.com/wlangstroth"
        },
        {
            "name": "Wil Moore III",
            "email": "wil.moore@wilmoore.com",
            "url": "https://github.com/wilmoore"
        },
        {
            "name": "Xavier Antoviaque",
            "email": "xavier@opencraft.com",
            "url": "https://github.com/antoviaque"
        },
        {
            "name": "Xavier Damman",
            "email": "xdamman@gmail.com",
            "url": "https://github.com/xdamman"
        },
        {
            "name": "Yanis Wang",
            "email": "yanis.wang@gmail.com",
            "url": "https://github.com/yaniswang"
        },
        {
            "name": "yuitest",
            "email": "developer.yuitest+github@cjhat.net",
            "url": "https://github.com/yuitest"
        },
        {
            "name": "Zhiye Li",
            "email": "github@zhiye.li",
            "url": "https://github.com/zhiyelee"
        },
        {
            "name": "Zhouxuan Yang",
            "email": "fool2fish@gmail.com",
            "url": "https://github.com/fool2fish"
        },
        {
            "name": "Zsolt Takács",
            "email": "firstname at lastname dot cc",
            "url": "https://github.com/oker1"
        }
    ],
    "dependencies": {
        "browser-stdout": "1.3.0",
        "commander": "2.9.0",
        "debug": "2.2.0",
        "diff": "1.4.0",
        "escape-string-regexp": "1.0.5",
        "glob": "7.0.5",
        "growl": "1.9.2",
        "json3": "3.3.2",
        "lodash.create": "3.1.1",
        "mkdirp": "0.5.1",
        "supports-color": "3.1.2"
    },
    "description": "simple, flexible, fun test framework",
    "devDependencies": {
        "assert": "^1.4.1",
        "browserify": "^13.0.0",
        "coffee-script": "^1.10.0",
        "eslint": "^2.13.1",
        "eslint-config-semistandard": "^6.0.2",
        "eslint-config-standard": "^5.0.0",
        "eslint-plugin-promise": "^2.0.1",
        "eslint-plugin-standard": "1.3.2",
        "expect.js": "^0.3.1",
        "karma": "^1.1.0",
        "karma-browserify": "^5.0.5",
        "karma-chrome-launcher": "^2.0.0",
        "karma-expect": "^1.1.2",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^0.2.3",
        "karma-sauce-launcher": "^1.0.0",
        "karma-spec-reporter": "0.0.26",
        "os-name": "^2.0.1",
        "phantomjs": "1.9.8",
        "rimraf": "^2.5.2",
        "should": "^9.0.2",
        "through2": "^2.0.1",
        "watchify": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "7dc4f45e5088075171a68896814e6ae9eb7a85e3",
        "tarball": "https://registry.npmjs.org/mocha/-/mocha-3.2.0.tgz"
    },
    "engines": {
        "node": ">= 0.10.x",
        "npm": ">= 1.4.x"
    },
    "files": [
        "bin",
        "images",
        "lib",
        "index.js",
        "mocha.css",
        "mocha.js",
        "browser-entry.js",
        "LICENSE",
        "bower.json"
    ],
    "gitHead": "b51e36014d9c6db07aee3057579c35315ec4efd7",
    "homepage": "https://mochajs.org",
    "keywords": [
        "mocha",
        "test",
        "bdd",
        "tdd",
        "tap"
    ],
    "license": "MIT",
    "logo": "https://cldup.com/S9uQ-cOLYz.svg",
    "maintainers": [
        {
            "name": "boneskull",
            "email": "boneskull@boneskull.com"
        },
        {
            "name": "dasilvacontin",
            "email": "dasilvacontin@gmail.com"
        }
    ],
    "name": "mocha",
    "optionalDependencies": {},
    "readme": "ERROR: No README data found!",
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mochajs/mocha.git"
    },
    "scripts": {
        "test": "make test"
    },
    "version": "3.2.0"
}
```



# <a name="apidoc.tableOfContents"></a>[table of contents](#apidoc.tableOfContents)

#### [module mocha](#apidoc.module.mocha)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Context ()](#apidoc.element.mocha.Context)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Hook (title, fn)](#apidoc.element.mocha.Hook)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Runnable (title, fn)](#apidoc.element.mocha.Runnable)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Runner (suite, delay)](#apidoc.element.mocha.Runner)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Suite (title, parentContext)](#apidoc.element.mocha.Suite)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Test (title, fn)](#apidoc.element.mocha.Test)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.base (runner)](#apidoc.element.mocha.reporters.base)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.dot (runner)](#apidoc.element.mocha.reporters.dot)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.html (runner)](#apidoc.element.mocha.reporters.html)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.landing (runner)](#apidoc.element.mocha.reporters.landing)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.list (runner)](#apidoc.element.mocha.reporters.list)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.min (runner)](#apidoc.element.mocha.reporters.min)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.nyan (runner)](#apidoc.element.mocha.reporters.nyan)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.progress (runner, options)](#apidoc.element.mocha.reporters.progress)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.spec (runner)](#apidoc.element.mocha.reporters.spec)
1.  [function <span class="apidocSignatureSpan">mocha.</span>reporters.xunit (runner, options)](#apidoc.element.mocha.reporters.xunit)
1.  object <span class="apidocSignatureSpan">mocha.</span>Context.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>Hook.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>Runnable.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>Runner.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>Suite.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>Test.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>interfaces
1.  object <span class="apidocSignatureSpan">mocha.</span>reporters
1.  object <span class="apidocSignatureSpan">mocha.</span>reporters.base.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>reporters.html.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>reporters.nyan.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>reporters.xunit.prototype
1.  object <span class="apidocSignatureSpan">mocha.</span>utils

#### [module mocha.Context](#apidoc.module.mocha.Context)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Context ()](#apidoc.element.mocha.Context.Context)

#### [module mocha.Context.prototype](#apidoc.module.mocha.Context.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>enableTimeouts (enabled)](#apidoc.element.mocha.Context.prototype.enableTimeouts)
1.  [function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>inspect ()](#apidoc.element.mocha.Context.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>retries (n)](#apidoc.element.mocha.Context.prototype.retries)
1.  [function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>runnable (runnable)](#apidoc.element.mocha.Context.prototype.runnable)
1.  [function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>skip ()](#apidoc.element.mocha.Context.prototype.skip)
1.  [function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>slow (ms)](#apidoc.element.mocha.Context.prototype.slow)
1.  [function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>timeout (ms)](#apidoc.element.mocha.Context.prototype.timeout)

#### [module mocha.Hook](#apidoc.module.mocha.Hook)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Hook (title, fn)](#apidoc.element.mocha.Hook.Hook)
1.  [function <span class="apidocSignatureSpan">mocha.Hook.</span>super_ (title, fn)](#apidoc.element.mocha.Hook.super_)

#### [module mocha.Hook.prototype](#apidoc.module.mocha.Hook.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.Hook.prototype.</span>error (err)](#apidoc.element.mocha.Hook.prototype.error)

#### [module mocha.Runnable](#apidoc.module.mocha.Runnable)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Runnable (title, fn)](#apidoc.element.mocha.Runnable.Runnable)

#### [module mocha.Runnable.prototype](#apidoc.module.mocha.Runnable.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>clearTimeout ()](#apidoc.element.mocha.Runnable.prototype.clearTimeout)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>constructor (title, fn)](#apidoc.element.mocha.Runnable.prototype.constructor)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>currentRetry (n)](#apidoc.element.mocha.Runnable.prototype.currentRetry)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>enableTimeouts (enabled)](#apidoc.element.mocha.Runnable.prototype.enableTimeouts)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>fullTitle ()](#apidoc.element.mocha.Runnable.prototype.fullTitle)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>globals (globals)](#apidoc.element.mocha.Runnable.prototype.globals)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>inspect ()](#apidoc.element.mocha.Runnable.prototype.inspect)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>isPending ()](#apidoc.element.mocha.Runnable.prototype.isPending)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>resetTimeout ()](#apidoc.element.mocha.Runnable.prototype.resetTimeout)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>retries (n)](#apidoc.element.mocha.Runnable.prototype.retries)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>run (fn)](#apidoc.element.mocha.Runnable.prototype.run)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>skip ()](#apidoc.element.mocha.Runnable.prototype.skip)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>slow (ms)](#apidoc.element.mocha.Runnable.prototype.slow)
1.  [function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>timeout (ms)](#apidoc.element.mocha.Runnable.prototype.timeout)

#### [module mocha.Runner](#apidoc.module.mocha.Runner)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Runner (suite, delay)](#apidoc.element.mocha.Runner.Runner)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.</span>immediately (callback, arg1, arg2, arg3)](#apidoc.element.mocha.Runner.immediately)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.</span>super_ ()](#apidoc.element.mocha.Runner.super_)

#### [module mocha.Runner.prototype](#apidoc.module.mocha.Runner.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>abort ()](#apidoc.element.mocha.Runner.prototype.abort)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>checkGlobals (test)](#apidoc.element.mocha.Runner.prototype.checkGlobals)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>fail (test, err)](#apidoc.element.mocha.Runner.prototype.fail)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>failHook (hook, err)](#apidoc.element.mocha.Runner.prototype.failHook)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>globalProps ()](#apidoc.element.mocha.Runner.prototype.globalProps)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>globals (arr)](#apidoc.element.mocha.Runner.prototype.globals)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>grep (re, invert)](#apidoc.element.mocha.Runner.prototype.grep)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>grepTotal (suite)](#apidoc.element.mocha.Runner.prototype.grepTotal)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>hook (name, fn)](#apidoc.element.mocha.Runner.prototype.hook)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>hookDown (name, fn)](#apidoc.element.mocha.Runner.prototype.hookDown)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>hookUp (name, fn)](#apidoc.element.mocha.Runner.prototype.hookUp)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>hooks (name, suites, fn)](#apidoc.element.mocha.Runner.prototype.hooks)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>parents ()](#apidoc.element.mocha.Runner.prototype.parents)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>run (fn)](#apidoc.element.mocha.Runner.prototype.run)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>runSuite (suite, fn)](#apidoc.element.mocha.Runner.prototype.runSuite)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>runTest (fn)](#apidoc.element.mocha.Runner.prototype.runTest)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>runTests (suite, fn)](#apidoc.element.mocha.Runner.prototype.runTests)
1.  [function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>uncaught (err)](#apidoc.element.mocha.Runner.prototype.uncaught)

#### [module mocha.Suite](#apidoc.module.mocha.Suite)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Suite (title, parentContext)](#apidoc.element.mocha.Suite.Suite)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.</span>create (parent, title)](#apidoc.element.mocha.Suite.create)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.</span>super_ ()](#apidoc.element.mocha.Suite.super_)

#### [module mocha.Suite.prototype](#apidoc.module.mocha.Suite.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>addSuite (suite)](#apidoc.element.mocha.Suite.prototype.addSuite)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>addTest (test)](#apidoc.element.mocha.Suite.prototype.addTest)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>afterAll (title, fn)](#apidoc.element.mocha.Suite.prototype.afterAll)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>afterEach (title, fn)](#apidoc.element.mocha.Suite.prototype.afterEach)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>bail (bail)](#apidoc.element.mocha.Suite.prototype.bail)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>beforeAll (title, fn)](#apidoc.element.mocha.Suite.prototype.beforeAll)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>beforeEach (title, fn)](#apidoc.element.mocha.Suite.prototype.beforeEach)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>clone ()](#apidoc.element.mocha.Suite.prototype.clone)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>eachTest (fn)](#apidoc.element.mocha.Suite.prototype.eachTest)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>enableTimeouts (enabled)](#apidoc.element.mocha.Suite.prototype.enableTimeouts)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>fullTitle ()](#apidoc.element.mocha.Suite.prototype.fullTitle)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>isPending ()](#apidoc.element.mocha.Suite.prototype.isPending)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>retries (n)](#apidoc.element.mocha.Suite.prototype.retries)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>run ()](#apidoc.element.mocha.Suite.prototype.run)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>slow (ms)](#apidoc.element.mocha.Suite.prototype.slow)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>timeout (ms)](#apidoc.element.mocha.Suite.prototype.timeout)
1.  [function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>total ()](#apidoc.element.mocha.Suite.prototype.total)

#### [module mocha.Test](#apidoc.module.mocha.Test)
1.  [function <span class="apidocSignatureSpan">mocha.</span>Test (title, fn)](#apidoc.element.mocha.Test.Test)

#### [module mocha.Test.prototype](#apidoc.module.mocha.Test.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.Test.prototype.</span>clone ()](#apidoc.element.mocha.Test.prototype.clone)
1.  [function <span class="apidocSignatureSpan">mocha.Test.prototype.</span>constructor (title, fn)](#apidoc.element.mocha.Test.prototype.constructor)

#### [module mocha.interfaces](#apidoc.module.mocha.interfaces)
1.  [function <span class="apidocSignatureSpan">mocha.interfaces.</span>bdd (suite)](#apidoc.element.mocha.interfaces.bdd)
1.  [function <span class="apidocSignatureSpan">mocha.interfaces.</span>exports (suite)](#apidoc.element.mocha.interfaces.exports)
1.  [function <span class="apidocSignatureSpan">mocha.interfaces.</span>qunit (suite)](#apidoc.element.mocha.interfaces.qunit)
1.  [function <span class="apidocSignatureSpan">mocha.interfaces.</span>tdd (suite)](#apidoc.element.mocha.interfaces.tdd)

#### [module mocha.reporters](#apidoc.module.mocha.reporters)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>Base (runner)](#apidoc.element.mocha.reporters.Base)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>Doc (runner)](#apidoc.element.mocha.reporters.Doc)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>Dot (runner)](#apidoc.element.mocha.reporters.Dot)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>HTML (runner)](#apidoc.element.mocha.reporters.HTML)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>JSON (runner)](#apidoc.element.mocha.reporters.JSON)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>JSONStream (runner)](#apidoc.element.mocha.reporters.JSONStream)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>Landing (runner)](#apidoc.element.mocha.reporters.Landing)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>List (runner)](#apidoc.element.mocha.reporters.List)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>Markdown (runner)](#apidoc.element.mocha.reporters.Markdown)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>Min (runner)](#apidoc.element.mocha.reporters.Min)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>Nyan (runner)](#apidoc.element.mocha.reporters.Nyan)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>Progress (runner, options)](#apidoc.element.mocha.reporters.Progress)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>Spec (runner)](#apidoc.element.mocha.reporters.Spec)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>TAP (runner)](#apidoc.element.mocha.reporters.TAP)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>XUnit (runner, options)](#apidoc.element.mocha.reporters.XUnit)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>base (runner)](#apidoc.element.mocha.reporters.base)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>doc (runner)](#apidoc.element.mocha.reporters.doc)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>dot (runner)](#apidoc.element.mocha.reporters.dot)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>html (runner)](#apidoc.element.mocha.reporters.html)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>json (runner)](#apidoc.element.mocha.reporters.json)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>json-stream (runner)](#apidoc.element.mocha.reporters.json-stream)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>landing (runner)](#apidoc.element.mocha.reporters.landing)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>list (runner)](#apidoc.element.mocha.reporters.list)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>markdown (runner)](#apidoc.element.mocha.reporters.markdown)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>min (runner)](#apidoc.element.mocha.reporters.min)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>nyan (runner)](#apidoc.element.mocha.reporters.nyan)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>progress (runner, options)](#apidoc.element.mocha.reporters.progress)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>spec (runner)](#apidoc.element.mocha.reporters.spec)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>tap (runner)](#apidoc.element.mocha.reporters.tap)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>xunit (runner, options)](#apidoc.element.mocha.reporters.xunit)

#### [module mocha.reporters.base](#apidoc.module.mocha.reporters.base)
1.  boolean <span class="apidocSignatureSpan">mocha.reporters.base.</span>inlineDiffs
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>base (runner)](#apidoc.element.mocha.reporters.base.base)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.base.</span>color (type, str)](#apidoc.element.mocha.reporters.base.color)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.base.</span>list (failures)](#apidoc.element.mocha.reporters.base.list)
1.  object <span class="apidocSignatureSpan">mocha.reporters.base.</span>colors
1.  object <span class="apidocSignatureSpan">mocha.reporters.base.</span>cursor
1.  object <span class="apidocSignatureSpan">mocha.reporters.base.</span>symbols
1.  object <span class="apidocSignatureSpan">mocha.reporters.base.</span>useColors
1.  object <span class="apidocSignatureSpan">mocha.reporters.base.</span>window

#### [module mocha.reporters.base.prototype](#apidoc.module.mocha.reporters.base.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.base.prototype.</span>epilogue ()](#apidoc.element.mocha.reporters.base.prototype.epilogue)

#### [module mocha.reporters.dot](#apidoc.module.mocha.reporters.dot)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>dot (runner)](#apidoc.element.mocha.reporters.dot.dot)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.dot.</span>super_ (runner)](#apidoc.element.mocha.reporters.dot.super_)

#### [module mocha.reporters.html](#apidoc.module.mocha.reporters.html)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>html (runner)](#apidoc.element.mocha.reporters.html.html)

#### [module mocha.reporters.html.prototype](#apidoc.module.mocha.reporters.html.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.html.prototype.</span>addCodeToggle (el, contents)](#apidoc.element.mocha.reporters.html.prototype.addCodeToggle)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.html.prototype.</span>suiteURL (suite)](#apidoc.element.mocha.reporters.html.prototype.suiteURL)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.html.prototype.</span>testURL (test)](#apidoc.element.mocha.reporters.html.prototype.testURL)

#### [module mocha.reporters.landing](#apidoc.module.mocha.reporters.landing)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>landing (runner)](#apidoc.element.mocha.reporters.landing.landing)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.landing.</span>super_ (runner)](#apidoc.element.mocha.reporters.landing.super_)

#### [module mocha.reporters.list](#apidoc.module.mocha.reporters.list)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>list (runner)](#apidoc.element.mocha.reporters.list.list)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.list.</span>super_ (runner)](#apidoc.element.mocha.reporters.list.super_)

#### [module mocha.reporters.min](#apidoc.module.mocha.reporters.min)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>min (runner)](#apidoc.element.mocha.reporters.min.min)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.min.</span>super_ (runner)](#apidoc.element.mocha.reporters.min.super_)

#### [module mocha.reporters.nyan](#apidoc.module.mocha.reporters.nyan)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>nyan (runner)](#apidoc.element.mocha.reporters.nyan.nyan)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.</span>super_ (runner)](#apidoc.element.mocha.reporters.nyan.super_)

#### [module mocha.reporters.nyan.prototype](#apidoc.module.mocha.reporters.nyan.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>appendRainbow ()](#apidoc.element.mocha.reporters.nyan.prototype.appendRainbow)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>cursorDown (n)](#apidoc.element.mocha.reporters.nyan.prototype.cursorDown)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>cursorUp (n)](#apidoc.element.mocha.reporters.nyan.prototype.cursorUp)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>draw ()](#apidoc.element.mocha.reporters.nyan.prototype.draw)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>drawNyanCat ()](#apidoc.element.mocha.reporters.nyan.prototype.drawNyanCat)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>drawRainbow ()](#apidoc.element.mocha.reporters.nyan.prototype.drawRainbow)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>drawScoreboard ()](#apidoc.element.mocha.reporters.nyan.prototype.drawScoreboard)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>face ()](#apidoc.element.mocha.reporters.nyan.prototype.face)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>generateColors ()](#apidoc.element.mocha.reporters.nyan.prototype.generateColors)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>rainbowify (str)](#apidoc.element.mocha.reporters.nyan.prototype.rainbowify)

#### [module mocha.reporters.progress](#apidoc.module.mocha.reporters.progress)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>progress (runner, options)](#apidoc.element.mocha.reporters.progress.progress)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.progress.</span>super_ (runner)](#apidoc.element.mocha.reporters.progress.super_)

#### [module mocha.reporters.spec](#apidoc.module.mocha.reporters.spec)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>spec (runner)](#apidoc.element.mocha.reporters.spec.spec)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.spec.</span>super_ (runner)](#apidoc.element.mocha.reporters.spec.super_)

#### [module mocha.reporters.xunit](#apidoc.module.mocha.reporters.xunit)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.</span>xunit (runner, options)](#apidoc.element.mocha.reporters.xunit.xunit)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.xunit.</span>super_ (runner)](#apidoc.element.mocha.reporters.xunit.super_)

#### [module mocha.reporters.xunit.prototype](#apidoc.module.mocha.reporters.xunit.prototype)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.xunit.prototype.</span>done (failures, fn)](#apidoc.element.mocha.reporters.xunit.prototype.done)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.xunit.prototype.</span>test (test)](#apidoc.element.mocha.reporters.xunit.prototype.test)
1.  [function <span class="apidocSignatureSpan">mocha.reporters.xunit.prototype.</span>write (line)](#apidoc.element.mocha.reporters.xunit.prototype.write)

#### [module mocha.utils](#apidoc.module.mocha.utils)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>canonicalize (value, stack, typeHint)](#apidoc.element.mocha.utils.canonicalize)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>clean (str)](#apidoc.element.mocha.utils.clean)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>escape (html)](#apidoc.element.mocha.utils.escape)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>files (dir, ext, ret)](#apidoc.element.mocha.utils.files)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>filter (arr, fn)](#apidoc.element.mocha.utils.filter)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>forEach (arr, fn, scope)](#apidoc.element.mocha.utils.forEach)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>getError (err)](#apidoc.element.mocha.utils.getError)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>highlightTags (name)](#apidoc.element.mocha.utils.highlightTags)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>indexOf (arr, obj, start)](#apidoc.element.mocha.utils.indexOf)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>inherits (ctor, superCtor)](#apidoc.element.mocha.utils.inherits)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>isArray ()](#apidoc.element.mocha.utils.isArray)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>isBuffer (value)](#apidoc.element.mocha.utils.isBuffer)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>isPromise (value)](#apidoc.element.mocha.utils.isPromise)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>isString (obj)](#apidoc.element.mocha.utils.isString)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>keys ()](#apidoc.element.mocha.utils.keys)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>lookupFiles (path, extensions, recursive)](#apidoc.element.mocha.utils.lookupFiles)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>map (arr, fn, scope)](#apidoc.element.mocha.utils.map)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>noop ()](#apidoc.element.mocha.utils.noop)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>parseQuery (qs)](#apidoc.element.mocha.utils.parseQuery)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>reduce (arr, fn, val)](#apidoc.element.mocha.utils.reduce)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>slug (str)](#apidoc.element.mocha.utils.slug)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>some (arr, fn)](#apidoc.element.mocha.utils.some)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>stackTraceFilter ()](#apidoc.element.mocha.utils.stackTraceFilter)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>stringify (value)](#apidoc.element.mocha.utils.stringify)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>trim (str)](#apidoc.element.mocha.utils.trim)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>type (value)](#apidoc.element.mocha.utils.type)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>undefinedError ()](#apidoc.element.mocha.utils.undefinedError)
1.  [function <span class="apidocSignatureSpan">mocha.utils.</span>watch (files, fn)](#apidoc.element.mocha.utils.watch)



# <a name="apidoc.module.mocha"></a>[module mocha](#apidoc.module.mocha)

#### <a name="apidoc.element.mocha.Context"></a>[function <span class="apidocSignatureSpan">mocha.</span>Context ()](#apidoc.element.mocha.Context)
- description and source-code
```javascript
function Context() {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Hook"></a>[function <span class="apidocSignatureSpan">mocha.</span>Hook (title, fn)](#apidoc.element.mocha.Hook)
- description and source-code
```javascript
function Hook(title, fn) {
  Runnable.call(this, title, fn);
  this.type = 'hook';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable"></a>[function <span class="apidocSignatureSpan">mocha.</span>Runnable (title, fn)](#apidoc.element.mocha.Runnable)
- description and source-code
```javascript
function Runnable(title, fn) {
  this.title = title;
  this.fn = fn;
  this.body = (fn || '').toString();
  this.async = fn && fn.length;
  this.sync = !this.async;
  this._timeout = 2000;
  this._slow = 75;
  this._enableTimeouts = true;
  this.timedOut = false;
  this._trace = new Error('done() called multiple times');
  this._retries = -1;
  this._currentRetry = 0;
  this.pending = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner"></a>[function <span class="apidocSignatureSpan">mocha.</span>Runner (suite, delay)](#apidoc.element.mocha.Runner)
- description and source-code
```javascript
function Runner(suite, delay) {
  var self = this;
  this._globals = [];
  this._abort = false;
  this._delay = delay;
  this.suite = suite;
  this.started = false;
  this.total = suite.total();
  this.failures = 0;
  this.on('test end', function (test) {
    self.checkGlobals(test);
  });
  this.on('hook end', function (hook) {
    self.checkGlobals(hook);
  });
  this._defaultGrep = /.*/;
  this.grep(this._defaultGrep);
  this.globals(this.globalProps().concat(extraGlobals()));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite"></a>[function <span class="apidocSignatureSpan">mocha.</span>Suite (title, parentContext)](#apidoc.element.mocha.Suite)
- description and source-code
```javascript
function Suite(title, parentContext) {
  if (!utils.isString(title)) {
    throw new Error('Suite 'title' should be a "string" but "' + typeof title + '" was given instead.');
  }
  this.title = title;
  function Context () {}
  Context.prototype = parentContext;
  this.ctx = new Context();
  this.suites = [];
  this.tests = [];
  this.pending = false;
  this._beforeEach = [];
  this._beforeAll = [];
  this._afterEach = [];
  this._afterAll = [];
  this.root = !title;
  this._timeout = 2000;
  this._enableTimeouts = true;
  this._slow = 75;
  this._bail = false;
  this._retries = -1;
  this._onlyTests = [];
  this._onlySuites = [];
  this.delayed = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Test"></a>[function <span class="apidocSignatureSpan">mocha.</span>Test (title, fn)](#apidoc.element.mocha.Test)
- description and source-code
```javascript
function Test(title, fn) {
  if (!isString(title)) {
    throw new Error('Test 'title' should be a "string" but "' + typeof title + '" was given instead.');
  }
  Runnable.call(this, title, fn);
  this.pending = !fn;
  this.type = 'test';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.base"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.base (runner)](#apidoc.element.mocha.reporters.base)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.dot"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.dot (runner)](#apidoc.element.mocha.reporters.dot)
- description and source-code
```javascript
function Dot(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var n = -1;

  runner.on('start', function () {
    process.stdout.write('\n');
  });

  runner.on('pending', function () {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    process.stdout.write(color('pending', Base.symbols.comma));
  });

  runner.on('pass', function (test) {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    if (test.speed === 'slow') {
      process.stdout.write(color('bright yellow', Base.symbols.dot));
    } else {
      process.stdout.write(color(test.speed, Base.symbols.dot));
    }
  });

  runner.on('fail', function () {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    process.stdout.write(color('fail', Base.symbols.bang));
  });

  runner.on('end', function () {
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.html"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.html (runner)](#apidoc.element.mocha.reporters.html)
- description and source-code
```javascript
function HTML(runner) {
  Base.call(this, runner);

  var self = this;
  var stats = this.stats;
  var stat = fragment(statsTemplate);
  var items = stat.getElementsByTagName('li');
  var passes = items[1].getElementsByTagName('em')[0];
  var passesLink = items[1].getElementsByTagName('a')[0];
  var failures = items[2].getElementsByTagName('em')[0];
  var failuresLink = items[2].getElementsByTagName('a')[0];
  var duration = items[3].getElementsByTagName('em')[0];
  var canvas = stat.getElementsByTagName('canvas')[0];
  var report = fragment('<ul id="mocha-report"></ul>');
  var stack = [report];
  var progress;
  var ctx;
  var root = document.getElementById('mocha');

  if (canvas.getContext) {
    var ratio = window.devicePixelRatio || 1;
    canvas.style.width = canvas.width;
    canvas.style.height = canvas.height;
    canvas.width *= ratio;
    canvas.height *= ratio;
    ctx = canvas.getContext('2d');
    ctx.scale(ratio, ratio);
    progress = new Progress();
  }

  if (!root) {
    return error('#mocha div missing, add it to your document');
  }

  // pass toggle
  on(passesLink, 'click', function (evt) {
    evt.preventDefault();
    unhide();
    var name = (/pass/).test(report.className) ? '' : ' pass';
    report.className = report.className.replace(/fail|pass/g, '') + name;
    if (report.className.trim()) {
      hideSuitesWithout('test pass');
    }
  });

  // failure toggle
  on(failuresLink, 'click', function (evt) {
    evt.preventDefault();
    unhide();
    var name = (/fail/).test(report.className) ? '' : ' fail';
    report.className = report.className.replace(/fail|pass/g, '') + name;
    if (report.className.trim()) {
      hideSuitesWithout('test fail');
    }
  });

  root.appendChild(stat);
  root.appendChild(report);

  if (progress) {
    progress.size(40);
  }

  runner.on('suite', function (suite) {
    if (suite.root) {
      return;
    }

    // suite
    var url = self.suiteURL(suite);
    var el = fragment('<li class="suite"><h1><a href="%s">%s</a></h1></li>', url, escape(suite.title));

    // container
    stack[0].appendChild(el);
    stack.unshift(document.createElement('ul'));
    el.appendChild(stack[0]);
  });

  runner.on('suite end', function (suite) {
    if (suite.root) {
      updateStats();
      return;
    }
    stack.shift();
  });

  runner.on('pass', function (test) {
    var url = self.testURL(test);
    var markup = '<li class="test pass %e"><h2>%e<span class="duration">%ems</span> ' +
      '<a href="%s" class="replay">‣</a></h2></li>';
    var el = fragment(markup, test.speed, test.title, test.duration, url);
    self.addCodeToggle(el, test.body);
    appendToStack(el);
    updateStats();
  });

  runner.on('fail', function (test) {
    var el = fragment('<li class="test fail"><h2>%e <a href="%e" class="replay">‣</a></h2></li>',
      test.title, self.testURL(test));
    var stackString; // Note: Includes leading newline
    var message = test.err.toString();

    // <=IE7 stringifies to [Object Error]. Since it can be overloaded, we
    // check for the result of the stringifying.
    if (message === '[object Error]') {
      message = test.err.message;
    }

    if (test.err.stack) {
      var indexOfMessage = test.err.stack.indexOf(test.err.message);
      if (indexOfMessage === -1) {
        stackString = test.err.stack;
      } else {
        stackString = test.err.stack.substr(test.err.message.length + indexOfMessage);
      }
    } else if (test.err.sourceURL && test.err.line !== undefined) {
      // Safari doesn't give you a stack. Let's at least provide a source line.
      stackString = '\n(' + test.err.sourceURL + ':' + test.err.line + ')';
    }

    stackString = stackString || '';

    if (test.err.htmlMessage && stackString) {
      el.appendChild(fragment('<div class="html-error">%s\n<pre class="error">%e</pre></div>',
        test.err.htmlMessage, stackString));
    } else if (test.err.htmlMessage) {
      el.appendChild(fragment('<div class="html-error">%s</div>', test.err.htmlMessage));
    } else {
      el.appendChild(fragment('<pre class= ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.landing"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.landing (runner)](#apidoc.element.mocha.reporters.landing)
- description and source-code
```javascript
function Landing(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var total = runner.total;
  var stream = process.stdout;
  var plane = color('plane', '✈');
  var crashed = -1;
  var n = 0;

  function runway () {
    var buf = Array(width).join('-');
    return '  ' + color('runway', buf);
  }

  runner.on('start', function () {
    stream.write('\n\n\n  ');
    cursor.hide();
  });

  runner.on('test end', function (test) {
    // check if the plane crashed
    var col = crashed === -1 ? width * ++n / total | 0 : crashed;

    // show the crash
    if (test.state === 'failed') {
      plane = color('plane crash', '✈');
      crashed = col;
    }

    // render landing strip
    stream.write('\u001b[' + (width + 1) + 'D\u001b[2A');
    stream.write(runway());
    stream.write('\n  ');
    stream.write(color('runway', Array(col).join('⋅')));
    stream.write(plane);
    stream.write(color('runway', Array(width - col).join('⋅') + '\n'));
    stream.write(runway());
    stream.write('\u001b[0m');
  });

  runner.on('end', function () {
    cursor.show();
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.list"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.list (runner)](#apidoc.element.mocha.reporters.list)
- description and source-code
```javascript
function List(runner) {
  Base.call(this, runner);

  var self = this;
  var n = 0;

  runner.on('start', function () {
    console.log();
  });

  runner.on('test', function (test) {
    process.stdout.write(color('pass', '    ' + test.fullTitle() + ': '));
  });

  runner.on('pending', function (test) {
    var fmt = color('checkmark', '  -') +
      color('pending', ' %s');
    console.log(fmt, test.fullTitle());
  });

  runner.on('pass', function (test) {
    var fmt = color('checkmark', '  ' + Base.symbols.ok) +
      color('pass', ' %s: ') +
      color(test.speed, '%dms');
    cursor.CR();
    console.log(fmt, test.fullTitle(), test.duration);
  });

  runner.on('fail', function (test) {
    cursor.CR();
    console.log(color('fail', '  %d) %s'), ++n, test.fullTitle());
  });

  runner.on('end', self.epilogue.bind(self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.min"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.min (runner)](#apidoc.element.mocha.reporters.min)
- description and source-code
```javascript
function Min(runner) {
  Base.call(this, runner);

  runner.on('start', function () {
    // clear screen
    process.stdout.write('\u001b[2J');
    // set cursor position
    process.stdout.write('\u001b[1;3H');
  });

  runner.on('end', this.epilogue.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.nyan (runner)](#apidoc.element.mocha.reporters.nyan)
- description and source-code
```javascript
function NyanCat(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var nyanCatWidth = this.nyanCatWidth = 11;

  this.colorIndex = 0;
  this.numberOfLines = 4;
  this.rainbowColors = self.generateColors();
  this.scoreboardWidth = 5;
  this.tick = 0;
  this.trajectories = [[], [], [], []];
  this.trajectoryWidthMax = (width - nyanCatWidth);

  runner.on('start', function () {
    Base.cursor.hide();
    self.draw();
  });

  runner.on('pending', function () {
    self.draw();
  });

  runner.on('pass', function () {
    self.draw();
  });

  runner.on('fail', function () {
    self.draw();
  });

  runner.on('end', function () {
    Base.cursor.show();
    for (var i = 0; i < self.numberOfLines; i++) {
      write('\n');
    }
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.progress"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.progress (runner, options)](#apidoc.element.mocha.reporters.progress)
- description and source-code
```javascript
function Progress(runner, options) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.50 | 0;
  var total = runner.total;
  var complete = 0;
  var lastN = -1;

  // default chars
  options = options || {};
  options.open = options.open || '[';
  options.complete = options.complete || '▬';
  options.incomplete = options.incomplete || Base.symbols.dot;
  options.close = options.close || ']';
  options.verbose = false;

  // tests started
  runner.on('start', function () {
    console.log();
    cursor.hide();
  });

  // tests complete
  runner.on('test end', function () {
    complete++;

    var percent = complete / total;
    var n = width * percent | 0;
    var i = width - n;

    if (n === lastN && !options.verbose) {
      // Don't re-render the line if it hasn't changed
      return;
    }
    lastN = n;

    cursor.CR();
    process.stdout.write('\u001b[J');
    process.stdout.write(color('progress', '  ' + options.open));
    process.stdout.write(Array(n).join(options.complete));
    process.stdout.write(Array(i).join(options.incomplete));
    process.stdout.write(color('progress', options.close));
    if (options.verbose) {
      process.stdout.write(color('progress', ' ' + complete + ' of ' + total));
    }
  });

  // tests are complete, output some stats
  // and the failures if any
  runner.on('end', function () {
    cursor.show();
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.spec"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.spec (runner)](#apidoc.element.mocha.reporters.spec)
- description and source-code
```javascript
function Spec(runner) {
  Base.call(this, runner);

  var self = this;
  var indents = 0;
  var n = 0;

  function indent () {
    return Array(indents).join('  ');
  }

  runner.on('start', function () {
    console.log();
  });

  runner.on('suite', function (suite) {
    ++indents;
    console.log(color('suite', '%s%s'), indent(), suite.title);
  });

  runner.on('suite end', function () {
    --indents;
    if (indents === 1) {
      console.log();
    }
  });

  runner.on('pending', function (test) {
    var fmt = indent() + color('pending', '  - %s');
    console.log(fmt, test.title);
  });

  runner.on('pass', function (test) {
    var fmt;
    if (test.speed === 'fast') {
      fmt = indent() +
        color('checkmark', '  ' + Base.symbols.ok) +
        color('pass', ' %s');
      console.log(fmt, test.title);
    } else {
      fmt = indent() +
        color('checkmark', '  ' + Base.symbols.ok) +
        color('pass', ' %s') +
        color(test.speed, ' (%dms)');
      console.log(fmt, test.title, test.duration);
    }
  });

  runner.on('fail', function (test) {
    console.log(indent() + color('fail', '  %d) %s'), ++n, test.title);
  });

  runner.on('end', self.epilogue.bind(self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.xunit"></a>[function <span class="apidocSignatureSpan">mocha.</span>reporters.xunit (runner, options)](#apidoc.element.mocha.reporters.xunit)
- description and source-code
```javascript
function XUnit(runner, options) {
  Base.call(this, runner);

  var stats = this.stats;
  var tests = [];
  var self = this;

  if (options && options.reporterOptions && options.reporterOptions.output) {
    if (!fs.createWriteStream) {
      throw new Error('file output not supported in browser');
    }
    mkdirp.sync(path.dirname(options.reporterOptions.output));
    self.fileStream = fs.createWriteStream(options.reporterOptions.output);
  }

  runner.on('pending', function (test) {
    tests.push(test);
  });

  runner.on('pass', function (test) {
    tests.push(test);
  });

  runner.on('fail', function (test) {
    tests.push(test);
  });

  runner.on('end', function () {
    self.write(tag('testsuite', {
      name: 'Mocha Tests',
      tests: stats.tests,
      failures: stats.failures,
      errors: stats.failures,
      skipped: stats.tests - stats.failures - stats.passes,
      timestamp: (new Date()).toUTCString(),
      time: (stats.duration / 1000) || 0
    }, false));

    tests.forEach(function (t) {
      self.test(t);
    });

    self.write('</testsuite>');
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Context"></a>[module mocha.Context](#apidoc.module.mocha.Context)

#### <a name="apidoc.element.mocha.Context.Context"></a>[function <span class="apidocSignatureSpan">mocha.</span>Context ()](#apidoc.element.mocha.Context.Context)
- description and source-code
```javascript
function Context() {}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Context.prototype"></a>[module mocha.Context.prototype](#apidoc.module.mocha.Context.prototype)

#### <a name="apidoc.element.mocha.Context.prototype.enableTimeouts"></a>[function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>enableTimeouts (enabled)](#apidoc.element.mocha.Context.prototype.enableTimeouts)
- description and source-code
```javascript
enableTimeouts = function (enabled) {
  this.runnable().enableTimeouts(enabled);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Context.prototype.inspect"></a>[function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>inspect ()](#apidoc.element.mocha.Context.prototype.inspect)
- description and source-code
```javascript
inspect = function () {
  return JSON.stringify(this, function (key, val) {
    return key === 'runnable' || key === 'test' ? undefined : val;
  }, 2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Context.prototype.retries"></a>[function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>retries (n)](#apidoc.element.mocha.Context.prototype.retries)
- description and source-code
```javascript
retries = function (n) {
  if (!arguments.length) {
    return this.runnable().retries();
  }
  this.runnable().retries(n);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Context.prototype.runnable"></a>[function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>runnable (runnable)](#apidoc.element.mocha.Context.prototype.runnable)
- description and source-code
```javascript
runnable = function (runnable) {
  if (!arguments.length) {
    return this._runnable;
  }
  this.test = this._runnable = runnable;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Context.prototype.skip"></a>[function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>skip ()](#apidoc.element.mocha.Context.prototype.skip)
- description and source-code
```javascript
skip = function () {
  this.runnable().skip();
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Context.prototype.slow"></a>[function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>slow (ms)](#apidoc.element.mocha.Context.prototype.slow)
- description and source-code
```javascript
slow = function (ms) {
  this.runnable().slow(ms);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Context.prototype.timeout"></a>[function <span class="apidocSignatureSpan">mocha.Context.prototype.</span>timeout (ms)](#apidoc.element.mocha.Context.prototype.timeout)
- description and source-code
```javascript
timeout = function (ms) {
  if (!arguments.length) {
    return this.runnable().timeout();
  }
  this.runnable().timeout(ms);
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Hook"></a>[module mocha.Hook](#apidoc.module.mocha.Hook)

#### <a name="apidoc.element.mocha.Hook.Hook"></a>[function <span class="apidocSignatureSpan">mocha.</span>Hook (title, fn)](#apidoc.element.mocha.Hook.Hook)
- description and source-code
```javascript
function Hook(title, fn) {
  Runnable.call(this, title, fn);
  this.type = 'hook';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Hook.super_"></a>[function <span class="apidocSignatureSpan">mocha.Hook.</span>super_ (title, fn)](#apidoc.element.mocha.Hook.super_)
- description and source-code
```javascript
function Runnable(title, fn) {
  this.title = title;
  this.fn = fn;
  this.body = (fn || '').toString();
  this.async = fn && fn.length;
  this.sync = !this.async;
  this._timeout = 2000;
  this._slow = 75;
  this._enableTimeouts = true;
  this.timedOut = false;
  this._trace = new Error('done() called multiple times');
  this._retries = -1;
  this._currentRetry = 0;
  this.pending = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Hook.prototype"></a>[module mocha.Hook.prototype](#apidoc.module.mocha.Hook.prototype)

#### <a name="apidoc.element.mocha.Hook.prototype.error"></a>[function <span class="apidocSignatureSpan">mocha.Hook.prototype.</span>error (err)](#apidoc.element.mocha.Hook.prototype.error)
- description and source-code
```javascript
error = function (err) {
  if (!arguments.length) {
    err = this._error;
    this._error = null;
    return err;
  }

  this._error = err;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Runnable"></a>[module mocha.Runnable](#apidoc.module.mocha.Runnable)

#### <a name="apidoc.element.mocha.Runnable.Runnable"></a>[function <span class="apidocSignatureSpan">mocha.</span>Runnable (title, fn)](#apidoc.element.mocha.Runnable.Runnable)
- description and source-code
```javascript
function Runnable(title, fn) {
  this.title = title;
  this.fn = fn;
  this.body = (fn || '').toString();
  this.async = fn && fn.length;
  this.sync = !this.async;
  this._timeout = 2000;
  this._slow = 75;
  this._enableTimeouts = true;
  this.timedOut = false;
  this._trace = new Error('done() called multiple times');
  this._retries = -1;
  this._currentRetry = 0;
  this.pending = false;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Runnable.prototype"></a>[module mocha.Runnable.prototype](#apidoc.module.mocha.Runnable.prototype)

#### <a name="apidoc.element.mocha.Runnable.prototype.clearTimeout"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>clearTimeout ()](#apidoc.element.mocha.Runnable.prototype.clearTimeout)
- description and source-code
```javascript
clearTimeout = function () {
  clearTimeout(this.timer);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.constructor"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>constructor (title, fn)](#apidoc.element.mocha.Runnable.prototype.constructor)
- description and source-code
```javascript
function Runnable(title, fn) {
  this.title = title;
  this.fn = fn;
  this.body = (fn || '').toString();
  this.async = fn && fn.length;
  this.sync = !this.async;
  this._timeout = 2000;
  this._slow = 75;
  this._enableTimeouts = true;
  this.timedOut = false;
  this._trace = new Error('done() called multiple times');
  this._retries = -1;
  this._currentRetry = 0;
  this.pending = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.currentRetry"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>currentRetry (n)](#apidoc.element.mocha.Runnable.prototype.currentRetry)
- description and source-code
```javascript
currentRetry = function (n) {
  if (!arguments.length) {
    return this._currentRetry;
  }
  this._currentRetry = n;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.enableTimeouts"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>enableTimeouts (enabled)](#apidoc.element.mocha.Runnable.prototype.enableTimeouts)
- description and source-code
```javascript
enableTimeouts = function (enabled) {
  if (!arguments.length) {
    return this._enableTimeouts;
  }
  debug('enableTimeouts %s', enabled);
  this._enableTimeouts = enabled;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.fullTitle"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>fullTitle ()](#apidoc.element.mocha.Runnable.prototype.fullTitle)
- description and source-code
```javascript
fullTitle = function () {
  return this.parent.fullTitle() + ' ' + this.title;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.globals"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>globals (globals)](#apidoc.element.mocha.Runnable.prototype.globals)
- description and source-code
```javascript
globals = function (globals) {
  if (!arguments.length) {
    return this._allowedGlobals;
  }
  this._allowedGlobals = globals;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.inspect"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>inspect ()](#apidoc.element.mocha.Runnable.prototype.inspect)
- description and source-code
```javascript
inspect = function () {
  return JSON.stringify(this, function (key, val) {
    if (key[0] === '_') {
      return;
    }
    if (key === 'parent') {
      return '#<Suite>';
    }
    if (key === 'ctx') {
      return '#<Context>';
    }
    return val;
  }, 2);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.isPending"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>isPending ()](#apidoc.element.mocha.Runnable.prototype.isPending)
- description and source-code
```javascript
isPending = function () {
  return this.pending || (this.parent && this.parent.isPending());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.resetTimeout"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>resetTimeout ()](#apidoc.element.mocha.Runnable.prototype.resetTimeout)
- description and source-code
```javascript
resetTimeout = function () {
  var self = this;
  var ms = this.timeout() || 1e9;

  if (!this._enableTimeouts) {
    return;
  }
  this.clearTimeout();
  this.timer = setTimeout(function () {
    if (!self._enableTimeouts) {
      return;
    }
    self.callback(new Error('Timeout of ' + ms +
      'ms exceeded. For async tests and hooks, ensure "done()" is called; if returning a Promise, ensure it resolves.'));
    self.timedOut = true;
  }, ms);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.retries"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>retries (n)](#apidoc.element.mocha.Runnable.prototype.retries)
- description and source-code
```javascript
retries = function (n) {
  if (!arguments.length) {
    return this._retries;
  }
  this._retries = n;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.run"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>run (fn)](#apidoc.element.mocha.Runnable.prototype.run)
- description and source-code
```javascript
run = function (fn) {
  var self = this;
  var start = new Date();
  var ctx = this.ctx;
  var finished;
  var emitted;

  // Sometimes the ctx exists, but it is not runnable
  if (ctx && ctx.runnable) {
    ctx.runnable(this);
  }

  // called multiple times
  function multiple (err) {
    if (emitted) {
      return;
    }
    emitted = true;
    self.emit('error', err || new Error('done() called multiple times; stacktrace may be inaccurate'));
  }

  // finished
  function done (err) {
    var ms = self.timeout();
    if (self.timedOut) {
      return;
    }
    if (finished) {
      return multiple(err || self._trace);
    }

    self.clearTimeout();
    self.duration = new Date() - start;
    finished = true;
    if (!err && self.duration > ms && self._enableTimeouts) {
      err = new Error('Timeout of ' + ms +
      'ms exceeded. For async tests and hooks, ensure "done()" is called; if returning a Promise, ensure it resolves.');
    }
    fn(err);
  }

  // for .resetTimeout()
  this.callback = done;

  // explicit async with 'done' argument
  if (this.async) {
    this.resetTimeout();

    // allows skip() to be used in an explicit async context
    this.skip = function asyncSkip () {
      done(new Pending('async skip call'));
      // halt execution.  the Runnable will be marked pending
      // by the previous call, and the uncaught handler will ignore
      // the failure.
      throw new Pending('async skip; aborting execution');
    };

    if (this.allowUncaught) {
      return callFnAsync(this.fn);
    }
    try {
      callFnAsync(this.fn);
    } catch (err) {
      emitted = true;
      done(utils.getError(err));
    }
    return;
  }

  if (this.allowUncaught) {
    callFn(this.fn);
    done();
    return;
  }

  // sync or promise-returning
  try {
    if (this.isPending()) {
      done();
    } else {
      callFn(this.fn);
    }
  } catch (err) {
    emitted = true;
    done(utils.getError(err));
  }

  function callFn (fn) {
    var result = fn.call(ctx);
    if (result && typeof result.then === 'function') {
      self.resetTimeout();
      result
        .then(function () {
          done();
          // Return null so libraries like bluebird do not warn about
          // subsequently constructed Promises.
          return null;
        },
        function (reason) {
          done(reason || new Error('Promise rejected with no or falsy reason'));
        });
    } else {
      if (self.asyncOnly) {
        return done(new Error('--async-only option in use without declaring 'done()' or returning a promise'));
      }

      done();
    }
  }

  function callFnAsync (fn) {
    var result = fn.call(ctx, function (err) {
      if (err instanceof Error || toString.call(err) === '[object Error]') {
        return done(err);
      }
      if (err) {
        if (Object.prototype.toString.call(err) === '[object Object]') {
          return done(new Error('done() invoked with non-Error: ' +
            JSON.stringify(err)));
        }
        return done(new Error('done() invoked with non-Error: ' + err));
      }
      if (result && utils.isPromise(result)) {
        return done(new Error('Resolution method is overspecified. Specify a callback *or* return a Promise; not both.'));
      }

      done();
    });
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.skip"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>skip ()](#apidoc.element.mocha.Runnable.prototype.skip)
- description and source-code
```javascript
skip = function () {
  throw new Pending('sync skip');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.slow"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>slow (ms)](#apidoc.element.mocha.Runnable.prototype.slow)
- description and source-code
```javascript
slow = function (ms) {
  if (typeof ms === 'undefined') {
    return this._slow;
  }
  if (typeof ms === 'string') {
    ms = milliseconds(ms);
  }
  debug('timeout %d', ms);
  this._slow = ms;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runnable.prototype.timeout"></a>[function <span class="apidocSignatureSpan">mocha.Runnable.prototype.</span>timeout (ms)](#apidoc.element.mocha.Runnable.prototype.timeout)
- description and source-code
```javascript
timeout = function (ms) {
  if (!arguments.length) {
    return this._timeout;
  }
  // see #1652 for reasoning
  if (ms === 0 || ms > Math.pow(2, 31)) {
    this._enableTimeouts = false;
  }
  if (typeof ms === 'string') {
    ms = milliseconds(ms);
  }
  debug('timeout %d', ms);
  this._timeout = ms;
  if (this.timer) {
    this.resetTimeout();
  }
  return this;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Runner"></a>[module mocha.Runner](#apidoc.module.mocha.Runner)

#### <a name="apidoc.element.mocha.Runner.Runner"></a>[function <span class="apidocSignatureSpan">mocha.</span>Runner (suite, delay)](#apidoc.element.mocha.Runner.Runner)
- description and source-code
```javascript
function Runner(suite, delay) {
  var self = this;
  this._globals = [];
  this._abort = false;
  this._delay = delay;
  this.suite = suite;
  this.started = false;
  this.total = suite.total();
  this.failures = 0;
  this.on('test end', function (test) {
    self.checkGlobals(test);
  });
  this.on('hook end', function (hook) {
    self.checkGlobals(hook);
  });
  this._defaultGrep = /.*/;
  this.grep(this._defaultGrep);
  this.globals(this.globalProps().concat(extraGlobals()));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.immediately"></a>[function <span class="apidocSignatureSpan">mocha.Runner.</span>immediately (callback, arg1, arg2, arg3)](#apidoc.element.mocha.Runner.immediately)
- description and source-code
```javascript
immediately = function (callback, arg1, arg2, arg3) {
  if (typeof callback !== 'function') {
    throw new TypeError('"callback" argument must be a function');
  }

  var i, args;

  switch (arguments.length) {
    // fast cases
    case 1:
      break;
    case 2:
      args = [arg1];
      break;
    case 3:
      args = [arg1, arg2];
      break;
    default:
      args = [arg1, arg2, arg3];
      for (i = 4; i < arguments.length; i++)
        // extend array dynamically, makes .apply run much faster in v6.0.0
        args[i - 1] = arguments[i];
      break;
  }
  return createImmediate(args, callback);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.super_"></a>[function <span class="apidocSignatureSpan">mocha.Runner.</span>super_ ()](#apidoc.element.mocha.Runner.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Runner.prototype"></a>[module mocha.Runner.prototype](#apidoc.module.mocha.Runner.prototype)

#### <a name="apidoc.element.mocha.Runner.prototype.abort"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>abort ()](#apidoc.element.mocha.Runner.prototype.abort)
- description and source-code
```javascript
abort = function () {
  debug('aborting');
  this._abort = true;

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.checkGlobals"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>checkGlobals (test)](#apidoc.element.mocha.Runner.prototype.checkGlobals)
- description and source-code
```javascript
checkGlobals = function (test) {
  if (this.ignoreLeaks) {
    return;
  }
  var ok = this._globals;

  var globals = this.globalProps();
  var leaks;

  if (test) {
    ok = ok.concat(test._allowedGlobals || []);
  }

  if (this.prevGlobalsLength === globals.length) {
    return;
  }
  this.prevGlobalsLength = globals.length;

  leaks = filterLeaks(ok, globals);
  this._globals = this._globals.concat(leaks);

  if (leaks.length > 1) {
    this.fail(test, new Error('global leaks detected: ' + leaks.join(', ') + ''));
  } else if (leaks.length) {
    this.fail(test, new Error('global leak detected: ' + leaks[0]));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.fail"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>fail (test, err)](#apidoc.element.mocha.Runner.prototype.fail)
- description and source-code
```javascript
fail = function (test, err) {
  if (test.isPending()) {
    return;
  }

  ++this.failures;
  test.state = 'failed';

  if (!(err instanceof Error || err && typeof err.message === 'string')) {
    err = new Error('the ' + type(err) + ' ' + stringify(err) + ' was thrown, throw an Error :)');
  }

  try {
    err.stack = (this.fullStackTrace || !err.stack)
      ? err.stack
      : stackFilter(err.stack);
  } catch (ignored) {
    // some environments do not take kindly to monkeying with the stack
  }

  this.emit('fail', test, err);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.failHook"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>failHook (hook, err)](#apidoc.element.mocha.Runner.prototype.failHook)
- description and source-code
```javascript
failHook = function (hook, err) {
  if (hook.ctx && hook.ctx.currentTest) {
    hook.originalTitle = hook.originalTitle || hook.title;
    hook.title = hook.originalTitle + ' for "' + hook.ctx.currentTest.title + '"';
  }

  this.fail(hook, err);
  if (this.suite.bail()) {
    this.emit('end');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.globalProps"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>globalProps ()](#apidoc.element.mocha.Runner.prototype.globalProps)
- description and source-code
```javascript
globalProps = function () {
  var props = keys(global);

  // non-enumerables
  for (var i = 0; i < globals.length; ++i) {
    if (~indexOf(props, globals[i])) {
      continue;
    }
    props.push(globals[i]);
  }

  return props;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.globals"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>globals (arr)](#apidoc.element.mocha.Runner.prototype.globals)
- description and source-code
```javascript
globals = function (arr) {
  if (!arguments.length) {
    return this._globals;
  }
  debug('globals %j', arr);
  this._globals = this._globals.concat(arr);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.grep"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>grep (re, invert)](#apidoc.element.mocha.Runner.prototype.grep)
- description and source-code
```javascript
grep = function (re, invert) {
  debug('grep %s', re);
  this._grep = re;
  this._invert = invert;
  this.total = this.grepTotal(this.suite);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.grepTotal"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>grepTotal (suite)](#apidoc.element.mocha.Runner.prototype.grepTotal)
- description and source-code
```javascript
grepTotal = function (suite) {
  var self = this;
  var total = 0;

  suite.eachTest(function (test) {
    var match = self._grep.test(test.fullTitle());
    if (self._invert) {
      match = !match;
    }
    if (match) {
      total++;
    }
  });

  return total;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.hook"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>hook (name, fn)](#apidoc.element.mocha.Runner.prototype.hook)
- description and source-code
```javascript
hook = function (name, fn) {
  var suite = this.suite;
  var hooks = suite['_' + name];
  var self = this;

  function next (i) {
    var hook = hooks[i];
    if (!hook) {
      return fn();
    }
    self.currentRunnable = hook;

    hook.ctx.currentTest = self.test;

    self.emit('hook', hook);

    if (!hook.listeners('error').length) {
      hook.on('error', function (err) {
        self.failHook(hook, err);
      });
    }

    hook.run(function (err) {
      var testError = hook.error();
      if (testError) {
        self.fail(self.test, testError);
      }
      if (err) {
        if (err instanceof Pending) {
          if (name === 'beforeEach' || name === 'afterEach') {
            self.test.pending = true;
          } else {
            utils.forEach(suite.tests, function (test) {
              test.pending = true;
            });
            // a pending hook won't be executed twice.
            hook.pending = true;
          }
        } else {
          self.failHook(hook, err);

          // stop executing hooks, notify callee of hook err
          return fn(err);
        }
      }
      self.emit('hook end', hook);
      delete hook.ctx.currentTest;
      next(++i);
    });
  }

  Runner.immediately(function () {
    next(0);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.hookDown"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>hookDown (name, fn)](#apidoc.element.mocha.Runner.prototype.hookDown)
- description and source-code
```javascript
hookDown = function (name, fn) {
  var suites = [this.suite].concat(this.parents());
  this.hooks(name, suites, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.hookUp"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>hookUp (name, fn)](#apidoc.element.mocha.Runner.prototype.hookUp)
- description and source-code
```javascript
hookUp = function (name, fn) {
  var suites = [this.suite].concat(this.parents()).reverse();
  this.hooks(name, suites, fn);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.hooks"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>hooks (name, suites, fn)](#apidoc.element.mocha.Runner.prototype.hooks)
- description and source-code
```javascript
hooks = function (name, suites, fn) {
  var self = this;
  var orig = this.suite;

  function next (suite) {
    self.suite = suite;

    if (!suite) {
      self.suite = orig;
      return fn();
    }

    self.hook(name, function (err) {
      if (err) {
        var errSuite = self.suite;
        self.suite = orig;
        return fn(err, errSuite);
      }

      next(suites.pop());
    });
  }

  next(suites.pop());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.parents"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>parents ()](#apidoc.element.mocha.Runner.prototype.parents)
- description and source-code
```javascript
parents = function () {
  var suite = this.suite;
  var suites = [];
  while (suite.parent) {
    suite = suite.parent;
    suites.push(suite);
  }
  return suites;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.run"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>run (fn)](#apidoc.element.mocha.Runner.prototype.run)
- description and source-code
```javascript
run = function (fn) {
  var self = this;
  var rootSuite = this.suite;

  // If there is an 'only' filter
  if (this.hasOnly) {
    filterOnly(rootSuite);
  }

  fn = fn || function () {};

  function uncaught (err) {
    self.uncaught(err);
  }

  function start () {
    self.started = true;
    self.emit('start');
    self.runSuite(rootSuite, function () {
      debug('finished running');
      self.emit('end');
    });
  }

  debug('start');

  // references cleanup to avoid memory leaks
  this.on('suite end', cleanSuiteReferences);

  // callback
  this.on('end', function () {
    debug('end');
    process.removeListener('uncaughtException', uncaught);
    fn(self.failures);
  });

  // uncaught exception
  process.on('uncaughtException', uncaught);

  if (this._delay) {
    // for reporters, I guess.
    // might be nice to debounce some dots while we wait.
    this.emit('waiting', rootSuite);
    rootSuite.once('run', start);
  } else {
    start();
  }

  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.runSuite"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>runSuite (suite, fn)](#apidoc.element.mocha.Runner.prototype.runSuite)
- description and source-code
```javascript
runSuite = function (suite, fn) {
  var i = 0;
  var self = this;
  var total = this.grepTotal(suite);
  var afterAllHookCalled = false;

  debug('run suite %s', suite.fullTitle());

  if (!total || (self.failures && suite._bail)) {
    return fn();
  }

  this.emit('suite', this.suite = suite);

  function next (errSuite) {
    if (errSuite) {
      // current suite failed on a hook from errSuite
      if (errSuite === suite) {
        // if errSuite is current suite
        // continue to the next sibling suite
        return done();
      }
      // errSuite is among the parents of current suite
      // stop execution of errSuite and all sub-suites
      return done(errSuite);
    }

    if (self._abort) {
      return done();
    }

    var curr = suite.suites[i++];
    if (!curr) {
      return done();
    }

    // Avoid grep neglecting large number of tests causing a
    // huge recursive loop and thus a maximum call stack error.
    // See comment in 'this.runTests()' for more information.
    if (self._grep !== self._defaultGrep) {
      Runner.immediately(function () {
        self.runSuite(curr, next);
      });
    } else {
      self.runSuite(curr, next);
    }
  }

  function done (errSuite) {
    self.suite = suite;
    self.nextSuite = next;

    if (afterAllHookCalled) {
      fn(errSuite);
    } else {
      // mark that the afterAll block has been called once
      // and so can be skipped if there is an error in it.
      afterAllHookCalled = true;

      // remove reference to test
      delete self.test;

      self.hook('afterAll', function () {
        self.emit('suite end', suite);
        fn(errSuite);
      });
    }
  }

  this.nextSuite = next;

  this.hook('beforeAll', function (err) {
    if (err) {
      return done();
    }
    self.runTests(suite, next);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.runTest"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>runTest (fn)](#apidoc.element.mocha.Runner.prototype.runTest)
- description and source-code
```javascript
runTest = function (fn) {
  var self = this;
  var test = this.test;

  if (!test) {
    return;
  }
  if (this.asyncOnly) {
    test.asyncOnly = true;
  }

  if (this.allowUncaught) {
    test.allowUncaught = true;
    return test.run(fn);
  }
  try {
    test.on('error', function (err) {
      self.fail(test, err);
    });
    test.run(fn);
  } catch (err) {
    fn(err);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.runTests"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>runTests (suite, fn)](#apidoc.element.mocha.Runner.prototype.runTests)
- description and source-code
```javascript
runTests = function (suite, fn) {
  var self = this;
  var tests = suite.tests.slice();
  var test;

  function hookErr (_, errSuite, after) {
    // before/after Each hook for errSuite failed:
    var orig = self.suite;

    // for failed 'after each' hook start from errSuite parent,
    // otherwise start from errSuite itself
    self.suite = after ? errSuite.parent : errSuite;

    if (self.suite) {
      // call hookUp afterEach
      self.hookUp('afterEach', function (err2, errSuite2) {
        self.suite = orig;
        // some hooks may fail even now
        if (err2) {
          return hookErr(err2, errSuite2, true);
        }
        // report error suite
        fn(errSuite);
      });
    } else {
      // there is no need calling other 'after each' hooks
      self.suite = orig;
      fn(errSuite);
    }
  }

  function next (err, errSuite) {
    // if we bail after first err
    if (self.failures && suite._bail) {
      return fn();
    }

    if (self._abort) {
      return fn();
    }

    if (err) {
      return hookErr(err, errSuite, true);
    }

    // next test
    test = tests.shift();

    // all done
    if (!test) {
      return fn();
    }

    // grep
    var match = self._grep.test(test.fullTitle());
    if (self._invert) {
      match = !match;
    }
    if (!match) {
      // Run immediately only if we have defined a grep. When we
      // define a grep — It can cause maximum callstack error if
      // the grep is doing a large recursive loop by neglecting
      // all tests. The run immediately function also comes with
      // a performance cost. So we don't want to run immediately
      // if we run the whole test suite, because running the whole
      // test suite don't do any immediate recursive loops. Thus,
      // allowing a JS runtime to breathe.
      if (self._grep !== self._defaultGrep) {
        Runner.immediately(next);
      } else {
        next();
      }
      return;
    }

    if (test.isPending()) {
      self.emit('pending', test);
      self.emit('test end', test);
      return next();
    }

    // execute test and hook(s)
    self.emit('test', self.test = test);
    self.hookDown('beforeEach', function (err, errSuite) {
      if (test.isPending()) {
        self.emit('pending', test);
        self.emit('test end', test);
        return next();
      }
      if (err) {
        return hookErr(err, errSuite, false);
      }
      self.currentRunnable = self.test;
      self.runTest(function (err) {
        test = self.test;
        if (err) {
          var retry = test.currentRetry();
          if (err instanceof Pending) {
            test.pending = true;
            self.emit('pending', test);
          } else if (retry < test.retries()) {
            var clonedTest = test.clone();
            clonedTest.currentRetry(retry + 1);
            tests.unshift(clonedTest);

            // Early return + hook trigger so that it doesn't
            // increment the count wrong
            return self.hookUp('afterEach', next);
          } else {
            self.fail(test, err);
          }
          self.emit('test end', test);

          if (err instanceof Pending) {
            return next();
          }

          return self.hookUp('afterEach', next);
        }

        test.state = 'passed';
        self.emit('pass', test);
        self.emit('test end', test);
        self.hookUp('afterEach', next);
      });
    });
  }

  this.next = next;
  this.hookErr = hookErr;
  next();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Runner.prototype.uncaught"></a>[function <span class="apidocSignatureSpan">mocha.Runner.prototype.</span>uncaught (err)](#apidoc.element.mocha.Runner.prototype.uncaught)
- description and source-code
```javascript
uncaught = function (err) {
  if (err) {
    debug('uncaught exception %s', err !== function () {
      return this;
    }.call(err) ? err : (err.message || err));
  } else {
    debug('uncaught undefined exception');
    err = undefinedError();
  }
  err.uncaught = true;

  var runnable = this.currentRunnable;

  if (!runnable) {
    runnable = new Runnable('Uncaught error outside test suite');
    runnable.parent = this.suite;

    if (this.started) {
      this.fail(runnable, err);
    } else {
      // Can't recover from this failure
      this.emit('start');
      this.fail(runnable, err);
      this.emit('end');
    }

    return;
  }

  runnable.clearTimeout();

  // Ignore errors if complete or pending
  if (runnable.state || runnable.isPending()) {
    return;
  }
  this.fail(runnable, err);

  // recover from test
  if (runnable.type === 'test') {
    this.emit('test end', runnable);
    this.hookUp('afterEach', this.next);
    return;
  }

 // recover from hooks
  if (runnable.type === 'hook') {
    var errSuite = this.suite;
    // if hook failure is in afterEach block
    if (runnable.fullTitle().indexOf('after each') > -1) {
      return this.hookErr(err, errSuite, true);
    }
    // if hook failure is in beforeEach block
    if (runnable.fullTitle().indexOf('before each') > -1) {
      return this.hookErr(err, errSuite, false);
    }
    // if hook failure is in after or before blocks
    return this.nextSuite(errSuite);
  }

  // bail
  this.emit('end');
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Suite"></a>[module mocha.Suite](#apidoc.module.mocha.Suite)

#### <a name="apidoc.element.mocha.Suite.Suite"></a>[function <span class="apidocSignatureSpan">mocha.</span>Suite (title, parentContext)](#apidoc.element.mocha.Suite.Suite)
- description and source-code
```javascript
function Suite(title, parentContext) {
  if (!utils.isString(title)) {
    throw new Error('Suite 'title' should be a "string" but "' + typeof title + '" was given instead.');
  }
  this.title = title;
  function Context () {}
  Context.prototype = parentContext;
  this.ctx = new Context();
  this.suites = [];
  this.tests = [];
  this.pending = false;
  this._beforeEach = [];
  this._beforeAll = [];
  this._afterEach = [];
  this._afterAll = [];
  this.root = !title;
  this._timeout = 2000;
  this._enableTimeouts = true;
  this._slow = 75;
  this._bail = false;
  this._retries = -1;
  this._onlyTests = [];
  this._onlySuites = [];
  this.delayed = false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.create"></a>[function <span class="apidocSignatureSpan">mocha.Suite.</span>create (parent, title)](#apidoc.element.mocha.Suite.create)
- description and source-code
```javascript
create = function (parent, title) {
  var suite = new Suite(title, parent.ctx);
  suite.parent = parent;
  title = suite.fullTitle();
  parent.addSuite(suite);
  return suite;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.super_"></a>[function <span class="apidocSignatureSpan">mocha.Suite.</span>super_ ()](#apidoc.element.mocha.Suite.super_)
- description and source-code
```javascript
function EventEmitter() {
  EventEmitter.init.call(this);
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Suite.prototype"></a>[module mocha.Suite.prototype](#apidoc.module.mocha.Suite.prototype)

#### <a name="apidoc.element.mocha.Suite.prototype.addSuite"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>addSuite (suite)](#apidoc.element.mocha.Suite.prototype.addSuite)
- description and source-code
```javascript
addSuite = function (suite) {
  suite.parent = this;
  suite.timeout(this.timeout());
  suite.retries(this.retries());
  suite.enableTimeouts(this.enableTimeouts());
  suite.slow(this.slow());
  suite.bail(this.bail());
  this.suites.push(suite);
  this.emit('suite', suite);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.addTest"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>addTest (test)](#apidoc.element.mocha.Suite.prototype.addTest)
- description and source-code
```javascript
addTest = function (test) {
  test.parent = this;
  test.timeout(this.timeout());
  test.retries(this.retries());
  test.enableTimeouts(this.enableTimeouts());
  test.slow(this.slow());
  test.ctx = this.ctx;
  this.tests.push(test);
  this.emit('test', test);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.afterAll"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>afterAll (title, fn)](#apidoc.element.mocha.Suite.prototype.afterAll)
- description and source-code
```javascript
afterAll = function (title, fn) {
  if (this.isPending()) {
    return this;
  }
  if (typeof title === 'function') {
    fn = title;
    title = fn.name;
  }
  title = '"after all" hook' + (title ? ': ' + title : '');

  var hook = new Hook(title, fn);
  hook.parent = this;
  hook.timeout(this.timeout());
  hook.retries(this.retries());
  hook.enableTimeouts(this.enableTimeouts());
  hook.slow(this.slow());
  hook.ctx = this.ctx;
  this._afterAll.push(hook);
  this.emit('afterAll', hook);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.afterEach"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>afterEach (title, fn)](#apidoc.element.mocha.Suite.prototype.afterEach)
- description and source-code
```javascript
afterEach = function (title, fn) {
  if (this.isPending()) {
    return this;
  }
  if (typeof title === 'function') {
    fn = title;
    title = fn.name;
  }
  title = '"after each" hook' + (title ? ': ' + title : '');

  var hook = new Hook(title, fn);
  hook.parent = this;
  hook.timeout(this.timeout());
  hook.retries(this.retries());
  hook.enableTimeouts(this.enableTimeouts());
  hook.slow(this.slow());
  hook.ctx = this.ctx;
  this._afterEach.push(hook);
  this.emit('afterEach', hook);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.bail"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>bail (bail)](#apidoc.element.mocha.Suite.prototype.bail)
- description and source-code
```javascript
bail = function (bail) {
  if (!arguments.length) {
    return this._bail;
  }
  debug('bail %s', bail);
  this._bail = bail;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.beforeAll"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>beforeAll (title, fn)](#apidoc.element.mocha.Suite.prototype.beforeAll)
- description and source-code
```javascript
beforeAll = function (title, fn) {
  if (this.isPending()) {
    return this;
  }
  if (typeof title === 'function') {
    fn = title;
    title = fn.name;
  }
  title = '"before all" hook' + (title ? ': ' + title : '');

  var hook = new Hook(title, fn);
  hook.parent = this;
  hook.timeout(this.timeout());
  hook.retries(this.retries());
  hook.enableTimeouts(this.enableTimeouts());
  hook.slow(this.slow());
  hook.ctx = this.ctx;
  this._beforeAll.push(hook);
  this.emit('beforeAll', hook);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.beforeEach"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>beforeEach (title, fn)](#apidoc.element.mocha.Suite.prototype.beforeEach)
- description and source-code
```javascript
beforeEach = function (title, fn) {
  if (this.isPending()) {
    return this;
  }
  if (typeof title === 'function') {
    fn = title;
    title = fn.name;
  }
  title = '"before each" hook' + (title ? ': ' + title : '');

  var hook = new Hook(title, fn);
  hook.parent = this;
  hook.timeout(this.timeout());
  hook.retries(this.retries());
  hook.enableTimeouts(this.enableTimeouts());
  hook.slow(this.slow());
  hook.ctx = this.ctx;
  this._beforeEach.push(hook);
  this.emit('beforeEach', hook);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.clone"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>clone ()](#apidoc.element.mocha.Suite.prototype.clone)
- description and source-code
```javascript
clone = function () {
  var suite = new Suite(this.title);
  debug('clone');
  suite.ctx = this.ctx;
  suite.timeout(this.timeout());
  suite.retries(this.retries());
  suite.enableTimeouts(this.enableTimeouts());
  suite.slow(this.slow());
  suite.bail(this.bail());
  return suite;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.eachTest"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>eachTest (fn)](#apidoc.element.mocha.Suite.prototype.eachTest)
- description and source-code
```javascript
eachTest = function (fn) {
  utils.forEach(this.tests, fn);
  utils.forEach(this.suites, function (suite) {
    suite.eachTest(fn);
  });
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.enableTimeouts"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>enableTimeouts (enabled)](#apidoc.element.mocha.Suite.prototype.enableTimeouts)
- description and source-code
```javascript
enableTimeouts = function (enabled) {
  if (!arguments.length) {
    return this._enableTimeouts;
  }
  debug('enableTimeouts %s', enabled);
  this._enableTimeouts = enabled;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.fullTitle"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>fullTitle ()](#apidoc.element.mocha.Suite.prototype.fullTitle)
- description and source-code
```javascript
fullTitle = function () {
  if (this.parent) {
    var full = this.parent.fullTitle();
    if (full) {
      return full + ' ' + this.title;
    }
  }
  return this.title;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.isPending"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>isPending ()](#apidoc.element.mocha.Suite.prototype.isPending)
- description and source-code
```javascript
isPending = function () {
  return this.pending || (this.parent && this.parent.isPending());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.retries"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>retries (n)](#apidoc.element.mocha.Suite.prototype.retries)
- description and source-code
```javascript
retries = function (n) {
  if (!arguments.length) {
    return this._retries;
  }
  debug('retries %d', n);
  this._retries = parseInt(n, 10) || 0;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.run"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>run ()](#apidoc.element.mocha.Suite.prototype.run)
- description and source-code
```javascript
function run() {
  if (this.root) {
    this.emit('run');
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.slow"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>slow (ms)](#apidoc.element.mocha.Suite.prototype.slow)
- description and source-code
```javascript
slow = function (ms) {
  if (!arguments.length) {
    return this._slow;
  }
  if (typeof ms === 'string') {
    ms = milliseconds(ms);
  }
  debug('slow %d', ms);
  this._slow = ms;
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.timeout"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>timeout (ms)](#apidoc.element.mocha.Suite.prototype.timeout)
- description and source-code
```javascript
timeout = function (ms) {
  if (!arguments.length) {
    return this._timeout;
  }
  if (ms.toString() === '0') {
    this._enableTimeouts = false;
  }
  if (typeof ms === 'string') {
    ms = milliseconds(ms);
  }
  debug('timeout %d', ms);
  this._timeout = parseInt(ms, 10);
  return this;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Suite.prototype.total"></a>[function <span class="apidocSignatureSpan">mocha.Suite.prototype.</span>total ()](#apidoc.element.mocha.Suite.prototype.total)
- description and source-code
```javascript
total = function () {
  return utils.reduce(this.suites, function (sum, suite) {
    return sum + suite.total();
  }, 0) + this.tests.length;
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Test"></a>[module mocha.Test](#apidoc.module.mocha.Test)

#### <a name="apidoc.element.mocha.Test.Test"></a>[function <span class="apidocSignatureSpan">mocha.</span>Test (title, fn)](#apidoc.element.mocha.Test.Test)
- description and source-code
```javascript
function Test(title, fn) {
  if (!isString(title)) {
    throw new Error('Test 'title' should be a "string" but "' + typeof title + '" was given instead.');
  }
  Runnable.call(this, title, fn);
  this.pending = !fn;
  this.type = 'test';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.Test.prototype"></a>[module mocha.Test.prototype](#apidoc.module.mocha.Test.prototype)

#### <a name="apidoc.element.mocha.Test.prototype.clone"></a>[function <span class="apidocSignatureSpan">mocha.Test.prototype.</span>clone ()](#apidoc.element.mocha.Test.prototype.clone)
- description and source-code
```javascript
clone = function () {
  var test = new Test(this.title, this.fn);
  test.timeout(this.timeout());
  test.slow(this.slow());
  test.enableTimeouts(this.enableTimeouts());
  test.retries(this.retries());
  test.currentRetry(this.currentRetry());
  test.globals(this.globals());
  test.parent = this.parent;
  test.file = this.file;
  test.ctx = this.ctx;
  return test;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.Test.prototype.constructor"></a>[function <span class="apidocSignatureSpan">mocha.Test.prototype.</span>constructor (title, fn)](#apidoc.element.mocha.Test.prototype.constructor)
- description and source-code
```javascript
function Test(title, fn) {
  if (!isString(title)) {
    throw new Error('Test 'title' should be a "string" but "' + typeof title + '" was given instead.');
  }
  Runnable.call(this, title, fn);
  this.pending = !fn;
  this.type = 'test';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.interfaces"></a>[module mocha.interfaces](#apidoc.module.mocha.interfaces)

#### <a name="apidoc.element.mocha.interfaces.bdd"></a>[function <span class="apidocSignatureSpan">mocha.interfaces.</span>bdd (suite)](#apidoc.element.mocha.interfaces.bdd)
- description and source-code
```javascript
bdd = function (suite) {
  var suites = [suite];

  suite.on('pre-require', function (context, file, mocha) {
    var common = require('./common')(suites, context, mocha);

    context.before = common.before;
    context.after = common.after;
    context.beforeEach = common.beforeEach;
    context.afterEach = common.afterEach;
    context.run = mocha.options.delay && common.runWithSuite(suite);
<span class="apidocCodeCommentSpan">    /**
     * Describe a "suite" with the given 'title'
     * and callback 'fn' containing nested suites
     * and/or tests.
     */
</span>
    context.describe = context.context = function (title, fn) {
      return common.suite.create({
        title: title,
        file: file,
        fn: fn
      });
    };

    /**
     * Pending describe.
     */

    context.xdescribe = context.xcontext = context.describe.skip = function (title, fn) {
      return common.suite.skip({
        title: title,
        file: file,
        fn: fn
      });
    };

    /**
     * Exclusive suite.
     */

    context.describe.only = function (title, fn) {
      return common.suite.only({
        title: title,
        file: file,
        fn: fn
      });
    };

    /**
     * Describe a specification or test-case
     * with the given 'title' and callback 'fn'
     * acting as a thunk.
     */

    context.it = context.specify = function (title, fn) {
      var suite = suites[0];
      if (suite.isPending()) {
        fn = null;
      }
      var test = new Test(title, fn);
      test.file = file;
      suite.addTest(test);
      return test;
    };

    /**
     * Exclusive test-case.
     */

    context.it.only = function (title, fn) {
      return common.test.only(mocha, context.it(title, fn));
    };

    /**
     * Pending test case.
     */

    context.xit = context.xspecify = context.it.skip = function (title) {
      context.it(title);
    };

    /**
     * Number of attempts to retry.
     */
    context.it.retries = function (n) {
      context.retries(n);
    };
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.interfaces.exports"></a>[function <span class="apidocSignatureSpan">mocha.interfaces.</span>exports (suite)](#apidoc.element.mocha.interfaces.exports)
- description and source-code
```javascript
exports = function (suite) {
  var suites = [suite];

  suite.on('require', visit);

  function visit (obj, file) {
    var suite;
    for (var key in obj) {
      if (typeof obj[key] === 'function') {
        var fn = obj[key];
        switch (key) {
          case 'before':
            suites[0].beforeAll(fn);
            break;
          case 'after':
            suites[0].afterAll(fn);
            break;
          case 'beforeEach':
            suites[0].beforeEach(fn);
            break;
          case 'afterEach':
            suites[0].afterEach(fn);
            break;
          default:
            var test = new Test(key, fn);
            test.file = file;
            suites[0].addTest(test);
        }
      } else {
        suite = Suite.create(suites[0], key);
        suites.unshift(suite);
        visit(obj[key], file);
        suites.shift();
      }
    }
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.interfaces.qunit"></a>[function <span class="apidocSignatureSpan">mocha.interfaces.</span>qunit (suite)](#apidoc.element.mocha.interfaces.qunit)
- description and source-code
```javascript
qunit = function (suite) {
  var suites = [suite];

  suite.on('pre-require', function (context, file, mocha) {
    var common = require('./common')(suites, context, mocha);

    context.before = common.before;
    context.after = common.after;
    context.beforeEach = common.beforeEach;
    context.afterEach = common.afterEach;
    context.run = mocha.options.delay && common.runWithSuite(suite);
<span class="apidocCodeCommentSpan">    /**
     * Describe a "suite" with the given 'title'.
     */
</span>
    context.suite = function (title) {
      if (suites.length > 1) {
        suites.shift();
      }
      return common.suite.create({
        title: title,
        file: file,
        fn: false
      });
    };

    /**
     * Exclusive Suite.
     */

    context.suite.only = function (title) {
      if (suites.length > 1) {
        suites.shift();
      }
      return common.suite.only({
        title: title,
        file: file,
        fn: false
      });
    };

    /**
     * Describe a specification or test-case
     * with the given 'title' and callback 'fn'
     * acting as a thunk.
     */

    context.test = function (title, fn) {
      var test = new Test(title, fn);
      test.file = file;
      suites[0].addTest(test);
      return test;
    };

    /**
     * Exclusive test-case.
     */

    context.test.only = function (title, fn) {
      return common.test.only(mocha, context.test(title, fn));
    };

    context.test.skip = common.test.skip;
    context.test.retries = common.test.retries;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.interfaces.tdd"></a>[function <span class="apidocSignatureSpan">mocha.interfaces.</span>tdd (suite)](#apidoc.element.mocha.interfaces.tdd)
- description and source-code
```javascript
tdd = function (suite) {
  var suites = [suite];

  suite.on('pre-require', function (context, file, mocha) {
    var common = require('./common')(suites, context, mocha);

    context.setup = common.beforeEach;
    context.teardown = common.afterEach;
    context.suiteSetup = common.before;
    context.suiteTeardown = common.after;
    context.run = mocha.options.delay && common.runWithSuite(suite);

<span class="apidocCodeCommentSpan">    /**
     * Describe a "suite" with the given 'title' and callback 'fn' containing
     * nested suites and/or tests.
     */
</span>    context.suite = function (title, fn) {
      return common.suite.create({
        title: title,
        file: file,
        fn: fn
      });
    };

    /**
     * Pending suite.
     */
    context.suite.skip = function (title, fn) {
      return common.suite.skip({
        title: title,
        file: file,
        fn: fn
      });
    };

    /**
     * Exclusive test-case.
     */
    context.suite.only = function (title, fn) {
      return common.suite.only({
        title: title,
        file: file,
        fn: fn
      });
    };

    /**
     * Describe a specification or test-case with the given 'title' and
     * callback 'fn' acting as a thunk.
     */
    context.test = function (title, fn) {
      var suite = suites[0];
      if (suite.isPending()) {
        fn = null;
      }
      var test = new Test(title, fn);
      test.file = file;
      suite.addTest(test);
      return test;
    };

    /**
     * Exclusive test-case.
     */

    context.test.only = function (title, fn) {
      return common.test.only(mocha, context.test(title, fn));
    };

    context.test.skip = common.test.skip;
    context.test.retries = common.test.retries;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters"></a>[module mocha.reporters](#apidoc.module.mocha.reporters)

#### <a name="apidoc.element.mocha.reporters.Base"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>Base (runner)](#apidoc.element.mocha.reporters.Base)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.Doc"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>Doc (runner)](#apidoc.element.mocha.reporters.Doc)
- description and source-code
```javascript
function Doc(runner) {
  Base.call(this, runner);

  var indents = 2;

  function indent () {
    return Array(indents).join('  ');
  }

  runner.on('suite', function (suite) {
    if (suite.root) {
      return;
    }
    ++indents;
    console.log('%s<section class="suite">', indent());
    ++indents;
    console.log('%s<h1>%s</h1>', indent(), utils.escape(suite.title));
    console.log('%s<dl>', indent());
  });

  runner.on('suite end', function (suite) {
    if (suite.root) {
      return;
    }
    console.log('%s</dl>', indent());
    --indents;
    console.log('%s</section>', indent());
    --indents;
  });

  runner.on('pass', function (test) {
    console.log('%s  <dt>%s</dt>', indent(), utils.escape(test.title));
    var code = utils.escape(utils.clean(test.body));
    console.log('%s  <dd><pre><code>%s</code></pre></dd>', indent(), code);
  });

  runner.on('fail', function (test, err) {
    console.log('%s  <dt class="error">%s</dt>', indent(), utils.escape(test.title));
    var code = utils.escape(utils.clean(test.body));
    console.log('%s  <dd class="error"><pre><code>%s</code></pre></dd>', indent(), code);
    console.log('%s  <dd class="error">%s</dd>', indent(), utils.escape(err));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.Dot"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>Dot (runner)](#apidoc.element.mocha.reporters.Dot)
- description and source-code
```javascript
function Dot(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var n = -1;

  runner.on('start', function () {
    process.stdout.write('\n');
  });

  runner.on('pending', function () {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    process.stdout.write(color('pending', Base.symbols.comma));
  });

  runner.on('pass', function (test) {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    if (test.speed === 'slow') {
      process.stdout.write(color('bright yellow', Base.symbols.dot));
    } else {
      process.stdout.write(color(test.speed, Base.symbols.dot));
    }
  });

  runner.on('fail', function () {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    process.stdout.write(color('fail', Base.symbols.bang));
  });

  runner.on('end', function () {
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.HTML"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>HTML (runner)](#apidoc.element.mocha.reporters.HTML)
- description and source-code
```javascript
function HTML(runner) {
  Base.call(this, runner);

  var self = this;
  var stats = this.stats;
  var stat = fragment(statsTemplate);
  var items = stat.getElementsByTagName('li');
  var passes = items[1].getElementsByTagName('em')[0];
  var passesLink = items[1].getElementsByTagName('a')[0];
  var failures = items[2].getElementsByTagName('em')[0];
  var failuresLink = items[2].getElementsByTagName('a')[0];
  var duration = items[3].getElementsByTagName('em')[0];
  var canvas = stat.getElementsByTagName('canvas')[0];
  var report = fragment('<ul id="mocha-report"></ul>');
  var stack = [report];
  var progress;
  var ctx;
  var root = document.getElementById('mocha');

  if (canvas.getContext) {
    var ratio = window.devicePixelRatio || 1;
    canvas.style.width = canvas.width;
    canvas.style.height = canvas.height;
    canvas.width *= ratio;
    canvas.height *= ratio;
    ctx = canvas.getContext('2d');
    ctx.scale(ratio, ratio);
    progress = new Progress();
  }

  if (!root) {
    return error('#mocha div missing, add it to your document');
  }

  // pass toggle
  on(passesLink, 'click', function (evt) {
    evt.preventDefault();
    unhide();
    var name = (/pass/).test(report.className) ? '' : ' pass';
    report.className = report.className.replace(/fail|pass/g, '') + name;
    if (report.className.trim()) {
      hideSuitesWithout('test pass');
    }
  });

  // failure toggle
  on(failuresLink, 'click', function (evt) {
    evt.preventDefault();
    unhide();
    var name = (/fail/).test(report.className) ? '' : ' fail';
    report.className = report.className.replace(/fail|pass/g, '') + name;
    if (report.className.trim()) {
      hideSuitesWithout('test fail');
    }
  });

  root.appendChild(stat);
  root.appendChild(report);

  if (progress) {
    progress.size(40);
  }

  runner.on('suite', function (suite) {
    if (suite.root) {
      return;
    }

    // suite
    var url = self.suiteURL(suite);
    var el = fragment('<li class="suite"><h1><a href="%s">%s</a></h1></li>', url, escape(suite.title));

    // container
    stack[0].appendChild(el);
    stack.unshift(document.createElement('ul'));
    el.appendChild(stack[0]);
  });

  runner.on('suite end', function (suite) {
    if (suite.root) {
      updateStats();
      return;
    }
    stack.shift();
  });

  runner.on('pass', function (test) {
    var url = self.testURL(test);
    var markup = '<li class="test pass %e"><h2>%e<span class="duration">%ems</span> ' +
      '<a href="%s" class="replay">‣</a></h2></li>';
    var el = fragment(markup, test.speed, test.title, test.duration, url);
    self.addCodeToggle(el, test.body);
    appendToStack(el);
    updateStats();
  });

  runner.on('fail', function (test) {
    var el = fragment('<li class="test fail"><h2>%e <a href="%e" class="replay">‣</a></h2></li>',
      test.title, self.testURL(test));
    var stackString; // Note: Includes leading newline
    var message = test.err.toString();

    // <=IE7 stringifies to [Object Error]. Since it can be overloaded, we
    // check for the result of the stringifying.
    if (message === '[object Error]') {
      message = test.err.message;
    }

    if (test.err.stack) {
      var indexOfMessage = test.err.stack.indexOf(test.err.message);
      if (indexOfMessage === -1) {
        stackString = test.err.stack;
      } else {
        stackString = test.err.stack.substr(test.err.message.length + indexOfMessage);
      }
    } else if (test.err.sourceURL && test.err.line !== undefined) {
      // Safari doesn't give you a stack. Let's at least provide a source line.
      stackString = '\n(' + test.err.sourceURL + ':' + test.err.line + ')';
    }

    stackString = stackString || '';

    if (test.err.htmlMessage && stackString) {
      el.appendChild(fragment('<div class="html-error">%s\n<pre class="error">%e</pre></div>',
        test.err.htmlMessage, stackString));
    } else if (test.err.htmlMessage) {
      el.appendChild(fragment('<div class="html-error">%s</div>', test.err.htmlMessage));
    } else {
      el.appendChild(fragment('<pre class= ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.JSON"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>JSON (runner)](#apidoc.element.mocha.reporters.JSON)
- description and source-code
```javascript
function JSONReporter(runner) {
  Base.call(this, runner);

  var self = this;
  var tests = [];
  var pending = [];
  var failures = [];
  var passes = [];

  runner.on('test end', function (test) {
    tests.push(test);
  });

  runner.on('pass', function (test) {
    passes.push(test);
  });

  runner.on('fail', function (test) {
    failures.push(test);
  });

  runner.on('pending', function (test) {
    pending.push(test);
  });

  runner.on('end', function () {
    var obj = {
      stats: self.stats,
      tests: tests.map(clean),
      pending: pending.map(clean),
      failures: failures.map(clean),
      passes: passes.map(clean)
    };

    runner.testResults = obj;

    process.stdout.write(JSON.stringify(obj, null, 2));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.JSONStream"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>JSONStream (runner)](#apidoc.element.mocha.reporters.JSONStream)
- description and source-code
```javascript
function List(runner) {
  Base.call(this, runner);

  var self = this;
  var total = runner.total;

  runner.on('start', function () {
    console.log(JSON.stringify(['start', { total: total }]));
  });

  runner.on('pass', function (test) {
    console.log(JSON.stringify(['pass', clean(test)]));
  });

  runner.on('fail', function (test, err) {
    test = clean(test);
    test.err = err.message;
    test.stack = err.stack || null;
    console.log(JSON.stringify(['fail', test]));
  });

  runner.on('end', function () {
    process.stdout.write(JSON.stringify(['end', self.stats]));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.Landing"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>Landing (runner)](#apidoc.element.mocha.reporters.Landing)
- description and source-code
```javascript
function Landing(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var total = runner.total;
  var stream = process.stdout;
  var plane = color('plane', '✈');
  var crashed = -1;
  var n = 0;

  function runway () {
    var buf = Array(width).join('-');
    return '  ' + color('runway', buf);
  }

  runner.on('start', function () {
    stream.write('\n\n\n  ');
    cursor.hide();
  });

  runner.on('test end', function (test) {
    // check if the plane crashed
    var col = crashed === -1 ? width * ++n / total | 0 : crashed;

    // show the crash
    if (test.state === 'failed') {
      plane = color('plane crash', '✈');
      crashed = col;
    }

    // render landing strip
    stream.write('\u001b[' + (width + 1) + 'D\u001b[2A');
    stream.write(runway());
    stream.write('\n  ');
    stream.write(color('runway', Array(col).join('⋅')));
    stream.write(plane);
    stream.write(color('runway', Array(width - col).join('⋅') + '\n'));
    stream.write(runway());
    stream.write('\u001b[0m');
  });

  runner.on('end', function () {
    cursor.show();
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.List"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>List (runner)](#apidoc.element.mocha.reporters.List)
- description and source-code
```javascript
function List(runner) {
  Base.call(this, runner);

  var self = this;
  var n = 0;

  runner.on('start', function () {
    console.log();
  });

  runner.on('test', function (test) {
    process.stdout.write(color('pass', '    ' + test.fullTitle() + ': '));
  });

  runner.on('pending', function (test) {
    var fmt = color('checkmark', '  -') +
      color('pending', ' %s');
    console.log(fmt, test.fullTitle());
  });

  runner.on('pass', function (test) {
    var fmt = color('checkmark', '  ' + Base.symbols.ok) +
      color('pass', ' %s: ') +
      color(test.speed, '%dms');
    cursor.CR();
    console.log(fmt, test.fullTitle(), test.duration);
  });

  runner.on('fail', function (test) {
    cursor.CR();
    console.log(color('fail', '  %d) %s'), ++n, test.fullTitle());
  });

  runner.on('end', self.epilogue.bind(self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.Markdown"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>Markdown (runner)](#apidoc.element.mocha.reporters.Markdown)
- description and source-code
```javascript
function Markdown(runner) {
  Base.call(this, runner);

  var level = 0;
  var buf = '';

  function title (str) {
    return Array(level).join('#') + ' ' + str;
  }

  function mapTOC (suite, obj) {
    var ret = obj;
    var key = SUITE_PREFIX + suite.title;

    obj = obj[key] = obj[key] || { suite: suite };
    suite.suites.forEach(function (suite) {
      mapTOC(suite, obj);
    });

    return ret;
  }

  function stringifyTOC (obj, level) {
    ++level;
    var buf = '';
    var link;
    for (var key in obj) {
      if (key === 'suite') {
        continue;
      }
      if (key !== SUITE_PREFIX) {
        link = ' - [' + key.substring(1) + ']';
        link += '(#' + utils.slug(obj[key].suite.fullTitle()) + ')\n';
        buf += Array(level).join('  ') + link;
      }
      buf += stringifyTOC(obj[key], level);
    }
    return buf;
  }

  function generateTOC (suite) {
    var obj = mapTOC(suite, {});
    return stringifyTOC(obj, 0);
  }

  generateTOC(runner.suite);

  runner.on('suite', function (suite) {
    ++level;
    var slug = utils.slug(suite.fullTitle());
    buf += '<a name="' + slug + '"></a>' + '\n';
    buf += title(suite.title) + '\n';
  });

  runner.on('suite end', function () {
    --level;
  });

  runner.on('pass', function (test) {
    var code = utils.clean(test.body);
    buf += test.title + '.\n';
    buf += '\n'''js\n';
    buf += code + '\n';
    buf += ''''\n\n';
  });

  runner.on('end', function () {
    process.stdout.write('# TOC\n');
    process.stdout.write(generateTOC(runner.suite));
    process.stdout.write(buf);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.Min"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>Min (runner)](#apidoc.element.mocha.reporters.Min)
- description and source-code
```javascript
function Min(runner) {
  Base.call(this, runner);

  runner.on('start', function () {
    // clear screen
    process.stdout.write('\u001b[2J');
    // set cursor position
    process.stdout.write('\u001b[1;3H');
  });

  runner.on('end', this.epilogue.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.Nyan"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>Nyan (runner)](#apidoc.element.mocha.reporters.Nyan)
- description and source-code
```javascript
function NyanCat(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var nyanCatWidth = this.nyanCatWidth = 11;

  this.colorIndex = 0;
  this.numberOfLines = 4;
  this.rainbowColors = self.generateColors();
  this.scoreboardWidth = 5;
  this.tick = 0;
  this.trajectories = [[], [], [], []];
  this.trajectoryWidthMax = (width - nyanCatWidth);

  runner.on('start', function () {
    Base.cursor.hide();
    self.draw();
  });

  runner.on('pending', function () {
    self.draw();
  });

  runner.on('pass', function () {
    self.draw();
  });

  runner.on('fail', function () {
    self.draw();
  });

  runner.on('end', function () {
    Base.cursor.show();
    for (var i = 0; i < self.numberOfLines; i++) {
      write('\n');
    }
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.Progress"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>Progress (runner, options)](#apidoc.element.mocha.reporters.Progress)
- description and source-code
```javascript
function Progress(runner, options) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.50 | 0;
  var total = runner.total;
  var complete = 0;
  var lastN = -1;

  // default chars
  options = options || {};
  options.open = options.open || '[';
  options.complete = options.complete || '▬';
  options.incomplete = options.incomplete || Base.symbols.dot;
  options.close = options.close || ']';
  options.verbose = false;

  // tests started
  runner.on('start', function () {
    console.log();
    cursor.hide();
  });

  // tests complete
  runner.on('test end', function () {
    complete++;

    var percent = complete / total;
    var n = width * percent | 0;
    var i = width - n;

    if (n === lastN && !options.verbose) {
      // Don't re-render the line if it hasn't changed
      return;
    }
    lastN = n;

    cursor.CR();
    process.stdout.write('\u001b[J');
    process.stdout.write(color('progress', '  ' + options.open));
    process.stdout.write(Array(n).join(options.complete));
    process.stdout.write(Array(i).join(options.incomplete));
    process.stdout.write(color('progress', options.close));
    if (options.verbose) {
      process.stdout.write(color('progress', ' ' + complete + ' of ' + total));
    }
  });

  // tests are complete, output some stats
  // and the failures if any
  runner.on('end', function () {
    cursor.show();
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.Spec"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>Spec (runner)](#apidoc.element.mocha.reporters.Spec)
- description and source-code
```javascript
function Spec(runner) {
  Base.call(this, runner);

  var self = this;
  var indents = 0;
  var n = 0;

  function indent () {
    return Array(indents).join('  ');
  }

  runner.on('start', function () {
    console.log();
  });

  runner.on('suite', function (suite) {
    ++indents;
    console.log(color('suite', '%s%s'), indent(), suite.title);
  });

  runner.on('suite end', function () {
    --indents;
    if (indents === 1) {
      console.log();
    }
  });

  runner.on('pending', function (test) {
    var fmt = indent() + color('pending', '  - %s');
    console.log(fmt, test.title);
  });

  runner.on('pass', function (test) {
    var fmt;
    if (test.speed === 'fast') {
      fmt = indent() +
        color('checkmark', '  ' + Base.symbols.ok) +
        color('pass', ' %s');
      console.log(fmt, test.title);
    } else {
      fmt = indent() +
        color('checkmark', '  ' + Base.symbols.ok) +
        color('pass', ' %s') +
        color(test.speed, ' (%dms)');
      console.log(fmt, test.title, test.duration);
    }
  });

  runner.on('fail', function (test) {
    console.log(indent() + color('fail', '  %d) %s'), ++n, test.title);
  });

  runner.on('end', self.epilogue.bind(self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.TAP"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>TAP (runner)](#apidoc.element.mocha.reporters.TAP)
- description and source-code
```javascript
function TAP(runner) {
  Base.call(this, runner);

  var n = 1;
  var passes = 0;
  var failures = 0;

  runner.on('start', function () {
    var total = runner.grepTotal(runner.suite);
    console.log('%d..%d', 1, total);
  });

  runner.on('test end', function () {
    ++n;
  });

  runner.on('pending', function (test) {
    console.log('ok %d %s # SKIP -', n, title(test));
  });

  runner.on('pass', function (test) {
    passes++;
    console.log('ok %d %s', n, title(test));
  });

  runner.on('fail', function (test, err) {
    failures++;
    console.log('not ok %d %s', n, title(test));
    if (err.stack) {
      console.log(err.stack.replace(/^/gm, '  '));
    }
  });

  runner.on('end', function () {
    console.log('# tests ' + (passes + failures));
    console.log('# pass ' + passes);
    console.log('# fail ' + failures);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.XUnit"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>XUnit (runner, options)](#apidoc.element.mocha.reporters.XUnit)
- description and source-code
```javascript
function XUnit(runner, options) {
  Base.call(this, runner);

  var stats = this.stats;
  var tests = [];
  var self = this;

  if (options && options.reporterOptions && options.reporterOptions.output) {
    if (!fs.createWriteStream) {
      throw new Error('file output not supported in browser');
    }
    mkdirp.sync(path.dirname(options.reporterOptions.output));
    self.fileStream = fs.createWriteStream(options.reporterOptions.output);
  }

  runner.on('pending', function (test) {
    tests.push(test);
  });

  runner.on('pass', function (test) {
    tests.push(test);
  });

  runner.on('fail', function (test) {
    tests.push(test);
  });

  runner.on('end', function () {
    self.write(tag('testsuite', {
      name: 'Mocha Tests',
      tests: stats.tests,
      failures: stats.failures,
      errors: stats.failures,
      skipped: stats.tests - stats.failures - stats.passes,
      timestamp: (new Date()).toUTCString(),
      time: (stats.duration / 1000) || 0
    }, false));

    tests.forEach(function (t) {
      self.test(t);
    });

    self.write('</testsuite>');
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.base"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>base (runner)](#apidoc.element.mocha.reporters.base)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.doc"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>doc (runner)](#apidoc.element.mocha.reporters.doc)
- description and source-code
```javascript
function Doc(runner) {
  Base.call(this, runner);

  var indents = 2;

  function indent () {
    return Array(indents).join('  ');
  }

  runner.on('suite', function (suite) {
    if (suite.root) {
      return;
    }
    ++indents;
    console.log('%s<section class="suite">', indent());
    ++indents;
    console.log('%s<h1>%s</h1>', indent(), utils.escape(suite.title));
    console.log('%s<dl>', indent());
  });

  runner.on('suite end', function (suite) {
    if (suite.root) {
      return;
    }
    console.log('%s</dl>', indent());
    --indents;
    console.log('%s</section>', indent());
    --indents;
  });

  runner.on('pass', function (test) {
    console.log('%s  <dt>%s</dt>', indent(), utils.escape(test.title));
    var code = utils.escape(utils.clean(test.body));
    console.log('%s  <dd><pre><code>%s</code></pre></dd>', indent(), code);
  });

  runner.on('fail', function (test, err) {
    console.log('%s  <dt class="error">%s</dt>', indent(), utils.escape(test.title));
    var code = utils.escape(utils.clean(test.body));
    console.log('%s  <dd class="error"><pre><code>%s</code></pre></dd>', indent(), code);
    console.log('%s  <dd class="error">%s</dd>', indent(), utils.escape(err));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.dot"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>dot (runner)](#apidoc.element.mocha.reporters.dot)
- description and source-code
```javascript
function Dot(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var n = -1;

  runner.on('start', function () {
    process.stdout.write('\n');
  });

  runner.on('pending', function () {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    process.stdout.write(color('pending', Base.symbols.comma));
  });

  runner.on('pass', function (test) {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    if (test.speed === 'slow') {
      process.stdout.write(color('bright yellow', Base.symbols.dot));
    } else {
      process.stdout.write(color(test.speed, Base.symbols.dot));
    }
  });

  runner.on('fail', function () {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    process.stdout.write(color('fail', Base.symbols.bang));
  });

  runner.on('end', function () {
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.html"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>html (runner)](#apidoc.element.mocha.reporters.html)
- description and source-code
```javascript
function HTML(runner) {
  Base.call(this, runner);

  var self = this;
  var stats = this.stats;
  var stat = fragment(statsTemplate);
  var items = stat.getElementsByTagName('li');
  var passes = items[1].getElementsByTagName('em')[0];
  var passesLink = items[1].getElementsByTagName('a')[0];
  var failures = items[2].getElementsByTagName('em')[0];
  var failuresLink = items[2].getElementsByTagName('a')[0];
  var duration = items[3].getElementsByTagName('em')[0];
  var canvas = stat.getElementsByTagName('canvas')[0];
  var report = fragment('<ul id="mocha-report"></ul>');
  var stack = [report];
  var progress;
  var ctx;
  var root = document.getElementById('mocha');

  if (canvas.getContext) {
    var ratio = window.devicePixelRatio || 1;
    canvas.style.width = canvas.width;
    canvas.style.height = canvas.height;
    canvas.width *= ratio;
    canvas.height *= ratio;
    ctx = canvas.getContext('2d');
    ctx.scale(ratio, ratio);
    progress = new Progress();
  }

  if (!root) {
    return error('#mocha div missing, add it to your document');
  }

  // pass toggle
  on(passesLink, 'click', function (evt) {
    evt.preventDefault();
    unhide();
    var name = (/pass/).test(report.className) ? '' : ' pass';
    report.className = report.className.replace(/fail|pass/g, '') + name;
    if (report.className.trim()) {
      hideSuitesWithout('test pass');
    }
  });

  // failure toggle
  on(failuresLink, 'click', function (evt) {
    evt.preventDefault();
    unhide();
    var name = (/fail/).test(report.className) ? '' : ' fail';
    report.className = report.className.replace(/fail|pass/g, '') + name;
    if (report.className.trim()) {
      hideSuitesWithout('test fail');
    }
  });

  root.appendChild(stat);
  root.appendChild(report);

  if (progress) {
    progress.size(40);
  }

  runner.on('suite', function (suite) {
    if (suite.root) {
      return;
    }

    // suite
    var url = self.suiteURL(suite);
    var el = fragment('<li class="suite"><h1><a href="%s">%s</a></h1></li>', url, escape(suite.title));

    // container
    stack[0].appendChild(el);
    stack.unshift(document.createElement('ul'));
    el.appendChild(stack[0]);
  });

  runner.on('suite end', function (suite) {
    if (suite.root) {
      updateStats();
      return;
    }
    stack.shift();
  });

  runner.on('pass', function (test) {
    var url = self.testURL(test);
    var markup = '<li class="test pass %e"><h2>%e<span class="duration">%ems</span> ' +
      '<a href="%s" class="replay">‣</a></h2></li>';
    var el = fragment(markup, test.speed, test.title, test.duration, url);
    self.addCodeToggle(el, test.body);
    appendToStack(el);
    updateStats();
  });

  runner.on('fail', function (test) {
    var el = fragment('<li class="test fail"><h2>%e <a href="%e" class="replay">‣</a></h2></li>',
      test.title, self.testURL(test));
    var stackString; // Note: Includes leading newline
    var message = test.err.toString();

    // <=IE7 stringifies to [Object Error]. Since it can be overloaded, we
    // check for the result of the stringifying.
    if (message === '[object Error]') {
      message = test.err.message;
    }

    if (test.err.stack) {
      var indexOfMessage = test.err.stack.indexOf(test.err.message);
      if (indexOfMessage === -1) {
        stackString = test.err.stack;
      } else {
        stackString = test.err.stack.substr(test.err.message.length + indexOfMessage);
      }
    } else if (test.err.sourceURL && test.err.line !== undefined) {
      // Safari doesn't give you a stack. Let's at least provide a source line.
      stackString = '\n(' + test.err.sourceURL + ':' + test.err.line + ')';
    }

    stackString = stackString || '';

    if (test.err.htmlMessage && stackString) {
      el.appendChild(fragment('<div class="html-error">%s\n<pre class="error">%e</pre></div>',
        test.err.htmlMessage, stackString));
    } else if (test.err.htmlMessage) {
      el.appendChild(fragment('<div class="html-error">%s</div>', test.err.htmlMessage));
    } else {
      el.appendChild(fragment('<pre class= ...
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.json"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>json (runner)](#apidoc.element.mocha.reporters.json)
- description and source-code
```javascript
function JSONReporter(runner) {
  Base.call(this, runner);

  var self = this;
  var tests = [];
  var pending = [];
  var failures = [];
  var passes = [];

  runner.on('test end', function (test) {
    tests.push(test);
  });

  runner.on('pass', function (test) {
    passes.push(test);
  });

  runner.on('fail', function (test) {
    failures.push(test);
  });

  runner.on('pending', function (test) {
    pending.push(test);
  });

  runner.on('end', function () {
    var obj = {
      stats: self.stats,
      tests: tests.map(clean),
      pending: pending.map(clean),
      failures: failures.map(clean),
      passes: passes.map(clean)
    };

    runner.testResults = obj;

    process.stdout.write(JSON.stringify(obj, null, 2));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.json-stream"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>json-stream (runner)](#apidoc.element.mocha.reporters.json-stream)
- description and source-code
```javascript
function List(runner) {
  Base.call(this, runner);

  var self = this;
  var total = runner.total;

  runner.on('start', function () {
    console.log(JSON.stringify(['start', { total: total }]));
  });

  runner.on('pass', function (test) {
    console.log(JSON.stringify(['pass', clean(test)]));
  });

  runner.on('fail', function (test, err) {
    test = clean(test);
    test.err = err.message;
    test.stack = err.stack || null;
    console.log(JSON.stringify(['fail', test]));
  });

  runner.on('end', function () {
    process.stdout.write(JSON.stringify(['end', self.stats]));
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.landing"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>landing (runner)](#apidoc.element.mocha.reporters.landing)
- description and source-code
```javascript
function Landing(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var total = runner.total;
  var stream = process.stdout;
  var plane = color('plane', '✈');
  var crashed = -1;
  var n = 0;

  function runway () {
    var buf = Array(width).join('-');
    return '  ' + color('runway', buf);
  }

  runner.on('start', function () {
    stream.write('\n\n\n  ');
    cursor.hide();
  });

  runner.on('test end', function (test) {
    // check if the plane crashed
    var col = crashed === -1 ? width * ++n / total | 0 : crashed;

    // show the crash
    if (test.state === 'failed') {
      plane = color('plane crash', '✈');
      crashed = col;
    }

    // render landing strip
    stream.write('\u001b[' + (width + 1) + 'D\u001b[2A');
    stream.write(runway());
    stream.write('\n  ');
    stream.write(color('runway', Array(col).join('⋅')));
    stream.write(plane);
    stream.write(color('runway', Array(width - col).join('⋅') + '\n'));
    stream.write(runway());
    stream.write('\u001b[0m');
  });

  runner.on('end', function () {
    cursor.show();
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.list"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>list (runner)](#apidoc.element.mocha.reporters.list)
- description and source-code
```javascript
function List(runner) {
  Base.call(this, runner);

  var self = this;
  var n = 0;

  runner.on('start', function () {
    console.log();
  });

  runner.on('test', function (test) {
    process.stdout.write(color('pass', '    ' + test.fullTitle() + ': '));
  });

  runner.on('pending', function (test) {
    var fmt = color('checkmark', '  -') +
      color('pending', ' %s');
    console.log(fmt, test.fullTitle());
  });

  runner.on('pass', function (test) {
    var fmt = color('checkmark', '  ' + Base.symbols.ok) +
      color('pass', ' %s: ') +
      color(test.speed, '%dms');
    cursor.CR();
    console.log(fmt, test.fullTitle(), test.duration);
  });

  runner.on('fail', function (test) {
    cursor.CR();
    console.log(color('fail', '  %d) %s'), ++n, test.fullTitle());
  });

  runner.on('end', self.epilogue.bind(self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.markdown"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>markdown (runner)](#apidoc.element.mocha.reporters.markdown)
- description and source-code
```javascript
function Markdown(runner) {
  Base.call(this, runner);

  var level = 0;
  var buf = '';

  function title (str) {
    return Array(level).join('#') + ' ' + str;
  }

  function mapTOC (suite, obj) {
    var ret = obj;
    var key = SUITE_PREFIX + suite.title;

    obj = obj[key] = obj[key] || { suite: suite };
    suite.suites.forEach(function (suite) {
      mapTOC(suite, obj);
    });

    return ret;
  }

  function stringifyTOC (obj, level) {
    ++level;
    var buf = '';
    var link;
    for (var key in obj) {
      if (key === 'suite') {
        continue;
      }
      if (key !== SUITE_PREFIX) {
        link = ' - [' + key.substring(1) + ']';
        link += '(#' + utils.slug(obj[key].suite.fullTitle()) + ')\n';
        buf += Array(level).join('  ') + link;
      }
      buf += stringifyTOC(obj[key], level);
    }
    return buf;
  }

  function generateTOC (suite) {
    var obj = mapTOC(suite, {});
    return stringifyTOC(obj, 0);
  }

  generateTOC(runner.suite);

  runner.on('suite', function (suite) {
    ++level;
    var slug = utils.slug(suite.fullTitle());
    buf += '<a name="' + slug + '"></a>' + '\n';
    buf += title(suite.title) + '\n';
  });

  runner.on('suite end', function () {
    --level;
  });

  runner.on('pass', function (test) {
    var code = utils.clean(test.body);
    buf += test.title + '.\n';
    buf += '\n'''js\n';
    buf += code + '\n';
    buf += ''''\n\n';
  });

  runner.on('end', function () {
    process.stdout.write('# TOC\n');
    process.stdout.write(generateTOC(runner.suite));
    process.stdout.write(buf);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.min"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>min (runner)](#apidoc.element.mocha.reporters.min)
- description and source-code
```javascript
function Min(runner) {
  Base.call(this, runner);

  runner.on('start', function () {
    // clear screen
    process.stdout.write('\u001b[2J');
    // set cursor position
    process.stdout.write('\u001b[1;3H');
  });

  runner.on('end', this.epilogue.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>nyan (runner)](#apidoc.element.mocha.reporters.nyan)
- description and source-code
```javascript
function NyanCat(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var nyanCatWidth = this.nyanCatWidth = 11;

  this.colorIndex = 0;
  this.numberOfLines = 4;
  this.rainbowColors = self.generateColors();
  this.scoreboardWidth = 5;
  this.tick = 0;
  this.trajectories = [[], [], [], []];
  this.trajectoryWidthMax = (width - nyanCatWidth);

  runner.on('start', function () {
    Base.cursor.hide();
    self.draw();
  });

  runner.on('pending', function () {
    self.draw();
  });

  runner.on('pass', function () {
    self.draw();
  });

  runner.on('fail', function () {
    self.draw();
  });

  runner.on('end', function () {
    Base.cursor.show();
    for (var i = 0; i < self.numberOfLines; i++) {
      write('\n');
    }
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.progress"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>progress (runner, options)](#apidoc.element.mocha.reporters.progress)
- description and source-code
```javascript
function Progress(runner, options) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.50 | 0;
  var total = runner.total;
  var complete = 0;
  var lastN = -1;

  // default chars
  options = options || {};
  options.open = options.open || '[';
  options.complete = options.complete || '▬';
  options.incomplete = options.incomplete || Base.symbols.dot;
  options.close = options.close || ']';
  options.verbose = false;

  // tests started
  runner.on('start', function () {
    console.log();
    cursor.hide();
  });

  // tests complete
  runner.on('test end', function () {
    complete++;

    var percent = complete / total;
    var n = width * percent | 0;
    var i = width - n;

    if (n === lastN && !options.verbose) {
      // Don't re-render the line if it hasn't changed
      return;
    }
    lastN = n;

    cursor.CR();
    process.stdout.write('\u001b[J');
    process.stdout.write(color('progress', '  ' + options.open));
    process.stdout.write(Array(n).join(options.complete));
    process.stdout.write(Array(i).join(options.incomplete));
    process.stdout.write(color('progress', options.close));
    if (options.verbose) {
      process.stdout.write(color('progress', ' ' + complete + ' of ' + total));
    }
  });

  // tests are complete, output some stats
  // and the failures if any
  runner.on('end', function () {
    cursor.show();
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.spec"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>spec (runner)](#apidoc.element.mocha.reporters.spec)
- description and source-code
```javascript
function Spec(runner) {
  Base.call(this, runner);

  var self = this;
  var indents = 0;
  var n = 0;

  function indent () {
    return Array(indents).join('  ');
  }

  runner.on('start', function () {
    console.log();
  });

  runner.on('suite', function (suite) {
    ++indents;
    console.log(color('suite', '%s%s'), indent(), suite.title);
  });

  runner.on('suite end', function () {
    --indents;
    if (indents === 1) {
      console.log();
    }
  });

  runner.on('pending', function (test) {
    var fmt = indent() + color('pending', '  - %s');
    console.log(fmt, test.title);
  });

  runner.on('pass', function (test) {
    var fmt;
    if (test.speed === 'fast') {
      fmt = indent() +
        color('checkmark', '  ' + Base.symbols.ok) +
        color('pass', ' %s');
      console.log(fmt, test.title);
    } else {
      fmt = indent() +
        color('checkmark', '  ' + Base.symbols.ok) +
        color('pass', ' %s') +
        color(test.speed, ' (%dms)');
      console.log(fmt, test.title, test.duration);
    }
  });

  runner.on('fail', function (test) {
    console.log(indent() + color('fail', '  %d) %s'), ++n, test.title);
  });

  runner.on('end', self.epilogue.bind(self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.tap"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>tap (runner)](#apidoc.element.mocha.reporters.tap)
- description and source-code
```javascript
function TAP(runner) {
  Base.call(this, runner);

  var n = 1;
  var passes = 0;
  var failures = 0;

  runner.on('start', function () {
    var total = runner.grepTotal(runner.suite);
    console.log('%d..%d', 1, total);
  });

  runner.on('test end', function () {
    ++n;
  });

  runner.on('pending', function (test) {
    console.log('ok %d %s # SKIP -', n, title(test));
  });

  runner.on('pass', function (test) {
    passes++;
    console.log('ok %d %s', n, title(test));
  });

  runner.on('fail', function (test, err) {
    failures++;
    console.log('not ok %d %s', n, title(test));
    if (err.stack) {
      console.log(err.stack.replace(/^/gm, '  '));
    }
  });

  runner.on('end', function () {
    console.log('# tests ' + (passes + failures));
    console.log('# pass ' + passes);
    console.log('# fail ' + failures);
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.xunit"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>xunit (runner, options)](#apidoc.element.mocha.reporters.xunit)
- description and source-code
```javascript
function XUnit(runner, options) {
  Base.call(this, runner);

  var stats = this.stats;
  var tests = [];
  var self = this;

  if (options && options.reporterOptions && options.reporterOptions.output) {
    if (!fs.createWriteStream) {
      throw new Error('file output not supported in browser');
    }
    mkdirp.sync(path.dirname(options.reporterOptions.output));
    self.fileStream = fs.createWriteStream(options.reporterOptions.output);
  }

  runner.on('pending', function (test) {
    tests.push(test);
  });

  runner.on('pass', function (test) {
    tests.push(test);
  });

  runner.on('fail', function (test) {
    tests.push(test);
  });

  runner.on('end', function () {
    self.write(tag('testsuite', {
      name: 'Mocha Tests',
      tests: stats.tests,
      failures: stats.failures,
      errors: stats.failures,
      skipped: stats.tests - stats.failures - stats.passes,
      timestamp: (new Date()).toUTCString(),
      time: (stats.duration / 1000) || 0
    }, false));

    tests.forEach(function (t) {
      self.test(t);
    });

    self.write('</testsuite>');
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.base"></a>[module mocha.reporters.base](#apidoc.module.mocha.reporters.base)

#### <a name="apidoc.element.mocha.reporters.base.base"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>base (runner)](#apidoc.element.mocha.reporters.base.base)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.base.color"></a>[function <span class="apidocSignatureSpan">mocha.reporters.base.</span>color (type, str)](#apidoc.element.mocha.reporters.base.color)
- description and source-code
```javascript
color = function (type, str) {
  if (!exports.useColors) {
    return String(str);
  }
  return '\u001b[' + exports.colors[type] + 'm' + str + '\u001b[0m';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.base.list"></a>[function <span class="apidocSignatureSpan">mocha.reporters.base.</span>list (failures)](#apidoc.element.mocha.reporters.base.list)
- description and source-code
```javascript
list = function (failures) {
  console.log();
  failures.forEach(function (test, i) {
    // format
    var fmt = color('error title', '  %s) %s:\n') +
      color('error message', '     %s') +
      color('error stack', '\n%s\n');

    // msg
    var msg;
    var err = test.err;
    var message;
    if (err.message && typeof err.message.toString === 'function') {
      message = err.message + '';
    } else if (typeof err.inspect === 'function') {
      message = err.inspect() + '';
    } else {
      message = '';
    }
    var stack = err.stack || message;
    var index = message ? stack.indexOf(message) : -1;
    var actual = err.actual;
    var expected = err.expected;
    var escape = true;

    if (index === -1) {
      msg = message;
    } else {
      index += message.length;
      msg = stack.slice(0, index);
      // remove msg from stack
      stack = stack.slice(index + 1);
    }

    // uncaught
    if (err.uncaught) {
      msg = 'Uncaught ' + msg;
    }
    // explicitly show diff
    if (err.showDiff !== false && sameType(actual, expected) && expected !== undefined) {
      escape = false;
      if (!(utils.isString(actual) && utils.isString(expected))) {
        err.actual = actual = utils.stringify(actual);
        err.expected = expected = utils.stringify(expected);
      }

      fmt = color('error title', '  %s) %s:\n%s') + color('error stack', '\n%s\n');
      var match = message.match(/^([^:]+): expected/);
      msg = '\n      ' + color('error message', match ? match[1] : msg);

      if (exports.inlineDiffs) {
        msg += inlineDiff(err, escape);
      } else {
        msg += unifiedDiff(err, escape);
      }
    }

    // indent stack trace
    stack = stack.replace(/^/gm, '  ');

    console.log(fmt, (i + 1), test.fullTitle(), msg, stack);
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.base.prototype"></a>[module mocha.reporters.base.prototype](#apidoc.module.mocha.reporters.base.prototype)

#### <a name="apidoc.element.mocha.reporters.base.prototype.epilogue"></a>[function <span class="apidocSignatureSpan">mocha.reporters.base.prototype.</span>epilogue ()](#apidoc.element.mocha.reporters.base.prototype.epilogue)
- description and source-code
```javascript
epilogue = function () {
  var stats = this.stats;
  var fmt;

  console.log();

  // passes
  fmt = color('bright pass', ' ') +
    color('green', ' %d passing') +
    color('light', ' (%s)');

  console.log(fmt,
    stats.passes || 0,
    ms(stats.duration));

  // pending
  if (stats.pending) {
    fmt = color('pending', ' ') +
      color('pending', ' %d pending');

    console.log(fmt, stats.pending);
  }

  // failures
  if (stats.failures) {
    fmt = color('fail', '  %d failing');

    console.log(fmt, stats.failures);

    Base.list(this.failures);
    console.log();
  }

  console.log();
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.dot"></a>[module mocha.reporters.dot](#apidoc.module.mocha.reporters.dot)

#### <a name="apidoc.element.mocha.reporters.dot.dot"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>dot (runner)](#apidoc.element.mocha.reporters.dot.dot)
- description and source-code
```javascript
function Dot(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var n = -1;

  runner.on('start', function () {
    process.stdout.write('\n');
  });

  runner.on('pending', function () {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    process.stdout.write(color('pending', Base.symbols.comma));
  });

  runner.on('pass', function (test) {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    if (test.speed === 'slow') {
      process.stdout.write(color('bright yellow', Base.symbols.dot));
    } else {
      process.stdout.write(color(test.speed, Base.symbols.dot));
    }
  });

  runner.on('fail', function () {
    if (++n % width === 0) {
      process.stdout.write('\n  ');
    }
    process.stdout.write(color('fail', Base.symbols.bang));
  });

  runner.on('end', function () {
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.dot.super_"></a>[function <span class="apidocSignatureSpan">mocha.reporters.dot.</span>super_ (runner)](#apidoc.element.mocha.reporters.dot.super_)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.html"></a>[module mocha.reporters.html](#apidoc.module.mocha.reporters.html)

#### <a name="apidoc.element.mocha.reporters.html.html"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>html (runner)](#apidoc.element.mocha.reporters.html.html)
- description and source-code
```javascript
function HTML(runner) {
  Base.call(this, runner);

  var self = this;
  var stats = this.stats;
  var stat = fragment(statsTemplate);
  var items = stat.getElementsByTagName('li');
  var passes = items[1].getElementsByTagName('em')[0];
  var passesLink = items[1].getElementsByTagName('a')[0];
  var failures = items[2].getElementsByTagName('em')[0];
  var failuresLink = items[2].getElementsByTagName('a')[0];
  var duration = items[3].getElementsByTagName('em')[0];
  var canvas = stat.getElementsByTagName('canvas')[0];
  var report = fragment('<ul id="mocha-report"></ul>');
  var stack = [report];
  var progress;
  var ctx;
  var root = document.getElementById('mocha');

  if (canvas.getContext) {
    var ratio = window.devicePixelRatio || 1;
    canvas.style.width = canvas.width;
    canvas.style.height = canvas.height;
    canvas.width *= ratio;
    canvas.height *= ratio;
    ctx = canvas.getContext('2d');
    ctx.scale(ratio, ratio);
    progress = new Progress();
  }

  if (!root) {
    return error('#mocha div missing, add it to your document');
  }

  // pass toggle
  on(passesLink, 'click', function (evt) {
    evt.preventDefault();
    unhide();
    var name = (/pass/).test(report.className) ? '' : ' pass';
    report.className = report.className.replace(/fail|pass/g, '') + name;
    if (report.className.trim()) {
      hideSuitesWithout('test pass');
    }
  });

  // failure toggle
  on(failuresLink, 'click', function (evt) {
    evt.preventDefault();
    unhide();
    var name = (/fail/).test(report.className) ? '' : ' fail';
    report.className = report.className.replace(/fail|pass/g, '') + name;
    if (report.className.trim()) {
      hideSuitesWithout('test fail');
    }
  });

  root.appendChild(stat);
  root.appendChild(report);

  if (progress) {
    progress.size(40);
  }

  runner.on('suite', function (suite) {
    if (suite.root) {
      return;
    }

    // suite
    var url = self.suiteURL(suite);
    var el = fragment('<li class="suite"><h1><a href="%s">%s</a></h1></li>', url, escape(suite.title));

    // container
    stack[0].appendChild(el);
    stack.unshift(document.createElement('ul'));
    el.appendChild(stack[0]);
  });

  runner.on('suite end', function (suite) {
    if (suite.root) {
      updateStats();
      return;
    }
    stack.shift();
  });

  runner.on('pass', function (test) {
    var url = self.testURL(test);
    var markup = '<li class="test pass %e"><h2>%e<span class="duration">%ems</span> ' +
      '<a href="%s" class="replay">‣</a></h2></li>';
    var el = fragment(markup, test.speed, test.title, test.duration, url);
    self.addCodeToggle(el, test.body);
    appendToStack(el);
    updateStats();
  });

  runner.on('fail', function (test) {
    var el = fragment('<li class="test fail"><h2>%e <a href="%e" class="replay">‣</a></h2></li>',
      test.title, self.testURL(test));
    var stackString; // Note: Includes leading newline
    var message = test.err.toString();

    // <=IE7 stringifies to [Object Error]. Since it can be overloaded, we
    // check for the result of the stringifying.
    if (message === '[object Error]') {
      message = test.err.message;
    }

    if (test.err.stack) {
      var indexOfMessage = test.err.stack.indexOf(test.err.message);
      if (indexOfMessage === -1) {
        stackString = test.err.stack;
      } else {
        stackString = test.err.stack.substr(test.err.message.length + indexOfMessage);
      }
    } else if (test.err.sourceURL && test.err.line !== undefined) {
      // Safari doesn't give you a stack. Let's at least provide a source line.
      stackString = '\n(' + test.err.sourceURL + ':' + test.err.line + ')';
    }

    stackString = stackString || '';

    if (test.err.htmlMessage && stackString) {
      el.appendChild(fragment('<div class="html-error">%s\n<pre class="error">%e</pre></div>',
        test.err.htmlMessage, stackString));
    } else if (test.err.htmlMessage) {
      el.appendChild(fragment('<div class="html-error">%s</div>', test.err.htmlMessage));
    } else {
      el.appendChild(fragment('<pre class= ...
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.html.prototype"></a>[module mocha.reporters.html.prototype](#apidoc.module.mocha.reporters.html.prototype)

#### <a name="apidoc.element.mocha.reporters.html.prototype.addCodeToggle"></a>[function <span class="apidocSignatureSpan">mocha.reporters.html.prototype.</span>addCodeToggle (el, contents)](#apidoc.element.mocha.reporters.html.prototype.addCodeToggle)
- description and source-code
```javascript
addCodeToggle = function (el, contents) {
  var h2 = el.getElementsByTagName('h2')[0];

  on(h2, 'click', function () {
    pre.style.display = pre.style.display === 'none' ? 'block' : 'none';
  });

  var pre = fragment('<pre><code>%e</code></pre>', utils.clean(contents));
  el.appendChild(pre);
  pre.style.display = 'none';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.html.prototype.suiteURL"></a>[function <span class="apidocSignatureSpan">mocha.reporters.html.prototype.</span>suiteURL (suite)](#apidoc.element.mocha.reporters.html.prototype.suiteURL)
- description and source-code
```javascript
suiteURL = function (suite) {
  return makeUrl(suite.fullTitle());
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.html.prototype.testURL"></a>[function <span class="apidocSignatureSpan">mocha.reporters.html.prototype.</span>testURL (test)](#apidoc.element.mocha.reporters.html.prototype.testURL)
- description and source-code
```javascript
testURL = function (test) {
  return makeUrl(test.fullTitle());
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.landing"></a>[module mocha.reporters.landing](#apidoc.module.mocha.reporters.landing)

#### <a name="apidoc.element.mocha.reporters.landing.landing"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>landing (runner)](#apidoc.element.mocha.reporters.landing.landing)
- description and source-code
```javascript
function Landing(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var total = runner.total;
  var stream = process.stdout;
  var plane = color('plane', '✈');
  var crashed = -1;
  var n = 0;

  function runway () {
    var buf = Array(width).join('-');
    return '  ' + color('runway', buf);
  }

  runner.on('start', function () {
    stream.write('\n\n\n  ');
    cursor.hide();
  });

  runner.on('test end', function (test) {
    // check if the plane crashed
    var col = crashed === -1 ? width * ++n / total | 0 : crashed;

    // show the crash
    if (test.state === 'failed') {
      plane = color('plane crash', '✈');
      crashed = col;
    }

    // render landing strip
    stream.write('\u001b[' + (width + 1) + 'D\u001b[2A');
    stream.write(runway());
    stream.write('\n  ');
    stream.write(color('runway', Array(col).join('⋅')));
    stream.write(plane);
    stream.write(color('runway', Array(width - col).join('⋅') + '\n'));
    stream.write(runway());
    stream.write('\u001b[0m');
  });

  runner.on('end', function () {
    cursor.show();
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.landing.super_"></a>[function <span class="apidocSignatureSpan">mocha.reporters.landing.</span>super_ (runner)](#apidoc.element.mocha.reporters.landing.super_)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.list"></a>[module mocha.reporters.list](#apidoc.module.mocha.reporters.list)

#### <a name="apidoc.element.mocha.reporters.list.list"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>list (runner)](#apidoc.element.mocha.reporters.list.list)
- description and source-code
```javascript
function List(runner) {
  Base.call(this, runner);

  var self = this;
  var n = 0;

  runner.on('start', function () {
    console.log();
  });

  runner.on('test', function (test) {
    process.stdout.write(color('pass', '    ' + test.fullTitle() + ': '));
  });

  runner.on('pending', function (test) {
    var fmt = color('checkmark', '  -') +
      color('pending', ' %s');
    console.log(fmt, test.fullTitle());
  });

  runner.on('pass', function (test) {
    var fmt = color('checkmark', '  ' + Base.symbols.ok) +
      color('pass', ' %s: ') +
      color(test.speed, '%dms');
    cursor.CR();
    console.log(fmt, test.fullTitle(), test.duration);
  });

  runner.on('fail', function (test) {
    cursor.CR();
    console.log(color('fail', '  %d) %s'), ++n, test.fullTitle());
  });

  runner.on('end', self.epilogue.bind(self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.list.super_"></a>[function <span class="apidocSignatureSpan">mocha.reporters.list.</span>super_ (runner)](#apidoc.element.mocha.reporters.list.super_)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.min"></a>[module mocha.reporters.min](#apidoc.module.mocha.reporters.min)

#### <a name="apidoc.element.mocha.reporters.min.min"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>min (runner)](#apidoc.element.mocha.reporters.min.min)
- description and source-code
```javascript
function Min(runner) {
  Base.call(this, runner);

  runner.on('start', function () {
    // clear screen
    process.stdout.write('\u001b[2J');
    // set cursor position
    process.stdout.write('\u001b[1;3H');
  });

  runner.on('end', this.epilogue.bind(this));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.min.super_"></a>[function <span class="apidocSignatureSpan">mocha.reporters.min.</span>super_ (runner)](#apidoc.element.mocha.reporters.min.super_)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.nyan"></a>[module mocha.reporters.nyan](#apidoc.module.mocha.reporters.nyan)

#### <a name="apidoc.element.mocha.reporters.nyan.nyan"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>nyan (runner)](#apidoc.element.mocha.reporters.nyan.nyan)
- description and source-code
```javascript
function NyanCat(runner) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.75 | 0;
  var nyanCatWidth = this.nyanCatWidth = 11;

  this.colorIndex = 0;
  this.numberOfLines = 4;
  this.rainbowColors = self.generateColors();
  this.scoreboardWidth = 5;
  this.tick = 0;
  this.trajectories = [[], [], [], []];
  this.trajectoryWidthMax = (width - nyanCatWidth);

  runner.on('start', function () {
    Base.cursor.hide();
    self.draw();
  });

  runner.on('pending', function () {
    self.draw();
  });

  runner.on('pass', function () {
    self.draw();
  });

  runner.on('fail', function () {
    self.draw();
  });

  runner.on('end', function () {
    Base.cursor.show();
    for (var i = 0; i < self.numberOfLines; i++) {
      write('\n');
    }
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.super_"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.</span>super_ (runner)](#apidoc.element.mocha.reporters.nyan.super_)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.nyan.prototype"></a>[module mocha.reporters.nyan.prototype](#apidoc.module.mocha.reporters.nyan.prototype)

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.appendRainbow"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>appendRainbow ()](#apidoc.element.mocha.reporters.nyan.prototype.appendRainbow)
- description and source-code
```javascript
appendRainbow = function () {
  var segment = this.tick ? '_' : '-';
  var rainbowified = this.rainbowify(segment);

  for (var index = 0; index < this.numberOfLines; index++) {
    var trajectory = this.trajectories[index];
    if (trajectory.length >= this.trajectoryWidthMax) {
      trajectory.shift();
    }
    trajectory.push(rainbowified);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.cursorDown"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>cursorDown (n)](#apidoc.element.mocha.reporters.nyan.prototype.cursorDown)
- description and source-code
```javascript
cursorDown = function (n) {
  write('\u001b[' + n + 'B');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.cursorUp"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>cursorUp (n)](#apidoc.element.mocha.reporters.nyan.prototype.cursorUp)
- description and source-code
```javascript
cursorUp = function (n) {
  write('\u001b[' + n + 'A');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.draw"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>draw ()](#apidoc.element.mocha.reporters.nyan.prototype.draw)
- description and source-code
```javascript
draw = function () {
  this.appendRainbow();
  this.drawScoreboard();
  this.drawRainbow();
  this.drawNyanCat();
  this.tick = !this.tick;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.drawNyanCat"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>drawNyanCat ()](#apidoc.element.mocha.reporters.nyan.prototype.drawNyanCat)
- description and source-code
```javascript
drawNyanCat = function () {
  var self = this;
  var startWidth = this.scoreboardWidth + this.trajectories[0].length;
  var dist = '\u001b[' + startWidth + 'C';
  var padding = '';

  write(dist);
  write('_,------,');
  write('\n');

  write(dist);
  padding = self.tick ? '  ' : '   ';
  write('_|' + padding + '/\\_/\\ ');
  write('\n');

  write(dist);
  padding = self.tick ? '_' : '__';
  var tail = self.tick ? '~' : '^';
  write(tail + '|' + padding + this.face() + ' ');
  write('\n');

  write(dist);
  padding = self.tick ? ' ' : '  ';
  write(padding + '""  "" ');
  write('\n');

  this.cursorUp(this.numberOfLines);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.drawRainbow"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>drawRainbow ()](#apidoc.element.mocha.reporters.nyan.prototype.drawRainbow)
- description and source-code
```javascript
drawRainbow = function () {
  var self = this;

  this.trajectories.forEach(function (line) {
    write('\u001b[' + self.scoreboardWidth + 'C');
    write(line.join(''));
    write('\n');
  });

  this.cursorUp(this.numberOfLines);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.drawScoreboard"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>drawScoreboard ()](#apidoc.element.mocha.reporters.nyan.prototype.drawScoreboard)
- description and source-code
```javascript
drawScoreboard = function () {
  var stats = this.stats;

  function draw (type, n) {
    write(' ');
    write(Base.color(type, n));
    write('\n');
  }

  draw('green', stats.passes);
  draw('fail', stats.failures);
  draw('pending', stats.pending);
  write('\n');

  this.cursorUp(this.numberOfLines);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.face"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>face ()](#apidoc.element.mocha.reporters.nyan.prototype.face)
- description and source-code
```javascript
face = function () {
  var stats = this.stats;
  if (stats.failures) {
    return '( x .x)';
  } else if (stats.pending) {
    return '( o .o)';
  } else if (stats.passes) {
    return '( ^ .^)';
  }
  return '( - .-)';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.generateColors"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>generateColors ()](#apidoc.element.mocha.reporters.nyan.prototype.generateColors)
- description and source-code
```javascript
generateColors = function () {
  var colors = [];

  for (var i = 0; i < (6 * 7); i++) {
    var pi3 = Math.floor(Math.PI / 3);
    var n = (i * (1.0 / 6));
    var r = Math.floor(3 * Math.sin(n) + 3);
    var g = Math.floor(3 * Math.sin(n + 2 * pi3) + 3);
    var b = Math.floor(3 * Math.sin(n + 4 * pi3) + 3);
    colors.push(36 * r + 6 * g + b + 16);
  }

  return colors;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.nyan.prototype.rainbowify"></a>[function <span class="apidocSignatureSpan">mocha.reporters.nyan.prototype.</span>rainbowify (str)](#apidoc.element.mocha.reporters.nyan.prototype.rainbowify)
- description and source-code
```javascript
rainbowify = function (str) {
  if (!Base.useColors) {
    return str;
  }
  var color = this.rainbowColors[this.colorIndex % this.rainbowColors.length];
  this.colorIndex += 1;
  return '\u001b[38;5;' + color + 'm' + str + '\u001b[0m';
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.progress"></a>[module mocha.reporters.progress](#apidoc.module.mocha.reporters.progress)

#### <a name="apidoc.element.mocha.reporters.progress.progress"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>progress (runner, options)](#apidoc.element.mocha.reporters.progress.progress)
- description and source-code
```javascript
function Progress(runner, options) {
  Base.call(this, runner);

  var self = this;
  var width = Base.window.width * 0.50 | 0;
  var total = runner.total;
  var complete = 0;
  var lastN = -1;

  // default chars
  options = options || {};
  options.open = options.open || '[';
  options.complete = options.complete || '▬';
  options.incomplete = options.incomplete || Base.symbols.dot;
  options.close = options.close || ']';
  options.verbose = false;

  // tests started
  runner.on('start', function () {
    console.log();
    cursor.hide();
  });

  // tests complete
  runner.on('test end', function () {
    complete++;

    var percent = complete / total;
    var n = width * percent | 0;
    var i = width - n;

    if (n === lastN && !options.verbose) {
      // Don't re-render the line if it hasn't changed
      return;
    }
    lastN = n;

    cursor.CR();
    process.stdout.write('\u001b[J');
    process.stdout.write(color('progress', '  ' + options.open));
    process.stdout.write(Array(n).join(options.complete));
    process.stdout.write(Array(i).join(options.incomplete));
    process.stdout.write(color('progress', options.close));
    if (options.verbose) {
      process.stdout.write(color('progress', ' ' + complete + ' of ' + total));
    }
  });

  // tests are complete, output some stats
  // and the failures if any
  runner.on('end', function () {
    cursor.show();
    console.log();
    self.epilogue();
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.progress.super_"></a>[function <span class="apidocSignatureSpan">mocha.reporters.progress.</span>super_ (runner)](#apidoc.element.mocha.reporters.progress.super_)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.spec"></a>[module mocha.reporters.spec](#apidoc.module.mocha.reporters.spec)

#### <a name="apidoc.element.mocha.reporters.spec.spec"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>spec (runner)](#apidoc.element.mocha.reporters.spec.spec)
- description and source-code
```javascript
function Spec(runner) {
  Base.call(this, runner);

  var self = this;
  var indents = 0;
  var n = 0;

  function indent () {
    return Array(indents).join('  ');
  }

  runner.on('start', function () {
    console.log();
  });

  runner.on('suite', function (suite) {
    ++indents;
    console.log(color('suite', '%s%s'), indent(), suite.title);
  });

  runner.on('suite end', function () {
    --indents;
    if (indents === 1) {
      console.log();
    }
  });

  runner.on('pending', function (test) {
    var fmt = indent() + color('pending', '  - %s');
    console.log(fmt, test.title);
  });

  runner.on('pass', function (test) {
    var fmt;
    if (test.speed === 'fast') {
      fmt = indent() +
        color('checkmark', '  ' + Base.symbols.ok) +
        color('pass', ' %s');
      console.log(fmt, test.title);
    } else {
      fmt = indent() +
        color('checkmark', '  ' + Base.symbols.ok) +
        color('pass', ' %s') +
        color(test.speed, ' (%dms)');
      console.log(fmt, test.title, test.duration);
    }
  });

  runner.on('fail', function (test) {
    console.log(indent() + color('fail', '  %d) %s'), ++n, test.title);
  });

  runner.on('end', self.epilogue.bind(self));
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.spec.super_"></a>[function <span class="apidocSignatureSpan">mocha.reporters.spec.</span>super_ (runner)](#apidoc.element.mocha.reporters.spec.super_)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.xunit"></a>[module mocha.reporters.xunit](#apidoc.module.mocha.reporters.xunit)

#### <a name="apidoc.element.mocha.reporters.xunit.xunit"></a>[function <span class="apidocSignatureSpan">mocha.reporters.</span>xunit (runner, options)](#apidoc.element.mocha.reporters.xunit.xunit)
- description and source-code
```javascript
function XUnit(runner, options) {
  Base.call(this, runner);

  var stats = this.stats;
  var tests = [];
  var self = this;

  if (options && options.reporterOptions && options.reporterOptions.output) {
    if (!fs.createWriteStream) {
      throw new Error('file output not supported in browser');
    }
    mkdirp.sync(path.dirname(options.reporterOptions.output));
    self.fileStream = fs.createWriteStream(options.reporterOptions.output);
  }

  runner.on('pending', function (test) {
    tests.push(test);
  });

  runner.on('pass', function (test) {
    tests.push(test);
  });

  runner.on('fail', function (test) {
    tests.push(test);
  });

  runner.on('end', function () {
    self.write(tag('testsuite', {
      name: 'Mocha Tests',
      tests: stats.tests,
      failures: stats.failures,
      errors: stats.failures,
      skipped: stats.tests - stats.failures - stats.passes,
      timestamp: (new Date()).toUTCString(),
      time: (stats.duration / 1000) || 0
    }, false));

    tests.forEach(function (t) {
      self.test(t);
    });

    self.write('</testsuite>');
  });
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.xunit.super_"></a>[function <span class="apidocSignatureSpan">mocha.reporters.xunit.</span>super_ (runner)](#apidoc.element.mocha.reporters.xunit.super_)
- description and source-code
```javascript
function Base(runner) {
  var stats = this.stats = { suites: 0, tests: 0, passes: 0, pending: 0, failures: 0 };
  var failures = this.failures = [];

  if (!runner) {
    return;
  }
  this.runner = runner;

  runner.stats = stats;

  runner.on('start', function () {
    stats.start = new Date();
  });

  runner.on('suite', function (suite) {
    stats.suites = stats.suites || 0;
    suite.root || stats.suites++;
  });

  runner.on('test end', function () {
    stats.tests = stats.tests || 0;
    stats.tests++;
  });

  runner.on('pass', function (test) {
    stats.passes = stats.passes || 0;

    if (test.duration > test.slow()) {
      test.speed = 'slow';
    } else if (test.duration > test.slow() / 2) {
      test.speed = 'medium';
    } else {
      test.speed = 'fast';
    }

    stats.passes++;
  });

  runner.on('fail', function (test, err) {
    stats.failures = stats.failures || 0;
    stats.failures++;
    test.err = err;
    failures.push(test);
  });

  runner.on('end', function () {
    stats.end = new Date();
    stats.duration = new Date() - stats.start;
  });

  runner.on('pending', function () {
    stats.pending++;
  });
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.reporters.xunit.prototype"></a>[module mocha.reporters.xunit.prototype](#apidoc.module.mocha.reporters.xunit.prototype)

#### <a name="apidoc.element.mocha.reporters.xunit.prototype.done"></a>[function <span class="apidocSignatureSpan">mocha.reporters.xunit.prototype.</span>done (failures, fn)](#apidoc.element.mocha.reporters.xunit.prototype.done)
- description and source-code
```javascript
done = function (failures, fn) {
  if (this.fileStream) {
    this.fileStream.end(function () {
      fn(failures);
    });
  } else {
    fn(failures);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.xunit.prototype.test"></a>[function <span class="apidocSignatureSpan">mocha.reporters.xunit.prototype.</span>test (test)](#apidoc.element.mocha.reporters.xunit.prototype.test)
- description and source-code
```javascript
test = function (test) {
  var attrs = {
    classname: test.parent.fullTitle(),
    name: test.title,
    time: (test.duration / 1000) || 0
  };

  if (test.state === 'failed') {
    var err = test.err;
    this.write(tag('testcase', attrs, false, tag('failure', {}, false, escape(err.message) + '\n' + escape(err.stack))));
  } else if (test.isPending()) {
    this.write(tag('testcase', attrs, false, tag('skipped', {}, true)));
  } else {
    this.write(tag('testcase', attrs, true));
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.reporters.xunit.prototype.write"></a>[function <span class="apidocSignatureSpan">mocha.reporters.xunit.prototype.</span>write (line)](#apidoc.element.mocha.reporters.xunit.prototype.write)
- description and source-code
```javascript
write = function (line) {
  if (this.fileStream) {
    this.fileStream.write(line + '\n');
  } else if (typeof process === 'object' && process.stdout) {
    process.stdout.write(line + '\n');
  } else {
    console.log(line);
  }
}
```
- example usage
```shell
n/a
```



# <a name="apidoc.module.mocha.utils"></a>[module mocha.utils](#apidoc.module.mocha.utils)

#### <a name="apidoc.element.mocha.utils.canonicalize"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>canonicalize (value, stack, typeHint)](#apidoc.element.mocha.utils.canonicalize)
- description and source-code
```javascript
function canonicalize(value, stack, typeHint) {
  var canonicalizedObj;
<span class="apidocCodeCommentSpan">  /* eslint-disable no-unused-vars */
</span>  var prop;
  /* eslint-enable no-unused-vars */
  typeHint = typeHint || type(value);
  function withStack (value, fn) {
    stack.push(value);
    fn();
    stack.pop();
  }

  stack = stack || [];

  if (indexOf(stack, value) !== -1) {
    return '[Circular]';
  }

  switch (typeHint) {
    case 'undefined':
    case 'buffer':
    case 'null':
      canonicalizedObj = value;
      break;
    case 'array':
      withStack(value, function () {
        canonicalizedObj = exports.map(value, function (item) {
          return exports.canonicalize(item, stack);
        });
      });
      break;
    case 'function':
      /* eslint-disable guard-for-in */
      for (prop in value) {
        canonicalizedObj = {};
        break;
      }
      /* eslint-enable guard-for-in */
      if (!canonicalizedObj) {
        canonicalizedObj = emptyRepresentation(value, typeHint);
        break;
      }
    /* falls through */
    case 'object':
      canonicalizedObj = canonicalizedObj || {};
      withStack(value, function () {
        exports.forEach(exports.keys(value).sort(), function (key) {
          canonicalizedObj[key] = exports.canonicalize(value[key], stack);
        });
      });
      break;
    case 'date':
    case 'number':
    case 'regexp':
    case 'boolean':
    case 'symbol':
      canonicalizedObj = value;
      break;
    default:
      canonicalizedObj = value + '';
  }

  return canonicalizedObj;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.clean"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>clean (str)](#apidoc.element.mocha.utils.clean)
- description and source-code
```javascript
clean = function (str) {
  str = str
    .replace(/\r\n?|[\n\u2028\u2029]/g, '\n').replace(/^\uFEFF/, '')
    // (traditional)->  space/name     parameters    body     (lambda)-> parameters       body   multi-statement/single
keep body content
    .replace(/^function(?:\s*|\s+[^(]*)\([^)]*\)\s*\{((?:.|\n)*?)\s*\}$|^\([^)]*\)\s*=>\s*(?:\{((?:.|\n)*?)\s*\}|((?:.|\n)*))$/, '$
1$2$3');

  var spaces = str.match(/^\n?( *)/)[1].length;
  var tabs = str.match(/^\n?(\t*)/)[1].length;
  var re = new RegExp('^\n?' + (tabs ? '\t' : ' ') + '{' + (tabs || spaces) + '}', 'gm');

  str = str.replace(re, '');

  return exports.trim(str);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.escape"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>escape (html)](#apidoc.element.mocha.utils.escape)
- description and source-code
```javascript
escape = function (html) {
  return String(html)
    .replace(/&/g, '&amp;')
    .replace(/"/g, '&quot;')
    .replace(/</g, '&lt;')
    .replace(/>/g, '&gt;');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.files"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>files (dir, ext, ret)](#apidoc.element.mocha.utils.files)
- description and source-code
```javascript
files = function (dir, ext, ret) {
  ret = ret || [];
  ext = ext || ['js'];

  var re = new RegExp('\\.(' + ext.join('|') + ')$');

  readdirSync(dir)
    .filter(ignored)
    .forEach(function (path) {
      path = join(dir, path);
      if (lstatSync(path).isDirectory()) {
        exports.files(path, ext, ret);
      } else if (path.match(re)) {
        ret.push(path);
      }
    });

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.filter"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>filter (arr, fn)](#apidoc.element.mocha.utils.filter)
- description and source-code
```javascript
filter = function (arr, fn) {
  var ret = [];

  for (var i = 0, l = arr.length; i < l; i++) {
    var val = arr[i];
    if (fn(val, i, arr)) {
      ret.push(val);
    }
  }

  return ret;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.forEach"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>forEach (arr, fn, scope)](#apidoc.element.mocha.utils.forEach)
- description and source-code
```javascript
forEach = function (arr, fn, scope) {
  for (var i = 0, l = arr.length; i < l; i++) {
    fn.call(scope, arr[i], i);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.getError"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>getError (err)](#apidoc.element.mocha.utils.getError)
- description and source-code
```javascript
getError = function (err) {
  return err || exports.undefinedError();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.highlightTags"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>highlightTags (name)](#apidoc.element.mocha.utils.highlightTags)
- description and source-code
```javascript
highlightTags = function (name) {
  var code = document.getElementById('mocha').getElementsByTagName(name);
  for (var i = 0, len = code.length; i < len; ++i) {
    code[i].innerHTML = highlight(code[i].innerHTML);
  }
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.indexOf"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>indexOf (arr, obj, start)](#apidoc.element.mocha.utils.indexOf)
- description and source-code
```javascript
indexOf = function (arr, obj, start) {
  for (var i = start || 0, l = arr.length; i < l; i++) {
    if (arr[i] === obj) {
      return i;
    }
  }
  return -1;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.inherits"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>inherits (ctor, superCtor)](#apidoc.element.mocha.utils.inherits)
- description and source-code
```javascript
inherits = function (ctor, superCtor) {

  if (ctor === undefined || ctor === null)
    throw new TypeError('The constructor to "inherits" must not be ' +
                        'null or undefined');

  if (superCtor === undefined || superCtor === null)
    throw new TypeError('The super constructor to "inherits" must not ' +
                        'be null or undefined');

  if (superCtor.prototype === undefined)
    throw new TypeError('The super constructor to "inherits" must ' +
                        'have a prototype');

  ctor.super_ = superCtor;
  Object.setPrototypeOf(ctor.prototype, superCtor.prototype);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.isArray"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>isArray ()](#apidoc.element.mocha.utils.isArray)
- description and source-code
```javascript
function isArray() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.isBuffer"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>isBuffer (value)](#apidoc.element.mocha.utils.isBuffer)
- description and source-code
```javascript
isBuffer = function (value) {
  return typeof Buffer !== 'undefined' && Buffer.isBuffer(value);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.isPromise"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>isPromise (value)](#apidoc.element.mocha.utils.isPromise)
- description and source-code
```javascript
function isPromise(value) {
  return typeof value === 'object' && typeof value.then === 'function';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.isString"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>isString (obj)](#apidoc.element.mocha.utils.isString)
- description and source-code
```javascript
isString = function (obj) {
  return typeof obj === 'string';
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.keys"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>keys ()](#apidoc.element.mocha.utils.keys)
- description and source-code
```javascript
function keys() { [native code] }
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.lookupFiles"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>lookupFiles (path, extensions, recursive)](#apidoc.element.mocha.utils.lookupFiles)
- description and source-code
```javascript
function lookupFiles(path, extensions, recursive) {
  var files = [];
  var re = new RegExp('\\.(' + extensions.join('|') + ')$');

  if (!exists(path)) {
    if (exists(path + '.js')) {
      path += '.js';
    } else {
      files = glob.sync(path);
      if (!files.length) {
        throw new Error("cannot resolve path (or pattern) '" + path + "'");
      }
      return files;
    }
  }

  try {
    var stat = statSync(path);
    if (stat.isFile()) {
      return path;
    }
  } catch (err) {
    // ignore error
    return;
  }

  readdirSync(path).forEach(function (file) {
    file = join(path, file);
    try {
      var stat = statSync(file);
      if (stat.isDirectory()) {
        if (recursive) {
          files = files.concat(lookupFiles(file, extensions, recursive));
        }
        return;
      }
    } catch (err) {
      // ignore error
      return;
    }
    if (!stat.isFile() || !re.test(file) || basename(file)[0] === '.') {
      return;
    }
    files.push(file);
  });

  return files;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.map"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>map (arr, fn, scope)](#apidoc.element.mocha.utils.map)
- description and source-code
```javascript
map = function (arr, fn, scope) {
  var result = [];
  for (var i = 0, l = arr.length; i < l; i++) {
    result.push(fn.call(scope, arr[i], i, arr));
  }
  return result;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.noop"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>noop ()](#apidoc.element.mocha.utils.noop)
- description and source-code
```javascript
noop = function () {}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.parseQuery"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>parseQuery (qs)](#apidoc.element.mocha.utils.parseQuery)
- description and source-code
```javascript
parseQuery = function (qs) {
  return reduce(qs.replace('?', '').split('&'), function (obj, pair) {
    var i = pair.indexOf('=');
    var key = pair.slice(0, i);
    var val = pair.slice(++i);

    obj[key] = decodeURIComponent(val);
    return obj;
  }, {});
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.reduce"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>reduce (arr, fn, val)](#apidoc.element.mocha.utils.reduce)
- description and source-code
```javascript
reduce = function (arr, fn, val) {
  var rval = val;

  for (var i = 0, l = arr.length; i < l; i++) {
    rval = fn(rval, arr[i], i, arr);
  }

  return rval;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.slug"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>slug (str)](#apidoc.element.mocha.utils.slug)
- description and source-code
```javascript
slug = function (str) {
  return str
    .toLowerCase()
    .replace(/ +/g, '-')
    .replace(/[^-\w]/g, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.some"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>some (arr, fn)](#apidoc.element.mocha.utils.some)
- description and source-code
```javascript
some = function (arr, fn) {
  for (var i = 0, l = arr.length; i < l; i++) {
    if (fn(arr[i])) {
      return true;
    }
  }
  return false;
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.stackTraceFilter"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>stackTraceFilter ()](#apidoc.element.mocha.utils.stackTraceFilter)
- description and source-code
```javascript
stackTraceFilter = function () {
  // TODO: Replace with 'process.browser'
  var is = typeof document === 'undefined' ? { node: true } : { browser: true };
  var slash = path.sep;
  var cwd;
  if (is.node) {
    cwd = process.cwd() + slash;
  } else {
    cwd = (typeof location === 'undefined' ? window.location : location).href.replace(/\/[^\/]*$/, '/');
    slash = '/';
  }

  function isMochaInternal (line) {
    return (~line.indexOf('node_modules' + slash + 'mocha' + slash)) ||
      (~line.indexOf('node_modules' + slash + 'mocha.js')) ||
      (~line.indexOf('bower_components' + slash + 'mocha.js')) ||
      (~line.indexOf(slash + 'mocha.js'));
  }

  function isNodeInternal (line) {
    return (~line.indexOf('(timers.js:')) ||
      (~line.indexOf('(events.js:')) ||
      (~line.indexOf('(node.js:')) ||
      (~line.indexOf('(module.js:')) ||
      (~line.indexOf('GeneratorFunctionPrototype.next (native)')) ||
      false;
  }

  return function (stack) {
    stack = stack.split('\n');

    stack = reduce(stack, function (list, line) {
      if (isMochaInternal(line)) {
        return list;
      }

      if (is.node && isNodeInternal(line)) {
        return list;
      }

      // Clean up cwd(absolute)
      if (/\(?.+:\d+:\d+\)?$/.test(line)) {
        line = line.replace(cwd, '');
      }

      list.push(line);
      return list;
    }, []);

    return stack.join('\n');
  };
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.stringify"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>stringify (value)](#apidoc.element.mocha.utils.stringify)
- description and source-code
```javascript
stringify = function (value) {
  var typeHint = type(value);

  if (!~indexOf(['object', 'array', 'function'], typeHint)) {
    if (typeHint === 'buffer') {
      var json = value.toJSON();
      // Based on the toJSON result
      return jsonStringify(json.data && json.type ? json.data : json, 2)
        .replace(/,(\n|$)/g, '$1');
    }

    // IE7/IE8 has a bizarre String constructor; needs to be coerced
    // into an array and back to obj.
    if (typeHint === 'string' && typeof value === 'object') {
      value = reduce(value.split(''), function (acc, char, idx) {
        acc[idx] = char;
        return acc;
      }, {});
      typeHint = 'object';
    } else {
      return jsonStringify(value);
    }
  }

  for (var prop in value) {
    if (Object.prototype.hasOwnProperty.call(value, prop)) {
      return jsonStringify(exports.canonicalize(value, null, typeHint), 2).replace(/,(\n|$)/g, '$1');
    }
  }

  return emptyRepresentation(value, typeHint);
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.trim"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>trim (str)](#apidoc.element.mocha.utils.trim)
- description and source-code
```javascript
trim = function (str) {
  return str.replace(/^\s+|\s+$/g, '');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.type"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>type (value)](#apidoc.element.mocha.utils.type)
- description and source-code
```javascript
function type(value) {
  if (value === undefined) {
    return 'undefined';
  } else if (value === null) {
    return 'null';
  } else if (typeof Buffer !== 'undefined' && Buffer.isBuffer(value)) {
    return 'buffer';
  }
  return Object.prototype.toString.call(value)
    .replace(/^\[.+\s(.+?)\]$/, '$1')
    .toLowerCase();
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.undefinedError"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>undefinedError ()](#apidoc.element.mocha.utils.undefinedError)
- description and source-code
```javascript
undefinedError = function () {
  return new Error('Caught undefined error, did you throw without specifying what?');
}
```
- example usage
```shell
n/a
```

#### <a name="apidoc.element.mocha.utils.watch"></a>[function <span class="apidocSignatureSpan">mocha.utils.</span>watch (files, fn)](#apidoc.element.mocha.utils.watch)
- description and source-code
```javascript
watch = function (files, fn) {
  var options = { interval: 100 };
  files.forEach(function (file) {
    debug('file %s', file);
    watchFile(file, options, function (curr, prev) {
      if (prev.mtime < curr.mtime) {
        fn(file);
      }
    });
  });
}
```
- example usage
```shell
n/a
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
