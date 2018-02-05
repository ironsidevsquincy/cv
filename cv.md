# Darren Hurley

* Address:
    * Albert Road
    * London
    * E10
* Mobile: 07841 860 XXX
* Email: hellodarrenhurley@gmail.com

I have nearly twelve years of professional Web Development experience, and many more on an amateur level. I have worked on high-profile, high-traffic websites, working within tight or immovable deadlines. I have led development teams, acting in both a mentoring and project-leadership role. I am an affable, self-motivated worker, quick to pick-up new techniques and technologies, who would fit into any modern web-development company.

## Education

### MSci Mathematics

* Royal Holloway, University of London
* Jun 2000 - 04
* Classification: 2.1

I studied for an MSci in Mathematics at undergraduate level for four years, culminating in a 2.1. Modules varied from Computational Mathematics, to Cypher Systems, to Public-Key Cryptography. Apart from the tangible skills learnt, such as algorithm complexity, RSA cryptosystems and working with programming languages, C++ in particular, I also obtained a greater understanding and practical experience of problem solving and analytical thinking.

## Professional Experience

### Principal Web Developer

* BBC
* Oct 2005 - Jul 2012

Since starting at the BBC in 2005 as a Junior Web Developer, I have worked my way up through Web Developer and Senior Web Developer, to my current position as Principal Web Developer. I have worked on three of the larger BBC sites, both in terms of user-traffic and scope; BBC Food, LabUK and the London 2012 Olympics.

I split my time between working with PHP primarily on the server-side and HTML, CSS and JS on the client. We use jQuery JS library for abstracting and ironing out browser eccentricities, Jasmine testing framework for our JS BDD and LESS CSS pre-processor for organising and managing large stylesheet codebases. I am a strong advocate for TDD, using PHPUnit to implement it on my PHP code, and continuous integration, having used both Cruise Control and Hudson to manage our CI. We integrated version control with our CI, and as such I am extremely comfortable working with SVN in large teams, spread over a wide, geographical area. I have also used Git for my own personal projects.

My current position of Tech Lead on London 2012 involves leading a development team of seven web developers, making architectural and ongoing design decisions, and working closely with the Product Owner and Business Analysts to advise on technical solutions for their ambitions and ways to implement them. The Olympics site is built around linked data, powered by a triplestore. We consume the data as RDF, over a HTTP API, using a third-party PHP RDF library.

The BBC has very strong standards and browser support guidelines. As such, I am used to creating code that not only conforms to the W3C standards, but is also supported in a variety of browser (right back to IE6). Accessibility and usability are paramount on such high profile projects, and as such I have an understanding through experience and from course attendance of creating sites accessible to users with disabilities.

I am used to working on multi-disciplinary projects. BBC Food in particular involved working closely with Designers and Software Engineers, creating a small feedback loop, where ideas were discussed, implemented and iterated regularly. All three major projects also used adopted an agile development philosophy, with daily scrums, generally fortnightly releases and sprint planning and the use of ticketing software (Jira, Pivotal Tracker) to manage features and bugs.

### Senior Web Developer

* The Guardian
* Jul 2012 - Feb 2015

I joined the team at the beginning of the build of the new site for The Guardian. This was an exciting time as the business was concentrating on their digital proposition, so we were given the freedom to try innovative things, with the proviso we could provide value for money. This involved hosting the site externally on AWS, which meant working with Cloudformation scripts, and using Scala as the main language for the site, which was an interesting challenge. To handle the traffic demands of the site, we opted for Fastly as our CDN, which involved getting intimate with VCL. As developers we organised our code and collaborated via Git; PRs would be peer-reviewd, but the power was very much in our hands, with a merge to master deploying continuously to production

I worked not only closely with the designers on creating the site itself, but also the editors to realise their ambitions for it, which was a new way of working not just for editorial, but also for tech, as in the past there had very much been a divide between the disciplines

### Front End Developer (Contractor)

* Financial Times
* Mar 2015 - June 2017

Again, I joined the team a few months into the redesign/build of the new responsive FT website. Not only was this a new site for the company, it was also a completely new way of working within the FT; the team worked closely with other departments (design, QA), in and agile, data-driven way, and had complete autonomy and ownership of the full stack. We, as a team, were afforded a freedom that was rare from a company of that size and structure, which has fortunately latest to this day. We had the ability to choose the right technology for the problem, leading to us use not only Heroku for our standard deployment, but also a variety of AWS services (Elasticsearch to serve the content for our site, S3 for general site assets, Lambda for small and quick regular jobs) for more scalable solutions. This led to use launching the site in Dec 2016, which was by all accounts a smooth process (a rather anticlimactic flick of the switch, our hard-work making the site robust meant there were no surprises) and now serving ~2m requests a day

As developers we owned the code all the way through the development process, from building the backend in Node.js, testing using a combination of Karma, Mocha and Browserstack, deploying to Heroku continuously with CircleCI, to monitoring with Graphite, Splunk and Sentry.

* Node.js - The majority of the site was built in Node, using an Express as our core framework. As we have complete ownership, it's been easy to stay up-to-date with the latest releases, e.g. we're starting to roll v8 out to our apps.
* React/Redux/Router - An editorial CMS to create video content I led heavily used these technologies. I was stunned by how quick and easy it was to build, and adapt to feedback from the journalists
* ES6 - As we used Babel to transpile our client code down, we had the ability to try out the latest developments in JS; whether that was the new sytax (e.g. arrow functions, destructuring), or new functionality (e.g. ES6 modules, async/await)
* Heroku - We had a strong micro-service philosophy, which involved breaking the site in to many hundreds of small Heroku hosted apps
* CircleCI - We practiced continuous integration, i.e. each build provisioned its own Heroku app, where we would run a series of integration tests. If it was a master build we would then push straight to production. The time from commit to reflect that change on the site (excluding caching) would take around 10 minutes.
* AWS - The site is powered by data from Elasticsearch, which often involves getting dirty with its query engine. We use S3 as a general store for assets, e.g. our video renditions, image assets on the site. Recently we've been given Lambda a test run on small jobs that seemed to light for a full-blown Heroku app, e.g. we build the sitemap using a Lambda job triggered every minute

## Links

 * [Github](https://github.com/ironsidevsquincy)
 * [JSDoc Toolkit Ant Task](http://code.google.com/p/jsdoc-toolkit-ant-task/)
