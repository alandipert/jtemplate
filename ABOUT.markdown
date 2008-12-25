###Directory structure
    
+ __docs:__ Project documentation. API javadocs will be written to docs/api/ 
  directory. You can include anything you want here (documentation for 
  dependencies, etc).  

+ __lib:__ Jar files to be incorporated into the distribution jar file.

+ __resources:__ Resources to be included in the distribution jar file.  They 
  will be added to the jar with a path relative to this directory, i.e., 
  resources/foo/bar.jpg will be accessed in java as "foo/bar.jpg".

+ __src:__ Java source files go here.

###Files:

+ __default.properties__ Project-specific preferences for the build process.

+ __build.properties__ User preferences for the build process.

+ __&lt;projectname&gt;-start.sh__ Application launcher wrapper script.
