# **Academic Writing Guide**

**Young-Ho Kim**

Leader, HCI Group @ NAVER AI Lab

**Target readers?** Interns and junior researchers in our HCI group.

**Why was this guide written?** The internship is super intensive, and you are already an experienced academic writer. You have developed your own writing style and file management conventions, which may conflict with those of your mentor. To better synchronize our writing styles and minimize mismatches across text written by different authors, I provide this guide.

# General Writing Tips

1. Avoid stating opinions as “We **think** A.” Instead, express your thoughts directly, or use more assertive words such as “insist” or “argue.”

2. Avoid using adjectives like “**better**” and “**good**” without clarifying in which aspect. In most cases, you can avoid these words by directly describing which aspect was good or better, and at what: 

   * **Don’t:** System A was $\color{red}{\textsf{better}}$ than System B.  
     **Do:** System A yielded $\color{red}{\textsf{faster completion times and higher accuracy}}$ than System B.

3. Use **en dashes** (two hyphens \-- in LaTeX) properly when indicating a range. Students often mistakenly use a hyphen where an en dash belongs:

   * **Don’t:** We recruited 13 participants $\color{red}{\textsf{(P1-13)}}$.  
     **Do:** We recruited 13 participants $\color{red}{\textsf{(P1–13)}}$.

4. Use en dashes for compound adjectives consisting of two nouns. Researchers often mistakenly use a hyphen to connect the two:

   * **Don’t:** $\color{red}{\textsf{Human-computer}}$ interaction  
     **Do:** $\color{red}{\textsf{Human–Computer}}$ Interaction

   * **Don’t:** $\color{red}{\textsf{Parent-child}}$ communication

   * **Do:** $\color{red}{\textsf{Parent–child}}$ communication

5. For numbered lists, **always use Arabic numerals enclosed in parentheses on both sides**. For instance, use ‘$\color{red}{\textsf{(1)}}$’ instead of ‘1\)’ or ‘(i).’ Numbered lists with unclosed parentheses look incomplete.

6. Provide **objective** information whenever possible, especially when reporting **Results**. Provide **numbers** if you have them. Minimize the use of “some” and “many,” especially when you report the number of participants who mentioned something in the interviews.

   * **Don’t**: $\color{red}{\textsf{Some}}$ participants reported that …  
     **Do:** $\color{red}{\textsf{Five participants (P1, P4, P7, P18, P24)}}$ reported that…

   * **Don’t**: $\color{red}{\textsf{Most}}$ participants reported that …  
     **Do:** $\color{red}{\textsf{17 out of 20 (85\%)}}$ participants reported that…

7. Distinguish between **citations as a backup for a claim** and **citations as an example**.

   * **Citation as a backup**: You are **citing a claim** made in the cited work to back up your own claim or a specific concept in your sentence. Put the citation directly after the part you want to back up, without parentheses.

     * Similarly, parents play an essential role in supporting how children identify and express their emotions $\color{red}{\textsf{[10, 37]}}$.

     * Studies demonstrated that when chatbots remember information across multiple sessions, such as users’ names or preferences, people perceive them as empathetic $\color{red}{\textsf{[29, 52, 63]}}$ and conscientious $\color{red}{\textsf{[8, 17]}}$.

   * **Citation as an example**: You are citing **the work itself as an example** of your claim. Wrap the citations in parentheses and prefix them with “*e.g.*”

     * The recent advance of pre-trained LLMs $\color{red}{\textsf{(e.g.,}}$ GPT \[8, 61\], PaLM \[15\], LLaMA \[77\], LaMDA \[76\], HyperCLOVA \[46\]$\color{red}{\textsf{)}}$ has presented new opportunities for…

     * One common approach is to include summarized information of the conversation history instead of a raw knowledge base $\color{red}{\textsf{(e.g., [2, 41, 75])}}$. 

8. Clearly distinguish between **present** and **past** tenses in the main text.

   * Present tense: When you report **what you do in this paper**.

     * To this aim, we $\color{red}{\textsf{propose}}$ …  
     * In this work, we $\color{red}{\textsf{explore}}$ …  
     * In this section, we $\color{red}{\textsf{describe}}$ …

   * Past tense: When you report **what you or your participants did as part of the method**.

     * We $\color{red}{\textsf{designed and developed}}$ MindfulDiary, …  
     * We $\color{red}{\textsf{recruited}}$ 18 participants from …  
     * We $\color{red}{\textsf{conducted}}$ an exploratory user study …  
     * From the study, we $\color{red}{\textsf{observed}}$ that …

9. ‘Related work’, ‘literature’, and ‘research’ are uncountable (mass) nouns. In most cases, they are conventionally used in the singular form. Grammatically, ‘related works’ is fine, but we seldom use that form.

10. When you describe the actions of researchers, use **verbs appropriately**. Choose verbs that accurately reflect the scope, depth, and intent of the research activity, and avoid using them interchangeably.

    * **Explore**: When the study is open-ended and aims to gain an initial understanding.

      * *We $\color{red}{\textsf{explore}}$ the feasibility and challenges with older adults in collecting activity labels… \[MyMove, 2023\]*

    * **Examine**: When the study is guided by a defined focus, clear research questions, or hypotheses.

      * *Quant: To $\color{red}{\textsf{examine}}$ the effect of framing on individuals’ productivity, we compared two versions of TimeAware. \[TimeAware, 2016\]*

      * *Qual: Through an exploratory study with 19 participants, we $\color{red}{\textsf{examine}}$ how participants explore and reflect on personal challenges using ExploreSelf. \[ExploreSelf, 2025\]*

    * **Investigate**: When the study seeks to uncover underlying mechanisms or causes that explain why a specific phenomenon occurs. But in practice, many HCI papers use this term interchangeably with ‘explore’ or ‘examine.’ 

      *  *We $\color{red}{\textsf{investigate}}$ the factors that contributed to participants’ disengagement over time.*

    * **Assess**: When you are evaluating something, usually driven by quantitative metrics or measurements.

      * *To $\color{red}{\textsf{assess}}$ the difference among the experimental conditions, we conducted Kruskal-Wallis tests over the four rating questions.* \[GPT-Chatbot, 2024\]

      * *A set of call logs with 100 users (721 sessions) was classified using Positive-Neutral-Negative labels, designed to $\color{red}{\textsf{assess}}$ user satisfaction with conversational agents.* \[CareCall Long-term Memory, 2024\]

11. Be aware of the **level of certainty** when you report the **interpretation** of the findings in an exploratory manner. Choose ***subjects*** and ***verbs*** appropriately:

    * **Low certainty**: When you strongly imply that the statement is mostly based on your interpretation or suspicion, with little or no data to back it up.

      * We $\color{red}{\textsf{suspect}}$ that…

      * Participants $\color{red}{\textsf{appeared to}}$… \=\> Usually when you interpret a pattern from the qualitative interviews.

      * These findings $\color{red}{\textsf{may reflect}}$…

    * **Moderate certainty**: When the statement is still your interpretation, but you have some data points to back it up.

      * The results $\color{red}{\textsf{suggest}}$ that… \=\> You can generally use this

      * The results $\color{red}{\textsf{indicate}}$ that… \=\> When the interpretation is more obvious than ‘suggest’

    * **High certainty**: Caution\! Use the following expressions only when they are justified by numerical outcomes or by very prevalent patterns of repeated observations:

      * *The results $\color{red}{\textsf{show}}$ that participants’ self-efficacy increased significantly after the intervention.*

      * The results $\color{red}{\textsf{imply}}$ that… \=\> Stronger than it looks; use it only when the logical connection between the evidence and the conclusion is genuinely tight.

      * The findings $\color{red}{\textsf{demonstrate}}$ that…

13. **Don’t use “say” to attribute what participants or prior authors stated.** It reads as colloquial. Use *remark*, *note*, *state*, *mention*, *stress*, *emphasize*, or *describe* instead, choosing the one whose force matches the strength of the statement, and don’t repeat the same verb across consecutive quotes.

    * **Don’t:** P7 $\color{red}{\textsf{said}}$ “I stopped checking it after a week.”  
      **Do:** P7 $\color{red}{\textsf{remarked,}}$ “I stopped checking it after a week.”

