<div align="center">

<img src="./profile-banner.jpg" alt="Botta Rohit Yadav — Agentic AI" width="100%" />

# Botta Rohit Yadav

**Agentic AI Engineer** · MCP · Multi-agent systems · RAG · Backend

<img src="https://readme-typing-svg.demolab.com?font=IBM+Plex+Mono&weight=500&size=18&duration=3200&pause=800&color=C8CCD4&center=true&vCenter=true&width=780&lines=LLMs+should+call+tools,+not+guess;Triage+%E2%86%92+specialist+%E2%86%92+read-only+tools;Writes+are+refused.+Guardrails+trip+first;If+the+world+is+a+lineage,+use+a+graph" alt="typing" />

[![DevOpsDesk](https://img.shields.io/badge/DevOpsDesk-multi--agent_MCP_desk-0c0e12?style=for-the-badge&labelColor=c8ccd4&color=0c0e12)](https://github.com/rohit-dev45/devops-desk)
[![Tutor](https://img.shields.io/badge/Tutor_Agent-LangChain_+_Gemini_+_MCP-0c0e12?style=for-the-badge&labelColor=7d9a7a)](https://github.com/rohit-dev45/programming-tutor-agent)
[![Parampara](https://img.shields.io/badge/Parampara-Neo4j_lineage_graph-0c0e12?style=for-the-badge&labelColor=c4a574)](https://parampara-ashy.vercel.app/)

</div>

---

## Operating principle

A chatbot answers. An **agent** routes, calls tools, and refuses work it should not do.

I design that loop:

`intent → guardrail → triage / planner → specialist agent → tools → grounded reply`

Tools read source-of-truth data. Writes (rollback, IAM grant, invented IDs) stay blocked unless a human owns them.

```ts
const agent = {
  role: "Agentic AI + backend engineer",
  location: "Visakhapatnam, India · remote",
  loop: [
    "input guardrail (jailbreak / off-topic)",
    "triage or planner",
    "handoff to a specialist",
    "function / MCP tools over real data",
    "refuse irreversible writes"
  ],
  stack: {
    agents: ["LangChain", "LangGraph", "OpenAI Agents SDK", "MCP", "Gemini", "NVIDIA NIM"],
    backend: ["Python", "C# / .NET 8", "ASP.NET Core", "EF Core", "JWT"],
    data: ["SQL Server", "PostgreSQL", "Neo4j", "Supabase"]
  }
};
```

---

## Systems

<table>
<tr>
<td width="50%" valign="top">

### DevOpsDesk
**Multi-agent platform support**

Triage agent hands off to Incidents, CI/CD, or Access.
Function tools over a CMDB.
Rollback and admin-grant tools do not exist.
Keyword + policy guardrail trips on homework, key-dump, and jailbreaks.
20-case routing sheet in-repo.

[Repo](https://github.com/rohit-dev45/devops-desk)

`Agents SDK` `MCP` `guardrails` `handoffs`

</td>
<td width="50%" valign="top">

### Programming Tutor Agent
**Tool-using tutor, not a guesser**

Concepts get an explanation.
Prime / palindrome / Fibonacci / GCD / leap-year go through **MCP tools**, then the model explains the result.
13 tools on FastMCP. Same server works in CLI, MCP Inspector, and Codex.

[Repo](https://github.com/rohit-dev45/programming-tutor-agent) · [Demo](https://drive.google.com/file/d/1X8HZTsvx9oTEdc2P6xVx4szGgzhltDgM/view?usp=sharing)

`LangChain` `LangGraph` `Gemini` `FastMCP`

</td>
</tr>
<tr>
<td width="50%" valign="top">

### Parampara
**Graph memory for lineages**

Guru · shishya · gharana · raga as a graph.
Multi-hop teaching chains and shortest path.
SQL can list who taught whom. It cannot walk a bloodline.

[Live](https://parampara-ashy.vercel.app/) · [Source](https://github.com/rohit-dev45/parampara)

`TypeScript` `Neo4j` `openCypher`

</td>
<td width="50%" valign="top">

### Backend spine
**.NET / Java services the agents sit on**

Employee Management: .NET 8, EF Core, JWT, RBAC.
Incident triage agent: classify + route tickets.
Banking API: Spring Boot, layered REST.

Agents need APIs and a data model. I build those too.

`.NET` `EF Core` `JWT` `Spring Boot` `SQL`

</td>
</tr>
</table>

---

## What I actually implement

| Layer | What I ship |
| --- | --- |
| Guardrails | Off-topic, injection, secret-dump tripwires before the model spends a token |
| Routing | Handoffs to named specialists instead of one mega-prompt |
| Tools | MCP / function tools with stable schemas over CMDB, checks, graphs |
| Policy | Read-only by default. No silent writes |
| Grounding | IDs and facts come from tools or a graph, not from the LLM |
| Eval | Routing sheets and demo traces before I call it done |

---

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=py,cs,dotnet,ts,java,js,react,spring,postgres,mysql,aws,docker,git,linux,vscode&perline=8" alt="stack" />
</p>

<p align="center">
  <img src="https://img.shields.io/badge/MCP-111111?style=for-the-badge" />
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" />
  <img src="https://img.shields.io/badge/LangGraph-0B3D2E?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Gemini-8E75B2?style=for-the-badge&logo=googlegemini&logoColor=white" />
  <img src="https://img.shields.io/badge/NVIDIA_NIM-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
  <img src="https://img.shields.io/badge/RAG-222222?style=for-the-badge" />
  <img src="https://img.shields.io/badge/Neo4j-008CC1?style=for-the-badge&logo=neo4j&logoColor=white" />
  <img src="https://img.shields.io/badge/.NET_8-512BD4?style=for-the-badge&logo=dotnet&logoColor=white" />
</p>

---

## Connect

<p align="center">
  <a href="https://www.linkedin.com/in/botta-rohit-yadav/"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="mailto:rohit.botta5@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" /></a>
  <a href="https://rohityadavportfolio.lovable.app/"><img src="https://img.shields.io/badge/Portfolio-111111?style=for-the-badge" /></a>
  <a href="https://leetcode.com/rohit-yadav"><img src="https://img.shields.io/badge/LeetCode-FFA116?style=for-the-badge&logo=leetcode&logoColor=black" /></a>
</p>

---

## Analytics

<div align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=rohit-dev45&theme=tokyo-night&hide_border=true&area=true" width="100%" alt="activity" />
</div>

<br/>

<div align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=rohit-dev45&show_icons=true&theme=tokyonight&hide_border=true&count_private=true&include_all_commits=true" alt="stats" />
  <img height="165" src="https://github-readme-stats.vercel.app/api/top-langs/?username=rohit-dev45&layout=compact&theme=tokyonight&hide_border=true&langs_count=6" alt="langs" />
</div>

<br/>

<div align="center">
  <img src="https://streak-stats.demolab.com?user=rohit-dev45&theme=tokyonight&hide_border=true" alt="streak" />
</div>

<div align="center">
  <img src="https://github-profile-trophy.vercel.app/?username=rohit-dev45&theme=tokyonight&no-frame=true&column=7&margin-w=12" alt="trophies" />
</div>

---

<div align="center">

Open to **remote Agentic AI / LLM platform / backend** roles.

[devops-desk](https://github.com/rohit-dev45/devops-desk) · [programming-tutor-agent](https://github.com/rohit-dev45/programming-tutor-agent) · [parampara](https://parampara-ashy.vercel.app/)

</div>
