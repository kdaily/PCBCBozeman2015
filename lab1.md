---
title: "Data Organization and Sharing"
subtitle: "PCBC, Bozeman 2015"
author: "Kenneth Daily"
date: "9/25/2015"
output: ioslides_presentation
---

## Introduction

Inspired by Karl Browman's notes on [Data Organization](http://kbroman.org/dataorg/).

Version for this presentation is here:
https://kdaily.github.io/dataorg/

## Be Consistent. | [xkcd.com](https://xkcd.com/927/)

![XKCD Standards](http://imgs.xkcd.com/comics/standards.png)


## Be consistent.

- Categorical variables (`M`, `male`, `Male`)
- Fixed code for missing values (`NA` = Not Applicable or Not Available?)
- Covariate/variable naming (the column names)
- Subject IDs (`1`, `cell1`, `Cell1`, `The first cell`)
- Data layout
- File names
- Dates
- Note-taking

https://kdaily.github.io/dataorg/pages/consistency.html

## Dates. | ([xkcd.com](https://xkcd.com/1179/))

<center>
<img src="https://imgs.xkcd.com/comics/iso_8601.png" width="40%" alt="XKCD Dates">
</center>

## Dates.

In Excel, use plain text column for dates, or proceed with caution.

(e.g., everyone's favorite gene, "10/04/2015"")

## No empty cells.

Fill them in.

Debatable...

https://kdaily.github.io/dataorg/pages/no_empty_cells.html

## Make it a rectangle.

Spreadsheets are inherently rectangular.

Maybe, you need multiple rectangles of data (don't duplicate info across)

If you can't do it with one or more rectangles, spreadsheets are not the answer.

https://kdaily.github.io/dataorg/pages/rectangle.html

## Create a data dictionary.
* The exact variable (column) name as in the data file
* A version of that name that might be used for plotting, summarizing
* A longer explanation of what the variable represents.
* The measurement units.
* Expected values (range of min and max, which text, etc.)

This is meta*data*, so what shape should it be in?

https://kdaily.github.io/dataorg/pages/dictionary.html

## No cell formatting.

No font color or highlighting as data (turn it into a column).

It's OK ONLY IF it's not in raw data!

https://kdaily.github.io/dataorg/pages/no_highlighting.html

## Make backups

- Use [Synapse](https://www.synapse.org/) - it's free!

## Why Synapse? | General

- It's free
- We can help you

## Why Synapse? | Backup

- Organized storage and sharing (like Box, DropBox, Google Drive)
- Available anywhere
- Sharing

## Why Synapse? | Versioning

<center>
<img src="http://www.phdcomics.com/comics/archive/phd101212s.gif" width="40%" alt="PhD Final">

[phdcomics.com](http://www.phdcomics.com/comics/archive.php?comicid=1531)
</center>

## Why Synapse? | Provenance

Who did what to which data?

- Tracking
- Attribution
- Results

## Why Synapse? | Automation

- R Client
- Python Client
- Command Line Client

## Why Synapse? | Citation

Create a DOI (Document Object Identifier)

You know that thing that's on all publications?

You can get your own for your data (to use in your publications, resume, etc.)

[doi:10.7303/syn4951755.1](http://dx.doi.org/10.7303/syn4951755.1)

## Save data in text files (csv)

- xls is proprietary
- Text works in many programs (including Excel)
- 
https://kdaily.github.io/dataorg/pages/csv_files.html