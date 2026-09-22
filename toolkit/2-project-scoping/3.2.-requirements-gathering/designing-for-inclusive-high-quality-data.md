# Designing for inclusive high-quality data

High-quality data and careful interpretation are the foundation of good data science and product development, and of the informed decisions they enable. Consider data as a resource that shapes pathways towards creating equitable experiences. It is not neutral, but reflective of socio-cultural, and economic histories, contexts and experience!

To ensure the quality and integrity of the research and data of your product, it's essential to:

1. Foster a culture of openness and critical thinking among the team, encouraging scrutiny and peer review.
2. Maintain meticulous documentation of the data collection, analysis, and interpretation processes, facilitating reproducibility and transparency.
3. Engage with stakeholders throughout the project to ensure the research remains aligned with its objectives and the needs of the intended audience.

{% hint style="info" icon="chart-tree-map" %}
Remember: Data without context can be meaningless or even misleading, so treat metadata as the entry point for any user to understand your dataset.&#x20;

Resource: Informing Change's "[Data Ethics Guidebook and Toolkit](https://informingchange.com/data-ethics-project/)"
{% endhint %}

#### Some of the ways in which you can avoid reinforcing equalities, misrepresentations or inaccuracies:&#x20;

1. #### Build inclusive datasets

Missing data, over-representation and under-representation can all cause design and algorithmic injustices.

* Build the data from scratch using existing literature and community collaboration.
* Ensure that the data used in your product is accurate, up-to-date, and sourced responsibly.&#x20;
* Transform the data collected, i.e. qualitative, quantitative, visual media to computing languages.
* Explore techniques to address over and under representation. This is easily addressed through diverse data representation in your model, and balancing out the sample size.
* Fill any gaps in your datasets, particularly recognising the impact of how they skew outcomes and disproportionately affect vulnerable and excluded groups.&#x20;

{% hint style="info" icon="head-side-gear" %}
While having diverse data helps mitigate biases and track possible injustice, it still risks contributing to a deficit narrative. That is, reducing minoritised groups to their problems, on collecting data that mirrors those problems.
{% endhint %}

2. #### Implement rigorous data validation and cleaning processes to mitigate risks.

* Check for missing, duplicated, or inconsistent entries before the data feeds into any model or decision. Specifically look for records with implausible values, conflicting entries or fields left blank consistently for a certain group over others.
* Document every cleaning decision and its rationale. It should be clear for someone to review the choices made about to correct, exclude, or impute.&#x20;



2. #### Actively seek out bias&#x20;

