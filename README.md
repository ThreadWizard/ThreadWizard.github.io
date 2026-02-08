# ThreadWizard

ThreadWizard is an interactive genealogy visualization and analysis tool for building, editing, and exploring family trees, including DNA relationship comparisons and centimorgan (cM) interpretation.

## Features

**Core Features**
- Interactive family tree editor with collapsible ancestors and descendants
- Cross-branch spouse and relationship links
- Free-form layout manipulation via "move left/right" buttons and "link to existing person" features for visual comparison and pattern discovery
- Automatic relationship calculation from shared cM values
- DNA comparison highlighting with percentile-centric interpretation
- Continuously reactive workspace (DNA data migrates effortlessly and interpretations update live as tree structure changes)
- Spatial comparison matrices (align individuals at edges for row/column easy analysis)
- Color-coded analytical cues for relationships and DNA matches
- Export and visualization tools
- Light/dark theming
- Privacy-friendly local browser operation (no accounts or uploads required)

**Design Philosophy**
- Direct manipulation interface for low-friction hypothesis testing
- Integrated DNA and genealogy context in single environment
- Minimal UI overhead to maintain analytical focus
- Reversible changes that encourage exploration

## Usage

Open the HTML file in a modern browser. No server is required.

Compatible browsers:
- Chrome
- Brave

- Edge
- Firefox

## Data Sources & Attribution

This project incorporates percentile and relationship data from:

**Shared cM Project v4.0**  
By Blaine T. Bettinger, Ph.D., J.D.  
https://thegeneticgenealogist.com  
Licensed under CC BY 4.0: https://creativecommons.org/licenses/by/4.0/

Modifications:  
Histogram bin counts were extracted and converted into a JavaScript lookup table for percentile calculation and UI integration.

No endorsement by the original author is implied.

## Third-Party Libraries

- D3.js v7 — https://d3js.org  
  License: BSD-style license

## License

GPL-3.0-only

Note: Third-party data and libraries retain their original licenses.
