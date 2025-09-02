

# EXP 5: COMPARATIVE ANALYSIS OF DIFFERENT TYPES OF PROMPTING PATTERNS AND EXPLAIN WITH VARIOUS TEST SCENARIOS

# Aim: To test and compare how different pattern models respond to various prompts (broad or unstructured) versus basic prompts (clearer and more refined) across multiple scenarios.  Analyze the quality, accuracy, and depth of the generated responses 

### AI Tools Required: 

# Explanation: 
Define the Two Prompt Types:

Write a basic Prompt: Clear, detailed, and structured prompts that give specific instructions or context to guide the model.
Based on that pattern type refined the prompt and submit that with AI tool.
Get the ouput and write the report.

Prepare Multiple Test Scenarios:
Select various scenarios such as:
Generating a creative story.
Answering a factual question.
Summarizing an article or concept.
Providing advice or recommendations.
Or Any other test scenario
For each scenario, create both a naïve and a basic prompt. Ensure each pair of prompts targets the same task but with different levels of structure.
Run Experiments with ChatGPT:
Input the naïve prompt for each scenario and record the generated response.
Then input the corresponding basic prompt and capture that response.
Repeat this process for all selected scenarios to gather a full set of results.
Evaluate Responses : 
	Compare how ChatGPT performs when given naïve versus basic prompts and analyze the output based on Quality,Accuracy and Depth. Also analyse does ChatGPT consistently provide better results with basic prompts? Are there scenarios where naïve prompts work equally well?
Deliverables:
A table comparing ChatGPT's responses to naïve and basic prompts across all scenarios.
Analysis of how prompt clarity impacts the quality, accuracy, and depth of ChatGPT’s outputs.
Summary of findings with insights on how to structure prompts for optimal results when using ChatGPT.


# OUTPUT
📊Comparative Analysis of Prompting Patterns

Prompting patterns are structured ways of interacting with AI systems to steer outputs effectively. Different patterns are suitable for different tasks, depending on whether you need creativity, precision, multi-step reasoning, or collaboration.
## 1. Zero-shot Prompting

Definition: The model is asked to perform a task without examples.
When to use: Simple tasks where the model already has general knowledge.

Test Scenario:

Prompt: "Translate 'How are you?' into French."

Expected Output: "Comment ça va ?"

✅ Works well for straightforward tasks.
⚠️ May fail on complex/niche tasks.

## Few-shot Prompting

Definition: The model is given a few examples before the actual task.
When to use: Tasks requiring structure or consistency.

Test Scenario:

Prompt:

Translate English to French:
- Good morning → Bonjour
- Thank you → Merci
- How are you? →


Expected Output: "Comment ça va ?"

✅ Improves accuracy and format adherence.
⚠️ Needs careful example selection.

##  Chain-of-Thought (CoT) Prompting

Definition: The model is guided to show reasoning steps before answering.
When to use: Complex reasoning, math, logic.

Test Scenario:

Prompt: "If a factory produces 120 items in 6 hours, how many items in 10 hours? Show steps."

Expected Output:

Step 1: Rate = 120 ÷ 6 = 20 items/hour

Step 2: In 10 hours = 20 × 10 = 200

Answer: 200 items

✅ Helps with transparency and logical correctness.
⚠️ Slightly verbose outputs.

## Self-Consistency Prompting

Definition: Generate multiple reasoning paths and pick the most consistent answer.
When to use: Ambiguous or high-stakes reasoning problems.

Test Scenario:

Prompt: "Solve: (15 ÷ 3) + (2 × 4)."

The model generates multiple paths:

Path 1: 15 ÷ 3 = 5; 2 × 4 = 8; 5 + 8 = 13 ✅

Path 2: Misstep leading to 17 ❌

Final Answer (most consistent): 13

✅ Reduces hallucinations/errors.
⚠️ More computationally expensive.

## Role-based Prompting

Definition: Assign a role to the model to shape its behavior.
When to use: Creative writing, professional tone, or domain-specific tasks.

Test Scenario:

Prompt: "You are a math teacher. Explain recursion in simple words with an example."

Expected Output: A structured, student-friendly explanation.

✅ Better control over style/tone.
⚠️ Might drift if role not reinforced.

## Chain-of-Verification (CoVe)

Definition: Model generates an answer, then verifies or critiques it.
When to use: Scenarios needing correctness (math, coding).

Test Scenario:

Prompt: "Is 97 a prime number? Explain and verify."

Expected Output:

First: 97 is prime.

Verification: No divisors other than 1 and 97.

Final: 97 is prime.

✅ Increases trustworthiness.
⚠️ Longer response time.

##. Group/Collaborative Prompting

Definition: Multiple agents (or simulated personas) collaborate.
When to use: Brainstorming, problem-solving.

Test Scenario:

Prompt: "Three experts (a data scientist, a statistician, and a project manager) discuss how to handle missing data in a dataset."

Expected Output:

Data Scientist: Suggests imputation.

Statistician: Emphasizes bias risks.

Project Manager: Focuses on project timeline.

✅ Useful for multi-perspective insights.
⚠️ Responses may get lengthy.

# RESULT:
     The prompt for the above said problem executed successfully
