# Week 0 — Billing and Architecture

So, the journey begins...

First off, I created all the required accounts

- New AWS account, 
- Gitpod and integrated it with github using a browser extension, 
- Lucid, 
- Rollbar, 
- Honeycomb and 
- configured Github Codespaces, just in case.


I had a dormant domain name and host which I plugged into this bootcamp project.


I already had Cantrill course which guided me to install the AWS CLI v2 early this year after reinstalling Windows 11, but I haven't been able to continue since the year began.

![AWS CLI](https://user-images.githubusercontent.com/109069039/220363490-a3041b52-2cd3-4d29-a6a5-bde2beeb4a9a.png)
AWS CLI


I read further on how to set up Momento since this was the only requirement that was a bit edgy for me at first. I downloaded a MSI package and had it installed
Here is a screenshot of how it looks like on my PC.

![Momento](https://user-images.githubusercontent.com/109069039/220365880-af8e2ec5-227c-420b-8458-10766edc52ac.png)
Momento installed


Other required tasks were:
- I also used MFA to secure all accounts.
- I also created admin user and generated AWS access keys and Secret access keys for use on the CLI. 
- I created cloud billing alarms and set up a $5 budget with alarm at 80% expenditure on root at first then on admin account thereafter.
- I added tags to be able to associate which processes with which processes. This [link](https://cloudacademy.com/blog/aws-tags-important/) gives better explanation. 
- I tested out event setting on Amazon EventBridge and set up parameters on health issues


Chirags video washelpful in understanding
