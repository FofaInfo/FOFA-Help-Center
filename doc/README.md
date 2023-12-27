# Basic Questions

## What is FOFA?

FOFA is a search engine for global cyberspace mapping belonging to Beijing Huashun Xin’an Technology Co., Ltd.

Through continuous active detection of global Internet assets, more than 10 billion assets and more than 350,000 fingerprint rules have been accumulated, identifying most software and hardware network assets. Asset data supports external presentation and application in various ways and can perform hierarchical portraits of assets based on IP.

## Membership Questions

As a FOFA subscription member, you will receive a large amount of free quota every month during the subscription period, and enjoy stable and rich API interfaces.

Currently, FOFA subscription members are divided into personal edition, professional edition, and business edition. You can choose to purchase by month or by year, and annual members can also enjoy exclusive discounts.
[Click here for more details](https://en.fofa.info/vip).

In addition to online direct payment, public transfer is supported. If you need to transfer to the public, please contact our official staff through email: service@baimaohui.net for operation.

## What is an F point?

F-point is a virtual point launched by FOFA. Every 1 F-point is equivalent to 1 piece of data and is mainly used for downloading data. When the member's rights and interests quota is exhausted, F-points can be used for replenishment. In addition, if you want to try features that are not currently at your membership level, you can also achieve this by consuming F-points.

F points are more suitable for environments where a large amount of data needs to be exported at one time and product trials, otherwise we recommend you to purchase subscription members.


## When can FOFA be used?

**External Attack Surface Management (EASM):** Search and identify publicly visible assets of an enterprise, analyze and assess the security risks of assets, mine the correlation between assets, and assist in vulnerability management and emergency response.

**Asset Discovery:** Asset discovery and identification, asset classification and categorization, asset correlation and dependency analysis, asset security assessment and risk management.

**Illegal/malicious website crackdown:** Interference data identification, malicious website correlation identification, threat intelligence analysis, etc.

**Security Situation Awareness:** Real-time asset monitoring, vulnerability and threat monitoring, security event response.



## What are the advantages of FOFA?

FOFA uses its independently developed high-performance distributed architecture and a huge accumulation of metadata. Currently, the total number of assets that can be queried exceeds 10 billion, the monthly update of asset quantity is more than 1 billion, and it supports the detection and identification of more than 1300 protocols.

FOFA's asset rule fingerprint library has been maintained for many years, currently has more than 350,000 rule fingerprints, including 13 major categories and 150 subcategories, covering a wide range of fields and industries.

FOFA has its own intellectual property rights of the Feature engine. This engine algorithm can aggregate websites with similar features, and can solve the needs of unknown asset discovery and automatic website clustering.



# Beginner's Guide

## First Understand FOFA

If you are a newcomer to the network security industry and have come into contact with FOFA for the first time, we recommend that you read our introductory article [Beginner's Guide](https://github.com/FofaInfo/Awesome-FOFA/blob/db4a6a3d6eaeca4fe7fabf3d3c6f743a2bdd5ff2/Get%20Started%20with%20FOFA/A%20Beginner%E2%80%98s%20Guide.md) for your understanding.

## Query Syntax

We have divided the syntax types into several major categories: **General, Special Label, Website, None website, certificate, Last update time, Location** and **unique IP syntax**.

Detailed syntax parsing can be seen in the "[Query Description](https://en.fofa.info/)" button on the homepage.

## How to use FOFA's rules?

We have combined and sorted the multiple key features of these assets to form a set of rule fingerprints.

To put it simply, we have made a navigation page for a lot of data, or it can be understood as the table of contents of a book. It can help users find the information they need more quickly and accurately.

The usage of rules includes:


1. Directly enter keywords in the search box and view through associated rule recommendations;
2. Directly search for keywords, if there are associated rules, they will be displayed in the search result box;
3. View in the [Rule List](https://en.fofa.info/library) page.

## Use of API

FOFA currently opens API interfaces including **Query Interface, Search After Interface, Statistical Aggregation Interface, HOST aggregation Interface, and Account Information Interface** 5 kinds of API call interfaces, which meet the needs of users to call data and secondary development through API as much as possible.

Details can be viewed at [API Documentation](https://en.fofa.info/api).

## What is Fuzzy Search?

Fuzzy search is a search technique used to find results similar to the query word or keyword in the data set.

On FOFA, fuzzy search is achieved by adding the wildcard * or ? after *=, but *= is not a wildcard, it is just a symbol used to indicate the use of the fuzzy search function. At the same time, the wildcards * and ? represent different meanings:

* represents an unlimited number of matches, which can be used to replace 0, 1 or more characters;

? can only replace 1 character.

Note: The syntax that supports fuzzy search has been marked in the query syntax reference, and you can check it. For more information about fuzzy search, you can check out the article [《The Correct Way to Use FOFA's Fuzzy Search》](https://github.com/FofaInfo/Awesome-FOFA/blob/db4a6a3d6eaeca4fe7fabf3d3c6f743a2bdd5ff2/Basic%20scenario/The%20correct%20way%20to%20use%20Fuzzy%20Search%20in%20FOFA.md).

## What is the Open Lab?

The Open Lab is the front station for FOFA to explore data, and you can see it on the personal center page. The functions currently open in the Open Lab include:

Cloud Source IP : Find the source IP of CDN or Cloud WAF, such as: Clouddlare, StackPath, etc.

Attack Surface Inventory: A visual and simplified mode of supply surface inventory, detailed articles can be viewed [《Asset Inventory from a God's Perspective》](https://github.com/FofaInfo/Awesome-FOFA/blob/db4a6a3d6eaeca4fe7fabf3d3c6f743a2bdd5ff2/Basic%20scenario/Asset%20Inventory%20from%20a%20God%E2%80%98s%20Perspective.md)

Fofahub: An intelligent data post station, FofaHub provides comprehensive data integration, processing and visualization functions, provides you with one-stop data services, can easily integrate, analyze and apply data, and make business decisions more efficiently. Detailed articles can be viewed [《Unleash the Power of Workflow: Unleash Your Creativity in Open Site Discovery》](https://github.com/FofaInfo/Awesome-FOFA/blob/db4a6a3d6eaeca4fe7fabf3d3c6f743a2bdd5ff2/Basic%20scenario/Unleash%20the%20Power%20of%20Workflow-%20Unleash%20Your%20Creativity%20in%20Open%20Site%20Discovery.md)

## How to use Favicon syntax?

Usage ①: When there is a Favicon file, upload the icon file in the search box on the homepage for searching;

Usage ②: When the icon_hash is known, use the icon_hash="" syntax to search directly;

Usage ③: The search results page will display the current result icon aggregation, and if there is an icon for a single piece of data, it will also be displayed, click to search.

## What is the Asset Reward Plan?

The Data Reward Plan is a special service launched by FOFA. When the data queried is not found in FOFA, you can submit the data in the format of IP+PORT through this function. FOFA will quickly include the data, and after successful inclusion, it will issue F points to you. More details can be found in [《How to Get Free F-point from FOFA?》](https://github.com/FofaInfo/Awesome-FOFA/blob/db4a6a3d6eaeca4fe7fabf3d3c6f743a2bdd5ff2/Get%20Started%20with%20FOFA/How%20to%20Get%20Free%20F-point%20from%20FOFA%3F.md).


## Where can I see FOFA technology articles?

You can follow our official [meidum](https://medium.com/@fofabot) channel or [github](https://github.com/FofaInfo/Awesome-FOFA) to view the latest FOFA technical article sharing.

Recent technical article sharing:

[Practical FOFA Asset Expansion: Unmasking the Trail of the 'Silver Fox' APT](https://github.com/FofaInfo/Awesome-FOFA/blob/5e54a179c7203cadc1e950e4e8f679caed5f9dee/Basic%20scenario/Practical%20FOFA%20Asset%20Expansion-%20Unmasking%20the%20Trail%20of%20the%20'Silver%20Fox'%20APT.md)

[Conducting APT Bitter Tracking Operation Using FOFA](https://github.com/FofaInfo/Awesome-FOFA/blob/159a94ef0098db6fa5093f8cefff4d133f25ed8c/Basic%20scenario/Conducting%20APT%20Bitter%20Tracking%20Operation%20Using%20FOFA.md)


[Analysis and Tracing of the ObserverStealer](https://github.com/FofaInfo/Awesome-FOFA/blob/1c416977d7f4dc2dd9d6d7a13e15c3dea7bfa60a/Basic%20scenario/Analysis%20and%20Tracing%20of%20the%20ObserverStealer.md)


# Usage Issues

## Same IP data repeated

FOFA's assets are unitized by IP and port, not by IP. Therefore, there are data with the same IP but different ports.

## Same IP, same port data repeated

Port data is divided into protocol data and website data, which can be distinguished by syntax.

Because multiple hosts (hostnames) are bound to an IP, and the content of each host is not exactly the same. It is distinguished based on different return information based on the protocol.

| Data Classification  | Difference  |
|:----------|:----------|
| Protocol data type="service"    | All protocols are called services, and http/https protocols do not include html source code   |
| Website data type="subdomain"    | http/https packet capture, includes html source code and other fields are parsed   |


## Can you recognize the version of the component?

If the version feature exists in the publicly exposed information, it can be recognized.

## If I want to exclude some features, how should I search?

For example, to exclude port 80, the syntax is port!="80", the syntax that supports feature exclusion can refer to the query syntax list.


## Double quotation marks can't find results?

Please use English quotation marks.

## What is the time on FOFA?

The time marked on FOFA is the last time FOFA updated the asset itself. Every scan of the platform will overwrite the history data of the asset. If the last update time has not changed for a long time, it is likely that the asset has been closed.


## Can search IP, but can't search the content in Body?

In English, . :// \_etc. are not segmented, search the whole to find, search a part can not find.

## What is the difference between using = and ==?

Single equals sign = search is a relationship of containment, double equals sign == search is a relationship of absolute equality.


## How to check my own remaining query data?

Check in the member rights and interests at the bottom left of the personal center.


## Why doesn't my personal center-download record have a download address?

According to the current membership identity restrictions, the longest download address save time is 30 days, please download your results as soon as possible.


# Other Questions


## How to get 1-on-1 technical support?

Contact our official staff through email service@baimaohui.net.


## How to change the email?

Email is the only identifier for logging into FOFA and cannot be changed.


## If I don't want my device to be included by FOFA, what should I do?

Don't put the device on the public network.

## Visit "403forbidden"?

The request is too frequent or the number of times is too many, the IP is permanently banned. Contact FofaBot via WeChat to unblock it.

## Why does FOFA show network error when I visit?

Generally, this situation is caused by your browser plugin causing privilege escalation, please turn off the plugin or visit with incognito mode.

## Why does it report a 500 error when I turn the page?

Generally, this situation is caused by your scanner or scanning plugin making malicious requests to FOFA and being intercepted by the firewall. Please turn off your scanner to use it normally.

## Under what circumstances will the FOFA account be permanently banned?

According to the "FOFA User Service Agreement", FOFA accounts do not support multi-person shared use. If your account is shared by multiple people or authorized illegally, it will be permanently banned.
