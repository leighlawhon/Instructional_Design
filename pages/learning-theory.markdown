---
layout: archive
title:  "Learning Theory (LDTC 600)"
---

# Unit 1: Copyright

For this website, I have chosen the **Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International license (CC BY-NC-SA 4.0)** for my original written content and graphics, except where otherwise noted. This license allows others to share and adapt covered material for noncommercial purposes, provided they give appropriate credit, indicate whether changes were made, and distribute adaptations under the same license (Creative Commons, n.d.).

When sharing or adapting covered material, please include:

- **Author:** Leigh Lawhon
- **Title:** The article or resource title, if available
- **Source:** A link to the original article or resource
- **License:** A link to [CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/)
- **Changes:** An indication of any modifications

These terms apply to material I own and have made available under this license. Third-party material remains subject to its own licensing terms.

## Exceptions and Permissions

My original paintings and illustrations are excluded from this Creative Commons license unless explicitly labeled otherwise. Please contact me for permission to reproduce or adapt those works.

I welcome collaborations and partnerships. Please contact me to discuss commercial uses or other uses outside the license terms.

If you share or adapt my work, I would love to hear from you. Notification is appreciated but is not a condition of the license.

**Contact:** [leighlawhon@gmail.com](mailto:leighlawhon@gmail.com)

<a name="unit2"> </a>
# Unit 2: Behaviorism 

## Overview of Behaviorism

Behaviorism is an approach to psychology that emphasizes the scientific study of behavior and its relationship with the environment. Its emergence in the early twentieth century represented a shift away from introspection, which relied on people describing their conscious experiences, toward observable and measurable evidence. In his 1913 article, *Psychology as the Behaviorist Views It*, John B. Watson argued that psychology should be an objective, experimental science concerned with predicting and controlling behavior. His approach challenged prevailing assumptions about what counted as scientific evidence in psychology (Watson, 1913).

Behaviorism also provides principles for designing instruction around observable performance, practice, and consequences. In this reflection, I use my software training experience as a starting point for considering how these principles might support adult learning. 

Prior to becoming a software instructor, I was a designer turned coder. One time I got an inline comment during a review which was just a bunch of farm animals. I didn't get it. They explained that I "left so many spaces between my lines of code, cows and horses could graze". Not a great experience, but definitely an opportunity to examine how to teach and reinforce these cultural rules without sarcasm and poking at the new kid.

### Classical Conditioning

Two major learning processes associated with behaviorism are **classical conditioning** and **operant conditioning**. Classical conditioning developed from Russian physiologist Ivan Pavlov’s research on digestion and conditioned reflexes around the turn of the twentieth century. His experiments demonstrated that a previously neutral stimulus could elicit a learned response after being paired with an unconditioned stimulus (Pavlov, 1927).

The components of classical conditioning can be illustrated through a software developer example:

1. **Unconditioned stimulus (UCS):** Learners read code that is properly formatted and well documented through comments. They may not directly understand the connection, but they may notice following along is easy.
2. **Unconditioned response (UCR):** They write their own code. Writing functional code while keeping formatting clean and documentation comments clear and up to date is not as easy as it sounds. The code can work functionally, but they have difficulty reading it and explaining how it works to other learners. It takes practice to get this right.
3. **Neutral stimulus (NS):** A class code review of another team's formatting and commenting would allow learners to see coders who are praised and coders who are corrected, without being directly exposed to the feedback. Additionally, they learn to give clear, professional feedback that echos and applies the principles they have learned. 
4. **Conditioned stimulus (CS):** After repeated code reviews of their own work—a long but crucial process—the feedback becomes a signal that elicits social acceptance and avoidance of mistakes.
5. **Conditioned response (CR):** Well formatted code and comments in preparation for the code review is the learned response.

### Operant Conditioning

Operant conditioning has roots in Edward Thorndike’s animal-learning experiments in the late nineteenth century. His **law of effect** proposed that responses followed by satisfying consequences become more likely in similar situations (Thorndike, 1911). B. F. Skinner expanded the experimental study of how consequences influence behavior during the twentieth century (Skinner, 1953).

Brau et al. (2018) describe behaviorist teaching as arranging environmental conditions to encourage changes in observable behavior. For an instructional designer, this means specifying what learners should be able to do, creating opportunities to practice, and examining how consequences affect subsequent performance. 

For example, a software-training objective could require learners to apply a specified formatting and commenting procedures. The designer would need to assess whether learners perform the procedure more reliably over time, rather than assuming that completing the training establishes learning. 

