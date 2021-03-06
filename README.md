![alt text](/static/horizontal-beeva-logo.png "BEEVA")

#Best Practices in BEEVA

Here is the list of best practices, guidelines, codestyles and recommendations that we follow and encourage in BEEVA, please read the contrib [guidelines](#contrib-guidelines) before sending your pull request with your content.

If you think any information is wrong or missing please write us an email or directly create an issue inside this repo.

### Agile
* [Kanban](agile/Kanban/README.md)
* [User Stories](agile/userStories/README.md)
* [Working Agreements](agile/workingAgreements/README.md)

### Backend
* [Java](backend/java/README.md)
* [Microservices](backend/microservices/README.md)
* [Node.js](backend/nodejs/README.md)
* [Python](backend/python/README.md)
* [REST Services](backend/rest/README.md)
* [Scala](backend/scala/README.md)

### Big Data
* [Best practices for Hadoop](big_data/hadoop/hadoop-management.md)
* [Hadoop Development & Best Practices](big_data/hadoop/hadoop-development.md)
* [Hadoop Management Hardware and OS](big_data/hadoop/hadoop-management-hardware-and-os.md)
* [Hadoop Management](big_data/hadoop/hadoop-management-hbase.md)
* [Spark Best Practices](big_data/spark/README.md)
* [Amazon Redshift Best Practices](big_data/redshift/README.md)

### Cloud Computing
* [Amazon Web Services](cloud/aws/README.md)

### DevOps
* [Configuration Management](devops/configuration_management/README.md)
* [Docker](devops/docker/README.md)
* [Infrastructure Management](devops/infrastructure/README.md)
* [Git](devops/git/README.md)

### Frontend
* [Angular.js](frontend/angular/README.md)
* [HTML5](frontend/general/html/README.md)
* [Javascript](frontend/general/javascript/README.md)
* [CSS & Styling](frontend/general/css/README.md)
* [Frontend Tool Ecosystem](frontend/general/tools/README.md)
* [Polymer](frontend/polymer/README.md)

### IT Security & Hardening
* [Server Security](it_security/server_security/README.md)
* [Secure Development](it_security/secure-development/README.md)

### Quality Assurance
* [ATDD Acceptance Test-driven Development](qa_testing/testing/ATDD/README.md)
* [Calabash](qa_testing/calabash/README.md)
* [Code Design](qa_testing/code_design/README.md)
* [Code Optimization](qa_testing/code_optimization/README.md)
* [Cucumber](qa_testing/cucumber/README.md)
* [Testing techniques](qa_testing/testing/TestTechniques.md)
* [TDD, BDD and Acceptance Test](qa_testing/testing/GoodPracticesBDD.md)
* [TDD Test-driven Development](qa_testing/testing/TDD/README.md)

## Contrib Guidelines
* To contrib using issues and [pull requests](https://help.github.com/articles/using-pull-requests/). For instance if you want to contrib to the documents of __Calabash__ and __Server Security__ you first should check if there is an [__issue__](https://github.com/beeva/beeva-best-practices/issues) about those subjects, if there isn't you should create 2 separate issues, and explain on the body of the issue what contributions you want to make, the whole idea behind this is that if another employee wants to contribute to the same document you both don't duplicate content, so the __issues__ will be the communication method between the __committers__. Once you agree on how you will contribute either (alone or with your colleagues) you can create a fork from the repo, you and other committers of the same document/subject have to use the same forked repository so you need to agree who will be the "fork" responsible (and of course grant write permissions between yourself in the fork).
* Once all your contributions are finished in your fork, you should send a Pull Request petition so the integrators can review it and merge it into the main repository of best practices.
* [Here is](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet) the markdown cheatsheet you can use to create your documents.
* Write in english please :), don't worry if everything is not perfect as we will continue improving this guidelines overtime as we find and implement new best practices.
* Add attributions and references if necessary to external sites, it's nice when your work is recognized by others.
* Please add the images that you required to this repo in the *static* subfolder of each subsection, in this way we ensure no broken links will be ever created, avoid using external image links.


---

# Licence

Please see [LICENSE](LICENSE).

[BEEVA](http://www.beeva.com) | 2016
