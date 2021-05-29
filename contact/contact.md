---
layout: layouts/base.njk
title: Contact Me
templateClass: tmpl-post
eleventyNavigation:
  key: Contact Me
  order: 3
---
Interesting?

Try to contact me

<form name="contact"  method="POST" netlify-honeypot="bot-field" netlify>
  <p class="hidden">
    <label>Honey-pot:<input name="bot-field" /></label>
  </p>
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

  <p>Do you want to get some super duper emails from me time to time?</p>

  <div>
  <input type="checkbox" id="newsLetter" name="subscribe" value="newsletter"
         checked>
  <label for="newsLetter">yes! definietly</label>
  </div>
</form>