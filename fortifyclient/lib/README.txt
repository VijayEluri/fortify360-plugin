You are suppose to put the wsclient.jar, wsobjects.jar, common.jar and common13.jar inside in this directory in order to compile the code. But of course, I can't distribut Fortify proprietary files.


The file name should be e.g.

wsclient-2.5.jar <-- this is for Fortify 360 server version 2.5
wsobjects-2.5.jar
common-2.5.jar
common13-2.5.jar

And starting from v3.0.0, common.jar and common13.jar are merged into fortify-common.jar. Just duplicate it to common-3.0.0.jar and common13-3.0.0.jar