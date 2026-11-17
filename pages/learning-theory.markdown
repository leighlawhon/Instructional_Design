---
layout: home
title:  "Learning Theory (LDTC 600)"
author_profile: true
author: Leigh Lawhon
---

{%include page_toc.html%}
<a name="#unit1"></a>
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

### Key Dates:
{% include behaviorism_timeline.html %}

## Personal Context

Before becoming a software instructor, I was a designer turned coder. During one code review, a colleague left an inline comment containing farm animals. I did not understand the message until they explained that I had left so much space between lines of code that cows and horses could graze there. Although the comment called attention to formatting, it did not clearly explain the expected convention. This experience led me to consider how instructors can teach team coding standards through explicit expectations and professional feedback.

## Classical Conditioning

### Explanation

Classical conditioning occurs when a previously neutral stimulus acquires the ability to elicit a response through association with another stimulus (Pavlov, 1927). In code review, this process can help explain learned emotional reactions to code reviews. Learning to format code in response to consequences is better explained through operant conditioning.

### Developer Code Review Example

#### Context

A new developer repeatedly encounters humiliating feedback during code review. Over time, a code review assignment may begin to elicit apprehension before the developer reads the comments. 

#### Unconditioned Stimulus

Stress and distancing from the team becomes associated with code reviews.

#### Unconditioned Response

The developer's immediate distress in response to social and negative feedback.

#### Neutral Stimulus

A code review that initially produces no particular distress.

#### Conditioned Stimulus

The code review assignment after repeated pairings with distressing feedback.

#### Conditioned Response

Anticipatory apprehension when the assignment appears, before the feedback is read.

### Instructional Implication

This interpretation reminds me that review conditions can shape how learners feel about participating. I would make feedback predictable, respectful, and focused on the submitted code. I would also ask learners about their review experiences rather than assume that participation or silence reveals their emotional response.

## Operant Conditioning

### Explanation

Operant conditioning concerns how consequences influence subsequent behavior. Thorndike's (1911) law of effect proposed that responses followed by satisfying consequences become more likely in similar situations. Skinner (1953) expanded the study of relationships between behavior and its consequences.

Positive and negative refer to adding and removing something. Reinforcement increases the future likelihood of a behavior, while punishment decreases it. A consequence is classified by its observed effect, not simply by the reviewer's intention.

### Observable Objective

Given the team's style guide and a code review checklist, developers will submit code that follows agreed spacing conventions and includes accurate comments explaining purpose or non-obvious reasoning. Progress will be assessed across later submissions, including work completed without instructor reminders.

### Developer Code Review Consequences

#### Positive reinforcement

**Environmental Change:** Something is added.

**Example:** A reviewer gives specific recognition (an emoji) when a developer submits code that follows the team's formatting and commenting standards.

**Required Observed Effect:** Adherence to those standards increases in subsequent submissions.

#### Negative reinforcement

**Environmental Change:** Something aversive is removed.

**Example:** A developer corrects formatting problems, which stops the repeated formatting warnings in the console. This qualifies as negative reinforcement because the warnings are highlighted red and yellow and their removal strengthens the behavior.

**Required Observed Effect:** Submitting correctly formatted code becomes more frequent because it prevents or ends the warnings.

#### Positive punishment

**Environmental Change:** Something aversive is added.

**Example:** A reviewer adds a reprimand after a developer submits code with excessive blank lines. This is a consequence and does happen, but it is not a recommended teaching practice.

**Required Observed Effect:** The targeted spacing behavior decreases in subsequent submissions.

#### Negative punishment

**Environmental Change:** Something valued is removed.

**Example:** A developer temporarily loses valued permission to merge independently.

**Required Observed Effect:** Adherence to formatting rules increases subsequent work.

### Interpretation

These categories depend on evidence about later behavior. Praise is not automatically reinforcement, and corrective feedback is not automatically punishment. Feedback may also provide information about how to improve. A review process should therefore examine both compliance with coding conventions and willingness to submit work, ask questions, and participate, which may be better addressed one-on-one, rather than in a group.

## Instructional Application

### Explicit Expectations

I would provide a style guide and review criteria before the first submission. Developers could discuss the reasons behind formatting and commenting conventions and help establish team rules where appropriate. This would make the expected performance visible and give learners a voice in shared standards.

### Practice And Feedback

Developers would practice reviewing code against the same criteria used to assess their own submissions. I would model comments that identify the issue, explain its effect, and describe a concrete revision. For instance: "Remove the extra blank lines between these statements to follow the team's spacing convention."

### Gradual Independence

Early reviews would include prompts and specific recognition of progress. As learners become more consistent, I would reduce reminders and ask them to check their own code before requesting review. 

### Assessment

