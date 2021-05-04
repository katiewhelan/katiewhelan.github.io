---
title: "Keyboard Placement"
date: 2021-04-10T20:03:58-05:00
draft: false
---
{{< rawhtml >}}
<br />
{{< /rawhtml >}}

***
{{< rawhtml >}}
<p>To improve the user experience on the edit page I wanted the fields to move up the height of the keyboard when the user selected a textfield at the bottom of the page.</p>
<img src="/images/swift/collect/Update2.gif" class="centergif">
<br />
<br />
<p>The tutorials below helped to understand how to get the height of the keyboard and how to move the location of the view up by the height of the keyboard. The tutorials are a bit older. The code
<br />
<br/>
 <code>NotificationCenter.default.addObserver(self, selector: #selector(keyboardWillChange(notification:)), name:NSNotification.Name.UIKeyboardWillShow, object: nil) </code>
<br/>
<br/>
has changed to</p>
<br/>
<img src="/images/swift/collect/KeyboardUpdate.png" class="center">
<br/>
<br/>
<iframe width="350" height="200" class="center" src="https://www.youtube.com/embed/iUQ1GfiVzS0" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
<br/>
<br />
<iframe width="350" height="200" class="center" src="https://www.youtube.com/embed/xVZubAMFuIU" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
{{< /rawhtml >}}
