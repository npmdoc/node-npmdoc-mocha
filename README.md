# npmdoc-mocha

#### basic api documentation for  [mocha (v3.3.0)](https://mochajs.org)  [![npm package](https://img.shields.io/npm/v/npmdoc-mocha.svg?style=flat-square)](https://www.npmjs.org/package/npmdoc-mocha) [![travis-ci.org build-status](https://api.travis-ci.org/npmdoc/node-npmdoc-mocha.svg)](https://travis-ci.org/npmdoc/node-npmdoc-mocha)

#### simple, flexible, fun test framework

[![NPM](https://nodei.co/npm/mocha.png?downloads=true&downloadRank=true&stars=true)](https://www.npmjs.com/package/mocha)

- [https://npmdoc.github.io/node-npmdoc-mocha/build/apidoc.html](https://npmdoc.github.io/node-npmdoc-mocha/build/apidoc.html)

[![apidoc](https://npmdoc.github.io/node-npmdoc-mocha/build/screenCapture.buildCi.browser.%252Ftmp%252Fbuild%252Fapidoc.html.png)](https://npmdoc.github.io/node-npmdoc-mocha/build/apidoc.html)

![npmPackageListing](https://npmdoc.github.io/node-npmdoc-mocha/build/screenCapture.npmPackageListing.svg)

![npmPackageDependencyTree](https://npmdoc.github.io/node-npmdoc-mocha/build/screenCapture.npmPackageDependencyTree.svg)



# package.json

```json

{
    "author": {
        "name": "TJ Holowaychuk"
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
            "url": "https://github.com/ahamid"
        },
        {
            "name": "Aaron Heckmann",
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
            "url": "https://github.com/thedark1337"
        },
        {
            "name": "amsul",
            "url": "https://github.com/amsul"
        },
        {
            "name": "Andreas Brekken",
            "url": "https://github.com/abrkn"
        },
        {
            "name": "Andreas Lind",
            "url": "https://github.com/papandreou"
        },
        {
            "name": "Andrew Miller",
            "url": "https://github.com/vnikiti"
        },
        {
            "name": "Andrew Nesbitt",
            "url": "https://github.com/andrew"
        },
        {
            "name": "Andrey Popp",
            "url": "https://github.com/andreypopp"
        },
        {
            "name": "Andrii Shumada",
            "url": "https://github.com/eagleeye"
        },
        {
            "name": "Anis Safine",
            "url": "https://github.com/anis"
        },
        {
            "name": "Arian Stolwijk",
            "url": "https://github.com/arian"
        },
        {
            "name": "Ariel Mashraki",
            "url": "https://github.com/a8m"
        },
        {
            "name": "Arnaud Brousseau",
            "url": "https://github.com/ArnaudBrousseau"
        },
        {
            "name": "Atsuya Takagi",
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
            "url": "https://github.com/berkerpeksag"
        },
        {
            "name": "Bjørge Næss",
            "url": "https://github.com/bjoerge"
        },
        {
            "name": "Brendan Nee",
            "url": "https://github.com/brendannee"
        },
        {
            "name": "Brian Beck",
            "url": "https://github.com/exogen"
        },
        {
            "name": "Brian C",
            "url": "https://github.com/brianc"
        },
        {
            "name": "Brian Lalor",
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
            "url": "https://github.com/cscott"
        },
        {
            "name": "Casey Foster",
            "url": "https://github.com/caseywebdev"
        },
        {
            "name": "Charles Lowell",
            "url": "https://github.com/cowboyd"
        },
        {
            "name": "Chris Buckley",
            "url": "https://github.com/cmbuckley"
        },
        {
            "name": "Christopher Hiller",
            "url": "https://github.com/boneskull"
        },
        {
            "name": "Chris Wren",
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
            "url": "https://github.com/danielstjules"
        },
        {
            "name": "Daniel Stockman",
            "url": "https://github.com/evocateur"
        },
        {
            "name": "Dave McKenna",
            "url": "https://github.com/davemckenna01"
        },
        {
            "name": "David da Silva",
            "url": "https://github.com/dasilvacontin"
        },
        {
            "name": "David Henderson",
            "url": "https://github.com/dhendo"
        },
        {
            "name": "Denis Bardadym",
            "url": "https://github.com/btd"
        },
        {
            "name": "Devin Weaver",
            "url": "https://github.com/sukima"
        },
        {
            "name": "Diogo Monteiro",
            "url": "https://github.com/diogogmt"
        },
        {
            "name": "Dmitry Shirokov",
            "url": "https://github.com/runk"
        },
        {
            "name": "Domenic Denicola",
            "url": "https://github.com/domenic"
        },
        {
            "name": "Dominic Barnes",
            "url": "https://github.com/dominicbarnes"
        },
        {
            "name": "domq",
            "url": "https://github.com/domq"
        },
        {
            "name": "Douglas Wilson",
            "url": "https://github.com/dougwilson"
        },
        {
            "name": "Duncan Beevers",
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
            "url": "https://github.com/piuccio"
        },
        {
            "name": "Fede Ramirez",
            "url": "https://github.com/2fd"
        },
        {
            "name": "Fedor Indutny",
            "url": "https://github.com/indutny"
        },
        {
            "name": "fengmk2",
            "url": "https://github.com/fengmk2"
        },
        {
            "name": "Florian Margaine",
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
            "url": "https://github.com/gaye"
        },
        {
            "name": "Gavin Mogan",
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
            "url": "https://github.com/curvedmark"
        },
        {
            "name": "Glen Mailer",
            "url": "https://github.com/glenjamin"
        },
        {
            "name": "Greg Perkins",
            "url": "https://github.com/gregrperkins"
        },
        {
            "name": "Guillermo Rauch",
            "url": "https://github.com/rauchg"
        },
        {
            "name": "Guy Arye",
            "url": "https://github.com/aryeguy"
        },
        {
            "name": "Gyandeep Singh",
            "url": "https://github.com/gyandeeps"
        },
        {
            "name": "Harish",
            "url": "https://github.com/hyeluri"
        },
        {
            "name": "Harry Brundage",
            "url": "https://github.com/airhorns"
        },
        {
            "name": "Ian Remmel",
            "url": "https://github.com/ianwremmel"
        },
        {
            "name": "Ian Storm Taylor",
            "url": "https://github.com/ianstormtaylor"
        },
        {
            "name": "Ian Young",
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
            "url": "https://github.com/startswithaj"
        },
        {
            "name": "Jake Verbaten",
            "url": "https://github.com/Raynos"
        },
        {
            "name": "Jakub Nešetřil",
            "url": "https://github.com/zzen"
        },
        {
            "name": "James Bowes",
            "url": "https://github.com/jbowes"
        },
        {
            "name": "James Carr",
            "url": "https://github.com/jamescarr"
        },
        {
            "name": "James G. Kim",
            "url": "https://github.com/jgkim"
        },
        {
            "name": "James Lal",
            "url": "https://github.com/lightsofapollo"
        },
        {
            "name": "James Nylen",
            "url": "https://github.com/nylen"
        },
        {
            "name": "Jason",
            "url": "https://github.com/jlai"
        },
        {
            "name": "Jason Barry",
            "url": "https://github.com/JCBarry"
        },
        {
            "name": "Javier Aranda",
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
            "url": "https://github.com/jschilli"
        },
        {
            "name": "JeongHoon Byun",
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
            "url": "https://github.com/joeycozza"
        },
        {
            "name": "Johnathon Sanders",
            "url": "https://github.com/outdooricon"
        },
        {
            "name": "John Doty",
            "url": "https://github.com/jrhdoty"
        },
        {
            "name": "John Firebaugh",
            "url": "https://github.com/jfirebaugh"
        },
        {
            "name": "John Reeves",
            "url": "https://github.com/jonnyreeves"
        },
        {
            "name": "Jo Liss",
            "url": "https://github.com/joliss"
        },
        {
            "name": "Jonas Dohse",
            "url": "https://github.com/dohse"
        },
        {
            "name": "Jonathan Kim",
            "url": "https://github.com/jkimbo"
        },
        {
            "name": "Jonathan Park",
            "url": "https://github.com/park9140"
        },
        {
            "name": "jongleberry",
            "url": "https://github.com/jonathanong"
        },
        {
            "name": "Jordan Sexton",
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
            "url": "https://github.com/jbnicolai"
        },
        {
            "name": "Joshua Krall",
            "url": "https://github.com/jkrall"
        },
        {
            "name": "João Moreno",
            "url": "https://github.com/joaomoreno"
        },
        {
            "name": "João Paulo Bochi",
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
            "url": "https://github.com/jvirtanen"
        },
        {
            "name": "Justin DuJardin",
            "url": "https://github.com/justindujardin"
        },
        {
            "name": "Juzer Ali",
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
            "url": "https://github.com/kentcdodds"
        },
        {
            "name": "Kevin Burke",
            "url": "https://github.com/kevinburke"
        },
        {
            "name": "Kevin Conway",
            "url": "https://github.com/kevinconway"
        },
        {
            "name": "Kevin Kirsche",
            "url": "https://github.com/kkirsche"
        },
        {
            "name": "Kirill Korolyov",
            "url": "https://github.com/Dremora"
        },
        {
            "name": "Koen Punt",
            "url": "https://github.com/koenpunt"
        },
        {
            "name": "Konstantin Käfer",
            "url": "https://github.com/kkaefer"
        },
        {
            "name": "Kris Rasmussen",
            "url": "https://github.com/krisr"
        },
        {
            "name": "Kyle Mitchell",
            "url": "https://github.com/kemitchell"
        },
        {
            "name": "lakmeer",
            "url": "https://github.com/lakmeer"
        },
        {
            "name": "Liam Newman",
            "url": "https://github.com/bitwiseman"
        },
        {
            "name": "Linus Unnebäck",
            "url": "https://github.com/LinusU"
        },
        {
            "name": "Long Ho",
            "url": "https://github.com/longlho"
        },
        {
            "name": "László Bácsi",
            "url": "https://github.com/lackac"
        },
        {
            "name": "Maciej Małecki",
            "url": "https://github.com/mmalecki"
        },
        {
            "name": "Mal Graty",
            "url": "https://github.com/mal"
        },
        {
            "name": "Marcello Bastéa-Forte",
            "url": "https://github.com/marcello3d"
        },
        {
            "name": "Marc Kuo",
            "url": "https://github.com/mck-"
        },
        {
            "name": "Mark Banner",
            "url": "https://github.com/Standard8"
        },
        {
            "name": "Matija Marohnić",
            "url": "https://github.com/silvenon"
        },
        {
            "name": "Matthew Shanley",
            "url": "https://github.com/arkadyan"
        },
        {
            "name": "mattias-lw",
            "url": "https://github.com/mattias-lw"
        },
        {
            "name": "Matt Robenolt",
            "url": "https://github.com/mattrobenolt"
        },
        {
            "name": "Matt Smith",
            "url": "https://github.com/twobitfool"
        },
        {
            "name": "Max Goodman",
            "url": "https://github.com/chromakode"
        },
        {
            "name": "Maximilian Antoni",
            "url": "https://github.com/mantoni"
        },
        {
            "name": "Merrick Christensen",
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
            "url": "https://github.com/mjackson"
        },
        {
            "name": "Michael Schoonmaker",
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
            "url": "https://github.com/mislav"
        },
        {
            "name": "mrShturman",
            "url": "https://github.com/mrShturman"
        },
        {
            "name": "Nathan Alderson",
            "url": "https://github.com/nathanalderson"
        },
        {
            "name": "Nathan Black",
            "url": "https://github.com/nathanboktae"
        },
        {
            "name": "Nathan Bowser",
            "url": "https://github.com/nathanbowser"
        },
        {
            "name": "Nathan Houle",
            "url": "https://github.com/ndhoule"
        },
        {
            "name": "Nathan Rajlich",
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
            "url": "https://github.com/noshir-patel"
        },
        {
            "name": "OlegTsyba",
            "url": "https://github.com/OlegTsyba"
        },
        {
            "name": "omar",
            "url": "https://github.com/omardelarosa"
        },
        {
            "name": "Panu Horsmalahti",
            "url": "https://github.com/panuhorsmalahti"
        },
        {
            "name": "Parker Moore",
            "url": "https://github.com/parkr"
        },
        {
            "name": "Paul Armstrong",
            "url": "https://github.com/paularmstrong"
        },
        {
            "name": "Paul Miller",
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
            "url": "https://github.com/psung"
        },
        {
            "name": "Prayag Verma",
            "url": "https://github.com/pra85"
        },
        {
            "name": "qiu zuhui",
            "url": "https://github.com/qiuzuhui"
        },
        {
            "name": "Quang Van",
            "url": "https://github.com/quangv"
        },
        {
            "name": "Rauno",
            "url": "https://github.com/Rauno56"
        },
        {
            "name": "Refael Ackermann",
            "url": "https://github.com/refack"
        },
        {
            "name": "Richard Dingwall",
            "url": "https://github.com/rdingwall"
        },
        {
            "name": "Richard Knop",
            "url": "https://github.com/RichardKnop"
        },
        {
            "name": "Rico Sta. Cruz",
            "url": "https://github.com/rstacruz"
        },
        {
            "name": "Robert Rossmann",
            "url": "https://github.com/Alaneor"
        },
        {
            "name": "Rob Wu",
            "url": "https://github.com/Rob--W"
        },
        {
            "name": "Romain",
            "url": "https://github.com/rprieto"
        },
        {
            "name": "Roman Neuhauser",
            "url": "https://github.com/roman-neuhauser"
        },
        {
            "name": "Roman Shtylman",
            "url": "https://github.com/defunctzombie"
        },
        {
            "name": "Russ Bradberry",
            "url": "https://github.com/devdazed"
        },
        {
            "name": "Russell Munson",
            "url": "https://github.com/rmunson"
        },
        {
            "name": "Rustem Mustafin",
            "url": "https://github.com/rulikkk"
        },
        {
            "name": "Ryan",
            "url": "https://github.com/ryan-shaw"
        },
        {
            "name": "Ryan Hubbard",
            "url": "https://github.com/ryedog"
        },
        {
            "name": "Ryunosuke Sato",
            "url": "https://github.com/tricknotes"
        },
        {
            "name": "ryym",
            "url": "https://github.com/ryym"
        },
        {
            "name": "Salehen Shovon Rahman",
            "url": "https://github.com/shovon"
        },
        {
            "name": "Salvador de la Puente González",
            "url": "https://github.com/delapuente"
        },
        {
            "name": "Sam Mussell",
            "url": "https://github.com/smussell"
        },
        {
            "name": "Samuel Goldszmidt",
            "url": "https://github.com/ouhouhsami"
        },
        {
            "name": "Sasha Koss",
            "url": "https://github.com/kossnocorp"
        },
        {
            "name": "Scott Santucci",
            "url": "https://github.com/ScottFreeCode"
        },
        {
            "name": "Sean Lang",
            "url": "https://github.com/slang800"
        },
        {
            "name": "seb vincent",
            "url": "https://github.com/sebv"
        },
        {
            "name": "Seiya Konno",
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
            "url": "https://github.com/sindresorhus"
        },
        {
            "name": "slientcloud",
            "url": "https://github.com/silentcloud"
        },
        {
            "name": "Sorin Iclanzan",
            "url": "https://github.com/iclanzan"
        },
        {
            "name": "Standa Opichal",
            "url": "https://github.com/opichals"
        },
        {
            "name": "Stephen Mathieson",
            "url": "https://github.com/stephenmathieson"
        },
        {
            "name": "Steve Mason",
            "url": "https://github.com/spmason"
        },
        {
            "name": "Stewart Taylor",
            "url": "https://github.com/Stewart-Taylor"
        },
        {
            "name": "Sune Simonsen",
            "url": "https://github.com/sunesimonsen"
        },
        {
            "name": "Sylvain Faucherand",
            "url": "https://github.com/slyg"
        },
        {
            "name": "Takuya Nishigori",
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
            "url": "https://github.com/graingert"
        },
        {
            "name": "Tim Ehat",
            "url": "https://github.com/timehat"
        },
        {
            "name": "Timothy Gu",
            "url": "https://github.com/TimothyGu"
        },
        {
            "name": "Timo Tijhof",
            "url": "https://github.com/Krinkle"
        },
        {
            "name": "Tingan Ho",
            "url": "https://github.com/tinganho"
        },
        {
            "name": "TJ Holowaychuk",
            "url": "https://github.com/tj"
        },
        {
            "name": "Tobias Bieniek",
            "url": "https://github.com/Turbo87"
        },
        {
            "name": "Toby Ho",
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
            "url": "https://github.com/travisjeffery"
        },
        {
            "name": "Tyson Tate",
            "url": "https://github.com/tysontate"
        },
        {
            "name": "Valentin Agachi",
            "url": "https://github.com/avaly"
        },
        {
            "name": "Victor Costan",
            "url": "https://github.com/pwnall"
        },
        {
            "name": "Vladimir Chernis",
            "url": "https://github.com/vlazzle"
        },
        {
            "name": "Vlad Magdalin",
            "url": "https://github.com/callmevlad"
        },
        {
            "name": "Will Langstroth",
            "url": "https://github.com/wlangstroth"
        },
        {
            "name": "Wil Moore III",
            "url": "https://github.com/wilmoore"
        },
        {
            "name": "Xavier Antoviaque",
            "url": "https://github.com/antoviaque"
        },
        {
            "name": "Xavier Damman",
            "url": "https://github.com/xdamman"
        },
        {
            "name": "Yanis Wang",
            "url": "https://github.com/yaniswang"
        },
        {
            "name": "yuitest",
            "url": "https://github.com/yuitest"
        },
        {
            "name": "Zhiye Li",
            "url": "https://github.com/zhiyelee"
        },
        {
            "name": "Zhouxuan Yang",
            "url": "https://github.com/fool2fish"
        },
        {
            "name": "Zsolt Takács",
            "url": "https://github.com/oker1"
        }
    ],
    "dependencies": {
        "browser-stdout": "1.3.0",
        "commander": "2.9.0",
        "debug": "2.6.0",
        "diff": "3.2.0",
        "escape-string-regexp": "1.0.5",
        "glob": "7.1.1",
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
        "coveralls": "^2.11.15",
        "expect.js": "^0.3.1",
        "istanbul-combine": "^0.3.0",
        "karma": "1.3.0",
        "karma-browserify": "^5.0.5",
        "karma-chrome-launcher": "^2.0.0",
        "karma-expect": "^1.1.2",
        "karma-mocha": "^1.3.0",
        "karma-phantomjs-launcher": "^1.0.2",
        "karma-sauce-launcher": "github:coderbyheart/karma-sauce-launcher",
        "karma-spec-reporter": "0.0.26",
        "nyc": "^10.0.0",
        "os-name": "^2.0.1",
        "phantomjs": "1.9.8",
        "rimraf": "^2.5.2",
        "semistandard": "^9.2.1",
        "should": "^11.1.1",
        "through2": "^2.0.1",
        "watchify": "^3.7.0"
    },
    "directories": {},
    "dist": {
        "shasum": "d29b7428d3f52c82e2e65df1ecb7064e1aabbfb5",
        "tarball": "https://registry.npmjs.org/mocha/-/mocha-3.3.0.tgz"
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
    "gitHead": "fb1687ec16e8ae347ca4498560f984e575224d59",
    "greenkeeper": {
        "ignore": [
            "phantomjs",
            "lodash.create"
        ]
    },
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
            "name": "boneskull"
        },
        {
            "name": "dasilvacontin"
        },
        {
            "name": "munter"
        }
    ],
    "name": "mocha",
    "optionalDependencies": {},
    "repository": {
        "type": "git",
        "url": "git+https://github.com/mochajs/mocha.git"
    },
    "scripts": {
        "coverage": "COVERAGE=true npm run test",
        "postcoverage": "istanbul-combine -d coverage -r lcov -r html coverage/reports/*/*.json",
        "precoverage": "rm -rf coverage",
        "preversion": "make test && make mocha.js && git add mocha.js",
        "test": "make test && make clean"
    },
    "semistandard": {
        "ignore": [
            "/mocha.js",
            "/lib/to-iso-string/**/*.js"
        ]
    },
    "version": "3.3.0"
}
```



# misc
- this document was created with [utility2](https://github.com/kaizhu256/node-utility2)