I would compare initial and later submissions for adherence to agreed conventions and track whether developers can apply them independently. I would also ask learners to explain their decisions and review unfamiliar code. These additional tasks would help distinguish repeated compliance from understanding and transfer.

## Strengths and Limitations

Behaviorism is useful in developer training when the target performance is observable, expectations are clear, and learners have repeated opportunities to practice. Code review provides timely information and consequences that may support consistent formatting, accurate comments, and adherence to team procedures.

However, a correctly formatted submission does not establish that a developer understands the code, can evaluate a convention critically, or can apply learning in another project. Reviewers may also unintentionally reinforce superficial compliance or discourage participation. A learner who avoids submitting code may appear to not be a team player.

I would therefore combine observable performance measures with explanations, discussion, and later application. My experience with sarcastic feedback reinforces the importance of checking what a review process actually changes, whether the change persists, and how the process affects learners' willingness to participate.

## Reflection

My central takeaway is that effective code review requires more than identifying mistakes. As an instructor, I need to define expectations, provide opportunities to practice, and examine how feedback influences future behavior. Behaviorist principles help explain those relationships, while a broader instructional approach helps me assess understanding, independence, and collaboration.

## References

Pavlov, I. P. (1927). *Conditioned reflexes: An investigation of the physiological activity of the cerebral cortex* (G. V. Anrep, Trans.). Oxford University Press. https://psychclassics.yorku.ca/Pavlov/lecture2.htm

Skinner, B. F. (1953). *Science and human behavior*. Macmillan. https://www.bfskinner.org/wp-content/uploads/2014/02/ScienceHumanBehavior.pdf

Thorndike, E. L. (1911). *Animal intelligence: Experimental studies*. Macmillan. https://psychclassics.yorku.ca/Thorndike/Animal/chap5.htm

Watson, J. B. (1913). Psychology as the behaviorist views it. *Psychological Review, 20*(2), 158–177. https://doi.org/10.1037/h0074428


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
# Constructivism in an In-Person Library Signage Workshop

## Overview of Constructivism

Constructivism holds that learners actively construct understanding by connecting new information to existing knowledge and experiences. An instructor can provide information, examples, and explanations, but learners must interpret and integrate them. Teaching therefore involves creating opportunities for investigation, discussion, experimentation, and reflection.

Constructivism developed through several related traditions rather than originating with one researcher or publication.

{% include constructivism_timeline.html %}

These contributions connect individual meaning-making with learning through social interaction. Piaget emphasizes changes in the learner’s cognitive structures, while Vygotsky emphasizes the social and cultural mediation of development. Scaffolding provides a practical connection between challenging tasks and supported participation (Piaget, 1936/1952; Vygotsky, 1978; Wood et al., 1976).

## Implications for Instructional Design

Constructivist learning design begins by identifying what learners already understand and creating a meaningful problem that requires them to extend that understanding. In an **in-person library signage workshop**, the central challenge could be:

> How can we redesign library signs so that first-time visitors can locate important services more easily?

Participants might include library employees, volunteers, and community members. They would work with temporary signs and prototypes before recommending permanent changes.

### Recognize Unique Entry Points

Participants will approach the problem through different experiences. A library employee may understand common visitor questions, a community member may recognize confusing terminology, and a participant with design experience may notice problems with visual hierarchy.

The facilitator can begin with a brief navigation task and discussion:

- Which signs helped you make a decision?
- Where did you hesitate?
- What knowledge did the signs assume you already had?
- What would a first-time visitor need?

These activities reveal existing knowledge and assumptions. Entry points guide support and participation without becoming fixed labels that restrict what someone can learn.

### Design for Discovery and Experimentation

Participants should investigate how signs function in the actual library. Small groups can select a destination, observe decision points, and create two alternative signs. They can then test the prototypes with consenting participants unfamiliar with the route.

For example, a group might compare “Circulation” with “Borrow and Return Books.” Before testing, learners predict which wording will be clearer and explain why. They then record wrong turns, requests for assistance, and participant comments.

A mismatch between predictions and observations gives learners a reason to revise their understanding. They may discover that terminology familiar to employees is unfamiliar to visitors, or that placement matters as much as wording.

### Provide Scaffolding Within the ZPD

Constructivism does not require learners to discover every design principle independently. Participants may need guidance to:

- Translate specialized terminology into clear language.
- Design a comparison that produces useful evidence.
- Explain design decisions using observations rather than preferences.

The facilitator can model one example, provide a test-planning checklist, and ask questions such as, “What changed between these versions?” or “What evidence supports that conclusion?” As learners become more capable, the facilitator reduces prompts and asks them to plan and justify their own revisions.

This approach reflects scaffolding as responsive assistance rather than a permanent template (Wood et al., 1976).

