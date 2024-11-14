# Design and Development

**Design and Development**: Focusing on creating design prototypes and developing the project infrastructure.

1. **Privacy by Design:** Integrate privacy measures from the start. Not only when privacy risks arise. **Tip**: If the user or beneficiary does nothing, their privacy is protected. Consider privacy as meaningful boundary management

**Framework**:

1. Only collect the amount and types of data you need. This means the absolute minimum amount of data necessary. Remember, more data does not always translate to better.
2. Ensure that you only **use** the data collected for the purpose you and the user or beneficiary agreed on.
3. **Keep a good data retention practice,** which means that you will not keep the data longer than needed for the purposes you and the user and/beneficary agreed to. That is delete data you no longer need or when requested to do so by the user
4. **Do not disclose** any data unless necessary **to achieve the purpose it was collected**. Where purpose has been agreed on by users or beneficiaries.
5. Privacy by Design cannot be a random feature on a product. It must be a practice where any new process or decision must be tested through a privacy-first mindset.
6. Positive-Sum: Provide full product functionality, from user experience to security. For example, a cryptpad provides functional collaborative documents, and privacy. Calyx has an android OS and Mobile internet service that is fully functional with no “trade offs”
7. In built end-to-end-security, and protection: Encrypt the full lifecycle of data in motion and at rest. Make sure it remains confidential, true to its original form and accessible. Encryption also protects to user or beneficiary from third-party spying.

**Lets do an exercise:** You need to collect data for a research project you are undertaking to improve access to libraries in a community. You and your team decide to use a form to collect information from residents. From the 7-step approach we have provided how will you embed privacy by design in your decisions, rolling out the forms and using the data?

(If there is interactivity, hopefully we see how they answer it, and provide feedback)

Answer: \*\*\*\*

1. **What form provides better privacy?** _**Action**_: Using form stack may provide better privacy than say google forms
2. **How can we collect the necessary information only? Action:** You do not need the personal information, like emails or names of the people you speak to. You only need them to answer specific questions on how the community library can work better for them. You only collect their contact details if you need to contact them.
3. **What is our data retention period? Action:** If you ever need to contact them, then only keep that information on a cryptpad sheet, and set a self destruct timer. The sheet will also be password protected. However, for research usable it is required that you keep data for up to 3 years after collection and deleting it thereafter. \*\*\*\*4. **How can we only distribute information to the team that needs it?**

_**Action:**_ Only share the information that is needed to a specific team. For example, instead of sharing the spreadsheet as “anyone with link or on web can access”, add the specific persons who need to be involved directly to the document. Remove their access after their tasks is done. And in the case you may need to share some data externally for verification, extract the exact data needed into another spreadsheet, or which ever format needed, and share it with with the people who it concerns. Remove access after their task is completed. Given that some people may create copies of the document, it may be important to disable certain replicable features when sharing data externally. Remember that it must only be used for the purpose it was stated to the users and beneficiaries in the first place.

2. **Safety by Design:**

Prioritise user safety and anticipate system manipulation.

This avoids online harms in any form. this could be technology facilitated, which means that harm caused through the use or as a result of the use of technologies.

It is proactive in protecting users.

Safety by Design Works hand in hand with privacy by design. One cannot exist without the other.

Framework:

**Detail the various risk levels and threat models for different user and beneficiary types of your product**:

Note that _Risk_ is not evenly distributed , But, you have to design for the person with the highest risk.

**Build in key safe guards to protect the users and beneficiaries of the product, tool or model.**

a. these could be reporting mechanisms that are easily findable, accessible and usable. The process for reporting and support for people who are exposed to risk should be clear.

b. Blocking certain uses that can harm users and beneficiaries. For instance, certain features of a product turned off for children to avoid interactions with adults and possible avenues for child abuse etc.

**Build accountability and Transparency processes: a.**

Transparency enables easy auditing of your algorithms and models for possible vulnerabilities . This goes without saying, it does help to make your source code open. (Open Data right?)

b. Ensure that your policies are clear and easily understandable. This also means how to hold you accountable if you don’t meet some of the basic safe guarding that is required.

Algorithmic Auditing generally helps with ensuring accountability, but it has to be merged with reporting mechanisms , policies to enforce safety standards and escalation points that are followed through.

***

1. **Accessibility by Design:**

People are not restricted from using a specific product or service due to their disability

**Tip**: This includes technical and user interaction and visual design requirement. It is not just an “add-on” feature, but embedded in the design of services and products

**Remember**

: Many disabled people do not ask for their disability to be “taken away”, but for our products, tools, social spaces and infrastructure to be made accessible with them in mind.

**What are the dynamics of disability?**

There are three types of disability and four categories, they usually fall within physical, cognitive and sensual.

1. **Permanent Disability2. Temporal3. Situational Framework to Accessibility:**
2. **Community Engagement:**

Speak with users or beneficiaries of the product or service who are disabled to reveal additional opportunities that will increase accessibility, pushing towards the positive impact of the product.

**Example**: Some disabled people may find that when cities have a delivery option their monthly medical supplies, it allows them access their needed medication without having to bear the cost of mobility.

1. **Again, design for the outlier:**

How would a poor disabled person use your product or access the benefit of your design?

A lot of assistive devices tend to be very expensive, and a poor disabled person may be hindered from accessing some of these products because accessibility functions were never designed.

Lets take a citizen portal that requires the user to prove that they are human for example.

a. Have you created or enabled an audio option for CAPTCHA?

b.

**Graphic design**

* What sensory considerations have you put in place for people who are :
* hypersensitive to light and sound or cannot hear at all
* Colour blind
* People who are partially sighted or totally blind
* Who cannot read in certain fonts

c.

**Text to speech and speech to textd. Cognitive accessibility:**

This often relate to how you present content in an easily percievable and understandable manner.

1. Can the reader skim through your content?
2. Is it easily understandable by people at various knowledge levels? That is less technical?
3. Make it short. No one wants to read blocks of texts.

Check out this :

1. [Accessibility handbook](https://rgd.ca/working-in-design/resources/accessability-2-a-practical-handbook-on-accessible-graphic-design)
2. [Inclusion is not an add on](https://pollicy.org/wp-content/uploads/2022/01/Inclusion\_Not\_Just\_an\_Addon\_guide.pdf)

***

**The Importance of MVPs and User Feedback**

Part of the OCL methodology is to deploy MVPs and improve based on direct user feedback. When considering potential harm, it is important to ask: ”Is this an MVP-safe” idea? In other words, is there a scenario where an insufficiently developed product launched too widely can do more harm than the value of gathering feedback?

**Case study: Public Scrutiny of Contact Tracing Apps**

During the COVID-19 pandemic, when urgency was highly valued, several governments proposed contact tracing apps to monitor virus spread. Public and expert feedback highlighted privacy concerns, leading to the adoption of more privacy-preserving approaches in many jurisdictions. For example, some apps shifted to decentralized models, where data processing occurs on individual devices rather than centralized servers, minimizing data privacy risks.