14. **Minimize be-verbs** and recast those sentences around a precise action verb. Plain “A is B” sentences read as flat to English readers and make the prose look unpolished.

    * **Don’t:** The main reason for the disengagement $\color{red}{\textsf{was}}$ the lack of feedback.  
      **Do:** The lack of feedback $\color{red}{\textsf{drove}}$ the disengagement.

15. **When a sentence opens with “this” pointing back at the previous sentence, ask whether “this + noun” would say it better.** A bare “this” leaves readers to reconstruct the referent themselves, and after a long or quote-heavy sentence they often reconstruct the wrong one. Naming the referent costs one word, and the noun you choose usually does interpretive work at the same time — it tells readers what *kind* of thing the previous sentence established.

    * *$\color{red}{\textsf{This growing clarity}}$ allowed P13 to “confidently decide when to explore a theme more deeply and when to move on to a new one”…* \[ExploreSelf, CHI 2025\]  
    * *$\color{red}{\textsf{This meticulous process}}$ highlights the challenge of aligning signs with the music, a task that demands significant time and effort.* \[ELMI, CHI 2025\]  
    * *$\color{red}{\textsf{This gap}}$ is consequential because the unique characteristics of autistic adolescents pose barriers to practice journaling themselves…* \[Autiverse, CHI 2026\]  
    * *$\color{red}{\textsf{This procedure}}$ was implemented to ensure active monitoring and communication.* \[MindfulDiary, CHI 2024\]

16. **Tone down absolute and extreme words.** Strong words like *imperfect*, *useless*, and *blind* make the message look aggressive rather than strong. To make a point forcefully, unpack the precise intent in softer wording instead of reaching for the harsh term.

    * **Don’t:** The existing approach is $\color{red}{\textsf{useless}}$ for this population.  
      **Do:** The existing approach $\color{red}{\textsf{offers little support}}$ for this population.

17. **Check whether a paragraph’s wrap-up sentence is redundant with what comes before it.** Closing every paragraph with $\color{red}{\textsf{Taken together}}$…, $\color{red}{\textsf{Together}}$…, or $\color{red}{\textsf{This suggests}}$... leaves the point stated twice — once at the top of the paragraph and again at the bottom. Put the point in one place. A summarizing sentence at the end of a **section/subsection** is fine.

18. Call a scale a **Likert scale** only when it measures the *degree of agreement* (*Strongly agree*–*Strongly disagree*). For a frequency or any other non-agreement scale, say **rating scale**, or simply name the **categories** the participant chose among.

    * **Don’t:** We measured frequency of use on a five-point $\color{red}{\textsf{Likert scale}}$.  
      **Do:** We measured frequency of use on a five-point $\color{red}{\textsf{rating scale}}$.  
      **Do:** Participants chose among $\color{red}{\textsf{five frequency categories}}$, from *Never* to *Every day*.

19. **Try to make each findings section header state the finding itself rather than the topic it covers.** A header that conveys ‘which aspect of what’ — the message the data support — carries more than a bare topic label or a UI feature name. The payoff is cumulative: when every header states a message, a reader who skims only the headers still follows the key messages of your findings, and that is how many reviewers first read a paper.

    * **Don’t:** $\color{red}{\textsf{Use of the Reflection Panel}}$  
      **Do:** $\color{red}{\textsf{Reflection surfaced overlooked patterns}}$

20. **Avoid orphaned figures and tables.** Every figure and every table must be referred to at least once in the main text; a float nobody cites is orphaned.


# LaTeX Convention

Moved to a separate document: [LaTeX Convention](./latex_convention.md) — Overleaf project management and LaTeX writing guides.

# Formulating Research Questions

## Qualities of RQs

Research questions should be…

1. **Novel**: Your questions shouldn’t have been answered elsewhere.

2. **Feasible**: You should be able to answer your questions. Consider the time budget, your expertise, and any other constraints on executing the method.

3. **Challenging**: You should be tackling sufficiently challenging questions. By answering them, you should make a significant contribution to HCI.

4. **Specific**: Be candid about the level of detail you can address. Avoid both overclaiming (i.e., phrasing your questions too generally) and underclaiming (i.e., phrasing them so that they cover only part of what you actually contribute).

## RQs vs. Research Goals/Aims

# Advice on Writing Paper Contents

## Writing the Title

1. **Calibrate the ambition of the title to the evidence the paper can show.** A title keyword is what reviewers fixate on. If the title promises an outcome you did not measure, you will be judged on exactly that. Pin down the scope of what you claim to promote in a “Promoting XXX through …” title before fixing it, because that XXX defines what you must evaluate. Conversely, when the results came out strongly significant, let the title be correspondingly ambitious.

    *MyMove: $\color{red}{\textsf{Facilitating}}$ Older Adults to Collect In-Situ Activity Labels on a Smartwatch with Speech* \[CHI 2022\] commits you to showing that the labeling task got easier, while *TimeAware: Leveraging Framing Effects to $\color{red}{\textsf{Enhance}}$ Personal Productivity* \[CHI 2016\] commits you to showing that productivity actually improved. Pick the verb whose bar your study clears.

2. **Choose the leading verb to match the kind of contribution you are claiming.** “$\color{red}{\textsf{Supporting}}$ X” puts the weight on the artifact, while “$\color{red}{\textsf{Understanding How}}$ …” claims the empirical contribution — pick the one the paper actually delivers. Be aware that “Supporting X” is also generic: beyond naming the target user it carries almost no information, so it is rarely the strongest frame. Check number agreement across the title’s nouns as well: if *models* is plural, *assistants* should be too.

    * *ELMI: Interactive and Intelligent Sign Language Translation of Lyrics for Song Signing* \[CHI 2025\] leads with the artifact.  
    * *$\color{red}{\textsf{Understanding}}$ the Benefits and Challenges of Deploying Conversational AI Leveraging Large Language Models for Public Health Intervention* \[CHI 2023\] leads with the empirical question.  
    * *$\color{red}{\textsf{Understanding}}$ the Impact of Long-Term Memory on Self-Disclosure with Large Language Model-Driven Chatbots for Public Health Intervention* \[CHI 2024\] does the same one project later, and names the exact mechanism it examined.

3. **Spend the words of a title economically and keep redundancy to a minimum.** Every word should earn its place, so drop the ones another word already implies. Length itself is not the problem; a word that restates what its neighbor already says is.

    * **Don’t:** $\color{red}{\textsf{Guidance}}$ through Social Narratives — guiding is by definition what a social narrative is for.  
      **Don’t:** A Diary for $\color{red}{\textsf{Recording Daily Routines}}$ — a diary is already that.

    * **Do:** *ChaCha: Leveraging Large Language Models to Prompt Children to Share Their Emotions about Personal Events* \[CHI 2024\] — a long title, but nothing in it is recoverable from anything else: the technology, the interaction, the population, and the content each appear exactly once.

4. **Name the interactions the system supports, and let the terms scan.** Choose the nouns that foreground what people do with the system (e.g., $\color{red}{\textsf{exploration and reflection}}$). A pair that shares a suffix gives the title an internal rhyme and makes it easier to remember.

    * *ExploreSelf: Fostering User-driven $\color{red}{\textsf{Exploration and Reflection}}$ on Personal Challenges with Adaptive Guidance by Large Language Models* \[CHI 2025\] — the shared *-tion* ending makes the pair scan and stick.  
    * *DataHalo: A Customizable Notification Visualization System for $\color{red}{\textsf{Personalized and Longitudinal}}$ Interactions* \[CHI 2023\] — the same move with a shared *-al* ending, naming the two properties of the interaction that matter.  
    * *AACessTalk: Fostering Communication between Minimally Verbal Autistic Children and Parents with $\color{red}{\textsf{Contextual Guidance and Card Recommendation}}$* \[CHI 2025\] — both mechanisms are named outright, so a reader knows what the system actually does before opening the paper.  
    * *Autiverse: Eliciting Autistic Adolescents’ Daily Narratives through $\color{red}{\textsf{AI-guided Multimodal Journaling}}$* \[CHI 2026\] — a single compound carries the activity, the modality, and who guides it.  
    * *ChaCha: Leveraging Large Language Models to $\color{red}{\textsf{Prompt Children to Share Their Emotions}}$ about Personal Events* \[CHI 2024\] — here the interaction is a verb phrase rather than a noun, which suits a system whose whole job is to elicit something.

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

# Checklist for Finalizing a Draft

