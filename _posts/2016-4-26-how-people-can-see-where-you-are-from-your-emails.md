---
layout: post
last-modified: '2016-04-25T12:00:00'
crosspost_to_medium: true

title: "How other people can see where you are by looking at your emails"
subtitle: "A simple way people can tell where you're currently located"
cover_image: mapscreen.png
cover_image_caption: "Insecure Email Headers"

excerpt: "...every email contains information about the IP address of the original sender. That IP address can be used to get a pretty precise location. Combine that with the near instant delivery of email and you might as well be wearing a tracking tag like someone on release from prison."

author:
  name: Daniel Caffrey
  twitter: topsecureemail
  bio: Technical Lead at Topmail.com
  image: dcaffrey.png  
---
Imagine for a moment you've told your Mother-in-law you can't make it to her party this weekend, because you and your husband are having a romantic weekend away. As it happens it's a small white lie. The kind we all tell everyday. Which we're perfectly entitled to tell, because we have our own private lives, but we don't want to hurt people's feelings. The truth is, you're both exhausted from work and just want to stay at home. But the weekend away story sounds better and it's final.

Now imagine, you're lolling on the sofa at home, reading something on the phone and you see an email from your Mother-in-law asking "How's the weekend going? Hope you're having a lovely time!". Not wanting to overdo the white lie you just reply briefly "Great! Thanks for asking". That's a relief. It's off your mind now. A minute later comes the reply:

<b>"I guess you couldn't be bothered to come to my party and preferred to laze about on the sofa at home."</b>

Probably the first thing you do is leap off the sofa. You go over to the window and start scanning the front lawn, the road. It's an uncomfortable feeling, this sudden invasion of your privacy. You have no idea how she knows...

The reality is that there are many, everyday reasons that we all like to feel that our current location is information that we can choose to share or not. But email, like many internet technologies, was designed a long time before any of these issues seemed important. One thing that is built into email by design is that every email contains information about the IP address of the sender. That IP address can be used to get a pretty precise location. Combine that with the near instant delivery of email and you might as well be wearing a tracking tag like someone on release from prison.

So how does a normal, even non-technical person, find out where someone is using this information? Well they probably go to a website like this:

* <b>How to get the email headers</b>: http://www.iptrackeronline.com/how-to-extract-email-headers.php
* <b>Geo-location analysis (with maps) of email headers</b>: http://www.iptrackeronline.com/email-header-analysis.php

It's important to note I don't advocate using this kind of service and I think their lack of a privacy policy, or any clear indication of what they do with the information they are given, means that it can't be recommended. Nonetheless the site itself makes the message clear. It's also important to keep in mind that Gmail (for example) often also removes this information, but <a href='https://support.google.com/mail/answer/26903?hl=en'>NOT ALWAYS</a>.

<a href='https://www.topmail.com'>Topmail</a> is different from most email providers, since we always strip out that identifying information from emails as they are sent. We think, if email was being designed from scratch today, that's exactly how any sensible person would do it.
