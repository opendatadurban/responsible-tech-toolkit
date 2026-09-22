# Designing for user privacy

Privacy protections and policies can sound abstract but there are real consequences that exist. It’s about preserving individual autonomy and agency in a world where institutions increasingly have the means to observe, predict, and influence behavior at scale. For an individual, privacy is therefore about maintaining control over information and personal data about yourself, and limiting the ability of others to make consequential decisions about you based on data you never knowingly or meaningfully consented to share. For organisations building the products, it’s about ensuring that steps to protect users’ data privacy is baked in from the start. Consider privacy as meaningful boundary management.&#x20;

In practice, this means collecting only the data you need, being transparent about what's collected and why, giving people meaningful control over their data, and securing it properly. At its core, it’s about respecting people's ability to make informed choices about the technology they use where they have genuine opt-in rather than buried terms of service, and preserving meaningful alternatives rather than coercive lock-in.&#x20;

Privacy is also anti-surveillance by design. Surveillance is the ability of an entity to observe your activities, communications, location, or behavior through the data trail you generate, often continuously and without your active awareness at the moment of collection. This can be for commercial, governmental or interpersonal interests. It is critical as a responsible product developer to ensure that your tool does not contribute to surveillance activities and protects your users’ safety and privacy at all times. &#x20;

**Questions to ask yourself: If the user or beneficiary does nothing, is their privacy protected? Is their use of your product still secure? Do users have meaningful control over their data?**&#x20;

{% hint style="info" icon="anchor-lock" %}
**Case study: Public Scrutiny of Contact Tracing Apps**

During the COVID-19 pandemic, when urgency was highly valued, several governments proposed contact tracing apps to monitor virus spread. Public and expert feedback highlighted privacy concerns, leading to the adoption of more privacy-preserving approaches in many jurisdictions. Some apps shifted to decentralized models, where data processing occurs on individual devices rather than centralized servers, minimising data privacy risks.
{% endhint %}

{% hint style="info" icon="lock-hashtag" %}
Privacy by Design cannot be a random feature on a product. It must be a practice where any new process or decision must be tested through a privacy-first mindset.
{% endhint %}

**Key steps to integrating privacy by design in your prototypes and project infrastructure:**&#x20;

* **Data Minimisation**&#x20;
  * Only collect the amount and types of data you need. This means the absolute minimum amount of data necessary.&#x20;
  * Remember, more data does not always translate to better.
  * Ensure that you only use the data collected for the purpose you and the user or beneficiary agreed on
  * **Example:** A maps app requesting location only while in use, not tracking it continuously in the background.&#x20;

