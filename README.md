# **Hosting WordPress on GCP**
### Version 1.0
Alright, are you thinking about deploying WordPress in GCP?

A good place to start is to get yourself familiarize with GCP (https://cloud.google.com/gcp/getting-started)

---

This is a POC architecture of WordPress running on GCP multi region using :

* GCP Networking: Google Virtual Private Cloud (https://cloud.google.com/vpcgcp )
* GCP Networking: Cloud DNS (https://cloud.google.com/dns)
* GCP Networking: Cloud CDN (https://cloud.google.com/cdn)
* GCP Database: Cloud SQL (https://cloud.google.com/sql)
* GCP Cloud Storage (https://cloud.google.com/storage)
* GCP Compute: App Engine (https://cloud.google.com/appengine)

## Prerequisites

* Good understanding of GCP  basic components and GPC account 
* Knowledges of WP
* Console access 
* Create a project in the Cloud Console.
* Enable billing for your project.
* Install the Cloud SDK.
* Enable the Cloud SQL API.
* Install Composer.

## App Engine

* Run WordPress on App Engine (https://cloud.google.com/community/tutorials/run-wordpress-on-appengine-standard)

## Deployment steps

1. Deploy GCP Networking infrastructure
2. Deploy App Engine
3. Create and Configure WordPress
4. Domain setup and certificates 

## Cost analysis

## Author
Please reach out to me if you have any questions on this diagram.

