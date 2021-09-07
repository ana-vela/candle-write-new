---
layout: default
title: Contact Me Page
---

Want to get in touch? Just fill out this form and I'll reply as soon as I can. 

<form name="contact" value="contact" method="post" netlify-honeypot="bot-field" action="/thanks" enctype="application/x-www-form-urlencoded" data-netlify="true">
<input type="hidden" name="bot-field" />
<input type="hidden" name="form-name" value="contact" />
  <p>
    <label>Your Name: <input type="text" name="name" /></label>   
  </p>
  <p>
    <label>Your Email: <input type="email" name="email" /></label>
  </p>

  <p>
    <label>Message: <textarea name="message"></textarea></label>
  </p>
  <p>
    <button type="submit">Send</button>
  </p>
</form>