{% hint style="info" icon="globe-pointer" %}
A range of incredible resources developed by the Responsible Data collective, originally convened by The Engine Room, alongside a number of partners – most notably Aspiration Tech. The group has a unifying interest in supporting the responsible use of data in social change efforts. [https://responsibledata.io](https://responsibledata.io/)
{% endhint %}

* **Good Data Retention Practices**
  * Do not keep the data longer than needed for the purposes you and the user and/beneficiary agreed to. That is, delete data you no longer need, after a specific period of time or when requested to do so by the user.
  * **Example:** A food delivery app automatically deletes exact GPS delivery routes 30 days after an order is completed, since they're only needed to resolve delivery disputes in the short term.&#x20;

{% hint style="info" icon="pencil-line" %}
Example of a Responsible Data Policy in action by The Engine Room: [https://www.theengineroom.org/responsible-data-policy](https://www.theengineroom.org/responsible-data-policy)
{% endhint %}

* **Disclosure and Data Sharing**
  * Do not disclose any data unless necessary to achieve the purpose it was collected. Where purpose has been agreed on by users or beneficiaries.
  * **Example:** A health app shares symptom data with a user's chosen doctor for diagnosis, but doesn't sell or pass that data to advertisers or insurers who weren't part of the original agreement&#x20;

{% hint style="info" icon="magnifying-glass-waveform" %}
**Data Privacy Compliance Check:** Regularly review compliance with data protection laws and ethical guidelines.&#x20;

Resource: [The Limits to Digital Consent: Understanding the risks of ethical consent and data collection\
for underrepresented communities. ](https://simplysecure.org/resources/The_Limits_to_Digital_Consent_FINAL_Oct2021.pdf)
{% endhint %}

* **End to End Encryption**
  * Create in-built end-to-end-security, and protection: encrypt the full lifecycle of data in motion and at rest. Make sure it remains confidential, true to its original form and accessible. Encryption also protects the user or beneficiary from third-party spying.
    * **Example:** messages encrypted so even the service provider can't read them (e.g., WhatsApp or Signal)

{% hint style="info" %}
Many people may find it useful to have additional protections through the use of VPNs and other surveillance circumvention technologies. Your product should be built to support some of these features and personal practices, not block them, which puts folks at risk.&#x20;
{% endhint %}

* **Positive Sum**
  * This principle rejects the misconception that designers need to choose between security and functionality. Thoughtful design makes it possible to achieve both at once. Therefore the aim is to build systems that satisfy user needs and privacy requirements simultaneously, without trade-offs, and therefore provide full product functionality, from user experience to security.&#x20;
  * **Example:** A banking app implements biometric login (Face ID/fingerprint) — this makes authentication faster and easier for the user (functionality) while also being more secure than a password (privacy/security), rather than forcing a trade-off between convenience and protection. Likewise, a cryptpad provides functional collaborative documents and privacy. Calyx has an android OS and Mobile internet service that is fully functional with no “trade offs”. Signal provides you with a messaging platform that centers on privacy in a functional way.

{% hint style="info" icon="head-side-gear" %}
Many data scientists and designers are wrangling between preserving privacy by not collecting certain identity data however risk their data being exclusive to a dominant group because of the cost of engagement. Other times not collecting disaggregated data, also means data on minority groups may not exist to trace challenges, biases and issues the community is facing. Still collecting the data may lead to targeting using said proxy factors. How might we balance out anonymity, and the social impact of diversified datasets?
{% endhint %}

***

**Lets Do an Exercise**

**Simple Scenario:** You need to collect data for a research project to improve access to libraries in a community. You and your team decide to use a form to collect information from residents. How will you embed privacy by design into your decisions when rolling out the forms and using the data?

1. **Consider the problem you’re trying to solve and define your purpose clearly:** Before collecting anything, articulate exactly what you're trying to learn: what barriers residents face in accessing the library, and what would make it work better for them. This purpose statement becomes your filter for every decision that follows.&#x20;
2. **Consider the platform: What form provides better privacy?**\
   Do a bit of research upfront about the types of data collection tools that not only offer great features but also are responsible in their own data practices. Questions to ask yourself: Where is their data stored? Is it encrypted? What jurisdiction governs it? Does the vendor sell data to third parties? Using FormStack or JotForm may provide better privacy protections than say Google Form&#x20;
3. **What data do we actually need to answer our question, and what's just "nice to have"?** You do not need personal information, such as emails or names of the people you speak to. You only need them to answer specific questions on how the community library can be improved to work better for them. Only collect contact details if you genuinely intend to follow up with that person.  But privacy is better protected if you never collect the information or data in the first place.
4. **What measures will you put in place to ensure that you will get informed consent from participants?** Tell participants upfront what data you're collecting, why, how long you'll keep it, and who will see it. Give them the option to skip optional fields (like contact info) and clearly explain that participation is voluntary. Also ensure that consent is written and explained in simple straightforward language.&#x20;
5. **If you do decide to collect key personal information, what measures will you take to protection their privacy?** When compiling findings, ensure that all data is anonymised (de-identified) and/or aggregated before analysing and sharing.&#x20;
6. **What is our data retention period?** For research standards it is generally accepted to keep data securely for 3 years after collection and deleting it thereafter. However you and your team can set your own data retention period. Define this in advance, document it, and build in a scheduled deletion rather than relying on someone to remember.
7. **How will we store the data?** Store survey responses in an encrypted, access-controlled system rather than an open spreadsheet. If contact information is ever needed, keep it separate from the survey responses (so the two can't easily be re-linked), on something like a password-protected CryptPad sheet with a self-destruct timer — rather than bundled into the main dataset indefinitely.
8. **How can we only distribute information to the team that needs it?**\
   Only share the information that is needed to a specific team. For example, instead of sharing the spreadsheet as “anyone with link” or anyone “on web can access”, add the specific persons who need to be involved directly to the document. Remove their access after their task is complete. And in the case you need to share some data externally for verification, extract the exact data needed into another spreadsheet, or whichever format needed, and share it with with the people who it concerns. Remove access after their task is completed.

{% hint style="info" icon="file-shield" %}
Given that some people may create copies of the document, it may be important to disable certain replicable features when sharing data externally. Remember that it must only be used for the purpose it was stated to the users and beneficiaries in the first place.
{% endhint %}
