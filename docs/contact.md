---
title: "Jimmy's Zoo"
description: "Contact Us"
---
{% include navigation.md %}

<form id="imagesubmit" method="POST" action="https://formspree.io/bwart@marketo.com">
  <input type="hidden" name="_subject" value="The Scrum Zoo: Contact Submission" />
  <input type="hidden" name="_gotcha" style="display:none" />
  <input type="hidden" name="_next" value="https://bwart-mkto.github.io/scrum_zoo/thankyou" />
  <input type="hidden" name="_cc" value="sfabini@marketo.com,kbielewicz@marketo.com,mfenwick@marketo.com,talkhateeb@marketo.com" />
Email<br/><input type="email" name="email" placeholder="Your email" /><br/>
Subject<br/><input type="text" name="subject" placeholder="Subject" /><br/>
Message<br/><textarea placeholder="Your message"></textarea><br/>
  <button type="submit">Submit</button>
</form>
<script>
    var imagesubmit =  document.getElementById('imagesubmit');
    contactform.setAttribute('action', '//formspree.io/' + 'bwart' + '@' + 'marketo' + '.' + 'com');
</script>
