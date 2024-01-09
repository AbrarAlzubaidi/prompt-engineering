# prompt-engineering

## what is prompt engineering?

it is a way to communicate with AI models by using natural languages to design prompts and that allow us to gain a suitable responses (outputs) ralated with the input .

طريقة لمخاطبة نماذج الذكاء الاصطناعي باستخدام اللغات الطبيعية من خلال تصميم الاوامر مما يسمح لنا بتوجيه هذه النماذج لانتاج مخرجات دقيقة ومراعية للسياق

prompt engineering use LLM's (large language models) from G-AI (generative artificial intelligence)

some famous LLM's in the market:

- chatGPT and bing from openAI and Microsoft which have 1.76 trillion parameter
- Bard from google which have 540 billion parameter
- Lama2 from Meta which have 70 billion parameter
- Bloom from hugging face which have 176 biliion parameter

*if number of parameters is increased the model and the responce will be more effecent and better

## artificial intelligence stages are

1. ANI (artificial narrow intelligence (machine learning)): specialized in one area and solves one problem 
2. AGI (artificial general intelligence (machine intelligence)): refers to a computer that is as smart as a human across the board
3. ASI (artificial super intelligence (machine consciousness)): an intellect that is much smarter than the best human brains in partically every field

## what is LLM's

it is a group of algorithms that analyse and processing the natural languages using ensemble learning. also LLM is kind of nural network (deep learning)

> from chatGPT:
LLM stands for "Large Language Model." It refers to a type of artificial intelligence model designed to understand and generate human-like text. These models are trained on massive amounts of textual data, learning patterns, structures, and context within language. The term "large" indicates that these models have a vast number of parameters, which are the internal variables the model uses to make predictions or generate responses.

*ensemble methods: the way of how we will gather more than one different and effecient algorithm for more effectient prediction.

## what any good prompt should have?

1. the task: what is the task that can the LLM do. for chatGPT there is a lot of tasks that can chatGPT do but here we will focus on 3 tasks:
    - filteration: as an example "filter these animals into Breeds of the animal kingdom"
    - sorting: as an example "sort the countries from lager to small depends on its area"
    - prediction: as an example "predict what is the relationship between increases the number of Drowning cases and the four seasons"
2. the context: give some details about the task. as an examples
    - "i am a beginner of learning python and i am struggling in arrays/list so could you give me examples with a simple explaination of each one. the examples that i want explain famous the methods that i can use in arrays like insert, delete, update...etc"
    - "i have a small business for printing pictures on cups and mugs, the target of my business are tenagers and youngs, give me some startigies that can help me to publish my business espically online marketing"
3. the roles: give the LLM a role. as an example: "you are a teacher and want to explain the Global warming to the students, the students age is 12, give me methods to explain it and teach them the outcomes from it"
4. output indicator: explaine the format of the output that you want. as an example: "you are a professor in IT department and you have hundrad of students learn programming. i am a beginner student in web development. plase tell me about the top 10 programming languages that i could learn and sort it from easiest to hardest.  i want the result as a table"

the outputs format: tables, csv, json, texts, latex, xml, tree, codes, markdown, checklists, vectors and graphs.
5. the input data: give the LLM some inputs so it will enhance the output. as an example:
"you are a proffesional digital marketing and we are a small Glasses shop we try to have new customers, design us a new stategy so we can implement it and it should be devided into weeks and here is my data: ..."

## prompting techniques

1. zero-shot prompting: deal with the LLM as a chat bot (direct questions). lets go to past a little bit in the 60th century there was a doctor called Joseph Weizenbaum created a chat bot called [Eliza](https://en.wikipedia.org/wiki/ELIZA). as examples:
    - what is the capital of USA?
    - translate this text...
    - Summarize this assay

2. few-shot prompting: by give the LLM a short senario and it will indecate the result, as an example:
" Q: Jordan   A: Amman,   Q: Iraq   A:Bagdag, Q:Morroco   A:?"

3. chain-of-thought prompting
4. self-consistency prompting

## resources

[كورس هندسة التلقين](https://www.youtube.com/watch?v=gZv5hFW3OF8&t=98s)
