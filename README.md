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

### 🛠️ Stack

[![Stack](https://skillicons.dev/icons?i=python,postgres,gcp,git,github&theme=dark)](https://skillicons.dev)

![Google Analytics](https://img.shields.io/badge/GA4-E37400?style=flat-square&logo=googleanalytics&logoColor=white)
![Google Tag Manager](https://img.shields.io/badge/GTM-246FDB?style=flat-square&logo=googletagmanager&logoColor=white)
![BigQuery](https://img.shields.io/badge/BigQuery-669DF6?style=flat-square&logo=googlebigquery&logoColor=white)
![pandas](https://img.shields.io/badge/pandas-150458?style=flat-square&logo=pandas&logoColor=white)
![NumPy](https://img.shields.io/badge/NumPy-013243?style=flat-square&logo=numpy&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-11557C?style=flat-square)

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
