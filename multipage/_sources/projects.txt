========
Projects
========

Admittedly I do not have a huge portfolio of projects to offer, and only one 
public project per-se, and I think that's one of my largest shortcomings: I 
seldom do my own projects, instead I do small hacks and fixes to other projects 
and submit pull requests.


######
Public
######

----------------
gigya-server-lib
----------------

I have only one public project, a port of `Gigya <http://www.gigya.com>`_'s 
SDK to python called 
`gigya-server-lib <http://pypi.python.org/pypi/gigya-server-lib/0.1.3>`_. 
The library is not entirely pythonic to maintain it closer in usage to the 
original. It has been abandoned since Gigya developed their own.

As an aside, while working on this library I discovered a security bug that 
was disclosed to Gigya.


----------------------
Assorted pull requests
----------------------

I've made small contributions to the following projects:

* Mongo C# Driver:
    - `CSHARP-204 <https://jira.mongodb.org/browse/CSHARP-204>`_: found, 
      diagnosed and fixed a concurrency issue in the mongodb driver for C#
    - `CSHARP-200 <https://jira.mongodb.org/browse/CSHARP-200>`_: created a 
      patch in response to a feature request for the C# Driver
* AL-Redis: `a quick patch <https://github.com/angieslist/AL-Redis/pull/5>`_ 
  in response to having seen a TODO on the code. (I never got the chance to use
  AL-Redis but found the TODO while browsing the code.)
* `mumble <http://mumble.sourceforge.net/>`_: No link but some client 
  functionality for saving last connected channel and some other settings 
  c.2005, patch submission was via email/IRC back then.

#######
Private
#######

* Architected new version of our Newspaper CMS for availability and scalability using 
  .NET MVC 4.0 and .NET Web API 2.0, implementing an MQ based job system for better
  backend user satisfaction. The FrontEnd was architected to use the subset of ESI 
  available in varnish for a better user experience
* Implemented a read-only API translation middleware using .NET Web API 2.0 and 
  AutoMapper to provide a proxy API so that legacy API responses could be
  cleaned up and made more consistent:

    - Corrected usage of mixed case, mixed language keys in json response
    - Coerced output into consistent output models (previously two representations
      of a model presented two different ways would have inconsistent keys)
    - Corrected HTTP status responses (legacy API always responded with 200 even 
      for empty responses)

* Implemented JIRA webhook processor in Falcon that:
    - Triggered and synchronized PagerDuty alerts for multiple projects/teams
    - Managed internal subproject issue dependencies to create a global project
      that gave visibility to project managers into many teams and projects

* Led switch to AWS for various products, worked closely with developers to
  help make the transition smoother and diagnose any problems
* Created guidelines with networking and datacenter operations teams to influence 
  their architectural choices
* Wrote a real time log aggregator and analytics service in python to monitor the
  most popular news articles on elnuevodia.com and primerahora.com
* Configured varnish to do things nobody should ever do on varnish to make up
  for a third party application's lack of caching
* Managed the cloud infrastructure initiative for GFR Media using AWS and 
  Rackspace Cloud.
* Architected solutions for web deployments using various AWS services

