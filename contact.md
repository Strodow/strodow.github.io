---
layout: page
title: Contact
sitemap: true
---

<script src="assets/js/jquery.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Your submission has been processed...');
  });
</script>



<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSdNTAHXa6ilBEjjNHoxX6QFi35j6pzsvnozPM8qy9rqsjTKsg/viewform?usp=pp_url" target="hidden_iframe" onsubmit="submitted=true;">
    First name: <br>
    <input type="text" name="firstname">
    Last name: <br>
    <input type="text" name="lastname">
    Email: <br>
    <input type="email" name="email">
    <input type="submit" value="Submit">
</form>
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>