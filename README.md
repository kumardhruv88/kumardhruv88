<!-- ────────────────────────────────────────────────────────────────────────
     This README renders as a live terminal session.
     Every section is a shell command — GitHub renders its stdout.
     Palette: #0D1117 (ground) · #00FF9C (phosphor) · #8B949E (dim)
──────────────────────────────────────────────────────────────────────── -->

<p align="center">
  <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&duration=2400&pause=1000&color=00FF9C&center=true&vCenter=true&width=700&height=60&lines=visitor%40github%3A~%24+ssh+dhruv%40nsut.edu;access+granted.+initializing+profile...;transformers+%C2%B7+RAG+%C2%B7+agentic+AI;fastapi+%C2%B7+docker+%C2%B7+production+scale" alt="terminal typing header" />
</p>

```text
Last login: always, from everywhere

██████╗ ██╗  ██╗██████╗ ██╗   ██╗██╗   ██╗    ██╗  ██╗██╗   ██╗███╗   ███╗ █████╗ ██████╗
██╔══██╗██║  ██║██╔══██╗██║   ██║██║   ██║    ██║ ██╔╝██║   ██║████╗ ████║██╔══██╗██╔══██╗
██║  ██║███████║██████╔╝██║   ██║██║   ██║    █████╔╝ ██║   ██║██╔████╔██║███████║██████╔╝
██║  ██║██╔══██║██╔══██╗██║   ██║╚██╗ ██╔╝    ██╔═██╗ ██║   ██║██║╚██╔╝██║██╔══██║██╔══██╗
██████╔╝██║  ██║██║  ██║╚██████╔╝ ╚████╔╝     ██║  ██╗╚██████╔╝██║ ╚═╝ ██║██║  ██║██║  ██║
╚═════╝ ╚═╝  ╚═╝╚═╝  ╚═╝ ╚═════╝   ╚═══╝      ╚═╝  ╚═╝ ╚═════╝ ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝  ╚═╝

dhruv@workstation
──────────────────────────────────────────────────
OS          NsutOS (rolling release, deadline-driven)
Host        Netaji Subhas University of Technology
Kernel      B.Tech CSE — 3rd Year
Shell       /bin/research-build-deploy
Resolution  research × production
Uptime      since first torch.backward()
Locale      new-delhi, IN
GPU         dreams@cuda:0
Memory      transformers loaded · context window: unlimited
```

```console
dhruv@workstation:~$ whoami
Dhruv Kumar — engineer of transformer-based AI systems.
I train things that learn, ship things that scale,
and occasionally win national hackathons.
```

```console
dhruv@workstation:~$ lsmod | sort -k2 -r
Module              Size        Used by
python              ██████████  everything_below
pytorch             █████████   transformers, cnn_rnn, fine_tuning
transformers        █████████   nlp, llm_apps, huggingface
langchain           ████████    rag_pipelines
langgraph           ████████    agentic_workflows, multi_agent
fastapi             ████████    rest_apis, inference_servers
nextjs              ████████    frontends, ssr_apps
react               ███████     uis, hackathon_uis
faiss               ███████     vector_search, semantic_retrieval
tensorflow          ███████     deep_learning, model_training
scikit_learn        ███████     feature_engineering, classic_ml
postgresql          ██████      supabase, persistence
docker              ██████      containerized_deploys
tailwind            █████       ui_polish
javascript          █████       the_glue

# compiled into kernel at boot:
# numpy · pandas · matplotlib · seaborn · jupyter · git · github
```

```console
dhruv@workstation:~$ dhruv render --graph=architecture
rendering pipeline... done. output attached below.
```

```mermaid
%%{init: {"theme":"base","themeVariables":{"primaryColor":"#0D1117","primaryTextColor":"#E6EDF3","primaryBorderColor":"#00FF9C","lineColor":"#00FF9C","secondaryColor":"#161B22","tertiaryColor":"#161B22","clusterBkg":"#0D1117","clusterBorder":"#30363D","fontFamily":"monospace","fontSize":"13px"}}}%%
flowchart LR
    subgraph ingress
        direction TB
        p[problem statements]
        d[(raw data)]
    end
    subgraph core [cognition core]
        direction TB
        fe[feature engineering]
        ml[ml / deep learning]
        llm[transformers · llms]
    end
    subgraph runtime [delivery runtime]
        direction TB
        api[rest apis · fastapi]
        ag[langgraph agents]
        ui[react / next.js]
    end
    subgraph egress
        direction TB
        dk[[docker image]]
        prod([production])
    end
    p --> fe
    d --> fe
    fe --> ml
    ml --> llm
    ml --> api
    llm --> api
    api --> ag
    api --> ui
    ag --> dk
    ui --> dk
    api --> dk
    dk --> prod
    classDef flare fill:#00FF9C,stroke:#00FF9C,color:#0D1117,font-weight:bold
    class prod flare
```

