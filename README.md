
Java AWEZOMG
============

Java was invented during the war. As such it's still unsure about all these web whippersnappers and their do-hickies.

...and like a well built tractor, Java is stable and mature. There is no reason why your project has to look like one.

java-awezomg is here to help bring the old Java tools up to date. No more framesets for javadocs, no more fiddling to find the maven site button.

Heavily inspired by html5boilerplate.com and domainszomg.com


![Logical Awesome](http://logicalawesome.com/logical_awesome.jpg)


javadoc AWEZOMG
---------------
Overview page before:
![joda-time-javadoc-overview-regular](https://github.com/olizilla/java-awezomg/raw/master/src/site/img/joda-time-javadoc-overview-regular.png)

Overview page after:
![joda-time-javadoc-overview-awezomg](https://github.com/olizilla/java-awezomg/raw/master/src/site/img/joda-time-javadoc-overview-awezomg.png)

Tree page before:
![joda-time-javadoc-tree-regular](https://github.com/olizilla/java-awezomg/raw/master/src/site/img/joda-time-javadoc-tree-regular.png)

Tree page after:
![joda-time-javadoc-tree-awezomg](https://github.com/olizilla/java-awezomg/raw/master/src/site/img/joda-time-javadoc-tree-awezomg.png)

OK, so perhaps not totally awesome just yet, but better, and minimal fuss to set up.


Pre-requisites
-------------

Awesome maven:

* mvn site should be h5bp based
* http://maven.apache.org/guides/mini/guide-site.html

Markdown for maven site

* https://bitbucket.org/nicoulaj/doxia-module-markdown/
* http://codeslife.com/2011/05/05/markdown-is-supported-in-maven-site/
* https://github.com/larrycai/doxia-module-markdown

* http://www.mkyong.com/maven/how-to-create-a-project-with-maven-template/



TODO
----

* issues with pom for maven archetype
  * site has warnings due to unspecified version on plugin
  * no site is created when running mvn site on maven 3
    * need to add maven-project-info-reports-plugin as per:
      http://maven.apache.org/plugins/maven-site-plugin-3.0-beta-3/maven-3.html



