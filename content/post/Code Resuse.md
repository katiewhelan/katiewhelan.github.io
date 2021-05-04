---
title: "Refactoring"
date: 2021-03-29T20:03:58-05:00
draft: false
---
{{< rawhtml >}}
<br />
{{< /rawhtml >}}

***
{{< rawhtml >}}
<p>Originally I had multiple collection types of Books, Movies and Dvds.  Each of these collections had specific fields, many of which overlapped. Refactoring to a single collection type offered multiple benefits.</p
<ul>
<li>Reuse Single Storyboard</li>
<li>Single Controller vs Controller per Type</li>
<li>Extensibility</li>
<li>Remove Multiple Switch Statements</li>
<li>Allow Multiple Item Types in Collection</li>
</ul>
<p>This is just a single example of how switching from multiple collection types to a single collection type made my code reusable and more extensible to adding other collection types.  All over the code switch statements were checking the collection type to decide a specific code path for the item type, now there is a single code path and adding a new item will not change that.</p>

 <p>The original code had to make multiple query calls since each collection type was stored in a separate firebase collection. With this code adding a new item type would mean adding a new query and another case to the switch statement. </p>
 <img src="/images/swift/collect/OriginalCode.png" class="center" width="650" height="550">
 <br/>
 <p>This updated code only searches a single query since all items are stored in a single Firebase collection. A collection can now include multiple types which allows users more options when creating a new collection. </p>
<img src="/images/swift/collect/CodeRefactor.png" class="center" width="650" height="550">



{{< /rawhtml >}}
