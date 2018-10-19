# Procedural generation

A mostly javascript-centric resource / links list on procedural content generation (PCG).


## JavaScript modules

### <a href="https://github.com/kchapelier/convchain" target="_blank">kchapelier/convchain</a>

Vanilla javascript port of <a href="https://twitter.com/ExUtumno" target="_blank">@ExUtumno</a>'s <a href="https://github.com/mxgmn/ConvChain" target="_blank">ConvChain</a>.

### <a href="https://github.com/kchapelier/wavefunctioncollapse" target="_blank">kchapelier/wavefunctioncollapse</a>

Vanilla javascript port of <a href="https://twitter.com/ExUtumno" target="_blank">@ExUtumno</a>'s <a href="https://github.com/mxgmn/WaveFunctionCollapse" target="_blank">WaveFunctionCollapse</a>.

### <a href="https://github.com/kchapelier/cellular-automata" target="_blank">kchapelier/cellular-automata</a>

Cellular automata runner supporting a broad set of rule format in arbitrary dimensions.

### <a href="https://github.com/kchapelier/poisson-disk-sampling" target="_blank">kchapelier/poisson-disk-sampling</a>

Poisson disk sampling in arbitrary dimensions.

### <a href="https://github.com/kchapelier/ngram-word-generator" target="_blank">kchapelier/ngram-word-generator</a>

Word generation based on n-gram models, and a cli utility to generate said models from generic text files.

### <a href="https://github.com/scijs/sphere-random" target="_blank">scijs/sphere-random</a>

Sample random points on the surface of a n-dimensional hypersphere (a sphere of any dimension).

<a href="https://github.com/kchapelier/sphere-random/tree/rngAsArgument" target="_blank">Fork</a> allowing to use custom random number generators instead of Math.random.

### <a href="https://github.com/davidbau/seedrandom" target="_blank">davidbau/seedrandom</a>

Seeded random number generator for JavaScript.

### <a href="https://github.com/xixixao/noisejs" target="_blank">xixixao/noisejs</a>

Javascript 2D and 3D Perlin & Simplex noise functions.

### <a href="https://github.com/zsoltc/worley-noise" target="_blank">zsoltc/worley-noise</a>

Worley noise (also called Cell noise) in JavaScript.

### <a href="https://github.com/kjirou/generate-maze-by-clustering">kjirou/generate-maze-by-clustering</a>

Generate a 2D maze using a <a href="http://apollon.issp.u-tokyo.ac.jp/~watanabe/tips/maze_e.html" target="_blank">clustering algorithm</a>.

### <a href="https://github.com/evanw/csg.js">evanw/csg.js</a>

Constructive Solid Geometry in javascript. Create complex 3D geometries using Boolean operations like union and intersection to combine 3D solids.

### <a href="https://github.com/galaxykate/tracery" target="_blank">galaxykate/tracery</a>

Grammar-based english text generation.

### <a href="https://github.com/sequitur/improv">sequitur/improv</a>

A model-backed generative text library for JavaScript. An alternative to Tracery.

### <a href="https://github.com/Jam3/heightmap-contours">hughsk/heightmap-contours</a>

Generate contour meshes from a 2D heightmap.

### <a href="https://github.com/hughsk/cave-automata-2d">hughsk/cave-automata-2d</a>

Generate 2D cave layouts using a single parametrized cellular automata rule.

### <a href="https://github.com/gorhill/Javascript-Voronoi">gorhill/voronoi</a>

Javascript implementation of Steven J. Fortune's algorithm to efficiently compute Voronoi diagrams on a 2D plane.

### <a href="https://github.com/nlp-compromise/nlp_compromise">nlp_compromise/nlp_compromise</a>

Lightweight natural language toolkit in Javascript for English with "good-enough" philosophy.

### <a href="https://github.com/NaturalNode/natural">NaturalNode/natural</a>

Heavyweight natural language toolkit in Javascript mainly for English but also with a few utilities for other languages.

### <a href="https://github.com/dhowe/RiTaJS">dhowe/RitaJS</a>

Another heavyweight natural language toolkit in Javascript for English.


## Talks / videos

### <a href="https://www.youtube.com/channel/UCgFSPzCM9rx_Hxl-g13KcYw">The PROCJAM (procedural generation jam) youtube channel</a>

Include playlists for all the talks made for PROCJAM 2014, 2015, 2016 and 2017.

### <a href="https://www.youtube.com/watch?v=o9RK6O2kOKo" target="_blank">[Unite 2015] A coder's guide to spline-based procedural geometry</a>

Generation of 3D geometries following a 3D Bézier curve.

### <a href="https://www.youtube.com/watch?v=ySTpjT6JYFU">[Unite 2014] Generating Procedural Dungeons in Galak Z</a>

Zach Aikman discusses all the techniques he experimented with to generate the 2D levels of Galak-Z (cellular automata, space partitioning and space filling curves).

### <a href="https://www.youtube.com/watch?v=GYYuhuarTA0">[Nordic Unite 2013] Procedurally generated content in Sir, You Are Being Hunted</a>

The two members of Big Robots explain the process used to generate the world in Sir, You Are Being Hunted (voronoi-delaunay dual graph, fractal heightmap, etc.) and present some earlier projects (including a classic 2D dungeon generation extended to 3D with elevation, stairs, etc.). The talk also touches subjects such as the player perspective on PCG (replayability, player-drive stories, ...), the necessity of PCG tools for small game studios and how it may impact the development of AI for the NPCs.

### <a href="https://www.youtube.com/watch?v=zPQOHX9hiL0">[Unite 2014] Dungeon of the Endless Rendering and Procedural Content</a>

