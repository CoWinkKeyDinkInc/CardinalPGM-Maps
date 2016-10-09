# CardinalPGM-Maps
The sequel to OCN-Maps, but like all sequels it's not as good.

A ton of maps are submitted on the OCN forums as public downloads. Unfortunately, lots of these maps don't get any further than the forums, including many good ones that could play great.

What this repository does is try to update and fix the maps so they can play better, look better, and are proven to work. We will also try to make them more compatible with [CardinalPGM](https://github.com/twizmwazin/CardinalPGM), an amazing open source plugin that allows you to play maps just like if it was on OCN!

## How to install
The best way to install CardinalPGM-Maps into your CardinalPGM server is to clone the repository into the server's `maps` folder. This makes it much easier to recieve updates with a single click or command from your faviourite [Git client](https://git-scm.com/downloads/guis). Much better than downloading entire repo as a zip, and then removing the old copy and putting in the new one. Here's how do to it!
 1. Download and install [GitKraken](https://www.gitkraken.com/)
 2. Click on the green clone or download button, and copy the URL
 3. Go to File > Clone Repo
 4. Paste the URL into the URL text box, locate the maps folder and click on the clone repo button
 5. To update the maps repository, open up the repo in GitKraken and click pull
 
### How to fork
Repeat the same steps as seen above, but fork this repo, and use the link given on the fork repository.

## How do I contribute?
 - If you have a map that you want to be updated or fixed, submit a pull request!
 - If the pull request is a fix in a map, please only have one map involved in a commit and include pictures on aesthetic changes.
 - Use proper spacing and formatting in XML, spacing will make XML files much easier to read.
 - Put this repo on your CardinalPGM server to test for errors.
 - Make sure to enable the `displayMapLoadErrors` property in `config.yml`, which can be located in the `Cardinal` folder which is inside the `plugins` folder.

## How do I get my map on this repository?
 - The only requirement for maps to be considered adding to the repo is that there will be no conflicts arising from the map being added. You must be the author of a map, or have permission to do so to submit a pull request containing the map.  You don't need an XML file to submit a map.
 - Submit a pull request with the map and XML **uncompressed**.  If approved, it will be merged, which then we can make fixes and improvements on the map through other pull requests.

## Saving space
 - Please [prune](https://docs.oc.tc/packaging/pruning_chunks) chunks, remove unnecessary entities and delete [useless files](https://docs.oc.tc/guides/packaging/cleaning_files) before submitting maps. GitHub repositories are limited to 1GB in size and I'd only want to make a second one if it's absolutely necessary.
 - Deleting unnecessary files can make a massive difference. This reduction was done by deleting 64 `.mcr` (Region files dating before 1.2) files and removing all entities.
![pic](http://puu.sh/gPEj4.png)

## Credits (Who allowed these maps here)

All maps are under this creative commons license unless otherwise specified.

<a rel="license" href="http://creativecommons.org/licenses/by-sa/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" /></a>
### CoWinkKeyDinkInc
 - Oculo
 - Q\*Boid

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

### KroestV2
 - Dry DTC
 - Fairy Tales 2: Mini
 <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png"/></a>
 - King of the Castle
 - Ultra Twizz  <a rel="license" href="http://creativecommons.org/licenses/by-nc/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by-nc/4.0/88x31.png"/></a>
 - A team gear map

### Spintown
 - Table Block

## An important note
Some forks of this repository may contain a huge list of maps that are from OCN. We won't accept these as they're usually obtained without permission.  We have absolutely nothing to do with these forks, so if you have issues, send it to them.
