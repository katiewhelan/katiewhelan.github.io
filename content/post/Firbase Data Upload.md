---
date: 2021-03-20T20:03:58-05:00
title: "Firebase - Data Upload"
draft: false
---
{{< rawhtml >}}
<br />
{{< /rawhtml >}}

***
{{< rawhtml >}}
View the uploader files on <a href="https://github.com/katiewhelan/firebaseUploader">Github</a>
<br/>

<p>One of the key components of my application is the ability to search collections of items. My application has the ability to add data directly however I did not wish to do this for every single item. I found a couple of tutorials on how to upload data from CSV files to firebase that were extremely useful.  
<br/>

<h4>Step 1 - Gather your Data</h4>
<li class="addHeight">Create an excel spread sheet with the first column named "objectId"</li>
<li class="addHeight">Make sure this matches the name in the uploader.js file exactly</li>
<li class="addHeight">Empty rows will cause errors as well as an empty "objefctId" field</li>
<li class="addHeight">Export your spreadsheet to csv</li>

<h4>Step 2 - Format your Data</h4>
<li class="addHeight">Export your CSV to JSON</li>
<li class="addHeight">Use something like <a href="https://csvjson.com/csv2json">CSVtoJson</a></li>
<li class="addHeight">Place your json file in the "file" folder, the name of your json file will be the name of the Firebase Collection</li>

<h4>Step 3 - Set Up Firebase</h4>
<li class="addHeight">Add Project on Firebase</li>
<li class="addHeight">Download Service Key for the project</li>
<li class="addHeight">Rename your service key to "service_key.json" and add it to the root project folder

<h4>Set Up Node</h4>
<li class="addHeight">NPM Init</li>
<li class="addHeight">NPM install firebase-admin</li>

<h4>Upload Data</h4>
<li>node uploader.js</li>

<h4>Tricks/Tips/Errors</h4>
<li class="addHeight">Remove your json from the "files" folder after running so you don't duplicate data</li>
<li style="margin-bottom:10px">If you run into the error below delete .DS_store in the "files" folder</li>
 <br />
<img src="/images/jsonUploader.png">

<br />
<br />

<h3>Sources</h3>
<p> This article on Medium -
<a href="https://medium.com/@devesu/how-to-upload-data-to-firebase-firestore-cloud-database-63543d7b34c5">How to Upload Data to Firebase</a> was a great resource or, if you prefer to watch a video, this one walks you through all the steps.</p>
<br/>

<iframe width="350" height="200" class="center" src="https://www.youtube.com/embed/Qg2_VFFcAI8" title="YouTube video player" frameborder="0" allow="accelerometer; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
{{< /rawhtml >}}