* Assess the analysis for potential biases that could affect the interpretation of the data. Bias can enter any stage of the data pipeline and often influences the magnitude and direction of findings. This means that the results are not necessarily a true reflection of the reality on the ground and can have major knock-on effects. Keep an eye out for:&#x20;
  * Confirmation bias: "[Confirmation bias occurs when an individual looks for and uses the information to support their own ideas or beliefs. It also means that information not supporting their ideas or beliefs is disregarded.](https://catalogofbias.org/biases/confirmation-bias/)"
  * Selection bias: "[..occurs when individuals or groups in a study differ systematically from the population of interest leading to a systematic error in an association or outcome."](https://catalogofbias.org/biases/selection-bias/)
  * Algorithmic bias: "[algorithmic bias describes systematic and repeatable errors in a computer system that create unfair outcomes, such as privileging one arbitrary group of users over others. Also, occurs when an algorithm produces results that are systemically prejudiced due to erroneous assumptions in the machine learning process.](https://guides.lib.fsu.edu/algorithm)"&#x20;

{% hint style="info" icon="magnifying-glass-waveform" %}
[Catalogue of Bias Collaboration](https://catalogofbias.org/): In response to concerns over quality of evidence informing health policies, a group of researchers put together a catalogue of the types of biases that researchers need to be aware of. Although the examples mainly reference health studies, it's a useful resource explaining different types of biases, their potential impact and how they affect the interpretation and use of evidence in decision-making.&#x20;
{% endhint %}

* Deliberate with diverse team members on the interpretation of the data. This can help mitigate any disciplinary or other blind spots. If possible validate through engagement with samples of the data sources.

{% hint style="info" icon="people-group" %}
Diverse team mean having team members who are not part of a marjoritized group (i.e white male), ones who are part of the community you are designing with, and provide them with the autonomy and power to inform decision
{% endhint %}

* Consider how the findings of your data analysis may impact different groups of people differently. For example, the same interpretation of your data could benefit one group while disadvantaging another. To avoid this, interrogate your own analysis and consider how benefits, harms, costs, or access are spread across different groups.&#x20;
* Make room for reflexivity. Create a pipeline where the community you are working with learns alongside your team. Rechannel available resources to empower your community in non-extractive ways.

{% hint style="info" %}
**When interrogating your data, reflect on some of the following questions:**&#x20;

* Who benefits from this finding being acted on, and who might be disadvantaged?
* Does this hold equally across subgroups (income, ability, age, geography, etc.), or does it mask disparities when only the average is reported?
* If we implement a recommendation based on this, whose access or outcomes improve, and whose might get worse?
* Are there groups who are underrepresented in the data, such that the finding doesn't actually apply well to them?
* Could this analysis, even if well-intentioned, reinforce an existing inequity rather than reduce it?
{% endhint %}

3. #### Interrogate power and undertake contextual analysis&#x20;

* Interpret the data within the context of the research problem. By keeping the inquiry closely tied to the problem, you reduce the risk of introducing assumptions or biases that could lead to misleading conclusions or solutions.
* Collaborate with domain experts to ensure the findings are meaningful and accurately reflect the complexities of the subject matter.
* Lay out the various frictions that occur in a given problem and contextual analysis. Frictions of power include how you frame your research problem at the beginning. For instance, how might we transform the transportation system to work for care givers (who are often women), and people who live in racially, and class segregated communities?

{% hint style="info" icon="book-bookmark" %}
Resource: [A Toolkit for Centering Racial Equity Throughout Data Integration 2.0](https://aisp.upenn.edu/centering-equity/)
{% endhint %}

#### 4. Report and visualise your findings clearly&#x20;

* Communicate the findings in a clear, transparent, and accessible manner.&#x20;
* Use visualizations to help convey complex data insights effectively.
* Include limitations of the data and potential sources of error in the analysis to provide a complete picture of the findings.

{% hint style="info" icon="circle-book-open" %}
Resource: [This guide](https://www.urban.org/sites/default/files/publication/104296/do-no-harm-guide.pdf) and the associated checklists and toolkits focus on the often hidden or subtle ways that data analysts and communicators fail to incorporate equitable awareness in the data they use and the products they create.
{% endhint %}

#### 5. Address injustices and bias in your model

In some cases, you'll rely on models, algorithms, or other tooling to generate the data your team or product needs to move forward. Just as you screen your underlying dataset for bias, you must also screen the models applied to that data. Tools that shape your data deserves the same scrutiny as the data itself. Be sure to:&#x20;

* Audit your algorithms thoroughly before rolling them out
* Engage in frequent audits
* Ensure that your source code is available for external review, support and insights

**Example of how to evaluate your model (similar to data bias evaluation in #2):**&#x20;

1. **Form your hypothesis and map proxy variables:** Name the specific harm you suspect. Then list every input the model uses, flag which ones are protected characteristics (race, gender, disability, age) and which are proxies for them (postcode, name, school attended, device type). Proxies are the usual route bias.&#x20;
2. **Source the missing data:** Identify who is underrepresented or absent from your training and test data, and source or commission data that fills the gap e.g. more diverse crash test dummies, more languages, more disability profiles.
3. **Build a test model to isolate outputs by group:** Build a test model that disaggregates outputs by race, gender, sexuality, ethnicity, location, class, and disability rather than relying on a single aggregate accuracy figure.
4. **Stress-test error costs and feedback loops:** For each group, weigh what happens when the model is wrong and whether the error compounds over time. Model what happens after deployment, not just at first use e.g. predictive policing increasing patrols, which increases recorded arrests in the same area, reinforcing the model's own prediction.
5. **Check for recourse and document your risk assessment:** Confirm affected people have recourse to contest a wrong output, then record your hypothesis, findings by group, and mitigations in a form your team and stakeholders can review.

{% hint style="info" icon="store-slash" %}
Understanding that algorithms exist in a social world with historical context means that the impacts of technology are shaped by the society that uses it - which in this case is deeply rooted in inequality.&#x20;

This [decision tree](https://www.aaas.org/sites/default/files/2023-08/AAAS%20Decision%20Tree.pdf) produced by the AAAS Center for Scientific Responsibility and Justice is intended to be a guide that assists the user and their organisation to structure the decision-making process on whether to develop or deploy AI solutions
{% endhint %}

{% hint style="success" %}
**Amsterdam and Helsinki’s AI Registers**

These cities have created [public-facing registers](https://ai-regulation.com/amsterdam-and-helsinki-launch-algorithm-and-ai-register/) that detail their use of AI systems, including the system’s purpose, data used, and the team responsible. This transparency initiative helps in oversight and public trust.
{% endhint %}

6. #### Advocate for change&#x20;

* Use data science to challenge Data science: Its structures of 'rigor' and 'objectivity' have too often reinforced the very biases they claim to guard against.&#x20;
* Finding ways to partner with partners, such as city officials, to show the depth of the issue which may prompt policy on accountability and improvements. For instance, a policy that moves to redesign transportation systems that takes into account care giver patterns, disabled people, class and age dynamics, gender, and sustainability.
* Move from community problem to gathering proof to policy change, through collective advocacy.

{% hint style="info" icon="megaphone" %}
Collecting, analysing and reporting harm is a method of speaking to power however should be accompanied by community engagement, political organizing and protest.
{% endhint %}

***