Congratulations on getting a submittable version of the paper. If you have time to put the final touches on your draft, this is the right moment to further strengthen the impression that the work is complete. Here are some steps you should go through, at the latest when you prepare the camera-ready version.

### **Entire Manuscript**

1. Fix typos, especially in the Abstract and Introduction. Typos on the first page critically affect reviewers’ impressions.

2. Check the consistency of conventions for words, phrases, and terms. Inconsistencies arise when multiple authors have edited the text and you have not had a chance to review it thoroughly. Here are some common phrases that different authors may use differently. The red text indicates my preference:

   1. ‘users’ vs ‘$\color{red}{\textsf{people}}$’

   2. ‘$\color{red}{\textsf{et al.}}$’ vs ‘and colleagues’

   3. $\color{red}{\textsf{American English}}$ vs British English (and sometimes vs Konglish…)

   4. Present tense vs $\color{red}{\textsf{past tense}}$ for stating what we’ve done (But NLP venues conventionally use the present tense)

3. Check the consistency of wording between the **figure/table captions** and the **main text**.

4. Remove dangling words/fragments in all paragraphs. For example:

   ![][image2]

   The word ‘events’ sits alone on the last line of the paragraph. Revise the paragraph to add words or shorten the text so that the last line contains more than two words.

### **Section Headers**

5. Check the consistency of capitalization across subsection headers. People especially make mistakes in **subsubsection** headers.

### **Tables**

6. Check the consistency of **capitalization**, especially in columns denoting a category.

7. Check the consistency of **punctuation**, especially in columns denoting descriptions. Decide consistently whether to end descriptions with a period. 

### **Reference**

8. Be consistent with the capitalization of paper titles. **I recommend capitalizing all words**, regardless of how the paper was published.

9. Be consistent with the convention for **the authors’ middle names**—that is, whether to include a period: e.g., Daniel $\color{red}{\textsf{A}}$ Epstein vs. Daniel $\color{red}{\textsf{A.}}$ Epstein.

10. For arXiv papers, check whether an accepted version exists, especially for papers in ML and AI venues. For the camera-ready version, check again whether any of the arXiv papers have since been accepted at a venue.

### **Acknowledgement**

11. Don’t forget to acknowledge all the people who contributed to the paper. These typically include funders (research grants, fellowships, etc.), people you sought advice from, people who gave constructive criticism (whether reviewers or not), and people who require copyright attribution. Double-check with the corresponding author, too. 

# 

# Resources

## Books on Writing 

Ask Young-Ho if you want to read one.

