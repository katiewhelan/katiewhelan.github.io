---
title: "TabBar"
date: 2021-03-28T20:03:58-05:00
draft: false
---
{{< rawhtml >}}
<br />
{{< /rawhtml >}}

***
{{< rawhtml >}}

<p>One of the core components of my application was the tab-bar controller to allow the user to switch from the collections section to the search functionality. I struggled to get this functionality working due to the minor detail that to add buttons to the tab bar you could not use a view controller but rather needed to use a tab-bar controller as the base. I was able to add buttons <a href="https://stackoverflow.com/questions/35106022/adding-buttons-to-toolbar-programmatically-in-swift">programmatically</a> to the tab-bar and build without errors however the buttons did not appear. </p>
<br />
<img src="/images/swift/collect/TabController.gif" class="centergif">
<br />
<p>This Youtube tutorial was great tool in understanding how the tabBar controllers and view controllers work together and finally allowed me to get the functionality I wanted for my app.</p>

<br />
<iframe width="350" height="200" class="center" src="https://www.youtube.com/embed/Nx3qPQ_qOFM" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
{{< /rawhtml >}}
