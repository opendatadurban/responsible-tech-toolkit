---
icon: toolbox
cover: ../.gitbook/assets/rtt-bg-initiate.png
coverY: 0
layout:
  width: default
  cover:
    visible: true
    size: full
    mask: none
  title:
    visible: true
  description:
    visible: false
  tableOfContents:
    visible: true
  outline:
    visible: true
  pagination:
    visible: true
  metadata:
    visible: true
  tags:
    visible: true
  actions:
    visible: true
  anchors:
    visible: true
---

# (2) Project Inception

This phase tackles all the preliminary requirements to ensure that many of the principles are baked in from the start of the process.&#x20;

{% stepper %}
{% step %}
### Contracting&#x20;

Contracts are one of the most durable levers for embedding responsible technology into a production pipeline. It locks in accountability before work begins and sets specific expectations and commitments for all partners.&#x20;

* **Mandate accessibility, privacy and safety standards contractually.** Reference specific standards (e.g. WCAG) as binding deliverables.&#x20;
* **Right to flag ethical concerns without penalty.** A contractual mechanism to pause or raise concerns if the vendor identifies that requested data use would cause harm, discriminate, or breach the responsible tech standards both parties signed up to without this being treated as a breach of contract or grounds for termination.
* **Build in an exit and decommissioning plan.** Require a clear plan for what happens to data, infrastructure, and continuity of service if the contract ends or the vendor fails to deliver.

{% hint style="info" icon="cart-shopping-fast" %}
The flipside of contracting is procurement. There are clear avenues for leveraging the procurement process to prioritise responsible tech, including:

* Develop ethical procurement guidelines that prioritise vendors who demonstrate strong commitments to data privacy, security, and ethical tech practices.
* Use procurement to promote equity by including accessibility and non-discrimination requirements in RFPs (Requests for Proposals) to ensure technology solutions are inclusive.

For a full list of activities to support this kind of procurement, see this [resource.](../governance/4-procuring-responsible-tech.md)&#x20;
{% endhint %}
{% endstep %}

{% step %}
### Resourcing your product team with the right balance of skills &#x20;

* Define the skill sets and roles required for the project, emphasising a balance of technical, ethical, design, and community engagement expertise.
  * Use a skills matrix to map out required skills against team members' competencies
* Recruit team members who not only possess the necessary technical skills but also demonstrate a commitment to responsible technology and public interest values.
* Incorporate the principles and duties of responsible technology into existing roles (see examples [here](../governance/3-organisational-capacity.md)).&#x20;

{% hint style="info" icon="pencil-line" %}
Consider soft skills and cultural fit as much as technical skills in recruitment.
{% endhint %}

* Use diversity and inclusion checklists to guide recruitment and team composition.&#x20;

