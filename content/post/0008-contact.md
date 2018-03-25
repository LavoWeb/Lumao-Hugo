+++
date = "2017-04-09T16:11:14+01:00"
title = "Contact Lumao"
draft = false
slug = "contact"
+++
Please contact us with that form.
<form class="contact-form"  action="https://formspree.io/aurelien@lavoweb.net" method="POST">
    <div class="row">
        <div class="col-md-6">
            <input class="form-input" type="text" placeholder="Name" name="name" required/>
        </div>
        <div class="col-md-6">
            <input class="form-input" type="email" placeholder="Email" name="_replyto" required/>
        </div>
    </div>
    <input type="hidden" name="_subject" value="Contact Lumao" />
    <input type="hidden" name="_next" value="{{ .Site.BaseURL }}post/merci/" />
    <input type="hidden" name="_format" value="plain" />
    <input type="text" name="_gotcha" style="display:none" />
    <textarea class="form-input" placeholder="Your Message" name="message"></textarea>
    <input class="btn form-btn" type="submit" value="Send your message"/>
</form>