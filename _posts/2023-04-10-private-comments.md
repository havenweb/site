---
layout: post
title: "Haven Blog"
meta-title: "Private Comments, or Why I’m Down On Webmentions"
meta-description: "The bulk of existing social media is about interacting in public, but there is a huge value in exploring what these systems look like if commenting is a private affair"
---
<img class="default" src="/assets/images/locked_conversation.jpg" alt="A speech bubble with a padlock on it." />

I love the IndieAuth community, I love what they stand for, and I love a lot of the technology they’ve built and defined.  But I have a hard time getting behind Webmentions, even though they clearly solve a problem that exists and the people who use them love them.  What’s going on here?

First, some background.  The [IndieWeb](https://indieweb.org/IndieWeb) community wants an internet that isn’t dominated by a few giant silos.  They want the internet to be free and open with a rich diversity of ways to interact with it.  When all of your posts and status updates live inside of Facebook or Twitter, then you don’t really own them.  The only way people can see them is to go to Facebook or Twitter and accept whatever comes with that relationship.  The IndieWeb is big on hosting your own content–maybe syndicating it to places like Facebook and Twitter–but making sure you have it available on your own website.

It is relatively easy to build a blog with Wordpress or Hugo or something else that publishes an RSS feed.  But we are social creatures and one thing that “Web 2.0” taught us was people like to talk and discuss.  The people want comments!  Technically, things get harder when the web gets social–especially when you want to keep owning your content.  The IndieWeb community suggests that owning your content means posting a comment on your own site, and telling the original poster that you’ve got a comment at your site.

Webmentions are a computer protocol to make this much easier.  Webmentions define how your comment should exist on your site, and how you can tall the original poster (or rather their web site software) about your comment so that it will understand your comment to display it and link back to the source on your site.

There’s even good precedent for this.  Twitter and Mastodon both work with a very similar semantic.  When you tweet (or toot) a reply, that’s still a tweet you posted which shows up on your own timeline.

Twitter is a great example too of the issue I take with not just Webmentions, but the model itself.  When anyone with lots of followers tweets something, they get inundated with reply tweets.  Reply tweets have to go through the same algorithmic filtering and ranking to try and separate the signal from the noise.  These are the same algorithms that we [bemoan for amplifying misinformation](https://barackobama.medium.com/my-remarks-on-disinformation-at-stanford-7d7af7ba28af).  But however poorly implemented they are, we need something that plays that role when we want to have anything approaching a useful view of public content where truly anyone can post.  When anyone can post the first problem you run into is spam–before we even get to what legitimate content should be promoted.

And spam is the core of the problem I have with Webmentions.  They are a tool for letting anyone make unauthenticated posts on your own site.  Today, they are only used by a small group of people within the IndieWeb community–and with such limited usage, there isn’t much value to spammers–but with broader adoption spam would become a huge problem.  

To be fair to the IndieWeb community, I'm not the only person who is worried about spam's impact on Webmentions.  Wouter Groeneveld has a great article on his website about [combating Webmention spam](https://brainbaking.com/post/2022/04/fighting-webmention-and-pingback-spam/).  He talks a lot about technical details, but ultimately builds for his own site, a content-moderation dashboard to manually approve or reject Webmentions from unknown source.

Before I built Haven, I tried to build a private blog on Wordpress.  I locked down self-signups with various plugins and I still had to wade through automated spam signup attempts (which were presumably hitting an exposed API directly) every day.  Based on that experience, I don’t even think that requiring manual approval of Webmention replies would be a great solution.  It improves the reading experience for people who visit your site, but forces you as the site owner to do a lot more work curating responses.  

So what is the solution?  The people want comments!  How do we give them comments?  

The answer is two-fold, and it depends on what kind of posting you do.  For very popular publishers, or news organizations that really want to engage with the public in their writing, something like Webmentions would be fine, but the publisher needs to devote the effort to curating the responses.  A great example of this is Scott Alexander of [Astral Codex Ten](https://astralcodexten.substack.com/).  He allows open comments on his posts which he [moderates heavily](https://astralcodexten.substack.com/p/open-thread-249).  A little while after a post, he will often make a separate post with [highlights from the comments](https://astralcodexten.substack.com/p/highlights-from-the-comments-on-bobos). Engaging with an unauthenticated public community is a lot of work and we shouldn’t be satisfied with publishers who add a comment box without actually engaging with their audience.

For the rest of us who publish socially, I don’t really believe in public comments.  This shouldn’t be much of a surprise, I built Haven because I don’t really believe in public posting in a social context to begin with.  But, we can have something much more interesting.  When you post on your Haven or any other private blog, that post only goes to people who have access to your Haven–your friends and family.  The most interesting conversations that I have about what’s going on in the world are conversations with (surprise!) my friends and family.  What if Haven and other social feed readers let you make comments on public posts, but only shared those comments with people on your Haven.  Now we have _private conversations_ about _public content_.  That is the vision I have for comments on Haven.

Just to be clear, this doesn’t exist yet in Haven–it is still a vision, but one I’m really excited about!  Today you can let your visitors comment on your own Haven posts, and you can make a post with a link to some public post to talk about it; but these features aren’t built into the reader to make them a pleasure to use.

So that’s it!  I’m down on Webmentions because their success and popularity will destroy their usability thanks to spam, but a similar model that enables private discussion on public content–right in your feed–could be a real game changer in how we interact socially on the internet.

