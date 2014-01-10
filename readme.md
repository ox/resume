# Artem Titoulenko #

email: <artem.titoulenko@gmail.com>  
github: [github.com/ox](http://github.com/ox)  
twitter: [@ox](http://twitter.com/ox)  

## OBJECTIVE ##

My objective is to explore the realm of user interaction and perception. I enjoy creating works that challenge expectations and do so in a way that smoothly guides and enlightens the user. Ultimately, I seek to create beautiful and easy to use works which stem from my experiences to deliver profound meanings to the user, be it in art or through the web.

## EDUCATION ##

Graduated Rutgers University in the Winter of 2013 with a BS in Computer Science.

## TECHNOLOGY

**Languages**: Go, JS, Ruby, C, Processing  
**Systems**: \*nix, Mac OSX, iOS  
**Frameworks**: Express, Matador, Sinatra, Rails, openFrameworks  
**Tools and Services**: Git, (Thin, Mongrel2, Unicorn), Heroku, AWS, Redis, MongoDB, DynamoDB  

## EXPERIENCE

#### Medium (June 2013 - August 2013) ####
Intern, specializing in backend architecture and supporting libraries. I updated and maintained Dynamite, our home-grown DynamoDB client. I also refactored, updated, and maintained zcache, our cache layer management and interface library. I collaborated with our Platform circle to decrease system latency six-fold and improve internal response times many more times than that. I also worked on admin tools and patched vulnerabilities in user-facing services.

#### Codecademy (March 2012 - August 2012) ####
Contractor and Intern, frontend and backend. Designed and implemented a service to allow asynchronous message passing from a Rails app or Sidekiq process to the client via websockets. The system scales linearly. I also added feedback functionality to various aspects of the site and even created a few courses to show off jQuery functionality.

#### HackerSchool, Batch[0] Summer 2011 ####
I was part of the first batch of HackerSchool students. I dove into the depths of Ruby and created quite a few small projects and experiments. I also experimented with Clojure and tweaked some forked Lisp interpreters.

#### BeenVerified Inc. (July 2010 - September 2010) ####
Played the tools and product developer role. I developed server maintenance software, and hacked away at the core product to kill bugs. I experimented with new tech and methodologies with peers to speed up our large app and decreased bandwidth and resource usage many fold.

#### NUICode (December 2008 - August 2009) ####
Spearheaded development of this Ruby on Rails application. It is a private project management tool I crafted especially for NUI Inc. Features usage-analytics, data warehousing, and bug tracking with user roles, as well. We achieved over 300,000 downloads of our tools and files with this app.

#### Community Core Vision (December 2008 - August 2009) ####
Previously called TBeta, CCV aims to simplify blob tracking utilizing cameras. I constructed most of the framework, ported it to new tools and software, and created an API and hooks to extend its capabilities to any C++ code. Co-Lead Developer with Seth Sandler.

#### Animo (October 2008) ####
Animo is a large-scale, distributed computing project which featured 8 different computers and cameras communicating and performing together to create a human-sized stop-motion animation across a wall 50 ft in length. Code Assistant to Zachary Lieberman.

## NOTABLE PROJECTS

#### [ZCache](https://github.com/Obvious/zcache)

During my time at Medium I helped extend and develop zcache, a multi-tiered caching system for node apps. Groups of services like Redis and MemCached can be organized as cache layers, like in a processor, and manipulated as if they were a single cache. These could then further be tweaked to invalidate cache items sooner or later, and querying for a set of items would search all cache layers (if necessary) to reduce database queries and improve application performance. It is used extensively in Medium and has helped reduce application latency by many orders of magnitude.

#### [Dynamite](https://github.com/Obvious/dynamite)

One of my first Medium projects was an extensive update and refactoring of their promise-based DynamoDB client Dynamite. It provides a very elegant and straight-forward interface to interact with DynamoDB and is an integral part of the Medium application. We also wrote a fake DynamoDB engine to test Dynamite queries against so testing is performed locally and doesn't incur AWS costs.

#### [Angstrom](https://github.com/ArtemTitoulenko/angstrom)

An evented, actor-based server for Ruby that scales horizontally. The purpose of the project initially was to create a framework similar to [Brubeck](http://brubeck.io), however it turned into a journey of self-discovery and reading Ruby internals documentation. The framework turned into an exploration of actor-based systems, using mongrel2, and finding a way to work around the GIL. Angstrom has been on the back burner but at the time it outperformed Sinatra.

#### [Micro Army](https://github.com/ArtemTitoulenko/microarmy)

This is a tool to quickly turn on some number of AWS micro instances and have them perform a given script at the same time. It has been used to load test different types of services at Codecademy and can be employed for many other tasks. The code is a fork of the original [Micro Army](http://github.com/j2labs/microarmy) by [James Dennis](http://github.com/j2labs).
