# Assignment 4: Prompt Engineering Experiments

**Name:** Hassan Murtaza Zaidi

**Internship:** AI Engineering Fellowship 2026

**Organization:** Invictus Solutions

---

# Introduction

Prompt engineering is the process of designing effective prompts that help Large Language Models (LLMs) generate accurate, useful, and well-structured responses. This report demonstrates five different prompt engineering techniques.

---

# Experiment 1 – Role Prompting

## Prompt

```
You are an experienced AI Engineering mentor.

Explain Artificial Intelligence to a beginner Software Engineering student using simple language and real-life examples.
```

## Output

Artificial Intelligence (AI) enables computers to perform tasks that normally require human intelligence, such as learning, reasoning, decision-making, and language understanding. Examples include ChatGPT, self-driving cars, recommendation systems, and virtual assistants.

## Observation

- The AI responded as an expert mentor.
- The explanation was easy to understand.
- Real-world examples made the concept clearer.

## Improvements

- Specify the education level of the audience.
- Request diagrams or bullet points for better understanding.

---

# Experiment 2 – Chain of Thought Prompting

## Prompt

```
Solve this problem step by step.

A company has 120 employees.
35% work remotely.
How many employees work remotely?
```

## Output

Step 1: Calculate 35% of 120.

Step 2: 120 × 35 ÷ 100 = 42.

Final Answer: 42 employees work remotely.

## Observation

- The AI explained every calculation.
- The reasoning was easy to follow.
- The final answer was accurate.

## Improvements

- Ask the AI to verify the final answer.
- Request additional explanation if teaching beginners.

---

# Experiment 3 – Few-Shot Prompting

## Prompt

```
Example 1:
Input: Hello
Output: Greeting

Example 2:
Input: Bye
Output: Farewell

Now classify:

Input: Good Morning
```

## Output

Greeting

## Observation

- The examples helped the AI understand the task.
- The classification was correct.

## Improvements

- Add more examples.
- Include different categories for better accuracy.

---

# Experiment 4 – Structured Output (JSON)

## Prompt

```
Generate student information in JSON format.

Name: Hassan Murtaza Zaidi
University: The University of Faisalabad
Department: Software Engineering
Semester: 4
```

## Output

```json
{
  "name": "Hassan Murtaza Zaidi",
  "university": "The University of Faisalabad",
  "department": "Software Engineering",
  "semester": 4
}
```

## Observation

- The output followed proper JSON structure.
- JSON format is useful for APIs and software applications.

## Improvements

- Validate the JSON before using it.
- Add more fields if required.

---

# Experiment 5 – Prompt Optimization

## Original Prompt

```
Tell me about AI.
```

## Output

A general explanation of Artificial Intelligence.

---

## Optimized Prompt

```
You are an AI professor.

Explain Artificial Intelligence to a second-year Software Engineering student.

Include:

- Definition
- Types of AI
- Real-world applications
- Advantages
- Challenges

Limit the answer to 300 words and use headings and bullet points.
```

## Output

The AI produced a structured explanation with headings, bullet points, and detailed information.

## Observation

- The optimized prompt produced a much better response.
- The output was more organized and informative.

## Improvements

- Clearly define the audience.
- Specify the response format.
- Add word limits and formatting instructions.

---

# Conclusion

This assignment demonstrated five important prompt engineering techniques:

- Role Prompting
- Chain of Thought Prompting
- Few-Shot Prompting
- Structured Output (JSON)
- Prompt Optimization

These techniques improve the quality, consistency, and usefulness of AI-generated responses.
