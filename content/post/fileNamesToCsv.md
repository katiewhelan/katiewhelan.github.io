---
title: "File Names To CSV"
date: 2021-05-05T20:03:58-05:00
draft: false
---
{{< rawhtml >}}
<br />
{{< /rawhtml >}}

***
{{< rawhtml >}}
<p> One major part of this project has been how to collect all the data and format it to create items and collections.  This <a href="https://github.com/katiewhelan/fileNameToCSV">Node script</a> I created  parses file names to CSV format. This will allow me to create records for all digital items. This script will add a unique id, a title, and a boolean value for own for each file within the folder.</p>

<h3>Steps</h3>
<ul>
<li>run: npm install</li>
<li>run: node FileNameParser.js files</li>
<li>out.csv is the output</li>
</ul>

<p>To add more columns simply add on to header and add the values within the foreach statement. </p>
<img src="/images/header.png" width="600" height="150" class="center">
<p>Here is an example of the output. </p>

<img src="/images/CSVFileOutput.png" width="600" height="150" class="center">
<!-- <img src="/images/ForEach.png"> -->

<p>This <a href="https://stackoverflow.com/questions/4351521/how-do-i-pass-command-line-arguments-to-a-node-js-program">stackoverflow</a> was great at showing multiple options on how to pass arguments to the Node script</p>

<img src="/images/PassFilePath.png" width="800" height="200" class="center">

<p>The <a href="
https://www.npmjs.com/package/uuid">UUID</a> Package generates a unique id for each item, however this could be replaced with any form unique id.</p>
{{< /rawhtml >}}
