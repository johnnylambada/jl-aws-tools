jl-aws-tools
============

A fun toolbox of aws scripts

== ec2GetUbuntuAmi ==

ec2GetUbuntuAmi returns the current 'ami-xxxxx' for the given configuration. It queries the same table that cloud.ubuntu.com/ami searches.

* requires: node.js

== s3AuthUrl ==

A bash script that will generate a query string for a protected S3 resource as described [here](http://docs.amazonwebservices.com/AmazonS3/latest/dev/RESTAuthentication.html#RESTAuthenticationQueryStringAuth).

* requires: perl
* requires access to your AWS Access Key Id and Secret
