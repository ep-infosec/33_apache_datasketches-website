---
layout: doc_page
dev: https://lists.apache.org/list.html?dev@datasketches.apache.org
users: https://lists.apache.org/list.html?users@datasketches.apache.org
---
<!--
    Licensed to the Apache Software Foundation (ASF) under one
    or more contributor license agreements.  See the NOTICE file
    distributed with this work for additional information
    regarding copyright ownership.  The ASF licenses this file
    to you under the Apache License, Version 2.0 (the
    "License"); you may not use this file except in compliance
    with the License.  You may obtain a copy of the License at

      http://www.apache.org/licenses/LICENSE-2.0

    Unless required by applicable law or agreed to in writing,
    software distributed under the License is distributed on an
    "AS IS" BASIS, WITHOUT WARRANTIES OR CONDITIONS OF ANY
    KIND, either express or implied.  See the License for the
    specific language governing permissions and limitations
    under the License.
-->

# Apache DataSketches Community

## Transitioning From Our Previous GitHub Site

* If you were a user of our library from our previous <a href="https://github.com/datasketches">GitHub Site</a> please refer to this <a href="{{site.docs_dir}}/Community/Transitioning.html">Transitioning</a> page.

## How We Communicate

There are many ways that are available for our community to communicate with each other and directly with our developers.  Please review the following for methods that meet your needs.

### [Users Mailing List]({{page.users}}) 
This is a great place for all users (new and experienced) to ask general questions about the library, its general capabilities, and where to get help and find more information.  This is also a great place to give the developers general feedback about the library. If you like what you see, please give us a [Star (Java)](https://github.com/apache/datasketches-java) and/or [Star (C++/Python)](https://github.com/apache/datasketches-cpp) If you have general suggestions on how we can improve we would like to hear from you.  All of our developers follow this list and all sincere questions and comments will get a response.
    
* To subscribe send an empty email to [users-subscribe@datasketches.apache.org](mailto:users-subscribe@datasketches.apache.org).
* To unsubscribe send an empty email to [users-unsubscribe@datasketches.apache.org](mailto:users-unsubscribe@datasketches.apache.org).
  
### [Developers Mailing List]({{page.dev}})
This is where the developers, committers, and contributors congregate to discuss, vote and establish priorities on addressing issues and opportunities with the library. The issues discussed tend to apply across all the different components of the library (see below).
    
* To subscribe send an empty email to [dev-subscribe@datasketches.apache.org](mailto:dev-subscribe@datasketches.apache.org).
* To unsubscribe send an empty email to [dev-unsubscribe@datasketches.apache.org](mailto:dev-unsubscribe@datasketches.apache.org).

### Slack
Chat with users and developers on Slack in _the-asf.slack.com_ workspace. 

* Anyone with an _apache.org_ email account can freely join via [ASF Slack Signup](https://the-asf.slack.com/signup).
* Otherwise, please send an email to our developers mail list above and we will send you an invite to join our slack channel. Join the _#datasketches_ channel when you receive notification.

### Bugs and Issues
If you have a problem or issue with any aspect of the performance, accuracy or documentation in our library please file an issue with the relevant [Component](https://datasketches.apache.org/docs/Architecture/Components.html) GitHub site.


## Contributing

We are always open to contributions from our community.  Contributions can be of many forms: documentation, testing, science as well as bug fixes, code enhancements, code reviews, feature suggestions, usability feedback, etc. Contributions usually take the form of a Pull Request (PR), but if you wish to contribute and not sure how, please contact us on our <dev@datasketches.apache.org> list.  

We are also open to the submission of entirely new sketch algorithms.  If you have a sketch algorithm (or a significant enhancement of our current algorithms), please read our [Sketch Criteria]({{site.docs_dir}}/Architecture/SketchCriteria.html) and contact us on our <dev@datasketches.apache.org> list.

## [Our Component Repositories]({{site.docs_dir}}/Architecture/Components.html)

### What to work on
* Our library is made up of components that are partitioned into GitHub repositories. If you have a specific issue or bug report that impacts only one of these components please open an issue on the respective component. If you are a developer and wish to submit a PR, please choose the appropriate repository. But most important, please contact us on <dev@datasketches.apache.org>

* We have three TODO lists for [Java](https://github.com/apache/datasketches-java/projects/1), [C++](https://github.com/apache/datasketches-cpp/projects/1) and the [Website](https://github.com/apache/datasketches-website/projects/1). Please check these out for potential contribution!

### Getting your proposed changes accepted

Proposed changes to the code or documentation are usually done through GitHub Pull Requests (PRs).

* Simple PRs, such as simple bug fixes, typos, and documentation corrections require one approval vote (+1) from a committer.
* Major changes to the code such as API or architectural changes or new sketch algorithms must be discussed on <dev@datasketches.apache.org> or on a GitHub issue as these will require additional design and compatibility reviews. These changes must receive at least three (+1) votes from committers. If the author is already a committer, than two additional committers must vote (+1). 

### Becoming a committer
We welcome anyone who is eager to continue to contribute to the DataSketches mission of providing open source, production quality sketch algorithms and become part of our team.  Please send us a message on <dev@datasketches.apache.org> where we can give you some guidance.  After you have made some successful contributions, the current committers will discuss your candidacy for becoming a committer.  You can also review the [Apache policies on becoming a committer](https://community.apache.org/contributors/index.html) as well as our [New Committer Process](https://datasketches.apache.org/docs/Community/NewCommitterProcess.html) for selecting and inviting a committer to join our project.  

### Reporting Security Issues
If you wish to report a security vulnerability, please contact <security@apache.org>. Apache DataSketches follows the typical [Apache vulnerability handling process](https://apache.org/security/committers.html#vulnerability-handling).

## Governance
The [Project Management Committee](https://www.apache.org/foundation/how-it-works.html) (PMC) is responsible for the administrative aspects of the DataSketches project.

The basic responsibilities of the PMC include:

* Approving releases
* Nominating new committers
* Maintaining the project's shared resources, including the github account, mailing lists, websites, social media channels, etc.
* Maintaining guidelines for the project