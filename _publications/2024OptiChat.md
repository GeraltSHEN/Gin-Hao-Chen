---
title: "Diagnosing Infeasible Optimization Problems Using Large Language Models"
collection: publications
category: manuscripts
#permalink: /publication/2024-02-17-paper-title-number-4
#excerpt: 'First-of-its-kind natural language-based dialogue system for diagnosing infeasible optimization problems using LLM'
date: 2024-08-03
venue: 'INFOR: Information Systems and Operational Research'
paperurl: 'https://www.tandfonline.com/doi/abs/10.1080/03155986.2024.2385189'
citation: 'Chen, H., Constante-Flores, G., Li, C. Diagnosing Infeasible Optimization Problems Using Large Language Models. INFOR: Information Systems and Operational Research, 1–15. (2024).'
---

Decision-making problems can be represented as mathematical optimization models, finding wide applications in fields, such as economics, engineering, transportation, and health care. One of the primary barriers to deploying these models in practice is the challenge of helping practitioners understand and interpret such models, particularly when they are infeasible, meaning no decision satisfies all the constraints. Existing methods for diagnosing infeasible optimization models often rely on expert systems, necessitating significant background knowledge in optimization. In this paper, we introduce OptiChat, a first-of-its-kind natural language-based system equipped with a chatbot GUI for engaging in interactive conversations about infeasible optimization models. OptiChat can provide natural language descriptions of the optimization model itself, identify potential sources of infeasibility, and offer suggestions to make the model feasible. The implementation of OptiChat is built on GPT-4, which interfaces with an optimization solver to identify the minimal subset of constraints that render the entire optimization problem infeasible, known as the Irreducible Infeasible Subset (IIS). We utilize few-shot learning, expert chain-of-thought, key-retrieve, and sentiment prompts to enhance OptiChat’s reliability. Our experiments demonstrate that OptiChat assists both expert and non-expert users in improving their understanding of the optimization models, enabling them to quickly identify the sources of infeasibility.
