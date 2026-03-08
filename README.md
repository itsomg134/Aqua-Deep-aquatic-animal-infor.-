# Aqua Deep

Aqua Deep is an immersive single-page encyclopedia of ocean creatures built with pure HTML, CSS, and JavaScript. It uses no frameworks and no external dependencies, focusing on a deep-sea visual aesthetic with smooth animations and interactive creature profiles.


## Overview

Aqua Deep presents detailed information about nine iconic marine animals across multiple ocean depth zones.

The site design follows a deep-ocean visual language featuring dark navy backgrounds, cyan and teal accents, floating animations, and a scrolling ocean fact ticker. The entire project is contained in a single HTML file, making it lightweight and easy to run in any modern browser.


## Features

### Creature Cards

Each animal appears as an interactive card displaying key information such as:

* Ocean depth zone
* Weight
* Length
* A defining statistic

Clicking a card opens a modal containing detailed information including two descriptive sections and a four-field fact grid.

---

### Ocean Depth Zones

A dedicated section visualizes the five major ocean zones:

* Sunlight Zone
* Twilight Zone
* Midnight Zone
* Abyssal Zone
* Hadal Zone

Animated bar charts display species count data. The bars animate when they appear in the viewport using the IntersectionObserver API.


### Fact Ticker

A continuously scrolling strip of twelve ocean facts runs across the page using a CSS keyframe animation.


### Custom Cursor

A dual-layer custom cursor replaces the default pointer.

* A bioluminescent dot tracks the mouse position directly.
* A larger ring follows the pointer with a slight delay using a requestAnimationFrame loop.


### Ambient Effects

Several visual effects create the underwater atmosphere:

* Procedurally generated CSS bubbles floating upward
* Slow background hue-rotation to simulate underwater light variation
* Floating animation effects on creature illustrations


## Animals Covered

| Animal                 | Scientific Name              | Zone         |
| ---------------------- | ---------------------------- | ------------ |
| Great White Shark      | *Carcharodon carcharias*     | Epipelagic   |
| Bottlenose Dolphin     | *Tursiops truncatus*         | Epipelagic   |
| Giant Pacific Octopus  | *Enteroctopus dofleini*      | Mesopelagic  |
| Clownfish              | *Amphiprioninae*             | Epipelagic   |
| Colossal Squid         | *Mesonychoteuthis hamiltoni* | Bathypelagic |
| Blue Whale             | *Balaenoptera musculus*      | Epipelagic   |
| American Lobster       | *Homarus americanus*         | Benthic      |
| Pufferfish             | *Tetraodontidae*             | Epipelagic   |
| Leatherback Sea Turtle | *Dermochelys coriacea*       | Mesopelagic  |


## Tech Stack

* HTML5
* CSS3

  * CSS Grid
  * Custom Properties
  * Keyframe Animations
* Vanilla JavaScript

  * DOM manipulation
  * IntersectionObserver
  * requestAnimationFrame
* Google Fonts

  * Playfair Display
  * DM Mono
  * Cormorant Garamond
    
## Getting Started

Clone the repository and open the HTML file in a browser.

```
git clone https://github.com/your-username/aqua-deep.git
cd aqua-deep
open index.html
```

You can also simply open the file directly in a browser without running a server.


## Design Notes

The visual identity is based on a bioluminescent deep-sea theme.

### Color Palette

* Navy to abyss gradient: `#020b18` to `#0a1f35`
* Cyan accent: `#00c9c8`
* Bioluminescent green: `#39ffdb`

### Typography

* Playfair Display for headings
* DM Mono for labels and data
* Cormorant Garamond (italic) for scientific names

### Motion

* Floating animations are staggered using animation-delay
* The cursor ring follows the pointer using interpolation for smooth movement
* Chart bars animate when visible using IntersectionObserver

### Layout

The layout uses CSS Grid with auto-fill and a minimum column width of 340px to ensure responsive card distribution.


## Browser Support

The project works in all modern browsers that support:

* CSS Grid
* CSS custom properties
* IntersectionObserver

Internet Explorer is not supported.


## License

MIT License


## Contact

Om Gedam

GitHub: [https://github.com/itsomg134](https://github.com/itsomg134)
Email: [omgedam123098@gmail.com](mailto:omgedam123098@gmail.com)
Twitter (X): [https://twitter.com/omgedam](https://twitter.com/omgedam)
LinkedIn: [https://linkedin.com/in/omgedam](https://linkedin.com/in/omgedam)
Portfolio: [https://ogworks.lovable.app](https://ogworks.lovable.app)