Sébastien Dubois discusses the issues encountered with the initial dungeon generation algorithm (mostly boiling down to lack of control) and how they fixed it by implementing a template-based generation with multiple layers of abstraction (and an extensive toolset for the artists). The first 25 minutes of the talk is purely about the rendering but is not uninteresting either.

### <a href="https://www.youtube.com/watch?v=_ooDLiU-o6c">[Digital Dragons 2017] GPU-Based Run-Time Procedural Placement in 'Horizon Zero Dawn'</a>

Jaap van Muijden explains the real-time procedural placement technique implemented in Horizon Zero Dawn on the GPU and how the game artists can use it to paint the world with ecotopes.

### <a href="https://www.youtube.com/watch?v=sUjW5zlgeoQ">[IRDC 2016] Markov by Candlelight</a>

Jason Grinblat discusses the use of markov chain to generate books in Caves of Qud, how the specificities of the algorithm matches the context of the game and how to insert meaningful bits of text in markov chains.

### <a href="https://www.youtube.com/watch?v=ClGAApZYIvI">[Roguelike Celebration 2017] Procedurally generated histories in Caves of Qud</a>

Jason Grinblat discusses how the history of the world is generated, how it is told to the player and how it is integrated in the gameplay.

### <a href="https://www.youtube.com/watch?v=Z6lHExfem6U">[Roguelike Celebration 2018] Machine Learning and Level Generation</a>

Ben Berman discusses advances, as well as his own investigation, in the use of Machine Learning and related algorithms in procedural content generation.

### <a href="https://www.youtube.com/watch?v=Uo9-IcHhq_w">[Roguelike Celebration 2018] Procedural level design in Brogue and beyond</a>

Brian Walker explains how the level generation in Brogue works. From how the rooms are placed to how the "puzzles" are added to bring life to the dungeon. Also discussed are his experiment in making a 2d platformer relying on PCG for its level.

## Books / Ebooks

### <a href="http://www.procjam.com/seeds/">Seeds, the PROCJAM Zine</a>

Zine made by the PROCJAM community featuring diverse looks at procedural content generation as a whole and insights on specific pcg methods.

### <a href="http://pcgbook.com/" target="_blank">pcgbook</a>

A textbook about procedural content generation in games, fully readable online.

### <a href="https://books.google.be/books?isbn=1558608486" target="_blank">Texturing &amp; modeling: a procedural approach</a>

A classic reference on the subject by pioneers and creators of the featured methods and algorithms (Ken Perlin, Steven Worley, F. Kenton Musgrave, David S. Ebert and Darwyn Peachey).

### <a href="https://books.google.be/books?isbn=1935182625" target="_blank">Generative Art: A Practical Guide Using Processing</a>

The book presents multiple examples of generative arts and explains the techniques used in some of them in the form of short tutorials (in Processing).

### <a href="https://www.scratchapixel.com/">Scratchapixel 2.0</a>

Free online ebook on computer graphics featuring articles on value noise, fractal noise, perlin noise and more in the appendix "Procedural Generation of Virtual Worlds". Sample codes are in C++.


## Dedicated websites and articles

### <a href="http://procedural-generation.tumblr.com/">Procedural Generation Tumblr</a>

### <a href="http://pcg.wikidot.com/">Procedural Content Generation Wiki</a>

### <a href="http://www.roguebasin.com/index.php?title=Articles#Map">RogueBasin's articles about development</a>

### <a href="https://www.reddit.com/r/proceduralgeneration/">Procedural generation subreddit</a>

### <a href="http://inconvergent.net/">The articles of Anders Hoff, aka inconvergent, on generative algorithms</a>

### The articles of Martin O'Leary, aka mewo2, on <a href="http://mewo2.com/notes/terrain/">2D map generation</a> and <a href="http://mewo2.com/notes/naming-language/">language-driven naming</a>

### <a href="http://tinysubversions.com/spelunkyGen/">Explanation of the template based generator used in Spelunky</a>

### <a href="http://www-cs-students.stanford.edu/~amitp/game-programming/polygon-map-generation/">Amit Patel's article on 2D polygon map generation with biomes using Voronoi</a>

### <a href="http://experilous.com/1/blog/post/procedural-planet-generation">Andy Gainey's article on procedural planet generation with subdivided icosahedrons, tectonic plates and air currents simulation</a>

### <a href="http://alanluo.com/procgen/midterm.html">Generating Art with Code, a handbook to "Little Planet Procedural" by Alan Luo</a> Procedural generation of landscape with canvas' 2d context.

### <a href="http://www.procjam.com/tutorials/">Procjam tutorials</a> PCG tutorials commissioned for the Procjam. The batch from 2017 covers topics such as the generation of music, the generation of text following predefined templates and the use of Wave Function Collapse.


## Datasets and corpora

### <a href="https://github.com/dariusk/corpora">dariusk/corpora</a>

A collection of small corpora available as JSON files for easy consumption.

### <a href="https://github.com/caesar0301/awesome-public-datasets">caesar0301/awesome-public-datasets</a>

A collection of "high-quality open datasets in public domains".

### <a href="https://www.reddit.com/r/datasets/">/r/datasets</a>

Subreddit about datasets.

### <a href="https://www.kaggle.com/datasets">Kaggle.com</a>

A collection of open datasets, mostly in CSV. The website requires you to setup an account in order to download datasets.

### <a href="https://catalog.data.gov/dataset">data.gov</a>

The home of the U.S. Government’s open data. Like most government-led open data initiatives, the quality (and even the availability) of the datasets is very variable.

### <a href="http://www.wikipedia.com">Wikipedia</a>

More often than not, a good resource for the pragmatic developer who is willing to copy-paste or write two-liners of JavaScript to scrape the website directly in the browser's console.
