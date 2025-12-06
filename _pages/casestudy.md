---
permalink: /casestudy/
title: "Case Study: Normative Discourse of AI"
author_profile: true
---

# Learning Objectives
- Explain how normative discourse operates within Large Language Models (LLMs).
- Reflect on the dialectic of society and AI.
- Identify how moral and epistemic biases are embedded in LLMs.
- Evaluate the effects of these biases on different stakeholders.


# Introduction

Large Language Models (LLMs) such as GPT, Claude, and Gemini are now integral to global knowledge production. They generate text, summarise ideas, and make moral judgements. While portrayed as objective and value-free, they are not. This case study analyses how these models shape and enforce normative discourses. A normative discourse is a set of moral, cultural, and epsitemological assumptions about what counts as truth, fairness, or reason that is structured through both language, power, and knowledge. Let's explore the ethical implications of these discourses from empirical and theoretical work to understand how LLMs encode moral norms, enact power through knowledge, and shape the boundaries of acceptable knowledge.



# The Issue
LLMs are not value-free. Agbon (2024) argues that generative AI operates through a dual discourse:
1. Technoslutionst discourse: frames AI as a benevolent problem-solver.
2. Generative discourse: the machine's language as shaped by its training data, architecture, and algorithms.

Together, these discourses reproduce existing power relations by privileging certain epistemologies, Western, Anglophone, liberal, techno-rational, while magrginalising others. This can harm groups whose moral frameworks differ from dominant ones, particularly when AI becomes an authority that adjudicates truth, fairness, and decency in online and institutional spaces.

Sachdeva and Van Nuenen (2025) show this empirically. Seven commercial LLMs were asked to judge moral dilemmas, their moral verdicts diverging sharply, that is, LLMs express distinct moralities. We will explore why this happens.

Moving beyond censorship or bias mitigation, the ethical question is whose morality is represented in the discourse.

# What We Know

Large Language Models are built through a multi-stage process each of which introduces risks of ethical and epistemic biases.

LLMs are trained on enormous text datasets drawn from web pages, books, Wikipedia, academic papers, news articles, and social media posts.

According to W3Techs, the internet's "relevant web," a network of webpages whose content is meaningful, is at least 50% in English. ChatGPT's training dataset is 93% English, according to Gillings. Because most digitized and accessible material online is Anglophone and Western, the resulting corpus overrepresents Western liberal, secular, and capitalist worldviews while underrepresenting oral, non-Western, or indigenous epistemologies.

Even when multilingual data are included, the quality and quantity of translations vary drastically, introducing translation bias. English concepts are treated as linguistic and moral “defaults,” while non-English expressions of ethics, religion, or emotion are often flattened or mistranslated. AI models do not critically assess interpretations or hermeneutics of translation. 

Data filtering removes explicit hate speech, violence, or misinformation, which improves safety but also constructs moral boundaries on what is harmful, acceptable, and rational. These judgments reflect the moral frameworks of a limited group of engineers, not global consensus. While on that note, a global consesus is not possible nor should necessarily be the goal. Further problematising this is incorrect or misleading labels. For example, a UK

Pre-Training: Predictive Language Modeling

The model learns to predict the next word (token) in a sequence based on probabilities computed from billions of examples.

This process builds what Agbon (2024) calls a Technical–Epistemic–Linguistic Substrate (TELS): the technical architecture (e.g., Transformer networks), the epistemic logic (data-driven inductivism), and the linguistic norms (grammar and style) that together shape the machine’s “voice.”

Because prediction is guided by statistical frequency rather than truth or moral reasoning, the model tends to reproduce what is most recurrent, not what is most just or true. It operationalizes empiricism without ethics—a pattern that privileges dominant discourse and marginalizes the rare or dissenting one.

Alignment and Reinforcement Learning from Human Feedback (RLHF)

After pre-training, the model undergoes fine-tuning through human feedback. Human annotators rank multiple AI outputs for quality, coherence, or “helpfulness.”

This introduces another layer of normative mediation: human raters, often drawn from specific cultural and linguistic backgrounds, implicitly encode their own moral judgments into the reward function.

The model then learns to favor the style of reasoning and tone preferred by these raters—commonly polite, liberal, Western moral sensibilities (Agbon, 2024).

Sachdeva and Van Nuenen (2025) show that moral divergence among LLMs stems partly from this stage: OpenAI’s alignment process produces reasoning closer to utilitarian individualism, while models trained by Asian or European firms show more collectivist or deontological leanings.

Opaque Evaluation and Post-Training Filtering

Developers perform additional filtering to suppress politically sensitive or “unsafe” topics, yet the criteria for safety are proprietary and undisclosed.

This opacity prevents external auditing and reinforces asymmetric epistemic power—only the companies and engineers truly know what moral and linguistic boundaries the model enforces.

As Koller (2023) notes, this lack of transparency turns language models into “black boxes of ideology”, where discourse itself is algorithmically curated before reaching the public.

