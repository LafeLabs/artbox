# Geometron 5


## Use cases for symbols

- Use a symbol in a page(illustrate a scroll)
- use a symbol in a map
     - arrow points to a thing on a geographic map
     - arrow points to a thing in a photo
     - graph theory combining math and arrows
     - memes that put symbols on top of photographs
     - symbols to make pages in decks, to compete with PowerPoint
     - symbol which represents a map or page used as a symbol in a link to that map or page
- copy/paste a symbol into something using png
- create a specialized figure in a iframe in a jupyter notebook(quantum gates, circuits)
- embed a png image into a Jupyter notebook
- create an icon for general use in web pages, such as a link or button
- create a "general use" vector graphic file of arbitrary size and shape, which can be edited by other Geometron instances and contains the Shape Table and Font as needed
- create and publish a font
- create and publish a shape table
- create a tutorial which teaches the whole Geometron system, and includes figures from geometron as well as spelled glyphs using Geometron symbols
- create symbols on mobile phone while bored, share on social media instantly
- program a robot using a language specific to that robot, publish that program

## Use cases for page

- make a page for a physical thing, put the url on the thing
    - bulletin board for a bus stop
    - bulletin board for a specific location in a public park
    - scroll that explains how to make a thing(lore)
    - scroll that tells the story of a thing(tale)
    - business informal page
    - business specific sale/coupon/promotion page
    - section of the library
- write and publish a technical paper
- write a book, print and bind it
- make a personal motd for a user

## Use cases for Maps

- treasure map, show location of hidden thing
- shopping center map with link to each business
- meme factory
- constructing slide deck to destroy PowerPoint
- label parts of a thing in a photograph
- graph theory figure without TeX
- graph theory figure with TeX formatted math
- map, e.g. graph theory, embedded in a iframe in a Jupyter notebook cell
- flow diagram for work flow



## pages

- map(links to other symbol factories, workflow diagram for this instance)
- scroll(documentation of this instance)
- symbol(main platform for creation of arbitrary symbols of all shapes and sizes)
- icon(like symbol but with fixed large size and fixed small save size)
- hypercube(edit the hypercube)
- styleeditor(edit the style JSON file)
- robot(create robot code using ASCII and Arduino)
- symbolfeed(displays all the symbols with delete button, capture link for markdown, edit, download)



Geometron 5 is a rewrite of geometron 4, streamlining and drastically enough changing things that I wanted a clean slate.


Geometron 4 further unified the elements:


- symbol
- scroll
- map
- propagator

This system is self replicating. Test.

## Here is the symbol for "scroll" in Geometron:
 
![](http://lafelabs.org/mapicons/scroll.svg) 


## Rules of Organic Media:

- everything replicates
- everything is editable
- everthing can get deleted
- next instance needs only the previous instance, no central code base referenced at all, same for subsequent instance

## To Do:

### Immediate, top priority:

- replicator.php, use to put on a remote server from github code, then replicate from new server to new one after that(make it living organic thing)
- deletebranch added so a branchdown can be undone
- design layout of hypercube.html(on paper)
- make it easy to export urls from feed to import into index.html 
- make index.html have nav as default
- fix layout, convert to css, to make it dynamic and work with mobile, same for all pages(web design) 

### Top Level/System

- branch down further tested
- add deletebranch
- replicator.php working, used to replicate to servers
- build a better CSS framework for the overall shape of the screens, make it dynamic so resize doesn't break everything
- add and test mobile functionality for all pages(portrait instead of landscape)
- try building out a universe of things: cherry tree shopping center for instance
- write the physical Book of Geometron, build a Universe of Things around it
- build a Universe of Things around ArtBox
- build a Universe of things with markers/maps/signs in physical locations as prototype
- build protocol for replicating a whole Universe
- plot out the path to build rapdily replicating post capitalist technology with this: build a factory in a location in space defined by a street and watershed, work in a locally defined Trash Camp, build/make/create, create economic activity in capitalist system which generates money locally but globally creates self replicating things which can expand across the system.  *Locally* people in Capitalism are drawn into our system by the profit motive, but globally our system totally undermines capitalism by releasing things for free which repilcate without money.
- add codemap.html, a MAP object which has links to editor.php?filename=[this file] for each file in the system, showing how they all go together
- add propagator.html which is a scroll that tells the user how to propagate the System using:
    - hostinger with paid hosting and a new domain, which can generate email addresses which are used to get..
    - 000webhost free hosting
    - raspberry pi zero w based local server on a local wifi
    - MAMP localhost 
    - php localhost


### index.html

- put nav on top instead of array display
- map import from remote
- JSON string import/export
- make text elements actually scale properly in some rational way with fontSize
- fix hammer on vertical sliders on work computer
- add link to editor, make editor dynamically update for whatever files are around, either html or in js or php, css


### scroll.html

- add no-update mode
- add math mode
- add conversion to standalone doc with hammer.js
- add icons for modes instead of words
- add copy remote scroll option


### symbol.html

- dynamic x0 and y0, unit, put these into the glyph feed as an object
- add svg functionality, export, save, etc
- background image functionality(low priority)

### hypercube.html

- export images with glyph spelling 
- export images with much more customization than symbol.html(ok to have it be complicated here, for expert users)
- design overall window layout and functionality
- easy import and export of fonts, shape tables, etc, sharing of all the parts
- metalanguage for robotics functionality set up as simple template
- control panel editor
- keyboard editor
- style editor
- product properties: shape, format, x0,y0, unit
- standard library of shapes and fonts:
    - katakana dots font
    - english dots font
    - hebrew calligraphy font
    - nautical signal flag font
    - standard circuit diagrams
    - quantum gates
    - golden ratio sacred geometry
    - yoga stuff
    - watershed symbolism, language of Watershed
    - street symbolism, language of Street
    - factory symbolism, language of Factory


![](symbolfeed/font.svg)

is this a better way to edit?