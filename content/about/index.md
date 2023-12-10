---
title: "About & Contact"
description: About BinaryDigit
date: 2023-11-10

---
<img src="BinaryDigit.png" alt="BinaryDigit" width="300"/>

I’m B, a Xennial who grew up when the internet was young, just as I was. My family bought our first computer in 1997, and I become fascinated with how computers worked, how the web evolved, and being online a bit too much!

I'm originally from New York and currently living in Michigan.  My work background is in tech (I was a systems engineer, part time web dev, and now a manager). I would love to find more diverse folks in gaming, tech, music and all things creative. I love to travel, take photos, game on my PC, PS5 and Switch, stream, tweak code and always learning something new. ✨

I’m doing a digital overhaul for the next few months and would like to make this site a digital garden, or in my case, a _digital cafe_; a personal space to gather projects, what I'm working on, thoughts, and notes. You can read about my projects or get in touch with me below.

<hr>

## Email
You can write to me: ```hi@binarydigit.cafe```

<hr>

## Contact Form

<form name="contact" class="contact-form width-normal" action="/thankyou/" method="POST" netlify-honeypot="bot-field" netlify>
    <p class="hidden">
        <label>
        Don’t fill this out if you’re human: <input name="bot-field" />
        </label>
    </p>
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