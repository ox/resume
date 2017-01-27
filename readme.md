# Artem Titoulenko #

email: <artem.titoulenko@gmail.com>  
github: [github.com/ox](http://github.com/ox)  
twitter: [@ox](http://twitter.com/ox)  

## EXPERIENCE

#### Spring (November 2013 - May 2016)

+ Software engineer at an early-stage startup, helped build a lot of first iterations of many pieces of software for the company.
+ Worked with a UI/UX designer on prototyping and building out a vendor-facing product management system, used by all 1000+ vendors. The product management system allowed vendors to import, sync, upload products from their inventory systems (like Magento, Shopify, Demandware, csv imports, etc) or to use Spring's. The system also allowed brands to control the way their brand page looking in the iOS app, schedule product releases, offer discounts, and manage a marketing calendar.
+ Built a variety of admin tools for the Concierge (customer support) team that enabled them to trace order history and resolve issues.
+ Collaborated on backend systems that normalize and keep remote inventory system products in sync with our DB, and how product changes affect customer purchases.
+ Part of small team tasked with rebuilding the [homepage](https://www.shopspring.com), so that users could also shop on the web, track their orders, and explore other brands. Additionally worked on SEO-focused changes to make products on the site show up higher in search results, building sitemaps for crawlers, and regularly exporting PLAs to Google Shopping. Our web team was extraordinarily successful and was eventually responsible for the majority of revenue across the company.

#### Medium (Intern, June 2013 - August 2013)
+ Intern, specializing in backend architecture and supporting libraries.
+ Updated and maintained Dynamite, our home-grown DynamoDB client.
+ Refactored, updated, and maintained zcache, our cache layer management and interface library.
+ Collaborated with our Platform circle to decrease system latency six-fold and improve internal response times many more times than that.
+ Worked on admin tools and patched vulnerabilities in user-facing services.

#### Codecademy (Contractor, Intern, March 2012 - August 2012)
Contractor and Intern, frontend and backend. Designed and implemented a service to allow asynchronous message passing from a Rails app or Sidekiq process to the client via websockets for thousands of concurrent users. I also added feedback functionality to various parts of the site and even created a few courses to show off jQuery functionality.

#### HackerSchool, Batch[0] Summer 2011
I was part of the first batch of HackerSchool students. I dove into the depths of Ruby and created quite a few small projects and experiments, mainly around tracking programmer productivity. I also experimented with Clojure and tweaked some forked Lisp interpreters to experiment adding functionality to a standard library.

## EDUCATION

BS in Computer Science from Rutgers University since the Winter of 2013.

## NOTABLE PROJECTS

#### [ZCache](https://github.com/Obvious/zcache)

During my time at Medium I helped extend and develop zcache, a multi-tiered caching system for node apps. Groups of services like Redis and MemCached can be organized as cache layers, like in a processor, and manipulated as if they were a single cache. These could then further be tweaked to invalidate cache items sooner or later, and querying for a set of items would search all cache layers (if necessary) to reduce database queries and improve application performance. It is used extensively in Medium and has helped reduce application latency by many orders of magnitude.

#### [Dynamite](https://github.com/Obvious/dynamite)

One of my first Medium projects was an extensive update and refactoring of their promise-based DynamoDB client Dynamite. It provides a very elegant and straight-forward interface to interact with DynamoDB and is an integral part of the Medium application. We also wrote a fake DynamoDB engine to test Dynamite queries against so testing is performed locally and doesn't incur AWS costs.

#### [Angstrom](https://github.com/ArtemTitoulenko/angstrom)

An evented, actor-based server for Ruby that scales horizontally. The purpose of the project initially was to create a framework similar to [Brubeck](http://brubeck.io), however it turned into a journey of self-discovery and reading Ruby internals documentation. The framework turned into an exploration of actor-based systems, using mongrel2, and finding a way to work around the GIL. Angstrom has been on the back burner but at the time it outperformed Sinatra.

## TECHNOLOGY

**Languages**: Go, Node, React, Ruby, C, Processing  
**Systems**: \*nix, Mac OSX, iOS  
**Frameworks**: React, Angular, Express, Matador, Sinatra, Rails, openFrameworks  
**Buzzword Tools**: Git, AWS, ElasticBeanstalk, Docker, ECR, Redis, Heroku, Postgresql, MongoDB, DynamoDB, Phabricator  
