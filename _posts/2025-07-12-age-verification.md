---
layout: post
title: "Haven Blog"
meta-title: "Age Assurance and Bluesky"
meta-description: "Bluesky's recent compliance with UK Age Assurange mandates demonstrates the dangers of relying on any centralized platform, no matter how open the protocols."
---
<img class="default" src="/assets/images/age_verification.jpg" alt="Young child getting face scanned by a computer for age verification"/>

This week, the popular Twitter/X alternative Bluesky shared that they're working with Epic Games and the UK Government to do [Age Assurance](https://bsky.social/about/blog/07-10-2025-age-assurance)"&mdash;verifying the age of a user before showing them adult-appropriate content.

At face value, this seems like it would be a good thing, we're protecting children, right?.  Unfortunately, there are some very important details that get glossed over.  

In the United States, if you want to buy movie tickets for an R-rated movie, or buy alcohol, you have to show your ID to the vendor.  The vendor looks at your ID, confirms your age, and allows you to make the purchase.  But the ID is only seen by the checkout person's eyes, the vendor doesn't take a picture of your ID, and store it forever with a record that you saw that movie or bought alcohol on that date.  (More recently, ID barcodes are being scanned which is troubling).  By contrast, Epig Games' Kids Web Services which Bluesky leverages for online age-verification uses "payment card verification, ID scans, and face scans."  Online age-verification technologies require you to share exactly who you are&mdash;not just prove that you are of age.  (Note that there is really cool cryptographic technolgy that _can_ do this, called [Zero Knowledge Proofs](https://en.wikipedia.org/wiki/Zero-knowledge_proof), but I don't know of any platform using that technology).

This is the first major downside, age verification is actually _identity_ verification which prevents free and anonymous access to information.  When your identity is verified, you can't get information about anything without that interest being associated with your identity.  

The second major downside is what gets classified as adult-appropriate content?  In this case it is the UK Government's decision. That means anything the current administration doesn't like, they get to effectively restrict everyone under 18 from seeing.  There is no global consensus around the precise boundaries of adult-appropriate content.  

There's one additional disappointment here, and that is the difference between the promise of Bluesky and what has actually happened.  Bluesky was supposed to be an open protocol so that anyone can participate on the network without being restricted to a single gate-keeper like Twitter/X, Facebook, Instagram, etc.  But the Bluesky protocol requires an app service, which is incredibly difficult to operate and results in almost everyone using the Bluesky-provided app service.  Despite the protocol being open in principle, Bluesky is still able to control everyone's use of the platform. I don't really want to put too much blame on Bluesky, they had a great vision.  Unfortunately one of the downsides of a centralized service (no matter how noble the mission or virtuous the founders!) is the fragility.  A company can be pressured by government laws that may run counter to its mission. For another example: the secure messaging app Signal intends to [leave the UK market](https://www.techradar.com/computing/cyber-security/we-will-not-walk-back-signal-would-rather-leave-the-uk-and-sweden-than-remove-encryption-protections) and be unavailable to UK citizens instead of complying with government demands to weaken the encryption it uses for secure messages.  

What's the alternative?  Decentralized platforms.  If it is easy for you to run your own social media node, then you have full control over what you access, and how you access it.  You have full control over who sees the posts and pictures that you share.

No company or government can get in the way when you take control.  
