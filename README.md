
<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,100:1f6feb&height=220&section=header&text=Ryan&fontSize=48&fontColor=f0f6fc&fontAlignY=38&desc=AI%20Orchestration%20and%20Automation%20Engineer&descAlignY=58&descSize=18&animation=fadeIn" width="100%"/>


<br/>

<img
  src="https://readme-typing-svg.demolab.com/?font=Fira+Code&amp;weight=500&amp;size=18&amp;duration=3000&amp;pause=1000&amp;color=58A6FF&amp;background=00000000&amp;center=true&amp;vCenter=true&amp;width=720&amp;lines=Architecting+scalable+AI+systems;Tracing+production+bugs+to+their+root+cause;Building+custom+automation+engines;Correctness+%E2%86%92+Performance+%E2%86%92+Clarity"
  alt="Typing SVG"
/>

<br/>

[![Email](https://img.shields.io/badge/EMAIL-brian.sbg12%40gmail.com-1F6FEB?style=for-the-badge&logo=gmail&logoColor=white)](mailto:brian.sbg12@gmail.com)
[![GitHub](https://img.shields.io/badge/GITHUB-Ryanakml-161B22?style=for-the-badge&logo=github&logoColor=white)](https://github.com/Ryanakml)
![Availability](https://img.shields.io/badge/STATUS-AVAILABLE-238636?style=for-the-badge)

</div>

<br/>

I build end-to-end AI and automation systems with a strict focus on reliability: define the architecture, trace failures to their source, and validate the real execution path before shipping.

<table>
<tr>
<td width="25%" valign="top"><sub>PRIMARY FOCUS</sub><br/><strong>AI orchestration<br/>&amp; automation</strong></td>
<td width="25%" valign="top"><sub>BUILD SCOPE</sub><br/><strong>Application to<br/>infrastructure</strong></td>
<td width="25%" valign="top"><sub>ENGINEERING STYLE</sub><br/><strong>Root-cause<br/>driven</strong></td>
<td width="25%" valign="top"><sub>STATUS</sub><br/><strong>Open-source<br/>&amp; freelance</strong></td>
</tr>
</table>

<br/>

## Open Source Engineering

Public work across agent and orchestration frameworks, centered on runtime behavior, tool execution, integration correctness, and production-facing failure modes.

<table>
<tr>
<td width="50%" valign="top">
<h3>LangChain</h3>
<p><strong>Runtime &amp; validation</strong></p>
<p>Investigations into tool runtime argument injection and model-side tool argument validation.</p>
<p><a href="https://github.com/langchain-ai/langchain/pull/34561">PR #34561</a> · <a href="https://github.com/langchain-ai/langchain/pull/36722">PR #36722</a></p>
<p><code>Runtime</code> <code>Tool execution</code> <code>Validation</code></p>
</td>
<td width="50%" valign="top">
<h3>OpenHands</h3>
<p><strong>Agent product reliability</strong></p>
<p>Merged fixes for conversation routing stability, loading states, and modal interaction behavior.</p>
<p><a href="https://github.com/OpenHands/OpenHands/pull/12223">PR #12223</a> · <a href="https://github.com/OpenHands/OpenHands/pull/12219">PR #12219</a></p>
<p><code>AI agents</code> <code>Routing</code> <code>UI state</code></p>
</td>
</tr>
<tr>
<td colspan="2" valign="top">
<h3>Mastra</h3>
<p><strong>Orchestration &amp; approval semantics</strong></p>
<p>Merged core fix enabling function-based approval requirements in tool builders.</p>
<p><a href="https://github.com/mastra-ai/mastra/pull/15346">PR #15346</a></p>
<p><code>Agents</code> <code>Tool approval</code> <code>Runtime behavior</code></p>
</td>
</tr>
</table>

<p align="center"><code>reproduce → isolate → trace → fix → validate</code></p>

<br/>

## Selected Systems

<table>
<tr>
<td width="50%" valign="top">
<h3><a href="https://www.nylo.me/">Streak ↗</a></h3>
<p><sub>AI / HABIT TRACKING</sub></p>
<p>A brutalist AI habit tracker with real-time coaching, intent parsing, proactive reminders, weekly reviews, authentication, and free/pro enforcement.</p>
<p><code>Next.js</code> <code>React</code> <code>Convex</code> <code>Clerk</code> <code>Groq</code> <code>Tailwind</code></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://chattiphy.nextstackhq.app/">Chattiphy ↗</a></h3>
<p><sub>AI / VOICE &amp; TEXT SUPPORT</sub></p>
<p>A real-time voice and text support system designed around low-latency AI interactions and shared conversational state across channels.</p>
<p><code>Next.js</code> <code>Groq</code> <code>Convex</code> <code>Vapi</code></p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<h3><a href="https://wabrix-ai.vercel.app/">Wabrix ↗</a></h3>
<p><sub>AI / WHATSAPP AUTOMATION</sub></p>
<p>A WhatsApp automation platform with webhook ingestion, asynchronous processing, AI routing, escalation workflows, observability, and multi-tenant infrastructure.</p>
<p><code>Next.js</code> <code>Express</code> <code>BullMQ</code> <code>Redis</code> <code>Supabase</code> <code>LangChain</code> <code>OpenTelemetry</code></p>
</td>
<td width="50%" valign="top">
<h3><a href="https://voxify-peach.vercel.app/">Voxify ↗</a></h3>
<p><sub>AI / VOICE SYNTHESIS</sub></p>
<p>A multi-voice TTS platform with real-time audio generation, voice management, API infrastructure, and a dashboard for teams.</p>
<p><code>Next.js</code> <code>Prisma</code> <code>Python</code> <code>tRPC</code></p>
</td>
</tr>
<tr>
<td colspan="2" valign="top">
<h3><a href="https://clipperai.tech/">ClipperAI ↗</a></h3>
<p><sub>AI / VIDEO AUTOMATION</sub></p>
<p>An automated video clipping engine with multi-stage processing, GPU-accelerated inference, long-running background workflows, and AI-assisted content understanding.</p>
<p><code>Gemini</code> <code>FFmpeg</code> <code>Modal GPU</code> <code>Inngest</code> <code>Next.js</code> <code>Prisma</code></p>
</td>
</tr>
</table>

<br/>

## Engineering Workflow

```text
$ diagnose    reproduce → isolate → trace the failure
$ architect   boundaries → data flow → failure modes
$ build       application → AI → workers → infrastructure
$ validate    tests → logs → runtime state → recovery
$ ship        deploy → observe → iterate
```

Architecture comes before implementation. Validation follows the same path the system will run in production—not a simplified substitute.

<br/>

## Technical Toolkit

<div align="center">

<sub>LANGUAGES</sub>

![TypeScript](https://img.shields.io/badge/TypeScript-1E293B?style=flat-square&logo=typescript&logoColor=3178C6)
![JavaScript](https://img.shields.io/badge/JavaScript-1E293B?style=flat-square&logo=javascript&logoColor=F7DF1E)
![Python](https://img.shields.io/badge/Python-1E293B?style=flat-square&logo=python&logoColor=4B8BBE)

<br/>

<sub>APPLICATION &amp; DATA</sub>

![React](https://img.shields.io/badge/React-1E293B?style=flat-square&logo=react&logoColor=61DAFB)
![Next.js](https://img.shields.io/badge/Next.js-1E293B?style=flat-square&logo=nextdotjs&logoColor=FFFFFF)
![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-1E293B?style=flat-square&logo=tailwindcss&logoColor=06B6D4)
![Node.js](https://img.shields.io/badge/Node.js-1E293B?style=flat-square&logo=nodedotjs&logoColor=5FA04E)
![Express](https://img.shields.io/badge/Express-1E293B?style=flat-square&logo=express&logoColor=FFFFFF)
![Hono](https://img.shields.io/badge/Hono-1E293B?style=flat-square&logo=hono&logoColor=E36002)
![Convex](https://img.shields.io/badge/Convex-1E293B?style=flat-square&logo=convex&logoColor=F3B01C)
![Prisma](https://img.shields.io/badge/Prisma-1E293B?style=flat-square&logo=prisma&logoColor=8B9CF7)
![Supabase](https://img.shields.io/badge/Supabase-1E293B?style=flat-square&logo=supabase&logoColor=3ECF8E)

<br/>

<sub>AI &amp; ORCHESTRATION</sub>

![LangChain](https://img.shields.io/badge/LangChain-1E293B?style=flat-square&logo=langchain&logoColor=58A6FF)
![OpenAI](https://img.shields.io/badge/OpenAI-1E293B?style=flat-square&logo=openai&logoColor=FFFFFF)
![Gemini](https://img.shields.io/badge/Gemini-1E293B?style=flat-square&logo=googlegemini&logoColor=8B9CF7)
![Groq](https://img.shields.io/badge/Groq-1E293B?style=flat-square&logo=groq&logoColor=F55036)
![RAG](https://img.shields.io/badge/RAG_Pipelines-1E293B?style=flat-square&logoColor=58A6FF)
![Agents](https://img.shields.io/badge/Agent_Orchestration-1E293B?style=flat-square&logoColor=8B9CF7)

<br/>

<sub>ASYNC, INFRASTRUCTURE &amp; DELIVERY</sub>

![Redis](https://img.shields.io/badge/Redis-1E293B?style=flat-square&logo=redis&logoColor=FF4438)
![BullMQ](https://img.shields.io/badge/BullMQ-1E293B?style=flat-square&logoColor=F43F5E)
![Inngest](https://img.shields.io/badge/Inngest-1E293B?style=flat-square&logo=inngest&logoColor=8B9CF7)
![Docker](https://img.shields.io/badge/Docker-1E293B?style=flat-square&logo=docker&logoColor=2496ED)
![Modal](https://img.shields.io/badge/Modal_GPU-1E293B?style=flat-square&logoColor=58A6FF)
![AWS](https://img.shields.io/badge/AWS-1E293B?style=flat-square&logo=amazonwebservices&logoColor=FF9900)
![GCP](https://img.shields.io/badge/GCP-1E293B?style=flat-square&logo=googlecloud&logoColor=4285F4)
![OpenTelemetry](https://img.shields.io/badge/OpenTelemetry-1E293B?style=flat-square&logo=opentelemetry&logoColor=8B9CF7)
![GitHub Actions](https://img.shields.io/badge/GitHub_Actions-1E293B?style=flat-square&logo=githubactions&logoColor=58A6FF)
![CI/CD](https://img.shields.io/badge/CI%2FCD-1E293B?style=flat-square&logoColor=3FB950)

</div>

<br/>

## Engineering Focus

| AI systems          | Backend systems   | Reliability          | Infrastructure  |
| :------------------ | :---------------- | :------------------- | :-------------- |
| Agent orchestration | Async processing  | Root-cause debugging | Containers      |
| RAG pipelines       | Queues & workers  | Observability        | Cloud delivery  |
| LLM routing         | Webhooks & APIs   | Failure recovery     | CI/CD           |
| Tool execution      | State & data flow | Runtime tracing      | Background jobs |

<br/>

## Engineering Metrics

<picture>
  <img src="./github-metrics.png" width="100%" alt="Ryan's engineering metrics: contribution calendar, languages, notable open-source contributions, and recent activity"/>
</picture>

<sub>Generated daily with <a href="https://github.com/lowlighter/metrics">lowlighter/metrics</a>.</sub>

<br/>

## GitHub Stats

<p align="center">
  <img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api?username=Ryanakml&amp;show_icons=true&amp;include_all_commits=true&amp;count_private=true&amp;title_color=58A6FF&amp;text_color=C9D1D9&amp;icon_color=58A6FF&amp;bg_color=0D1117&amp;border_color=30363D&amp;rank_icon=github" alt="GitHub Stats"/>
  <img height="180" src="https://github-readme-stats-eight-theta.vercel.app/api/top-langs/?username=Ryanakml&amp;layout=compact&amp;hide=jupyter%20notebook&amp;langs_count=10&amp;exclude_repo=Adaptive-Sobel-VS-Sobel,Reinforcement-Learning-Concept-and-Implementation&amp;title_color=58A6FF&amp;text_color=C9D1D9&amp;bg_color=0D1117&amp;border_color=30363D" alt="Top Languages"/>
</p>

<p align="center">
  <img height="180" src="https://github-readme-streak-stats.herokuapp.com/?user=Ryanakml&amp;theme=github-dark-blue&amp;hide_border=false&amp;border=30363D&amp;background=0D1117&amp;ring=58A6FF&amp;fire=3FB950&amp;currStreakLabel=58A6FF" alt="GitHub Streak"/>
</p>

<br/>
<br/>

---

<div align="center">

**Let's talk.**<br/>
Open to new opportunities, OSS collaboration, and high-impact freelance projects.<br/>
If you're working on AI infrastructure, automation, or a hard production problem, reach out.

[![Gmail](https://img.shields.io/badge/-brian.sbg12%40gmail.com-D14836?style=flat-square&logo=gmail&logoColor=white)](mailto:brian.sbg12@gmail.com)
[![GitHub](https://img.shields.io/badge/-@Ryanakml-181717?style=flat-square&logo=github&logoColor=white)](https://github.com/Ryanakml)

<!--
[Upwork](https://www.upwork.com/freelancers/~0190d89421d495254e)
[LinkedIn](https://www.linkedin.com/in/ryan-akmal-943a2a1a6/)
-->

<br/>

<img src="https://capsule-render.vercel.app/api?type=waving&amp;color=0:1F6FEB,100:0D1117&amp;height=100&amp;section=footer" width="100%" alt="Profile footer"/>

<img
  src="https://waveify.up.railway.app/api/wave/gradient?color=%2358a6ff&amplitude=12&frequency=1"
  width="100%"
  alt=""
/>

<sub>© 2026 Ryan. All rights reserved.</sub>



</div>
