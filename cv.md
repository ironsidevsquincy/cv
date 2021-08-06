# Darren Hurley

* **Address**: Berlin, Germany
* **Mobile**: +49 176 67169899
* **Email**: hellodarrenhurley@fastmail.com

I have nearly fifteen years of professional Web Development experience. I have worked on high-profile, high-traffic websites, constrained by tight or immovable deadlines. I have led development teams, acting in both a mentoring and project-leadership role. I am an affable, self-motivated worker, quick to pick-up new techniques and technologies, who would fit into any modern company.

## Professional Experience

### Engineering Manager at Klarna (Berlin)
Mar 2018 - Present

* I am currently the EM for a platform team, whose chief role is to not only manage up to 5 engineers, but also design and maintain the development and production architecture for 15 teams
* We maintain a Jenkins pipeline, montioring and tweaking agents and configuration files with performance in mind
* We extensively use Docker, e.g. for our services, Jenkins agents. I am versed in writing Docker (and compose) files
* Keycloak is our user authentication system. We have extended it exstensively, which involves writing plugins in Java that integrate with its API
* As most of our infrastructure needs are supplied by AWS, I am regularly deep in a CloudFormation script, maintaining our databases, CloudFront caching, security groups, load balancers and EC2 instances
* We also maintain the frontend architecture of a (primarlity React-based) mono-repo; I'm heavily involved in making design decisions on how we develop, build and run the site

### Senior Developer at 101 Ways (London)
Jul 2017 - Jan 2018 (7 months)

* Worked on the rebuild of the Arcadia codebase, which powers seven high-profile e-commerce sites (e.g. Topshop, Topman, Miss Selfridge)
* Site was rebuilt responsively, as a single page, isomorphic app, primarily using React (with Redux, Thunk/Saga and Router), with additional libraries, such as Ramda
* We achieved thorough unit testing coverage, having moved to Jest from an earlier usage of Mocha, and a high quality of code, using a combination of ESLint and peer reviews
* We used Github to peer-review and approve pull requests before merging to master, which would then automatically deploy to our staging environment, using Jenkins
* As many developers were junior or mid level, I took a leadership role in the team, by helping them to work through, or suggesting potential ways to approach, problems

### Front End Developer at The Financial Times (London)
Mar 2015 - Jun 2017 (2 years, 4 months)

* Worked on the redesign/build of the new responsive website (serving ~2 million requests per day), as well an internal tool used by journalists throughout the globe to upload video assets, attach metadata and captions, and deploy to the site in minutes
* Worked closely with all disciplines; QA, Design, Data Scientists, Product Owners and especially Journalists, as they, alongside the readers, were our main stakeholders
* Took ownership of the complete stack, from Node.js (v8) using Express on the server, to modern, Babel-transpiled ES6 and Sass on the client
* Continual deployment, via CircleCI, on merge to master, meant we shipped to production a few hundred times a week. On a good day, the time from merge to commit was as low as 10 minutes (Fastly caching excluded)
* A quick feedback loop, powered by Graphite/Grafana to monitor the servers, Splunk for general logging, Sentry for error capturing, and Speedcurve to montior site performance, coupled with 24/7 support through PagerDuty, meant we were immediately informed if anything untoward happened, and could react to it remotely
* Performance was a key metric, aiming for a 1.5 second 'load start to read' time
* Strong micro-service mentality meant we had several hundred small apps hosted on Heroku, ranging from serving parts of the site, to APIs to power functionality
* We had a strong belief in A/B testing and data as a way of confirming our hypotheses. At any one time we had ~4 tests running, and were able to interrogate the results in real time using Graphite
* Flexibility to use the right tool for the job, be it frameworkes like React and Redux, or infrastructure, such as AWS' S3 (for images and site assets), Elasticsearch (for indexing the news articles), or Lambda (for small, regular jobs such as updating and deploying the sitemap)

### Senior Web Developer The Guardian (London)
Jul 2012 - Feb 2015 (2 years, 8 months)

* Worked on the redesign/build of the new responsive website (serving ~10 million requests per day)
* Site was hosted on AWS, with a Fastly caching layer. This was completely owned by the developers (rather than a separate devops team), meaning we had to get intimate with Cloudformation scripts and VCL templates
* Server-side language was Scala, which was a fun challenge to work in a purely functional laguage. Client-side we adopted a micro-lbrary approach, using many small, easily changeable libraries (e.g. Bonzo, Reqwest, Qwery)
* Continuous deployment, on merge to master, to a staging environment, before a one-click deploy to production
* Worked very closely (daily stand ups, regular meetings, showcases) with both journalists and the creative director to realise their vision

### Principal Web Developer at The BBC (London)
Oct 2005 - Jul 2012 (6 years, 10 months)

* Over nearly seven years, I worked on many different projects, starting as a Junior Web Developer, and through the years working up to Principal Web Developer. This meant I was exposed to many different codebases, colleagues (and their style of working), processes (agile, waterfall), tools (Jira, Pivotal Tracker) and technologies. As such, I'm left with the skills to easily integrate into a team and adapt to a situation, as well as voicing my opinions and ideas
* My final project was Tech Lead on the London 2012 Olympics site, which involved leading seven developers, making architectural and ongoing design decisions, and working closely with the Product Owner and Business Analysts. It was also one of the first sites to make a strong use of the BBC's (semantic) linked data, powered by a triplestore
* Accessibilty, through working to standards and wide browser support, was an integral part of the BBC culture. Making sure sites were usable in a whole range of browsers (IE6!), as well as accessible to all users, means I still carry around that mentality to this day, regardless of the size or type of site I'm working on
* Primary server side language was PHP (following some early years of SSI and XSLT). We also took ownership of the HTML, CSS (Less) and JS (jQuery) on the client, and testing via PHPUnit and Jasmine

## Education

### Royal Holloway, University of London
MSci Mathematics (2.1), Jun 2000 - 2004
