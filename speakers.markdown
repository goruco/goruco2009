---
layout:   default
title:    Speakers - GoRuCo 2009
author:   Francis
template: speakers
---

Speakers
=====

<a name="brown"></a>

## [Gregory Brown](http://blog.majesticseacreature.com/) Where is Ruby *really* heading?

<div class="headshot">
<img src="/images/greg_brown.png">
</div>

For those who want to run a standard Ruby build, we've got Ruby 1.8.6,
Ruby 1.8.7, and Ruby 1.9.1 to choose from.  This alone can create
confusion for the uninitiated as well as complications for the
seasoned Ruby veteran.   But our choices are actually far more diverse
than that.   While alternative implementations may have previously
been a concern only for language design geeks, the chances that you'll
encounter JRuby, MacRuby, and even Rubinius in the wild become greater
each day.  Throw things like Sapphire and "Ruby Enterprise Edition"
into the mix and you end up with a perfect storm of WTF on your hands
with a side order of FUD.

If we try to answer the question "Which Ruby Should I Use?", the
answer is invariably "It Depends".  This talk will give the audience a
chance to see what the variables are and help them reach the sweet
spot based on several common needs.  It will also hint at the
challenges involved in writing implementation agnostic Ruby code, to
give those who can't make up their minds something to chew on as well.

Gregory Brown is the author of "Ruby Best Practices" and an
all-around crunchy person.  He took off half a year in 2008 to work on
the PDF generation library Prawn, supported by the kindness of the
Ruby community.  Gregory lives in New Haven, CT with his girlfriend,
some small animals, and a bamboo plant that seems to live without
water.


<a name="howerton"></a>

## [Jake Howerton](http://jake.howmeta.com/) Into the Heart of Darkness: Rails Anti-Patterns

<div class="headshot">
<img src="/images/jake_howerton.png">
</div>

Everybody has hopefully heard the term "code rot". This talk will be
one part guided tour and one part expos&eacute; on the phenomenon within
Rails projects. Since Rails' release in July 2004, it has served as a
beacon of light for many developers, but there is a nasty underbelly
to this story. With the growth of its popularity, these problems have
become widespread enough to foster an entire 'Rails Audit' and 'Rails
Rescue' microindustry. We have all been guilty of writing terrible
code or making bad technical decisions at one point or another, but we
need not be held hostage to or be ignorant of these issues.

This talk will:

<ul class="bullets">
<li>explain some of the most common Rails anti-patterns</li>

<li>prove these things actually happen in the real world by showing code that I or others have actually written and pushed into production systems (method and class names may be changed to protect the innocent)</li>

<li>explain how to identify these issues within your code base</li>

<li>help you determine how bad (or good) your current situation is</li>

<li>introduce tools for ensuring they do not creep back in (cucumber, CI, etc)</li>

<li>show you how to measure their reduction and your progress back to the light</li>
</ul>

Jake Howerton is a developer from Brooklyn, NY. Jake has been a
(relatively) active member of #nycrb and been working professionally
with Ruby and Ruby on Rails projects since late 2005. Jake has served
as the Chief Technologist of startup space Sunshine Suites, and is
currently working to help scale infrastructure for TuneCore.com. Some
might say that Jake has an unhealthy obsession with entrepreneurial
pursuits, economic theory, and backpacks.


<a name="katz"></a>

## [Yehuda Katz](http://yehudakatz.com/) From Rails to Rack: Making Rails 3 a Better Ruby Citizen

<div class="headshot">
<img src="/images/yehuda_katz.png">
</div>

Rails 3 is on its way, and Yehuda Katz is giving attendees a sneak peek! With the advent of the Rack spec and library, Ruby web frameworks can interact in unprecedented ways. Imagine a Rails application routing to a Sinatra application, or Merb-style exception pages that catch exceptions from Rails or Cloudkit. These are focal points of Rails 3 and Yehuda's talk.

The idea is simple: create a tiny API for interaction between elements of a web application. Instead of requiring special mechanisms for tests, controller instantiation, or CSRF forgery protection, design apps as a collection of such elements strung together into a stack. As with Unix pipes, limiting the interaction between elements makes powerful combinations a snap.

Merb 0.9 was rebuilt from the ground up to take advantage of Rack, and Rails has begun incorporating it as well. Rails 3 will make Rack a fundamental part of the framework.

Join Yehuda and talk about how this powerful idea is informing Rails 3, and how it will change the way you develop.

Yehuda Katz is currently employed by Engine Yard, and works full time as a Core Team Member on the Rails and Merb projects. He is the co-author of jQuery in Action and the upcoming Rails 3 in Action , and is a contributor to Ruby in Practice. He spends most of his time hacking on Rails and Merb, but also on other Ruby community projects, like Rubinius and Datamapper. And when the solution doesn't yet exist, he'll try his hand at creating one--as such, he's also created projects like Thor and DO.rb.


