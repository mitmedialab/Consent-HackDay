# Consent Hack Day at Media Lab

## Event site: https://mitmedialab.github.io/Consent-HackDay/

## #ConsentHackDay

## Functional Aspects

0. Provide individuals an easy to use method for expressing they do not consent to add tracking in a way that services must comply with

1. What is the policy? (Content)

2. How is the policy rendered for user independently of whoever created it? (format, language, display)

3. How is the policy coded? (Which bits mean what?) 

## GDPR Connection
* In context of GDPR consent, use of this cookie approach should be structured to become part of the consent process and the result should include agreement on the user terms with the vendor terms

* The Nightmare letter: https://www.linkedin.com/pulse/nightmare-letter-subject-access-request-under-gdpr-karbaliotis/


## Other considerations

- Substitutability
    - Where you inherit policies from
    - Where you get the rendering

... carrots for the ad industry
- Intent casting
- Better signaling
- Better programmatic framework
- Eliminate fraud and malware
- Speed up load time
- Increasing operational efficiencies in a world where consent is in play
- Risk reduction, efficient audit reporting
- IAB Europe clearly states in their documents that the 'cookie' solution is a temporary measure. We can help them with design inputs that are more person-friendly.

## Technical Aspects
* There is a cookie capability that could be a good fit.  There are a handful of flags that can be set.

## 

### Technical Links

IABE Cookie Format: https://www.google.com/url?q=https://github.com/InteractiveAdvertisingBureau/GDPR-Transparency-and-Consent-Framework/blob/master/Draft_for_Public_Comment_Transparency%2520%26%2520Consent%2520Framework%2520-%2520cookie%2520and%2520vendor%2520list%2520format%2520specification%2520v1.0a.pdf&sa=D&ust=1523464528097000

JSON file for purposes & vendors (from above link): https://vendorlist.consensu.org/vendorlist.json

IAB JS Library: https://www.google.com/url?q=https://github.com/InteractiveAdvertisingBureau/GDPR-Transparency-and-Consent-Framework/blob/master/Draft_for_Public_Comment_Transparency%2520%26%2520Consent%2520Framework%2520Formatted%2520CMP%2520JS%2520API%2520v1.0.pdf&sa=D&ust=1523464528097000

GDPR https://gdpr-info.eu

Registered CMPs http://advertisingconsent.eu/iab-europe-transparency-consent-framework-list-of-registered-cmps/


# Organizations who could participate

* Kantara Initiative https://kantarainitiative.org
** Consent & Information Sharing WG - Produced the Consent Receipt Specification 
** Consent Management Solutions WG - Developing a compendium of consent management practices from companies that claim to 'do' consent management. Will become a Best Current Practice doc then a certification program.
* EFF
* IEEE
* Wymsical/Wault
* HIE of One
* Hyperledger Indy
* Sovrin Foundation
* TUCOWS (hover et al.)
* Customer Commons
* IAB Europe :)
* Aligned Orgs/Companies/etc.
** DCN (formerly Online Publishers Association in USA)
** ITEGA
** Mozilla
** Cliqz
** Brave Browser
** IAB Labs

# Quick Hack Teams

## Legal: Applicable Rules and Terms

* Elizabeth
* Dazza
* Robert Mahari
* Stephanie

## Technical: Hack the Cookie Terms
hang out link: https://hangouts.google.com/call/f71g1SrzihwRublHgFC2AAEE


* Sal (seek a privacy dashboard for individuals)
* Sean 
* Hanno 
* Sam
* Sherry
* Andrew (from time to time)

## Business: Describe "Go to Market" Use Case in Engineerable Way
* Doc
* Joyce
* Dazza 
* Sean
* Stephanie
* Kathy
* Bill
* Adrian
* Dmitri
 

# End of Day Report Outs

# Business (Go-to-Market)
## Ideas
* Getting Mozilla, et. al. to add this to the browser
* Getting EFF to put this in Privacy Badger
* Getting friendly startups
* Q: What differentiates the different CMPs? 
* Two approaches: 1. Customer Commons listed as CMP 2. Customer Commons hijacks CMP's UI

## Buildable description (scope)
* Make an engineerable spec, something buildable, that we can evaluate against the intention
**DRAFT Indications for Use:** 
* "Provide data subjects a method for expressing they do not consent to profiling in a manner acceptable to data controllers."
    - Tracking is: ad tracking, profiling by third parties, 
    - Data subjects are defined by the GDPR
    - Manner acceptable is a cookie or equivalent

## Narrative to Technical Engineering Teams

## Narrative to Users (Tech Wizards and Muggles)

## Go to Market
### Possible promotional partners
* Linux Journal
* (See others above)
### Use customer commons as a certification provider
* Very heavy, slow process - lots of work
* 


## Benefits
### Data Subjects
* Peace of mind
* Removal of consent wall
* Faster load time
### Data Controllers (= IAB E publisher)
* Reduced operating cost / risk
* Align values with data subjects (= less friction e.g. on-boarding)
* Reduced incentives for ad-blocking
### Data Processor
* Reduced operating cost / risk
### IAB E
#### Publisher (website owner)
* Faster load time
* IAB PDF about why Publishers should use their framework - includes benefits and value to publishers. http://advertisingconsent.eu/wp-content/uploads/2018/04/TCF-Publisher-Facstsheet-2504.pdf
#### Vendor (owns ad inventory / ad tech / data broker)
#### Consent Manager Provider (CMP)
### Civil Society / GDPR DPA




# Technical (Hack the Cookie)
* link to notes doc: https://docs.google.com/document/d/1F5TSucLbIyU_4xJZy-RkTnRtzEaSK2R2qfScVKAbYj4/edit?ts=5ae21fd7

Table to be updated! Link above up to date

| Purposes | IAB E Says | Customer Commons Says |
| -------- | -------- | -------- |
|      | Storage and access of information      | You can ask us to delete/forget when you want     |
|      | Personalisation   |Tracking (GDPR: Profiling)| 
|     | Ad selection, delivery, reporting   |My topic prefs and exclusions | 
|      | Content selection, delivery, reporting   |Where do I see the logs?| 
|      | Measurement  |Only aggregate info allowed (at least c. 10 subjects) | 
| Duration?     |  |    |
| Features    |      |      |
|      |Matching Data to Offline Sources|You won’t use my data to correlate me with my offline self|
|      |If you link my devices through pivotal data points I supply implicitly or explicitly, you will notify me?|
|      |    Precise Geographic Locations  |      |
|     Vendors |      |      |
|      |      |      |
|      |      |      |
|      |      |      |


Basic Chrome Extension demonstrating cookie setting mechanism: https://github.com/TelegramSam/ConsentCookieManager






# Legal (Terms and Rules)

### Questions:
* To what degree does a blanket "do not track me" cookie satisfy the GDPR requirements for specific consent?
* Does a chrome extension give the data subject sufficient clear info?
* What are the requirements of GDPR's certification idea and how could we satisfy them? Could this act as an additional incentive?
* What are the transparent icons GDPR speaks about, who defines them (UI task)?
* 
