ojb-1.0.4
=========
This is a patched version of OJB 1.0.4 since the Apache ObJectRelationalBridge has been 
retired in 2011. Several bug fixes were needed for continued support of Kuali 
applications that still rely on OJB.

KUALI-README.txt has details of the applied changes since the official OJB 1.0.4 release.

The patched ojb-1.0.4 version is home at https://github.com/kuali/ojb-1.0.4 .

Build Instructions:
-------------------
* Use Java 6. Java 7 & 8 causes build errors.
* Run `ant clean jar` to build the jar.
* Optionally run `mvn install` to add the jar to your local .m2 repo.