A behaviorist approach to software training could establish observable objectives for formatting and commenting, such as using consistent spacing and writing comments that explain a function’s purpose. Peer review would provide social consequences or reward that might influence subsequent coding behavior. Specific approval could function as positive reinforcement if it increased adherence to those conventions, while criticism could function as punishment if it reduced a targeted behavior. However, the function of feedback depends on its observed effect rather than the reviewer’s intention (a joke) (Skinner, 1953). 

As an instructional designer, I would take a different approach to my colleagues. I would provide a style guide and review criteria rather than leave learners to infer expectations from individual preferences. I might even run an exercise where learners decide on formatting and commenting rules as a group. I would assess whether their later code followed those conventions independently. I would also monitor review participation, because feedback that improves formatting while discouraging learners from sharing their work would create another instructional concern. I might say: “Remove extra blank lines so as to follow the team's style guide" identifies the desired change more clearly while emphasizing it is a group and social norm.

The following hypothetical examples distinguish the four consequence categories from my perspective, working in my office:

| Consequence | Environmental change | Effect on future behavior | Hypothetical example |
|---|---|---|---|
| **Positive reinforcement** | Something is added | Behavior increases | Offering positive, encouraging comment when the group establishes formatting or commenting guides |
| **Negative reinforcement** | Something unpleasant is removed | Behavior increases | With better formatting and commenting, their code becomes easier to read and explain |
| **Positive punishment** | Something unpleasant is added | Behavior decreases | During regular code reviews, they get  feedback that is visible to the group and goes against group norms |
| **Negative punishment** | Something valued is removed | Behavior decreases | The independence and autonomy of merging code into the group repository is restricted. |

These examples illustrate categories rather than recommendations. I find “additive” and “subtractive” helpful reminders because **positive and negative mean adding and removing, rather than good and bad**. Reinforcement increases behavior; punishment decreases it. Classification depends on the observed effect, not the person’s intention (Skinner, 1953).

Some key dates in the development of behaviorism are presented below:

{% include behaviorism_timeline.html %}

## Implications of Behaviorism in Code Training

Behaviorism has practical implications for adult education and because it provides ways to understand learning through associations and consequences. In a very collaborative and social software development environment, social acceptance and teamwork shaped the desired actions and rewarded gradual progress toward more complex behaviors. For example, if developers, choose their own style or don't use group rules, the overall code base becomes incomprehensible and difficult for future coders to understand the intent of the code. Additionally, team cohesion suffers.

## Strengths and Limitations of Behaviorism in Code Training

Applying these techniques to animals on my farm, especially my two pigs, has helped me recognize the importance of training conditions. My pigs have learned to sit and wait for dinner in designated spots and accept brushing while they eat. However, their large enclosure and my less frequent contact with them may provide fewer opportunities for consistent practice than I had with the guide dog puppies.

These experiences do not necessarily mean that pigs are less trainable or that greater autonomy prevents learning. Instead, they lead me to consider differences in motivation, distractions, reinforcement history, and opportunities to practice. Similarly, describing a dog as “stubborn” may overlook competing rewards or a cue that has not been learned reliably in a distracting setting.

With my own dogs, I have used an electronic training collar because of concerns about safety on our rural property. I initially interpreted their rapid responses as evidence that the collar was effective. A more precise behaviorist interpretation distinguishes several processes: a shock following an action could function as positive punishment if that action decreases, while a warning beep paired with shock could acquire aversive properties through classical conditioning. This association is different from shaping a behavior through successive approximations.

However, my observations alone cannot establish the collar’s overall effectiveness or its effects on welfare. The American Veterinary Society of Animal Behavior (2021) recommends reward-based training and identifies welfare risks associated with aversive methods, including electronic collars. This evidence adds an important limitation to my personal interpretation: an immediate change in behavior does not, by itself, demonstrate that a technique produces the best long-term outcome.

My experiences suggest that behaviorism is particularly useful when the target performance is observable and can be practiced under clear conditions. In adult software training, it can guide the reinforcement of accurate procedures and increasingly independent performance. Its limitations become apparent when successful practice is treated as proof of understanding, motivation, or transfer. I would therefore use behaviorist principles as part of a broader instructional approach, assessing both immediate performance and later application. The central lesson I take from animal training is to examine what actually changes, under which conditions, and whether that change persists.

# References

