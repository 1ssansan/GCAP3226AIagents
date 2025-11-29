# GCAP 3226 Human-AI Collaboration Report — Chen Man Ching (23232781)

## Executive Summary
Throughout this course, my use of generative AI evolved from occasional assistance to an integrated part of my learning and project workflow. I relied mostly on ChatGPT, GitHub Copilot, and the built-in AI tools in Jupyter Notebook. At the start, I viewed AI primarily as a convenient helper for debugging and simple code generation, but over time I discovered its value as a reasoning companion that supported my understanding of algorithms, mathematical modeling, and project design. Working with AI taught me that effective human–AI collaboration depends on my ability to provide context, evaluate responses critically, and control the direction of the work. This course changed how I perceive AI: instead of replacing my thinking, it amplified my ability to learn, reason, and complete complex tasks.

## AI Usage Overview
During the semester, I used AI tools for many different tasks. At first, I used ChatGPT mainly to understand new concepts. For example, I asked questions about regression, optimization, and how certain algorithms work. These explanations helped me follow lectures more easily. As the course continued, I started using AI for more technical tasks. When my Python code failed, I asked AI for help to find errors or explain why my logic did not work. I also used GitHub Copilot to generate simple code structures and help with repetitive tasks like writing loops or formatting plots.

Additionally, AI also helped me improve my writing. Sometimes my explanations were unclear, and AI helped me reorganize my paragraphs or add missing details. Toward the end of the course, I used AI not just for answers but as a thinking partner. I asked it to check my logic, challenge my ideas, and help compare different methods. My AI usage changed from basic support to deeper collaboration.

## Chat History Portfolio

### Example 1: VS Code learning for basic CS knowledge
When I started using the AI agent inside VS Code, I was completely new to coding, VS Code, and mathematical models. Since I am not a computer science or math student, I did not know how to set up my environment. During my in-class exercise, I opened the notebook but could not run any code. The terminal kept telling me that it could not find pandas, matplotlib, or seaborn. I did not understand why this happened, so I asked the AI agent for help and began my first conversation with it.

#### Chat Excerpt 1 — Installing Packages Failed
Me: “why i cannot run pip install pandas matplotlib seaborn”

AI Agent: “You cannot run pip install pandas matplotlib seaborn because the pip command is not found in your terminal. This usually means Python (and pip) is not installed, or pip is not in your system's PATH.”

AI Agent: “Try this command:

```
python3 -m pip install pandas matplotlib seaborn --user
```

AI Agent: “If python3 is also not found, you need to install Python first using `brew install python`.”

The AI explained that my computer could not find pip because Python was not correctly installed, or the path was missing. It also taught me an alternative command using `python3 -m pip install`. This was the first time I understood that “not finding pip” is often a system setup problem, not a coding problem.

#### Chat Excerpt 2 — Imports Not Working
Me: “The imports still cannot run. What should I do?”

AI Agent: “You need to restart your Jupyter kernel after installing the packages. The notebook environment does not automatically update. Restart the kernel and run the imports again.”

After following this instruction and restarting the kernel, the import statements finally worked. This helped me understand that VS Code’s terminal and notebook environment are separate, and I need to manage both.

As I continued working, I faced another problem. I did not know how to make pandas read a CSV file from my Mac desktop because I did not know the correct file path. This led to my third conversation with the AI.

#### Chat Excerpt 3 — Finding File Path on Mac
Me: “How do I let pandas read a CSV file from my desktop? What is the correct path?”

AI Agent: “On macOS, your Desktop path usually looks like this:

```
/Users/your-username/Desktop/filename.csv
```

You can right-click the file in Finder, choose ‘Get Info,’ and copy the full path.”

After this explanation, I finally understood how Mac file paths work and successfully loaded my CSV into pandas.

Through these three conversations, I learned the basic skills needed to work with VS Code, for instance installing packages, restarting kernels, and locating file paths. These tasks were very confusing at first, but the AI agent helped break them down into simple steps that I could follow. This experience made me feel more confident using coding tools, even though I am not from a technical background.

