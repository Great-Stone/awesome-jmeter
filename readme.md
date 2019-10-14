# Awesome JMeter 
[![Awesome](https://awesome.re/badge.svg)](https://awesome.re) [![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat)](https://github.com/aliesbelik/awesome-jmeter/blob/master/contributing.md)

[<img src="jmeter-logo.svg" align="right" width="260">](http://jmeter.apache.org/)

> A curated collection of resources covering [Apache JMeter](http://jmeter.apache.org/) and related resources and shiny things: plugins, integrations, testing techniques, devops practicies, etc.

The [Apache JMeter](http://jmeter.apache.org/) is open source, pure Java application designed to load test functional behavior and measure performance.

This list grew up from [this answer on Stack Exchange](https://sqa.stackexchange.com/a/2552/1842) and personal JMeter-related links collection, got further inspiration from [awesome](https://github.com/sindresorhus/awesome) project and improved by these [amazing contributors](https://github.com/aliesbelik/awesome-jmeter/graphs/contributors).

## Contents

- [Getting Started](#getting-started)
- [Tutorials](#tutorials)
- [Best Practices](#best-practices)
- [Scripting](#scripting)
- [DSL](#dsl)
- [Distributions](#distributions)
- [Plugins](#plugins)
- [CI](#ci)
- [Distributed Testing](#distributed-testing)
- [Cloud Services / SaaS](#cloud-services--saas)
- [Monitoring](#monitoring)
- [Results Analysis](#results-analysis)
- [Results Visualisation](#results-visualisation)
- [JMeter Performance](#jmeter-performance)
- [Tips & Tricks](#tips--tricks)
- [IDE Integration](#ide-integration)
- [Performance Testing](#performance-testing)
    - [Streaming Protocols](#streaming-protocols)
    - [Mobile Apps](#mobile-apps)
- [Books](#books)
- [Trainings & Courses](#trainings--courses)
- [Community](#community)
    - [Blogs](#blogs)
    - [Forums](#forums)
    - [Newsletters](#newsletters)
    - [Twitter](#twitter)
    - [Q&A](#qa)
- [Contributing](#contributing)
- [License](#license)


## Getting Started

- [Getting Started with Apache JMeter @ DZone](https://dzone.com/refcardz/getting-started-with-apache-jmeter)
- [A Simple Load Test with JMeter @ Urban Insight](https://www.urbaninsight.com/2011/07/18/simple-load-test-with-jmeter)
- [Performance testing with JMeter @ Atlassian](https://www.atlassian.com/blog/archives/performance_testing_with_jmete)

## Tutorials

- [JMeter Tutorials @ ArtOfTesting.com](https://artoftesting.com/jmeter-tutorial.html)
- [Load Testing your Applications with Apache JMeter by Keld H. Hansen @ jGuru.com](http://www.jguru.com/article/server-side/load-testing-with-apache-jmeter.html)
- Load Testing with JMeter:
    - [part 1](https://lincolnloop.com/blog/2011/sep/21/load-testing-jmeter-part-1-getting-started/) - Getting started.
    - [part 2](https://lincolnloop.com/blog/2011/oct/12/load-testing-jmeter-part-2-headless-testing-and-je/) - Headless testing and Jenkins integration.
    - [part 3](https://lincolnloop.com/blog/2012/sep/19/load-testing-jmeter-part-3-replaying-apache-logs/) - Replaying Apache logs.
- [Concurrent, High Throughput Performance Testing with JMeter](https://planet.jboss.org/post/concurrent_high_throughput_performance_testing_with_jmeter)
- [Functional Testing with JMeter](https://hub.packtpub.com/functional-testing-jmeter/)
- [JMeter Resources @ InfoSec Institute](https://resources.infosecinstitute.com/search/?s=jmeter)
- [JMeter Tutorial @ tutorialspoint.com ](https://www.tutorialspoint.com/jmeter/)
- [JMeter Tutorial for Load Testing: The ULTIMATE Guide](https://www.javacodegeeks.com/2014/11/jmeter-tutorial-load-testing.html)
- [RESTful API testing with JMeter](https://www.ibm.com/developerworks/cloud/library/cl-jmeter-restful/)
- [How to Hit Your RESTful Web Service Using JMeter](https://crunchify.com/how-to-hit-your-restful-web-service-using-jmeter-perform-a-simple-load-test/)
- [JMeter: Load Development LifeCycle](https://gerardnico.com/jmeter/lifecycle)
- [Load Testing with Apache JMeter @ DigitalOcean](https://www.digitalocean.com/community/tutorial_series/load-testing-with-apache-jmeter)
- [JMeter Tutorial @ Guru99](https://www.guru99.com/jmeter-tutorials.html)
- [JMeter Series @ Sourcepole](http://blog.sourcepole.com/2011/01/04/jmeter-series/)

## Best Practices

- [JMeter Official Best Practices](http://jmeter.apache.org/usermanual/best-practices.html)
- [JMeter Best Practices @ BlazeMeter](https://guide.blazemeter.com/hc/en-us/articles/207421405-JMeter-Best-Practices)

## Scripting

- [Beanshell vs JSR223 vs Java JMeter Scripting](https://www.blazemeter.com/blog/beanshell-vs-jsr223-vs-java-jmeter-scripting-its-performance/) - Most popular scripting mechanisms performance comparison.
- [Testing with Groovy](https://static.packt-cdn.com/downloads/Testingwithgroovy.pdf) - Using JMeter and Groovy for load testing.
- [JMeter: forget about BeanShell Sampler](https://habr.com/ru/post/250731/) *(Russian)*

## DSL

- [RubyJmeter](https://github.com/flood-io/ruby-jmeter) - A Ruby based DSL for building JMeter test plans.

## Distributions

- [Download Apache JMeter](http://jmeter.apache.org/download_jmeter.cgi) - Apache JMeter: Official downloads.
- [JMeter for Windows](https://sourceforge.net/projects/jmeterforwindows/) - Package for installation JMeter with plugins.

## Plugins

- [JMeter Plugins list](https://docs.google.com/spreadsheets/d/1FYMw3zCMr2Y37QCG_vOyC3HyrLxxi7x5I3khWLj3isU/) - List of available plugins and extensions.
- [JMeter Plugins](https://jmeter-plugins.org/) - Independent set of plugins for Apache JMeter.
- [UBIK Load Pack](https://ubikloadpack.com/) - Productivity extensions for Apache JMeter.
- [AtlantBH Custom JMeter Components](https://github.com/ATLANTBH/jmeter-components/) - Set of JMeter extensions developed by Atlantbh (currently included into [JMeter Plugins](https://jmeter-plugins.org/) project).

## CI

- Tools & Plugins
    - [JMeter Ant Task](http://www.programmerplanet.org/projects/jmeter-ant-task/) - Ant task to automate running JMeter test plans.
    - [JMeter Maven Plugin](https://github.com/jmeter-maven-plugin/jmeter-maven-plugin) - Maven plugin that provides the ability to run JMeter tests as part of the build.
    - [Jenkins Performance Plugin](https://wiki.jenkins-ci.org/display/JENKINS/Performance+Plugin) - Jenkins plugin to capture reports from JMeter and generate graphic charts with the trend report of performance and robustness.
    - [TeamCity Performance Tests Analysis Plugin](https://github.com/jtorgan/jmeter_plugin)
    - Bamboo JMeter Aggregator Plugin: [documentation](https://marketplace.atlassian.com/plugins/jmeterAggregator/server/overview), [sources](https://bitbucket.org/atlassian/bamboo-jmeter-plugin) - Bamboo plugin to collect, assert and graph JMeter test results.
    - [Sonar JMeter Plugin](https://github.com/SonarCommunity/sonar-jmeter) - Plugin to collect JMeter performance tests results and display in Sonar dashboard.
    - [Lightning](http://automatictester.github.io/lightning/) - Framework to integrate JMeter non-functional tests with CI/CD server.
- Tutorials & Demo
    - Jenkins
        - [Automated performance testing using JMeter and Maven](https://www.atlassian.com/blog/archives/automated_performance_testing_using_jmeter_and_maven)
        - [Performance Tests with JMeter, Maven and Hudson](http://www.theserverlabs.com/blog/?p=280)
        - [CI with Jenkins, Git, Maven, Grunt, and JMeter](https://github.com/dzuluagaapigee/apigee-ci-jenkins-git-maven-jmeter)
        - [Continuous automated web tests using Jenkins and JMeter](https://www.linkedin.com/pulse/continuous-automated-web-tests-using-jenkins-jmeter-mahanta)
        - [Automating JMeter tests with Maven and Jenkins](https://blog.codecentric.de/en/2014/01/automating-jmeter-tests-maven-jenkins/)
        - How to automate JMeter tests with Maven and Jenkins: [part 1](https://ribblescode.wordpress.com/2012/04/16/how-to-run-jmeter-tests-with-maven/), [part 2](https://ribblescode.wordpress.com/2012/04/16/how-to-automate-jmeter-tests-with-maven-and-jenkins-hudson-8/)
        - JMeter Continuous Performance Testing (JMeter + Ant + Jenkins): [part 1](http://www.testautomationguru.com/jmeter-continuous-performance-testing-part1/), [part 2](http://www.testautomationguru.com/jmeter-continuous-performance-testing-part2/)
        - [Continuous Integration 101: How to Run JMeter with Jenkins](https://www.blazemeter.com/blog/continuous-integration-101-how-run-jmeter-jenkins)
    - Bamboo
        - [How to Run JMeter in a Continuous Integration Environment with Bamboo](https://www.blazemeter.com/blog/how-run-jmeter-continuous-integration-environment-bamboo)
    - SonarQube
        - [JMeter with Sonar](http://testersinaction.blogspot.com.by/2013/05/v-behaviorurldefaultvmlo_24.html)

## Distributed Testing

- [JMeter Distributed Testing Step-by-step](http://jmeter.apache.org/usermanual/jmeter_distributed_testing_step_by_step.pdf)
- [JMeter Remote Testing](http://jmeter.apache.org/usermanual/remote-test.html)
- Dockerized
    - [Dockerized JMeter](https://gist.github.com/hhcordero/abd1dcaf6654cfe51d0b) - Distributed load testing workflow with Docker and JMeter.
    - [JMeter Docker Images](https://hub.docker.com/search/?isAutomated=0&isOfficial=0&page=1&pullCount=0&q=jmeter&starCount=0)
    - [Distributed JMeter testing using Docker](http://srivaths.blogspot.com/2014/08/distrubuted-jmeter-testing-using-docker.html)
- Testing in Cloud
    - Amazon
        - [jmeter-ec2](http://web.archive.org/web/20120209090437/http://www.http503.com/2012/jmeter-ec2/) - Run JMeter on Amazon’s EC2 Cloud.
        - [Load Testing with JMeter and Amazon EC2](https://medium.com/@alttaf_untangl/load-testing-with-jmeter-and-amazon-ec2-e143a7350596)
        - [Performance Testing in the Cloud with JMeter & AWS](http://www.artofsoftwaredevelopment.com/performance/performance-testing-in-the-cloud-with-jmeter-aws)
        - [JMeter distributed testing with Amazon EC2](https://vedovini.net/2009/08/jmeter-distributed-testing-with-amazon-ec2/)
    - DigitalOcean
        - [Lightweight JMeter Cloud](https://docs.google.com/presentation/d/1Yi5C27C3Q0AnT-uw9SRnMeEqXSKLQ8h9O9Jqo1gQiyI/) - Building your own JMeter Cloud using Digital Ocean, JMeter and Docker.

## Cloud Services / SaaS

*List of cloud-based load testing services with support of JMeter test plans execution.*

- [CA BlazeMeter](http://blazemeter.com/) - Performance engineering platform with JMeter and Selenium support.
- [OctoPerf](https://octoperf.com/) - Saas and On-Premise Load Testing Tool with JMeter and Selenium support.
- [Tricentis Flood](http://flood.io/) - Load testing service with JMeter, Gatling and Selenium scenarios support.
- [RedLine13](http://redline13.com/) - AWS-based load testing service with JMeter, Gatling and Selenium scenarios support.
- [HP StormRunner Load](https://saas.hpe.com/en-us/software/stormrunner-load) - HP cloud-based solution for web and mobile performance testing with JMeter and Gatling support.
- [Loadster](http://www.loadsterperformance.com/) - Solution for distributes load testing of web applications and services.
- [Loadium](https://www.loadium.com/) - AWS-based load testing service with JMeter and Selenium support.

## Monitoring

- [CA App Synthetic Monitor](https://cloudmonitor.ca.com/en/feature/transaction-monitoring-web-application-testing.html) - Transaction monitoring & testing solution with JMeter support.
- [Dynatrace JMeter Integration](https://community.dynatrace.com/community/display/DOCDT65/Integrate+Web+API+Performance+Monitoring+in+JMeter) - Saas Monitoring solution with JMeter support.
- [AppDynamics JMeter Integration](https://community.appdynamics.com/appdynamics/attachments/appdynamics/appdynamics-discussions/8314/1/JMeter%20integration%20with%20AppDynamics.pdf) - Saas Monitoring solution with JMeter integration.

## Results Analysis

- [JMeter Report Dashboard](http://jmeter.apache.org/usermanual/generating-dashboard.html)
- [JMeter Log Analysis](http://wiki.apache.org/jmeter/LogAnalysis) - Suggestions and recipes for JMeter log analysis.
- [Analyzing JMeter Results](http://www.datazoo.de/articles/158/performance-testing-analyzing-jmeter-results)
- [JMeter Result Analysis: The Ultimate Guide](https://octoperf.com/blog/2017/10/19/how-to-analyze-jmeter-results/)
- [BlazeMeter Sense](https://sense.blazemeter.com/) - Service for storing and analysing performance test results.
- [JAnalyser](http://epireum.com/page-section/janalyser/) - Browser-based results analysis tool.
- [JMeter Result Analysis Plugin](https://github.com/afranken/jmeter-analysis-maven-plugin) - Maven plugin that parses JMeter test results and generates detailed reports with charts.
- [JMeter Results Analyser](http://sourceforge.net/projects/jmstats/) - Web-based application for collating, analysing and reporting JMeter test results.
- DB Result Collectors
    - [JMeter DBCollector Plugin](http://sourceforge.net/projects/jmeterdbcollect/) - Plugin to enable results logging into a database for more effective reporting.
    - [JMeter MySQLCollector Plugin](http://wiki.apache.org/jmeter/MysqlCollectorPlugin) - Patch to configure listener to log into MySQL database.

## Results Visualisation

- [JMeter Report Dashboard](http://jmeter.apache.org/usermanual/generating-dashboard.html) - JMeter supports dashboard report generation to get graphs and statistics from a test plan.
- [Using InfluxDB & Grafana](http://www.testautomationguru.com/jmeter-real-time-results-influxdb-grafana/) - Real-time results with InfluxDB & Grafana.
    - [JMeter Load Test Dashboard](https://grafana.com/dashboards/1152)
- [Using ELK](http://ecmarchitect.com/archives/2014/09/09/3932) - Using Elasticsearch, Logstash, and Kibana to visualize JMeter test results.
- [Using Matplotlib & Python](http://www.metaltoad.com/blog/plotting-your-load-test-jmeter) - Plotting JMeter load test results with Matplotlib plotting tool and Python.
- [Statistical Aggregate Report](http://rubenlaguna.com/wp/better-jmeter-graphs/) - Custom Statistical Aggregate Report listener for enhanced results visualization.
- [JChav](https://github.com/d6y/jchav) - JMeter Chart History and Visualisation library.
- [Using CMDRunner & Powershell](http://performancewebautoamtionother.blogspot.com.by/2015/12/jmeter-create-graphs-with-cmdrunner.html) - Create JMeter graphs with CMDRunner with powershell parallel execution.
- JMeter Dashboard: [howto](http://seangkuan.blogspot.com.by/2015/06/jmeter-dashboard-realtime-monitoring-of.html), [sources](https://github.com/vincentskooi/JMeterDashboard) - Realtime monitoring of JMeter load test.
- [JMeter + ElasticSearch Live Monitoring](https://medium.com/@anthony.gauthier325/jmeter-elasticsearch-live-monitoring-c895c843c51e), [sources](https://github.com/delirius325/jmeter-elasticsearch-backend-listener) - Using the ElasticSearch Backend listener and Grafana/Kibana to monitor results in realtime.

## JMeter Performance

- [JMeter Performance](http://wiki.apache.org/jmeter/JMeterPerformance) - JMeter performance evolution across versions.
- [JMeter Performance and Tuning Tips @ UBIK Ingenierie](http://www.ubik-ingenierie.com/blog/jmeter_performance_tuning_tips/)
- [JMeter Performance and Tuning Tips @ BlazeMeter](https://blazemeter.com/blog/jmeter-performance-and-tuning-tips)
- [Beanshell vs JSR223 vs Java JMeter Scripting](http://blazemeter.com/blog/beanshell-vs-jsr223-vs-java-jmeter-scripting-its-performance) - Most popular scripting mechanisms performance comparison.

## Tips & Tricks

- [JMeter tips @ WebWob](http://www.webwob.com/html/jmeter_tips.html) - JMeter tips and tricks scratchpad.

## IDE Integration

- [Intellij IDEA IDE Plugin](https://plugins.jetbrains.com/plugin/7013-jmeter-plugin) - Create run configurations and run JMeter tests from Intellij IDEA.
- [JMeter + Eclipse HOWTO](https://cwiki.apache.org/confluence/display/jmeter/JMeterAndEclipseHowTo) - Develop the JMeter project with Eclipse IDE.
- [NetBeans JMeter Kit](http://plugins.netbeans.org/plugin/49923/jmeter) - JMeter integration module for NetBeans IDE.
- [Using a Load Generator in NetBeans IDE](https://netbeans.org/kb/docs/java/profile-loadgenerator.html)

## Performance Testing

### Streaming Protocols

- [Easy and realistic Load Testing of HTTP Live Streaming (HLS) with Apache JMeter](http://www.ubik-ingenierie.com/blog/easy-and-realistic-load-testing-of-http-live-streaming-hls-with-apache-jmeter/)
- [Using JMeter to Load Test Live HLS Concurrency of Wowza Streaming Engine](http://www.realeyes.com/blog/2015/08/26/using-jmeter-to-load-test-live-hls-concurrency-of-wowza-streaming-engine/)
- [How to Load Test HTTP Live Media Streaming (HLS) with JMeter](https://www.blazemeter.com/blog/how-load-test-http-live-media-streaming-hls-jmeter)
- [Load testing HLS with Ruby JMeter](https://smoothscaling.com/load-testing-hls-with-ruby-jmeter-85b9b1e6db72)

### Mobile Apps

- [Record iOS application HTTP requests](http://www.testautomationguru.com/jmeter-record-ios-application-http-requests/)
- [BlazeMeter Mobile Recorder](https://guide.blazemeter.com/hc/en-us/articles/207420545-BlazeMeter-Recorder-Mobile-Recorder-)
- [Performance Testing for Native Mobile Apps @ Blazemeter](https://www.blazemeter.com/blog/view-webcast-performance-testing-native-mobile-apps)

## Extending JMeter

- [JMeter Developer Manual](http://wiki.apache.org/jmeter/DeveloperManual)
- [How to write a plugin for JMeter](https://jmeter.apache.org/extending/jmeter_tutorial.pdf)
- [How to build a JMeter plugin utilising groovy](http://artur.ejsmont.org/blog/content/how-to-build-a-jmeter-plugin-utilising-groovy)
- [How to create a plugin in JMeter](http://stackoverflow.com/questions/20422640/how-to-create-a-plugin-in-jmeter)
- [Custom JMeter Samplers and Config Elements](http://codyaray.com/2014/07/custom-jmeter-samplers-and-config-elements)

## Books

- [Apache JMeter: A Practical Beginner's Guide to Automated Testing and Performance Measurement for Your Websites](http://books.google.com/books?id=nX8oKIEvUcYC) by Emily H. Halili ([Packt Publishing](https://www.packtpub.com/networking-and-servers/apache-jmeter)) - A practical beginner's guide to automated testing and performance measurement for your websites.
- [Performance Testing with JMeter 2.9](http://books.google.com/books?id=fpWmv3wPT64C) by Bayo Erinle ([Packt Publishing](https://www.packtpub.com/application-development/performance-testing-jmeter-29)) - Guide to test web applications using Apache JMeter with practical, hands-on examples.
- [Performance Testing with JMeter, 2nd Edition](https://books.google.com/books?id=6ditCAAAQBAJ) by Bayo Erinle ([Packt Publishing](https://www.packtpub.com/application-development/performance-testing-jmeter-second-edition))
- [Performance Testing with JMeter 3, 3rd Edition](https://books.google.com/books?id=BedDDwAAQBAJ) by Bayo Erinle ([Packt Publishing](https://www.packtpub.com/web-development/performance-testing-jmeter-3-third-edition))
- [JMeter Cookbook](https://books.google.com/books?id=gJUeBQAAQBAJ) by Bayo Erinle ([Packt Publishing](https://www.packtpub.com/application-development/jmeter-cookbook)) - 70 insightful and practical recipes to help successfully use Apache JMeter.
- [JMeter by Example](https://books.google.com/books?id=iWeJDAEACAAJ) by Sai Matam and Jagdeep Jain ([Leanpub](https://leanpub.com/jmeterbyexample)) - A simple, practical, step-by-step tutorial to measure the performance of websites.
- [Pro Apache JMeter: Web Application Performance Testing](https://books.google.com/books?id=YJ4xDwAAQBAJ) by Sai Matam and Jagdeep Jain ([Apress](https://www.apress.com/gp/book/9781484229606))
- [Master Apache JMeter: From load testing to DevOps](https://books.google.com/books?id=D_amDwAAQBAJ) by Antonio Gomes Rodrigues, Bruno Demion (Milamber) and Philippe Mouawad ([Leanpub](https://leanpub.com/master-jmeter-from-load-test-to-devops), [Packt Publishing](https://books.google.com/books?id=D_amDwAAQBAJ
https://www.packtpub.com/programming/master-apache-jmeter-from-load-testing-to-devops))
- [Maîtriser JMeter: Du Test de charge à Devops](http://samples.leanpub.com/maitriser-jmeter-du-test-de-charge-a-devops-sample.pdf) by Antonio Gomes Rodrigues, Bruno Demion (Milamber) and Philippe Mouawad ([Leanpub](https://leanpub.com/maitriser-jmeter-du-test-de-charge-a-devops)) *(French)*

## Trainings & Courses

- [JMeter: Performance and Load Testing](https://www.linkedin.com/learning/jmeter-performance-and-load-testing) @ LinkedIn Learning
- [JMeter Training Courses](https://www.nobleprog.co.uk/jmeter-training) @ NobleProg
- [JMeter Training Course](https://info.blazemeter.com/jmeter-training-course) @ BlazeMeter
- [JMeter Training Academy](https://www.blazemeter.com/jmeter-tutorial/) @ BlazeMeter
- [JMeter Courses collection](https://www.udemy.com/courses/search/?q=jmeter) @ Udemy
- [JMeter Training Course](http://www.absofttrainings.com/jmeter-training-course-and-tutorials/) @ ABSoft Trainings
- [Web Applications (and Mobile Apps) Performance Testing with JMeter](http://pragmatictestlabs.com/web-applications-mobile-apps-performance-testing-jmeter/) @ Pragmatic Test Labs
- [Training courses on Load Testing with Apache JMeter](https://www.ubik-ingenierie.com/blog/jmeter-trainings-by-contributors-and-committers/) @ Ubik Ingrnierie
- [Apache JMeter Testing Courses](https://qainsights.com/services/) @ QAInsights

## Community

### Blogs

- [BlazeMeter Blog](https://www.blazemeter.com/jmeter) - BlazeMeter blog about JMeter and performance testing.
- [Ubik Load Pack Blog](http://www.ubik-ingenierie.com/blog/category/jmeter/) - UBIK INGENIERIE blog.
- [TestAutomationGuru Blog](http://www.testautomationguru.com/category/jmeter/) - Technical blog on test automation.
- [JMeter Tips](http://jmeter-tips.blogspot.com/) - Blog about Apache JMeter and performance testing of web applications.
- [RedLine13 Blog](https://www.redline13.com/blog/tag/jmeter/) - JMeter articles in RedLine13 blog.
- [Smooth Scaling (Flood.io) Blog](https://smoothscaling.com/tagged/tutorial) - Load testing thoughts, stories and ideas from Flood IO.
- [JMeter Blog @ Shantonu Sarker](http://shantonusarker.blogspot.com.by/p/jmeter.html) - Another blog for performance & automation testing using JMeter.
- [JMeter Expert Blog](http://jmeter-expert.blogspot.com/) - JMeterExpert blog (not updated).
- [OctoPerf Blog](https://octoperf.com/blog) - OctoPerf blog about JMeter and load testing.
- [Abstracta](https://abstracta.us/blog/tag/jmeter/) - Abstracta blog about JMeter.

### Forums

- [JMeter Nabble Forum](http://www.jmeter-archive.org/)
- [JMeter SQAforums](http://www.sqaforums.com/postlist.php?Cat=0&Board=UBB54)

### Newsletters

- [JMeter @ Linkedin](https://www.linkedin.com/learning/search?keywords=jmeter)
- [JMeter @ Reddit](https://www.reddit.com/r/jmeter/)

### Twitter

- [@ApacheJMeter](https://twitter.com/apachejmeter) - Official Twitter account of the Apache JMeter load testing tool.
- [@jmeter_plugins](https://twitter.com/jmeter_plugins) - Twitter account of custom plugins project for JMeter load testing tool.
- [@BlazeMeter](https://twitter.com/BlazeMeter) - Official Twitter account of Blazemeter, performance engineering platform for DevOps, based on JMeter.
- [@masterjmeter](https://twitter.com/masterjmeter) - Official account of the [Master Apache JMeter from Load Testing to DevOps](#books) book.
- [@ubikloadpack](https://twitter.com/ubikloadpack) - Twitter account of [Ubik Load Pack](#plugins), custom JMeter plugins for Video Streaming & complex protocols load testing.

### Q&A

- [JMeter @ Stack Overflow](http://stackoverflow.com/questions/tagged/jmeter)
- [Skype chat of JMeter enthusiasts](http://is.gd/jmeterchat) *(Russian)*
- JMeter @ gitter: [![Have questions\issues\problems, join the chat at https://gitter.im/aliesbelik/jmeter-chat](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/aliesbelik/jmeter-chat)
- [JMeter Slack workspace](http://jmeterusers.slack.com/)


# Contributing

Contributions are welcome!<br />
Please take a look at the [contribution guidelines](https://github.com/aliesbelik/awesome-jmeter/blob/master/contributing.md) first.

# License

<a rel="license" href="http://creativecommons.org/licenses/by/4.0/"><img alt="Creative Commons License" style="border-width:0" src="https://i.creativecommons.org/l/by/4.0/88x31.png" /></a><br />This work is licensed under a <a rel="license" href="https://github.com/aliesbelik/awesome-jmeter/blob/master/LICENSE.md">CC-BY-4.0</a>.