## Data Collection
LLMs are trained on enormous text databases scraped from web pages, books, encyclopedias, academic papers, news articles, and social media posts. Since 

# Stakeholders

- Gen AI Users
- Developers
- Marginalised communities
- Policymakers
- Researchers

# Activity

Users will answer receive Am I The Asshole prompts and answer them. Each answer will explain the harm in taking a moral stance, compare to the answers of models, understand why the models differ.

[Activity](/computes_ethics/casestudy/activity/)

**Do not read the section below until you are done with the activity**

When presented with the same scenario, ChatGPT, Gemini, and Claude deliver moral judgments that agree that the father is not the wrongdoer. However, they diverge in the ethical frameworks they implicitly mobilise to justify that conclusion. Examining these differences reveals how each model encodes a distinct moral vocabulary, prioritises different forms of harm, and foregrounds particular social relationships. These divergences matter for AI ethics because they illuminate the value-laden architectures underlying ostensibly neutral judgments.

Claude’s response is the most explicitly grounded in a care ethics perspective, emphasising emotional well-being, psychological safety, and relational harm. Claude treats the 16-year-old daughter’s distress not merely as property loss but as a significant moral injury—“a serious red flag”—and frames the father's action as a necessary response to protect a vulnerable person’s emotional security. Claude interprets the silent treatment the household deploys as an act of emotional manipulation, again centering relational dynamics rather than formal rules. In this way, Claude conceptualizes the household as an affective ecosystem and judges the moral agents according to how well they sustain or harm that ecosystem. This aligns strongly with feminist care ethics traditions, where vulnerability, dependence, and emotional safety constitute primary moral facts.

Gemini offers a different moral grammar, one closer to deontological fairness and property rights. Although it also concludes that the father is morally justified, its justification foregrounds the daughters’ violation of boundaries, improper “borrowing,” and disrespect for personal property. Gemini treats the harm in largely instrumental terms: the cousins took items, caused financial loss, and dismissed clear rules about permission. Its criticism of the wife (“inadequate parent”) is structured around failure to enforce norms rather than failure to empathize. Gemini does acknowledge emotional dynamics, but they appear secondary to rule-based obligations. In this reading, the moral world is structured by enforceable duties—parents must protect their child’s property and privacy; guests must respect household norms—rather than the maintenance of relational well-being.

ChatGPT’s response occupies a middle ground, constructing a hybrid of care ethics and deontological reasoning. It unequivocally prioritizes the minor child’s safety, privacy, and autonomy, but describes this protection in both emotional and rights-based terms. For ChatGPT, the father’s moral justification arises from proportionality (a just response to repeated violations), parental duty (obligation to safeguard a minor), and the principle of consent (taking without permission). This reasoning integrates relational considerations with rule-based obligations, presenting morality as both a matter of protecting the vulnerable and upholding rights. Unlike Gemini, ChatGPT sees the harm as more than just property loss, but unlike Claude, it frames emotional harm as part of a broader landscape of boundary violations rather than the sole moral center.

These three responses illustrate how LLMs encode distinct ethical sensibilities that shape their interpretations of the same event. Claude’s model privileges emotional safety and relational ethics; Gemini foregrounds rules, fairness, and property rights; ChatGPT synthesizes these into a balanced account of parental duty, boundaries, and vulnerability. The differences matter: had the prompt been more ambiguous, or had different stakeholders been harmed, each model’s underlying value structure could plausibly generate divergent outcomes.

For AI ethics, this comparison underscores that LLM judgments are not neutral but are shaped by embedded moral priorities. The models are trained on vast data containing culturally situated moral discourse, and they reproduce those moral logics in patterned ways. Understanding these patterns is crucial for evaluating the reliability, bias, and normativity of AI-generated moral reasoning, especially as such models increasingly mediate interpersonal disputes, institutional decision-making, and public reasoning about harm and responsibility.

# Actions

Lists possible actions, implementation steps, and evaluates them through our six ethical frameworks

# Conclusion

Will choose the best option, flesh out its implementation. Reflect on exercise

# Discussion Questions

1. How do the dual discourses shape the way we perceive LLMs?
2. Is algorithmic neutrality impossible achievable?
3. How can algorithmic control balance protecting users and allowing for moral pluralism?

# Works Cited

Agbon, G. (2024). Who speaks through the machine? Generative AI as discourse and implications for management. Critical Perspectives on Accounting, 100, 102761. https://doi.org/10.1016/j.cpa.2024.102761
   
Gillings, M., Kohn, T., & Mautner, G. (2024). The rise of large language models: challenges for Critical Discourse Studies. Critical Discourse Studies, 22(6), 625–641. https://doi.org/10.1080/17405904.2024.2373733

Sachdeva, Pratik, and Tom van Nuenen. "Normative evaluation of large language models with everyday moral dilemmas." Proceedings of the 2025 ACM Conference on Fairness, Accountability, and Transparency. 2025.