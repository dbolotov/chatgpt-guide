# ChatGPT: Capabilities, Limits, and Practical 


<!-- TOC -->

- [ChatGPT: Capabilities, Limits, and Practical](#chatgpt-capabilities-limits-and-practical)
- [Introduction](#introduction)
- [Features](#features)
- [Limits and Gotchas](#limits-and-gotchas)
- [How to Use ChatGPT More Safely and Effectively](#how-to-use-chatgpt-more-safely-and-effectively)
- [System & Settings Tips](#system--settings-tips)
- [Prompt Engineering](#prompt-engineering)
- [Documentation & Resources](#documentation--resources)
- [OpenAI products June 2025](#openai-products-june-2025)
- [Glossary](#glossary)

<!-- /TOC -->

# Introduction

This is a guide to ChatGPT from OpenAI. It's intended for readers with a technical background or at least a working familiarity with software, data, or systems thinking. It covers features (free and paid), limits and gotchas (and how to deal with these), prompt engineering, settings, and technical jargon. 

# Features

## Free (GPT-3.5)

- **Chat with GPT-3.5:** Good for basic writing, planning, and quick answers. Fast, but less accurate than GPT-4.
- **Prompt interface:** Ask questions or give instructions in plain language.
- **Chat history:** Conversations are saved and searchable.

## Paid (GPT-4-turbo with ChatGPT Plus)

- **Access to GPT-4-turbo:** More accurate, better at reasoning, and handles longer input (up to 128K tokens).
- **Custom GPTs:** Build your own assistant with saved instructions, files, and tools. No coding required.
- **Memory:** GPT-4 can remember your preferences or facts across chats. You can review, update, or delete what it remembers.
- **Code Interpreter (Advanced Data Analysis):** Upload files like CSVs, run analysis, make plots, clean data, and do quick math.
- **Image input:** Ask questions about screenshots, photos, diagrams, or scanned notes.
- **Web browsing:** Pulls live information from the internet when needed. Useful for current events and tool research.
- **Mobile app features:** Speak to ChatGPT or use your camera to upload images.
- **System instructions:** Define tone, format, or rules inside a Custom GPT.
- **Tool and API integration:** Developers can connect GPTs to other apps, like Notion or scheduling tools.
- **Canvas (experimental):** A visual workspace where you can lay out ideas, diagrams, or notes alongside the chat. Useful for planning or visual tasks. Available in some GPT-4 accounts with advanced tools enabled.

## When to Consider Upgrading

- You need better accuracy or longer responses.
- You work with data or want help analyzing files.
- You want to build reusable assistants or workflows.
- You need features like memory, image input, or live browsing.
- You rely on ChatGPT regularly and want better performance.

# Limits and Gotchas

- **It makes stuff up (hallucination):** Sometimes ChatGPT gives answers that sound right but aren't. It might invent facts, URLs, or citations. Always double-check anything factual or important.
- **It doesn't know current events (unless browsing is on):** The model doesn't have live data unless web browsing is enabled. Even then, it can miss context or return outdated info.
- **It forgets mid-conversation (in long chats):** If a chat gets too long, it may forget earlier parts or lose consistency.
- **It may follow bad instructions too literally:** If a prompt is vague or poorly worded, the output can be off. Clear prompts are important.
- **Formatting and logic can break with complex tasks:** It can miscount, repeat sections, or mess up tables, especially in long outputs or technical writing.
- **It has no real understanding or beliefs:** ChatGPT doesn't "know" things. It generates text based on patterns.
- **It can change behavior unexpectedly:** Small changes to your prompt or earlier replies can lead to different results.
- **Custom GPTs may misbehave:** Even with good instructions, Custom GPTs can produce off-topic or inconsistent responses.
- **No true privacy or confidentiality:** Don't put sensitive client or business data into ChatGPT. It's still a third-party system.

# How to Use ChatGPT More Safely and Effectively

- **Ask it to double-check its own work:** Add a follow-up prompt like “Can you check for mistakes or inconsistencies?” It often catches its own errors.
- **Make it explain its reasoning:** Say “Write out the steps you took to get this answer.” This helps spot logic gaps or weak assumptions.
- **Be specific with prompts:** Clear, detailed instructions lead to better results. Say what role it should play, what format you want, and what to avoid.
- **Break up complex tasks:** For long or multi-step work, give it one step at a time. This improves quality and makes it easier to track.
- **Use short chats for clean results:** Start a new thread if things get off track. Long chats can lead to memory drift or confusion.
- **Repeat back instructions when needed:** If you're using a Custom GPT or longer prompt, ask it to summarize what it thinks the task is.
- **Test important outputs yourself:** Don't assume the answer is correct. Check math, code, citations, and key facts manually.
- **Use multiple prompts if needed:** Rewording or asking from another angle can produce better or more accurate results.
- **Keep sensitive data out:** If privacy is a concern, don't enter confidential or personal information. Use mock data instead.

# System & Settings Tips

These aren't model features, but they give you more control over how ChatGPT works. You'll find most of them in **Settings** (bottom left corner in the app).

- **Export Data:** You can export all your conversations and settings to a downloadable `.zip` file. Go to Settings → Data Controls → Export Data.
- **Custom Instructions:** This lets you set persistent preferences like how you want ChatGPT to respond (tone, format, goals). Found under Settings → Custom Instructions.
- **Memory Management:** If you're on GPT-4 with memory enabled, you can view, edit, or delete what the model remembers about you. Settings → Personalization → Manage Memory.
- **Beta Features Toggle:** Turn on experimental tools like **code interpreter**, **image input**, and **browsing** (if available). Settings → Settings & Beta → Beta features.
- **Clear Chat History:** You can disable or delete saved chats. Useful if you're testing prompts or sharing your screen.
- **Keyboard Shortcuts:** Use `/` to trigger command suggestions (like “/summarize” or “/upload file”) in the input box.
- **Mobile-Specific Features:** On mobile, you can use voice input or image input via your camera. This varies by platform and plan.
- **Dark Mode & Compact Layout:** Available in general settings.

# Prompt Engineering

Prompt engineering means writing clear instructions so the model gives you useful responses. You don't need to be technical. Just tell it what to do, like you would with a smart assistant.

This section shows how to structure prompts and gives you examples you can copy and adjust.

## Structuring Prompts

Good prompts are clear and specific. The model works best when it knows who it's supposed to be, what task it's doing, and how you want the answer.

### Basic Format
>You are [role]. Your task is to [goal].
>Here is the input: [data, text, question].
>Output should be [format, tone, or structure].

### Example 1
>You are a legal analyst. Your task is to summarize this contract in plain English.
>Output should be bullet points.

### Example 2
>You are a project manager. Your task is to break down a high-level goal into action steps.
>Here is the input: Launch a personal website to showcase my consulting services.
>Output should be a short task list with deadlines.

### Example 3
>You are a technical writer. Your task is to summarize the following meeting notes for a product update email.
>Here's the input: [Paste notes here]
>Output should be a short, clear email in plain language.


## Useful Prompts

These are plug-and-play prompts. You can copy them and change the content to fit your needs.

### Natural Speaking

(Modified from this [prompt source](https://old.reddit.com/r/ChatGPTPromptGenius/comments/1h2bkrs/i_finally_found_a_prompt_that_makes_chatgpt_write/))

>I would like to alter the way your talk. Please follow these instructions in this conversation:
>
>- Use simple language: Write plainly. Example: "I need help with this issue."
>- Avoid AI-giveaway phrases: Don't use clichés like "dive into," "unleash your potential," etc. Avoid: "Let's dive into this game-changing solution." Use instead: "Here's how it works."
>- Be direct and concise: Get to the point; remove unnecessary words. Example: "We should meet tomorrow."
>- Maintain a natural tone: Write as people normally speak; it's okay to start sentences with "and" or "but." Example: "And that's why it matters."
>- Avoid marketing language: Don't use hype or promotional words. Avoid: "This revolutionary product will transform your life." Use instead: "This product can help you."
>- Keep it real: Be honest; don't force friendliness. Example: "I don't think that's the best idea."
>- Stay away from fluff: Avoid unnecessary adjectives and adverbs. Example: "We finished the task."
>- Focus on clarity: Make your message easy to understand. Example: "Please send the file by Monday."
>- Avoid frequent use of em dashes.
>- Avoid frequent use of three-item lists.


# Documentation & Resources

- [ChatGPT pricing](https://openai.com/chatgpt/pricing)
- [ChatGPT release notes](https://help.openai.com/en/articles/6825453-chatgpt-release-notes)

# OpenAI products (June 2025)

- **ChatGPT**: A web and mobile app where you talk to GPT models directly. It's meant for general users. There's a free plan (GPT-3.5) and a paid plan (GPT-4-turbo). You can also create **Custom GPTs** inside the app that act like mini assistants with special instructions.
    - Use cases: write emails, summarize documents, plan projects, or brainstorm ideas—all in plain language, no coding needed.
- **OpenAI API:** Used by developers to add GPT (and other models) to software. You can send text or data to the model and get a response back. Pricing is based on usage (tokens). This is separate from the ChatGPT app.
    - Use cases: add AI features to your product. For example, build a support bot that answers customer questions based on your company docs.
- **Playground:** A web interface to test the API without writing code. It's helpful for trying different prompts, settings, and models before building something.
    - Use cases: test prompts and model settings before building anything.
- **Whisper:** OpenAI's speech-to-text model. Converts spoken audio into written text. You can access it through the API or tools that use it under the hood.
    - Use cases: transcribe meeting recordings or voice memos into text automatically.
- **DALL·E:** An image generation model. You describe an image in text, and it creates one. You can use this in ChatGPT (with the right tools enabled) or through the API.
    - Use cases: generate images for blog posts, mockups, or concept art.
- **Codex** *(used less now):* An earlier model for writing code. Replaced by GPT-4-turbo for most coding use cases.

# Glossary

- **ChatGPT**: A conversational interface built by OpenAI that lets users interact with GPT models through natural language. Available as a web app and mobile app, with free and paid versions using different model tiers (GPT-3.5 or GPT-4-turbo).
- **Context Window:** The maximum amount of text (in tokens) a model can “remember” in a single conversation or prompt. GPT-4-turbo supports up to 128,000 tokens (~300 pages of text), but older models have much smaller limits.
- **Custom GPTs:** Mini-apps built inside ChatGPT that allow you to customize behavior, memory, tools, and instructions, without writing code. Often used for tailored workflows or branded assistants.
- **Few-Shot Prompting:** A technique where you include a few examples in your prompt to show the model how to behave. It helps steer the response by providing context or formatting.
- **Fine-Tuning**: A follow-up training step where a pre-trained model (like GPT) is further trained on a smaller, specialized dataset. This helps the model adapt to specific industries, use cases, or writing styles, while still retaining its general language abilities.
- **Hallucination (in LLMs):** When a model confidently generates incorrect or made-up information. Common in LLMs due to how they generate language based on patterns—not true understanding.
- **Inference (in AI):** The process of generating an output (like a response or prediction) using a trained model. In simple terms: training teaches the model, inference is when you use it.
- **GPT (Generative Pre-trained Transformer)**: A type of AI model developed by OpenAI that generates human-like text based on a given input. Trained on large amounts of internet text to predict what comes next in a sentence, making it useful for tasks like writing, summarizing, and answering questions.
- **LLM (Large Language Model)**: A machine learning model trained on vast amounts of text to understand and generate human language. LLMs like GPT-4 are the core technology behind tools like ChatGPT, capable of reasoning, summarizing, writing, and more.
- **Machine Learning**: A type of computer programming where systems learn patterns from data instead of being explicitly programmed. It's the foundation behind technologies like recommendation engines, fraud detection, and AI tools like ChatGPT.
- **Memory (in ChatGPT):** A feature in paid ChatGPT that lets the model remember facts about you across sessions, like your name, preferences, or past instructions. This is different from the context window, which only remembers things *within* a single chat.
- **Model Training (in GPTs)**: The process of teaching a GPT by feeding it vast amounts of text (like books, websites, and articles) so it can learn patterns in language. During training, the model adjusts its internal settings to get better at predicting the next word in a sentence, over and over, across billions of examples.
- **Neural Network**: A type of machine learning model inspired by the way the human brain processes information. It consists of layers of interconnected “nodes” (like artificial neurons) that transform input data into outputs by learning patterns during training.
- **NLP (Natural Language Processing):** A field of AI focused on enabling computers to understand, interpret, and generate human language. NLP powers tools like ChatGPT, speech-to-text, translation apps, and sentiment analysis by combining linguistics with machine learning.
- **Prompt**: The text or instruction you give to an AI model to generate a response. A good prompt clearly defines the model's role, task, input, and desired output.
- **Prompt Engineering:** The art and practice of writing effective prompts to get high-quality results from language models. Involves structuring inputs clearly and anticipating model behavior.
- **RAG (Retrieval Augmented Generation)**: A technique that combines a language model with an external source of knowledge. Instead of only relying on what the model remembers, it “retrieves” relevant documents in real time, and then generates answers based on both the prompt and the retrieved info. This improves accuracy and keeps answers more up-to-date.
- **System Prompt:** A behind-the-scenes instruction given to a GPT to set its behavior before the user prompt is even entered. Custom GPTs use system prompts to shape personality, tone, or constraints.
- **Temperature (in prompts):** A setting that controls how creative or focused the model's responses are. Lower values (e.g. 0.2) make answers more predictable; higher values (e.g. 0.8) make them more varied and creative.
- **Token**: A chunk of text used by language models to process and generate language. Tokens can be as short as one character or as long as one word. For example, “ChatGPT is great” breaks into four tokens. Models are priced and limited based on the number of tokens used in an interaction.
- **Transformer**: A type of neural network architecture designed to handle sequential data, like text. Introduced in 2017, it powers modern language models (like GPT) by efficiently capturing the relationships between words in a sentence, regardless of their position.
- **Zero-Shot Prompting:** Prompting without examples; just giving instructions and expecting the model to figure it out based on its training.