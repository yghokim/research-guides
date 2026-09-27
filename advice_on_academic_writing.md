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
