## Overview

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