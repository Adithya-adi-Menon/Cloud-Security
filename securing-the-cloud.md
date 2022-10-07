# Securing the Cloud

\-> The responsibility for a secured cloud is split among the customer as well as the cloud provider. It is not the sole responsibility of the cloud the cloud provider to make the cloud secure

\-> Cloud can be secure or insecure depends on how we make it&#x20;

\-> Difference  B/W a Cloud Based Sec and Traditional IT Sec

<figure><img src=".gitbook/assets/image (1).png" alt=""><figcaption></figcaption></figure>

\-> Firewalls are built-in&#x20;

\-> Patching can be easy&#x20;

\-> Auditing tools are built-in&#x20;



\-> Cloud Vendor is responsible for security Of the cloud&#x20;

\-> Customer is responsible for the security in the cloud&#x20;

### ->AWS Shared Responsiblity Model&#x20;

<figure><img src=".gitbook/assets/image (3).png" alt=""><figcaption></figcaption></figure>

### -> Azure Shared Responsiblity Model&#x20;

![](<.gitbook/assets/image (2).png>)



\-> In the cloud API Key Access is same thing as physical world access in the real world



#### -> Vendor Lock-In :&#x20;

* Too expensive to migrate to another cloud vendor from previous vendor or forced to use the particular vendor&#x20;

#### -> Vendor Lock-Out :&#x20;

* Can easily switch between vendors if there is any problem not too expensive or stuck&#x20;

## Multitenant Environments

### -> Information Bleed :&#x20;

* With multiple customers using the same infrastructure it is possible that the data from Customer A could be accessed by Customer B

### -> Data Seizure/Legal Activity :&#x20;

* If Customer A's data/services are seized as part of a lawful order then Customer B could be offline &#x20;

## Virtualization Risks&#x20;

* Attacks on the hypervisor&#x20;
* Guest escape&#x20;
* Information Bleed
  * Meltdown and Spectre exploit
  * [https://meltdownattack.com/](https://meltdownattack.com/)&#x20;

\-> AWS API Log Hunting

\-> Credential Compromise via Public Exposure&#x20;

\-> Credential Compromise via Phishing

\-> Credential Compromise via Endpoint



## Defense Methodologies

* Host-base IPS
* Continuous Monitoring of logs&#x20;
* Continuous Patching
* Continuous Vulnerability Scanning
* Good User account Management&#x20;
* Automate everything&#x20;
* Configuration Management