{% hint style="info" icon="books" %}
[Xindeling Pan](https://medium.com/@xindeling?source=post_page---byline--45fd16e3f855---------------------------------------) offers this [Diversity and Inclusion Checklist](https://xindeling.github.io/Diversity-and-Inclusion-Checklist/) as a helpful resource
{% endhint %}
{% endstep %}

{% step %}
### Setting up good governance structures&#x20;

* Develop a governance framework that includes clear policies and procedures for ethical decision-making, data governance, and handling of concerns or breaches.&#x20;
* Identify if the project requires any specific or unique guardrails due to the nature of of the problem, data or vulnerability of users or stakeholders and develop necessary safeguarding policies in response.&#x20;
* Establish a reporting mechanism for team members and stakeholders to raise ethical concerns or issues related to technology misuse or unintended consequences. This could include whistleblowing mechanisms, if needed.&#x20;
* Where necessary, establish cross-sector advisory boards or review panels that can strengthen the oversight and monitoring process.
* Clarify the role of the funders, partners and other stakeholders to identify and resolve ethical risks, harmful tech or waste
* <mark style="background-color:$primary;">Develop Theories of Change and GESI frameworks -</mark> <mark style="background-color:$success;">Conduct GESI Scorecards: Regularly review product features to identify potential to advance gender and social inclusion considerations, or identify risks of exclusion of specific groups.</mark>
* Develop KPIs focused on inclusivity, data privacy, value for money and ethical use of technology.
* **Adopt and Enforce Data Security Standards:** Implement standards such as ISO/IEC 27001 to manage and protect digital information.

{% hint style="info" icon="calendar-check" %}
- Use project management tools to embed transparent tracking of decisions and actions.
- Regularly review and update governance policies to reflect new insights, challenges, or changes in the project scope.
- Promote a culture of openness and accountability, where raising concerns is encouraged and valued.
{% endhint %}
{% endstep %}

{% step %}
### Conducting baseline risk assessments and mitigation strategies&#x20;

Most project risk assessments focus on project-specific risks such as delivery challenges or running over budget. In this assessment, specific attention must also be paid to systematically evaluate the potential ethical challenges of the project, covering aspects such as data privacy, equity, and potential harm to individuals or communities.

The point is to anticipate possible misuse, failure modes, and unintended consequences before deployment, rather than reacting after the fact. This spans a wide range of potential issues from physical safety (e.g. autonomous vehicles) to psychological harm (e.g. social media and mental health) to societal-scale risks.

Steps:&#x20;

1. Identify project risks including ethical risks. Conduct a preliminary stakeholder and power-mapping exercise: who benefits, who could be harmed and who is missing from the room?&#x20;

<details>

<summary>To identify ethical risks, a helpful framework is <strong>Dystopian Future Mapping.</strong> </summary>

**(1) Scenario Development**

Brainstorm potential dystopian outcomes related to the project. Consider scenarios like exacerbating social inequalities, enabling surveillance and privacy breaches, and causing environmental harm.

**(2) Reverse Engineering**

For each dystopian scenario, work backward to identify what decisions or project aspects could lead to such outcomes. This includes technology misuse, data mismanagement, and lack of oversight.

**(3) Design Against Dystopia**

Develop strategies and safeguards to prevent the identified dystopian outcomes. This might involve design choices, governance frameworks, and community engagement strategies. Employ design thinking methodologies to ideate and prototype solutions that mitigate identified risks. Consider opportunities and strategies throughout the production pipeline.&#x20;

**(4) Documentation and Communication**

Clearly document the dystopian scenarios, the reverse-engineered pathways, and the preventative strategies.&#x20;

Share these findings with all stakeholders and assess if and how they can be improved to match reality.

</details>

2. Evaluate their likelihood and impact.
3. Propose mitigation strategies

{% hint style="info" icon="lightbulb-exclamation-on" %}
Trustable has developed an extensive list of mitigation ideas mapped against potential risks. Focus is given to AI systems, but can be extended to other types of technologies.&#x20;
{% endhint %}

4. Engage with stakeholders to validate and refine the assessment.

{% hint style="info" %}
Tip: Use collaborative documentation platforms to share and discuss the findings.
{% endhint %}



#### &#x20;An Intersectional Framework to Assess Risk and Threat Models

* Key actions\
  Detail the various risk levels and threat models for different user and beneficiary types of your product. In an intersectional framework, you may categories users and beneficiaries using: Age, gender, family configuration, geographic location, sexuality, race, disability, ethnicity, educational background, language, economic status, and sustainability\
  <mark style="background-color:$danger;">Risk is not evenly distributed ,but you have to design with the person with the highest risk.</mark>&#x20;
* Resource? The Trust and Safety Partnership developed this framework for assessing and evaluating these 35 best practices for online platforms to incorporate to keep users of digital services safe from abuse. The framework can be used to develop robust assessment processes to gauge to what degree digital platforms are following these best practices.[ Read more here.https://dtspartnership.org/wp-content/uploads/2021/12/DTSP\_Safe\_Framework.pdf](https://dtspartnership.org/wp-content/uploads/2021/12/DTSP_Safe_Framework.pdf)&#x20;
{% endstep %}

{% step %}
### Co-creating Theories of Change and Indicators of Success


{% endstep %}

{% step %}
### Embedding learnings in the project process&#x20;


{% endstep %}
{% endstepper %}

* Ethical decision-making frameworks, such as the [Markkula Center for Applied Ethics framework](https://www.cse.sc.edu/~mgv/csce390f22/MarkkulaFramework.pdf). Use of project management tools that allow for transparent tracking of <mark style="background-color:$warning;">decisions and actions.</mark>
*

    #### Ethical Impact Assessment (EIA)

    Conduct an Ethical Impact Assessment to systematically evaluate the ethical implications of the project. This should cover aspects like data privacy, equity, and potential harm to individuals or communities.

    * **Responsibility**: Conducted by ethics advisors, with input from the entire project team. Tools: Utilize EIA frameworks and checklists to guide the assessment.
    * **Steps**: Identify ethical risks, evaluate their likelihood and impact, and propose mitigation strategies. Engage with stakeholders to validate and refine the assessment. At this stage it may be useful to take the team through a tool such as [https://responsibletech.se/tool.php#firstbatch](https://responsibletech.se/tool.php#firstbatch)

## Monitoring, Reporting, Evaluating, Learning (MREL)

The MREL framework is crucial for fostering responsible technology development and deployment, ensuring that the technology solutions are ethical, protect data privacy, and utilize public funds efficiently.

Here’s how to integrate these considerations into the MREL process:

### Monitoring

* **Action Steps**
  * **Identify Ethical KPIs:** Develop KPIs focused on inclusivity, data privacy, value for money and ethical use of technology.
  * **Implement Privacy-Focused Monitoring Tools:** Use tools that respect user privacy while collecting essential data for performance monitoring.
  * **Conduct GESI Scorecards:** Regularly review product features to identify potential to advance gender and social inclusion considerations, or identify risks of exclusion of specific groups.
*   **Responsible Roles**

    Project Manager

    Data Protection Officer
* **Tips**
  * Incorporate [privacy by design](/broken/pages/iT84HWNT6I85kP6G9H1Y) principles in selecting monitoring tools.
  * Regularly update KPIs to reflect evolving ethical standards and regulations.

### Reporting

* **Action Steps**
  * **Incorporate Ethics in Reporting:** Highlight efforts and measures taken to ensure inclusivity, data privacy, and ethical considerations in regular reports.
  * **Consider Transparent Reporting:** Open reports to the public for transparency on key decisions, spend, and progress.
  * **Document Ethical Considerations:** Keep detailed records of decisions made to address ethical concerns, including stakeholder feedback.
  * **Transparency Reports:** Publish transparency reports detailing data usage, privacy measures, and inclusivity efforts.
* **Responsible roles**
  * Data Protection Officer
  * Community Engagement Specialist
* **Tips**
  * Use clear, non-technical language to enhance understanding among all stakeholders.
  * Engage with external ethics reviewers for report validation.

### Evaluation

* **Action Steps**
  * **Ethical Impact Assessment:** Evaluate the social and ethical impact of the product, focusing on potential harms or exclusions. _This step_ can be complicated by the multiple legislative mandates of government, which can at times come into conflict with one another - such as the mandate to protect property, and the mandate to protect data rights, and the mandate to provide services and shelter when dealing with informal settlements data for use in either improved planning and service delivery, or evictions. A rights-based approach focusing on the data producer is helpful: ensure that their right to consent to how their data is used has been protected. Secondly, ensure that the legislative hierarchy of rights is being honoured when assessing potential costs and benefits or benefits and harms of a technology solution (for example, Constitutional rights are superior to by-laws).
  * **Data Privacy Compliance Check:** Regularly review compliance with data protection laws and ethical guidelines.
  * **Cost-Benefit Analysis (CBAs):** Evaluate the efficient use of public funds in relation to the ethical and social benefits of the technology. ⚠️ However, this assessment should not be done in isolation of other assessments or deliberations, as CBAs have limited ability to capture all costs and benefits, and in particular have limited ability to capture the distributional impacts of costs and benefits and may therefor skew decisions towards specific groups.
*   **Responsible roles**

    Ethics Committee

    Chief Data Officer
* **Tips**
  * Include diverse perspectives in the evaluation process to uncover potential biases and harms.
  * Utilize ethical frameworks and impact assessment tools designed for technology evaluation.

### Learning

* **Action Steps**
  * **Integrate Feedback Mechanisms:** Establish clear channels for users and affected groups to provide feedback on ethical concerns and inclusivity.
  * **Conduct Ethical Review Sessions:** Regularly review project outcomes and processes to identify ethical learnings and improvements.
  * **Update Ethical Guidelines:** Revise internal guidelines and documentation based on learnings to improve future projects.
*   **Responsible roles**

    Entire Team

    With leadership from the Chief Technology Officer
* **Tips**
  * Foster a culture where ethical considerations are discussed openly and integrated into daily work.
  * Document and share learnings widely to promote ethical practices across the industry.
