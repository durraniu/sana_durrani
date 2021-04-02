---
# An instance of the Contact widget.
# Documentation: https://sourcethemes.com/academic/docs/page-builder/
widget: contact

# This file represents a page section.
headless: true

# Order that this section appears on the page.
weight: 130

title: Contact
subtitle:
---

<form action="https://formspree.io/f/mgerevke" method="POST">
  <label for="name">Your name: </label>
  <input type="text" name="name" required="required" placeholder="here"><br>
  <label for="email">Your email: </label>
  <input type="email" name="_replyto" required="required" placeholder="here"><br>
  <label for="message">Your message:</label><br>
  <textarea rows="4" name="message" id="message" required="required" class="form-control" placeholder="I can't wait to read this!"></textarea>
  <input type="hidden" name="_next" value="/html/thanks.html" />
  <input type="submit" value="Send" name="submit" class="btn btn-primary btn-outline">
  <input type="hidden" name="_subject" value="Website message" />
  <input type="text" name="_gotcha" style="display:none" />
</form>
