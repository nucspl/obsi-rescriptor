# Rescriptor
v0.2b "Working Prototype" for [Obsidian](https://obsidian.md/) 1.2.8+

Rescriptor (Latin for "rewriter") is a reimplementation of [Typewriter](https://github.com/crashmoney/obsidian-typewriter) for post-1.0 Obsidian. The goal is to get the theme's aesthetics to be on-par with more recent ones, while packaging my own fixes and improvements to a handful of vanilla Obsidian's shortcomings.

![image](https://github.com/nucspl/obsi-rescriptor/assets/80261260/a67847e7-867d-47cb-b18d-c569763ad74e)

### Features
- [iA Writer typeface](https://ia.net/topics/a-typographic-christmas), base64-encoded for use on any platform; 
- Earthy light and dark workspace color schemes (currently borrowed from [Jotter](https://github.com/lnbgc/obsidian-jotter));
- Larger clickspace for workspace tabs and buttons (inspired by [Buena Vista](https://github.com/oqipoDev/Buena-Vista-Theme));
- Hierarchical colors and weights for interactive elements;
- Altered positioning of file explorer elements;
- Hidden view header breadcrumbs (from [Jotter](https://github.com/lnbgc/obsidian-jotter));
- Improved header hierarchies with neat inline title integration;
	- h1 through h3 weights made thinner;
	- h4 through h6 are significantly smaller, with progressively fainter coloration;
	- h6 headers may be placed margin-side, useful for navigating via the Outline core plugin (inspired by [Dayspring](https://github.com/erykwalder/dayspring-theme));
- Better callouts with tighter spacing and color-aligned accented elements;
	- Sleek icon positioning (from [Listive](https://github.com/efemkay/obsidian-listive-theme));
	- Works best alongside my Metadata Callouts snippet, or something similar;
- [Lost Paul's Folder Notes](https://github.com/LostPaul/obsidian-folder-notes) support;

And some more on the way...

---
## That "some more"...

The theme is a work-in-progress. There are still a good few things I've planned but yet to implement. Should anyone want to take a look, or even help, some drafts can be found in the respective directory; but be warned, these are really messy.

**Pending tasks as of 230827**
- [ ] Color scheme derived from Typewriter;
- [ ] App-wide scale-transform hover effects (inspired by Feather);
	- [ ] Weight and color hierarchy;
	- [ ] Text-overflow fade-out instead of ellipsis;
	- [ ] Context menu compatibility;
	- [ ] Modals compatibility;
- Settings menu overhaul
	- [ ] Support for app-wide hover effects;
	- [ ] Dropdown menu style parity with context menus;
	- [ ] Slider and toggle style parity;
- [ ] Style Settings options;
	- [ ] Line Width slider;
	- [ ] Embed Headings toggle;
		- [ ] `cssclass` toggle;
	- [ ] Dayspring Verses toggle;
		- [ ] `cssclass` toggle;
	- [ ] Task Strikethrough toggle;
