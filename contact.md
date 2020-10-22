---
layout: page
title: Contact
tagline: Create a contact form and you are good to go
ref: contact
order: 1
---

<form
  action="https://formspree.io/f/xyybwdgg"
  method="POST"
>
  <label>
    Your email:
    <input type="text" name="_replyto">
  </label>
  
  <br>
  <br>
  
  <label>
    Your message:
    <textarea name="message"></textarea>
  </label>

  <!-- your other form fields go here -->

  <button type="submit">Send</button>
</form>

[Go to the Home Page]({{ '/' | absolute_url }})