American Veterinary Society of Animal Behavior. (2021). *Position statement on humane dog training*. [https://avsab.org/wp-content/uploads/2021/08/AVSAB-Humane-Dog-Training-Position-Statement-2021.pdf](https://avsab.org/wp-content/uploads/2021/08/AVSAB-Humane-Dog-Training-Position-Statement-2021.pdf)

Creative Commons. (n.d.). *Attribution-NonCommercial-ShareAlike 4.0 International (CC BY-NC-SA 4.0).* [https://creativecommons.org/licenses/by-nc-sa/4.0/](https://creativecommons.org/licenses/by-nc-sa/4.0/)

Pavlov, I. P. (1927). *Conditioned reflexes: An investigation of the physiological activity of the cerebral cortex* (G. V. Anrep, Trans.). Oxford University Press. [https://psychclassics.yorku.ca/Pavlov/lecture2.htm](https://psychclassics.yorku.ca/Pavlov/lecture2.htm)

Skinner, B. F. (1953). *Science and human behavior*. Macmillan. [https://www.bfskinner.org/wp-content/uploads/2014/02/ScienceHumanBehavior.pdf](https://www.bfskinner.org/wp-content/uploads/2014/02/ScienceHumanBehavior.pdf)

Thorndike, E. L. (1911). *Animal intelligence: Experimental studies*. Macmillan. [https://psychclassics.yorku.ca/Thorndike/Animal/chap5.htm](https://psychclassics.yorku.ca/Thorndike/Animal/chap5.htm)

Watson, J. B. (1913). Psychology as the behaviorist views it. *Psychological Review, 20*(2), 158–177. [https://doi.org/10.1037/h0074428](https://doi.org/10.1037/h0074428)


<a name="unit3"> </a>

# Unit 3: Cognativism

## Understanding How I Learn

I taught myself to code, enjoyed solving puzzles, and was placed in advanced mathematics classes in school. I loved Statistics. It made sense. I can reverse engineer, breakdown and reorganize essays, and understand the big picture of complex systems as a whole.

However, I struggled with word problems, often missed details in mathematical work, and have to force myself into details. Later in life, difficulties appeared in job interviews such as coding challenges and annalist assessments. Understanding how to code or calculate the optimal discount for a sale did not mean I could reliably solve a basic problem presented through verbal instructions. I would practice these for hours before an interview, trying different methods and they never worked. My brain just didn't work that way and I gave up. I felt dumb.

Cognitivism provides a framework for examining this gap because it focuses on the processes involved in attending to, interpreting, organizing, storing, and retrieving information. My experiences with dyslexia and ADHD provide personal context, but neither label fully explains how I overcame these challenges and succeeded as a life-long learner. 

My personal experiences provide a lens for evaluating cognitivism and I argue that cognitivism offers valuable principles for instructional design, particularly when designers investigate learners’ strategies and prior knowledge while preparing them to apply knowledge independently.

But, how does one instructor do that for a whole classroom and how do they prepare without an understanding of each learner's unique perspective.

### From Observable Performance to Cognitive Processes

Cognitivism developed partly in response to the limitations of explaining learning primarily through observable behavior. Michela (2018) identifies research on expectations, insight, and purposeful activity by researchers such as Edward Tolman and Wolfgang Köhler during the 1920s and 1930s as important precursors. Cognitive approaches gained prominence during the 1950s, directing greater attention toward what happens between receiving information and producing a response, the "Black Box."

Cognitivism encompasses multiple theories rather than one universally accepted explanation, which I like. It's complex and evolves as one gets older. Information-processing approaches examine attention, working memory, encoding, and long-term memory. Cognitive load theory examines the demands that learning places on limited processing resources. Self-regulated learning, one of my favorite topics, emphasizes learners’ roles in planning, monitoring, and adjusting their learning (Michela, 2018). Are instructional designers capable of addressing this complex matrix for every learner?

For teaching, these approaches shift attention toward how learners interpret a task and select strategies. An incorrect answer might reflect a calculation error, a misunderstood relationship, an ineffective strategy, or difficulty coordinating information. The answer alone cannot establish which explanation applies. I myself how and why a mathematical word problem flummoxed me every time.

This distinction matters to me because I was described as smart but as someone who did not apply herself. I remember being curious, experimenting, and trying new things. I could sit still and work on homework, yet miss details and need to reread. Cognitivism encourages a more informative question than whether I tried hard enough: what processes did the task require, and where did my approach stop working?

### Attention, Encoding, and Prior Knowledge

My attention varies considerably across activities. I can paint or write for hours, while I continuously interrupt myself with distractions trying to settle into monthly bills and piled up mail. Michela (2018) explains that attention is influenced by factors including familiarity, motivation, and individual differences. This helps me consider the interaction between the learner and the task without assuming that sustained attention in one setting should automatically occur elsewhere.

Encoding is particularly meaningful to me. I think of it as "known, unknown, and unknown-unknown" and I build paths connecting dots, even when they are disparate. Michela (2018) describes organization, elaboration, and schemas as processes that connect new information with existing knowledge. Elaboration involves expanding information or connecting it to something already understood. Schemas provide structures through which situations and relationships can be interpreted.

My experience teaching myself to code helps me form a mental model of these connections. I began with conditional (IF ELSE) functions in Excel and, as an Adobe software instructor, became curious about how software was organized in order to teach it. Building websites and portfolios later gave me reasons to learn HTML, JavaScript, ActionScript, and CSS. A curriculum of necessity that started a career.

When a website required Django/Python, I used two books. An older book provided a tutorial for a content management system similar to what I needed. A newer book explained related concepts using the current language version. I followed the older project while reconstructing its implementation through the newer material. I had to create a workable sequence by comparing what remained consistent with what had changed.

This was purposeful, active learning. New information revised the organization of what I knew. I recognize a similar process in painting multiple versions of one subject. Comparing compositions and experimenting with color and brush work helps clarify my decisions. Sometimes the painting I initially like least becomes the most successful because it provides room to experiment. Sometimes they just get shoved in a corner.

### Guidance, Interaction, and Multiple Perspectives

Jerome Bruner’s work provides a way to examine instructional support. Wood et al. (1976) described scaffolding through a study of tutoring young children in a construction task. Their account emphasizes assistance that allows learners to address parts of a task they could not initially manage alone. Although this was not a study of dyslexia or ADHD, it offers a useful question for my context: which aspects of a professional learning task require support and which supports work for an individual? How can I teach myself math word problems when supports haven't worked?

My books provided structures I could adapt, but videos demonstrating interview solutions did not produce the same outcome. The explanations made sense while I watched. When I attempted exercises independently, I struggled for hours. This suggests that a complete demonstration may need additional support that helps a learner identify why a particular step is appropriate and when to use it.

Lev Vygotsky contributes a related sociocultural perspective. His zone of proximal development concerns the distance between what learners can accomplish independently and what they can accomplish with guidance (Vygotsky, 1978). The publication date of *Mind in Society* reflects a posthumous collection of his earlier work.

For me, the ZPD raises questions about the fit of assistance. Coaching did not always resolve my difficulty constructing a solution. That experience does not disprove the theory, but it makes me question whether the assistance addressed the point where my understanding broke down. Social interaction also needs attention to its quality; participation alone does not establish that an interaction supports learning.

Rand Spiro and colleagues offer another connection through cognitive flexibility theory. Their work addresses advanced knowledge acquisition in complex, ill-structured domains, emphasizing multiple representations and contexts (Spiro et al., 1988). My two-book experience provides a personal analogy: comparing implementations helped me reconstruct concepts. However, applying this theory to my experience is an interpretation, not evidence that the approach has been validated for my learning differences.

### What Word-Problem Research Contributes

Research by Fuchs et al. (2018) helps clarify why calculation ability and word-problem performance should be examined separately. They followed 325 second-grade students, assessing cognitive, language, reading, and mathematical skills near the beginning and end of the school year. Initial language ability predicted later word-problem outcomes more strongly than calculations, while initial arithmetic skill predicted calculations more strongly than word-problem outcomes.

Text comprehension predicted all outcomes, and contrary to the researchers’ expectations, its predictive strength was comparable across calculations and word-problem outcomes. These findings support a nuanced relationship rather than a complete separation between mathematical and language processes, and is reinforced by my highschool SAT scores.

The authors explain word-problem solving through the construction of representations, inferences, and relationships among quantities. Their instructional discussion emphasizes language and problem representation alongside computation. This connects to my experience of understanding the requested outcome without being able to construct the solution.

The study involved children and did not test an instructional intervention. It cannot explain my adult interview experiences or establish their cause. Nevertheless, it supports asking whether instruction addresses interpreting relationships and organizing a solution rather than concentrating mainly on calculation practice.

### Implications for Instructional Design

In adult professional learning, I would begin by identifying the decisions a task requires and gathering evidence about where learners struggle. For a word problem, an assessment might separately ask learners to explain the goal, represent relationships, propose an initial step, and justify that choice. Those responses could be more informative than a single final answer.

This approach also offers a manageable starting point for a large class, an implementation I have struggled with. An instructor could collect brief responses, identify recurring difficulties, and provide temporary groups or targeted prompts. The instructor would still need to monitor individual progress, but would not have to create bespoke material for each student.

Self-regulated learning provides another useful principle. My self-directed projects involved goals, resources, experimentation, and strategy changes. In teaching, I would make those processes visible rather than assume learners already know how to manage them. Learners could set a goal, choose a strategy, evaluate its effect, and decide what to change. Michela (2018) emphasizes planning, self-monitoring, and feedback as relevant design considerations.

Bandura’s (2001) social cognitive theory further connects agency with personal and environmental influences. Personal  responsibility must be considered alongside available opportunities and support. Motivation and confidence matter, but they do not guarantee successful performance. Having a deadline and a paycheck that depends on success seems to have shaped my sense of responsibility and grit.

My recent use of conversational AI has helped me connect cognitivism to personal experiences through questions and reflection. This may offer an instructional possibility, but I have not established that it improves my independent word-problem solving. That would require practice and assessment without the conversational assistance.

### Evaluating an Online Instructional Material

The instructional material I selected is OpenStax’s [“Use a Problem-Solving Strategy”](https://openstax.org/books/elementary-algebra-2e/pages/3-1-use-a-problem-solving-strategy), from *Elementary Algebra 2e*. The lesson introduces a seven-step strategy for algebra word problems. It includes prerequisite checks, worked solutions, and practice opportunities (Marecek et al., 2020). 

First off, the opening emphasis on positive thinking likely would not help, as my bad experiences are deeply engrained. I personally needed help identifying and practicing the missing reasoning.

The first cognitive load principle is **demonstrating problem solving to reduce unnecessary search demands**. Michela (2018) identifies demonstrations as one strategy for managing cognitive load. OpenStax’s first example shows how to translate a purchase scenario into an equation, solve it, and check the answer. My proposed improvement would add prompts asking learners to explain the mathematical relationship based on the question.

For example, before asking students to provide the answer, I would ask, “Which amount is half of the other? Why?” A student might explain that the $18 sale price represents half of the unknown original price, leading to the equation \(18 = \frac{1}{2}p\). Perhaps this prompt would help the instructor distinguish difficulty interpreting the relationship from difficulty performing the calculation.

The second principle is **organizing information into manageable components**. The lesson’s numbered stages and solution tables provide structure. For learners like me, I would supplement these with partially completed problems and feedback at the representation stage, before requiring a full solution. 

Example 3.5 is where the lesson becomes especially abstract for me. There is no real world mental model for me. The instruction to express two numbers using one variable assumes that I can translate their relationship into symbols. I would add a simple visual showing two equal unknown lengths, with five extra tick marks attached to the second. This would make “five more” visible: removing those five extras from the combined total of 21 leaves 16 shared equally between the two matching lengths. Each length therefore represents 8, making the numbers 8 and 13. Placing the visual beside the equation could help connect the wording to the mathematical relationship, reducing the need to hold that relationship entirely in working memory.

Something like this:

![Figure]({{ '/assets/images/tickmarks.jpeg' | relative_url }})

### Strengths, Limitations, and Future Questions

Cognitivism’s greatest strength in my context is its attention to processes that an answer cannot fully reveal. It encourages designers to investigate prior knowledge, interpretation, memory demands, and strategy use. Its limitation is that these processes are difficult to infer, and responsive assessment requires time. A broad framework does not automatically identify the right assistance.

I also question personalization that keeps instruction within familiar interests. Analogies such as explaining economics through a grocery store may provide an entry point, but education, particularly in the AI era, should introduce relationships and perspectives beyond that analogy. I would personalize support while deliberately expanding learners world views once they can accomplish the learning objective.

This connects to my emerging idea of perspective learning: comparing representations and experiences to identify similarities, conflicts, and new possibilities. I believe it is the only way to elevate education toward the unknown-unknown and a more multi-faceted understanding of the world. For now, it remains an idea to investigate. Cognitivism gives me a foundation for asking how those comparisons support understanding—and how instruction can help that understanding become independent performance.

### References

Bandura, A. (2001). Social cognitive theory: An agentic perspective. *Annual Review of Psychology, 52*, 1–26. https://doi.org/10.1146/annurev.psych.52.1.1

Fuchs, L. S., Gilbert, J. K., Fuchs, D., Seethaler, P. M., & Martin, B. N. (2018). Text comprehension and oral language as predictors of word-problem solving: Insights into word-problem solving as a form of text comprehension. *Scientific Studies of Reading, 22*(2), 152–166. https://doi.org/10.1080/10888438.2017.1398259

Marecek, L., Anthony-Smith, M., & Mathis, A. H. (2020). *Elementary algebra 2e*. OpenStax. https://openstax.org/details/books/elementary-algebra-2e

Michela, E. (2018). Cognitivism. In R. Kimmons (Ed.), *The students’ guide to learning design and research*. EdTech Books. https://edtechbooks.org/studentguide/cognitivism

Spiro, R. J., Coulson, R. L., Feltovich, P. J., & Anderson, D. K. (1988). *Cognitive flexibility theory: Advanced knowledge acquisition in ill-structured domains* (Technical Report No. 441). University of Illinois at Urbana-Champaign, Center for the Study of Reading. https://files.eric.ed.gov/fulltext/ED302821.pdf

Vygotsky, L. S. (1978). *Mind in society: The development of higher psychological processes* (M. Cole, V. John-Steiner, S. Scribner, & E. Souberman, Eds.). Harvard University Press.

Wood, D., Bruner, J. S., & Ross, G. (1976). The role of tutoring in problem solving. *Journal of Child Psychology and Psychiatry, 17*(2), 89–100. https://doi.org/10.1111/j.1469-7610.1976.tb00381.x

<a name="unit4"> </a>

# Unit 4: Constructivim

At the fictional Harbor Community College, 24 adult learners enroll in a six-week Community Futures Studio. The studio belongs to a proposed interdisciplinary degree pathway in which students build a coherent education through demonstrated competencies and faculty advising rather than declaring a conventional major. Its central question is: How could a neighborhood library become a more accessible community learning space within a limited budget? Students investigate a fictional library using an instructor-prepared floor plan, anonymized visitor data, accessibility observations, interview transcripts, and cost estimates. They must develop, test, and defend an improvement proposal. The scenario combines spatial design, statistics, communication, technology, and civic decision-making around one consequential problem.

Students arrive with different entry points. Maya can sketch spaces and recognize visual patterns but cannot independently interpret visitor data. Luis can calculate costs but struggles to incorporate qualitative evidence. Amina can analyze interview themes but needs support designing a fair prototype test. These fictional profiles illustrate provisional starting points, not fixed learner categories. An entry point includes existing knowledge, interests, language, practical experience, and confidence in a particular context. Initial interviews, concept maps, and short performance tasks reveal these resources. Following the evidence on prior knowledge and learning contexts, the instructor uses this information to connect new demands to existing understanding while checking for misconceptions (National Academies of Sciences, Engineering, and Medicine [NASEM], 2018).

Constructivism guides the studio because students develop explanations through investigation and revision. Piaget's (1936/1952) distinction between assimilation and accommodation helps explain the intended change: students may incorporate evidence into an existing schema or revise that schema when it cannot adequately explain what they encounter. For example, a team initially assumes that additional digital kiosks will improve access. A prototype test reveals that the placement obstructs movement and that some visitors prefer human assistance. This discrepancy creates an opportunity to reconsider the team's definition of accessibility. Cognitive equilibrium represents a more coherent, revisable explanation. The instructor supports the reasoning process through questions, demonstrations, and feedback; constructing understanding does not require unguided discovery.

The studio adapts the BSCS 5E sequence: Engage, Explore, Explain, Elaborate, and Evaluate (BSCS Science Learning, n.d.). During Engage, students compare competing visitor accounts and record predictions about the library's problems. During Explore, teams examine the supplied evidence, build inexpensive models, and conduct structured role-based walkthroughs. During Explain, they present their initial interpretations before receiving targeted instruction on sampling, accessibility criteria, and evidence-based claims. During Elaborate, they revise a prototype and test it under a new constraint, such as reduced funding or increased attendance. During Evaluate, they defend their conclusions, assess the limits of their evidence, and complete an independent transfer task. Reflection occurs throughout the cycle.

Each team tests two versions of one intervention, such as signage, seating arrangements, or a service-information interface. Students predict an outcome, identify what they will measure, keep relevant conditions consistent, and document unexpected results. Classmates test navigation tasks while following assigned constraints, and teams compare completion patterns and feedback. These classroom simulations cannot represent every disability or establish actual community effectiveness. Students therefore distinguish prototype evidence from claims requiring consultation with real users. The instructor evaluates the quality of the investigation and revision rather than whether a team's first design succeeds. An unsuccessful prototype can generate valuable evidence when learners explain what it reveals.

Vygotsky's (1978) Zone of Proximal Development distinguishes independent performance from performance possible with capable assistance. The instructor identifies each learner's ZPD through a brief attempt, a graduated prompt, and another attempt. A task belongs within the learner's working ZPD when assistance enables meaningful progress that independent performance does not yet support. If even substantial guidance produces little understanding, the instructor first addresses prerequisite knowledge. The three skills below are initial hypotheses that must be confirmed individually.

## Skills

    - skill: "Interpret quantitative evidence alongside community perspectives"
      independent_start: |-
        Learners can read a simple table or summarize an interview but cannot yet independently reconcile conflicting numerical and qualitative findings.
      guided_performance: |-
        With a partially completed comparison chart and instructor prompts, learners connect visitor counts with interview themes, question whose perspectives are missing, and qualify an interpretation.
      independent_target: |-
        Each learner analyzes a fresh evidence packet, makes a supported claim, and identifies one limitation without the chart or interpretive prompts.
    - skill: "Design and interpret a fair prototype comparison"
      independent_start: |-
        Learners can suggest improvements but cannot yet separate an appealing idea from a testable claim or control major differences between trials.
      guided_performance: |-
        Using a modeled example and peer questioning, learners define a measurable outcome, maintain comparable testing conditions, and explain alternative reasons for a result.
      independent_target: |-
        Each learner designs a small comparison for an unfamiliar service problem, interprets supplied results, and proposes a justified revision.
    - skill: "Integrate disciplinary perspectives into a defensible recommendation"
      independent_start: |-
        Learners can explain an issue through a familiar perspective but cannot yet independently balance spatial, financial, and community considerations.
      guided_performance: |-
        A decision matrix and facilitated dialogue help learners compare competing criteria, explain trade-offs, and revise a proposal when another discipline exposes a weakness.
      independent_target: |-
        Each learner defends a recommendation using at least two disciplinary perspectives and explains how an additional constraint would change the decision.

## Scaffolding and Social Constructivism:

  contingent_support: |-
    The primary scaffolding strategy is a model-practice-fade sequence. Wood et al. (1976) describe tutoring functions that include simplifying a task, maintaining direction, highlighting important features, and managing frustration. In this studio, the instructor first thinks aloud through an unrelated example, demonstrating how to distinguish a claim from evidence and uncertainty. Students then use a partially completed evidence chart and test-planning checklist. During conferences, the instructor begins with an open question, adds a cue if needed, and models one step only when lesser assistance is insufficient. Support responds to observed difficulty rather than a predetermined label. Templates gradually lose prompts, and learners ultimately tackle an individual problem without interpretive assistance.
  collaborative_knowledge_construction: |-
    The social constructivist approach is a reciprocal expertise exchange. Teams initially divide evidence among temporary investigation groups focused on spatial access, resource allocation, or visitor communication. Students return to their project teams and teach the reasoning behind their findings. Peers must paraphrase the explanation, identify an uncertainty, and ask a question that could change the recommendation. Teams then produce a shared decision record documenting disagreements, supporting evidence, and revisions. This makes collaboration an opportunity to negotiate meaning rather than simply divide production tasks. Consistent with Vygotsky's (1978) emphasis on socially mediated learning, dialogue supports reasoning that individuals subsequently practice independently. Rotating roles prevents initial strengths from becoming permanent disciplinary boundaries.
  differentiation_and_diversity: |-
    Differentiation begins with the diagnostic evidence and continuing learner feedback. A student unfamiliar with spreadsheets receives a short prerequisite activity; a student already proficient in basic analysis investigates sampling bias or uncertainty. Evidence packets include accessible text, labeled visuals, and captioned demonstrations, with equivalent access to the same substantive information. Multilingual learners may annotate in a preferred language, use a glossary, and rehearse explanations before discussion. Learners can present through writing, recorded explanation, or an accessible visual presentation when each format demonstrates the required reasoning. Flexible meeting arrangements and downloadable materials support working adults. Accessibility tools remain available during independent assessment; fading concerns reasoning support, not removal of accommodations.

The instructor also checks whose assumptions shape the project. Interview accounts deliberately include conflicting priorities and perspectives without assigning any learner responsibility for representing a cultural group. Quiet reflection precedes discussion, and rotating facilitation gives students multiple ways to contribute. Learners may question the fictional brief or propose an alternative intervention if they can justify its relevance. These choices preserve agency while keeping expectations visible. Difficulty is treated as information about the interaction among the learner, task, and support. This approach aims to make uncertainty manageable, including for learners who associate evaluation with embarrassment or a threat to competence.
unique_exit_points_and_cross_disciplinary_completion:
  competency_and_completion: |-
    Every learner has a unique exit point: a documented combination of demonstrated abilities, changed understanding, and emerging questions. However, completion requires common minimum competencies. The proposed rubric rates evidence interpretation, experimental reasoning, disciplinary integration, and reflection on four levels. Students must reach the proficient level in every dimension, supported by both project evidence and an independent transfer task. Group success alone cannot establish individual competence. Students who need further work receive targeted feedback and another opportunity to demonstrate the missing competency. Exit points therefore recognize distinctive achievements while preserving a meaningful completion standard. The portfolio records the starting evidence, assistance provided, revisions, final independent performance, and proposed next challenge.
  expanding_range: |-
    One learner might finish with a strong accessibility prototype and new statistical reasoning; another might develop a persuasive resource-allocation model and improved qualitative analysis. Their next studios could connect those achievements to public health, environmental planning, or information systems. Epstein's (2019) Range argues for the value of broad experience and connections across domains, especially in complex environments. Here, that argument informs a proposed educational structure rather than proving that majors should disappear. Faculty advisers would help students assemble increasingly demanding projects, maintain essential disciplinary foundations, and explain the coherence of their education. Breadth becomes purposeful when students integrate perspectives and demonstrate depth, rather than merely accumulate unrelated experiences.
machine_learning_and_ai_resources:
  proposed_role: |-
    Machine learning could help maintain an evolving map of competencies and suggest appropriate challenges. Knowledge tracing models estimate aspects of student knowledge from coursework interactions; Piech et al. (2015) demonstrated recurrent neural networks for predicting student performance. Prediction, however, does not establish a learner's full understanding or identify a ZPD automatically. In the proposed studio, a system could flag repeated difficulty connecting claims to evidence, recommend a scaffold, or suggest an adjacent discipline that would extend an existing strength. Learners and instructors would review these suggestions together. The system would offer several routes and invite correction, including exploration outside patterns inferred from earlier performance.

    A separate generative AI tool could provide instructor-reviewed practice questions, alternative examples, and simulated objections to a proposal. It would ask learners to explain predictions before offering hints, preserving opportunities for discovery and revision. Neither tool would independently certify completion. Instructors would verify consequential judgments through portfolios, conferences, and unaided reasoning tasks. Students could choose equivalent activities without AI, inspect recommendations, and challenge inaccurate profiles. Data collection would be limited to relevant learning evidence, with clear consent and access arrangements. These design commitments align with the human-centered orientation of Miao and Holmes (2023). A pilot would examine learning gains, recommendation errors, accessibility, and unequal patterns of support before expansion.
reflective_analysis: |-
  This scenario treats learning as developing and revising a system of meaning through purposeful activity. Unique entry points establish where instruction can connect; ZPD assessment identifies what assistance makes possible; scaffolding bridges the gap toward independent performance. Social interaction exposes assumptions that solitary work may leave unexamined. Cross-disciplinary problems create a reason to integrate perspectives because no single lens sufficiently addresses the design challenge. The anticipated outcomes are stronger evidence-based reasoning, more deliberate experimentation, and greater capacity to explain trade-offs. These remain predictions to evaluate through baseline tasks, independent exit assessments, and a delayed transfer activity rather than assumed consequences of participation.

  The broader proposal is an education organized around evolving competency profiles and connected inquiries, potentially offering an alternative to a conventional major. Its credibility depends on transparent standards, sustained advising, disciplinary depth, and recognition beyond the classroom. Machine learning could help coordinate possible routes, while human judgment protects room for unexpected interests and growth. Each exit point becomes a possible entry into another inquiry. Successful completion therefore marks a defensible achievement and a newly visible horizon for learning, supporting a lifelong capacity to encounter unfamiliar questions with curiosity and increasingly effective strategies.
ai_use_disclosure: |-
  The originating ideas about unique entry and exit points, education beyond a conventional major, expanding range, and cross-disciplinary learning were supplied by the student. An OpenAI assistant generated this draft, developed the fictional scenario, and helped locate and check reference information. The proposed classroom AI and machine-learning functions are design suggestions, not implemented or evaluated systems. Course-specific readings and the syllabus AI policy were not supplied; their integration and any required AI citation remain to be checked before submission.
references:
  - |-
    BSCS Science Learning. (n.d.). *The BSCS 5E instructional model: Origins and effectiveness*. https://bscs.org/reports/the-bscs-5e-instructional-model-origins-and-effectiveness/
  - |-
    Epstein, D. (2019). *Range: Why generalists triumph in a specialized world*. Riverhead Books.
  - |-
    Miao, F., & Holmes, W. (2023). *Guidance for generative AI in education and research*. UNESCO. https://doi.org/10.54675/EWZM9535
  - |-
    National Academies of Sciences, Engineering, and Medicine. (2018). *How people learn II: Learners, contexts, and cultures*. The National Academies Press. https://doi.org/10.17226/24783
  - |-
    Piaget, J. (1952). *The origins of intelligence in children* (M. Cook, Trans.). International Universities Press. (Original work published 1936)
  - |-
    Piech, C., Bassen, J., Huang, J., Ganguli, S., Sahami, M., Guibas, L. J., & Sohl-Dickstein, J. (2015). Deep knowledge tracing. In C. Cortes, N. D. Lawrence, D. D. Lee, M. Sugiyama, & R. Garnett (Eds.), *Advances in neural information processing systems* (Vol. 28, pp. 505–513). Curran Associates, Inc. https://proceedings.neurips.cc/paper/2015/hash/bac9162b47c56fc8a4d2a519803d51b3-Abstract.html
  - |-
    Vygotsky, L. S. (1978). *Mind in society: The development of higher psychological processes* (M. Cole, V. John-Steiner, S. Scribner, & E. Souberman, Eds.). Harvard University Press. https://doi.org/10.2307/j.ctvjf9vz4
  - |-
    Wood, D., Bruner, J. S., & Ross, G. (1976). The role of tutoring in problem solving. *Journal of Child Psychology and Psychiatry, 17*(2), 89–100. https://doi.org/10.1111/j.1469-7610.1976.tb00381.x


# Unit 5

# Unit 6

# Unit 7

# Unit 8