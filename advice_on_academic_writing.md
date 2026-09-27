# General Writing Tips

1. Avoid stating opinions as “We **think** A.” Instead, express your thoughts directly, or use more assertive words such as “insist” or “argue.”

2. Avoid using adjectives like “**better**” and “**good**” without clarifying in which aspect. In most cases, you can avoid these words by directly describing which aspect was good or better, and at what: 

   * **Don’t:** System A was $\color{red}{\text{better}}$ than System B.  
     **Do:** System A yielded $\color{red}{\text{faster completion times and higher accuracy}}$ than System B.

3. Use **en dashes** (two hyphens \-- in LaTeX) properly when indicating a range. Students often mistakenly use a hyphen where an en dash belongs:

   * **Don’t:** We recruited 13 participants $\color{red}{\text{(P1-13)}}$.  
     **Do:** We recruited 13 participants $\color{red}{\text{(P1–13)}}$.

4. Use en dashes for compound adjectives consisting of two nouns. Researchers often mistakenly use a hyphen to connect the two:

   * **Don’t:** $\color{red}{\text{Human-computer}}$ interaction  
     **Do:** $\color{red}{\text{Human–Computer}}$ Interaction

   * **Don’t:** $\color{red}{\text{Parent-child}}$ communication

   * **Do:** $\color{red}{\text{Parent–child}}$ communication

5. For numbered lists, **always use Arabic numerals enclosed in parentheses on both sides**. For instance, use ‘$\color{red}{\text{(1)}}$’ instead of ‘1\)’ or ‘(i).’ Numbered lists with unclosed parentheses look incomplete.

6. Provide **objective** information whenever possible, especially when reporting **Results**. Provide **numbers** if you have them. Minimize the use of “some” and “many,” especially when you report the number of participants who mentioned something in the interviews.

   * **Don’t**: $\color{red}{\text{Some}}$ participants reported that …  
     **Do:** $\color{red}{\text{Five participants (P1, P4, P7, P18, P24)}}$ reported that…

   * **Don’t**: $\color{red}{\text{Most}}$ participants reported that …  
     **Do:** $\color{red}{\text{17 out of 20 (85\%)}}$ participants reported that…

7. Distinguish between **citations as a backup for a claim** and **citations as an example**.

   * **Citation as a backup**: You are **citing a claim** made in the cited work to back up your own claim or a specific concept in your sentence. Put the citation directly after the part you want to back up, without parentheses.

     * Similarly, parents play an essential role in supporting how children identify and express their emotions $\color{red}{\text{[10, 37]}}$.

     * Studies demonstrated that when chatbots remember information across multiple sessions, such as users’ names or preferences, people perceive them as empathetic $\color{red}{\text{[29, 52, 63]}}$ and conscientious $\color{red}{\text{[8, 17]}}$.

   * **Citation as an example**: You are citing **the work itself as an example** of your claim. Wrap the citations in parentheses and prefix them with “*e.g.*”

     * The recent advance of pre-trained LLMs $\color{red}{\text{(e.g.,}}$ GPT \[8, 61\], PaLM \[15\], LLaMA \[77\], LaMDA \[76\], HyperCLOVA \[46\]$\color{red}{\text{)}}$ has presented new opportunities for…

     * One common approach is to include summarized information of the conversation history instead of a raw knowledge base $\color{red}{\text{(e.g., [2, 41, 75])}}$. 

8. Clearly distinguish between **present** and **past** tenses in the main text.

   * Present tense: When you report **what you do in this paper**.

     * To this aim, we $\color{red}{\text{propose}}$ …  
     * In this work, we $\color{red}{\text{explore}}$ …  
     * In this section, we $\color{red}{\text{describe}}$ …

   * Past tense: When you report **what you or your participants did as part of the method**.

     * We $\color{red}{\text{designed and developed}}$ MindfulDiary, …  
     * We $\color{red}{\text{recruited}}$ 18 participants from …  
     * We $\color{red}{\text{conducted}}$ an exploratory user study …  
     * From the study, we $\color{red}{\text{observed}}$ that …

9. ‘Related work’, ‘literature’, and ‘research’ are uncountable (mass) nouns. In most cases, they are conventionally used in the singular form. Grammatically, ‘related works’ is fine, but we seldom use that form.

10. When you describe the actions of researchers, use **verbs appropriately**. Choose verbs that accurately reflect the scope, depth, and intent of the research activity, and avoid using them interchangeably.

    * **Explore**: When the study is open-ended and aims to gain an initial understanding.

      * *We $\color{red}{\text{explore}}$ the feasibility and challenges with older adults in collecting activity labels… \[MyMove, 2023\]*

    * **Examine**: When the study is guided by a defined focus, clear research questions, or hypotheses.

      * *Quant: To $\color{red}{\text{examine}}$ the effect of framing on individuals’ productivity, we compared two versions of TimeAware. \[TimeAware, 2016\]*

      * *Qual: Through an exploratory study with 19 participants, we $\color{red}{\text{examine}}$ how participants explore and reflect on personal challenges using ExploreSelf. \[ExploreSelf, 2025\]*

    * **Investigate**: When the study seeks to uncover underlying mechanisms or causes that explain why a specific phenomenon occurs. But in practice, many HCI papers use this term interchangeably with ‘explore’ or ‘examine.’ 

      *  *We $\color{red}{\text{investigate}}$ the factors that contributed to participants’ disengagement over time.*

    * **Assess**: When you are evaluating something, usually driven by quantitative metrics or measurements.

      * *To $\color{red}{\text{assess}}$ the difference among the experimental conditions, we conducted Kruskal-Wallis tests over the four rating questions.* \[GPT-Chatbot, 2024\]

      * *A set of call logs with 100 users (721 sessions) was classified using Positive-Neutral-Negative labels, designed to $\color{red}{\text{assess}}$ user satisfaction with conversational agents.* \[CareCall Long-term Memory, 2024\]

