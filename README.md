# saki
hyper realistic discord friend with freewill, advanced context/memory, realistic conversational abilities, search abilities, decide when/if to respond, multimodal input/outputs (send it images/video n receive images/video), and live time integrated into 

made the bot for fun to test out gemini's api and their free limit.

2.0 flash lite is used to operate the context and memory system, we have long context (realistically we could do up to 1m, but <100k keeps conversation effective). we use flash lite to summarize and store all events after 50k tokens up to 100k (can all be adjusted in config).
actual calls/bot interactions are handled via 2.0 flash
