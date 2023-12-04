---
title: "Contact Me"
description: Contact BinaryDigit
date: 2023-12-01
---

<form name="contact" class="contact-form width-normal" action="/thankyou/" method="POST" netlify>
    <input type="hidden" name="form-name" value="contact" />
    <!-- Text input-->
    <div class="form-group">
        <label class="col-md-4 control-label" for="Name"></label>
        <div class="col-md-4">
            <input id="contact-form-name" name="Name" type="text" placeholder="Name" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <br>
    <!-- Text input-->
    <div class="form-group">
        <label class="col-md-4 control-label" for="Email"></label>
        <div class="col-md-4">
            <input id="contact-form-email" name="Email" type="email" placeholder="Email Address" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <br>
    <!-- Text input-->
    <div class="form-group">
        <label class="col-md-4 control-label" for="Subject"></label>
        <div class="col-md-4">
            <input id="contact-form-subject" name="Subject" type="text" placeholder="Subject" class="form-control input-md" required="" autocomplete="off">
        </div>
    </div>
    <br>
    <!-- Textarea -->
    <div class="form-group">
        <label class="col-md-4 control-label" for=""></label>
        <textarea class="form-control" id="contact-form-message" name="Message" placeholder="Message" rows="8"></textarea>
    </div>
    <br>
    <!-- Button -->
    <div class="form-group">
        <button class="!rounded-md bg-primary-600 px-4 py-2 !text-neutral !no-underline hover:!bg-primary-500 dark:bg-primary-800 dark:hover:!bg-primary-700" role="button" type="submit" value="Submit" id="Form-submit">Submit</button>
    </div>
</form>