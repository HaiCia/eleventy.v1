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

<form name="contact" netlify>
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