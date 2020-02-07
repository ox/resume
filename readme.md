# Artem Titoulenko

email: artem.titoulenko@gmail.com  
github: github.com/ox  
twitter: @ox  

## EXPERIENCE

#### SVRF, Lead Systems Architect (July 2016)

+ Outlined and led project to create Kubernetes-backed production environment from scratch, with metrics monitoring and logging infrastructure. Our cluster of nodes run: web servers for admin tools and user-facing content viewing services, cron jobs, api servers, a web crawling cluster, media storage and resizing workers, image recognition workers, a multi-stage 3D model optimizing pipeline, as well as a robust and secure ElasticSearch cluster.
+ Wrote the majority of the aforementioned backend services using Node.js to be highly parallelizable and auditable. This included detailed logging + metrics for servers, auditable change histories for crucial data, and a shared PostgreSQL-backed work queue for queue-based workers.
+ Led project to rebuild an aging Angular.js website to React using Next.js with an emphasis on blazing fast loading. As part of the rebuild I also worked with our design team to build a design system to unify the look and feel of our websites and iOS app.
+ Set up alerting for metrics that notifies relevant engineers and provide context for resolving the incident. Along with alerting I wrote up an incident response plan that details the process of coordinating and resolving an outage while keeping customers/partners up to date with the progress being made.
+ Repeatedly led efforts to drastically shorten test times, increase durability of tests, creating a development environment enabling engineers to deploy code with confidence. This included creating an automatic CI/CD system that coordinates deployment of dependent, interrelated services.
+ Upheld code + design standards using tools like eslint and encouraged culture of code reviews for all changes.
+ Focused on getting new engineers up and contributing as quickly as possible through automated setup scripts and extensive documentation, both in code as well as design documents for services and features.

#### Spring (November 2013 - May 2016)

+ Software engineer at an early-stage startup, helped build a lot of first iterations of many foundational pieces of software, all in Go.
+ Worked with UI/UX designers on prototyping and building out a vendor-facing product management system, used by all 1000+ vendors. The system allowed vendors to import, sync, upload products from their inventory systems (Magento, Shopify, Demandware, csv imports, etc) or to use Spring's. The system also allowed brands to control the way their brand page looking in the iOS app, schedule product releases, offer discounts, and manage a marketing calendar.
+ Part of small team tasked with rebuilding the [Spring homepage](https://www.shopspring.com) using React, enabling users to shop, track their orders, and explore other brands on the web. I additionally worked on SEO-focused changes to improve Google Shopping ranking. I built sitemaps for various crawlers, and tools to regularly export PLA to Google Shopping. Our team was extraordinarily successful and was eventually responsible for the majority of revenue across the company.
+ Built a variety of admin tools for the Concierge (customer support) team that enabled them to trace order history and resolve customer issues.
+ Collaborated on backend systems that normalize and keep remote inventory system products in sync with our DB, and how product changes affect customer purchases.
+ Participated in regular on-call rotation, and helped flesh out the monitoring and alerting systems to send alerts to the appropriate people. This reduced engineer frustration (mysterious system failures) and improved time to resolving issues considerably.
+ Maintained on-prem Phabricator instance to facilitate more effective code reviews. I also built several tools with the goal of reducing idle engineering hours and forgotten diffs. These tools reduced turnaround time for code reviews to minutes rather than hours.
+ Worked on testing infrastructure to reduce test duration, improve test result readability, and make testing as painless and consistent as possible. Eventually we were able to reduce average test times from 25 minutes to 3 minutes, all while increasing code coverage.

#### Medium (June 2013 - August 2013)
+ Intern, specializing in backend architecture and supporting libraries.
+ Updated and maintained Dynamite, our home-grown DynamoDB client.
+ Refactored, updated, and maintained zcache, our cache layer management and interface library.
+ Collaborated with our Platform circle to decrease system latency six-fold and improve internal response times many more times than that.
+ Worked on admin tools and patched vulnerabilities in user-facing services.

#### Codecademy (March 2012 - August 2012)
Contractor and Intern, frontend and backend. I designed and implemented a messaging service alongside a Rails app to enable rudimentary user notifications. This sped up the critical path to rendering the next lesson, and maintained the ability to give the user feedback on their progress. I also added feedback functionality to various parts of the site and even created a few courses to show off jQuery functionality.

#### HackerSchool, Batch[0] Summer 2011
I was part of the first batch of HackerSchool students. I dove into the depths of Ruby and created quite a few small projects and experiments, mainly around tracking programmer productivity. I also experimented with Clojure and played with a forked Lisp interpreter to experiment adding functionality to a standard library.

## EDUCATION

Rutgers University, School of Arts and Sciences
_BS Computer Science_
