<div>

<span class="c2"></span>

<span class="c2"></span>

<span class="c2"></span>

</div>

<span class="c2">What is missing?</span>

<span class="c2"></span>

<span class="c2">Not explicit, or encoded.</span>

<span class="c2"></span>

<span class="c2">Domain specific cookie</span>

<span class="c2"></span>

<span class="c2">How does adtech/publish</span>

<span class="c2"></span>

<span class="c2"></span>

<span class="c2">Sam - hack an extension</span>

<span class="c2">Andrew- background reading - to try to figure out what we can express via the cookie</span>

<span class="c2">Sean - ICONS</span>

<span class="c2">Sal - JSON purposes</span>

<span class="c2"></span>

# <span class="c16">Key aspects of the consent cookie:</span>

<span class="c2"></span>

<span class="c2"></span>

<span class="c2">Go here for all the links to the Transparency & Consent Framework</span>

<span class="c6">[http://advertisingconsent.eu/](https://www.google.com/url?q=http://advertisingconsent.eu/&sa=D&ust=1524780472108000)</span>

<span class="c2"></span>

*   <span class="c2">Publisher - e.g. wired.com</span>
*   <span class="c2">Vendor - e.g. the ad-tech company in between you and wired.com</span>
*   <span class="c2">Consent Provider - the organization showing you the screen you consent to</span>
*   <span class="c2">Purpose</span>

<span class="c2"></span>

<span class="c2">Create a cookie that is honored by the advertiser selling space on wired.com</span>

<span class="c2"></span>

<span class="c2">Are there configurations of the cookie as defined in the document that are person friendly so they don’t have to do this every time (maybe?)  Can we change the bits to accomplish this?</span>

<span class="c2"></span>

<span class="c2">If we can parse what is in the cookie/api we can suggest additional functionality (get them to add purposes)</span>

<span class="c2"></span>

<span class="c2">Hack the cookie or hack the specification. (short term)</span>

<span class="c2"></span>

<span class="c2">Hacking the cookie can make it easier for the user...</span>

<span class="c2"></span>

<span class="c2">We can become the CMP… is this chosen by the vendor, if so we could then go to them indivually</span>

<span class="c2"></span>

<span class="c2">And write a vendor consent cookie, that has specific (defined by us) purposes (only 6)</span>

<span class="c2"></span>

<span class="c2">Can we create an EFF, Customer Commons CMP or set others up to do so…. And possibly create a consortium to do so (long term)</span>

<span class="c2"></span>

<span>[NOTE: Here’s a blog about one vendor’s CMP</span> <span class="c6">[https://www.sovrn.com/blog/sovrn-gdpr-cmp/](https://www.google.com/url?q=https://www.sovrn.com/blog/sovrn-gdpr-cmp/&sa=D&ust=1524780472110000)</span><span class="c2">   ]</span>

<span class="c2"></span>

<span class="c2">We could do a rogue version.</span>

<span class="c2"></span>

<span class="c2">Refer to JSON for specific references…</span>

<span class="c2"></span>

<span class="c2">Publisher purposes consent cookie format could be flipped to achieve global purposes not vendor specific.</span>

<span class="c2"></span>

<span class="c2">Using the official vendor list but can hack that.</span>

<span class="c2"></span>

<span class="c6">[https://vendorlist.consensu.org/vendorlist.json](https://www.google.com/url?q=https://vendorlist.consensu.org/vendorlist.json&sa=D&ust=1524780472111000)</span>

<span class="c2"></span>

<span class="c2">Chrome Extension API for client side cookie hacking:</span>

<span class="c6">[https://developer.chrome.com/extensions/cookies#method-set](https://www.google.com/url?q=https://developer.chrome.com/extensions/cookies%23method-set&sa=D&ust=1524780472112000)</span>

<span class="c2"></span>

<span class="c6">[https://hangouts.google.com/call/f71g1SrzihwRublHgFC2AAEE](https://www.google.com/url?q=https://hangouts.google.com/call/f71g1SrzihwRublHgFC2AAEE&sa=D&ust=1524780472112000)</span>

<span class="c2"></span>

# <span class="c16">1\. Mechanics</span>

<span class="c2"></span>

<span class="c2">Mechanics of Chrome extension</span>

<span class="c2"> Base extention: https://github.com/TelegramSam/ConsentCookieManager</span>

<span class="c2"></span>

<span class="c2">Mechanics of encoding</span>

<span class="c2"></span>

<span class="c2">Mechanics of cookie extension.</span>

# <span class="c16">2\. Mapping of purposes for our CMP</span>

<span class="c2"></span>

<span class="c2">Become the only CMP that could be chosen by the uers</span>

# <span class="c16">3\. Move some of this into Kantara Consent Management?</span>

<span class="c2">Registered CMPs</span>

<span class="c2"></span>

<span class="c6">[http://advertisingconsent.eu/iab-europe-transparency-consent-framework-list-of-registered-cmps/](https://www.google.com/url?q=http://advertisingconsent.eu/iab-europe-transparency-consent-framework-list-of-registered-cmps/&sa=D&ust=1524780472114000)</span>

<span class="c2"></span>

<span class="c2"></span>

<a id="t.8a9e5c1da1282d8206083fdaafb3b4db57223d4b"></a><a id="t.0"></a>

<table class="c27">

<tbody>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c5">ID</span>

</td>

<td class="c24" colspan="1" rowspan="1">

<span class="c5">Company Name</span>

</td>

<td class="c13" colspan="1" rowspan="1">

<span class="c5">Website</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">Sub-Domain</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c5">9</span>

</td>

<td class="c24" colspan="1" rowspan="1">

<span class="c5">Admiral</span>

</td>

<td class="c13" colspan="1" rowspan="1">

<span class="c5">getadmiral.com</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">admiral.mgr.consensu.org</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c5">2</span>

</td>

<td class="c24" colspan="1" rowspan="1">

<span class="c5">Chandago</span>

</td>

<td class="c13" colspan="1" rowspan="1">

<span class="c5">chandago.com</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">appconsent.mgr.consensu.org</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c5">23</span>

</td>

<td class="c24" colspan="1" rowspan="1">

<span class="c5">Conversant Europe Ltd.</span>

</td>

<td class="c13" colspan="1" rowspan="1">

<span class="c5">conversantmedia.eu</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">conversant.mgr.consensu.org</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c5">7</span>

</td>

<td class="c24" colspan="1" rowspan="1">

<span class="c5">Didomi</span>

</td>

<td class="c13" colspan="1" rowspan="1">

<span class="c5">didomi.io</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">didomi.mgr.consensu.org</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c5">3</span>

</td>

<td class="c24" colspan="1" rowspan="1">

<span class="c5">Faktor BV</span>

</td>

<td class="c13" colspan="1" rowspan="1">

<span class="c5">faktor.io</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">faktor.mgr.consensu.org</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c5">12</span>

</td>

<td class="c24" colspan="1" rowspan="1">

<span class="c5">Germantag Web Services</span>

</td>

<td class="c13" colspan="1" rowspan="1">

<span class="c5">germantag.de</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">germantag.mgr.consensu.org</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c5">10</span>

</td>

<td class="c24" colspan="1" rowspan="1">

<span class="c5">Quantcast International Limited</span>

</td>

<td class="c13" colspan="1" rowspan="1">

<span class="c5">quantcast.com</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">quantcast.mgr.consensu.org</span>

</td>

</tr>

<tr class="c9">

<td class="c14" colspan="1" rowspan="1">

<span class="c5">6</span>

</td>

<td class="c24" colspan="1" rowspan="1">

<span class="c5">Sourcepoint Technologies, Inc.</span>

</td>

<td class="c13" colspan="1" rowspan="1">

<span class="c5">sourcepoint.com</span>

</td>

<td class="c12" colspan="1" rowspan="1">

<span class="c5">sourcepoint.mgr.consensu.or</span>

</td>

</tr>

</tbody>

</table>

<span class="c2"></span>

# <span class="c16">Icons…</span>

<a id="t.94b3aa30f933eac04833b571afd0694def441148"></a><a id="t.1"></a>

<table class="c27">

<tbody>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c25 c11">Purposes</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c25 c11">IAB E Translates to</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11 c25">Customer Commons Translates to</span>

</td>

<td class="c21" colspan="1" rowspan="1">

<span class="c25 c11">Relevant GDPR Articles</span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c17" colspan="1" rowspan="1">

<span class="c4">Storage and access of information</span>

</td>

<td class="c19" colspan="1" rowspan="1">

<span class="c4">You can ask us to delete/forget when you want</span>

</td>

<td class="c35" colspan="1" rowspan="1">

<span class="c28 c30">Article 18</span>

<span class="c8">Right to restriction of processing</span>

<span class="c8"></span>

<span class="c37">Article 17</span>

<span class="c22">Right to erasure (‘right to be forgotten’)</span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4">Personalisation</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4">Tracking (GDPR: Profiling)</span>

</td>

<td class="c21" colspan="1" rowspan="1">

<span class="c28 c30">Article 21</span>

<span class="c8">Right to object</span>

<span class="c8"></span>

<span class="c28 c30">Article 22</span>

<span class="c22">Automated individual decision-making, including profiling</span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c17" colspan="1" rowspan="1">

<span class="c4">Ad selection, delivery, reporting</span>

</td>

<td class="c19" colspan="1" rowspan="1">

<span class="c4">My topic prefs and exclusions</span>

</td>

<td class="c35" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c34" colspan="1" rowspan="1">

<span class="c4">Content selection, delivery, reporting</span>

</td>

<td class="c31" colspan="1" rowspan="1">

<span class="c4">Where do I see the logs?</span>

</td>

<td class="c33" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4">Measurement (Analytics etc.)</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c11">Only</span> <span class="c11">aggregate</span><span class="c4"> info allowed (at least c. 10 subjects)</span>

</td>

<td class="c21" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c25 c11">Duration?</span>

<span class="c4"></span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c21" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c25 c11">Features</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c21" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c17" colspan="1" rowspan="1">

<span class="c4">Matching Data to Offline Sources</span>

</td>

<td class="c19" colspan="1" rowspan="1">

<span class="c4">If you use my data to correlate me with my offline self, you will notify me</span>

</td>

<td class="c35" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4">Linking Devices</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4">If you link my devices through pivotal data points I supply implicitly or explicitly, you will notify me?</span>

<span class="c4"></span>

</td>

<td class="c21" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c17" colspan="1" rowspan="1">

<span class="c4">Precise Geographic Locations</span>

</td>

<td class="c19" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c35" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c21" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

<tr class="c18">

<td class="c10" colspan="1" rowspan="1">

<span class="c4">Vendors</span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c10" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

<td class="c21" colspan="1" rowspan="1">

<span class="c4"></span>

</td>

</tr>

</tbody>

</table>

* * *

# <span class="c16"></span>

<span class="c2"></span>

<span class="c2"></span>

# <span class="c16">Features</span>

<span class="c25 c26">These are the currently-defined Features from the</span>

<span class="c25 c26"> https://vendorlist.consensu.org/vendorlist.json file</span>

<span class="c2"></span>

<span class="c2">    "features": [</span>

<span class="c2">        {</span>

<span class="c2">            "description": "Combining data from offline sources that were initially collected in other contexts.",</span>

<span class="c2">            "id": 1,</span>

<span class="c2">            "name": "Matching Data to Offline Sources"</span>

<span class="c2">        },</span>

<span class="c2">        {</span>

<span class="c2">            "description": "Allow processing of a user's data to connect such user across multiple devices.",</span>

<span class="c2">            "id": 2,</span>

<span class="c2">            "name": "Linking Devices"</span>

<span class="c2">        },</span>

<span class="c2">        {</span>

<span class="c2">            "description": "Allow processing of a user's precise geographic location data in support of a purpose for which that certain third party has consent.",</span>

<span class="c2">            "id": 3,</span>

<span class="c2">            "name": "Precise Geographic Location Data"</span>

<span class="c2">        }</span>

<span class="c2">    ],</span>

<span class="c2"></span>

* * *

<span class="c2"></span>

# <span class="c16">Purposes</span>

<span class="c25 c26">These are the currently-defined Purposes from the</span>

<span class="c25 c26"> https://vendorlist.consensu.org/vendorlist.json file</span>

<span class="c2">    "purposes": [</span>

<span class="c2">        {</span>

<span class="c2">            "description": "The storage of information, or access to information that is already stored, on your device such as accessing advertising identifiers and/or other device identifiers, and/or using cookies or similar technologies.",</span>

<span class="c2">            "id": 1,</span>

<span class="c2">            "name": "Storage and access of information"</span>

<span class="c2">        },</span>

<span class="c2">        {</span>

<span class="c2">            "description": "The collection and processing of information about your use of this site to subsequently personalize advertising for you in other contexts, i.e. on other sites or apps, over time. Typically, the content of the site or app is used to make inferences about your interests which inform future selections.",</span>

<span class="c2">            "id": 2,</span>

<span class="c2">            "name": "Personalisation"</span>

<span class="c2">        },</span>

<span class="c2">        {</span>

<span class="c2">            "description": "The collection of information, and combination with previously collected information, to select and deliver advertisements for you, and to measure the delivery and effectiveness of such advertisements. This includes using previously collected information about your interests to select ads, processing data about what advertisements were shown, how often they were shown, when and where they were shown, and whether you took any action related to the advertisement, including for example clicking an ad or making a purchase. ",</span>

<span class="c2">            "id": 3,</span>

<span class="c2">            "name": "Ad selection, delivery, reporting"</span>

<span class="c2">        },</span>

<span class="c2">        {</span>

<span class="c2">            "description": "The collection of information, and combination with previously collected information, to select and deliver content for you, and to measure the delivery and effectiveness of such content. This includes using previously collected information about your interests to select content, processing data about what content was shown, how often or how long it was shown, when and where it was shown, and whether the you took any action related to the content, including for example clicking on content. ",</span>

<span class="c2">            "id": 4,</span>

<span class="c2">            "name": "Content selection, delivery, reporting"</span>

<span class="c2">        },</span>

<span class="c2">        {</span>

<span class="c2">            "description": "The collection of information about your use of the content, and combination with previously collected information, used to measure, understand, and report on your usage of the content.",</span>

<span class="c2">            "id": 5,</span>

<span class="c2">            "name": "Measurement"</span>

<span class="c2">        }</span>

<span class="c2">    ],</span>

<span class="c2"></span>

<span class="c2"></span>

<span class="c2">Ad Vendors</span>

<span class="c2"></span>

<span class="c2">{  
 "vendorListVersion": 9,  
 "lastUpdated": "2018-04-26T16:01:58Z",  
 "purposes": [  
   {  
     "id": 1,  
     "name": "Storage and access of information",  
     "description": "The storage of information, or access to information that is already stored, on your device such as accessing advertising identifiers and\/or other device identifiers, and\/or using cookies or similar technologies."  
   },  
   {  
     "id": 2,  
     "name": "Personalisation",  
     "description": "The collection and processing of information about your use of this site to subsequently personalize advertising for you in other contexts, i.e. on other sites or apps, over time. Typically, the content of the site or app is used to make inferences about your interests which inform future selections."  
   },  
   {  
     "id": 3,  
     "name": "Ad selection, delivery, reporting",  
     "description": "The collection of information, and combination with previously collected information, to select and deliver advertisements for you, and to measure the delivery and effectiveness of such advertisements. This includes using previously collected information about your interests to select ads, processing data about what advertisements were shown, how often they were shown, when and where they were shown, and whether you took any action related to the advertisement, including for example clicking an ad or making a purchase. "  
   },  
   {  
     "id": 4,  
     "name": "Content selection, delivery, reporting",  
     "description": "The collection of information, and combination with previously collected information, to select and deliver content for you, and to measure the delivery and effectiveness of such content. This includes using previously collected information about your interests to select content, processing data about what content was shown, how often or how long it was shown, when and where it was shown, and whether the you took any action related to the content, including for example clicking on content. "  
   },  
   {  
     "id": 5,  
     "name": "Measurement",  
     "description": "The collection of information about your use of the content, and combination with previously collected information, used to measure, understand, and report on your usage of the content."  
   }  
 ],  
 "features": [  
   {  
     "id": 1,  
     "name": "Matching Data to Offline Sources",  
     "description": "Combining data from offline sources that were initially collected in other contexts."  
   },  
   {  
     "id": 2,  
     "name": "Linking Devices",  
     "description": "Allow processing of a user's data to connect such user across multiple devices."  
   },  
   {  
     "id": 3,  
     "name": "Precise Geographic Location Data",  
     "description": "Allow processing of a user's precise geographic location data in support of a purpose for which that certain third party has consent."  
   }  
 ],  
 "vendors": [  
   {  
     "id": 8,  
     "name": "Emerse Sverige AB",  
     "policyUrl": "https:\/\/www.emerse.com\/privacy-policy\/",  
     "purposeIds": [  
       1,  
       2,  
       4  
     ],  
     "legIntPurposeIds": [  
       3,  
       5  
     ],  
     "featureIds": [  
       1,  
       2  
     ]  
   },  
   {  
     "id": 12,  
     "name": "BeeswaxIO Corporation",  
     "policyUrl": "https:\/\/www.beeswax.com\/privacy.html",  
     "purposeIds": [  
       1,  
       3,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       3  
     ]  
   },  
   {  
     "id": 28,  
     "name": "TripleLift, Inc.",  
     "policyUrl": "https:\/\/triplelift.com\/privacy\/",  
     "purposeIds": [  
       1,  
       3  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       3  
     ]  
   },  
   {  
     "id": 9,  
     "name": "AdMaxim Inc.",  
     "policyUrl": "http:\/\/www.admaxim.com\/privacy\/",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       1,  
       2,  
       3  
     ]  
   },  
   {  
     "id": 27,  
     "name": "ADventori SAS",  
     "policyUrl": "https:\/\/www.adventori.com\/with-us\/legal-notice\/",  
     "purposeIds": [  
       2  
     ],  
     "legIntPurposeIds": [  
       1,  
       3,  
       4,  
       5  
     ],  
     "featureIds": [  

     ]  
   },  
   {  
     "id": 25,  
     "name": "Oath (EMEA) Limited",  
     "policyUrl": "https:\/\/policies.oath.com\/ie\/en\/oath\/privacy\/index.html",  
     "purposeIds": [  
       1,  
       2  
     ],  
     "legIntPurposeIds": [  
       3,  
       5  
     ],  
     "featureIds": [  
       1,  
       2,  
       3  
     ]  
   },  
   {  
     "id": 26,  
     "name": "Venatus Media Limited",  
     "policyUrl": "https:\/\/www.venatusmedia.com\/privacy\/",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  

     ]  
   },  
   {  
     "id": 1,  
     "name": "Exponential Interactive, Inc",  
     "policyUrl": "http:\/\/exponential.com\/privacy",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  

     ]  
   },  
   {  
     "id": 6,  
     "name": "AdSpirit GmbH",  
     "policyUrl": "http:\/\/www.adspirit.de\/privacy",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  

     ]  
   },  
   {  
     "id": 30,  
     "name": "BidTheatre AB",  
     "policyUrl": "https:\/\/www.bidtheatre.com\/privacy-policy",  
     "purposeIds": [  
       1,  
       2,  
       3  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       2,  
       3  
     ]  
   },  
   {  
     "id": 24,  
     "name": "Conversant Europe Ltd.",  
     "policyUrl": "https:\/\/www.conversantmedia.eu\/legal\/privacy-policy",  
     "purposeIds": [  
       1  
     ],  
     "legIntPurposeIds": [  
       2,  
       3,  
       4,  
       5  
     ],  
     "featureIds": [  
       1,  
       2,  
       3  
     ]  
   },  
   {  
     "id": 29,  
     "name": "Etarget SE",  
     "policyUrl": "https:\/\/www.etarget.sk\/privacy.php",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       1  
     ]  
   },  
   {  
     "id": 39,  
     "name": "ADITION technologies AG",  
     "policyUrl": "adition.com\/datenschutz",  
     "purposeIds": [  

     ],  
     "legIntPurposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "featureIds": [  
       1,  
       2,  
       3  
     ]  
   },  
   {  
     "id": 11,  
     "name": "Quantcast International Limited",  
     "policyUrl": "https:\/\/www.quantcast.com\/privacy\/",  
     "purposeIds": [  
       1  
     ],  
     "legIntPurposeIds": [  
       2,  
       3,  
       4,  
       5  
     ],  
     "featureIds": [  
       1  
     ]  
   },  
   {  
     "id": 15,  
     "name": "Adikteev",  
     "policyUrl": "https:\/\/www.adikteev.com\/eu\/privacy\/",  
     "purposeIds": [  
       1,  
       2  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  

     ]  
   },  
   {  
     "id": 4,  
     "name": "Roq.ad GmbH",  
     "policyUrl": "https:\/\/www.roq.ad\/privacy-policy",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       2,  
       3  
     ]  
   },  
   {  
     "id": 7,  
     "name": "Vibrant Media Limited",  
     "policyUrl": "https:\/\/www.vibrantmedia.com\/en\/privacy-policy\/",  
     "purposeIds": [  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  
       1  
     ],  
     "featureIds": [  

     ]  
   },  
   {  
     "id": 2,  
     "name": "Captify Technologies Limited",  
     "policyUrl": "http:\/\/www.captify.co.uk\/privacy-policy\/",  
     "purposeIds": [  
       2,  
       3,  
       5  
     ],  
     "legIntPurposeIds": [  
       1  
     ],  
     "featureIds": [  
       2  
     ]  
   },  
   {  
     "id": 37,  
     "name": "NEURAL.ONE",  
     "policyUrl": "https:\/\/web.neural.one\/privacy-policy\/",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       1,  
       2  
     ]  
   },  
   {  
     "id": 13,  
     "name": "Sovrn Holdings Inc",  
     "policyUrl": "https:\/\/www.sovrn.com\/sovrn-privacy\/",  
     "purposeIds": [  
       1,  
       2,  
       3  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       2,  
       3  
     ]  
   },  
   {  
     "id": 34,  
     "name": "NEORY GmbH",  
     "policyUrl": "https:\/\/www.neory.com\/privacy.html",  
     "purposeIds": [  
       1,  
       2,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  
       3  
     ],  
     "featureIds": [  

     ]  
   },  
   {  
     "id": 32,  
     "name": "AppNexus Inc.",  
     "policyUrl": "https:\/\/www.appnexus.com\/en\/company\/platform-privacy-policy",  
     "purposeIds": [  
       1  
     ],  
     "legIntPurposeIds": [  
       3  
     ],  
     "featureIds": [  
       2,  
       3  
     ]  
   },  
   {  
     "id": 10,  
     "name": "Index Exchange, Inc. ",  
     "policyUrl": "www.indexexchange.com\/privacy",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       2,  
       3  
     ]  
   },  
   {  
     "id": 57,  
     "name": "ADARA MEDIA UNLIMITED",  
     "policyUrl": "https:\/\/adara.com\/2018\/04\/10\/adara-gdpr-faq\/",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       1,  
       2  
     ]  
   },  
   {  
     "id": 63,  
     "name": "Avocet Systems Limited",  
     "policyUrl": "http:\/\/www.avocet.io\/privacy-policy",  
     "purposeIds": [  

     ],  
     "legIntPurposeIds": [  
       1,  
       3  
     ],  
     "featureIds": [  

     ]  
   },  
   {  
     "id": 51,  
     "name": "xAd, Inc. dba GroundTruth",  
     "policyUrl": "https:\/\/www.groundtruth.com\/privacy-policy\/",  
     "purposeIds": [  
       1,  
       2,  
       3,  
       4,  
       5  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       1,  
       2,  
       3  
     ]  
   },  
   {  
     "id": 49,  
     "name": "Tradelab, SAS",  
     "policyUrl": "http:\/\/tradelab.com\/en\/privacy\/",  
     "purposeIds": [  
       1,  
       2,  
       3  
     ],  
     "legIntPurposeIds": [  
       5  
     ],  
     "featureIds": [  
       1,  
       2,  
       3  
     ]  
   },  
   {  
     "id": 45,  
     "name": "Smart Adserver",  
     "policyUrl": "http:\/\/smartadserver.com\/company\/privacy-policy\/",  
     "purposeIds": [  
       1,  
       2  
     ],  
     "legIntPurposeIds": [  
       3,  
       5  
     ],  
     "featureIds": [  
       3  
     ]  
   },  
   {  
     "id": 52,  
     "name": "The Rubicon Project, Limited",  
     "policyUrl": "http:\/\/rubiconproject.com\/rubicon-project-yield-optimization-privacy-policy\/",  
     "purposeIds": [  
       1  
     ],  
     "legIntPurposeIds": [  
       2,  
       3,  
       4,  
       5  
     ],  
     "featureIds": [  
       3  
     ]  
   },  
   {  
     "id": 35,  
     "name": "Purch Group, Inc.",  
     "policyUrl": "http:\/\/www.purch.com\/privacy-policy\/",  
     "purposeIds": [  
       1  
     ],  
     "legIntPurposeIds": [  
       3,  
       5  
     ],  
     "featureIds": [  

     ]  
   },  
   {  
     "id": 71,  
     "name": "Dataxu, Inc. ",  
     "policyUrl": "https:\/\/www.dataxu.com\/about-us\/privacy\/data-collection-platform\/",  
     "purposeIds": [  
       1,  
       2,  
       3  
     ],  
     "legIntPurposeIds": [  

     ],  
     "featureIds": [  
       1,  
       2,  
       3  
     ]  
   },  
   {  
     "id": 79,  
     "name": "MediaMath, Inc.",  
     "policyUrl": "http:\/\/www.mediamath.com\/privacy-policy\/",  
     "purposeIds": [  
       1  
     ],  
     "legIntPurposeIds": [  
       2,  
       3,  
       4,  
       5  
     ],  
     "featureIds": [  
       1,  
       2,  
       3</span>

<span class="c2"></span>

<span class="c2"></span>

<span class="c2"></span>
