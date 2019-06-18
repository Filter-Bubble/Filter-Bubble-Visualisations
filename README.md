# Filter Bubble Visualisations

This repository contains a _Jupyter Notebook_ which generates visualisations based on mobile browser history.

## Background

Online and mobile news consumption leaves digital traces that are used to personalize news supply, possibly creating filter bubbles where people are exposed to a low diversity of issues and perspectives that match their preferences. The [JEDS Filter Bubble](http://ccs.amsterdam/projects/jeds/) project aims to understand the filter bubble effect by performing deep semantic analyses on mobile news consumption traces. This project is a collaboration between the [VU](https://www.vu.nl/nl/index.aspx), the [UvA](http://www.uva.nl/) and [NLeSC](https://www.esciencecenter.nl/), lead by [Wouter van Atteveldt](http://vanatteveldt.com/).

Part of this project includes gathering data from a group of participants. These fill in a questionnaire and consent to giving us their browsing history. The _Jupyter Notebook_ in this repository provides some preliminary descriptive statistics on our data.

## Repository content

### data

The _data_ directory contains the _Qualtrics_ survey data and the _Passive Data Kit_ and _Web Historian_ browsing history. Due to the privacy sensitivity of the data, the entire directory is _gitignored_.

### figures

The _figures_ directory contains saved output of the _Jupyter Notebook_ which visualise aggregate statistics of our data.

### tables

The _tables_ directory contains saved output of the _Jupyter Notebook_ which list aggregate statistics of our data.

### Visualisations.ipynb

This _Jupyter Notebook_ imports the data, cleans and restructures it and subsequently outputs various aggregate descriptive statistics.