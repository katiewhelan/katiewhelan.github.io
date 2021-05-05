---
title: "Cloud Functions"
date: 2021-03-05T20:03:58-05:00
draft: false
---
{{< rawhtml >}}
<br />
{{< /rawhtml >}}
***
{{< rawhtml >}}
<p>After using test data in Algolia to make sure results were retuning properly I set up Cloud Functions to trigger when items are added, updated or deleted to the Firestore collection.</p>

<h3>Setup Steps</h3>
<ul>
<li>Firebase init Functions</li>
<li>NPM install algoliasearch</li>
<li>firebase functions:config:set algolia.appid"" algolia.apikey""</li>
<li>firebase deploy --only functions</li>
</ul>

<p>This video walks through an example, however some of the syntax has changed since the video was created. Here is the main TS file for my project on <a href="https://github.com/katiewhelan/Collections/blob/master/functions/src/index.ts">Github</a> The trickiest part of getting the functions to work was spacing, if the spacing was not perfect the function fails to upload. After getting one function to run it was easiest to copy and paste instead of trying to retype the next function.</p>
<p>Another tip - If you are adding/updating functions you can deploy <a href="https://firebase.google.com/docs/functions/manage-functions">specific</a> functions, by default "firebase deploy --only functions" deploys all functions even if they have not changed.</p>
<br />
<iframe width="350" height="200" class="center" src="https://www.youtube.com/embed/3Z0V3cvgns8" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
{{< /rawhtml >}}
