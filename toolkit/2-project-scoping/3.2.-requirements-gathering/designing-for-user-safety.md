# Designing for user safety

Prioritise user safety and anticipate system manipulation to prevent technology-facilitated harm. This could be harm caused through, or as a result of, using your technology. Safety by Design is proactive, not reactive, and works hand in hand with [Privacy by Design](designing-for-user-privacy.md). One cannot exist without the other.

> And remember, “**what we need to explain and account for are not only the inner workings of \[our technology products], but also the history, culture, and context that lead to discriminatory outputs in the first place**” (D’Ignazio and Klien, 2020)

#### Key steps to enhance user safety as a core component of your product:&#x20;

* **Assess and mitigate risks, including active misuse of your product.** Ask not just "how could this fail?" but "how could someone deliberately exploit this?" Consider bad actors, coordinated manipulation, bot networks or bulk exploitation. This should take place during the [Project Inception Phase](../../1-project-initiation-1.md#conducting-baseline-risk-assessments-and-mitigation-strategies), and be revisited regularly throughout the product's lifecycle.

{% hint style="danger" %}
Design against known abuse patterns: stalking via location features, harassment via messaging/comment tools, doxxing via data exposure, coercive control via account-sharing or activity visibility.
{% endhint %}

* **Maintain secure, reliable systems.** Reliability is a safety property. A system that fails unpredictably creates openings for harm.
* **Design a deployment strategy with fail-safes.** Assume something will go wrong, and build in mechanisms that contain the issue rather than let it escalate. This could include staged or limited rollouts, kill switches or rollback plans that let you revert to a known-safe state without disrupting the wider system.&#x20;
* **Regularly undertake security audits.** Build in a recurring checkpoint where risk assumptions are revisited as the product and its user base evolve.
* **Frequently update your product to address potential vulnerabilities that arise** over the lifetime of the product. Our products will never be perfect from the start, which is why testing, auditing and user feedback value-chains are important to understanding the emerging vulnerabilities and blocking those with updated versions.
* **Default to deny.** Assume access only to the lowest layer of a system, and require verification to unlock each higher layer, rather than granting broad access by default and restricting after the fact.

#### **Building safeguards**

* **Make reporting mechanisms easy to find, access and use.** The process for reporting and providing support for people who are exposed to risk should be clear.
* **Block certain uses that can harm users and beneficiaries.** For instance, certain features of a product turned off for children to avoid interactions with adults and possible avenues for child abuse. Or testing against evasive uses, and blocking those uses.<br>

{% hint style="info" icon="box-ballot" %}
Algorithmic auditing generally aids accountability, but it has to be merged with reporting mechanisms, policies to enforce safety standards and escalation points that are followed through. Accountability also means ensuring the benefits of your designs act as benefit for the community.
{% endhint %}

