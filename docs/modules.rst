.. _modules:

Modules
=======
Omnibus supports all of the following modules for **version 1.2**.
Some of these modules may require public / free API keys. We made sure not to include any modules that forced users to pay a third party for access to its API functionality - you can read more about the API keys on your API Keys documentation page, as well.

**All currently available modules:**


* Blockchain.info
* Censys
* ClearBit
* CSIRTG
* Cymon
* DNS resolution
* DShield (SANS ISC)
* GeoIP lookup
* Full Contact
* GitHub user search
* HackedEmails.com email search
* Hurricane Electric host search
* HIBP search
* IPInfo
* IPVoid
* KeyBase
* Nmap
* PassiveTotal
* PGP Email and Name lookup
* RSS Feed Reader
* Shodan
* ThreatCrowd
* URLVoid
* VirusTotal
* WHOIS

Future Plans
------------
We had some time-constraints and many unfinished or buggy modules did not make this initial Beta release. Although within the next few days to weeks, we will continue to expand Omnibus' module capability.

Including:

* modules to import data from remote sources:
    * HTTP Files (Text, PDF)
    * Local Files (PDF, Office)
    * Amazon SQS

* modules to export enriched data to remote sources:
    * HTTP REST Endpoints
    * Amazon SQS

* executing modules across more than one artifact in bulk

* ability to query MongoDB for specific fields and values

* ability to query MongoDB and run modules on returned results

* adding detailed documentation on how anyone can contribute their own module
From executing modules across more than one artifact, give users the ability to query the database and run modules on all returned results, as well as providing detailed documentation on how you can add your own module back to our main repository! :)

If you wish to contribute, please visit our GitHub repo for this project (located on the left side bar) and submit your Issue or Pull Request. We try to get to any and all issues immediately, though if several days to a week have passed without a repsonse, please make a small comment on the Issue/PR just to remind us :)


Return to Homepage
------------------
Click here to return to main documentation page: `a home`_.

.. a home: https://omnibus.readthedocs.io/en/master
