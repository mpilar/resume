.. raw:: pdf

    PageBreak

================
Technical Skills
================


This is a list of my stronger technical skills. Through my years
I've made many different small projects with varied purposes. Among
them:

* 6+ years experience with Python and C#
* Have played with many others like Go, Ruby and even AutoIT

##
C#
##

When not programming in Python for work I've had to *maintain* C# applications
be them web, console or desktop. I've had some experience working with ASP.NET 
MVC.

######
Python
######

I've spent the last few years programming in Python professionally and 
otherwise. Most of my experience with Python is centered around
writing web applications and management scripts.

********
requests
********

I will be frank, I don't actually remember how to use urllib for actual web 
requests (still use it to parse urls, etc) and would have to spend a few 
minutes figuring things out again, requests is just so perfect.

******
Django
******

For most web projects that interact with databases I enjoy using django. I feel
The django app ecosystem is powerful and make it very easy to create a complex
project quickly and efficiently.

*****
Flask
*****

For smaller web projects and prototypes I turn to Flask, nimble enough to 
create small projects quickly but powerful enough to expand them into larger 
projects. Specially true of projects that don't need an ORM to be tightly 
integrated.

******
Falcon
******

A great framework for middleware and/or pure APIs, it's speedy and very useful
for APIs and generally "glue" projects.

******
Celery
******

When doing tasks asynchronously celery provides a quick and very well designed
platform to do them with.

#####
Redis
#####

I've used Redis as a very powerful hash and key/value store. I am always
impressed with it's speed and stability.

##########
PostgreSQL
##########

This is my preferred relational database, but I have only played around with
it's more advanced and powerful features like writable CTEs.

######
jQuery
######

I don't always have to work with javascript, but when I do, I enjoy using
jQuery for it. At least where browser compatibility is concerned.

###
Git
###

My preferred source control mechanism, but not the only one I have experience
with. I am by no means an expert but know the commands used on most workflows.

###
AWS
###

I am familiar with most AWS services, that is to say I've used most of them, 
while I am not an expert at all of them I understand where they are best used
for certain jobs. I have scripted some aspects of our operations using python
and boto.

###########
munin/monit
###########

I have used munin and monit to monitor and script some self-healing into hosts.

######
StatsD
######

While it has been replaced with Cloudwatch, StatsD has been a go-to tool for
metrics collection.

#######
Grafana
#######

A great way to create a dashboard for metrics.

#######
Varnish
#######

Varnish is for my go-to tool for caching full web pages or even fragments 
through ESI. I've spent time tweaking configurations and adapting Varnish to 
cache pages in a legacy application that had no concept of browser caching.

##############
Traffic Server
##############

When a caching layer does not need to have as many customizations of the 
request/response as can be done with Varnish I have used Apache Traffic
Server which is an extremely powerful caching server with a tiered 
architecture.

#######
haproxy
#######

While there are other load balancing options, I find that haproxy has the
most flexible balancing algorithms.

################
spread/wackamole
################

This project is outdated but it's still useful to run N master clusters of
load balancers when necessary (it allows haproxy to scale horizontally by
sharing IPs among a cluster).