---
name: Atlas Exandria Design Document
slug: atlas-exandria-design-document
order: 00
pdf-page-style: single-column
footer: Copyright © 2022-2023 MrFarland
---
![Heading](./module/assets/img/heading.png){.size-cover}

<div align="center">
  <h1>Atlas Exandria</h1>
  <h4>Design Document</h4>
  <br/>
  by <strong>Donald Farland</strong>
  <br/>
  <a href="https://donfarland.com">donfarland.com</a> - <a href="https://twitter.com/MrFarland">@MrFarland</a>
  <br/>
  <br/>
</div>
<p align="center">
  <a href="#introduction">Introduction</a> •
  <a href="#functional-requirements">Functional</a> •
  <a href="#non-functional-requirements">Non-functional</a>
</p>

## Introduction
Atlas Exandria is a comprehensive geographical reference of Exandria for 5th edition [Dungeons & Dragons](https://dnd.wizards.com) game masters running "open world" campaigns & adventures in the [Critical Role](https://critrole.com) universe. Atlas Exandria is an interactive reference module for the [EncounterPlus](https://encounter.plus) virtual tabletop system available for Apple iOS and MacOS devices. 

#### Objectives
The high-level objective of this project is to create an [EncounterPlus](https://encounter.plus) module & a limited, offline PDF version with the following information for D&D 5e game masters:

1. detailed maps of Exandria, its continents, and regions;
1. lore for places represented on the maps;
1. regional climate & weather data;
1. regional & settlement demographic data;

#### Audience
This module was conceived, designed, and developed for the purpose of supporting my personal campaigns & adventures in the world of Exandria. As such, this module was created for:

- **[EncounterPlus](https://encounter.plus)**: Atlas Exandria is, first & foremost, a module for the EncounterPlus virtual tabletop system available for Apple iOS & MacOS devices. There will be an offline PDF version of this atlas, but it will lack many of the capabilities it was created for.
- **[Dungeons & Dragons](https://dnd.wizards.com) (5th Edition)**: While you may be able to use this module for your Pathfinder or other preferred tabletop role-playing game system, the module was created specifically for DnD5e.
- **Game Masters**: The Atlas Exandria was created for game masters running campaigns & adventures in Exandria. It is not a reference for the [stream](https://critrole.com) or "[The Legend of Vox Machina](https://www.imdb.com/title/tt11247158/)". The goal is "canon consistency", not 100% canon.

## Deliverables
The following are the intended deliverables for this project.

1. **Maps (Wonderdraft)**: Source files for the world, continent, & region maps.
1. **Maps (1x JPG)**: 1:1 exports of the Wonderdraft maps to a standard JPG format.
1. **Maps (2x JPG)**: 2:1 exports of the Wonderdraft maps to a standard JPG format.
1. **Module**: Interactive atlas module for the EncounterPlus virtual tabletop.
1. **Offline Atlas**: An offline, non-interactive version of the atlas in PDF format.
1. **Cartographer's Guide**: Documentation on the settings & conventions used to create the maps.

## Functional Requirements
The following are the various functional requirements I have identified to date for this module and related deliverables. The requirements are grouped alphabetically and do not reflect priority or delivery date.

### Maps
1. As a GM, I want to open a map of the world of Exandria and see a canon-consistent representation of the world based on available resources such as:
    - Tal'Dorei Reborn
    - Explorer's Guide to Wildemount
    - Tal'Dorei Campaign Setting Guide
    - Critical Role Actual Play Stream
1. As a GM, I want to open a map of the world of Exandria and see an overlay of the climate zones super-imposed over the world.



### Region
1. As a GM, I want to open a region page and see the following maps:
    - Standard:
    - Climate:
    - Political:

1. As a GM, I want to open a region page and see the following information:
    - **Name**: The name of the region and any alternate names it may be known as.
    - **Description**: A brief summary of the region, its location, history & current state.
    - **Area**: A rough estimate of the region's size in square miles.
    - **Population**: A rough estimate of the region's population.
    - **Population Density**: A rough estimate of the region's population density.
    - **Climate**: A seasonal breakdown of the hi/lo temperatures and average precipitation.
    - **Demographics**: A breakdown of the region's racial diversity.
    - **Nations**: A list of the nations with influence in the region.
    - **Religions**:
    - **Settlements**:
    - **Travel**:
    



#### Continents
1. As a GM, I want to open a continent page and see the following information:
    - **Name**: The name of the continent and any alternate names it may be known as.
    - **Description**: A brief summary of the continent's location, history & current state.
    - **Area**: A rough estimate of the continent's size.
    - **Population**: A rough estimate of the continent's total population.
    - **Density**: A rough estimate of the continent's population density.
    - **Regions**: A list of all regions located on this continent.
    - **Settlements**: A list of the major settlements on the continent. (Capitals & Cities)
    - **Nations**: A list of the major realms, kingdoms, or nations on the continent.
1. As a GM, I want to open a region page and see the following information:
    - **Name**: The name of the continent and any alternate names it may be known as.
    - **Description**: A brief summary of the continent's location, history & current state.
    - **Area**: A rough estimate of the continent's size.
    - **Population**: A rough estimate of the continent's total population.
    - **Density**: A rough estimate of the continent's population density.
    - **Settlements**: All of the minor & major settlements in the region.
    - **Travel**: All major travel routes in the region

1. As a GM, I want to open a page for an area (world, continent, region, or feature) and be given information about the:
    - Area: size of the area in square miles, so I can accurately convey its size to the players.
    - Demographics:
    - Density: 
    - Population:
    - Population Density:

#### Climate


#### Demographics
1. As a GM, I want to see the racial demographics for a region or settlement, so I can relay that information to my players when I describe people in that region or settlement.

#### Encounters
#### Hex Crawl
#### Lore
#### Maps
#### Travel



## Non-Functional Requirements
The following are the various non-functional requirements I have identified to date for this module and related deliverables. The requirements are grouped alphabetically and do not reflect priority or delivery date.

#### Accessibility
There currently no requirements related to accessibility, but this is an area that should be researched and added as development moves forward.

#### Capacity
1. As a user, I want the module to be less than ... ?

#### Interface
1. As a user, I want an interface that uses large, easy-to-read buttons and labels so I can navigate the interface more easily on a small screen.
1. As a user, I want a visual indication of the path I took from the main menu to the current page so I know where the current page is located.
1. As a user, I want an interface that scales to different window sizes supported by EncounterPlus so it doesn't break if I open it:
    - from the library,
    - from search,
    - from a shortcut.
1. As a user, I want an interface that scales to different devices supported by EncounterPlus so it doesn't break if I open it:
    - on my iPad,
    - on my iPhone,
    - on my Mac.

#### Printing
1. As a GM, I want digital versions of the maps in JPG format, so I can print them out for more players to use as handouts.
1. As a GM, I want to print borderless prints of the maps on standard US Letter (8.5"x11") and/or US Tabloid (11"x17") paper, so I can print them at home myself.
1. As a GM, I want extra-large, digital versions of the maps in JPG format, so I can order large format prints that can be framed and hung in my game room.

#### Wonderdraft
1. As a Wonderdraft user, I want access to the source Wonderdraft files so I can download and edit them in my own copy of Wonderdraft.
1. As a Wonderdraft user, I want the maps to use standard assets, so I don't have to search for, download, and install custom asset packs.
1. As a Wonderdraft user, I want to know the settings, fonts, and colors in the maps so I can make edits and new maps with the same look & feel.