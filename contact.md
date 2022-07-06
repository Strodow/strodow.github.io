---
layout: page
title: Contact
sitemap: true
---


<form name="gform" id="gform" enctype="text/plain" action="https://docs.google.com/forms/d/e/1FAIpQLSdNTAHXa6ilBEjjNHoxX6QFi35j6pzsvnozPM8qy9rqsjTKsg/formResponse?" target="hidden_iframe" onsubmit="submitted=true;">
    <div class="form-row">
        <div class="form-group col-md-6">
            <label for="firstname" class="col-form-label">First Name</label>
            <input required type="text" placeholder="First Name" class="form-control" name="entry.12059350" id="entry.12059350" xml:id="firstname">
        </div>
        <div class="form-group col-md-6">
            <label for="lastname" class="col-form-label">Last Name</label>
            <input type="text" placeholder="Last Name" class="form-control" name="entry.1508620441" id="entry.15086204410" xml:id="lastname">
        </div>
    </div>
    <div class="form-row">
        <div class="form-group col-md-6">
            <label for="email" class="col-form-label">Email</label>
            <input required type="email" placeholder="Email Address" class="form-control" name="entry.69488973" id="entry.69488973" xml:id="email">
        </div>
    </div>
    <div class="form-row">
        <div class="form-group col-md-12">
            <label for="message" class="col-form-label">Message</label>
            <textarea required placeholder="Let me know how I can help" class="form-control" name="entry.1663185659" id="entry.1663185659" xml:id="message" rows="3"></textarea>
        </div>
    </div>
    <input class="btn btn-primary" type="submit" value="submit">
    <script src="https://www.google.com/recaptcha/enterprise.js?render=6Led6cMgAAAAAARHwmzrzrBZJnCa136gJXE-wpyH"></script>
    <script>
    grecaptcha.enterprise.ready(function() {
        grecaptcha.enterprise.execute('6Led6cMgAAAAAARHwmzrzrBZJnCa136gJXE-wpyH', {action: 'login'}).then(function(token) {
        ...
        });
    });
    </script>
</form>
<iframe name="hidden_iframe" id="hidden_iframe" style="display:none;" onload="if(submitted) {}"></iframe>






<script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
<script type="text/javascript">var submitted=false;</script>
<script type="text/javascript">
$('#gform').on('submit', function(e) {
  $('#gform *').fadeOut(2000);
  $('#gform').prepend('Thank you for your inquiry, I'll get back to you as soon as posible!');
  });
</script>