### Example 2: using ChatGPT to improve my presentation content and prepare Q&A

#### Chat Excerpt — Refining Presentation Language & Preparing Q&A
Me: “I am working on Part 5 of our GCAP 3226 presentation. I am not sure if my language is formal enough or if the structure is clear. Can you help me improve it?”

AI Agent: “Your draft is generally clear, but some parts are too conversational. I will refine the tone and reorganize the structure to make it more academic.”

Me: [I sent my full draft]

AI Agent: [Returned a revised, clearer, and more formal version]

AI Agent: “It is better to highlight the logic between sections and avoid casual phrases. Here is a revised version with a more academic tone and smoother transitions.”

Me: “We will have a Q&A after the presentation. Based on our topic (HKO Signal No. 8), what questions might the professor ask?”

AI Agent:

AI Agent: “Possible questions include:

- ‘How did you evaluate whether the HKO issued the signal too early or too late?’
- ‘Do you think forecast-based issuance should be allowed even if wind stations do not meet the threshold?’
- ‘What are the limitations of using only wind station data?’
- ‘Why is 3–4 hours of lead time reasonable?’

I can also provide short sample answers if needed.”

In this interaction, I relied on ChatGPT to review a complete section of my draft presentation. I often write in a mixed casual–academic style, so I needed help making the tone more formal. ChatGPT reorganized several paragraphs, strengthened the transitions, and replaced informal expressions with clearer academic phrasing. These revisions helped me understand what formal academic communication should look like, and I incorporated many of these improved sentences into my final presentation script.

Overall, this exchange showed me that AI is not only useful for correcting grammar but also for supporting deeper academic thinking. ChatGPT helped me identify gaps in my reasoning, anticipate possible criticisms, and improve the clarity of my arguments. Through this process, I realized that AI can be an effective learning tool that supports both writing and critical thinking in university coursework.

## Reflection on Human-AI Collaboration
Working with different AI tools across this course helped me understand both what AI can do well and what humans must still take responsibility for. I learned very quickly that humans always lead the process, while AI plays a supporting role. For example, in GCAP 3226, AI could not understand the assignment goals, the research focus, or the presentation requirements unless I explained them clearly first. Only after I gave enough background could AI help me rewrite sentences, improve structure, or think of possible Q&A questions the professor might ask. This showed me that good AI output always depends on clear human guidance.

However, I discovered that AI information cannot be trusted without checking. Even when I used Grok’s “expert mode” to search online data, such as how early the Hong Kong Observatory released Signal No. 8 for eight different typhoons, but the results were completely wrong. Many links were broken or unreliable, and some did not contain any relevant data at all. This experience taught me that AI is not a reliable source by itself. I always needed to fact-check using lecture notes, official HKO documents, codebooks, or policy guidelines. AI can make searching faster, but humans must still verify the truth.

Over time, I started to view AI more as a “reasoning partner” than as an encyclopedia. AI helped me clarify ideas, test arguments, and explain complicated concepts in simpler terms. For example, when I used VS Code, the AI agent helped break down coding steps and explain errors, which was useful because I am not a computer science student. In writing tasks, AI helped make my language more formal and my structure clearer. However, its output was not always perfect. Sometimes it was too long, too casual, or too academic, so I still needed to edit the content myself. When different AI tools gave different answers, I had to analyze which one made more sense. This process strengthened my critical thinking.

Another important reflection is the risk of over-relying on AI. I noticed that when AI helped too quickly, I may sometimes understand the assignment or dataset less deeply. AI can make writing easier, but it may weaken my academic or critical thinking if I rely on it too much. Because of this, I learned that AI should support my work, not replace my effort. Real learning happens when I question information, compare options, and make decisions myself.

Overall, this course changed how I understand human and AI collaboration. AI can provide speed, organization, and alternative ideas, but humans must provide context, judgment, and final decisions. In the future, I will continue to use AI as a helpful tool, but I will always take responsibility for the final output. AI can guide me, but it cannot replace my understanding of the course goals or my critical thinking. Good collaboration happens when AI supports human reasoning instead of replacing it.