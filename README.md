# CTOstartwhere

Taking an IT management role in a new company? Don't know where to start? Then, you're welcome.

Disclaimer: In reality, and condescension aside (don't misunderstand me). I found myself in a role of responsibility where I had to manage all the IT equipment, licences, software, troubleshooting, etc. Sometimes you're blessed and everything runs smoothly, everything is already up and running, but sometimes there's nothing and you start from scratch.

If you fall into the 2nd category then you can continue reading.

## What, Where, Who, When, Why?

The basic questions that really get you started and enable you to take stock of the situation.

## Inventory is all.

I know this phrase sucks. But hear me out.

Make an inventory of everything that's physical... screen, CPU, mouse, keyboard, servers, printers, etc. everything. The advantage is that you don't actually have to do it yourself, you can delegate or ask certain users if their level allows it.

Here is the information you need to gather:

* Brand.
* Model.
* Serial Number.
* Date of purchase.
* End of warranty date.
* User.
* Previous user.
* Where can I find it? Where in the open space? In which office? Be specific so you don't waste your time searching for a switch hidden behind a printer.

## What about softwares?

Same. inventory is all.

* List all software: Free and open source (FOSS), Freemium, proprietary, etc.
* Licence.
* Name.
* Date of purchase.
* End of subscription.
* Who purchased it and with which e-mail address? Important if the person leaves the company and the licence is bound to a specific address.

Make a dashboard to follow the subscriptions you have. A SharePoint list will do perfectly. In your list, add the link to the website, you'll save time.

WAIT A MINUTE. You thought it was that easy? No, what about the credentials used for that subscription? Yes... you need to document that also. Because if your CTO leaves, what about the email address used to log in and subscribe? You lost it all. So document it.

## Password manager

Two words: password. manager. Everyone, and everything must be in a password manager. You're not clever saving your logs in Excel files. You don't have redundancy or contingency plans. It is their job. I recommend:

* 1password.
* ProtonPass.
* Bitwarden (FOSS).

It will also help you make quick offboarding processes through the admin tool.

## Infrastructure Documentation

So, now we have the lists of:

* All the hardware (What, where)
* All the software (What, where)

To those, we will add the user access (who):

* Who can log in where and with what level of access?
* Is it necessary? (why)
* Any superadmin out there who shouldn't be?
* Old employee access?

## Diagram time

Now that everything is listed. Time to draw it. Don't waste time, make it functional and easily readable. You can use one of the following software:

* Microsoft Visio
* Draw\.io (open source)
* Excalidraw (FOSS)
* tldraw (FOSS)
* Miro (Honestly, f\*\*\* the hype around this. But it is a good all-in-one solution if you can afford it and need more than IT diagrams.)

The aim here is to have a visual representation of what you have, hardware and software. This will ease your decision-making process and your CEO should understand it.

## Security & Compliance

I hate to break it to you, but yes, this is also your job now.

1. Checklist security
  * Antivirus ?
  * Firewall ?
  * MFA activated ?
2. Quick audit of risks and vulnerabilities
  * OpenVAS is FOSS
3. Physical access management
  * Badges
  * Keys
4. Backup strategy:
  * Is it in place?
  * Tested recently? (Bacula is FOSS)
  * Redundancy ? Where ?
5. GDPR and regulatory compliance basics

## Contracts & Providers

Who loves paperwork? Nobody. But it's essential:

1. List all critical providers (contacts, SLA, renewals)
   * Contacts
   * SLA
   * Renewals
2. Existing contracts
   * Duration
   * Key clauses
3. Simplified procurement process
   * Who approves
   * spending thresholds

## Budget & Finance

Don't skip this or your CFO will make your life miserable.

1. Current IT budget (CAPEX, OPEX)
2. Upcoming financial deadlines (licence renewals, planned purchases)
3. IT spending history (anticipate better)

## Support & Incidents

Nobody likes incidents, but they happen:

* Incident reporting process (ticketing tools: Zammad or GLPI are FOSS)
* Statistics of frequent incidents (anticipate future needs)

## Quick Checklists

Save your future self time, create these:

* Employee onboarding (access, hardware, standard software)
* Employee offboarding (revoke access, retrieve hardware, reset devices)
* Crisis management checklist (server outage, cybersecurity incident)

## Communication & Internal Awareness

Users are your best allies and your worst enemies (dumb in both case):

1. Quick email template to raise awareness of IT best practices (password management, phishing, software installs)
   * password management
   * phishing
   * software installs
   * incidents
   * doubts -> better encourage them to ask if any doubts than be ransomwared to oblivion.
2. Recommended awareness frequency (e.g. quarterly)

## Recommended Team Collaboration Stack (please avoid big US tech company like hell).

Let's make teamwork suck less:

1. Collaborative suites
   * Nextcloud (FOSS) and very good
   * MS365 99% chance you've inherited this shit and you'll be stuck in it. Don't even try to change it if your users are on it. Waste of time and energy.
   * Google Workspace. Say byebye to privacy.
  
2. Internal messaging tools
   * Mattermost (uninstall this shit right now).
   * Rocket.Chat (FOSS)
   * Slack
   * Teams...
     
3. Secure cloud storage
   * Nextcloud
   * OneDrive
   * Dropbox
   * Google Drive
   * Proton Drive

## Emergency Documentation

When everything breaks, you'll thank me for this:

* Centralized simplified doc for emergencies (emergency access credentials, critical contacts)
