From tomcat:
We would like Apache httpd to act as frontend that receive user request and forward to the tomcat instance.

Use Case:

Based on the context root eg: /Dep1 /Dep2 /Dep3 it would redirect to the different tomcat instances.

Why should I integrate Apache HTTP Server with Apache Tomcat? (or not)

There are many reasons to integrate Tomcat with Apache. And there are reasons why it should not be done too. Needless to say, everyone will disagree with the opinions here. With the performance of Tomcat 5 and 6, performance reasons become harder to justify. So here are the issues to discuss in integrating vs not.
•	Clustering. By using Apache as a front end you can let Apache act as a front door to your content to multiple Tomcat instances. If one of your Tomcats fails, Apache ignores it and your Sysadmin can sleep through the night. This point could be ignored if you use a hardware loadbalancer and Tomcat's clustering capabilities.
•	Clustering/Security. You can also use Apache as a front door to different Tomcats for different URL namespaces (/app1/, /app2/, /app3/, or virtual hosts). The Tomcats can then be each in a protected area and from a security point of view, you only need to worry about the Apache server. Essentially, Apache becomes a smart proxy server.
•	Security. This topic can sway one either way. Java has the security manager while Apache has a larger mindshare and more tricks with respect to security. I won't go into this in more detail, but let Google be your friend. Depending on your scenario, one might be better than the other. But also keep in mind, if you run Apache with Tomcat - you have two systems to defend, not one.
•	Add-ons. Adding on CGI, perl, PHP is very natural to Apache. Its slower and more of a kludge for Tomcat. Apache also has hundreds of modules that can be plugged in at will. Tomcat can have this ability, but the code hasn't been written yet.
•	Decorators! With Apache in front of Tomcat, you can perform any number of decorators that Tomcat doesn't support or doesn't have the immediate code support. For example, mod_headers, mod_rewrite, and mod_alias could be written for Tomcat, but why reinvent the wheel when Apache has done it so well?
•	Speed. Apache is faster at serving static content than Tomcat. But unless you have a high traffic site, this point is useless. But in some scenarios, tomcat can be faster than Apache httpd. So benchmark YOUR site. Tomcat can perform at httpd speeds when using the proper connector (APR with sendFile enabled). Speed should not be considered a factor when choosing between Apache httpd and Tomcat
Socket handling/system stability. Apache has better socket handling with respect to error conditions than Tomcat. The main reason is Tomcat must perform all its socket handling via the JVM which needs to be cross platform. The problem is socket optimization is a platform specific ordeal. Most of the time the java code is fine, but when you are also bombarded with dropped connections, invalid packets, invalid requests from invalid IP's, Apache does a better job at dropping these error conditions than JVM based program. (YMMV)


S/w Used
1.	httpd-2.2.8
2.	apache-tomcat-7.0.25
3.	tomcat-connectors-1.2.32

URLS

https://archive.apache.org/dist/tomcat/tomcat-7/v7.0.25/bin/apache-tomcat-7.0.25.tar.gz

https://archive.apache.org/dist/tomcat/tomcat-connectors/jk/tomcat-connectors-1.2.32-src.tar.gz

http://archive.apache.org/dist/httpd/httpd-2.2.8.tar.bz2




