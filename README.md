# mfilterit-visit-pixel

﻿
1\. Introduction to Visit and Event Pixel

    a. Visit Pixel

    b. Event Pixel

        i. What data pixel collects

        ii. How data is collected

        iii. How data is processed

        iv. Insights Obtained

2\. Introduction to Ad fraud Validation

    a. What is Ad Fraud

    b. Types of Ad Fraud

    c. Types of Bots

    d. Best Practices

3\. How to implement Visit and Event Pixel via GTM

4\. How To import mFilterIt Template in GTM.



                                    **Introduction to Visit and Event Pixel**

Advertisers use different incentives for acquiring users to their business, and acquiring new users is typically an expensive activity. But the cost of acquiring a user is typically set off as the user generates business over his lifecycle, allowing addition to a loyal and engaged user base.



One important step to this journey, is acquiring users inorganically using platforms like Google Ads, LinkedIn Ads, Meta Ads, etc. However, ensuring that only genuine and unique users get acquired is a big challenge. In the mobile app, the device Id based solutions allow a fairly easier approach to detect uniqueness among new users. However, in the browser world (desktop or mobile web), identifying whether a user is unique or not is difficult and easily adaptable by users who are interested in taking advantage.



Mfilterit provides an easy, JavaScript based solution, which gets embedded on the landing page as a simple pixel, which can be integrated via tag management tools like Google Tag Manager Adobe Launch, etc. or can be directly placed on the header of the source code of webpage, being used as a landing page or thank you page in the user journey. It detects new and unique users who are coming and registering using the browser.



Key benefits of using MfilterIt tool:

1.  It does not depend on the cookie to identify uniqueness of users. This is important since cookies are easily cleaned by users or even blocked by the Incognito mode in browsers. And as the world is moving towards a cookie less environment, mfilterit pixels plays a vital role in identifying and differentiating a genuine user from a bot traffic.

2.  Works even in Incognito Mode: Since browsers block all cookies in the Incognito mode,allowing detection in this mode is important to prevent misuse by spooked visitor or bots.
   
   

Frictionless experience: Critical criteria of the solution is to prevent addition of friction or onus on users to identify themselves, since it adds to dropout rates and failure rates, the solution works in the background without exposing users to any extra actions



**Visit Pixel**

Visit pixel is a JavaScript which is placed on the landing pages of campaigns with the help of a tag management tool like google tag manager or can also be directly placed on the website code. Once placed on the landing page, the pixel is set to trigger for all incoming campaigns traffic and send the required set of data from the user system to mfilterit servers.

**Event Pixel**

Event pixel is similar to visit pixel, being it a JavaScript, which is placed on the thank you page of the advertisers, which marks the completion of a successful sale or a lead. It too, sends the similar set of information as the visit pixel of landing pages, to the mfilterit servers.



• **What data pixel collects:** Pixel sends multiple non-PII data sets from the user browser to mfilterit servers, which may include information like user browser, user cookie, user, device, etc.

• **How data is collected:** Data received from user device/browser is stored on mfilterit servers to go through the predefined set of rules, in order to filter between genuine user and invalid traffic.

• **How data is processed:** Data stored on mfilterit server is then processed and go through multiple rule checks to identify and filter incoming campaign traffic between a human user and a bot device.

• **Insights Obtained:** Once data is processed on mfilterit servers, insights are obtained from it as per the client's requirement and directly shared with the client via a web dashboard.



                                        **Introduction to Ad fraud Validation**

**What is Ad Fraud?**

Ad traffic fraud refers to the practice of artificially inflating or manipulating the number of ad impressions, clicks, conversions, or other engagement metrics to deceive advertisers and profit from their advertising budgets. It is a form of digital ad fraud and can occur through various fraudulent techniques employed by unscrupulous individuals or organizations.



Ad traffic fraud can be detrimental to advertisers, as it wastes their advertising budgets, reduces the effectiveness of their campaigns, and erodes trust in digital advertising. To combat ad traffic fraud, advertisers and ad platforms employ various fraud detection tools and best practices to identify and prevent fraudulent activities.



**Types of Ad Fraud**



Some common types of ad traffic fraud include:



**Click Fraud**: In this scheme, bots or automated scripts simulate clicks on ads without any genuine interest from real users. The purpose is to drain the advertiser's budget and exhaust their ad spend without providing any meaningful value or potential customers.



**Impression Fraud**: Fraudsters use bots to generate fake impressions on ads, making it seem like the ad is being seen by a large audience when it's not. This can artificially inflate the ad's perceived reach and effectiveness.