### Support Collaborative Knowledge Construction

Groups should discuss competing interpretations rather than simply divide tasks. One participant might favor a visually striking sign, while another questions whether its language is understandable. The group must examine evidence and negotiate a recommendation.

Rotating roles—designer, observer, tester, and discussion facilitator—allows participants to practice beyond their initial strengths. Collaboration becomes a way to encounter alternative perspectives and reconsider assumptions.

### Assess Learning Through Performance and Reflection

Assessment should examine both the resulting sign and the reasoning behind it. Each participant could explain:

1. Their original assumption.
2. What the test revealed.
3. How they revised the design.
4. How they would apply the lesson to another location.

Participants may have **unique exit points**, such as improved visual communication, stronger testing skills, or greater awareness of visitor perspectives. Nevertheless, everyone should meet shared minimum expectations: identify a navigation problem, use evidence to justify a revision, and explain relevant limitations.

## Strengths and Limitations

### Strengths

In my view, constructivism is particularly appropriate for a library signage workshop because the problem requires judgment in context. A sign’s usefulness depends on its wording, placement, surrounding environment, and audience. Working in the library allows participants to examine those relationships directly.

The approach also encourages participants to question familiar assumptions. Employees may know where everything is and underestimate how much interpretation a visitor must perform. Observing someone navigate can make that gap visible and provide a concrete reason to reconsider a design.

Another strength is **cross-disciplinary learning**. Signage connects graphic design, language, spatial reasoning, accessibility, and user research. Participants can enter through a familiar area and expand their understanding through another. Someone interested in typography, for example, may discover the importance of testing and observation.

Finally, constructing and defending a revision makes learning visible. Participants demonstrate how their thinking changed, rather than merely repeat design vocabulary.

### Limitations

The main limitation is the possibility of insufficient guidance. Beginners may spend considerable time experimenting without recognizing why a design succeeds or fails. Alfieri et al. (2011) distinguished unassisted discovery from supported discovery, finding more favorable results for approaches that incorporated assistance. I would therefore combine exploration with concise demonstrations, feedback, and explicit instruction.

Time is another constraint. Conducting observations, creating prototypes, testing, and revising may exceed a short workshop. I would limit each group to one destination and one focused design question.

Group participation can also be uneven. Confident participants may dominate decisions, while others defer despite having useful insights. Individual reflection before discussion, rotating roles, and individual explanations would help reveal each learner’s understanding.

Finally, a small workshop test cannot establish that signage works for every visitor. Classmates cannot represent the full diversity of library users. I would treat the prototypes as preliminary proposals requiring broader user feedback and review against applicable accessibility requirements.

My judgment is that constructivism offers a strong foundation for this workshop when inquiry is paired with clear guidance and credible evidence. The facilitator’s role is to help participants turn observations into increasingly defensible decisions.

## References

