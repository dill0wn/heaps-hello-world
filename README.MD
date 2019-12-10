# HEAPS (Haxe) Hello World #

A quick js `Hello World` made with [heaps](https://heaps.io/), a graphics framework slash game engine built on [haxe](https://haxe.org/).

## Setup ##

### Prerequisites ###

Install [haxe](https://haxe.org/) (I used [brew](https://brew.sh)).

### Local or Global haxelib ###
Optionally set up haxelib to use a local repo: 

```
haxelib newrepo
```
Otherwise make sure to run `haxelib setup` to configure where haxelib puts your haxe libraries.
```
haxelib setup
```

### Dependencies ###
Install haxelib dependencies

```
haxelib install compile.hxml
```

### Compile ###
Compile your js

```
haxelib compile.hxml
```

### Run ###
Open `index.html` (or run some sort of web server)

```
open ./index.html
```