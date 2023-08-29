```


Deployment Overview
This page provides a brief overview of the AppDynamics deployment options. 


AppDynamics provides Cisco AppDynamics and the cloud-based Software as a Service AppDynamics SaaS solution. AppDynamics hosts and maintains both environments. You have the option to manage user account credentials via SAML or LDAP integration.

Every deployment includes


* A Controller Tenant for data collection.


* A Controller Tenant UI to view, understand, and analyze the data. 


* An online Account Management Portal to manage your account, users, subscriptions, license usage, and role functionality.


 

Every deployment requires


* Installed agents to collect data from your monitored environment. 


* Network port requirements.


* Health rules to monitor system parameters.


* Validated users.


 

AppDynamics does not support user or agent requests that originate from any URL other than the Tenant URL provided at registration or otherwise edited by AppDynamics. Due to system security improvements, requests from custom URLs will be rejected and may cause a service disruption.

If you require a custom URL, we recommend that you create a forward proxy in your environment.

```