<a name="mchugh"></a>
## [Eleanor McHugh](http://slides.games-with-brains.net/) The Ruby Guide to \*nix Plumbing

<div class="headshot">
<img src="/images/eleanor_mchugh.png">
</div>

During the course of this talk Eleanor will look at Ruby's support for the \*nix process model and explore some of the cool ways this can be exploited to create multi-process applications suited to today's multi-core systems.

London-based hacker Eleanor trained as a physicist and for the last thirteen years has worked on real-time software systems ranging from safety-critical cockpit avionics to mission-critical broadcast automation. She's always enjoyed high-level languages and discovered the Joy of Ruby in 2001. Since 2005 she's worked predominantly with the Ruby and related technologies with a particular interest in low-level networking and application scalability.

<br style="clear:both" />


<a name="metz"></a>
## [Sandi Metz](http://sandimetz.com/) SOLID Object Oriented Design

<div class="headshot">
<img src="/images/sandi_metz.png">
</div>

While TDD is universally accepted in the Ruby community, the design principles that underlay OOD are much less widely practiced. That's both too bad and to our detriment.  Even a little bit of knowledge about OOD leads to improved code and simplified tests.  Over the lifetime of an application, good design provides significant payback.

The talk will cover all the SOLID principles:

<ul class="bullets">
<li>Single Responsibility</li>

<li>Open Closed</li>

<li>Liskov Substitution</li>

<li>Interface Segregation</li>

<li>Dependency Inversion</li>
</ul>

... and give examples of the effect that following them would have on TDD.

Sandi Metz works for Duke University in Durham, NC, is a member of the newly formed West End Ruby Group on Carborro, NC. and is one of the many DevChix. She's been working in Ruby and Rails for over 4 years (since 0.13) and has an ongoing and active interested in all things OOD.


<a name="stein"></a>
## [Benjamin Stein](http://benjaminste.in/) Building Cross Platform Mobile Apps with Ruby & PhoneGap 

<div class="headshot">
<img src="/images/benjamin_stein.png">
</div>

Surging popularity for rich mobile applications has left many once
cutting edge Ruby developers feeling left behind. Developing for
Android, the iPhone, and Blackberry requires completely different
skill sets (Objective-C, Java, and new APIs).  And just serving up a
lite version of your customer's web site is only a half-baked
solution.

Consider this alternative technology stack for mobile devices:
<ul class="bullets">
<li>The WebKit rendering engine on phones lets you build applications
with standard HTML, CSS and Javascript.  Web content can live locally,
remotely, or both.</li>
<li>The HTML 5 specification gives you local persistent storage via a
Javascript interface to SQLite.</li>
<li>The PhoneGap project (http://phonegap.com) exposes all the new
exciting mobile features (GPS, accelerometer, phone, vibration, sound)
through a common Javascript API.</li>
</ul>

Now Rubyists can create "native" mobile applications for all 3
platforms simultaneously using their favorite web development tools.
And all the business logic can be served directly from their RESTful
Rails application!

Ben is the co-founder and CTO of Mobile Commons, a mobile
technology company focusing on SMS & voice applications.  He is active
in the New York City Ruby community and a contributer to a number of
open-source Ruby libraries.


<a name="yoder"></a>
## [Dan Yoder](http://rubywaves.com/) Resource-Oriented Architecture With Waves

<div class="headshot">
<img src="/images/daniel_yoder.png">
</div>

REST is a much talked about but often misunderstood architectural style. The application and benefits of REST are seen throughout the Web itself. Yet most Web frameworks focus on hiding the Web (HTTP in particular) behind an MVC facade. This creates obstacles to using what is, without question, the most successful distributed applications architecture ever devised. Waves, a Ruby architectural framework for developing more consistently with REST, attempts to remove this obstacle between the programmer and the Web.

This talk will focus on the benefits of REST and resource-oriented architecture and how Waves delivers those benefits to the programmer. We will go beyond the basic GET, PUT, POST, DELETE paradigm and into the "real" REST of content-type negotiation, layered architecture, and more. We will show examples of Waves services built using REST principals can be more easily reused and repurposed than more typical RPC-style "REST-light" services.

Dan has over two decades of experience in all aspects of the software business. He has been using Ruby for over three years and is the author of the resource-oriented Web application framework Waves as well as numerous other gems, including AutoCode, Functor, and Filebase. He has spoken on Waves at LoneStar RubyConf, RubyConf, and has been invited to speak at the first LA RubyConf. He is the Director of Development at AT&T Interactive R&D, where Ruby and Rails applications handle several million HTTP requests every day. Dan helped start the LA Ruby users' group, helping bring on AT&T Interactive as a major sponsor. His development group is also responsible for one of the first voice-enabled local search apps for the iPhone, Speak4It.