Alfieri, L., Brooks, P. J., Aldrich, N. J., & Tenenbaum, H. R. (2011). Does discovery-based instruction enhance learning? *Journal of Educational Psychology, 103*(1), 1–18. [https://doi.org/10.1037/a0021017](https://doi.org/10.1037/a0021017)

Bruner, J. S. (1961). The act of discovery. *Harvard Educational Review, 31*, 21–32. [Article reprint](https://digitalauthorship.org/wp-content/uploads/2015/01/the-act-of-discovery-bruner.pdf)

Dewey, J. (1916). *Democracy and education: An introduction to the philosophy of education*. Macmillan.

Dewey, J. (1938). *Experience and education*. Macmillan.

Piaget, J. (1952). *The origins of intelligence in children* (M. Cook, Trans.). International Universities Press. (Original work published 1936)

Vygotsky, L. S. (1978). *Mind in society: The development of higher psychological processes* (M. Cole, V. John-Steiner, S. Scribner, & E. Souberman, Eds.). Harvard University Press. [https://doi.org/10.2307/j.ctvjf9vz4](https://doi.org/10.2307/j.ctvjf9vz4)

Wood, D., Bruner, J. S., & Ross, G. (1976). The role of tutoring in problem solving. *Journal of Child Psychology and Psychiatry, 17*(2), 89–100. [https://doi.org/10.1111/j.1469-7610.1976.tb00381.x](https://doi.org/10.1111/j.1469-7610.1976.tb00381.x)

# Unit 4: Scenario
At the Harbor Community College, 24 adult learners enroll in a six-week Enhancing Public Space Workshop. The workshop is a pilot program for a proposed interdisciplinary degree pathway in which students build a coherent education through a unique self-directed degree, which allows learners to build competencies across topics and decide on their own completion. 

The workshop challenges learners to make a modification to  the local neighborhood library and make it a more accessible community learning space within a limited budget. Students investigate the library using an instructor-prepared floor plan, anonymized visitor data, accessibility observations, interview transcripts, and cost estimates. They must develop, test, and defend an improvement proposal. The scenario combines spatial design, statistics, communication, technology, and civic decision-making around one consequential problem.

The students all come from different experiences. Maya can sketch spaces and recognize visual patterns but cannot independently interpret visitor data. Luis can calculate costs but struggles to incorporate qualitative evidence. Amina can analyze interview themes but needs support designing a fair prototype test. Each student has their own unique entry point into their unique learning experience. 

An entry point could include: existing knowledge, interests, language, practical experience, and confidence in a particular context. The instructor kicks off the workshop by having student interview each other and fill out an assessment to help define potential entry points, overlaps and opposition. The instructor uses this information to build a scenario, using AI, that compliments the teams and connect new demands to existing understanding while checking for misconceptions. (National Academies of Sciences, Engineering, and Medicine [NASEM], 2018).

Constructivism guides the workshop because students develop explanations through investigation and revision. Piaget's (1936/1952) distinction between assimilation and accommodation helps explain the intended change: students may incorporate evidence into an existing schema or revise that schema when it cannot adequately explain what they encounter. 

For example, a team initially assumes that additional digital kiosks will improve access. A prototype test reveals that the placement obstructs movement and that some visitors prefer human assistance. This discrepancy creates an opportunity to reconsider the team's definition of accessibility. Cognitive equilibrium represents a more coherent, revisable explanation. The instructor supports the reasoning process through questions, demonstrations, and feedback; constructing understanding does not require unguided discovery.

The workshop adapts the BSCS 5E sequence: Engage, Explore, Explain, Elaborate, and Evaluate (BSCS Science Learning, n.d.). During Engage, students compare competing visitor accounts and record predictions about the library's problems. During Explore, teams examine the supplied evidence, build inexpensive models, and conduct structured role-based walkthroughs. During Explain, they present their initial interpretations before receiving targeted instruction on sampling, accessibility criteria, and evidence-based claims. During Elaborate, they revise a prototype and test it under a new constraint, such as reduced funding or increased attendance. During Evaluate, they defend their conclusions, assess the limits of their evidence, and complete an independent transfer task. Reflection occurs throughout the cycle.

Each team tests two versions of one intervention, such as signage, seating arrangements, or a service-information interface. Students predict an outcome, identify what they will measure, keep relevant conditions consistent, and document unexpected results. Classmates test navigation tasks while following assigned constraints, and teams compare completion patterns and feedback. The instructor evaluates the quality of the investigation and revision rather than whether a team's first design succeeds. An unsuccessful prototype can generate valuable evidence when learners explain what it reveals.

Vygotsky's (1978) Zone of Proximal Development distinguishes independent performance from performance possible with capable assistance. The instructor identifies each learner's ZPD through a brief attempt, a graduated prompt, and another attempt. A task belongs within the learner's working ZPD when assistance enables meaningful progress that independent performance does not yet support. If even substantial guidance produces little understanding, the instructor first addresses prerequisite knowledge. The three skills below are initial hypotheses that must be confirmed individually.

## ZPD Skills

### Interpret quantitative evidence alongside community perspectives

**Independent Start:** Learners can read a simple table or summarize an interview but cannot yet independently reconcile conflicting numerical and qualitative findings.

**Guided Performance:** With a partially completed comparison chart and instructor prompts, learners connect visitor counts with interview themes, question whose perspectives are missing, and qualify an interpretation.

**Independent Target:** Each learner analyzes evidence, makes a supported claim, and identifies one limitation without the chart or interpretive prompts.

### Design and interpret a fair prototype comparison

**Independent Start:** Learners can suggest improvements but cannot yet separate an appealing idea from a testable claim or control major differences between trials.

**Guided Performance:** Using a modeled example and peer questioning, learners define a measurable outcome, maintain comparable testing conditions, and explain alternative reasons for a result.

**Independent Target:** Each learner designs a small comparison for an unfamiliar service problem, interprets supplied results, and proposes a justified revision.

### Integrate disciplinary perspectives into a defensible recommendation
**Independent Start:**  Learners can explain an issue through a familiar perspective but cannot yet independently balance spatial, financial, and community considerations.

**Guided Performance:** A decision matrix and facilitated dialogue help learners compare competing criteria, explain trade-offs, and revise a proposal when another discipline exposes a weakness.
    
**Independent Target:** Each learner defends a recommendation using at least two disciplinary perspectives and explains how an additional constraint would change the decision.

## Scaffolding and Social Constructivism

## Contingent Support
The primary scaffolding strategy is a model-practice-fade sequence. Wood et al. (1976) describe tutoring functions that include simplifying a task, maintaining direction, highlighting important features, and managing frustration. In this workshop, the instructor first thinks aloud through an unrelated example, demonstrating how to distinguish a claim from evidence and uncertainty. Students then use a partially completed evidence chart and test-planning checklist. During conferences, the instructor begins with an open question, adds a cue if needed, and models one step only when lesser assistance is insufficient. Support responds to observed difficulty rather than a predetermined label. Templates gradually lose prompts, and learners ultimately tackle an individual problem without interpretive assistance.

## Collaborative Knowledge Construction
The social constructivist approach is a reciprocal expertise exchange. Teams initially divide evidence among temporary investigation groups focused on spatial access, resource allocation, or visitor communication. Students return to their project teams and teach the reasoning behind their findings. Peers must paraphrase the explanation, identify an uncertainty, and ask a question that could change the recommendation. Teams then produce a shared decision record documenting disagreements, supporting evidence, and revisions. This makes collaboration an opportunity to negotiate meaning rather than simply divide production tasks. Consistent with Vygotsky's (1978) emphasis on socially mediated learning, dialogue supports reasoning that individuals subsequently practice independently. Rotating roles prevents initial strengths from becoming permanent disciplinary boundaries.

## Differentiation and Diversity

Differentiation begins with the diagnostic evidence and continuing learner feedback. A student unfamiliar with spreadsheets receives a short prerequisite activity; a student already proficient in basic analysis investigates sampling bias or uncertainty. Evidence packets include accessible text, labeled visuals, and captioned demonstrations, with equivalent access to the same substantive information. Multilingual learners may annotate in a preferred language, use a glossary, and rehearse explanations before discussion. Learners can present through writing, recorded explanation, or an accessible visual presentation when each format demonstrates the required reasoning. Flexible meeting arrangements and downloadable materials support working adults. Accessibility tools remain available during independent assessment; fading concerns reasoning support, not removal of accommodations.

The instructor also checks whose assumptions shape the project. Interview accounts deliberately include conflicting priorities and perspectives without assigning any learner responsibility for representing a cultural group. Quiet reflection precedes discussion, and rotating facilitation gives students multiple ways to contribute. Learners may question the fictional brief or propose an alternative intervention if they can justify its relevance. These choices preserve agency while keeping expectations visible. Difficulty is treated as information about the interaction among the learner, task, and support. This approach aims to make uncertainty manageable, including for learners who associate evaluation with embarrassment or a threat to competence.

## Unique Exit Points and Cross Disciplinary Completion

### Competency and Completion
Every learner has a unique exit point: a documented combination of demonstrated abilities, changed understanding, and emerging questions. However, completion requires common minimum competencies. The proposed rubric rates evidence interpretation, experimental reasoning, disciplinary integration, and reflection on four levels. Students must reach the proficient level in every dimension, supported by both project evidence and an independent transfer task. Group success alone cannot establish individual competence. Students who need further work receive targeted feedback and another opportunity to demonstrate the missing competency. Exit points therefore recognize distinctive achievements while preserving a meaningful completion standard. The portfolio records the starting evidence, assistance provided, revisions, final independent performance, and proposed next challenge.

### Expanding Range

One learner might finish with a strong accessibility prototype and new statistical reasoning; another might develop a persuasive resource-allocation model and improved qualitative analysis. Their next workshops could connect those achievements to public health, environmental planning, or information systems. Epstein's (2019) Range argues for the value of broad experience and connections across domains, especially in complex environments. Here, that argument informs a proposed educational structure rather than proving that majors should disappear. Faculty advisers would help students assemble increasingly demanding projects, maintain essential disciplinary foundations, and explain the coherence of their education. Breadth becomes purposeful when students integrate perspectives and demonstrate depth, rather than merely accumulate unrelated experiences.

## Machine Learning and AI Roles

Machine learning could help maintain an evolving map of competencies and suggest appropriate challenges. Knowledge tracing models estimate aspects of student knowledge from coursework interactions; Piech et al. (2015) demonstrated recurrent neural networks for predicting student performance. Prediction, however, does not establish a learner's full understanding or identify a ZPD automatically. In the proposed workshop, a system could flag repeated difficulty connecting claims to evidence, recommend a scaffold, or suggest an adjacent discipline that would extend an existing strength. Learners and instructors would review these suggestions together. The system would offer several routes and invite correction, including exploration outside patterns inferred from earlier performance.

A separate generative AI tool could provide instructor-reviewed practice questions, alternative examples, and simulated objections to a proposal. It would ask learners to explain predictions before offering hints, preserving opportunities for discovery and revision. Neither tool would independently certify completion. Instructors would verify consequential judgments through portfolios, conferences, and unaided reasoning tasks. Students could choose equivalent activities without AI, inspect recommendations, and challenge inaccurate profiles. Data collection would be limited to relevant learning evidence, with clear consent and access arrangements. These design commitments align with the human-centered orientation of Miao and Holmes (2023). A pilot would examine learning gains, recommendation errors, accessibility, and unequal patterns of support before expansion.

## Reflective Analysis

This scenario treats learning as developing and revising a system of meaning through purposeful activity. Unique entry points establish where instruction can connect; ZPD assessment identifies what assistance makes possible; scaffolding bridges the gap toward independent performance. Social interaction exposes assumptions that solitary work may leave unexamined. Cross-disciplinary problems create a reason to integrate perspectives because no single lens sufficiently addresses the design challenge. The anticipated outcomes are stronger evidence-based reasoning, more deliberate experimentation, and greater capacity to explain trade-offs. These remain predictions to evaluate through baseline tasks, independent exit assessments, and a delayed transfer activity rather than assumed consequences of participation.

The broader proposal is an education organized around evolving competency profiles and connected inquiries, potentially offering an alternative to a conventional major. Its credibility depends on transparent standards, sustained advising, disciplinary depth, and recognition beyond the classroom. Machine learning could help coordinate possible routes, while human judgment protects room for unexpected interests and growth. Each exit point becomes a possible entry into another inquiry. Successful completion therefore marks a defensible achievement and a newly visible horizon for learning, supporting a lifelong capacity to encounter unfamiliar questions with curiosity and increasingly effective strategies. 

## References

### AI Use Disclosure
I provided the originating ideas about unique entry and exit points, education beyond a conventional major, expanding range, and cross-disciplinary learning. AI help develop the fictional scenario, and helped locate and check reference information.
 
 BSCS Science Learning. (n.d.). *The BSCS 5E instructional model: Origins and effectiveness*. https://bscs.org/reports/the-bscs-5e-instructional-model-origins-and-effectiveness/
 
 Epstein, D. (2019). *Range: Why generalists triumph in a specialized world*. Riverhead Books.
 
 Miao, F., & Holmes, W. (2023). *Guidance for generative AI in education and research*. UNESCO. https://doi.org/10.54675/EWZM9535
 
 National Academies of Sciences, Engineering, and Medicine. (2018). *How people learn II: Learners, contexts, and cultures*. The National Academies Press. https://doi.org/10.17226/24783
 
 Piaget, J. (1952). *The origins of intelligence in children* (M. Cook, Trans.). International Universities Press. (Original work published 1936)
 
 Piech, C., Bassen, J., Huang, J., Ganguli, S., Sahami, M., Guibas, L. J., & Sohl-Dickstein, J. (2015). Deep knowledge tracing. In C. Cortes, N. D. Lawrence, D. D. Lee, M. Sugiyama, & R. Garnett (Eds.), *Advances in neural information processing systems* (Vol. 28, pp. 505–513). Curran Associates, Inc. https://proceedings.neurips.cc/paper/2015/hash/bac9162b47c56fc8a4d2a519803d51b3-Abstract.html
 
 Vygotsky, L. S. (1978). *Mind in society: The development of higher psychological processes* (M. Cole, V. John-Steiner, S. Scribner, & E. Souberman, Eds.). Harvard University Press. https://doi.org/10.2307/j.ctvjf9vz4
 
 Wood, D., Bruner, J. S., & Ross, G. (1976). The role of tutoring in problem solving. *Journal of Child Psychology and Psychiatry, 17*(2), 89–100. https://doi.org/10.1111/j.1469-7610.1976.tb00381.x

<a name="unit5"> </a>

# Unit 5: Connectivism 

## Overview and Connections to Teaching and Learning

Connectivism views learning as a process of developing and maintaining connections among people, information sources, and digital tools. George Siemens introduced the concept online in 2004 and published his foundational article in 2005. Stephen Downes further developed the perspective, explaining that knowledge is distributed across networks and that learning involves forming and navigating these connections (Downes, 2012; Siemens, 2005).

In 2008, Siemens and Downes demonstrated these principles through *Connectivism and Connective Knowledge* (CCK08), an early massive open online course. Participants learned by interacting with resources, sharing ideas, and contributing to a distributed learning network (Downes, 2009).

These ideas are relevant to workplace learning and mentorship. Employees learn through formal training, conversations with colleagues, access to organizational resources, and guidance from experienced professionals. From a connectivist perspective, a mentor can help an employee build a broader network of expertise. For example, a mentor might introduce a new employee to colleagues in other departments, recommend reliable resources, and demonstrate how to seek assistance when facing an unfamiliar task. This application reflects Siemens’s (2005) emphasis on knowing where to find knowledge and maintaining connections that support continued learning.

### Key Dates
{% include connectivism_timeline.html%}

## Implications for Instructional Design

Applying connectivism to workplace learning means designing opportunities for employees to access expertise, exchange knowledge, and apply what they learn. Instructional designers should consider how learning will continue after a course or onboarding program ends.

For a workplace mentorship program, I would incorporate the following:

- **Network-building activities.** Ask mentors to help employees identify people, communities, and resources relevant to their responsibilities.
- **Authentic work problems.** Have employees address a real task using mentor guidance, colleague input, and organizational resources.
- **Knowledge sharing.** Provide opportunities for employees to contribute examples, lessons learned, and useful resources to a shared knowledge base.
- **Reflection and feedback.** Use mentoring conversations to examine what employees learned, how they evaluated advice, and how they applied it.
- **Assessment through performance.** Evaluate employees’ ability to solve problems, explain decisions, and locate appropriate support.

These are proposed applications of connectivism rather than a formal mentorship model. They should include clear expectations and support because networked learning requires autonomy and the ability to evaluate information critically (Kop, 2011).

## Strengths and Limitations

I believe connectivism offers a useful foundation for workplace learning and mentorship because it recognizes that employees cannot acquire everything they need through formal training. Work responsibilities change, and employees benefit from knowing whom to consult and where to find current information. Mentorship can support this process by helping employees develop relationships and gradually become more independent.

For example, I would design an onboarding program in which a new employee works with a mentor to complete a project requiring input from several departments. The mentor would help the employee identify relevant expertise, evaluate recommendations, and reflect on the outcome. The employee would leave the experience with both practical knowledge and relationships that could support future work.

However, the quality of a learning network matters. An employee may receive outdated advice, encounter conflicting information, or rely too heavily on one mentor. Access may also be unequal if some employees have more opportunities to connect with experienced colleagues. I would address these concerns through multiple sources of support, reviewed organizational resources, and scheduled mentoring opportunities.

Another limitation is that access to expertise does not guarantee understanding. Employees still need foundational knowledge and opportunities to practice independently. Kop and Hill (2008) questioned whether connectivism sufficiently explains learning beyond existing theories, while Kop (2011) identified challenges involving learner autonomy and participation. For these reasons, I would combine networked learning and mentorship with clear instruction, guided practice, and feedback. This approach would support both immediate job performance and employees’ capacity to continue learning throughout their careers.

## References

Downes, S. (2009, February 16). *Access2OER: The CCK08 solution*. Stephen’s Web. https://www.downes.ca/post/53418

Downes, S. (2012). *Connectivism and connective knowledge: Essays on meaning and learning networks*. National Research Council Canada. https://www.downes.ca/files/books/Connective_Knowledge-19May2012.pdf

Kop, R. (2011). The challenges to connectivist learning on open online networks: Learning experiences during a massive open online course. *The International Review of Research in Open and Distance Learning, 12*(3), 19–38. https://doi.org/10.19173/irrodl.v12i3.882

Kop, R., & Hill, A. (2008). Connectivism: Learning theory of the future or vestige of the past? *The International Review of Research in Open and Distance Learning, 9*(3), 1–13. https://doi.org/10.19173/irrodl.v9i3.523

Siemens, G. (2005). Connectivism: A learning theory for the digital age. *International Journal of Instructional Technology and Distance Learning, 2*(1), 3–10. https://www.itdl.org/Journal/Jan_05/article01.htm


# Unit 5: Building My Personal Learning Network (PLN) for Simulation-Based Training

## Part I: Creating My PLN

My career goal is to develop expertise in designing highly technical training, particularly simulation-based instruction like the training used to prepare elite military pilots. I want to understand how instructional designers create realistic learning experiences that help people practice complex procedures, make decisions under pressure, and apply their skills effectively.

As a project-based learner, I learn best by creating something, testing it, and improving it through feedback. My Personal Learning Network (PLN) will connect me with resources and professionals who can help me translate instructional design principles into practical projects.

### Research and Selection

I identified five potential connections that align with my interests:

1. **[National Training & Simulation Association (NTSA)](https://www.ntsa.org/membership)**  
   NTSA connects professionals working in modeling, simulation, and training. Its educational and networking opportunities align closely with my interest in military and aviation training. My company did not attend ITTSEC this year, NTSA's annual conference, but I hope to be ble to attend in 2027.

2. **[Human Factors and Ergonomics Society (HFES), Training Technical Group](https://www.hfes.org/Groups-Communities/Technical-Groups/Training)**  
   This group explores human factors in training systems, including human-machine interaction, safety, performance, and emerging training technologies. I joined Aerospace Systems Technical Group for free which should be interesting. If this is a good source, I will also become a member of the Cognitive Engineering and Decision Making Technical Group.

3. **[NASA’s Aviation Systems Division](https://www.nasa.gov/ames/aviationsystems/publications/simulation-capabilities/)**  
   NASA’s aviation simulation publications provide technical resources that could deepen my understanding of simulation environments and their applications. They have several interesting publications and—with the recent issues with air travel—I am especially going to review their research on Air Traffic Management.

4. **[The Learning Guild](https://www.learningguild.com/)**  
   The Learning Guild provides a community of learning professionals, along with webinars and resources related to instructional design and learning technologies.

5. **[Society for Simulation in Healthcare (SSH)](https://ssih.org)**  
   SSH offers opportunities to learn about simulation education in another high-stakes field. Exploring healthcare simulation could help me consider approaches that might inform technical training in other settings. Their [Sim Series Webinar](https://ssih.org/simseries-webinars) looks good.

### Two Key Connections

#### National Training & Simulation Association

NTSA is probably the most relevant to my career goals because its community focuses on modeling, simulation, and training and my company often attends. I hope to attend Interservice/Industry Training, Simulation and Education Conference (I/ITSEC). Reading the [I/ITSEC publications and proceedings](https://www.iitsec.org/about-iitsec/publications-and-proceedings) would give me material to investigate training problems and generate ideas for portfolio projects.

NTSA would also provide opportunities to meet experienced professionals and seek informal mentorship. I would ask practitioners about designing realistic scenarios, and evaluating whether learners can transfer their skills to operational settings. These relationships would develop through ongoing participation rather than membership alone.

#### HFES Training Technical Group

The HFES Training Technical Group would help me understand the relationship between training design and human performance. Its focus on human factors aligns with my interest in preparing learners to perform complex tasks and make decisions under demanding conditions.

This connection would support my exploration of cognitive workload, feedback, practice, and performance assessment. For example, when designing a simulation, I would want to determine whether additional visual detail, such as color contrast, helps learners make decisions or distracts them from the learning objective.

Following the group would also help me examine emerging technologies, such as artificial intelligence and virtual reality, through the lens of learning and performance.

## Part II: Professional Learning Plan

### Reflection and Future Goals

The process of identifying PLN connections helped me recognize that my career interests span several fields. Instructional design, simulation technology, human factors, and performance assessment, though tough material, all contribute to the work I hope to pursue.

My PLN reflects connectivism because my learning will develop through connections among people, communities, and information sources. I will need to know where to find relevant knowledge, how to evaluate it, and whom to consult when I encounter an unfamiliar problem. Contributing my own ideas and receiving feedback will also help me develop my understanding.

My long-term goal is to create a simulation-based technical training projects of my own with the help of subject matter experts from my company. To work toward that goal, I will use my PLN to support the project. An initial project could be an aviation-inspired branching scenario (A/B testing) in which learners interpret screens, prioritize actions, and their responses are recorded. 

### Continuous Learning and Engagement

Because I learn best through projects, I will connect my PLN activities to specific design tasks.

- **Weekly:** Spend approximately one hour reviewing publications and professional discussions. Save at least one useful resource and explain how it could inform a project.
- **Monthly:** Participate in an accessible webinar, event, or discussion. Contribute a thoughtful question or share a relevant resource with a brief explanation.
- **Every three months:** Complete a small project or test, such as a scenario storyboard, simulation design plan, or debriefing guide. Request feedback from peers and experienced practitioners when available.
- **After each project/test:** Document what I learned, the feedback I applied, and the questions I still need to investigate.

I will ask focused questions when seeking feedback. For example, I might ask, “Does this scenario assess decision-making or primarily recall?” or “Does the feedback help learners understand the consequences of their choices?”

I will contribute to my PLN by sharing annotated resources, project reflections, and examples of revisions made in response to feedback. This will help me participate as both a learner and a contributor.

### Staying Current and Evaluating Credibility

I will follow organizational updates and professional discussions related to simulation, virtual reality, artificial intelligence, and performance assessment. I will organize useful resources by topic, including scenario design, human factors, debriefing, and evaluation. Each saved entry will include the author, publication date, link, main finding, and possible application.

Before applying information, I will examine the author’s expertise, supporting evidence, publication process, and potential commercial interests. I will use social media to discover ideas, then trace significant claims to original research or technical documentation.

I will also consider whether evidence applies to my intended learners and training context. An approach that works in healthcare, for example, may require creative adaptation before it is useful in aviation training.

Every three months, I will review whether my PLN is helping me improve my projects and identify gaps in my knowledge or connections. Through this cycle of connecting, creating, seeking feedback, and revising, I can make lifelong learning a practical part of my professional development.

<a name="unit6"> </a>

# Unit 6

<a name="unit7"> </a>

# Unit 7

<a name="unit8"> </a>

# Unit 8