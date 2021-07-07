# **<p align="center">UFO Finder</p>**

### **<p align="center">A JavaScript-powered webpage designed to filter and display UFO data on an interactive HTML webpage.</p>**

---
## Overview
This report will outline how to use the "UFO Finder" website and provide suggestions for improvements. HTML filter boxes inserted into the page are interactive and can be used to sort the UFO information table on the Date, City, State, Country and Shape parameters. Images and examples of how the site can be used are provided below in the Results section (**Note:** A variety of search parameters will return no results). Additional suggestions for a cleaner experience are provided in the Summary section.

---
## Results
---
### **<p align="center">UFO Finder at a Glance</p>**
                        Green ==> Interactive, Red ==> Descriptive, Blue ==> UFO Sightings Information
---

<p align="center">
   <img width="1000" height="1250" src="https://github.com/Jamesrx33/UFOs/blob/main/static/images/At%20a%20Glance.png?raw=true">
</p>

### **<p align="center">Section Descriptions</p>**

1. **Reload Link:**

   * This is an interactive link that, once clicked, will reset all filters and reload the page

<p align="center">
   <img width="600" height="200" src="https://github.com/Jamesrx33/UFOs/blob/main/static/images/Reload%20Page.png?raw=true">
</p>

2. **Title Section:**

   * The page is titled "The Truth Is Out There" in this JumboTron-Style title section
   * A custom image was inserted as the background for visual effect

3. **Article Section:**

   * This article section is designed to introduce site visitors to the topic of discussion
   * The article's title, "UFO Sightings: Fact or Fancy?", is to the left of this section
     * The subtext under the title, "Ufologists Weigh In", is a smaller subtitle
   * The article's paragraph is displayed on the right that encourages site visitors to use the following sections

4. **Table Filters:**

   * This is an interactive section where site visitors can input search criteria and filter the table information
   * Default values are provided in search input box to ensure the correct syntax of search criteria
   * Filters are applied after pressing **ENTER**
   * Filters can be removed by deleting existing search criteria and pressing **ENTER**

<p align="center">
   <img width="900" height="400" src="https://github.com/Jamesrx33/UFOs/blob/main/static/images/Using%20Filters.png?raw=true">
</p>

5. **UFO Sightings Table:**

   * This is where the UFO Sightings information is located
   * This is the data that the filters manipulate

<p align="left">
   <img width="800" height="200" src="https://github.com/Jamesrx33/UFOs/blob/main/static/images/Table.png?raw=true">
</p>

   * **Date:** The Date of the siting
   * **City, State, Country:** The location of the siting
   * **Shape:** How the UFO appeared to manifest in the sky
   * **Duration:** How long the UFO was visible
   * **Comments:** A short description of the siting


---
## Summary
---
This site is functional and well laid out, however the filters are limited in what criteria they can accept. I would suggest adding a ".toLowerCase()" method in our "UpdateFilters()" function so user input can be transformed to reflect the syntax of data in the table. At the moment, any upper-case search criteria will return zero results.

Additionally, here are two modifications i would suggest to make this page more dynamic:
1. Remove the Filter Input Boxes and use Bootstraps "Table Filter Control" instead
   > [Reference Link](https://bootstrap-table.com/docs/extensions/filter-control/)

2. Add a web-scraping utility provides more robust UFO sighting data from sites and inserts them into our table
   > [UFO Sightings Wiki](https://en.wikipedia.org/wiki/List_of_reported_UFO_sightings) 
   
   > [UFO Sightings Map](https://www.arcgis.com/apps/webappviewer/index.html?id=ddda71d5211f47e782b12f3f8d06246e)
---

## Reference Documentation - [Source Code Repository](https://github.com/Jamesrx33/UFOs), [Download .zip file](https://github.com/Jamesrx33/UFOs/archive/refs/heads/main.zip)
