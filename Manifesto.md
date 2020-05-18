# ProvideSG

## Problem Statement
Today, people in need do not always know who to call. Generally, they reach out to Family Service Centres (FSCs), who then do one of the following:

1. Refer them to the appropriate agency
2. Render direct help

However, there are tradeoffs to operating with a model where FSCs serve as central referrers to social services (where they are not the appropriate agency to render such services). Directing people to the right agency depends on (1) resources like manpower, money, and time, and (2) knowledge of the social services available.

First, referrals take up resources. Social workers need to spend time analysing a client's needs before identifying the appropriate agency to deal with their request. Thereafter, they need to perform a handover to the appropriate agency, taking up resources from that agency. Reducing the load from referrals could enable social workers to focus on the core work of rendering services.

Second, referrals require social workers to be conversant with social services across Singapore. As the central referrers of social services, they receive calls from clients outside their service boundary, and must still make the best referrals possible. In fact, it is a challenge to be conversant with the growing list of social services even within their service boundaries.

**There is an opportunity to reduce the resources required for referrals, while potentially improving the quality of referrals through technology.**

## Assumptions
* People know what they need
* What people are asking for is what they really want
* People are able to clearly articulate what they need

## Mission
To help people by connecting them to the social services they need.

## Value Proposition
There are several groups that ProvideSG serves:

1. Tech savvy people in need
2. Social workers
3. Organisations and people who want to give

### Tech-Savvy People in Need
By tech savvy, we mean people who are able to use the internet on their mobile phones to search for things. While there is a decreasing number of people who are *not* tech savvy, we still make this distinction to recognise that different segments within the community have different ways of seeking help.

ProvideSG helps tech-savvy people in need **directly** by enabling them to search for services that meet their needs. Some people don't know who to approach for their issue, and need that first number to call. Some people are willing and able to help themselves, and simply need direction to the relevant agency. Some people don't want to go to intermediaries for various reasons, and would prefer to go straight to the appropriate authority. No matter their orientation, giving people the best first contact is efficient for them and the organisations that will serve them.

For the non-tech savvy, ProvideSG helps in **indirect ways**. We elaborate on these in the sub-sections below.

### Social Workers
While social workers may be familiar with the resources within their respective service boundaries, there is a vast and expanding range of social services across Singapore that they may not know about. It is challenging to maintain a (1) full and (2) updated directory of services. ProvideSG takes this burden off social workers' shoulders, providing them with quick access to an updated directory of services to (a) better advise their clients on the agencies they should approach for help, and more importantly, (b) to focus on the core work of rendering social services.

### Donors
If it is challenging even for social workers to maintain a list of social services available across the island, it must also be the case for organisations and people to find the right social work organisations to donate to - organisations that need help, and that also have a profile that donors are interested in. 

## The Need for ProvideSG
In this section, we explain why the existing options are not suitable.

### Available Tools
The tools available for helping people find the services they need are not sufficiently intuitive and efficient. There is one - the [NCSS Navigator](https://www.ncss.gov.sg/navigator) - that contains a comprehensive list of programmes, schemes, and policies. However, the form in which it is delivered is not user-friendly. It wasn't a positive experience using the app, and we can't possibly blame social workers for not using it. Here's why.

First, it is slow. It starts with the assumption that its users (primarily social workers) want **all information**. Hence, the application, a Tableau dashboard, loads the entire database, and requires social workers to filter the services according to their needs. The (1) size of the data transferred, and (2) mechanics behind Tableau dashboards result in a laggy application.

Second, it is not built for mobile use, despite the fact that users are increasingly accessing web apps from their mobiles. On mobile devices, the dashboard is reduced to four filters for programmes (Target Group, Programme Type, Area, and Programme Info), and an accompanying map. Still, it is laggy **even when emulated on Google Chrome on a desktop**. This is because it loads a whole chunk of data in a 4.5 MB text file. As you progressively filter programmes, the amount of data transferred decreases, and the app becomes faster. But, to reach that stage, users need to deal with the initial lag in response from the app when changing the filters. By then, users would have jumped over to Google.

### Google Search
Google is the next best option. Social workers should know what search terms to include to get the results they need. However, Google may not be as useful for non-social workers because it provides generic results that don't take into account Singaporean's unique context. It is highly dependent on organisations configuring their websites to help Google identify them as the best resource available. For example, search "My mother injured my father. Who do I call?", a pretty Singaporean way of describing family violence. Google's top hits are book previews. The user would then have to generalise their query to "family violence" or "family abuse". We cannot all users to do that.