**Conversion Fraud**: Advertisers often measure the success of their campaigns based on the number of conversions (e.g., sign-ups, purchases, downloads). Fraudsters can manipulate these numbers using automated bots or fake accounts to create false conversions, leading advertisers to believe their campaign is performing better than it actually is.



**Domain Spoofing**: In this method, fraudsters misrepresent the source of ad placements by disguising their low-quality websites as reputable and high-traffic platforms. This tricks advertisers into paying for ad space on sites with little to no actual engagement.



**Ad Stacking**: Ad stacking involves placing multiple ads on top of each other within the same ad placement. While only the top ad is visible to users, all ads are counted as impressions, even if they were not seen. This results in advertisers paying for impressions that weren't actually seen by real users.



**Invisible or Low-Visibility Ads**: Some fraudsters hide ads on web pages, either by using tiny ad placements that are not visible to users or by placing ads behind other elements on the page. These invisible or low-visibility ads generate fraudulent impressions without users ever seeing the ad.



**Types of Bots**



Bots are software applications designed to automate tasks and perform specific functions. While some bots are legitimate and serve useful purposes, others are created for malicious or deceptive purposes. Here are some common types of bots:


Web Crawlers/Spiders: These bots are used by search engines like Google to index and catalogue web pages. They browse the internet, following links, and gathering data to create searchable indexes.


Social Media Bots: These bots are programmed to interact with social media platforms, automatically posting, liking, sharing, or following users based on specific criteria. Some social media bots are legitimate tools for social media management, while others are used for spamming or engagement manipulation. 



Scrapers: Scraping bots are used to extract data from websites on a large scale. They can be legitimate tools for data analysis, but they can also be used for unauthorized data harvesting and content theft.



Click bots: Click bots simulate human clicks on web pages, advertisements, or affiliate links, with the purpose of generating fraudulent ad revenue or artificially inflating website traffic.



Ticket Bots: These bots are used in the ticketing industry to automate the purchase of tickets for concerts, sports events, and other entertainment shows. They often enable ticket scalpers to buy tickets in bulk, leading to shortages and inflated prices.



Spam Bots: Spam bots flood email inboxes, comment sections, and social media platforms with unsolicited and often irrelevant messages, links, or advertisements.



AI Bots: AI-powered bots can perform various tasks, such as natural language processing, image recognition, or data analysis, often used in business and research applications.



SIVT (Sophisticated Invalid Traffic) and GIVT (General Invalid Traffic) are two categories used to classify types of invalid traffic in digital advertising. Both SIVT and GIVT represent different types of fraudulent or non-genuine activities that can affect ad campaigns and analytics. Let's explore each category:



1. SIVT (Sophisticated Invalid Traffic): SIVT refers to invalid traffic that is generated through more sophisticated and advanced methods, often designed to evade detection and mimic human behaviour. This category includes various complex and deceptive techniques employed by fraudsters. Some examples of SIVT include:

• Bots that mimic human behaviour to interact with ads or simulate genuine user engagement.

• Click injection or click flooding, where malicious apps or software insert fake clicks into legitimate user interactions.

• Cookie stuffing, where websites or ads unknowingly place cookies on users' devices without their consent to claim undeserved attribution.

• Ad stacking, as mentioned earlier, involves stacking multiple ads on top of each other, leading to multiple impressions for a single view.

• Domain spoofing, where the actual source of an ad impression is misrepresented to appear to come from a reputable website.



SIVT is more challenging to detect and requires sophisticated anti-fraud measures to combat effectively.



2\. GIVT (General Invalid Traffic): GIVT refers to invalid traffic that is more easily identifiable as non-human or non-legitimate without the need for advanced analysis. These types of traffic are usually obvious and do not attempt to hide their fraudulent nature. Some examples of GIVT include:



• Bots that exhibit easily detectable patterns and characteristics, making them distinguishable from genuine human users.

• Crawlers and spiders used by search engines for indexing, which may trigger ad impressions without any real human intent.

• Known data centers and IP addresses that are associated with non-human traffic. 



GIVT is generally easier to detect using standard traffic quality measurement tools and methodologies.



Advertisers and ad platforms use SIVT and GIVT classifications to understand the quality of their ad traffic and take appropriate actions to mitigate the impact of fraudulent activities. By filtering out invalid traffic, advertisers can ensure that their ad campaigns are reaching real, engaged audiences, and they are not wasting their advertising budget on non-human interactions. Various industry initiatives and technologies have been developed to combat both SIVT and GIVT to maintain a healthy and trustworthy digital advertising ecosystem.



