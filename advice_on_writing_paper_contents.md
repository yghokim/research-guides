# **Advice on Writing Paper Contents**

## Formulating Research Questions

### Qualities of RQs

Research questions should be…

1. **Novel**: Your questions shouldn’t have been answered elsewhere.

2. **Feasible**: You should be able to answer your questions. Consider the time budget, your expertise, and any other constraints on executing the method.

3. **Challenging**: You should be tackling sufficiently challenging questions. By answering them, you should make a significant contribution to HCI.

4. **Specific**: Be candid about the level of detail you can address. Avoid both overclaiming (i.e., phrasing your questions too generally) and underclaiming (i.e., phrasing them so that they cover only part of what you actually contribute).

### RQs vs. Research Goals/Aims

Most papers declare their intent in the Introduction as an **aim** — *“In this work, we aim to…,” “we investigate…”* — and some additionally pose **research questions** that a specific study answers. Every project should establish its research questions internally; what follows concerns which of the two the paper states explicitly.

1. **Not every paper needs to explicitly state its research questions.** Define them during the research process — they are how you and your coauthors establish what the study addresses. Whether to state them in the paper is a separate decision: most of our group’s papers state only an aim, and present RQs only where a study is designed to answer them one by one.

2. **The aim covers the paper; an RQ belongs to a study.** *LingoQ* \[CHI 2026\] states both in the Introduction, but scopes them differently:

   * Aim: *Building on these insights, we $\color{red}{\text{investigate whether}}$ generating study materials of mobile language learning apps directly from work tasks can further enhance language learning and foster long-term engagement.* \[Introduction\]
   * RQs: *Through the $\color{red}{\text{deployment study}}$, with a focus on feasibility, we explore the following research questions: RQ1–How do EFL workers engage in and sustain their English learning when using study materials generated from their work context? RQ2–How does studying English with work-related content influence workers’ learning outcomes and self-efficacy? and RQ3–How do EFL workers perceive the value of studying English with questions generated from work-related content?* \[Introduction\]

3. **Pick the verb in the aim to match what the study can settle.** Reviewers hold the Findings to it; see the verb-choice item in the [Academic Writing Guide](./advice_on_academic_writing.md).

   * *To understand the benefits and challenges of deploying conversational AI leveraging LLMs for public health, we $\color{red}{\text{explore}}$ the case of CLOVA CareCall…* \[CareCall, CHI 2023, Introduction\]
   * *In this work, we $\color{red}{\text{investigate}}$ ways to empower individuals to take greater control of the reflective process of their personal challenges…* \[ExploreSelf, CHI 2025, Introduction\]
   * *In this study, we therefore $\color{red}{\text{seek to understand}}$ the utility of LTM for public health monitoring, with particular attention to self-disclosure.* \[CareCall-LTM, CHI 2024, Introduction\]
   * *Through a two-week deployment study with 10 autistic adolescent-parent dyads, we $\color{red}{\text{examine}}$ how Autiverse supports autistic adolescents to organize their daily experience and emotion.* \[Autiverse, CHI 2026, Abstract\]

4. **“How can we design…” is an aim, not a research question.** No data answer it, so leave it declarative; if you want a question, ask what the study can settle.

   * *In this work, we $\color{red}{\text{aim to design}}$ a system that supports translation of song lyrics and gloss creation for song-signing in a more accessible manner.* \[ELMI, CHI 2025, Introduction\]
   * *With this LLM-driven chatbot, we aim to answer the following research question: $\color{red}{\text{How feasible is}}$ an LLM-driven chatbot in prompting children to share their emotions about personal events?* \[ChaCha, CHI 2024, Introduction\]

5. **A numbered RQ owes the reader an explicit answer in the Findings.** One subsection per question, numbering mirrored. Keep them few and comparable in scope — if one question takes half the paper and another a paragraph, they are not siblings. An aim is discharged differently: by the contributions as a whole.

6. **In a multi-study paper, state one aim in the Introduction and open each study with its own.** *ExploreSelf* \[CHI 2025\]:

   * *In this work, we investigate ways to empower individuals to take greater control of the reflective process of their personal challenges…* \[Introduction\]
   * *…our goal was to design a system that enables individuals to explore their challenges at their own pace, without clinical oversight.* \[Introduction\]
   * *we aimed to gain a nuanced understanding of the challenges of providing effective guidance…* \[Formative Interviews\]

