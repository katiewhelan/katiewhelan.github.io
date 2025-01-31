---
title: "Algolia"
date: 2021-02-26T20:03:58-05:00
draft: false
---

{{< rawhtml >}}
<br />
{{< /rawhtml >}}

***
{{< rawhtml >}}
<p> I chose to add Algolia to my project after learning that I would not be able to do a <a href="https://firebase.google.com/docs/firestore/solutions/search">full text search</a> search with Firebase.</p>


<p> This Demo from <a href="https://www.algolia.com/doc/guides/building-search-ui/resources/demos/ios/#media"> Algolia</a> was exactly what I needed:</p>
<br/>
<img src="/images/swift/AlgoliaDemo.gif" height="350" width="200" class="centergif">
<p class="imageTag">Example Demo from Algolia documentation<p/>



<p> Although Algolia had plenty of good documentation it was hard to set up the functionality needed for this application without over engineering. I started by downloading the <a href="https://github.com/algolia/instantsearch-ios-examples">demo</a> example. Algolia's documentation on basic <a href="https://www.algolia.com/doc/api-reference/api-methods/search/">search</a> functionality was a good starting point but this post on <a href="https://rsfarias.medium.com/how-to-set-up-firestore-and-algolia-319fcf2c0d37">Medium</a> was what helped me to finally get Algolia working with my data.  Returning the data from Algolia was fairly straight forward however working with the JSON to the display the data was more difficult.  The last part of the article above walked through this step by step.  
</p>

<p>I set up example data in Algolia for testing, after I was able to return the data I needed to set up cloud functions so changes made to my Firebase records would automatically update to Algolia. Check out my post on <a href="/post/cloud-functions/">Cloud Functions</a> for more details.0</p>










{{< /rawhtml >}}
