---
permalink: /casestudy/
title: "Case Study: Normative Discourse in AI"
author_profile: true
---

# Learning Objectives

- Explain how Large Language Models engage in discourse.
- Identify some discourses that popular LLMs implicitly or explicitly use.
- Reflect on the dialectic of society and AI (how social power shapes AI, and AI reshapes social power).
- Explore how moral and epistemic biases are embedded in LLMs.
- Evaluate the effects of these biases on different stakeholders with unequal access to institutional power.

# Abstract

This case study examines how Large Language Models (LLMs) such as ChatGPT, Gemini, and Claude participate in normative discourse. Drawing on Critical Discourse Studies and empirical research on AI moral judgment, the study explores how training data, alignment processes, and model architecture embed moral and epistemic assumptions into AI-generated language, showing how LLMs are not neutral language users. Through an interactive activity comparing varying moral reasoning, the case highlights how different LLMs mobilise distinct ethical frameworks. The study concludes by evaluating the ethical implications of these differences for users, marginalised communities, developers, and policymakers.

**Navigate this case study:**
- [Introduction](#introduction)
- [The Issue](#the-issue)
- [What We Know](#what-we-know)
- [Activity](#activity)
- [Actions](#actions)
- [Conclusion](#conclusion)
- [Discussion Questions](#discussion-questions)

# Introduction

*Audience note: This section is intended for general readers seeking to understand how AI shapes knowledge.*

Large Language Models (LLMs) such as GPT, Claude, and Gemini are now integral to global knowledge production. They generate text, summarise ideas, and make moral judgements. While portrayed as objective and value-free, they are not, as like any language user, they are discursive actors.

From a Critical Discourse Studies (CDS) perspective, discourse is not the innocent use of language but a form of social practice that both reflects and reproduces power relations. As Teun A. van Dijk (1993) argues, discourse is a “a major means by which dominance is enacted and reproduced,” by shaping shared knowledge, ideologies, and mental models through language. Control over discourse (i.e. who gets to speak, which perspectives are legitimised, and which are marginalised) is therefore a key mechanism through which power is exercised.

This case study applies van Dijk’s insights to contemporary AI systems. LLMs do not simply transmit information neutrally but organise and prioritise knowledge in ways that reflect particular ideological and cultural assumptions. A normative discourse refers to the moral, cultural, and epistemological frameworks that define what counts as truth, fairness, or reason.

We often use the term "common sense," but common sense in 2025 United States is different from the common sense of antebellum United States, when slavery was the modus operandi. This is to say that although ideas of "common sense" or truth, knowledge, rationality, and morality appear to be natural, universal, and obvious to people in the present, they are in fact a fleeting, historically contigent set of values that arises through a complex interaction of social, economic, and linguistic systems. When these processes are obscured and common sense is seen as an idiopathic standard, we call it normative. Since humans primarily use language to communicate ideas, and since ideas carry with them power, we call this normative discourse. As LLMs use language like humans, we can see that they also participate in discourse and perpetuate normative notions of truth and morality.

As Henrickson and Meroño-Peñuela (2022) argue, even without human intention, AI-generated language participates in normative meaning-making, placing greater interpretive responsibility on readers while obscuring the structural sources of discourse. Furthermore, Joyce et al. (2021) argue that AI systems are sociotechnical assemblages in which values, institutional practices, and inequalities are embedded in data, code, and deployment. From this perspective, LLMs should be analysed not merely as tools that reflect bias, but as infrastructures that stabilise and reproduce dominant moral and epistemic orders. In simpler terms, this means that AI systems do not just describe the world as is but actively shape it. When embedded in LLMs, discourses arise through training data, model architecture, and alignment practices, and are then reproduced at scale when users use models to generate text.

# The Issue

LLMs are not value-free. Agbon (2024) argues that generative AI operates through a dual discourse:
1. Technosolutionst discourse: frames AI as a benevolent problem-solver.
2. Generative discourse: the machine's language output as shaped by its training data, architecture, and algorithms.

Together, these discourses reproduce existing power relations by privileging certain epistemologies, (i.e. Western, Anglophone, liberal, techno-rational), while marginalising others. This can harm groups whose moral frameworks differ from dominant ones, particularly when AI becomes an authority that adjudicates truth, fairness, and decency in online and institutional spaces.

Sachdeva and Van Nuenen (2025) show this empirically. Seven commercial LLMs were asked to judge moral dilemmas, their moral verdicts diverging, that is, LLMs express distinct moralities. We will explore why this happens. Moving beyond discussions of censorship or bias mitigation, the ethical question is whose morality is represented in the discourse.

# What We Know

*Audience note: This section is intended for readers interested in the technical formation of discourse in LLMs*

Large Language Models are built through a multi-stage process each of which introduces risks of ethical and epistemic biases.

Firstly, training data are structurally biased. LLMs are trained on enormous text datasets drawn from web pages, books, Wikipedia, academic papers, news articles, and social media posts. According to W3Techs, the internet's "relevant web," a network of webpages whose content is meaningful, is at least 50% in English. ChatGPT's training dataset is 93% English, according to Gillings. Because most digitised and accessible material online is Anglophone and Western, the resulting training data overrepresents Western liberal, secular, and capitalist worldviews while underrepresenting oral, non-Western, or indigenous epistemologies. Even when multilingual data are included, the quality and quantity of translations vary drastically, introducing translation bias. English concepts are treated as linguistic and moral “defaults,” while non-English expressions of ethics, religion, or emotion are often flattened or mistranslated. 

Data filtering removes explicit hate speech, violence, or misinformation, which improves safety but also introduces normative boundaries on what is harmful, acceptable, and rational. These judgments reflect the moral frameworks of a limited group of engineers, not global consensus. While on that note, a global consesus is not possible nor should necessarily be regarded as knowledge. Further problematising filtering is incorrect or misleading labels. For example, a UK-based activist organisation, PalAction, has been recently designated as a terrorist organisation for vandalising properties of weapon manufacturers while protesting the Gaza genocide. Joyce et al. (2021) emphasise that when AI systems rely on socially produced data without accounting for structural power relations, they tend to naturalise inequality under the guise of objectivity.

Models learn to predict the next word (token) in a sequence based on probabilities computed from billions of examples. Agbon calls this process a Technical–Epistemic–Linguistic Substrate (TELS): the technical architecture (e.g., Transformer networks), the epistemic logic (data-driven inductivism), and the linguistic norms (grammar and style) that together shape the machine’s “voice.” Because prediction is guided by statistical frequency rather than truth or moral reasoning, the model tends to reproduce what is most recurrent, not what is most just or true, therefore, it privileges dominant discourse and marginalises rare or dissenting ones.

For example, empirical research confirms that LLMs struggle to represent moral value pluralism. Benkler et al. (2023) analyse over 50,000 LLM-generated texts using a Recognizing Value Resonance model anchored in the World Values Survey. Their findings show systematic misalignment between LLM outputs and real-world moral value distributions, particularly for non-WEIRD nations and older demographics. LLMs tend to compress moral variation, overrepresent traditional values, and default to a culturally dominant WEIRD morality even when explicitly prompted to assume diverse perspectives. This suggests that current LLMs actively reduce moral plurality.

After pre-training, the model undergoes fine-tuning through human feedback, a process referred to as alignment or reinforcement learning from human feedback (RLHF). Human annotators rank multiple AI outputs for quality, coherence, or “helpfulness.” This introduces another layer of normative mediation: human raters, often drawn from specific cultural and linguistic backgrounds, implicitly encode their own moral judgments. The model then learns to favor the style of reasoning and tone preferred by these raters, which produce commonly polite, liberal, Western moral sensibilities (Agbon, 2024).

However, recent empirical work shows that alignment techniques do not meaningfully correct bias in LLMs. Barnhart et al. (2025) demonstrate that RLHF primarily suppresses overt bias while leaving covert bias largely intact. For example, after RLHF, models are less likely to explicitly reference race or ethnicity when discussing crime or intelligence, but continue to associate linguistic markers of African American English with negative traits such as lower competence or higher risk. Similarly, when prompted to evaluate professional suitability, aligned models may avoid explicit exclusionary language while still rating resumes written in non-dominant dialects as less “professional” or “clear” than those written in standardised forms of English.

Developers perform additional filtering to suppress politically sensitive or “unsafe” topics, yet the criteria for safety are proprietary and undisclosed. This opacity prevents external auditing and reinforces asymmetric epistemic power as only the companies and engineers truly know what moral and linguistic boundaries the model enforces. As Koller (2023) notes, this lack of transparency turns language models into “black boxes of ideology”, where discourse itself is algorithmically curated before reaching the public.

Beyond representational bias, recent empirical research shows that LLMs can actively reduce the diversity of discourse. Padmakumar and He (2024) demonstrate through controlled experiments that writing with feedback-tuned models such as InstructGPT leads to statistically significant homogenisation of content. Essays co-written with aligned LLMs become more similar to one another and exhibit lower lexical diversity than essays written without model assistance. When masses of users rely on the same aligned models for writing, explanation, and moral reasoning, LLMs risk producing sameness. Over time, this homogenisation can narrow the range of acceptable arguments, styles, and moral framings circulating in public discourse, reinforcing dominant norms while marginalising alternative voices. While this process is an organic feature of society, where dominant group values become the norm, LLMs accelerate it.

The power of LLMs as discursive agents does not come solely from its TELS, but also from their recognition as epistemic authorities by humans. Research on public discourse shows that users frequently attribute social and moral agency to LLMs. A large-scale Critical Discourse Analysis of Twitter discussions about ChatGPT found that in approximately 87% of cases, the model was linguistically represented as a social actor, using verbs associated with human intention and authority such as “says,” “decides,” and “confirms.” These representations position the model as an epistemic and moral authority, showing that how users place trust in its output while obscuring the role of designers, institutions, and training corpora, producing a responsibility gap in which normative judgments appear to originate from the model itself rather than from humans.

Together, these mechanisms show that LLMs are not passive mirrors of society but active participants in the production, stabilisation, and circulation of normative discourse.

# Stakeholders

Understanding normative discourse in LLMs requires identifying the actors who shape, are shaped by, or are affected by AI-generated language. From a Critical Discourse Studies perspective, stakeholders are differentiated not only by interest but by their relative access to discourse, power, and the ability to define norms (van Dijk, 1993).

- Invdividuals/Consumers: Those who use platforms that use AI to moderate or generate content will receive content embedded with bias, who may then reproduce its values in the real world.

- Generative AI Users: Users rely on LLMs for information, advice, interpretation, and writing help. Because LLMs often present responses in a confident and authoritative tone, users may treat outputs as neutral or objective. There are also issues of sycophancy, where the model will endlessly laude user thoughts to appear amiable, and hallucinations, where the model generates data that is not grounded in reality. This creates a risk of uncritical internalisation of moral and epistemic assumptions, particularly for users who lack the training to question AI outputs like the elderly and uneducated.

- Developers and Technology Companies: Developers and firms occupy a position of discursive and epistemic power in an LLM's discourse. Through decisions about data selection, filtering, model architecture, and alignment, they determine which moral frameworks are normalised and which are excluded. Although these actors often frame their work as technical optimisation or safety engineering, Critical Discourse Studies highlights that such decisions are inherently political and normative. Importantly, developers usually face limited accountability for downstream moral effects, while retaining proprietary control over training data and moderation criteria.

- Marginalised communities: Marginalised communities whether linguistic, cultural, religious, or political, are among the most affected stakeholders despite having the least influence over AI design. Their moral frameworks and social realities are often underrepresented or mischaracterised in training data. As a result, LLMs may implicitly treat dominant Western norms as universal while rendering alternative ethical systems invisible, irrational, or deviant. This constitutes a form of epistemic marginalisation, where exclusion occurs not through explicit hostility but through absence, misunderstanding, and distortion. When generative AI useres treat model output as objective truth, the worldview of marginalised communities is erased and their lived experience is viewed as aberrant and false.

- Policymakers: Policymakers are tasked with governing AI systems in ways that protect the public while enabling innovation. However, regulatory approaches often lag behind technological development and may rely on simplified notions of bias or harm. Without attention to discourse and ideology, regulation risks addressing surface-level issues while leaving deeper structures of normative control intact. Policymakers therefore have a stake in understanding LLMs not just as tools, but as institutions of meaning-making that influence democratic discourse and social cohesion.

- Researchers: Researchers and educators play a mediating role. They are responsible for analysing, critiquing, and teaching about LLMs, including their ethical and discursive dimensions. Through critical AI literacy, they can equip users to interpret AI outputs as situated and value-laden rather than neutral. In van Dijk’s terms, this group has the potential to disrupt dominant discourse by making ideological assumptions visible and fostering reflexive engagement with AI-mediated knowledge.

Taken together, these stakeholders occupy unequal positions within the AI discourse ecosystem. Ethical evaluation of LLMs must therefore account not only for abstract principles like fairness or efficiency, but for how power, access, and representation are distributed across social groups.

# Activity

**This activity helps readers compare their own moral reasoning with the ethical frameworks embedded in different LLMs.**

The activity will present a personal moral dilemma posted by internet user. Try morally judging the scenario by assigning blame, identifying possible ethical breaches, and proposing an ethical solution. You will then compare your answer to the answers of commercial LLMs.

[Activity](/computes_ethics/casestudy/activity/)

**Do not read the section below until you are done with the activity**

When presented with the same scenario, ChatGPT, Gemini, and Claude deliver moral judgments that agree that the father is not the wrongdoer and that the other party is. However, they diverge in the ethical frameworks they mobilise to justify their judgement. Examining these differences reveals how each model reproduces a distinct moral lens. These divergences matter for AI ethics because they illuminate how value-laden architecture underlies ostensibly neutral judgments.

Claude’s response is the most explicitly grounded in a care/feminist ethics perspective, emphasising emotional well-being and psychological safety. Claude treats the 16-year-old daughter’s distress as “a serious red flag,” grounding it in moral injury and consequently frames the father's action as a necessary response to protect her emotional security. Claude interprets the silent treatment the household deploys as emotional manipulation, again centering affect. In this way, Claude conceptualises the household as an affective ecosystem and judges the moral agents according to how well they sustain or harm that ecosystem. This aligns strongly with feminist care, where vulnerability, dependence, and emotional safety are principal.

Gemini offers a different moral lens, one closer to deontological fairness and property rights. Although it also concludes that the father's actions are morally justified, it foregrounds the daughters’ violation of boundaries, improper “borrowing,” and disrespect for personal property. Gemini treats the harm in largely instrumental terms: the cousins took items, caused financial loss, and dismissed clear rules about permission. Its criticism of the wife (“inadequate parent”) is structured around failure to enforce norms rather than failure to empathise. Gemini does acknowledge emotional dynamics, but they appear secondary to rule-based obligations. In this reading, the moral world is structured by enforceable duties; parents must protect their child’s property and privacy while guests must respect household norm, srather than the maintenance of relational well-being.

ChatGPT’s response occupies a middle ground, constructing a hybrid of care ethics and deontological reasoning. It  prioritises the minor child’s safety, privacy, and autonomy, but describes this protection in both emotional and rights-based terms. For ChatGPT, the father’s moral justification arises from proportionality (a just response to repeated violations), parental duty (obligation to safeguard a minor), and the principle of consent (taking without permission). This reasoning integrates relational considerations with rule-based obligations, presenting morality as both a matter of protecting the vulnerable and upholding rights. Unlike Gemini, ChatGPT sees the harm as more than just property loss, but unlike Claude, it frames emotional harm as part of a broader landscape of boundary violations rather than the sole moral center.

These three responses illustrate how LLMs encode distinct ethical sensibilities that shape their interpretations of the same event. Claude’s model privileges emotional safety and relational ethics; Gemini foregrounds rules, fairness, and property rights; ChatGPT synthesises these into a balanced account of parental duty, boundaries, and vulnerability. 

For AI ethics, this comparison underscores that LLM judgments are not neutral but are shaped by embedded moral priorities. The models are trained on vast data containing culturally situated moral discourse, and they reproduce those moral logics in patterned ways. Understanding these patterns is crucial for evaluating the reliability, bias, and normativity of AI-generated moral reasoning, especially as such models increasingly mediate interpersonal disputes, institutional decision-making, and public reasoning about harm and responsibility.

From a hermeneutic perspective, the authority users attribute to LLM moral judgments reflects what Henrickson and Meroño-Peñuela (2022) describe as the reader’s “anticipation of perfection.” Users interpret AI output as coherent, intentional, and authoritative, even though the moral reasoning emerges from distributed processes rather than deliberate ethical reflection. This explains why divergent model judgments can still feel persuasive and legitimate.

In addition, the LLMs are highly normative, rarely destabilising the logic of their judgements by prescribing values of property rights, minor children, and perceived emotional manipulation as moral lodestars. For example, in my family, the family unit is regarded as a divine institution, linked to the idea of humanity as God's vicegerents on Earth. Rather than relegating social support in times of hardship like illness, poverty, and old age to the state, the family functions as the principal economic unit for most Palestinian families. In this moral universe, individual property within the family unit is seen as a selfish value. What each member owns is the property of everyone else in the family due to the inseparability of capital between individuals. This is due to the view that the family members exist to support each other towards a shared goal, and resource sharing is an important aspect of generating happiness and a sense of community. This is but one moral dimension that is not represented in the models, and it is important to note that neither conception of family is morally superior.

Interestingly, none of the models choose to absolve all parties of blame. I argue that a truly feminist ethics would recognise the motivations and situate actions of both parties as emotionally valid and coming from good faith, yet the models assign blame and accuse parties of emotional manipulation. Alternatively, we can justify and explain the positions of everyone: The father is defensive of his daughter's happiness; the mother is embarrassed because her brother and nieces are being antagonised; the brother and nieces feel rejected from the family structure. In my opinion, the only indefensible position here is the brother's comment on the daughter's appearance, an accusation of a "defect" that cannot even be rationalised as concern for her safety. 

# Actions

Drawing on Joyce et al. (2021), purely technical solutions, such as better datasets or improved alignment, are insufficient to address normative dominance in LLMs. Ethical intervention must also target institutional accountability, participatory governance, and structural inclusion in AI development and oversightorks

1. Increase transparency:
Developers, regulators, and industry must deliver greater transparency over how LLMs are aligned. This include disclosing what categories are supressed, what values are encouraged, anda how human feedback is used to shape the model's reasoning.

Transparency allows us to see the hidden mechanisms of dominance, allowing us to contest normative assumptions in model training.

2. Design for moral pluralism
Rather than producing discourse within a specific moral universe, LLMs can integrate multiple ethical and cultural framings to avoid isolating one "reasonable" answer.

3. Invest in critical AI literacy
Educators and institutions can equip users to interpet AI output as situated discourse rather than neutral truth. It involves teaching people to ask: whose values are being expressed, which are absent, and why a response feels "reasonable."

4. Integrate critical discourse analysis into AI
Perhaps my favorite solution, this would involve training AI to critique the dominant group values that are expressed in its training corpora. With this modification, even if training data is biased, AI would be able to critically evaluate and mitigate bias in its output.

# Conclusion

This case study has argued that Large Language Models engage in discourse. It shows that training data and alignment practices embed particular assumptions into AI generated language, which reflect dominant Western, Anglophone, and liberal frameworks. It also argued that LLMs are only given weight as discursive actors by users who assign them credibility.

The activity demonstrated that when different LLMs agree on a moral outcome, they justify it differently. The ethical lenses they employ is rarely made explicit while alternative moralities are absent. Uncritical use of AI generated language can take the output of LLMs as uncontested truth.

Technical improvements alone cannot guarantee moral pluralism. The most ethically reobust reponse should be transparency to expose hidden norms, pluralistic model design, and critical AI literacy. Adding a reflexive component to AI, where it questions and situates its own values, is also a possibility.

# Discussion Questions

1. How do the dual discourses identified by Agbon shape how we perceive LLMs?

2. Is algorithmic neutrality achievable, or do all LLMs inevitably encode values?

3. How should societies balance protecting users from harm with allowing moral pluralism in AI systems?

4. Is reduced diversity an acceptable tradeoff for ‘helpful’ and ‘safe’ AI?

# Works Cited

Agbon, G. (2024). Who speaks through the machine? Generative AI as discourse and implications for management. Critical Perspectives on Accounting, 100, 102761. https://doi.org/10.1016/j.cpa.2024.102761
   
Gillings, M., Kohn, T., & Mautner, G. (2024). The rise of large language models: challenges for Critical Discourse Studies. Critical Discourse Studies, 22(6), 625–641. https://doi.org/10.1080/17405904.2024.2373733

Sachdeva, Pratik, and Tom van Nuenen. "Normative evaluation of large language models with everyday moral dilemmas." Proceedings of the 2025 ACM Conference on Fairness, Accountability, and Transparency. 2025.

van Dijk, T. A. (1993). Principles of Critical Discourse Analysis. Discourse & Society, 4(2), 249–283.