## Writing the Title

1. **Calibrate the ambition of the title to the evidence the paper can show.** A title keyword is what reviewers fixate on. If the title promises an outcome you did not measure, you will be judged on exactly that. Pin down the scope of what you claim to promote in a “Promoting XXX through …” title before fixing it, because that XXX defines what you must evaluate. Conversely, when the results came out strongly significant, let the title be correspondingly ambitious.

    *MyMove: $\color{red}{\text{Facilitating}}$ Older Adults to Collect In-Situ Activity Labels on a Smartwatch with Speech* \[CHI 2022\] commits you to showing that the labeling task got easier, while *TimeAware: Leveraging Framing Effects to $\color{red}{\text{Enhance}}$ Personal Productivity* \[CHI 2016\] commits you to showing that productivity actually improved. Pick the verb whose bar your study clears.

2. **Choose the leading verb to match the kind of contribution you are claiming.** “$\color{red}{\text{Supporting}}$ X” puts the weight on the artifact, while “$\color{red}{\text{Understanding How}}$ …” claims the empirical contribution — pick the one the paper actually delivers. Be aware that “Supporting X” is also generic: beyond naming the target user it carries almost no information, so it is rarely the strongest frame. Check number agreement across the title’s nouns as well: if *models* is plural, *assistants* should be too.

    * *ELMI: Interactive and Intelligent Sign Language Translation of Lyrics for Song Signing* \[CHI 2025\] leads with the artifact.  
    * *$\color{red}{\text{Understanding}}$ the Benefits and Challenges of Deploying Conversational AI Leveraging Large Language Models for Public Health Intervention* \[CHI 2023\] leads with the empirical question.  
    * *$\color{red}{\text{Understanding}}$ the Impact of Long-Term Memory on Self-Disclosure with Large Language Model-Driven Chatbots for Public Health Intervention* \[CHI 2024\] does the same one project later, and names the exact mechanism it examined.

3. **Spend the words of a title economically and keep redundancy to a minimum.** Every word should earn its place, so drop the ones another word already implies. Length itself is not the problem; a word that restates what its neighbor already says is.

    * **Don’t:** $\color{red}{\text{Guidance}}$ through Social Narratives — guiding is by definition what a social narrative is for.  
      **Don’t:** A Diary for $\color{red}{\text{Recording Daily Routines}}$ — a diary is already that.

    * **Do:** *ChaCha: Leveraging Large Language Models to Prompt Children to Share Their Emotions about Personal Events* \[CHI 2024\] — a long title, but nothing in it is recoverable from anything else: the technology, the interaction, the population, and the content each appear exactly once.

4. **Name the interactions the system supports, and let the terms scan.** Choose the nouns that foreground what people do with the system (e.g., $\color{red}{\text{exploration and reflection}}$). A pair that shares a suffix gives the title an internal rhyme and makes it easier to remember.

    * *ExploreSelf: Fostering User-driven $\color{red}{\text{Exploration and Reflection}}$ on Personal Challenges with Adaptive Guidance by Large Language Models* \[CHI 2025\] — the shared *-tion* ending makes the pair scan and stick.  
    * *DataHalo: A Customizable Notification Visualization System for $\color{red}{\text{Personalized and Longitudinal}}$ Interactions* \[CHI 2023\] — the same move with a shared *-al* ending, naming the two properties of the interaction that matter.  
    * *AACessTalk: Fostering Communication between Minimally Verbal Autistic Children and Parents with $\color{red}{\text{Contextual Guidance and Card Recommendation}}$* \[CHI 2025\] — both mechanisms are named outright, so a reader knows what the system actually does before opening the paper.  
    * *Autiverse: Eliciting Autistic Adolescents’ Daily Narratives through $\color{red}{\text{AI-guided Multimodal Journaling}}$* \[CHI 2026\] — a single compound carries the activity, the modality, and who guides it.  
    * *ChaCha: Leveraging Large Language Models to $\color{red}{\text{Prompt Children to Share Their Emotions}}$ about Personal Events* \[CHI 2024\] — here the interaction is a verb phrase rather than a noun, which suits a system whose whole job is to elicit something.

## Synthesizing Related Work Sections