1. **Bugs In Writing (Lyn Dupre)** \- discontinued.

   * [https://www.amazon.com/BUGS-Writing-Revised-Guide-Debugging/dp/020137921X](https://www.amazon.com/BUGS-Writing-Revised-Guide-Debugging/dp/020137921X)

2. **Style: Lessons in Clarity and Grace (Williams, Bizup)**

   * [https://www.amazon.com/Style-Lessons-Clarity-Grace-12th/dp/0134080416/ref=sr\_1\_1?crid=3EL2Z5I2PHH1I\&dib=eyJ2IjoiMSJ9.0QR5cWqQ\_fvRa-CwIDU5D5FjRIDftm0uiu3FaQPEetlCH5hvVPEF\_8qn5IndC9bJ3pKa2NYHy9bKy4GbIEHf4ZGOBwcQ9Os3JCiDSiUQH4sFngnIStKlh7PTEXph0EnsMDC5xhUlJO\_772S3eIbKmj5AUNVfrd1k5PVRLoELTEnlB8fz3SayeZIDToQtL1ehf9T01HI8un8m2VK57jVK80VYKuQnVHA1yQ4zir2oK9g.d0TWi4W6yBm7qM4XS5Gfcl0cwWP\_NvQwWAtGSwiwTi0\&dib\_tag=se\&keywords=Style%3A+Lessons+in+Clarity+and+Grace\&qid=1708921992\&s=books\&sprefix=style+lessons+in+clarity+and+grace+%2Cstripbooks%2C255\&sr=1-1](https://www.amazon.com/Style-Lessons-Clarity-Grace-12th/dp/0134080416/ref=sr_1_1?crid=3EL2Z5I2PHH1I&dib=eyJ2IjoiMSJ9.0QR5cWqQ_fvRa-CwIDU5D5FjRIDftm0uiu3FaQPEetlCH5hvVPEF_8qn5IndC9bJ3pKa2NYHy9bKy4GbIEHf4ZGOBwcQ9Os3JCiDSiUQH4sFngnIStKlh7PTEXph0EnsMDC5xhUlJO_772S3eIbKmj5AUNVfrd1k5PVRLoELTEnlB8fz3SayeZIDToQtL1ehf9T01HI8un8m2VK57jVK80VYKuQnVHA1yQ4zir2oK9g.d0TWi4W6yBm7qM4XS5Gfcl0cwWP_NvQwWAtGSwiwTi0&dib_tag=se&keywords=Style%3A+Lessons+in+Clarity+and+Grace&qid=1708921992&s=books&sprefix=style+lessons+in+clarity+and+grace+%2Cstripbooks%2C255&sr=1-1)

3. **On Writing Well: The Classic Guide to Writing Nonfiction (William Zinsser)**

   * [https://www.amazon.com/Writing-Well-Classic-Guide-Nonfiction/dp/0060891548/ref=sr\_1\_1?crid=38FKP6U39EJ3E\&dib=eyJ2IjoiMSJ9.iNIAcvcj5MRwcIrUvw9dgfI3aUApSwDWkZpR4EUwZX34Mhao53UgRHzJODqnHmFXZvB9uw0nA0VC9C2bUFaBQO5iPSuYuByLW4HPLqAxgizeku1K3GrElYWb1phR-HdsqVDgG7H1H7HHDshBRJgZdMX93vy-fBInM4u849e7FhO3laxRLjZXAmuNI1dWls9mimh\_S8Aq4Hzq41J-Y80XPiQ36SU9h5hSlQ\_jnILDb5M.Kg8x3Bx8-ho-CGbV6EhIzZlMKS\_TQRIQP-gnHkI1StI\&dib\_tag=se\&keywords=On+Writing+Well\&qid=1708922063\&s=books\&sprefix=on+writing+well%2Cstripbooks%2C303\&sr=1-1](https://www.amazon.com/Writing-Well-Classic-Guide-Nonfiction/dp/0060891548/ref=sr_1_1?crid=38FKP6U39EJ3E&dib=eyJ2IjoiMSJ9.iNIAcvcj5MRwcIrUvw9dgfI3aUApSwDWkZpR4EUwZX34Mhao53UgRHzJODqnHmFXZvB9uw0nA0VC9C2bUFaBQO5iPSuYuByLW4HPLqAxgizeku1K3GrElYWb1phR-HdsqVDgG7H1H7HHDshBRJgZdMX93vy-fBInM4u849e7FhO3laxRLjZXAmuNI1dWls9mimh_S8Aq4Hzq41J-Y80XPiQ36SU9h5hSlQ_jnILDb5M.Kg8x3Bx8-ho-CGbV6EhIzZlMKS_TQRIQP-gnHkI1StI&dib_tag=se&keywords=On+Writing+Well&qid=1708922063&s=books&sprefix=on+writing+well%2Cstripbooks%2C303&sr=1-1)

## Tips by HCI Researchers

1. How To Write A Literature Review (Saul Greenberg) [https://pages.cpsc.ucalgary.ca/\~saul/wiki/pmwiki.php/Chapter1/HowToWriteALiteratureReview](https://pages.cpsc.ucalgary.ca/~saul/wiki/pmwiki.php/Chapter1/HowToWriteALiteratureReview)  
2. How to write better discussions for your HCI study (Daniel Buschek) [https://dbuschek.medium.com/how-to-write-better-discussions-for-your-hci-study-be851092f351](https://dbuschek.medium.com/how-to-write-better-discussions-for-your-hci-study-be851092f351)  
3. Prof. Tony Tang’s Resources (Many) [https://hcitang.github.io/resources/](https://hcitang.github.io/resources/)


[image2]: <data:image/png;base64,iVBORw0KGgoAAAANSUhEUgAAAb4AAAB+CAYAAABbEnTpAAA0VElEQVR4Xu2defRtY/3H+6OlQqlE0jWEzIqrJJkjmccMoWu4aDDLkFwuN1OoWOoautfFL2S2yszKmF/oYpF0V9c1LCQrpEWx6Px+r6337rM/3+fZ53y/33PO95x7Pq+1zjrPtJ952Pt59v583tPoIz7wgQ94p4Ltt9++MWfOHO/cEv/+978bU6dObfz973/3XgVvvPFG46mnnvLOJTNmzGi89NJLFbfXX3+98fbbb1fcWoX8XH755dn8NOO8887zTo33vOc9Ffv666/fmDRpUsWtGVdddZV3asr06dO9U8nv/vd3jdtuu807F6TK0ApPPPFEEa+FvpHrN5bLLrtsWG3WSjvRJ2fOnOmda5k1a1bjzjvv9M6N6667zjsFQTBCqjNiMFfCwsdELRZddNEhC0QQBMGgEAvfAHDzzTc3Pv7xjxcL4HzzzRdPD0EQDDSx8AVBEAQDRSx8QRAEwUARC18QBEEwUMTCFwRBEAwUsfAFQRAEA0UsfEEQBMFAEQtfEARBMFDEwhcEQRAMFLHwBUEQBANFLHxBEATBQBELXxAEQTBQdHzhQyByHa1Izs/xzjvveKeB5bHHHivq2mti6AQbb7xx473vfa937klefPHFIr/dqJdW+PWvf13khZ/VBoH2i49+9KM9k8/Pf/7zLedlzz33LPrehhtu6L0Keqn+BxXGwZJLLhnt8B86Wgu+klERo0Fv8fZWSMXTy5DX2bNne+cKrYSpY4UVVuhanXQqnaeffto7tQWfX2/vBmussUaZ7tVXX914+OGHK/691KdfeOGF2rz4voZ9woQJ/w3gqItrbsLXSy+xySab1Oatzm9uo2Ml/fCHP9xYeumlS/sCCyzQ2GOPPQrzjjvuWHlioMLXW2+90t4Kiy22WF811B133OGdhtBKmDq+9KUvda1OOpEOcZ500kneuS34/PLk1W3Iw7rrruudS+aZZ54h+RxLmuXFqrqi7/Hkl6NZXHMTY9G3WuEb3/hGbTv0ar47Qb4WRomvYOxnnnlmxS4effTRIeHrQMUOcM0999zjfBuNf/zjH6WZuO0AzeGVycKrr75amv/0pz8Zn0bjj3/8Y8UOUliLQtRmvPXWW94py5NPPumdijJRNstoF75W6k1hcul4Za6UE8W88Morr1T8fP4/+MEPJpXQotDVtoXQVvdf/vKXZF6BLWDw+fWKi2+99dbS/Mwzzxif/6L8Xn/99Y1x48Y53yqp+iMPO++8c8XNYhe+5557rvH888+7EO/i660dsNPg286PUY9VJJxb+HL9JdcnwOeDOFppa6FxmGtH8GmAypMabyk3SMXj+1YzUnOPJzXeodW6YRw0W/h8vlsZE/1KvhZGSV0F//nPfx7i7+11KOw222zTWGihhYb48UOLtcx1cf/rX/8q/Hka5V+Ls65Dg7aNR9sFNl7u4jFrD92nmbNfe+21lfA2DOy2226NlVZaqdwi/utf/1q4r7322o2vfOUrja233rpyTd3C96lPfarwO/nkkwu7T0/2XL2pnrbddtshfrD//vs3ll122cY666zTmH/++Qu3973vfUU4JkR7zWuvvVaYv/WtbxX/P/7xjytp8nvzzTcL7eaYiZsdgsmTJxfXKwxPh9IzyM9ODAcffHDhpjpS2vZ64CZFdhuX3ZHQudwRRxxR/K+++uqNeeedt/S3fPvb3y7CaFvzggsuKNwVr8+LRQsfNwAK9+yzz5b+xM1Zmo97/fXXL+zsqoCu5ZwOdHa41FJLKaoStcXEiRMb73//+xvLLbdc6Ye7bxtYeOGFC/PHPvaxMqxf+HL9xfYJ0sOsBSfVh3QtbW3zkVoEcuNw6tSpZRjSwI00lCdQWDsmITcGVb5cPCA/70/f4saGOGhzP/d4cuNdcdfVDeOAm7TUOLBYv1bGRL+TroVRctRRRzUWWWQR71ySqnzc7r33Xu88BO7mrCJVrvN3TLjZp65UekAntn7q3AIzHRS4s7N+TEg+rLVvtNFGQ/wt2A8//PAhboJJzF/PHRjl9+6ibuED/C6++OKK3YI9V2+psIIJ0IdlK1pmfy2D6Sc/+UlhZiF+8MEHC/OHPvShyhMfAw3FucLGw2T/kY98pOKnNDWZW+rsWjgE/deX5+ijjy7MPqzljTfeGOLn42n1iQ/22Wefxsorr1yY/db+j370o4qdRc4eLeCnpy12J/wNoiAc543CvmyG3z//+c+KXXAT8OlPf7q024WvWf3vvffeQ/xTfciac23twc9ea8dharzbePCzYzI3Buvi0c2RWHGFFYfEYc3caKb8LP4antysPVc3zMH22p122imbBlg/38/9mOh3OlISzvDsILRQeam3MXG/5pprvPMQCMfkqB923yDN7EKDgidQJodHHnmk8fvf/77099dZO1t41t4sH3V+KTfM48ePN75V7J2YaGXh+8X//KJit9TZm/lxV8x28OOPP9546KGHipcj5KcnD6G648eAEn7hAxZFwvGEZdOk7ewigp+eErbaaqviJQNLXf79Tcq0adOGlG+VVVYpzPRrH5fg6cDf8BFWT22Yh7PwnXrqqeVb0bjXxS07k/Khhx5ayWcuvzAcP2vnRoCnM2EXPuq/7tr99ttvSJ/A3/ch65draw9+ubRpZ9JgvJMG41391Iaz9tQYtPOGj4d6ScWjLd0DDzyw4s4WKnMPW5F27vHY8b7qqquW7nV1g9mOg2ZbndavlTGhXz/SkVyzJZWqEOvm397Dr9nZ2E033TQk3tVWW22IWzO7+MIXvpD1A+9n7d1Y+NgW8miLRec/9pqxXPjYnkuBn5/kgCfoz3zmM4X/97///cLNL3z+lXprrlv42I72dVeX/2aDnIUEu7ZPmexSfP3rX0+moxs9zKNZ+Orilp3FSOH456nPPpl5CMO2copUeqJu4Uu9PWjtuYWvrg/l2tqTqydgvOfSgNR1vh9B3byRWvgIzzw1Y8aMijvh7BN1DsLZ8T6chc/mv50LX7/TsZL4SsLOeYG1W7w9BWFSkw7uL7/8csVuwa7DdAvX4HfQQQeVblOmTCnNqXiEf90bs7VzVpJ7mSdl9266wxOcPeywww7lWZ2wZu5mU/EK/PimCph8sNvDcH8tdtUbZj1d8HKHtfttKuL85je/WV63zDLLlH5ys2ZNoGwtaRGU32c/+9nCzARvr/vc5z7X+OpXv1ra8ZO/2jWXX4UXxGXtp5122pA8tgphL7nkkordmjfbbLPS7rFlAJ6GNVH7rae77757SL50w3nOOecUdh9fCh+Gt7GB4wN/rbXTf/SSGdD3OEeCZvXP1qDvE6k+pAUZ91xbe7wf41D21HhXPwUfZ24M1sWjceXx+Uq5MfekbkJsGMx+ezZXN2yB2mt1dpzD+jUbE/1Ox0pCJfF0Yu3+J26++ebaSqUzLL744kMaHewBMgfA2tfWXe6aa65Z2HN3iN/5zncqeWKbFujg2JdffvnCrgP9tdZaq7DzdIJdr6frejrIJz/5yUp5yAt2OuLll19eHr4ThyZ6H8bGyYLAiwBwxRVXFG56qlE8nAUpPE8eKfQyAZPMXnvtVYZnq6au3hjwG2ywQWHnCUQLLL8jjzyyePrlPA47Eyf/tJnOFPj5BY3zK90d625WTwrEZbdDeTpQ/JTVfg/KCx9nn312aSevSoMfdWTzy9tpqmtevHjggQcqcdlrN99884pdP/tSh0dtf8YZZxR9RmdG6k/8TjnlFHdVo3H++eeX/hdeeGFx9im7FhTipj2IG3d/Rgy4C54YrT2Fzm70+9nPfla4c7aKXR+l80IPdvriLrvsUoanDhkzsqvv5fqL7RObbrppmY9UHwL/7W+qrS3yYxyqznnbUfg06Kf0ATsmLYrPjkHQvGHjoW8pPPViwY3zP4ude+inmns8+Nvxzo8n7GZ1o7NWxb/77rtXwouRjIl+p35UjALuGGxHqYMKTU0G/USqQwVzB75dOYv2bkFvEOMwaIWO9pBWO6Bew+5nYsDNvaRu4KKte5MYh0ErdLyHpA6HLXNDJ9VWLb9Bkn4wKNCuvObPa//2zCjoLWIcBq0SI7gN/PSnP21Mnz69eGsr9xFq0L/wBirnZWeddVZWMkYw9sQ4DFolFr4gCIJgoIiFLwiCIBgoYuELgiAIBopY+HoEPtDmHCmYO/DaPLrJWKY9UiSvNRjKWLcnc5OXh9zvxMLXJRABxAe1KSSVZLhvC26xxRbFNfqIlo+OrST6dqA07EfI7U7Dgzg7paU6QVehdwPJpBxu3XUKSfWwouG6xVimPVL4uJw89/t3vJ2gW+1JGrm5Se1TJ0e0H+mN2aJFuj3BITy2Xen5twGJ94YbbqjYh5MWYa+88sqKW50MwZGQSsNrqegkpIPqIpGS+g8pt7EENUC+3oaL7x+t0o60uw2fiFhxhu2ineN3pIw2D91oT6vtJpVf7ClRkf3MyFtkDBju4jBakKjeqfSI97777qvYW01r3333rajrsbQahwdRaBbSyMWVc2+GlUzfCqk6wX7uuedW3LzA47GmHZOV7x+t0o60u02nFr5Ojt9WGW0eut2eqfxib6ZAoN8YeYt0mV/+8pflRGgbRnIC7YfFCmOVaAICj5GzKEWeFgS9IofTajiw6SEXzyKll0pHcjCRpwiS/YegW+QrYkahJNh4fVqSJZhKU+A3a9Ys7zwEwvFdk7UrPYvStOTCenwaqOZJXZdKoxmSLWjx+SKMkOLaCRMmFP/Svu5RW/u4JPsQ+az8v/jii4W7wvEEJnMqX6iA0bazJisb9vjjjx9yLWlQN1LKK00QPp26su26667JtD25/q906spnSY25n//855Xr0LeIWTJt+SETVuYVV1yxjM8vfGiUIEyuHerGtYR6+/lCY6lZG9u4rUxSySCV9gvGtwdFv9yESe4l2Dzwk7g7+af6BGbfnsPNi8K2a25ivrFzU7/TVyVIVbq1Y+YsSGZ+dGwJjMUuNSCYpU3ZK1nE/Jvf/KYcgDnokP46qwHA6sJCK4IVykvY+++/v2LnJ3VNqbKKnLvHh0vFiaJdlJTijnJTgT01oDw+vpTqKCANBplNoxleIwOCjyV4GKWvYP29OZUP29Z85OyvEbfcckvF7pV6YmayB1Qp2TMS/LT4PPzww5Xr+MjaCkL2ccrOv+8fEvSNHjiFk05KGy638OGX6v+y+3hUPo8PpzGnxRt4QvAqsCTcW+2ql7n8wmfj9+0grQGcPTUb16nxWxe36sDOGb/61a+GxIEi3RQ2nMQw5vLg01WfqOtLw8lLs7nJ+2luqsuvnZta0Z3ay1RL2OP4DqOBZn9WHU5O2vkhhxxS+J9++umFHbPueCypTuDB/8QTTyzNCo/kdcsee+zR2GabbUo74fzEZtOSrroUuLdy2Ew47ij182koDKTUHfmwKXwa6GTz12mC45zT+zVjiSWWKDVk6Fr+0WKBJgFpKE/1hVRauKXaGk0RSkcQVhoQeKo46aSTKn7f/e53S7PFbk8xiVp/3PGHOv1ouKf6hy8b/9IYAq1sjfn+D9hz5bOk6tmq9tGTHtpULL6ctgx24Uvps8OudkBTRavj2o/fXBtbcypu3Ndbb73CrKemFCqT1bvn8wC27LKrT/iwvj1bzQsQNjc3HXPMMZVwmpty+bU7DMxNtq/0I+lR16P4DoOKIp4CUhBOijEFAxn3O++8s1DmaBc+O3mIVCfwKE/EiVokhffXtXvha+Vci3B/+MMfyp9PA5ig0C0oVSQiFTaFT4NtT38ddtKQDkNU7rSK8sVLNT/84Q8LN+kZQ3GrNF/TF3y6KQiTamueyL2OOMJKJVAnFr66POPu+0cK3HmpSfiJ0pLr/4B7rnyWujEnuFbquqybt8vNLny0Qyqs2oH/unHNf27hy7WxNfu4QVuF4PNm0Ytf/HQO7fMAtuyyt7rwtZoXUDp2bpozZ86Q67DHwtfD+A6DLjjfSAJ3zpu8m2Dgq/F8vCLVCTxsq9jrmYzHjRs35Js88mJ1WRH+rrvuqthtWpyB5NJW5z3hhBO8V+WlF3+9T4PBYGGQaYtnpGl43YqkYSdY0vDXNMPnW7r6FlxwwdKtri9YfFyCRca7Y3/qqacKM59z2LrAD43sMtutOurnggsuKMx6JV3gPu+88xZmFI/6NGfPnl384+77x3bbbVfarbuNw6btseFs/5dfrnyWZvVM/0c3HWG8Pk4Ldul645MU3dQ0awfGUN24xqxy+fGbi9uafdwCPwSV0/dSsA1t9QMqXp8H+fl01Scw5/qSaJYXkZqbMPu5CTfNTbn8smUvmJtS80I/ke/BPYgOyv0LG9IAgQJXKdLEnXMZC25MLEhux8w3arzKi4JI7Chy1KSqToWZV3xTTwmCMLoj9XvrgsXQTtSUhbsslcV2UJDSyRzy1xMPZxzY7YfA2NEoYO2KUy9LWLirs25s2WDnaRVIgwWgLg22vWwczdLAzHZmHb5u5MadrHejXjgDoy+kNIPYtuYc1+dFW3S33357ZbuOuLTFBITVCxra3uUjX31Swo8XVRSWtKyiUHs+xdnnq6++WigbHT9+fOlO/5B2el1H2UhHZWuWtgV33/+tX658HvxSY47tcjSQA/VHOHuNtgBZgHhRQmC2T5Gcj+Xagaf9Vsa19bPjF3subvx83ILzSS1OKTi7ZWEB/2ak8qC2tC/Q2T7BCzm59rQ0y4uFa5vNTbjZucnnFzuKfQVt/8UvfrG09yNDa6HHueSSS7xT8X2X/ebpb3/7W7HtwOL1+uuvl+7cfdtF8/rrry/NcOmllxYHyBbSI/46/J2Xl7RAJ+ZlDBYO8iakOoW7LO6O+XG3DIQlXgZRHUyEV111VaWcwMLGmZpeAiEe4iZO0qNM1JG9KycMbj5NrqHeUmkQnjTw4zr+lW/qG3/+hfKhNFJatD2pb4hsPVoo17Rp07zzEGhr3TR4/FYh+adMqivS5gUN1S3grztzf/5KHdhzHw/9xb9IwosEKdU6lI2ncU8ubUuu/+NOX6krn8ePOcLavqM41GeYPFUPts8Rjr7O9V46iG8HhfXjwpaLCduO69z4TcWdmjOE/dYtB/2adpw5c2bFnbb0eSAtbobgoosuqvjV9SVoJS/Cz01eawV1Tl5Ur2DzS93SXtgpH+EJq/Her/TdwhcEQf+RetLoJ/SZRC/QS3npV/q7NwZB0Bew8D3//PPeuec59thji7zvtdde3qvr9FJe+p1Y+IIg6CicAbKd57dz+wFt4fYCvZSXficWviAIgmCgiIUvCIIgGChi4QuCIAgGilj4/gOvXudekU+Res1YnHHGGd5pYPEfy/YKZ511lncac/iuLPpOe+Azn6A1kLg0aPUVC1/j3TfO+N19993eq8SKp+J33HHHVQP8h9QHp51mwoQJhRohPh7Xb5999vHBus5Y1EUzJOh3tPlKifMaDTvttFMhsWPRRRctpOZb+HYKocy9wKRJk7xTT6G2td8r9hvt7lt1+PqifXulr3WS0Y3+LsObYTQSjcP/jTfeWPoddNBBhdvCCy9cqPMYLlyb+lBa2IkS9SMI480x2kl1JJCm7bBeJmE34GnFll2a1HuR0eZrtNdbEEBQFx/SUOjfrTASQeDDoZNxtwvEfOW0B/g+2ou0mr92tTVxqL4wt9rX+pnR11oXoVEkuBezbXTMknoyks7ANV7iSg5E+fTiwucZztZtO/BtwkKcylcv0Ev5Qp9eu/LDt3Ltiqtf4cY3t/D5PtrPtKutiSNXX3Mro6+1LiKZkYCQVjU6IopsB2Ai2WyzzUq7B1mAhL/ssstKN+zI+0MwMGYrCw8VHjb+1MK30UYbFWFWW221MixisZC/iIihyZMnV7awEKVEPtZcc83CfuGFFxYS7ckDusyIIyVrMocfADvvvHNxbmnzzr9EZ6H3C7Um1KMV8YWMRyTAw5Zbbllcw5M1223kl/ApHn300SIsP1QFTZw4sbLwSc6qFwdFvRHvAQccUHG3TJ06tWgP4pACXsSuSRlwrr64Dner/04oX8iXRFUN//DQQw8V2gJQJgqUW+VCjRD4/gDsNOCGFgdfRpGqc7bXkcTBtausskrjlFNOqVxzxRVXFMpTV1999cJe109oAymHVRsI39/oG6m+Sd+mPnTXz+4GMjtRR0ReUjoakR2JrEeJuUIPJXFwHICQcuS7qn65Hn/ZPbatRV2ZLdQtdYnsz9REnuqjufGB+C7ygZvtc6hHUnjkhpIPK7qLfqw+p/4CyPKk/iV1RfVPWOpfcdr8MBexBY7OPamwkuDwXFvTX9UXbfoe7TKo71Ffal/1NUiNvbmB6ujtI2gsOh6gh8vq2ULZqZReWiQ1XmCWHEnMLFoMYAYadmRRgtcR5he+L3/5y6XeKwa1wkqjNfFydiN3VApp4KINHM3RyKzEHwG2dDQmKuytSrsgLKpQ+LHNKb1i0lEm7cnrr79+UQ8SEsyihrvkJCIYGTsCdw877LBSDQp5ktoXVAWlwI+fPrLVwscPpaRMrnZCox64OdC11EMKCf+lrlSHyA9U3Kn6Im57HSppLIpHk6EtE3bdFCkcE6HazPcHFiYrHD1FXZ2z4Nl6s9x2221FGyj/zfqJBCTbuFL9DQjn+yYCw20ZEJ4tO3mxfnarjfqRmcXShsPMRG/tXJsi1WbNygxKj10bzKmFD/Cz9ZMaHwoHtoz0ObSfK7xUcOlG0V7HnKA6p+1VrnXWWad0V15s/du+xU0YY4Z5Do0TUmoslWSptsZOX7T91UPelIatL7WvHSupsTc30Jcl4U7GKnrljnTDDTcs7SmdcICb7uTh3nvvrfhZO4uHXdxsfHbhY4L0aVn7VlttVdHEDvjzAgpPpnpSBPRcoSFccOeFmKJWsGlSDklk934p+znnnFNxs2YGhLUzAKROxkM4Gza11Sk7CzRm7ma11efDCrsFbcN4nYW2vpASkrvO233atm/hjgYCjw1PX2Hyyk3m4NO3de7L4WGnw6okqusnPHX5uLCn+luqbwL+6BEEnlKsgOVUvfFyFU8mmKURHLM0obNYSevBI488kn3ag1yb1ZWZcGg/EcPd6vR2sOMOfwmNll2QD18nvr/4+HUTQP17P7Bu9BP6ltCNKeTa2oZPkbrGnvHZvpZrD54w9etHhtZ6H+AbDl1SVjErb8f5MICb1MF48LMvt7A9Ix1h8hd24dt0002HpGXtdG5NBgL/J598spAkzxOHPo1gcFslrdzh2sFeh8+Dxft5O3eM1s2a2QqzdsprNW5bCGfD1i18Us3Ca9TUA3ezuU9EeNJkMvO6/PyC4etLT6j+OrB2to9k928DcofuywXWLh1m/NguSuGvt3Xuy+FJLXy5fpKbDFP9LdU3gZtItmzBqg8CGzdmtjKZHHklHq0EdlJfcYV31RpZ5ansxGhBTFHX1rkyKx+iHQsfEI/C526CrYoh+fGzN9i5+Ftd+OyNAouq/FNtneuvFu+HPbfw5dpDafi4+oW+yrV/utLg9BMsiyCKIT2E0aO7B7+RLHzc7frGt/bU5IJ/6tOJusHdDJ8Hi/fDfsstt5T21Baw6NTClxv0HraiOLsR9hq/YPjJMHddzu7f+EPvICpYgDvbXB3pPEw6Ea0iUYF7rs59OTztWPhS/S3VNwXXPPvss5UtSrlbs0/Lgh/bkdouZALP6fiDZm2dKzPh7Jn8aBc+bX8KzK0sfF5Ppdz5T52P5caAdfML3/HHH1/6p9o6118tuFuVU9hTC19de/Q7fVUSKp6BgxLExRZbrNIQmDmYRsdaroF0MM1Bs84kpIMKs/14mAVy7bXXLswKq87CXTD75AI/hcXMDyWSwP78Jz7xiTKsDcPTDne/2osnTZ0xAAfPDHgg7Vy5NIlyEO2Rwlnb0XWupe0sXraQ/29/+9tKOvvvv3/FzhmoPU+16KCcFzeoD85a7bVo0bZ2zJSdekAJZ+pMgpsbvRCgsxCdaUijtLD1hXvuOp5OfF3yQgpuVkefVS5qNan7/uDLdN9995V2UVfnOl/KweRjz6zr+gkQF093vk/6/pbqm0LXeGy59QkRWtmBemYL24ZVHP6mNUWzts6VWcpbeYuZ80ulm/oezvfR1PggH8qrvvvU0QEv2NhyKD6gv6jtWazkbucddPBpd4r693Xi+1bqGOKmm26q2G1bp/qrR/UDtr7kp75W1x79TrpmehQ1kP0JPV3Q8M8884y5qgp3brpWLxfY+LRNqp+0Oud+oEVJdhZlOngqrFh66aULN20l2XBowrZ2Xgip+2Ynl87pp5+edAedFfCzH7v78NauN2n58eaYR2/X6s1Bey1bbT5u0OKlazwqNz++C2TSps6mTJlSuqfqy7ajvifkOt3N+3yAt3MXbMsMvj+AJj9+dZJXUnVe10Zg/fzPl9teY1+4AN/fmqX7ve99r3J8ADb8xRdfXLgxmcvNP1XyhGaf8FLpWHxbK782XV9mvSylM0YUzPIOAE9Gevqx1PVRQT64wcONoxH6HGbb5/hp0VQ+dB7Oj/q2aDHVW9Gp+k/1LS18+vlPrnCzbe37awrmK/VZaWXXk6R+tK9vD429flZAK/K1EwQDBDdBnNUFQS/htzqD9hALXxD8PwsttJB3CoIxh/cMom+2n1j4goFG2zmcwQVBL2G3Hr381mB0xMIXBEEQDBSx8AVBEAQDRSx8QRAEwUARC18QBEEwUPTNwsfLB3xsW/d9SjeRZoCgPfBRub7RGgkSrqxvkkYCH0Lzoa4EfPcrfH830npsN7vsskvLeakb4/QPK8w56A60Hx/an3/++d6rr+mrXrT44ov3VMfvpbz0C9RZSkKLGEmd8rExkuUB4QUjiUOwgFqJH8SV+hC6l5HE/V6hLi9eG0TdGPdhO8lw2/13//s779Rx2pVmK2Py1ltv9c59TXd6UZtYddVVu9bxW6GX8tIvWHFLKUZSp/6ae+65p2IfDkjblwguaJbfXkTi13qFZnmxk2rdGPeaEDrJcNp9tDdbI4H02pWmLWuqLNjvuOOOilu/056a6xK5QSH5hynYIgF0VElafKvUqZmBVF5AotA8yM+TdJC11lqrkPsnHnvssdLcbuqk4QvJqCRPvtzoIQMvLglUv8PBqn8SEhCeqlOfH0/qGitWSXoVoe57PeQk+oXPgyg6IE+5uKTjESTrULTazqk+1Go5/MJXFzaVzmigXnx7NcuL7Ve5MU7/SC18etL3fTPV51utvxR11yLI2+dL+LoAyQf2T5TIUvVuAoHhlnYufKAxmSoLdomjY2FEJmq/076a6wJ+UIwfP77UWO3PBpDQLokHnMchNFoTuO80KftZZ51VmnMate01tsOgcwwziiRBAopBk5JXzAnIGOTaOhgAhEcTNaD+xOaDjikZi/YcEg3aKQkQqAPi7GT++ecvBUZzjWRxsghglzZq5JD6wYFZcUsmp8pu1e9Ifqm0auha5GeCPzfF3KwdFD///CSkHGHbIAHGyDBEo3xq8sROmZgsMWvhmzRpUiWsjevss88eEhftbPscfupz6MI74YQTCjPuqXau60OtlEOoj/HbbbfdCnmZNmxdOroO1NfsTUQuTdvOXmNJXV7od9buxzhmjRWbN5CcVwmsJw+5Pj+c+qtr99S1tg8K7Km+S54Rrm3zjIBpxYfmExT5CsaKzqwJgxJjmX2aFvzq5gjZ/Zj04wnkz02cZHvefvvtZXz9SLrlexQ7KKQDzYJdEx5mtANYP2vO2VGj4v222GKL0m6x4fzCawe/P5vAfNxxx1XsIjW5e3hytUKd7fX2xQ7craolG87iFfdKQrwV4n3mmWeW/nVlBczclMBpp53W+NrXvlbxQ5ULpCTIy+7bAS3lrbSD7PbJCjtCzK1dsMDbrZ6VV1658sSXijsXF+2c63O8IIDmcNhrr72S7dxKvebStmjh8xOxqEuHvuXTRBuKQAN5CiZFPRWkboxyeWFxsnY7xmkb60fbWDsvIfk6wJ7r85hbqT/wfs2utfa6vpvLMzfq1g5eEwQyO7W7hbuPx9JsjrDtiJ/GpOwW7KgjE9xY77vvviZE/5GvuR7EDgpJY7egTVpS0fHjLUHweqt8p7F2rmGg8+TDNh53wlYDtcXHgZ4+i/yZ+H1YezCt9K3uq2YQngUKjeiYJdLIpyMFpCwEOUWvF110UTExW7hWmtZtnLLnygpItJc9da1UqHD3LPVN1h98O/Bk0ko7yO4XPouvI4vf6vT+dXbaOdfnpKuPn9XtZsGvrl7r0rb4rU7w8TRLR9txPH3Iz05+Hp+exftZu1d7Zcc4/7Z/+CctJu9U3Lk+nwqbw/sNx17Xd8lz6gaOc2niQMuD4pLKoBS45/wE/pojaMfUHCG7xqTsFuz2CY/FG00j/Ux9zfUYdlD4xQQ23njjxgYbbFCYUfuC/2GHHVb82z1632msncHVqlw8H0cr2qrJn93qE9qOuOqqq7xXEsKiKZt/Jgf+USWDNnEbxisSTZFb+HQHb8she11Zrd0rBMZdgwydhmh29v4w0naQfSwWPtlpZ/59O7PtWdfOzeo1lVaKVha+unR4WqdvHXPMMRU/H6dlOH7W3mzhs/2j1YUv1+dTYXN4v+HY6/puauFbbbXVKtfLzBObT0fgnvMT+GuOkB3sHCH3WPh6GKvcETDbN8Kw6zDZN56FTunjkZ2tBMw6O0R31YknnliGtdg4fCflrl5bDSjQpAOmsPrbfvCDHxRPS0BH5K41x3777Vekp0NpWwbh3Q444ADj+19Y+KwG6zlz5jTmm2++0u7jTZXVh8l9v4UbW1YgHYo6Q5IOPfDtAK20g+z2LbSUv+AOmzNO6+eVulrq7FZRqseGw6x2tqTqNbddlbIL2s/7WXuzdAB/heHzDszXXXddJYwF5aVSggpoFRB1efGLlx3j9ukHbJ5gk002ScZt3WyfT4XN4f1atbOlW9d3yTMvtlkIm9opkBklzYKjA7DlzJ3ztTJHyF1jUnYLdnujxo2d8tuvDK2FHoVzGDUcL4HADTfcUNg5EOaMwT61KKx+dhuRSRE3DbIFFlig+OcbInstd5v+zlho8VxppZXKvX/OJNirJz+28xx77LGFXQot+aG9GujUpK8nU73VpXB1WP/NN9+8WDgtOpTnRzn0coWHhY8wPI1yN4pZd806hOdbOYvKqsVqxowZFX/w+ddiyO/OO+8swyh/pC+z9aMdfFxCW960A4f2mgyZhKl3tZMWM71cocWON9QUnn+eQpUHKW9dZJFFivw2iyvVzpz3AGYmYd/Onlwfqkubhc6iF5E222yzwq6nTPq33nbMpSNwQ8mstTdDZeanscj2aC4vbEMqPDs4fozbtqE9bNvcf//9ZditttqqzEOuz9fVn2e47Q5KUwu+7Lbv5vIsN3YIpEhWZ356IvY3AXohxqaZwl7DHGHtUDcmuflV+6HslvlW+eHHtf1K897cp/gGpnN4t25BJ2ZxETyV8jYbZxE52K7yWrQ7RWqrMxg+9gUFkMqjIAh6i7lyVDLh+EkI7HZeN2Hy89/z8HTGNmoOnhpyZxXt5sILLyyeOoORk1vkUm5BEIwtc+2oZMLhqYq9aV697dbTUwptDVx88cXFZwGYJ0+e7IONCbfccku5HTN16lTvHQwD9TnamT4Xi14Q9CZz7ch88803GyeffHIhscVLdRgLrr322sZRRx1V7JP3EpzjnHfeecUZXSx8o4c+Rzv3Qp8LgiDNXLvwBUEQBEGKWPiCIAiCgSIWviAIgmCgGJiFT99PteOFA+kM6/QnAMovsh3rmDJlypBvuTpFu8q+8847F+WaOHFiIbzYggDo3XffvXhBhO+yUtocuH7vvffOvvlK3Dm5kjn4kP7AAw/0ziOmXf1NkL9utXM3oN+ONe1uo7kd1Rcfx/czA9Xio+nkVoUQEM+4ceMqbq3i46qDdLyIIQ9h6hRJtpvRlF0gAFuCA+666y7v3fjF//yi8EPAbwoJ8EVMXQr8pk2b5p1rWXLJJUfcP3K0Mz7y1812bje+31M3KWHd3aadbeRpt9qnXgBh7EcccYR37is61+I9yEgXPi9wGLAj1WS4pOKqg7A8rfYSIy27R5925MDv6aef9s4lufZEik/KfSzolXyMNbm26gU6lS/iteLG5haQLcqby/1MZ1q8w7Sq/NQrxbSDjy2ynEJFH3/q42Q7+c+aNaviJ5DZ5+/4UnGlYFtL6oHswpdTvDkareNghXh7pZeeVsreCugrq6sL/BBDlgPdZP566pdtWNy90ABIKSi1+PKgrwyIq07hsfDx2/x5BaYipYAUgdZ8kkO6VtBBrp3r2kzKj1E9gwaT4WDHiN9mfe655yp24ccPDGfhS11fpwhWtKLkN1XXyhflycm9bKXtPcRbJ99UGlpo4zopTh7pePT9OzefQbM6zfWf1HWx8HUZOtLMmTNLszqAxyrF5KxHZg0+ngjOP//8IYMxF39O0aTCXHPNNYX55ptvLvysFHkGI+YHH3wwG5cFGX66lkUTsxY+KYVFhh7/yAr0iiSlCFblAOyapBS3lYrP4MSMoGJUBak80h/nwY9fquxe6aXkE6YY7cIHyOiU0lyQoGSulXYJ2SU0IJemVYrKoqNyIvNRea2rk1T8igNFtOTV+lkFpKiAQnYsSGYl27yS3E87kz+1s20z8pdqM+xM2CycmOlzuTGjfNh+cfXVVxdmhG9zpnPOOeeU5UEEoPqhjYPvGIG+ieBq66c8gOSaipQOP40ZrwgWfXA2LGfEsvNv+77I1TXgTh8ib8iktcIuGMu2TD6PV1xxRcUueZca57RLaqxLsDvpMs6R44rdLkBKizZRXdo5gL4heaEKu8cee5TmVJ0qntyYt2FTcyHEwtdlaACrHNUq/bSwsOncyD5h8W8bF51ZvrEV//LLL59VKip7SkitzPZOz6fr47LgZz9yx26f+LAjGNqCm1UWip3OKbbffvviX09Cwpt9eXKqR1JhfVw6u2GCSZ3hwWgWPu7c4dVXX63EscwyyxT/uHFzI7BzbgiorErhlaL6CRaBvXV1koofd3/DZM1WVJz383VD/mw7kz/fDjZ/9npeSvIqogT9IqfGCbPVCG790BQge04xtNo+VR5r98px7Q0rYH7hhRcqdmH7NXVvn2QE/nV1bcHOGGylTF47DLr3rL3uiQ9/v3CyuEOzNknNAULC9lupU99/rDk3F8bCNwbo7o6ffxtQ2Aa06DqRUp2Ti9+Hw27PuawUdh/W3+l7f4v3w+4XPg9uVtXJdtttV4bbeuutS3fcuMNjm5RBhZJd6yeNEbJbHV2WurLLX3aeAHOMZuHzam9YaLUNLDfe+hTSkccvd8Oku27hb4y4887VSS5+Xz5vlwJSfy6JGWn6FvJn25n81bWZjY/4U2/HAuHYKcj1CzR2W7tA2o/saMnwbY0fL+TI7Mvuy5u6PmX2dqvkN9e2UFfXFuyMoZSya8ayLZPvc8Nd+LxdbvzbNqlTqCs3fn4ha1anvv9YcnNhLHxdhgbQwPeNYfENKGzHAr/w2fjp+MNZ+Gzc/NtzGa83zMdl8X7Yh7vwyc3+y2y3BS34+UGQm+Tryg4TJkwo7Jx31QniTi189mUW/PzCp88N+JxBcCfPYNTdMnCtlBILtmt8Xi2jWfggFb9Py9pzCkhlbsfCx5aYVUaaAr/cZyH4tbLwoVbIq/DCb5111inNPg++vKnrU+aUHbTNfvnll3uvpnVtwc7TbErZNWPZlqmTC19dm6TgMyAfR7M69f3HmnNzYSx8XcY3DHfZKdjHtg1++umnF/+2UwA6wnycgjsnG7/8tG2F3U/+mqQx+0mYbSlrh9TeP37+ro27TGv34IaOMIsUfNqXIfxWpz3kx116DmW3yiktdWW3bqm8Whg8Poy1Y77vvvtKu9UnZhXlAu5W8Sd27uxFqi09nMNZvxVXeFfvmvXP1Ukufp+W91t33XULs99Ww+yVw5K+bWfyV9dmfuHP0axf5CZHnq58nnXWK7tewGA8KqwdQ8LfZCBDNjVmUnZvtrrurHtdXQuesqzW97oyoadP34pqy/3oo48uw1Jm3lzOQXi7uGF/4IEHCrNvk1wbgFVmzXmk/FN16svt+0/K7OdCji/4xrafqdZgj0NjcHevQcQv96q//PnRiezLLNdff30ljJ4ebPzLLbdcJX6F1eQqOx2Nhfbcc899N+HGfxXk8kIA5zL+Y28fl0WdFcW5CsePp6OUUlirSFJvIArcLPaJhDLq5oAzQLkDg1d2naVZ5Jcqu+A8yWoy9+y4445lPNwk6MUBfugH1Dd1/LQA8eMMT2dv/ulGIGxb4bkLlj9PTJxX2LDiqaeeKq/hTt8qDeVFDJCdvHtS8UuJJ/+gJxLakfMqxecVkGqLjR8vQYBtZ/Jn24z8pdoMsxTs8rPayC25frHDDjuU7oDWeMwoKwb5EQ6ksJXzJxSnTp8+/d0EGlXFqfR7KXvlGvVbzFa5sVC8+qZTRwcoiqWsmElPmuJTuwxK29e1/HihRXVqsWOZNOxY5kUW/FgIpAgbu25cbZlTyO/UU08txhFCG4Rvk+OOO65wt3OA+gafTJA3zXEbbbRRGY+vU7VJbszbOvVzIT87bu2i2W+kWyQIRsnhhx/unYIu8vjjjxdbkRZ/thWMLdEWY0fUfNARYlCPLdzp+++8eNKyW/DB2BJjZOyImg/aisSQ+TO/oLvoRQe28bVNPmnSJB8sGCN0Fpc7Mw46Syx8QRAEwUARC18QBEEwUMTCFwRBEAwUsfAFQRAEA0UsfEEQBMFAEQtfEARBMFDEwpdB6n2CIAiCuYuY2TNIh1kQBEEwd9FXM7uEy0rZIgKYrTy8Qw89tAgn2X7INwRk4Ek57Lhx4wo3XXPZZZeVZi106Miybuutt16h3RizFHXmtEAHQRAEvU1fLXwsOAcffHBhlqBZQEirzIButtmzZxdmK/D2lVdeqYSzi53skq7+1ltvVfys9mUksbMIB0EQBP1H3y18/mf9jjzyyNJs3f3P+lm9UtilrdwvfIh7wj5+/PjCLwiCIOhP+m7h84J3BapB8EcNkNfObfXbWYaz8Amlc/vtt3uvIAiCoA8YOrP3MCw4OeWzL7744pAnOki5CdzR4WXtW2+9dWH2C581b7nllrWauIMgCILeJb0i9CgoPtRCxs9rN1522WUbV155ZcUNbdL2GhROglfEiIZj2V9++eXCTXZpLkbzwCGHHFKYtd2J2Wr6DoIgCHqbvlr4xLRp07xTwZtvvumdSu6+++7GrFmzSjuLG9umuoYXX955552K9uZLL720NMMDDzxQvAVqt1uvu+46EyIIgiDodfpy4QuCIAiCkRILXxAEQTBQxMIXBEEQDBSx8AVBEAQDRSx8QRAEwUARC18QBEEwUMTCFwRBEAwUsfAFQRAEA0UsfEEQBMFAEQtfEARBMFDEwhcEQRAMFLHwBUEQBANFLHxBEATBQNHRhQ/NBWhFqGPKlCmNOXPmeOchzJgxo7Hnnns29tlnn8Zuu+3W2GmnnRoXXHCBDzZiTj31VO/Ul+TK8fTTT1fUMHWa1157rfH44497544zzzzzVFRMjRb62cSJE4sfZgvqqmyf9CqxYNdddy38c+y9995D4q2j1XLl+sFY0Gqem7HEEku0La6RQLrMQ/yfd9553rttNCujHVsKu+2227pQ3R/z/URHa8RW+Ntvv91YbrnlCrf555/fhKqGq2PBBRcswk6fPr1x//33N3bcccfCzuQzWohn9uzZ3rnvqCvHJpts0nJdD5eZM2dW7CussELH0qpDaV599dWNpZZayvkOn5deeqmcPFBd5VGfvPHGG71XAYtarh4mT55c+D3xxBPeq5ZcfJa6ftBtXnjhhZby3ArHH3/8qPRfshiMhDXWWKPx0EMPFeaFF1648fDDD7sQ7aNZffmxhX3ChAn/DeCoi2tQ+T+qtgHXn3a0vgAAAABJRU5ErkJggg==>
