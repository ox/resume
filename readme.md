# Artem Titoulenko

email: <artem.titoulenko@gmail.com>  
github: [github.com/ox](http://github.com/ox)  
twitter: [@ox](http://twitter.com/ox)  

## EXPERIENCE

#### SVRF (July 2016)

+ Lead System Architect, led effort to create Kubernetes-backed production environment along with basic monitoring and logging infrastructure. Our cluster of nodes run: web servers for admin tools and user-facing content viewing services, cron jobs, api servers, a scraper cluster, media storage and resizing workers, image recognition workers, as well as a robust and secure Elasticsearch cluster.
+ Wrote the majority of the aforementioned backend services. Many of the service workers needed to be able to handle high computational loads and thus were designed as parallelizable workers using Google Cloud Pub/Sub to handle message passing.
+ Wrote tools and scripts to make local testing similar to production environments using docker-compose, and configured a CI service to ensure tests/linting are being run for every pull request and deploy. Other tools aimed to simplify deploying new container images to production.
+ Refactored the testing suite to reduce test duration by 80% while increasing coverage. Additionally wrote tools to make testing as easy as possible, with more readable results.
+ Refactored much of the codebase to focus on concise, functional, readable, testable code. I aimed to uphold those standards using tools like eslint and thorough code reviews.
+ Wrote and updated documentation for every system I touched, as well as creating on-boarding documents for new engineers. I also created docker-compose-based tools to reduce the time it takes to set up a new engineering environment and increase time to first contribution significantly.

#### Spring (November 2013 - May 2016)

+ Software engineer at an early-stage startup, helped build a lot of first iterations of many foundational pieces of software, all in Go.
+ Worked with UI/UX designers on prototyping and building out a vendor-facing product management system, used by all 1000+ vendors. The system allowed vendors to import, sync, upload products from their inventory systems (Magento, Shopify, Demandware, csv imports, etc) or to use Spring's. The system also allowed brands to control the way their brand page looking in the iOS app, schedule product releases, offer discounts, and manage a marketing calendar.
+ Part of small team tasked with rebuilding the [Spring homepage](https://www.shopspring.com), enabling users to shop, track their orders, and explore other brands on the web. I additionally worked on SEO-focused changes to improve Google Shopping ranking. I also built sitemaps for various crawlers, and tools to regularly export PLA to Google Shopping. Our team was extraordinarily successful and was eventually responsible for the majority of revenue across the company.
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

## Interests and Skills

I have a passion for reducing avoidable engineering errors and burdens, notably time wasted just waiting for something to happen, or not being confident in the correctness of a change. I combat these wherever I can by automating testing, measuring errors and sources, and using tools like Kubernetes to manage operations. I believe that better products are built by agile, confident teams.

I am deeply interested in music, namely machine-based composition. Algorithmic composition is an interesting collaboration between the artist and the machine, creating previously unimaginable music.

I am also interested in exploring various programming languages like Haskell and Erlang to study new approaches to solving problems.
