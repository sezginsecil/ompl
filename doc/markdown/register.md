# Registration

Registration for OMPL is completely voluntary. We will not spam you with emails. Work on OMPL is funded in part by the National Science Foundation (NSF). It is extremely helpful for us if we can report to the NSF where and how our work is being used. Your cooperation would be highly appreciated.

\htmlonly
<form class="form" role="form" action="http://formspree.io/mmoll@rice.edu" method="POST">
  <div class="form-group">
    <input type="email" class="form-control" name="_replyto" value='' placeholder="Email (optional)">
  </div>
  <div class="form-group">
    <input type="text" class="form-control" name="name" value='' placeholder="School / employer">
  </div>
  <div class="form-group">
    <b>I plan to use OMPL for (check all that apply)</b>
    <div class="checkbox"><label><input type="checkbox" name="research" value='yes'>research</label></div>
    <div class="checkbox"><label><input type="checkbox" name="education" value='yes'>education</label></div>
    <div class="checkbox"><label><input type="checkbox" name="industry" value='yes'>industrial applications</label></div>
  </div>
  <div class="form-group">
    <textarea id="message" name="message" rows=6 class="form-control" placeholder="Comments / suggestions (optional)"></textarea>
  </div>
  <input type="hidden" name="_next" value="thank-you.html" />
  <input type="hidden" name="_subject" value="=== OMPL registration ===" />
  <input type="hidden" name="IP" id="IP">
  <script type="application/javascript">
    window.onload = function () {
    $.getJSON("https://api.ipify.org?format=jsonp&callback=?",function(json){$("#IP").val(json.ip);});};
  </script>
  <input type="text" name="_gotcha" style="display:none" />
  <input type="submit" value="Send" name='submit' class="btn btn-primary" />
</form>
\endhtmlonly