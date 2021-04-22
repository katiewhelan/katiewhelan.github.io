---
date: 2021-03-20T20:03:58-05:00
title: "Firebase - Data Upload"
draft: true
---
{{< rawhtml >}}
<br />
{{< /rawhtml >}}

***
{{< rawhtml >}}

Uploader on <a href="https://github.com/katiewhelan/firebaseUploader">Github</a>
<br/>

<p>One of the key components of my application is the ability to search collections of items. My application has the ability to add data directly however I did not wish to do this for every single item. I found a couple of tutorials on how to upload data from csv files to firebase that were extremely useful.  
<br/>

create excel, with id column of objectId (make sure spelling matches in uploader.js file exactly)
empty rows will cause an errors
export excel to csv and than convert to JSON

node uploader.js --> to run

-- remove lists that you have already uploaded from the "files" folder

-- if you run into errors running the uploader delete .DS_store file in the "files folder" </p>
<br/>
<img src="/images/jsonUploader.png">
<br/>



<br/>
<br />



<a href="https://medium.com/@devesu/how-to-upload-data-to-firebase-firestore-cloud-database-63543d7b34c5">Medium - How to Upload Data to Firebase</a>
<br/>
<br/>
<!-- https://www.youtube.com/watch?v=Qg2_VFFcAI8 -->
<iframe width="350" height="200" src="https://www.youtube.com/embed/Qg2_VFFcAI8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>






{{< /rawhtml >}}