1. **Rule of thumb:** The purpose of a related work section is to prepare readers to grasp the gist of your method, evaluation, and discussion, not to demonstrate your effort in reading a bunch of related papers.

2. **Try to be concise.** For typical system papers, around one page in double-column format would suffice. 

3. **Be as specific as possible**. You don’t have to consider audiences far outside the domain of your paper. If your paper is about Personal Informatics, you don’t have to explain what Personal Informatics is. Start directly with a closely relevant sub-domain or concept.

4. Start with prior work in the broadest scope and end with the most relevant one. If you are writing a system paper, a typical organization would be (1) the domain challenges and (2) the core technology \+ domain examples that employed the technology.

## Discussing Limitations and Future Work

1. **Rule of thumb: Think carefully about whether you can avoid explicitly writing a limitation section. Avoid placing a limitation section at the end of the Discussion** (although we often fail to do so when reviewers request it)**.**

   * If all limitations are about the method (e.g., recruitment biases), place the Limitations section as the last subsection of the Method.

   * If you can, frame the limitations of your system/investigation as a call for future work in subsections of the Discussion section, instead of having an explicit “Limitation and Future Work” section.

     * **A paper that doesn’t have any limitations section:** Young-Ho Kim, Bongshin Lee, Arjun Srinivasan, and Eun Kyoung Choe. 2021\. Data@Hand: Fostering Visual Exploration of Personal Data on Smartphones Leveraging Speech and Touch Interaction. In Proceedings of the 2021 CHI Conference on Human Factors in Computing Systems (CHI '21). Association for Computing Machinery, New York, NY, USA, Article 462, 1–17. [https://doi.org/10.1145/3411764.3445421](https://doi.org/10.1145/3411764.3445421)

2. **Study limitations are not flaws**. If your study contains flaws, such as an unfair condition design in a comparative study, we must re-run the study. **Study limitations typically arise from methodological compromises you had to make due to external constraints**, such as budget, resources, or potential risks. These compromises could include noise in the dataset, recruitment bias (location, age, or background), and omitted system features. When reporting and discussing such limitations, focus on (1) how the results might differ under ideal conditions and (2) why the compromises do not critically undermine your contributions. Call for further investigation only when it is interesting.

3. Every work has limitations. You **don’t have to be defensive** when reporting them.

4. **Distinguish the future work that belongs in Limitations from the future work that belongs in the Discussion.** These are two different kinds of future work, and they live in different places. A “Limitations and Future Work” section takes only the work that follows from this study’s own limits — what still needs examining before the findings generalize, what a different sample or a longer deployment would settle. Future work that envisions where the field should go belongs in the Discussion’s own subsections, where it reads as ambition rather than as an apology. Placing a visionary direction next to your limitations makes it look like another shortcoming.

## What Should Come in a Discussion Section

1. Rule of thumb 1: **Don’t introduce new information in the Discussion section**; everything you discuss should be grounded in the Results section.

2. Rule of thumb 2: **Only discuss insights or predictions that directly emerged from the current study;** don’t discuss anything that could be said by someone who did not conduct the study.

3. **The first subsections usually cover how your study answered the RQs.** Answering an RQ means stating the answer as a claim — what you now know — not replaying the results that produced it. Point back to the relevant findings, then spend the subsection on what they mean.

4. **Make every subsection deliver a takeaway.** A subsection that merely summarizes the section it discusses leaves readers unsure what point you wanted to make. End each one with the insight its heading promised. Where the Results are dense but the Discussion thin, spend the space explaining *why* the differences appeared.

5. **Keep the Results dry and factual, and let the Discussion carry interpretation, background, and future work.** Results wordiness usually comes from mixing in interpretation or background. Too much interpretation in the Results reliably draws a reviewer comment asking you to separate the two. A subsection whose job is interpreting results should not drift into future work either.

6. **Reach beyond your data only when the literature licenses the leap.** Discuss only the implication your findings actually support; the same restraint applies to reassuring claims, such as arguing that the system is safe. To claim a longer-term effect you did not measure, first cite literature establishing your measure as a proxy for it.

7. **Discuss where your findings diverge from prior work, your design rationale, or expert expectations.** Name the tension outright instead of leaving it unaddressed, and interpret any result that contradicts what your design or your domain experts assumed. Reporting a score on a standard instrument obliges you to compare with prior studies that used the same scale — do it before a reviewer does.
