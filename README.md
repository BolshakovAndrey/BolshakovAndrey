# Hi, I'm Andrey Bolshakov

### Senior Software Engineer · Full-stack product development

I build and maintain complete systems: interactive web interfaces, Python and TypeScript services, integrations, and analytics. My work spans architecture, implementation, testing, deployment, and ongoing support.

Full-stack developer at **VoxLink**, based in **Belgrade, Serbia**.

[Portfolio](https://bolshakovandrey.github.io/personal_portfolio/) · [Visual editor demo](https://bolshakovandrey.github.io/qcodes-react-demo-pages/) · [BeyondGreen video](https://youtu.be/R_AA3WqmVyw)

## Professional work · VoxLink

My professional work at VoxLink is hosted on GitLab, so this GitHub profile does not show the full scope of that work.

For QCodes, I developed the **client-side visual script editor**, including its implementation, testing, and maintenance. The [separate public editor demo](https://bolshakovandrey.github.io/qcodes-react-demo-pages/) illustrates the interface; the production implementation remains private.

## Selected work

### BeyondGreen — verification for AI-assisted code changes

A workflow for evaluating React state-to-signals changes with reproducible checks, a baseline comparison, and inspectable evidence. The evaluation uses a bounded synthetic benchmark; it is not a claim of general production readiness.

**My contribution:** architecture, implementation, test and evaluation tooling, and delivery.

[Watch the project walkthrough](https://youtu.be/R_AA3WqmVyw)

### Visual Script Editor — public React demo

A node-based interface for editing branching conversation scripts, with questions, answers, connections, and connection constraints.

**My contribution:** the client-side visual editor. This is a separate public demonstration; the production implementation remains private. The operator preview is an illustration, not a live backend demonstration.

[Open the interactive editor](https://bolshakovandrey.github.io/qcodes-react-demo-pages/)

### Lubimovka — team delivery

Backend development for the Lubimovka drama festival website, January–June 2022. Contributed as part of the team that brought the project to release.

[Festival website](https://lubimovka.art/) · [Letter of gratitude](https://user-images.githubusercontent.com/19635244/201071937-e0b517a7-81fa-43cd-a15f-2f4007578a66.png)

## LLM engineering

- Build LangGraph and CrewAI agent workflows, including candidate generation, coder–tester loops, and model-based comparison.
- Combine structured outputs and schema validation with execution results, runtime and memory measurements, and regression tests.
- Integrate multiple model providers with fallbacks; work with vision, speech transcription, and filtering of known transcription failure patterns.
- Assemble context from documents and database-backed factual briefs. My document-loading work does not use vector databases or embeddings.

## How I work

- Own the engineering lifecycle, from design decisions to deployment and maintenance.
- Treat tests, reproducible runs, and failure handling as part of the implementation.
- Review and validate AI-assisted code; take responsibility for the resulting system.
- Keep client source code and private data out of public demonstrations.

Not all of my work is public. This profile highlights shareable examples rather than exposing private repositories.

## Technologies

<!-- OpenAI logo source: simple-icons/simple-icons, tag 14.15.0, icons/openai.svg. -->

### Languages

![TypeScript](https://img.shields.io/badge/TypeScript-161B22?style=flat-square&logo=typescript&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-161B22?style=flat-square&logo=javascript&logoColor=white)
![Python](https://img.shields.io/badge/Python-161B22?style=flat-square&logo=python&logoColor=white)
![SQL](https://img.shields.io/badge/SQL-161B22?style=flat-square)

### LLM orchestration & integration

![LangChain](https://img.shields.io/badge/LangChain-161B22?style=flat-square&logo=langchain&logoColor=white)
![LangGraph](https://img.shields.io/badge/LangGraph-161B22?style=flat-square&logo=langgraph&logoColor=white)
![CrewAI](https://img.shields.io/badge/CrewAI-161B22?style=flat-square&logo=crewai&logoColor=white)
![MCP adapters](https://img.shields.io/badge/MCP%20adapters-161B22?style=flat-square&logo=modelcontextprotocol&logoColor=white)
![Vercel AI SDK](https://img.shields.io/badge/Vercel%20AI%20SDK-161B22?style=flat-square&logo=vercel&logoColor=white)

### Model providers & speech

![OpenAI API / SDK](https://img.shields.io/badge/OpenAI%20API%20%2F%20SDK-161B22?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU%2BT3BlbkFJPC90aXRsZT48cGF0aCBmaWxsPSJ3aGl0ZSIgZD0iTTIyLjI4MTkgOS44MjExYTUuOTg0NyA1Ljk4NDcgMCAwIDAtLjUxNTctNC45MTA4IDYuMDQ2MiA2LjA0NjIgMCAwIDAtNi41MDk4LTIuOUE2LjA2NTEgNi4wNjUxIDAgMCAwIDQuOTgwNyA0LjE4MThhNS45ODQ3IDUuOTg0NyAwIDAgMC0zLjk5NzcgMi45IDYuMDQ2MiA2LjA0NjIgMCAwIDAgLjc0MjcgNy4wOTY2IDUuOTggNS45OCAwIDAgMCAuNTExIDQuOTEwNyA2LjA1MSA2LjA1MSAwIDAgMCA2LjUxNDYgMi45MDAxQTUuOTg0NyA1Ljk4NDcgMCAwIDAgMTMuMjU5OSAyNGE2LjA1NTcgNi4wNTU3IDAgMCAwIDUuNzcxOC00LjIwNTggNS45ODk0IDUuOTg5NCAwIDAgMCAzLjk5NzctMi45MDAxIDYuMDU1NyA2LjA1NTcgMCAwIDAtLjc0NzUtNy4wNzI5em0tOS4wMjIgMTIuNjA4MWE0LjQ3NTUgNC40NzU1IDAgMCAxLTIuODc2NC0xLjA0MDhsLjE0MTktLjA4MDQgNC43NzgzLTIuNzU4MmEuNzk0OC43OTQ4IDAgMCAwIC4zOTI3LS42ODEzdi02LjczNjlsMi4wMiAxLjE2ODZhLjA3MS4wNzEgMCAwIDEgLjAzOC4wNTJ2NS41ODI2YTQuNTA0IDQuNTA0IDAgMCAxLTQuNDk0NSA0LjQ5NDR6bS05LjY2MDctNC4xMjU0YTQuNDcwOCA0LjQ3MDggMCAwIDEtLjUzNDYtMy4wMTM3bC4xNDIuMDg1MiA0Ljc4MyAyLjc1ODJhLjc3MTIuNzcxMiAwIDAgMCAuNzgwNiAwbDUuODQyOC0zLjM2ODV2Mi4zMzI0YS4wODA0LjA4MDQgMCAwIDEtLjAzMzIuMDYxNUw5Ljc0IDE5Ljk1MDJhNC40OTkyIDQuNDk5MiAwIDAgMS02LjE0MDgtMS42NDY0ek0yLjM0MDggNy44OTU2YTQuNDg1IDQuNDg1IDAgMCAxIDIuMzY1NS0xLjk3MjhWMTEuNmEuNzY2NC43NjY0IDAgMCAwIC4zODc5LjY3NjVsNS44MTQ0IDMuMzU0My0yLjAyMDEgMS4xNjg1YS4wNzU3LjA3NTcgMCAwIDEtLjA3MSAwbC00LjgzMDMtMi43ODY1QTQuNTA0IDQuNTA0IDAgMCAxIDIuMzQwOCA3Ljg3MnptMTYuNTk2MyAzLjg1NThMMTMuMTAzOCA4LjM2NCAxNS4xMTkyIDcuMmEuMDc1Ny4wNzU3IDAgMCAxIC4wNzEgMGw0LjgzMDMgMi43OTEzYTQuNDk0NCA0LjQ5NDQgMCAwIDEtLjY3NjUgOC4xMDQydi01LjY3NzJhLjc5Ljc5IDAgMCAwLS40MDctLjY2N3ptMi4wMTA3LTMuMDIzMWwtLjE0Mi0uMDg1Mi00Ljc3MzUtMi43ODE4YS43NzU5Ljc3NTkgMCAwIDAtLjc4NTQgMEw5LjQwOSA5LjIyOTdWNi44OTc0YS4wNjYyLjA2NjIgMCAwIDEgLjAyODQtLjA2MTVsNC44MzAzLTIuNzg2NmE0LjQ5OTIgNC40OTkyIDAgMCAxIDYuNjgwMiA0LjY2ek04LjMwNjUgMTIuODYzbC0yLjAyLTEuMTYzOGEuMDgwNC4wODA0IDAgMCAxLS4wMzgtLjA1NjdWNi4wNzQyYTQuNDk5MiA0LjQ5OTIgMCAwIDEgNy4zNzU3LTMuNDUzN2wtLjE0Mi4wODA1TDguNzA0IDUuNDU5YS43OTQ4Ljc5NDggMCAwIDAtLjM5MjcuNjgxM3ptMS4wOTc2LTIuMzY1NGwyLjYwMi0xLjQ5OTggMi42MDY5IDEuNDk5OHYyLjk5OTRsLTIuNTk3NCAxLjQ5OTctMi42MDY3LTEuNDk5N1oiLz48L3N2Zz4%3D&logoColor=white)
![Anthropic API / SDK](https://img.shields.io/badge/Anthropic%20API%20%2F%20SDK-161B22?style=flat-square&logo=anthropic&logoColor=white)
![Google Gemini API](https://img.shields.io/badge/Google%20Gemini%20API-161B22?style=flat-square&logo=googlegemini&logoColor=white)
![Whisper](https://img.shields.io/badge/Whisper-161B22?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU%2BT3BlbkFJPC90aXRsZT48cGF0aCBmaWxsPSJ3aGl0ZSIgZD0iTTIyLjI4MTkgOS44MjExYTUuOTg0NyA1Ljk4NDcgMCAwIDAtLjUxNTctNC45MTA4IDYuMDQ2MiA2LjA0NjIgMCAwIDAtNi41MDk4LTIuOUE2LjA2NTEgNi4wNjUxIDAgMCAwIDQuOTgwNyA0LjE4MThhNS45ODQ3IDUuOTg0NyAwIDAgMC0zLjk5NzcgMi45IDYuMDQ2MiA2LjA0NjIgMCAwIDAgLjc0MjcgNy4wOTY2IDUuOTggNS45OCAwIDAgMCAuNTExIDQuOTEwNyA2LjA1MSA2LjA1MSAwIDAgMCA2LjUxNDYgMi45MDAxQTUuOTg0NyA1Ljk4NDcgMCAwIDAgMTMuMjU5OSAyNGE2LjA1NTcgNi4wNTU3IDAgMCAwIDUuNzcxOC00LjIwNTggNS45ODk0IDUuOTg5NCAwIDAgMCAzLjk5NzctMi45MDAxIDYuMDU1NyA2LjA1NTcgMCAwIDAtLjc0NzUtNy4wNzI5em0tOS4wMjIgMTIuNjA4MWE0LjQ3NTUgNC40NzU1IDAgMCAxLTIuODc2NC0xLjA0MDhsLjE0MTktLjA4MDQgNC43NzgzLTIuNzU4MmEuNzk0OC43OTQ4IDAgMCAwIC4zOTI3LS42ODEzdi02LjczNjlsMi4wMiAxLjE2ODZhLjA3MS4wNzEgMCAwIDEgLjAzOC4wNTJ2NS41ODI2YTQuNTA0IDQuNTA0IDAgMCAxLTQuNDk0NSA0LjQ5NDR6bS05LjY2MDctNC4xMjU0YTQuNDcwOCA0LjQ3MDggMCAwIDEtLjUzNDYtMy4wMTM3bC4xNDIuMDg1MiA0Ljc4MyAyLjc1ODJhLjc3MTIuNzcxMiAwIDAgMCAuNzgwNiAwbDUuODQyOC0zLjM2ODV2Mi4zMzI0YS4wODA0LjA4MDQgMCAwIDEtLjAzMzIuMDYxNUw5Ljc0IDE5Ljk1MDJhNC40OTkyIDQuNDk5MiAwIDAgMS02LjE0MDgtMS42NDY0ek0yLjM0MDggNy44OTU2YTQuNDg1IDQuNDg1IDAgMCAxIDIuMzY1NS0xLjk3MjhWMTEuNmEuNzY2NC43NjY0IDAgMCAwIC4zODc5LjY3NjVsNS44MTQ0IDMuMzU0My0yLjAyMDEgMS4xNjg1YS4wNzU3LjA3NTcgMCAwIDEtLjA3MSAwbC00LjgzMDMtMi43ODY1QTQuNTA0IDQuNTA0IDAgMCAxIDIuMzQwOCA3Ljg3MnptMTYuNTk2MyAzLjg1NThMMTMuMTAzOCA4LjM2NCAxNS4xMTkyIDcuMmEuMDc1Ny4wNzU3IDAgMCAxIC4wNzEgMGw0LjgzMDMgMi43OTEzYTQuNDk0NCA0LjQ5NDQgMCAwIDEtLjY3NjUgOC4xMDQydi01LjY3NzJhLjc5Ljc5IDAgMCAwLS40MDctLjY2N3ptMi4wMTA3LTMuMDIzMWwtLjE0Mi0uMDg1Mi00Ljc3MzUtMi43ODE4YS43NzU5Ljc3NTkgMCAwIDAtLjc4NTQgMEw5LjQwOSA5LjIyOTdWNi44OTc0YS4wNjYyLjA2NjIgMCAwIDEgLjAyODQtLjA2MTVsNC44MzAzLTIuNzg2NmE0LjQ5OTIgNC40OTkyIDAgMCAxIDYuNjgwMiA0LjY2ek04LjMwNjUgMTIuODYzbC0yLjAyLTEuMTYzOGEuMDgwNC4wODA0IDAgMCAxLS4wMzgtLjA1NjdWNi4wNzQyYTQuNDk5MiA0LjQ5OTIgMCAwIDEgNy4zNzU3LTMuNDUzN2wtLjE0Mi4wODA1TDguNzA0IDUuNDU5YS43OTQ4Ljc5NDggMCAwIDAtLjM5MjcuNjgxM3ptMS4wOTc2LTIuMzY1NGwyLjYwMi0xLjQ5OTggMi42MDY5IDEuNDk5OHYyLjk5OTRsLTIuNTk3NCAxLjQ5OTctMi42MDY3LTEuNDk5N1oiLz48L3N2Zz4%3D&logoColor=white)

### Validation & evaluation

![Pydantic](https://img.shields.io/badge/Pydantic-161B22?style=flat-square&logo=pydantic&logoColor=white)
![Zod](https://img.shields.io/badge/Zod-161B22?style=flat-square&logo=zod&logoColor=white)
![pytest](https://img.shields.io/badge/pytest-161B22?style=flat-square&logo=pytest&logoColor=white)
![node:test](https://img.shields.io/badge/node%3Atest-161B22?style=flat-square&logo=nodedotjs&logoColor=white)
![jsdom](https://img.shields.io/badge/jsdom-161B22?style=flat-square)

### Frontend & design

![React](https://img.shields.io/badge/React-161B22?style=flat-square&logo=react&logoColor=white)
![Next.js](https://img.shields.io/badge/Next.js-161B22?style=flat-square&logo=nextdotjs&logoColor=white)
![Preact Signals](https://img.shields.io/badge/Preact%20Signals-161B22?style=flat-square&logo=preact&logoColor=white)
![HTML5](https://img.shields.io/badge/HTML5-161B22?style=flat-square&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-161B22?style=flat-square&logo=css&logoColor=white)
![Bootstrap](https://img.shields.io/badge/Bootstrap-161B22?style=flat-square&logo=bootstrap&logoColor=white)
![Redux](https://img.shields.io/badge/Redux-161B22?style=flat-square&logo=redux&logoColor=white)
![Vite](https://img.shields.io/badge/Vite-161B22?style=flat-square&logo=vite&logoColor=white)
![Webpack](https://img.shields.io/badge/Webpack-161B22?style=flat-square&logo=webpack&logoColor=white)
![Storybook](https://img.shields.io/badge/Storybook-161B22?style=flat-square&logo=storybook&logoColor=white)
![Figma](https://img.shields.io/badge/Figma-161B22?style=flat-square&logo=figma&logoColor=white)

### Backend & integrations

![FastAPI](https://img.shields.io/badge/FastAPI-161B22?style=flat-square&logo=fastapi&logoColor=white)
![Django](https://img.shields.io/badge/Django-161B22?style=flat-square&logo=django&logoColor=white)
![Django REST Framework](https://img.shields.io/badge/Django%20REST%20Framework-161B22?style=flat-square&logo=django&logoColor=white)
![Node.js](https://img.shields.io/badge/Node.js-161B22?style=flat-square&logo=nodedotjs&logoColor=white)
![Express.js](https://img.shields.io/badge/Express.js-161B22?style=flat-square&logo=express&logoColor=white)
![aiohttp](https://img.shields.io/badge/aiohttp-161B22?style=flat-square&logo=aiohttp&logoColor=white)
![Celery](https://img.shields.io/badge/Celery-161B22?style=flat-square&logo=celery&logoColor=white)
![RabbitMQ](https://img.shields.io/badge/RabbitMQ-161B22?style=flat-square&logo=rabbitmq&logoColor=white)
![Telegram Bot API](https://img.shields.io/badge/Telegram%20Bot%20API-161B22?style=flat-square&logo=telegram&logoColor=white)
![aiogram](https://img.shields.io/badge/aiogram-161B22?style=flat-square)

### Data, analytics & document loading

![PostgreSQL](https://img.shields.io/badge/PostgreSQL-161B22?style=flat-square&logo=postgresql&logoColor=white)
![SQLite](https://img.shields.io/badge/SQLite-161B22?style=flat-square&logo=sqlite&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-161B22?style=flat-square&logo=mongodb&logoColor=white)
![Redis](https://img.shields.io/badge/Redis-161B22?style=flat-square&logo=redis&logoColor=white)
![Supabase](https://img.shields.io/badge/Supabase-161B22?style=flat-square&logo=supabase&logoColor=white)
![Convex](https://img.shields.io/badge/Convex-161B22?style=flat-square&logo=convex&logoColor=white)
![Streamlit](https://img.shields.io/badge/Streamlit-161B22?style=flat-square&logo=streamlit&logoColor=white)
![Beautiful Soup](https://img.shields.io/badge/Beautiful%20Soup-161B22?style=flat-square)

### Delivery & development tools

![Docker](https://img.shields.io/badge/Docker-161B22?style=flat-square&logo=docker&logoColor=white)
![GitHub Actions](https://img.shields.io/badge/GitHub%20Actions-161B22?style=flat-square&logo=githubactions&logoColor=white)
![Sentry](https://img.shields.io/badge/Sentry-161B22?style=flat-square&logo=sentry&logoColor=white)
![Railway](https://img.shields.io/badge/Railway-161B22?style=flat-square&logo=railway&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-161B22?style=flat-square&logo=linux&logoColor=white)
![NGINX](https://img.shields.io/badge/NGINX-161B22?style=flat-square&logo=nginx&logoColor=white)
![Gunicorn](https://img.shields.io/badge/Gunicorn-161B22?style=flat-square&logo=gunicorn&logoColor=white)
![Git](https://img.shields.io/badge/Git-161B22?style=flat-square&logo=git&logoColor=white)
![GitHub](https://img.shields.io/badge/GitHub-161B22?style=flat-square&logo=github&logoColor=white)
![npm](https://img.shields.io/badge/npm-161B22?style=flat-square&logo=npm&logoColor=white)
![Poetry](https://img.shields.io/badge/Poetry-161B22?style=flat-square&logo=poetry&logoColor=white)

### AI tools I use (not projects I authored)

![Claude Code](https://img.shields.io/badge/Claude%20Code-161B22?style=flat-square&logo=claudecode&logoColor=white)
![Codex CLI](https://img.shields.io/badge/Codex%20CLI-161B22?style=flat-square&logo=data%3Aimage%2Fsvg%2Bxml%3Bbase64%2CPHN2ZyByb2xlPSJpbWciIHZpZXdCb3g9IjAgMCAyNCAyNCIgeG1sbnM9Imh0dHA6Ly93d3cudzMub3JnLzIwMDAvc3ZnIj48dGl0bGU%2BT3BlbkFJPC90aXRsZT48cGF0aCBmaWxsPSJ3aGl0ZSIgZD0iTTIyLjI4MTkgOS44MjExYTUuOTg0NyA1Ljk4NDcgMCAwIDAtLjUxNTctNC45MTA4IDYuMDQ2MiA2LjA0NjIgMCAwIDAtNi41MDk4LTIuOUE2LjA2NTEgNi4wNjUxIDAgMCAwIDQuOTgwNyA0LjE4MThhNS45ODQ3IDUuOTg0NyAwIDAgMC0zLjk5NzcgMi45IDYuMDQ2MiA2LjA0NjIgMCAwIDAgLjc0MjcgNy4wOTY2IDUuOTggNS45OCAwIDAgMCAuNTExIDQuOTEwNyA2LjA1MSA2LjA1MSAwIDAgMCA2LjUxNDYgMi45MDAxQTUuOTg0NyA1Ljk4NDcgMCAwIDAgMTMuMjU5OSAyNGE2LjA1NTcgNi4wNTU3IDAgMCAwIDUuNzcxOC00LjIwNTggNS45ODk0IDUuOTg5NCAwIDAgMCAzLjk5NzctMi45MDAxIDYuMDU1NyA2LjA1NTcgMCAwIDAtLjc0NzUtNy4wNzI5em0tOS4wMjIgMTIuNjA4MWE0LjQ3NTUgNC40NzU1IDAgMCAxLTIuODc2NC0xLjA0MDhsLjE0MTktLjA4MDQgNC43NzgzLTIuNzU4MmEuNzk0OC43OTQ4IDAgMCAwIC4zOTI3LS42ODEzdi02LjczNjlsMi4wMiAxLjE2ODZhLjA3MS4wNzEgMCAwIDEgLjAzOC4wNTJ2NS41ODI2YTQuNTA0IDQuNTA0IDAgMCAxLTQuNDk0NSA0LjQ5NDR6bS05LjY2MDctNC4xMjU0YTQuNDcwOCA0LjQ3MDggMCAwIDEtLjUzNDYtMy4wMTM3bC4xNDIuMDg1MiA0Ljc4MyAyLjc1ODJhLjc3MTIuNzcxMiAwIDAgMCAuNzgwNiAwbDUuODQyOC0zLjM2ODV2Mi4zMzI0YS4wODA0LjA4MDQgMCAwIDEtLjAzMzIuMDYxNUw5Ljc0IDE5Ljk1MDJhNC40OTkyIDQuNDk5MiAwIDAgMS02LjE0MDgtMS42NDY0ek0yLjM0MDggNy44OTU2YTQuNDg1IDQuNDg1IDAgMCAxIDIuMzY1NS0xLjk3MjhWMTEuNmEuNzY2NC43NjY0IDAgMCAwIC4zODc5LjY3NjVsNS44MTQ0IDMuMzU0My0yLjAyMDEgMS4xNjg1YS4wNzU3LjA3NTcgMCAwIDEtLjA3MSAwbC00LjgzMDMtMi43ODY1QTQuNTA0IDQuNTA0IDAgMCAxIDIuMzQwOCA3Ljg3MnptMTYuNTk2MyAzLjg1NThMMTMuMTAzOCA4LjM2NCAxNS4xMTkyIDcuMmEuMDc1Ny4wNzU3IDAgMCAxIC4wNzEgMGw0LjgzMDMgMi43OTEzYTQuNDk0NCA0LjQ5NDQgMCAwIDEtLjY3NjUgOC4xMDQydi01LjY3NzJhLjc5Ljc5IDAgMCAwLS40MDctLjY2N3ptMi4wMTA3LTMuMDIzMWwtLjE0Mi0uMDg1Mi00Ljc3MzUtMi43ODE4YS43NzU5Ljc3NTkgMCAwIDAtLjc4NTQgMEw5LjQwOSA5LjIyOTdWNi44OTc0YS4wNjYyLjA2NjIgMCAwIDEgLjAyODQtLjA2MTVsNC44MzAzLTIuNzg2NmE0LjQ5OTIgNC40OTkyIDAgMCAxIDYuNjgwMiA0LjY2ek04LjMwNjUgMTIuODYzbC0yLjAyLTEuMTYzOGEuMDgwNC4wODA0IDAgMCAxLS4wMzgtLjA1NjdWNi4wNzQyYTQuNDk5MiA0LjQ5OTIgMCAwIDEgNy4zNzU3LTMuNDUzN2wtLjE0Mi4wODA1TDguNzA0IDUuNDU5YS43OTQ4Ljc5NDggMCAwIDAtLjM5MjcuNjgxM3ptMS4wOTc2LTIuMzY1NGwyLjYwMi0xLjQ5OTggMi42MDY5IDEuNDk5OHYyLjk5OTRsLTIuNTk3NCAxLjQ5OTctMi42MDY3LTEuNDk5N1oiLz48L3N2Zz4%3D&logoColor=white)
![Context7](https://img.shields.io/badge/Context7-161B22?style=flat-square)
![OpenClaw](https://img.shields.io/badge/OpenClaw-161B22?style=flat-square)

## Education

- **Yandex.Practicum — Web Developer**, October 2021–July 2022. [Diploma](https://user-images.githubusercontent.com/19635244/201074828-25c49bec-ee76-41dc-9c4a-2805411d9f08.png)
- **Yandex.Practicum — Back-End Python Developer**, 2020–2021. [Diploma](https://user-images.githubusercontent.com/19635244/201067854-db8f5873-de87-4954-be92-2dd37259fc49.png)
