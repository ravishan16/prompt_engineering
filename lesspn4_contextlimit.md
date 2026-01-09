# Historical Evolution of Context Limits

The advancement of context limit expansion over time has been remarkable. Here's a simplified table showcasing the changes:

| Model      | Context window (Tokens) |
|------------|--------------------------|
| GPT-3      | 2k                       |
| GPT-3.5    | 4k                       |
| GPT-4      | 4k-32k                   |
| Mistral 7B | 8k                       |
| PALM-2     | 8k                       |
| Claude 2   | 100k                     |

This progression has unlocked more opportunities in generating coherent and contextually rich responses. However, most LLM providers charge based on the number of tokens used, and often, you may work with a model that has a limited context window, necessitating strategies to optimize your prompts within these constraints.

Prompt Simplification: Condense prompts to their essence, stripping away excess detail while preserving key information.
Precise Queries: Focus inquiries to elicit specific, targeted responses, enhancing relevance within context constraints.
Stepwise Prompting: Break down complex tasks into smaller, sequential prompts. This iterative refinement guides LLMs through logical thought sequences, even under stringent token limits.


__ASK__

- turn this unargonized list 

__CONTEXT__

GPT-4: 4k-32k tokens, Claude 2: 100k, GPT-3.5: 4k, PALM-2: 8k, GPT-3: 2k, Mistral 7B: 8k

__CONSTRAINTS__

 - includes two columns and a header.
 - table is in markdown
 - like the example
 
 __EXAMPLE__
 
| Model       | Context limit|
|-------------|--------------|
| GPT-4       | 4k-32k       |
| Claude 2    | 100k         |
| GPT-3.5     | 4k           |
| PALM-2      | 8k           |
| GPT-3       | 2k           |
| Mistral 7B  | 8k           |