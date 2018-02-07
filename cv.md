# Darren Hurley

* Address:
    * Berlin
    * Germany
* Mobile: 07841 860 947
* Email: hellodarrenhurley@gmail.com

I have nearly thirteen years of professional Web Development experience. I have worked on high-profile, high-traffic websites, constrained by tight or immovable deadlines. I have led development teams, acting in both a mentoring and project-leadership role. I am an affable, self-motivated worker, quick to pick-up new techniques and technologies, who would fit into any modern web-development company.

## Professional Experience

### Senior Developer (Contractor)

* 101 Ways
* Jul 2017 - Jan 2018 (7 months)

* Worked on the rebuild of the Arcadia codebase, which powers seven high-profile e-commerce sites (e.g. Topshop, Topman, Miss Selfridge)
* Site was rebuilt responsively, as a single page, isomorphic app, primarily using React (with Redux, Thunk/Saga and Router), with additional libraries, such as the Ramda
* We achieved thorough unit testing coverage, having moved to Jest from an earlier usage of Mocha, and a high quality of code, using a combination of ESLint and peer reviews
* We used Github to peer-review and approve pull requests before merging to master, which would then automatically deploy to our staging environment, using Jenkins
* As the codebase powers seven separate sites, that meant we effectively had seven different stakeholders to work with, each with their own requirements and needs
* As many developers were junior or mid level, I took a leadership role in the team, by helping them to work through, or suggesting potential ways to approach, problems

### Front End Developer (Contractor)

* Financial Times
* Mar 2015 - Jun 2017 (2 years, 4 months)

* Worked on the redesign/build of the new responsive website (serving ~2 million requests per day), as well an internal tool used by journalists throughout the globe to upload video assets, attach metadata and captions, and deploy to the site in minutes
* Worked closely with all disciplines; QA, Design, Data Scientists, Product Owners and especially Journalists, as they, alongside the readers, were our main stakeholders
* Took ownership of the complete stack, from Node.js (v8) using Express on the server, to modern, Babel-transpiled ES6 and Sass on the client
* Continual deployment, via CircleCI, on merge to master, meant we shipped to production a few hundred times a week. On a good day, the time from merge to commit was as low as 10 minutes (Fastly caching excluded)
* Karma and Mocha unit tests, alongside Browserstack integration tests, meant we were assured we were shipping quality code
* A quick feedback loop, powered by Graphite/Grafana to monitor the servers, Splunk for general logging, Sentry for error capturing, and Speedcurve to montior site performance, coupled with 24/7 support through PagerDuty, meant we were immediately informed if anything untoward happened, and could react to it remotely
* Performance was a key metric, aiming for a 1.5 second 'load start to read' time
* Strong micro-service mentality meant we had several hundred small apps hosted on Heroku, ranging from serving parts of the site, to APIs to power functionality such as search
* We had a strong belief in A/B testing and data as a way of confirming our hypotheses. At any one time we had ~4 tests running, and were able to interrogate the results in real time using Graphite
* Flexibility to use the right tool for the job, be it frameworkes like React and Redux, or infrastructure, such as AWS' S3 (for images and site assets), Elasticsearch (for indexing the news articles), or Lambda (for small, regular jobs such as updating and deploying the sitemap)

### Senior Web Developer

* The Guardian
* Jul 2012 - Feb 2015 (2 years, 8 months)

* Worked on the redesign/build of the new responsive website (serving ~10 million requests per day)
* Site was hosted on AWS, with a Fastly caching layer. This was completely owned by the developers (rather than a separate devops team), meaning we had to get intimate with Cloudformation scripts and VCL templates
* Server-side language was Scala, which was a fun challenge to work in a purely functional laguage. Client-side we adopted a micro-lbrary approach, using many small, easily changeable libraries (e.g. Bonzo, Reqwest, Qwery)
* Continuous deployment, on merge to master, to a staging environment. Here we could do any further manual testing (using Browserstack or real devices), before a one-click deploy to production
* Worked very closely (daily stand ups, regular meetings, showcases) with both journalists and the creative director to realise their vision

### Principal Web Developer

* BBC
* Oct 2005 - Jul 2012 (6 years, 10 months)

* Over nearly seven years, I worked on many different projects, meaning I was exposed to many different codebases, colleagues (and their style of working), processes (agile, waterfall), tools (Jira, Pivotal Tracker) and technologies. As such, I'm left with the skills to easily integrate into a team and adapt to a situation, as well as voicing my opinions and ideas
* Started as a Junior Web Developer, and through the years worked up to Principal Web Developer
* Worked on many high-profile, high traffic site, such as Lab UK and BBC Food
* My final project was Tech Lead on the London 2012 Olympics site, which involved leading seven developers, making architectural and ongoing design decisions, and working closely with the Product Owner and Business Analysts. It was also one of the first sites to make a strong use of the BBC's (semantic) linked data, powered by a triplestore
* Accessibilty, through working to standards and wide browser support, was an integral part of the BBC culture. Making sure sites were usable in a whole range of browsers (IE6!), as well as accessible to all users, means I still carry around that mentality to this day, regardless of the size or type of site I'm working on
* Primary server side language was PHP (following some early years of SSI and XSLT). We also took ownership of the HTML, CSS (Less) and JS (jQuery) on the client, and testing via PHPUnit and Jasmine
* On various projects I used both Cruise Control and Hudson for our CI, and Subversion and Git for source control

## Education

### MSci Mathematics

* Royal Holloway, University of London
* Jun 2000 - 2004
* Classification: 2.1

* I studied for an MSci in Mathematics at undergraduate level for four years, culminating in a 2.1
* Modules varied from Computational Mathematics, to Cypher Systems, to Public-Key Cryptography
* Apart from the tangible skills learnt, such as algorithm complexity, RSA cryptosystems and working with programming languages, C++ in particular, I also obtained a greater understanding and practical experience of problem solving and analytical thinking

## Links

 * [Github](https://github.com/ironsidevsquincy)
 * [JSDoc Toolkit Ant Task](http://code.google.com/p/jsdoc-toolkit-ant-task/)
