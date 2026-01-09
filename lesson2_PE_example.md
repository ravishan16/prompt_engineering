
Your task is to explore the importance of including examples when improving the quality and relevance of output produced by LLMs. Remember, examples are crucial as they guide the model towards delivering the desired results. Your current task is to reorganize the given prompt according to the following sections: ASK, CONTEXT, CONSTRAINTS, and EXAMPLE.

As an added challenge, make sure the prompt doesn't return the same output as your example.


One great strategy for building up your prompts and including examples is to start without an example, then manually adjust the output you get to make it perfect and then include it as an example for future executions of the prompt.

In this task, you need to run this prompt, get the table (and only the table) from the output, and include it as an example in your prompt.

------

__ASK__

- I need a short and uplifting song about the spirit of teamwork for a children's animated football show. 

__CONTEXT__
- The show is called "Dream Team" and the main characters are a group of animated animals who form a football team. 
- The team consists of Penny the Penguin (Goalkeeper), Leroy the Leopard (Striker), and Bobby the Bear (Captain and Midfielder). 

__CONSTRAINT__
- The song has to mention the characters by name and illustrate the importance of teamwork. 
- The song should have a catchy chorus and two verses like the given example
- donot return the same output as the example.

__EXAMPLE__

(Chorus)  
Penny, Leroy and Bobby too,  
Playing football, dream come true!  
Through wind or rain, they got the knack,  
With teamwork, there's no turning back. 
 
(Verse 1)  
A penguin in goal, wings spread wide,  
Leroy leaps, no place to hide.  
Bobby calls 'pass', then 'shoot',  
When they play together, it's a hoot!

(Verse 2)  
Through each challenge, they found a way,  
United under the sun's bright ray.  
Their dream was football, their spirit strong,  
Together in team, where they belong.


---------


__ASK__  
Generate a table for my report.

__CONTEXT__  
- The report is about renewable energy sources across different countries.  
- It should highlight the energy type, country, and the percentage of total energy produced by that source.
- It focuses on solar, wind, and hydroelectric power.

__CONSTRAINTS__  
- The table must have headers for "Energy Type", "Country", and "Percentage".
- Include at least 5 countries, with a mix of leading and developing nations.
- The table should be formatted in Markdown for easy integration into my digital report.
- Leave two empty rows between each energy type to visually separate them for clarity.
- See the example below but expand it to include the requested number of countries and the specified empty rows.

__EXAMPLE__

| Energy Type | Country   | Percentage |
|------------|-----------|------------|
| Solar      | Germany   | 8%         |
| Solar      | China     | 7%         |
| Solar      | USA       | 6%         |
| Solar      | India     | 4%         |
| Solar      | Japan     | 3%         |
|            |           |            |
|            |           |            |
| Wind       | Brazil    | 10%        |
| Wind       | Denmark   | 9%         |
| Wind       | UK        | 7%         |
| Wind       | Canada    | 5%         |
| Wind       | Spain     | 4%         |
|            |           |            |
|            |           |            |
| Hydro      | China     | 15%        |
| Hydro      | Canada    | 12%        |
| Hydro      | Brazil    | 10%        |
| Hydro      | USA       | 8%         |
| Hydro      | Russia    | 6%         |
