# EXP-2-PROMPT-ENGINEERING-

## Aim: 
Comparative Analysis of different types of Prompting patterns and explain with Various Test Scenarios

Experiment:
Test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios. 
Analyze the quality, accuracy, and depth of the generated responses.


## Algorithm:
Algorithm for Choosing Prompting Patterns

step 1: Identify Task Type

• If task is simple, fact-based, or well-known → go to Step 2.

• If task is complex reasoning, multi-step, or logical → go to Step 3.

• If task requires specific tone, role, or style → go to Step 4.

Step 2: Simple/Direct Tasks

• If clear instruction can solve → Instructional Prompting.

• If no instruction but model should infer → Zero-Shot Prompting.

• If examples are needed for better accuracy → Few-Shot Prompting.

Step 3: Reasoning Tasks

• If single reasoning chain is sufficient → Chain-of-Thought Prompting.

• If high accuracy is required and resources allow → Self-Consistency Prompting.

Step 4: Contextual/Role-Specific Tasks

• If response must reflect expertise, persona, or simulation → Role-Based
Prompting.

Step 5: Refine

• Evaluate outputs; combine methods if needed (e.g., Role-Based + CoT for an
expert reasoning persona).
## Prompt:

Create a 5–6 page, well-structured report titled “Comparative Analysis of Different Types of Prompting Patterns with Experimental Test Scenarios,” covering an introduction to prompting, its importance, and how prompt design affects output quality, along with explanations and examples of zero-shot, few-shot, chain-of-thought, instruction-based, role-based, and structured vs unstructured prompting. Include an experimental setup comparing broad/unstructured and refined/structured prompts using criteria like accuracy, clarity, depth, relevance, and creativity, and present 3–5 scenarios (e.g., technical, creative, problem-solving, data analysis) with basic vs refined prompts, output comparisons, and analysis. Add a comparison table, key insights, best-use cases, and a conclusion with best practices, formatted as a modern professional report with clear headings, tables, suggested fonts (Montserrat/Poppins, Open Sans/Roboto), visual placeholders (charts, diagrams), and optional prompt engineering tips.

## Output
[PE-02.pdf](https://github.com/user-attachments/files/27213789/PE-02.pdf)


## Result
Each prompting pattern has unique advantages. Zero-shot and instructional are efficient
for direct tasks, few-shot excels with examples, chain-of-thought and self-consistency
shine in reasoning, while role-based adapts to audience needs. The choice depends on the
task domain.
