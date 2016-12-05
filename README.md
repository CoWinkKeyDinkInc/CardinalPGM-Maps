# CardinalPGM-Maps
The sequel to OCN-Maps, but like all sequels it's not as good.

A ton of maps are submitted on the Lifeboat PC (OCN) forums as public downloads. Unfortunately, lots of these maps don't get any further than the forums, including many good ones that could play great.

What this repository does is try to update and fix the maps so they can play better, look better, and are proven to work. We will also try to make them more compatible with [CardinalPGM](https://github.com/twizmwazin/CardinalPGM), an amazing open source plugin that allows you to play maps just like if it was on Lifeboat PC (Overcast Network)!

## How to install
The best way to install CardinalPGM-Maps into your CardinalPGM server for production use is by cloning the repository by using CardinalPGM's cloning feature. This makes it much easier to receive updates with a single command! Much better than downloading entire repo as a zip, and then removing the old copy and putting in the new one. Here's how do to it!

  1. Go to the `Cardinal` folder inside the `plugins` folder, and open up `config.yml`
  2. Enter a new line underneath the default repository `maps`
  3. Paste in this line: `git:https://github.com/CoWinkKeyDinkInc/CardinalPGM-Maps`
  4. Maps and new commits should be download after a restart, if not, type in `/newmaps`

### How to use for map testing/fork
Clone the repository using your favorite [Git client](https://git-scm.com/downloads/guis) into the `maps` folder.
Copy and paste your fork URL.

## How do I contribute?
 - If you have a map that you want to be updated or fixed, submit a pull request!
 - If the pull request is a fix in a map, please only have one map involved in a commit and include pictures on aesthetic changes.
 - Use proper spacing and formatting in XML, spacing will make XML files much easier to read.
    - **The official spacing is four spaces, do not space tags inside the `<map>` tag.**
 - Put this repo on your CardinalPGM server to test for errors.
 - Make sure to enable the `displayMapLoadErrors` property in `config.yml`, which can be located in the `Cardinal` folder which is inside the `plugins` folder.

## How do I get my map on this repository?
 - The only requirement for maps to be considered adding to the repo is that there will be no conflicts arising from the map being added. You must be the author of a map, or have permission to do so to submit a pull request containing the map.  You don't need an XML file to submit a map.
 - Submit a pull request with the map and XML **uncompressed**.  If approved, it will be merged, which then we can make fixes and improvements on the map through other pull requests.

## Saving space
 - Please [prune](https://docs.oc.tc/packaging/pruning_chunks) chunks, remove unnecessary entities and delete [useless files](https://docs.oc.tc/guides/packaging/cleaning_files) before submitting maps. GitHub repositories are limited to 1GB in size and I'd only want to make a second one if it's absolutely necessary.
 - Deleting unnecessary files can make a massive difference. This reduction was done by deleting 64 `.mcr` (Region files dating before 1.2) files and removing all entities.
![pic](http://puu.sh/gPEj4.png)
 - Map images are to be a resolution of 290 x 246

## Credits (Who allowed these maps here)

All maps are under this creative commons license unless otherwise specified.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>

### CoWinkKeyDinkInc
 - Oculo
 - Q\*Boid

### KroestV2
 - A team gear map
 - Dry DTC
 - Fairy Tales 2: Mini  <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png"/></a>
 - King of the Castle
 - Ultra Twizz  <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png"/></a>

### Mikeg542
 - Bayou Battle
 - Jungle Beat
 - Lights Out
 - Myan Apocalypse
 - Ring Race
 - Swamped
 - Swamped Mini
 - Tenbrous

### Mitchiii_
 - Deadwater
 - Deadwater Pirate's Grotto

### Prodigy4532
 - NoDebuf-Sh1Prot1-PotPvP
 - Sh1Prot1-PotPvP
 - Sh2Prot1-PotPvP

### Spintown
 - Table Block

## An important note
Some forks of this repository may contain a huge list of maps that are from Lifeboat PC AKA OCN. We won't accept these as they're usually obtained without permission.  We have absolutely nothing to do with these forks, so if you have issues, send it to them.
