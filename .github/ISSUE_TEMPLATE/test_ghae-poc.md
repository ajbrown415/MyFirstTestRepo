---
name: test_GHAE POC
about: 'Request a pilot for a GHAE prospect '
title: test_GHAE POC Request_[add customer name]
labels: ''
assignees: ''

---

## Pilot Status

See/update the status on the [project board](https://github.com/github/sales/projects/36)

- [x] Pilot request submitted
- [ ] Pilot request approved by Regional Sales/SE Leader and Maya (links to comments)
- [ ] [Pilot addemdum](https://docs.google.com/document/d/1kKOaYk-ffJ0iu9hK4TcqTg4bjjyR0HoJo9JuVhPIk9s/edit?usp=sharing) signed by the customer and by either dedicated MSFT Business Desk or GitHub Inc. Usually large customer have dedicated business desks but if a small customer, then GitHub can sign the addemdum. 
- [ ] Customer provided instance name and admin e-mail
- [ ] Pilot started

## Who is the pilot for and what's their context?

- Company Name: TDB
- Link to SFDC Opportunity: TBD
- Link to SFDC PoC Object: TBD
- Account Rep:
- Account SE:
- Regional Sales Leader/Sponsor:
- Existing customer: Yes/No
  - Number of seats: (specify product)
  - What services are they using: (Actions, GHAS, Connect, PRH, etc)
  - Number of potential seats: (specify products)

_Briefly explain why the customer is interested in the pilot and why this would be a valid candidate leading to a purchase._

## Pilot requirements?

- 🌐 Which region should be pilot be deployed on? _(US, Germany, UK, etc) - add corresponding label_
- 📆 What is the target date for pilot to start:
- :cloud: What type of deployment is required (Commercial, GovCloud, Secret, Top Secret):
- :computer: What product(s) and version(s) is the customer using (GHE 2.22, BBS 4.0, etc):
- :truck: Which of those products will we need to migrate data from (all or specify):
- :information_source: After pilot is approved internally customer needs to provide: 
  - Instance name: `INSTACE_NAME.githubenterprise.com` for Commercial and `INSTANCE_NAME.github.us` for Us Gov
  - Admin e-mail: the e-mail of the person that will be setting up the IdP integration (i.e. AAD)

## What to do when the pilot gets approved and instance launched?

[Send the documentation to the administrator](https://docs.github.com/en/github-ae@latest/admin/configuration/initializing-github-ae). 

### GitHub Actions (CI/CD) Context

> Use this section to explain where the customer is in their CI/CD journey, their strategy and plans. Please add as much details as you see fit in addition to the questions below. If Actions is critical to this pilot and deal, please directly cc `@thejoebourneidentity`.

 - How crucial is GitHub Actions in the context of the whole deal?
 - Which CI systems are in use at the company?
 - Are the runners hosted on on-premise hardware, using a public cloud or hosted by a CI vendor?
 - Is this customer trying to offload compute from on-prem, public cloud into vendor managed?
 - Do you have an idea (% wise) of where this company spends their compute minutes (on-prem, cloud, CI vendor cloud)?
 - Do you have an estimate of how many CI/CD minutes they use?
 - Is this company an Azure customer or do they have other big cloud deals with the other Big 2?
 - Is there a hard requirement on self-hosted runners and why? Please justify if so.

## Terms and Condition

After confirmation that the pilot has been approved, the account team needs to have the customer or prospect accept the terms and conditions for the pilot.

cc:
