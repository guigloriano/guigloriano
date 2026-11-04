<img width="100%" alt="Guilherme G. de Souza" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=170&section=header&text=Guilherme%20G.%20de%20Souza&fontSize=38&fontColor=ffffff&fontAlignY=35&desc=EV%20Smart%20Charging%20%C2%B7%20V2G%20%C2%B7%20Multi-objective%20Optimization&descSize=16&descAlignY=58" />

**PhD candidate in Computer Science** · Researcher at LSCAD · Data engineer at MTR · Brazil 🇧🇷

I work on **smart charging of electric vehicles**: scheduling algorithms that flatten grid load (valley-filling, peak-shaving, Vehicle-to-Grid) and multi-objective optimization with evolutionary algorithms (NSGA-II / NSGA-III). In industry, I build analytics and data pipelines (GA4 → BigQuery, server-side tracking with GTM and the Measurement Protocol).

### 🔬 Research

- **V2G scheduling for city-scale EV fleets** – a three-stage peak-shaving algorithm with state-of-charge recovery, compared against a charging-only heuristic (LCVF) and an exact Gurobi model on 768 instances.
  Reproduction package: [`v2g-3-stages`](https://github.com/guigloriano/v2g-3-stages) *(manuscript under review)*
- **Smart decision making in EV charging systems** – scenarios and algorithms for charging station operation.
  [`Article-Smart_Decision_Making_in_EVCS`](https://github.com/guigloriano/Article-Smart_Decision_Making_in_EVCS)
- **Topics:** valley-filling · V2G · combinatorial optimization · NSGA-III · reproducible research

```mermaid
flowchart LR
    A["Grid base load<br/>+ EV fleet<br/>(arrivals, SoC, departures)"] --> B["Stage 1<br/>V2G discharge<br/>at the peak"]
    B --> C["Stages 2–3<br/>levelled recharge<br/>(SoC recovery)"]
    C --> D["Flattened load curve<br/>+ departure SoC met"]
    D -. "benchmark" .-> E["LCVF heuristic<br/>· Exact model (Gurobi)"]
```

### 💼 Industry · MTR

Analytics and data engineering for a virtual try-on (VTO) product embedded in e-commerce sites — from event tracking inside the iframe to server-side purchase attribution and reporting.

```mermaid
flowchart LR
    VTO(["Virtual try-on iframe<br/>on client e-commerce sites"])

    subgraph S1["1 · Tracking & collection"]
        direction TB
        A1["GTM containers<br/>centralized variables · cross-domain"]
        A2["JS snippet + postMessage<br/>iframe ↔ parent page"]
        A3["Custom funnel events<br/>dataLayer · GA4"]
    end

    subgraph S2["2 · Server-side attribution"]
        direction TB
        B1["GA4 client_id correlation<br/>PostgreSQL"]
        B2["Order reconciliation<br/>Nuvemshop / Shopify APIs"]
        B3["GA4 Measurement Protocol<br/>purchase events"]
    end

    subgraph S3["3 · Data warehouse"]
        direction TB
        C1["GA4 → BigQuery export<br/>multi-property migration"]
        C2["SQL funnel & latency analysis"]
    end

    subgraph S4["4 · Insights"]
        direction TB
        D1["Looker Studio dashboards"]
        D2["Data-storytelling reports<br/>Python · Chart.js"]
    end

    VTO --> S1 --> S2 --> S3 --> S4
    A1 --- A2 --- A3
    B1 --> B2 --> B3
    C1 --> C2
    D1 --- D2
```

### 🛠️ Stack

[![Stack](https://skillicons.dev/icons?i=py,c,js,postgres,gcp,aws,linux,latex,git,github&theme=dark)](https://skillicons.dev)

**Analytics & data engineering**<br/>
![GA4](https://img.shields.io/badge/GA4-E37400?style=flat-square&logo=googleanalytics&logoColor=white)
![Google Tag Manager](https://img.shields.io/badge/GTM-246FDB?style=flat-square&logo=googletagmanager&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![Looker Studio](https://img.shields.io/badge/Looker_Studio-4285F4?style=flat-square&logo=looker&logoColor=white)
![DynamoDB](https://img.shields.io/badge/DynamoDB-4053D6?style=flat-square&logo=amazondynamodb&logoColor=white)

**Scientific computing**<br/>
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![SciPy](https://img.shields.io/badge/SciPy-8CAAE6?style=flat-square&logo=scipy&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Google Colab](https://img.shields.io/badge/Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white)

<!-- TODO: uncomment and fill in your links
### 📫 Contact

[LinkedIn](https://www.linkedin.com/in/...) · [Lattes](http://lattes.cnpq.br/...) · [ORCID](https://orcid.org/...) · [Google Scholar](https://scholar.google.com/citations?user=...)
-->

### 🐍 Contributions

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/guigloriano/guigloriano/output/github-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/guigloriano/guigloriano/output/github-snake.svg" />
  <img alt="Contribution graph snake animation" src="https://raw.githubusercontent.com/guigloriano/guigloriano/output/github-snake.svg" />
</picture>

---

<details>
<summary>🇧🇷 Em português</summary>

Doutorando em Ciência da Computação e pesquisador no LSCAD. Pesquiso **recarga inteligente de veículos elétricos** — algoritmos de escalonamento que achatam a curva de carga da rede (*valley-filling*, *peak-shaving*, V2G) e otimização multiobjetivo com algoritmos evolutivos (NSGA-II/NSGA-III). Na indústria, atuo com engenharia de dados e analytics na MTR (pipelines GA4 → BigQuery, rastreamento server-side com GTM e Measurement Protocol).

</details>

<img width="100%" alt="" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f2027,50:203a43,100:2c5364&height=90&section=footer" />
