# Awesome Agentic AI [![Awesome](https://awesome.re/badge.svg)](https://awesome.re)

A curated list of awesome Agentic AI resources, tools, frameworks, platforms, and learning materials.

## Contents

- [What is Agentic AI?](#what-is-agentic-ai)
- [Commercial Products](#commercial-products)
- [Open Source Projects](#open-source-projects)
- [Learning Resources](#learning-resources)
- [News and Research](#news-and-research)
- [Feature Comparison Matrix](#feature-comparison-matrix)

## What is Agentic AI?

Agentic AI refers to artificial intelligence systems that can act autonomously on behalf of users to achieve specific goals. Unlike traditional generative AI that simply responds to prompts, agentic AI can plan, reason, make decisions, and take actions in dynamic environments.

### Key Characteristics

- **Autonomy**: Agentic AI can operate independently with minimal human supervision, making decisions and taking actions to accomplish tasks.
- **Goal-oriented**: These systems work toward specific objectives, planning steps and adapting strategies as needed.
- **Tool use**: Agentic AI can leverage various tools and APIs to interact with external systems and accomplish complex tasks.
- **Memory and context awareness**: These systems maintain context across interactions and learn from past experiences.
- **Reasoning capabilities**: Agentic AI can analyze situations, solve problems, and make logical inferences.
- **Adaptability**: These systems can adjust to changing circumstances and learn from feedback.

### How Agentic AI Works

Agentic AI typically follows a cycle of:
1. **Perception**: Gathering information from the environment
2. **Planning**: Determining actions to achieve goals
3. **Execution**: Carrying out planned actions
4. **Learning**: Updating knowledge based on outcomes

### Agentic AI vs. Generative AI

While generative AI focuses on creating content based on patterns in training data, agentic AI emphasizes decision-making and action. Key differences include:

| Aspect | Generative AI | Agentic AI |
|--------|--------------|------------|
| Primary function | Content creation | Task completion |
| User interaction | Responds to prompts | Proactively works toward goals |
| Autonomy | Limited to generating responses | Can plan and execute multi-step tasks |
| External systems | Limited integration | Can use tools and APIs |
| Memory | Often limited to current conversation | Maintains persistent memory |

## Commercial Products

### Enterprise Agentic AI Platforms

1. **Manus AI**: Versatile autonomous AI agent platform with extensive tool integration capabilities.
   - **Key Features**: Autonomous task execution, multi-modal capabilities, advanced tool integration, adaptive learning
   - **Performance**: State-of-the-art results on GAIA benchmark (86.5% on Level 1, 70.1% on Level 2, 57.7% on Level 3)
   - **Architecture**: Linux sandbox environment, shell execution, web browser control, file system management, deployment capabilities
   - **Use Cases**: Report writing, data analysis, content generation, travel planning, file processing
   - **Website**: [Manus AI](https://manus.im/)

2. **Anthropic Claude**: Advanced AI assistant with agentic capabilities, strong reasoning, and tool use.
   - **Key Features**: Context window of 200K tokens, API integration, document analysis
   - **Website**: [Anthropic](https://www.anthropic.com/)

3. **OpenAI GPT-4o and Assistants API**: Powerful foundation models with agentic capabilities through the Assistants API.
   - **Key Features**: Function calling, code interpreter, retrieval, vision capabilities
   - **Website**: [OpenAI](https://openai.com/blog/assistants-api)

4. **Google Gemini**: Google's multimodal AI with agentic capabilities.
   - **Key Features**: Multimodal understanding, reasoning, code generation
   - **Website**: [Google Gemini](https://gemini.google.com/)

5. **Adept AI**: Enterprise-focused agentic AI platform.
   - **Key Features**: Action transformers, business process automation, custom agent creation
   - **Website**: [Adept](https://www.adept.ai/)

6. **Cognition Labs Devin**: AI software engineer with autonomous coding capabilities.
   - **Key Features**: Full-stack development, debugging, project planning
   - **Website**: [Cognition Labs](https://www.cognition.dev/)

7. **Salesforce Agentforce**: Enterprise-grade AI agents for business applications.
   - **Key Features**: CRM integration, business process automation, customer service
   - **Website**: [Salesforce Agentforce](https://www.salesforce.com/agentforce/)

8. **Microsoft Copilot**: AI assistant with agentic capabilities across Microsoft's ecosystem.
   - **Key Features**: Office integration, coding assistance, data analysis
   - **Website**: [Microsoft Copilot](https://copilot.microsoft.com/)

### Specialized Agentic AI Tools

1. **Moveworks**: AI platform for IT support and employee service automation.
   - **Key Features**: IT ticket resolution, knowledge base integration, conversational interface
   - **Website**: [Moveworks](https://www.moveworks.com/)

2. **Inflection AI Pi**: Personal AI assistant with agentic capabilities.
   - **Key Features**: Natural conversation, personalization, memory
   - **Website**: [Inflection AI](https://inflection.ai/)

3. **Perplexity AI**: AI search engine with agentic research capabilities.
   - **Key Features**: Real-time information retrieval, citation generation, conversational interface
   - **Website**: [Perplexity AI](https://www.perplexity.ai/)

4. **Cohere**: Enterprise-focused LLM platform with agentic capabilities.
   - **Key Features**: RAG, tool use, enterprise data integration
   - **Website**: [Cohere](https://cohere.com/)

5. **Fixie.ai**: Platform for building and deploying AI agents.
   - **Key Features**: Agent orchestration, knowledge integration, API connections
   - **Website**: [Fixie.ai](https://www.fixie.ai/)

6. **Reka**: Advanced AI with strong reasoning and planning capabilities.
   - **Key Features**: Long-context understanding, complex reasoning, creative problem-solving
   - **Website**: [Reka](https://reka.ai/)

7. **Klu**: No-code platform for building AI agents.
   - **Key Features**: Visual agent builder, workflow automation, business process integration
   - **Website**: [Klu](https://klu.ai/)

8. **Databricks Mosaic AI**: Enterprise AI platform with agent capabilities.
   - **Key Features**: Data processing, analytics integration, enterprise security
   - **Website**: [Databricks](https://www.databricks.com/product/mosaic-ai)

9. **Nvidia NIM**: Microservices platform for deploying AI agents.
   - **Key Features**: Scalable deployment, enterprise integration, optimization
   - **Website**: [Nvidia NIM](https://www.nvidia.com/en-us/ai-data-science/products/nim/)

10. **Automation Anywhere Automation Co-Pilot**: RPA platform with agentic AI capabilities.
    - **Key Features**: Process automation, document processing, enterprise integration
    - **Website**: [Automation Anywhere](https://www.automationanywhere.com/)

11. **Glean**: Enterprise search with agentic capabilities.
    - **Key Features**: Knowledge discovery, document understanding, enterprise data integration
    - **Website**: [Glean](https://www.glean.com/)

12. **Jasper**: AI content platform with agentic features for marketing.
    - **Key Features**: Content generation, brand voice customization, marketing automation
    - **Website**: [Jasper](https://www.jasper.ai/)

## Open Source Projects

### General Purpose Autonomous Agents

1. **AutoGPT**: One of the first autonomous GPT-4 agents capable of breaking down tasks into subtasks.
   - **GitHub**: [Significant-Gravitas/Auto-GPT](https://github.com/Significant-Gravitas/Auto-GPT)
   - **Features**: Long-term memory, web browsing, file operations

2. **AgentGPT**: Web-based platform for creating and deploying autonomous AI agents.
   - **GitHub**: [reworkd/AgentGPT](https://github.com/reworkd/AgentGPT)
   - **Features**: Web UI, customizable goals, cloud deployment

3. **GPT Engineer**: Agent that generates entire codebases from a prompt.
   - **GitHub**: [AntonOsika/gpt-engineer](https://github.com/AntonOsika/gpt-engineer)
   - **Features**: Code generation, project structuring, iterative refinement

4. **OpenDevin**: Open-source autonomous software engineer.
   - **GitHub**: [OpenDevin/OpenDevin](https://github.com/OpenDevin/OpenDevin)
   - **Features**: Code generation, debugging, project management

5. **SuperAGI**: Autonomous AI agent framework with memory and planning.
   - **GitHub**: [TransformerOptimus/SuperAGI](https://github.com/TransformerOptimus/SuperAGI)
   - **Features**: Tool use, memory management, resource management

6. **HuggingGPT**: Connecting LLMs with ML models for solving AI tasks.
   - **GitHub**: [microsoft/JARVIS](https://github.com/microsoft/JARVIS)
   - **Features**: Task planning, model selection, result integration

### Multi-Agent Frameworks

1. **AutoGen**: Framework for building multi-agent systems with LLMs.
   - **GitHub**: [microsoft/autogen](https://github.com/microsoft/autogen)
   - **Features**: Agent conversation, tool use, customizable roles

2. **CrewAI**: Framework for orchestrating role-based autonomous AI agents.
   - **GitHub**: [joaomdmoura/crewAI](https://github.com/joaomdmoura/crewAI)
   - **Features**: Role definition, task delegation, agent collaboration

3. **LangGraph**: Library for building stateful, multi-agent applications with LLMs.
   - **GitHub**: [langchain-ai/langgraph](https://github.com/langchain-ai/langgraph)
   - **Features**: State management, agent communication, workflow design

4. **CAMEL**: Communicative Agents for "Mind" Exploration of Large Scale Language Models.
   - **GitHub**: [camel-ai/camel](https://github.com/camel-ai/camel)
   - **Features**: Role-playing, task decomposition, agent collaboration

5. **DSPy**: Framework for programming with foundation models.
   - **GitHub**: [stanfordnlp/dspy](https://github.com/stanfordnlp/dspy)
   - **Features**: Modular components, optimization, evaluation

### Coding and Development Agents

1. **Smol Developer**: Small, focused code generation agent.
   - **GitHub**: [smol-ai/developer](https://github.com/smol-ai/developer)
   - **Features**: Code generation, project scaffolding, lightweight

2. **MetaGPT**: Multi-agent framework specializing in software development.
   - **GitHub**: [geekan/MetaGPT](https://github.com/geekan/MetaGPT)
   - **Features**: Software development lifecycle, documentation, testing

3. **Aider**: Terminal-based coding assistant with Git integration.
   - **GitHub**: [paul-gauthier/aider](https://github.com/paul-gauthier/aider)
   - **Features**: Code editing, Git integration, pair programming

4. **Sweep**: AI junior developer that turns GitHub issues into pull requests.
   - **GitHub**: [sweepai/sweep](https://github.com/sweepai/sweep)
   - **Features**: Issue resolution, code generation, PR creation

### Specialized Agents

1. **MiniAGI**: Simplified autonomous agent focused on research tasks.
   - **GitHub**: [muellerberndt/mini-agi](https://github.com/muellerberndt/mini-agi)
   - **Features**: Web search, document analysis, report generation

2. **BabyAGI**: Task-driven autonomous agent with simple architecture.
   - **GitHub**: [yoheinakajima/babyagi](https://github.com/yoheinakajima/babyagi)
   - **Features**: Task management, execution, prioritization

3. **GPT Researcher**: Autonomous agent for comprehensive research on any topic.
   - **GitHub**: [assafelovic/gpt-researcher](https://github.com/assafelovic/gpt-researcher)
   - **Features**: Web search, information synthesis, report generation

4. **MemGPT**: System for augmenting LLMs with tools and memory management.
   - **GitHub**: [cpacker/MemGPT](https://github.com/cpacker/MemGPT)
   - **Features**: Memory management, context handling, persistent conversations

### Agent Development Tools and SDKs

1. **LangChain**: Framework for developing applications with LLMs.
   - **GitHub**: [langchain-ai/langchain](https://github.com/langchain-ai/langchain)
   - **Features**: Chains, agents, memory, document loaders

2. **LlamaIndex**: Data framework for LLM applications.
   - **GitHub**: [jerryjliu/llama_index](https://github.com/jerryjliu/llama_index)
   - **Features**: Data indexing, retrieval, query engines

3. **Haystack**: Framework for building NLP applications.
   - **GitHub**: [deepset-ai/haystack](https://github.com/deepset-ai/haystack)
   - **Features**: Document retrieval, question answering, agents

4. **Semantic Kernel**: Integration framework for LLMs in applications.
   - **GitHub**: [microsoft/semantic-kernel](https://github.com/microsoft/semantic-kernel)
   - **Features**: Skills management, memory, planning

5. **Guidance**: Language for controlling text generation models.
   - **GitHub**: [guidance-ai/guidance](https://github.com/guidance-ai/guidance)
   - **Features**: Structured generation, control flow, templating

### Agent Evaluation and Benchmarking

1. **AgentBench**: Benchmark for evaluating LLM agents.
   - **GitHub**: [thudm/agentbench](https://github.com/thudm/agentbench)
   - **Features**: Diverse tasks, standardized evaluation, leaderboard

2. **Guardrails**: Tool for implementing guardrails in LLM applications.
   - **GitHub**: [guardrails-ai/guardrails](https://github.com/guardrails-ai/guardrails)
   - **Features**: Input validation, output validation, safety checks

### BabyAGI Variants

1. **BabyBeeAGI**: Experimental autonomous agent with enhanced capabilities.
   - **GitHub**: [yoheinakajima/babybeeagi](https://github.com/yoheinakajima/babybeeagi)
   - **Features**: Task creation, execution, resource management

2. **SocraticAI**: Agent focused on reasoning through dialogue.
   - **GitHub**: [socratic-ai/socraticai](https://github.com/socratic-ai/socraticai)
   - **Features**: Dialogue-based reasoning, knowledge exploration

### Agent Simulation and Society

1. **Generative Agents**: Simulated agents with memory, reflection, and planning.
   - **GitHub**: [joonspk-research/generative_agents](https://github.com/joonspk-research/generative_agents)
   - **Features**: Memory streams, reflection, social interaction

2. **Camel-AutoGPT**: Combining CAMEL and AutoGPT for enhanced agent capabilities.
   - **GitHub**: [SamurAIGPT/Camel-AutoGPT](https://github.com/SamurAIGPT/Camel-AutoGPT)
   - **Features**: Role-based agents, autonomous task execution

## Learning Resources

### Online Courses

1. **Agentic AI and AI Agents for Leaders Specialization** - Coursera/Vanderbilt University
   - **Description**: Comprehensive specialization providing leaders with understanding of Agentic AI and AI agents for driving innovation and strategic decision-making.
   - **Instructor**: Dr. Jules White
   - **Duration**: 1 month (3 hours/week)
   - **Level**: Beginner
   - **URL**: [Coursera](https://www.coursera.org/specializations/ai-agents-for-leaders)

2. **Agentic AI and AI Agents: A Primer for Leaders** - Coursera
   - **Description**: Course that demystifies Agentic AI, teaching how these agents work and how to design them.
   - **URL**: [Coursera](https://www.coursera.org/learn/agentic-ai)

3. **Artificial Intelligence A-Z 2025: Agentic AI, Gen AI, and RL** - Udemy
   - **Description**: Comprehensive course teaching how to build 8 different AI agents using various techniques including foundation models, reinforcement learning, and more.
   - **Instructors**: Hadelin de Ponteves, Kirill Eremenko, SuperDataScience Team
   - **Rating**: 4.4/5 (44,613 ratings)
   - **URL**: [Udemy](https://www.udemy.com/course/artificial-intelligence-az/)

4. **Agentic AI - A Modern Approach of Automation** - Euron
   - **Description**: Beginner-friendly course providing a deep dive into Agentic AI for solving complex problems autonomously.
   - **URL**: [Euron](https://euron.one/course/agentic-ai-a-mordern-approach-of-automation)

5. **Agentic Intelligence for Leaders** - Maven
   - **Description**: Course teaching how to increase value and gain competitive advantage by mastering the next evolution of AI.
   - **Instructors**: Pascal Bornet and Brian Solis
   - **URL**: [Maven](https://maven.com/the-future-solving-company/agentic-intelligence-for-leaders)

### Learning Paths and Tutorials

1. **Agentic AI Learning Path** - ProjectPro
   - **Description**: Structured learning path covering fundamentals, tools, frameworks, project ideas, and advanced topics in Agentic AI.
   - **Features**: Step-by-step guide, project ideas, resource recommendations
   - **URL**: [ProjectPro](https://www.projectpro.io/article/agentic-ai-learning-path/1091)

2. **How to Become an Agentic AI Expert** - Analytics Vidhya
   - **Description**: Learning path guiding through key concepts, tools, and techniques to build AI agents.
   - **URL**: [Analytics Vidhya](https://www.analyticsvidhya.com/blog/2024/10/learning-path-for-ai-agents/)

### Books

1. **AI Agents in Action** - Manning Publications
   - **Author**: Micheal Lanham
   - **Published**: February 2025
   - **Description**: Guide to building production-ready assistants, multi-agent systems, and behavioral agents using state-of-the-art tools.
   - **Topics**: Knowledge management, memory systems, feedback loops, collaborative multi-agent systems
   - **URL**: [Manning](https://www.manning.com/books/ai-agents-in-action)

2. **Practical AI Agents**
   - **Description**: Guide to building and implementing AI agents for real-world applications.
   - **Mentioned in**: [Quora](https://www.quora.com/What-are-the-best-books-or-online-resources-to-learn-about-AI-Agents-and-their-real-world-use-cases)

3. **LLM-Based Agents**
   - **Description**: Book focusing on creating agents using large language models.
   - **Mentioned in**: [Quora](https://www.quora.com/What-are-the-best-books-or-online-resources-to-learn-about-AI-Agents-and-their-real-world-use-cases)

### Community Resources

1. **HuggingFace's smolagents**
   - **Description**: Framework for learning how agents work, implementing a basic agent framework within 1000 lines of code.
   - **Mentioned in**: [Reddit](https://www.reddit.com/r/singularity/comments/1hvrjfx/what_courses_or_resources_can_help_me_create_ai/)

## News and Research

### Recent Industry Developments

1. **Accenture Expands AI Refinery and Launches Industry Agent Solutions** (March 2025)
   - **Summary**: Accenture has expanded its AI Refinery platform with an AI agent builder that allows business users to quickly build and customize agents without coding. The company is developing over 50 industry-specific AI agent solutions with a goal of having more than 100 by the end of 2025.
   - **Key Applications**: Telecommunications call centers, insurance underwriting, order-to-cash processes, commercial banking
   - **Source**: [Accenture Newsroom](https://newsroom.accenture.com/news/2025/accenture-expands-ai-refinery-and-launches-new-industry-agent-solutions-to-accelerate-agentic-ai-adoption)

2. **Agentic AI Set to Change How Business Gets Done** (March 2025)
   - **Summary**: ServiceNow executives predict agentic AI will cause a more rapid and impactful shift in business operations than previous technological revolutions. They highlight use cases like automated employee onboarding and domain-specific agents that can work together to handle complex business processes.
   - **Key Quote**: "Agentic AI cannot completely take the place of a human, but what it can do is work alongside your teams—handling repetitive tasks, seeking out information and resources, doing work in the background—24/7, 365 days a year." - Chris Bedi, Chief Customer Officer at ServiceNow
   - **Source**: [Deloitte Insights](https://www2.deloitte.com/us/en/insights/focus/tech-trends/2025/servicenow-and-agentic-ai-set-to-change-how-business-gets-done.html)

3. **AWS Launches New Agentic AI for Bedrock** (March 2025)
   - **Summary**: AWS has introduced new agentic AI capabilities for Amazon Bedrock, focusing on automation and enterprise applications.
   - **Source**: [CRN](https://www.crn.com/news/ai/2025/aws-launches-new-agentic-ai-for-bedrock-the-next-frontier-in-computing)

4. **Industry-First Agentic AI Services Study by ISG** (March 2025)
   - **Summary**: ISG has launched a research study examining providers of agentic AI services as part of a series of 2025 research reports on AI and analytics.
   - **Source**: [Business Wire](https://www.businesswire.com/news/home/20250317271217/en/Industry-First-Agentic-AI-Services-Study-Bolsters-Broad-ISG-Portfolio-of-AI-Analytics-Provider-Research)

### Cybersecurity Implications

1. **How Agentic AI Will Drive the Future of Malware** (March 2025)
   - **Summary**: Security experts warn that autonomous AI agents could be weaponized to create sophisticated malware that can scan the internet, identify targets, design social engineering attacks, and adapt tactics automatically.
   - **Key Concern**: "Agentic AI may consist of multiple independent agents, each specialized in handling a particular task, working cooperatively towards a common goal, and possibly, in the hands of threat actors, leading to the creation of self-driven AI-enabled malware."
   - **Mitigation Strategies**: Training employees to detect AI-powered attacks, using defensive AI agents, implementing phishing-resistant MFA
   - **Source**: [SC Media](https://www.scworld.com/perspective/how-agentic-ai-will-drive-the-future-of-malware)

### Market Analysis and Predictions

1. **AI Agents in 2025: Expectations vs. Reality** (March 2025)
   - **Summary**: IBM experts discuss the hype versus reality of AI agents in 2025. While 99% of developers surveyed are exploring or developing AI agents, experts caution that current "agents" are primarily LLMs with function calling capabilities rather than truly autonomous systems.
   - **Key Quote**: "The true definition [of an AI agent] is an intelligent entity with reasoning and planning capabilities that can autonomously take action. Those reasoning and planning capabilities are up for discussion."
   - **Source**: [IBM](https://www.ibm.com/think/insights/ai-agents-2025-expectations-vs-reality)

2. **Agentic AI: Three Themes to Watch for 2025** (December 2024)
   - **Summary**: Constellation Research identifies key trends in agentic AI platforms for 2025.
   - **Source**: [Constellation Research](https://www.constellationr.com/blog-news/insights/agentic-ai-three-themes-watch-2025)

3. **Deloitte Predicts 25% of Companies Using Gen AI Will Launch Agentic AI Pilots in 2025** (March 2025)
   - **Summary**: According to Deloitte's predictions, a quarter of companies already using generative AI will begin experimenting with agentic AI this year.
   - **Source**: [Computerworld](https://www.computerworld.com/article/3843138/agentic-ai-ongoing-coverage-of-its-impact-on-the-enterprise.html)

## Feature Comparison Matrix

This matrix compares key features across major agentic AI tools, both commercial and open-source, to help you select the right solution for your needs.

### Core Capabilities

| Tool | Type | Browser Tool | GitHub Tool | Document Parser | Code Generation | Multi-Agent Support | Memory Management | Planning | Reasoning |
|------|------|-------------|-------------|-----------------|-----------------|---------------------|-------------------|----------|-----------|
| **Manus AI** | Commercial | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **Anthropic Claude** | Commercial | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| **OpenAI Assistants** | Commercial | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| **Google Gemini** | Commercial | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| **Adept AI** | Commercial | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| **Cognition Labs Devin** | Commercial | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| **AutoGPT** | Open Source | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| **AgentGPT** | Open Source | ✅ | ❌ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| **LangChain** | Open Source | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **AutoGen** | Open Source | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **CrewAI** | Open Source | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **LangGraph** | Open Source | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |
| **GPT Engineer** | Open Source | ❌ | ✅ | ✅ | ✅ | ❌ | ❌ | ✅ | ✅ |
| **OpenDevin** | Open Source | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | ✅ |
| **MetaGPT** | Open Source | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ |

### Integration and Deployment

| Tool | API Access | Custom Tool Integration | Cloud Deployment | Self-Hosted | Enterprise Security | Multimodal | Benchmarks |
|------|------------|------------------------|------------------|-------------|---------------------|------------|------------|
| **Manus AI** | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | GAIA SOTA |
| **Anthropic Claude** | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | MMLU, HumanEval |
| **OpenAI Assistants** | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | MMLU, HumanEval |
| **Google Gemini** | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | MMLU, HumanEval |
| **Adept AI** | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | Proprietary |
| **Cognition Labs Devin** | ✅ | ✅ | ✅ | ❌ | ✅ | ✅ | SWE-bench |
| **AutoGPT** | ✅ | ✅ | ❌ | ✅ | ❌ | ❌ | AgentBench |
| **AgentGPT** | ✅ | ✅ | ✅ | ✅ | ❌ | ❌ | N/A |
| **LangChain** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | N/A |
| **AutoGen** | ✅ | ✅ | ✅ | ✅ | ✅ | ✅ | AgentBench |
| **CrewAI** | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | N/A |
| **LangGraph** | ✅ | ✅ | ✅ | ✅ | ❌ | ✅ | N/A |
| **GPT Engineer** | ❌ | ❌ | ❌ | ✅ | ❌ | ❌ | N/A |
| **OpenDevin** | ✅ | ✅ | ❌ | ✅ | ❌ | ❌ | SWE-bench |
| **MetaGPT** | ✅ | ✅ | ❌ | ✅ | ❌ | ✅ | N/A |

### Use Case Suitability

| Tool | General Purpose | Software Development | Research | Data Analysis | Content Creation | Business Automation | Customer Service |
|------|----------------|----------------------|----------|---------------|------------------|---------------------|------------------|
| **Manus AI** | ✅ High | ✅ High | ✅ High | ✅ High | ✅ High | ✅ High | ✅ Medium |
| **Anthropic Claude** | ✅ High | ✅ Medium | ✅ High | ✅ Medium | ✅ High | ✅ Medium | ✅ High |
| **OpenAI Assistants** | ✅ High | ✅ Medium | ✅ High | ✅ Medium | ✅ High | ✅ Medium | ✅ High |
| **Google Gemini** | ✅ High | ✅ Medium | ✅ High | ✅ Medium | ✅ High | ✅ Medium | ✅ Medium |
| **Adept AI** | ✅ Medium | ✅ Medium | ✅ Medium | ✅ Medium | ✅ Medium | ✅ High | ✅ Medium |
| **Cognition Labs Devin** | ❌ Low | ✅ High | ✅ Medium | ✅ Medium | ❌ Low | ❌ Low | ❌ Low |
| **AutoGPT** | ✅ Medium | ✅ Medium | ✅ High | ✅ Medium | ✅ Medium | ✅ Low | ❌ Low |
| **AgentGPT** | ✅ Medium | ✅ Low | ✅ Medium | ✅ Low | ✅ Medium | ✅ Low | ❌ Low |
| **LangChain** | ✅ High | ✅ High | ✅ High | ✅ High | ✅ High | ✅ High | ✅ High |
| **AutoGen** | ✅ High | ✅ High | ✅ High | ✅ High | ✅ Medium | ✅ Medium | ✅ Medium |
| **CrewAI** | ✅ High | ✅ Medium | ✅ High | ✅ Medium | ✅ Medium | ✅ Medium | ✅ Medium |
| **LangGraph** | ✅ High | ✅ Medium | ✅ High | ✅ Medium | ✅ Medium | ✅ Medium | ✅ Medium |
| **GPT Engineer** | ❌ Low | ✅ High | ❌ Low | ❌ Low | ❌ Low | ❌ Low | ❌ Low |
| **OpenDevin** | ❌ Low | ✅ High | ✅ Low | ✅ Low | ❌ Low | ❌ Low | ❌ Low |
| **MetaGPT** | ✅ Medium | ✅ High | ✅ Medium | ✅ Medium | ✅ Medium | ✅ Medium | ❌ Low |

## Contributing

Contributions welcome! Please read the [contribution guidelines](contributing.md) first.

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0)

To the extent possible under law, the contributors have waived all copyright and related or neighboring rights to this work.
