---
title: Privacy and consent in Adobe Campaign Standard
description: This section provides an overview of privacy, personal data and consent management in Adobe Campaign Standard, as well as the tools available to handle these.
page-status-flag: never-activated
uuid: ed9e631c-5ad1-49f1-be1e-b710bc64dc91
contentOwner: sauviat
products: SG_CAMPAIGN/STANDARD
audience: start
content-type: reference
topic-tags: discovering-the-interface
discoiquuid: 5227ca05-3856-4e54-aec6-14444d6534e3

feature: Privacy
role: User
level: Intermediate
exl-id: 0fc71c2f-f294-43f7-825c-73ab4d43fcf7
---
# Privacy and Consent{#privacy-and-consent}

## General recommendations {#general-recommendations}

Adobe Campaign is a powerful tool for collecting and processing extremely large amounts of data, including personal information and sensitive data. This is why privacy needs to be managed carefully.

* Always make responsible and ethical use of personal information.

* Refrain from sending unsolicited email, push notifications and SMS messages ("spam"). Adobe strongly believes in the principles of permission marketing in fostering customer lifetime value and loyalty, and therefore strictly forbids the use of Adobe Campaign in sending unsolicited messages.

### Privacy regulations {#privacy-regulations}

To correctly handle privacy and manage personal data, work within the legislations applicable to the region(s) where you operate. These regulations include:
* [GDPR](https://ec.europa.eu/info/law/law-topic/data-protection/reform/what-does-general-data-protection-regulation-gdpr-govern_en) (European General Data Protection Regulation)
* [DPA](https://www.gov.uk/data-protection) (UK’s implementation of GDPR)
* [European Directive on privacy and electronic communications](https://eur-lex.europa.eu/legal-content/EN/TXT/?uri=CELEX:02002L0058-20091219)
* [CAN-SPAM Act](https://www.ftc.gov/tips-advice/business-center/guidance/can-spam-act-compliance-guide-business) (US law setting the rules and requirements for commercial email)
* [CCPA](https://leginfo.legislature.ca.gov/faces/codes_displayText.xhtml?lawCode=CIV&division=3.&title=1.81.5.&part=4.&chapter=&article=) (California Consumer Privacy Act)
* [PDPA](https://secureprivacy.ai/thailand-pdpa-summary-what-businesses-need-to-know/) (Thailand Personal Data Protection Act)

>[!NOTE]
>
>For more on how GDPR, CCPA, and PDPA apply to Adobe Campaign, see [this page](../../start/using/privacy-management.md#privacy-management-regulations).

### Adobe Experience Cloud privacy {#experience-cloud-privacy}

Adobe Campaign is part of the Adobe Experience Cloud solutions. The way privacy is handled in Campaign obeys the Adobe Experience Cloud general principles, such as the following:

* **What information is collected when using Adobe Experience Cloud**

    As a company using Adobe Experience Cloud solutions, you choose what information to collect and send to your Adobe Experience Cloud account. Examples of the types of information that may be collected include web browsing activity, IP addresses, location information from mobile devices, campaign success rates, items purchased or placed in shopping cart, etc.

    >[!NOTE]
    >
    >As for all Adobe products, Campaign collects information about app and website users. For more on this, see the [Adobe Privacy Policy](https://www.adobe.com/privacy/policy.html).

* **How Adobe Experience Cloud is used to collect information**

    * Adobe Experience Cloud solutions use cookies and similar technologies, such as web beacons (also known as tags or pixels), to enable you to collect information. For more on cookies and tracking capabilities with Adobe Campaign, see [this section](#tracking-capabilities).
    * You may also use Adobe Experience Cloud technologies within your mobile apps. For more on sending mobile deliveries with Campaign, see [this page](../../channels/using/mobile-guide.md).

* **You users' privacy choices about your use of Adobe Experience Cloud**

    Adobe asks you to provide your customers privacy policies describing:

    * Your privacy practices in connection with Adobe Experience Cloud
    * How users can set their preferences for the collection or use of their information in connection with Adobe Experience Cloud

    >[!NOTE]
    >
    >As for all Adobe products, Campaign users can opt-out sharing information collected about them through apps and websites. For more on this, see the [Adobe Experience Cloud Usage Information FAQ](https://www.adobe.com/privacy/experience-cloud-usage-info-faq.html).

For further details on the Adobe Experience Cloud privacy, see [this page](https://www.adobe.com/privacy/marketing-cloud.html).

## Personal Data and Personas {#personal-data}

When managing Privacy, it is important to define what data should be handled with care and by whom.
* **Personal Data** is information that can directly or indirectly identify a living individual.
* **Sensitive Personal Data** is information related to an individual’s race, political views, religious beliefs, criminal background, genetic information, health data, sexual preference, biometric information, as well as trade union membership.

The [main legislations](#privacy-regulations) refer to the different entities that manage data as follows:
* A **Data Controller** is the authority that determines the means and purpose of collecting, using, and sharing personal data.
* A **Data Processor** is any individual or party that collects, uses, or shares personal data as directed by the Data Controller.
* A **Data Subject** is any living individual whose personal data is being collected, used or shared, and who can be identified, directly or indirectly, by reference to that personal data.

Therefore, as a company collecting and sharing personal data, you are the Data Controller, your clients are the Data Subjects and Adobe Campaign acts as a Data Processor when handling their personal data as directed by you. Note that it is your responsibility as a Data Controller to handle the relationship with the Data Subjects such as when managing [privacy requests](#privacy-requests).

When integrating Campaign with other Experience Cloud solutions where audiences can be transferred from one system to another, such as the [Audience Destinations service](../../integrating/using/aep-about-audience-destinations-service.md), [Adobe Analytics](../../integrating/using/about-campaign-analytics-integration.md), [Audience Manager or People core service](../../integrating/using/sharing-audiences-with-audience-manager-or-people-core-service.md), or with other solutions such as [Microsoft Dynamics 365](../../integrating/using/d365-acs-get-started.md), you need to pay extra care to personal data protection.

## Data acquisition {#data-acquisition}

Adobe Campaign enables you to collect data, including personal and sensitive information. It is therefore essential that you receive and monitor consent from your recipients.

* Always have recipients agree to receive communications. To do this, keep honoring opt-out requests as quickly as possible and verify consent through a double opt-in process. For more on this, see [Managing opt-in and opt-out in Campaign](../../audiences/using/managing-opt-in-and-opt-out-in-campaign.md) and [Setting up a double opt-in process](../../channels/using/setting-up-a-double-opt-in-process.md).
* Do not import fraudulent lists and use traps to check that your client file is not being used fraudulently. For more on this, see [Using traps](../../sending/using/using-traps.md).
* Through consent and rights management, you can track your recipients' preferences as well as manage who within your organization can access which data. For more on this, see [this section](#consent).
* Facilitate and manage Privacy requests from your recipients. For more on this, see [this section](#privacy-requests).

## Privacy management {#privacy-management}

Privacy management refer to all the processes and tools that can help you comply with Privacy regulations (GDPR, CCPA, etc.). Get an overview of what privacy management is on [this page](../../start/using/privacy-management.md#privacy-management-regulations).

Adobe Campaign provides you with various sets of features dedicated to privacy management:
* Consent management, data Retention and user Roles. See [this section](#consent).
* Privacy requests (Right to Access and Right to be Forgotten). See [this section](#privacy-requests).
* Opt-out for the Sale of Personal Information (CCPA-specific). See [this section](../../start/using/privacy-requests.md#sale-of-personal-information-ccpa).

The main Privacy capabilities in Campaign and an example of the personas involved are presented in [this section](#personal-data).


### Consent, Retention and Roles {#consent}

Originally, Adobe Campaign offers important features that are essential to Privacy:

* **Consent management**: Through the subscription management process, you can manage your recipients' preferences and track which recipients have opted-in to which type of subscriptions. For more on this, see [Subscriptions](../../audiences/using/about-subscriptions.md) and [Landing pages](../../channels/using/getting-started-with-landing-pages.md).
* **Data retention**: All built-in standard log tables have pre-set retention periods, generally limiting their data storage to 6 months or less. Additional retention periods can be set up with workflows. For more on this, reach out to the Adobe consultants or technical administrators.
* **Rights management**: Adobe Campaign provides you with the ability to manage the rights assigned to the various Campaign operators via different pre-built or custom roles. This allows you to manage who within your company can access, modify or export different types of data. For more on this, see [About access management](../../administration/using/about-access-management.md).

For more on these features and how to manage them in Adobe Campaign, see [this page](../../start/using/privacy-management.md#consent-retention-roles).

### Privacy requests {#privacy-requests}

Adobe Campaign provides additional capabilities to help you facilitate your readiness as a Data Controller for certain Privacy requests:

* The **Right to Access** is the right for the Data Subject to obtain from the Data Controller confirmation as to whether or not personal data concerning them is being processed, where and why.

* The **Right to be Forgotten** (delete request) entitles the Data Subject to have the Data Controller erase their personal data.

>[!NOTE]
>
>This set of tools is here to help you with your privacy compliance for GDPR, CCPA, and PDPA. For more on these different regulations, see [this page](../../start/using/privacy-management.md#privacy-management-regulations).

The **Access** and **Delete** requests are presented on [this page](../../start/using/privacy-management.md#right-access-forgotten). The implementation steps to create these requests are detailed on [this page](../../start/using/privacy-requests.md#about-privacy-requests). Tutorials are also available [here](https://experienceleague.adobe.com/docs/campaign-standard-learn/tutorials/privacy/privacy-overview.html).

## Tracking capabilities {#tracking-capabilities}

Thanks to its tracking functionalities, Adobe Campaign enables you to track the behavior of your delivery recipients using session cookies and permanent cookies. For more on tracking, see [this page](../../sending/using/tracking-messages.md).

>[!NOTE]
>
>Regulations such as the General Data Protection Regulation (GDPR) state that companies require the agreement of website users before installing any cookies. You must inform users that your sites are equipped with web tracking tools via an authorization request.

You can also add [tracked links](../../designing/using/links.md#about-tracked-urls) in your messages in order to measure the impact of your delivery and recipient behavior in the [Tracking indicators](../../reporting/using/tracking-indicators.md) built-in report, or create your own [dedicated reports](../../reporting/using/about-dynamic-reports.md).
