# vanguard-project

**Goal**

Explore Vanguard’s customer experience (CX) process data using Python to evaluate customer behaviours and outcomes across process steps.

**Questions**

1. Does the redesigned process (Test) lead to a higher completion rate compared to the existing process (Control)?

2. How does the new UI/UX variation affect user completion, efficiency, and error rates, and does age influence these effects?

**Hypotheses** 

This document summarises the four key hypotheses tested in the Vanguard Project, which aimed to evaluate the impact of a new UI/UX variation on user behavior and efficiency.

Hypothesis 1: Variation vs Completion

Objective: Determine whether the new UI/UX variation affects the likelihood of users completing the journey.
Method: Compared completion rates between the Test and Control groups using a chi-square test.
Results:

Statistically significant difference detected.

Practical impact is minimal; the variation does not meaningfully increase completion.
Interpretation: While the numbers indicate a difference, the real-world effect on completion is negligible.

Hypothesis 2: Age × Variation vs Completion

Objective: Examine whether user age moderates the effect of the variation on completion rates.
Method: Chi-square test comparing completion rates across age groups for Test vs Control.
Results:

No significant association between age and completion (p-value = 0.53).
Interpretation: Age does not influence completion. User demographics have little effect; design itself is the primary factor.

Hypothesis 3: Step Duration

Objective: Assess whether the variation impacts efficiency by measuring time spent on each step.
Method: Conducted t-tests for each step comparing Control and Test groups.
Results:

Step 1 was completed significantly faster in the Test group.

Other steps showed minimal differences.
Interpretation: The variation improved efficiency only at Step 1. Applying similar improvements to other steps may yield further gains.

Hypothesis 4: Error Rate

Objective: Investigate whether the Test variation reduces user errors compared to Control.
Method: Measured error frequency at each step and tested differences with chi-square.
Results:

Some reduction in errors in Steps 0 to 3 observed.

Differences were measurable but not large enough to claim significant usability improvement.
Interpretation: The variation has a limited effect on reducing errors; design improvements are needed for meaningful impact.

Summary

Completion: Minimal practical effect from the variation.

Demographics: Age does not explain completion differences.

Efficiency: Only Step 1 benefited from the variation.

Errors: Partial reduction, but not significant enough for overall usability improvement.

This README provides a concise overview of the statistical analysis and key takeaways for each hypothesis tested in the Vanguard Project.