```console
dhruv@workstation:~$ git log --graph --all --oneline
rendering commit topology... done. output attached below.
```

```mermaid
%%{init: {"theme":"base","themeVariables":{"commitLabelColor":"#0D1117","commitLabelBackground":"#00FF9C","tagLabelColor":"#0D1117","tagLabelBackground":"#E6EDF3","tagLabelBorder":"#00FF9C","git0":"#E6EDF3","git1":"#00FF9C","git2":"#3FB6FF","gitBranchLabel0":"#0D1117","gitBranchLabel1":"#0D1117","gitBranchLabel2":"#0D1117","fontFamily":"monospace"}}}%%
gitGraph
    commit id: "hello_world.py"
    commit id: "dsa_grind"
    branch ml_core
    commit id: "classical_ml"
    commit id: "cnn_rnn"
    commit id: "transformers"
    checkout main
    branch full_stack
    commit id: "fastapi_backends"
    commit id: "nextjs_frontends"
    checkout main
    merge ml_core tag: "ai online"
    merge full_stack tag: "SIH: WINNER"
    commit id: "llm_apps" type: HIGHLIGHT
    commit id: "productionizing_ai"
```

```console
dhruv@workstation:~$ grep -iE "winner|shipped|active" /var/log/achievements.log
[ACH-001]  Smart India Hackathon      ▸ WINNER — national level
[ACH-002]  Amazon ML Summer School    ▸ TOP 2% — 10,000+ participants
[ACH-003]  hackathon circuit          ▸ ACTIVE — scalable AI products
```

```console
dhruv@workstation:~$ htop --user=kumardhruv88 --mode=github
```

<p align="center">
  <img src="https://streak-stats.demolab.com?user=kumardhruv88&hide_border=true&background=0D1117&stroke=8B949E&ring=00FF9C&fire=00FF9C&currStreakNum=E6EDF3&sideNums=E6EDF3&currStreakLabel=00FF9C&sideLabels=8B949E&dates=8B949E" alt="contribution streak" />
</p>

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=kumardhruv88&bg_color=0D1117&color=8B949E&line=00FF9C&point=E6EDF3&area=true&area_color=00FF9C&hide_border=true" alt="contribution graph" />
</p>

```console
dhruv@workstation:~$ cat /proc/dhruv/focus
llm_apps         [ACTIVE]   building llm-powered applications
agentic_ai       [ACTIVE]   multi-agent workflows over langgraph
rag_pipelines    [ACTIVE]   retrieval-augmented generation at scale
productionize    [ALWAYS]   models that survive contact with real users
```

```console
dhruv@workstation:~$ curl -s https://api.dhruvkumar.dev/v1/contact | jq
```

```json
{
  "status": 200,
  "channels": {
    "linkedin": "https://www.linkedin.com/in/dhruv-kumar-64752327a",
    "email": "kumardhruv2308@gmail.com",
    "portfolio": "https://portfolio-blush-sigma-cnmnqaewtr.vercel.app"
  },
  "open_to": ["ai/ml engineering", "research collaborations", "hackathon teams"],
  "latency": "low"
}
```

<p align="center">
  <a href="https://www.linkedin.com/in/dhruv-kumar-64752327a/"><img src="https://img.shields.io/badge/linkedin-dhruv--kumar-161B22?style=flat-square&logo=linkedin&logoColor=00FF9C&labelColor=0D1117" alt="linkedin" /></a>
  <a href="mailto:kumardhruv2308@gmail.com"><img src="https://img.shields.io/badge/email-kumardhruv2308%40gmail.com-161B22?style=flat-square&logo=gmail&logoColor=00FF9C&labelColor=0D1117" alt="email" /></a>
  <a href="https://portfolio-blush-sigma-cnmnqaewtr.vercel.app/"><img src="https://img.shields.io/badge/portfolio-live-161B22?style=flat-square&logo=vercel&logoColor=00FF9C&labelColor=0D1117" alt="portfolio" /></a>
</p>

```console
dhruv@workstation:~$ exit
logout
Connection to dhruvkumar.dev closed.
```

<p align="center">
  <img src="https://komarev.com/ghpvc/?username=kumardhruv88&label=sessions&color=00ff9c&style=flat-square" alt="session counter" />
</p>

<p align="center">
  <sub>star what deserves stars · fork what sparks ideas</sub><br />
  <sub>no emojis were harmed in the making of this profile</sub>
</p>