**Best Practices**

To tackle SIVT (Sophisticated Invalid Traffic) and GIVT (General Invalid Traffic) in digital advertising, it's essential to implement a multi-layered approach that combines various best practices and technologies. Here are some effective strategies to combat ad fraud and maintain a healthy ad ecosystem:



1\. Choose Reputable Partners: Work with reputable and trusted ad networks, publishers, and platforms that have a proven track record of implementing anti-fraud measures. Conduct due diligence before partnering with any new entities in the digital advertising space.



2\. Implement Fraud Detection Tools: Invest in advanced fraud detection and prevention tools that can identify suspicious traffic patterns, abnormal behaviour, and characteristics associated with bots and fraudulent activities. These tools should cover both SIVT and GIVT detection.



3\. Set Quality Standards: Define clear and strict guidelines for traffic quality and ensure your partners adhere to these standards. Establish key performance indicators (KPIs) that help you assess the legitimacy of the traffic and optimize your campaigns accordingly.



4\. Use Verification Services: Consider using third-party verification services that can independently audit and verify your ad traffic to ensure compliance with industry standards and detect any fraudulent activities.



5\. Monitor and Analyse Traffic: Continuously monitor your ad traffic and analyse data to identify anomalies and patterns that may indicate fraudulent activities. Regularly review your analytics and traffic reports to spot any suspicious trends.



6\. Employ Bot Filtering: Implement bot filtering techniques and solutions that can block or minimize bot traffic from interacting with your ads. These filtering mechanisms can be applied at the server level or through third-party services.



7\. Employ CAPTCHAs and Security Measures: Use CAPTCHAs or other security measures on your websites or apps to prevent bot access and interactions. These measures can help distinguish between human and bot traffic.



8\. Verify Ad Placements: Ensure your ads are displayed on legitimate and verified websites. Use ad verification tools to verify ad placements and detect any instances of domain spoofing.



9\. Monitor Conversion Quality: Keep an eye on your conversions and their sources. High conversion rates from suspicious sources could indicate fraudulent activities.



10\. Educate Your Team: Educate your marketing and advertising teams about ad fraud, its impact, and the best practices to combat it. Awareness is crucial to prevent unintentional engagement with fraudulent traffic.



11\. Stay Updated on Industry Trends: Keep abreast of the latest developments in ad fraud and the techniques used by fraudsters. Stay informed about new fraud patterns and continuously evolve your anti-fraud strategies.



Remember that no single approach can completely eliminate ad fraud, but combining

multiple measures and staying vigilant can significantly reduce its impact and protect your advertising investments. Collaboration within the industry, along with the implementation of industry standards, is also crucial to tackle ad fraud effectively.



**How to implement Visit and Event Pixel via GTM**

Visit and Event pixel can be placed with the help of google tag manager on the respective pages of the website.



Here is a sample visit pixel for your understanding.



```
<script>
 (function (m, f, i, l, t, e, r) { 
 m[t] = m[t] || function () {(m[t].q = m[t].q || []).push(arguments)}, m[t].l = 1 * new Date();
 e = f.createElement(l); e.async = 1; e.id = "mfilterit-visit-tag"; e.src = i;
 r = f.getElementsByTagName(l)[0]; r.parentNode.insertBefore(e, r);
 })(window, document, "https://script.mfilterit.net/v3/v/client/web.sample.cpv.js", "script", "mf");

 mf("mf_package_name", "web.sample.cpv");
 mf("mf_tracking_type", "pageviews");
 </script>
```



Now to place this on the landing page please follow the below steps:



1\. Click on "Add a new tag" option on the GTM interface.

2\. In tag configuration, select "Custom HTML" from "Choose tag type".

3\. Copy and paste mFilterIt code in the box. Replace required codes as per document.

4\. Choose "Page views" from "choose a trigger" option in "Triggering" or modify trigger as per your requirement.

5\. Finally Save and Publish the created tags and triggers in the GTM container.



**How To import mFilterIt Template in GTM**

Follow the below instructions to import mfilterit visit and event pixel template into GTM container.



1\. Go to templates from the left menu on the GTM interface.

2\. Click on “Search Gallery” from the Tag Templates.

3\. In Import Tag Template window, search for mFilterIt visit or event pixel.

4\. Choose the respective mfilterit pixel and click on “Add to workspace”.

5\. Once added to the account use the template to create the respective mfilterit pixel tags.
