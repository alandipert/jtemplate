JTemplate
=========

JTemplate is a simple java project skeleton. Use it to start out new java
projects without making a big deal out of it. There are no dependencies other
than [java][] and [ant][], and there is no framework or IDE needed. Good for
if you don't use Eclipse or Netbeans or whatever.

[java]:       http://sun.java.com/      "Java"
[ant]:        http://ant.apache.org/    "ant"

Quickstart
----------

1.  Edit the _build.xml_ file to your liking.  The first few properties
    are clearly marked, and are expected to be set for your specific
    project.

2.  Run 'ant init'.  This deletes .git and makes you a _/src_ tree with
    a Main class stub and the _resources/_, _lib/_, and _doc/_ directories
    for your resource files, external jarfile dependencies, and project
    documentation.

3.  You're cooking!

Ant targets you might use from here on out (remember ant -projecthelp): 

+ 'all' or 'dist'
+ 'clean'
+ 'jar'
+ 'javadoc'

Directories
-----------
    
+ __docs:__ Project documentation. API javadocs will be written to _docs/api/_ 
  directory. You can include anything you want here (documentation for 
  dependencies, etc).  

+ __lib:__ Jar files to be incorporated into the distribution jar file.

+ __resources:__ Resources to be included in the distribution jar file.  They 
  will be added to the jar with a path relative to this directory, i.e., 
  resources/foo/bar.jpg will be accessed in java as "foo/bar.jpg".

+ __src:__ Java source files go here.

Files
-----

+ __<i>projectname</i>-start.sh__ Application launcher wrapper script.
