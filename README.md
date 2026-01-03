# AI-Team
Playground to have multiple AI Models working as a team to optimize the answer.

## Prompt

GROQ Prompt:

- write a short JS tool, where user post a question to ai-models team. first will give concise, complete reply to the answer and save in a conclusion, then second reads that and correct or accept it, then third do the same, and it keeps running unless all accept the answer OR everyone gets 3 turns. Show final result as conclusion.

keep ui modern and slick with team chat mode style - properly format the output of each reply.

All will use one groq key (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) for all, just change models. 
Also test all model are getting correct output.

models:
openai/gpt-oss-120b
meta-llama/llama-4-scout-17b-16e-instruct
qwen/qwen3-32b
groq/compound

make one file solution.

- Make a left bar with new chat and recent chats. Store everything in browser storage. auto-suggest recent chats title and start date and option to delete (use emoji). update the full code.

- Add support in code to add unique groq key for each model