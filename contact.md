---
layout: page
---

<style>
#exampleSelectInput1 {
  height: 200px;
}

select > option {
    font-size: x-large;
}
</style>

<form action="http://formspree.io/joshua.thorild.hull@gmail.com" method="POST">
<input type="hidden" name="_subject" value="Hull Cloud Concepts Contact Submission" />
<input type="hidden" name="_next" value="//joshua-hull.github.io/cloudconsulting/thank-you" />
<div class="form-group">
    <label for="exampleInputEmail1">Email Address</label>
    <input type="email" name="_replyto" class="form-control" id="exampleInputEmail1" placeholder="Email">
</div>
<div class="form-group">
    <label for="exampleSelectInput1">Services</label>
    <select multiple class="form-control" name="services" id="exampleSelectInput1">
      <option>Shared Hosting</option>
      <option>Dedicated VPS Hosting</option>
      <option>Domain Registration / Hosting</option>
      <option>Custom Development</option>
    </select>
</div>
<div class="form-group">
    <label for="exampleTextArea1">Comments / Questions</label>
    <textarea class="form-control" rows="3" name="comments" id="exampleTextArea1"></textarea>
</div>
<input type="text" name="_gotcha" style="display:none" />
<input type="submit" class="btn btn-default" value="Submit" />
</form>
