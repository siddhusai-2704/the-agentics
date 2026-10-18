# CrewAI Build Report

**Name:** Seera Sai Surya Siddhardha

**Topic I used:** How artificial intelligence helps students learn

## 1. What I changed

I changed the backstory of the Writer agent in `main.py`. I instructed the Writer to explain complicated topics to children around 10 years old. The instructions emphasize simple English, short sentences, familiar examples, and avoiding unnecessary technical terms. I chose this change because it modifies how the agent communicates without changing the topic or the overall workflow. This makes it easier to compare the original output with the changed output.

## 2. How CrewAI works

CrewAI organizes work using agents and tasks. Each agent has a role, a goal, and background instructions that guide its behavior. Tasks specify the work an agent must complete and the expected output. The crew coordinates the agents so they can complete the assigned workflow. In this experiment, the Writer's backstory provides additional guidance about the audience and writing style.

## 3. What I observed

In the original run, the agents attempted to explain how artificial intelligence helps students learn. In the changed run, I instructed the Writer to target children around 10 years old. I compared `explainer_run1.md` with `explainer_run2.md` to identify differences in vocabulary, sentence length, examples, and explanation style.

**Observed differences:** Replace this sentence with specific differences you actually see in the two output files.

## 4. What I learned

This experiment helped me understand that an agent's instructions can influence its output. Changing the Writer's backstory can guide the language, examples, and level of detail used in an explanation. Comparing the two runs also showed me why it is useful to keep the topic the same when testing a change to an agent's behavior.