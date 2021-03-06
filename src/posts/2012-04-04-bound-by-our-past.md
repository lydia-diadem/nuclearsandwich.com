---
layout: post
title: "Bound by our Past"
date: 2012-04-04 20:43:00 -7
comments: true
categories: Rails, Ruby, Teaching
---

I was about to ask a question on Identi.ca and Twitter, when I realized I would
probably be flamed into oblivion if I didn't explain myself in more than 140
characters.

My question: __Why are we still typing `rake db:migrate` instead of `rails
db:migrate`?__

Before you scoff and walk away. Hear me out. I *get* that Rake is a more general
tool than Rails and we can use it to automate all sorts of cool tasks. In fact
I've been using Rake to do all kinds of bonkers stuff in my projects since I
first started learning Ruby. Teaching at [RailsBridge][] this weekend, I had a
surprisingly high number of students ask "What is rake?". I was really happy
when I got this question so much because it means that they're actually thinking
about what they're typing, which is hugely important. Each time it was asked, my
smile quickly faded. What should I tell them. "Rake is Ruby's Make, It's like
make but in Ruby." would work for anyone who has been using or programming UNIX
for any significant amount of time, but for many Railsbridge students (and many
people learning Rails), Ruby is what will expose them to all of that, so we
can't use it as the base of our teaching metaphor(1).

I settled for "Rake is a tool for automating common tasks in a project. The name
comes from a program called make, but since Rake is written in Ruby, it's Rake."

While my students seemed satisfied with that answer, I sure wasn't. The whole
purpose of Railsbridge is to demystify programming and software development.
We're not trying to build an army of new software developers (but I'd love to),
just trying to grant people some basic coding literacy and comfort. Trying to do
this in an environment where some commands start with `rake` (assets:precompile
is another culprit) and others with `rails` and the only way to know which is to
be in the club already or have someone tell you is suboptimal.

So, developers, why are Rails's built in Rake tasks still Rake tasks and should
we start the discussion of baking them into the Rails command for Rails 4.0?
Without a better answer than "it's always been that way", I think we should.

(1) More information and musings on them forthcoming.
[RailsBridge]: http://railsbridge.org