11. Be aware of the **level of certainty** when you report the **interpretation** of the findings in an exploratory manner. Choose ***subjects*** and ***verbs*** appropriately:

    * **Low certainty**: When you strongly imply that the statement is mostly based on your interpretation or suspicion, with little or no data to back it up.

      * We $\color{red}{\text{suspect}}$ that…

      * Participants $\color{red}{\text{appeared to}}$… \=\> Usually when you interpret a pattern from the qualitative interviews.

      * These findings $\color{red}{\text{may reflect}}$…

    * **Moderate certainty**: When the statement is still your interpretation, but you have some data points to back it up.

      * The results $\color{red}{\text{suggest}}$ that… \=\> You can generally use this

      * The results $\color{red}{\text{indicate}}$ that… \=\> When the interpretation is more obvious than ‘suggest’

    * **High certainty**: Caution\! Use the following expressions only when they are justified by numerical outcomes or by very prevalent patterns of repeated observations:

      * *The results $\color{red}{\text{show}}$ that participants’ self-efficacy increased significantly after the intervention.*

      * The results $\color{red}{\text{imply}}$ that… \=\> Stronger than it looks; use it only when the logical connection between the evidence and the conclusion is genuinely tight.

      * The findings $\color{red}{\text{demonstrate}}$ that…

13. **Don’t use “say” to attribute what participants or prior authors stated.** It reads as colloquial. Use *remark*, *note*, *state*, *mention*, *stress*, *emphasize*, or *describe* instead, choosing the one whose force matches the strength of the statement, and don’t repeat the same verb across consecutive quotes.

    * **Don’t:** P7 $\color{red}{\text{said}}$ “I stopped checking it after a week.”  
      **Do:** P7 $\color{red}{\text{remarked,}}$ “I stopped checking it after a week.”

14. **Minimize be-verbs** and recast those sentences around a precise action verb. Plain “A is B” sentences read as flat to English readers and make the prose look unpolished.

    * **Don’t:** The main reason for the disengagement $\color{red}{\text{was}}$ the lack of feedback.  
      **Do:** The lack of feedback $\color{red}{\text{drove}}$ the disengagement.

15. **When a sentence opens with “this” pointing back at the previous sentence, ask whether “this + noun” would say it better.** A bare “this” leaves readers to reconstruct the referent themselves, and after a long or quote-heavy sentence they often reconstruct the wrong one. Naming the referent costs one word, and the noun you choose usually does interpretive work at the same time — it tells readers what *kind* of thing the previous sentence established.

    * *$\color{red}{\text{This growing clarity}}$ allowed P13 to “confidently decide when to explore a theme more deeply and when to move on to a new one”…* \[ExploreSelf, CHI 2025\]  
    * *$\color{red}{\text{This meticulous process}}$ highlights the challenge of aligning signs with the music, a task that demands significant time and effort.* \[ELMI, CHI 2025\]  
    * *$\color{red}{\text{This gap}}$ is consequential because the unique characteristics of autistic adolescents pose barriers to practice journaling themselves…* \[Autiverse, CHI 2026\]  
    * *$\color{red}{\text{This procedure}}$ was implemented to ensure active monitoring and communication.* \[MindfulDiary, CHI 2024\]

16. **Tone down absolute and extreme words.** Strong words like *imperfect*, *useless*, and *blind* make the message look aggressive rather than strong. To make a point forcefully, unpack the precise intent in softer wording instead of reaching for the harsh term.

    * **Don’t:** The existing approach is $\color{red}{\text{useless}}$ for this population.  
      **Do:** The existing approach $\color{red}{\text{offers little support}}$ for this population.

17. **Check whether a paragraph’s wrap-up sentence is redundant with what comes before it.** Closing every paragraph with $\color{red}{\text{Taken together}}$…, $\color{red}{\text{Together}}$…, or $\color{red}{\text{This suggests}}$... leaves the point stated twice — once at the top of the paragraph and again at the bottom. Put the point in one place. A summarizing sentence at the end of a **section/subsection** is fine.

18. Call a scale a **Likert scale** only when it measures the *degree of agreement* (*Strongly agree*–*Strongly disagree*). For a frequency or any other non-agreement scale, say **rating scale**, or simply name the **categories** the participant chose among.

    * **Don’t:** We measured frequency of use on a five-point $\color{red}{\text{Likert scale}}$.  
      **Do:** We measured frequency of use on a five-point $\color{red}{\text{rating scale}}$.  
      **Do:** Participants chose among $\color{red}{\text{five frequency categories}}$, from *Never* to *Every day*.

19. **Try to make each findings section header state the finding itself rather than the topic it covers.** A header that conveys ‘which aspect of what’ — the message the data support — carries more than a bare topic label or a UI feature name. The payoff is cumulative: when every header states a message, a reader who skims only the headers still follows the key messages of your findings, and that is how many reviewers first read a paper.

    * **Don’t:** $\color{red}{\text{Use of the Reflection Panel}}$  
      **Do:** $\color{red}{\text{Reflection surfaced overlooked patterns}}$

20. **Avoid orphaned figures and tables.** Every figure and every table must be referred to at least once in the main text; a float nobody cites is orphaned.


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
