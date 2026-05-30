---
title: 'Beyond Embeddedness'
subtitle: 'Bibliometric Evidence from Prize-Winning Articles in Economic Sociology'
date: 2026-05-22
excerpt: ""
thumbnail: /images/coauthor_network.png
thumbnail_zoom: 1.8

permalink: /posts/2026/05/beyond-embeddedness/
tags:
  - research
  - econ soc
---

*What counts as an innovation in economic sociology?* Since its emergence in the late twentieth century, New Economic Sociology has largely defined itself in opposition to neoclassical economics through concepts such as embeddedness, uncertainty, and social networks. But now that the social nature of markets is broadly accepted within the field, the more interesting question becomes which kinds of intellectual contributions are institutionally rewarded today.

As a young scholar entering economic sociology, I wanted a clearer empirical sense of where the field's gold standard actually sits. To answer that question, I conducted a small bibliometric analysis of all ASA and SASE prize-winning articles in economic sociology from 2012 to 2025.

## Three Schools of Economic Sociology

But first, a brief map. Contemporary economic sociology, as I see it, can be divided into roughly three camps: the cultural school, the business school, and the political economy school. In a somewhat Weberian sense, these three poles can be understood as ideal-typical groupings rather than rigid classifications; many of the scholars discussed here could be placed in multiple categories. However, categorization should not be discarded simply because there is ambiguity at the borders, and I believe that these groups capture the lion's share of economic sociologists' output in recent years. In terms of criteria, the schema is largely U.S.-centric and reflects differences in analytical frameworks, along with the practical division of labor embedded within the organizational structures of academic institutions.

The first branch is what I would call the *cultural school*, which centers around questions of value, morality, legitimacy, and the cultural construction of markets: Zelizer on life insurance, Fourcade on quantification, Healy on organ donation. This work is often theoretical, historical, qualitative, and oriented toward symbolic meaning-making more broadly. These studies tend to be foundational and highly cited, yet the time-intensive nature of the work makes it difficult for new entrants to penetrate this field.

The second approach to economic sociology can be defined by its close relations with *business* schools. Focusing on organizations, job searches, the theory of the firm, and the emergence of markets, this approach draws on the Granovetterian tradition to ask how social ties shape individual and organizational outcomes. This approach is especially visible in places with close ties between sociology departments and management schools, such as MIT Sloan, Northwestern, and Stanford. Since this work may also have utility for market actors themselves, this branch generally does not seek to challenge the capitalist order at large, despite pointing out some of its negative externalities.

The last branch of economic sociology is, in many ways, closely aligned with *political economy*. This body of work spans several substantive fields—primarily finance, work, inequality, gender, race, and the state—while remaining analytically unified by a focus on power and institutions. In contrast to the business school, the political economy school is more overtly critical of capitalism and its negative distributional consequences, asking: Who benefits from market arrangements? How does financial capitalism reshape households? How do firms exercise power over workers? Sociologists such as Neil Fligstein, Nathan Wilmers, and Adam Goldstein exemplify this approach. Despite the cultural school's tight grip on the field, my sense is that this final branch reflects the direction in which the discipline is partly headed, especially given that many newly hired faculty in American sociology departments seem to adopt this approach.

## Prize-Winning Articles

To empirically evaluate this schema, I next analyze all ASA and SASE/SER prize-winning articles in economic sociology (2012–2025). Rather than looking at citation counts, I decided to focus on prize-winning articles for two reasons. First, since economic sociology is a subdiscipline, it is difficult to systematically delineate what constitutes "economic sociology" from other types of articles within well-known sociology journals. By focusing on prizes distinctively awarded for "economic sociology," I ensure that the final sample represents papers that both the author(s) and the selection committees understood to belong to this subdiscipline. Second, while prize-winning articles are by no means representative of economic sociology's full contribution, they reflect what leading figures in the field consider significant and innovative work. This helps filter out potential noise arising from the tendency to cite well-known scholars regardless of the novelty of their contributions.

The final sample comprises 37 peer-reviewed articles: 26 from the [ASA Granovetter Award](https://www.asanet.org/communities-and-sections/sections/current-sections/economic-sociology-award-recipient-history/) (2012–2025) and 11 from the [SER Best Article Award](https://sase.org/awards/ser-best-article-prize/) (2020–2025).

**Table 1. Summary statistics**
{: .table-label}

| | |
|---|---|
| **Corpus** | |
| Total articles | 37 |
| ASA Granovetter Award (winner) | 17 |
| ASA Granovetter Award (hon. mention) | 9 |
| SER Best Article Prize (winner) | 8 |
| SER Best Article Prize (hon. mention) | 3 |
| **Authorship** | |
| Solo-authored | 25 |
| Two authors | 5 |
| Three or more authors | 7 |
| **Article Citations** | |
| Mean | 87.6 |
| Median | 26 |
| Range | 1–1158 |
| **Methods** | |
| Qualitative | 18 (48.6%) |
| Causal (experiment/RDD/IV) | 6 (16.2%) |
| TWFE/panel regression | 5 (13.5%) |
| OLS/descriptive regression | 5 (13.5%) |
| Network analysis | 3 (8.1%) |
| **Gender** | |
| Total authors | 56 |
| Female | 15 (26.8%) |
| Male | 41 (73.2%) |

A few things stand out from the descriptive statistics. Most articles are sole-authored, and the mean citation count sits around 88, though that figure is biased downward due to the recency of some papers' publication. Interestingly, nearly half the corpus uses qualitative methods—theory-building, historical case studies, process tracing—while only six articles (16%) use explicitly causal designs such as regression discontinuities, experiments, or instrumental variables. The field therefore remains heavily qualitative at its recognized peak. The gender skew is also notable: 73% of prize-winning authors between 2012 and 2025 were men, with no statistically significant change over the period.[^1] Looking at which scholars are cited most frequently across the corpus, Zelizer leads by a wide margin (cited in 59% of articles), followed by Fourcade, Fligstein, and Lamont. Notably, Granovetter—after whom the ASA prize is named—does not appear in the top ten.

**Table 2. Most frequently cited authors**
{: .table-label}

| Rank | Author | Papers citing | % of corpus |
|------|--------|--------------|-------------|
| 1 | Zelizer, V. | 22 | 59% |
| 2 | Fourcade, M. | 14 | 38% |
| 3 | Fligstein, N. | 13 | 35% |
| 4 | Lamont, M. | 13 | 35% |
| 5 | Espeland, W. | 12 | 32% |
| 6 | Piketty, T. | 12 | 32% |
| 7 | Krippner, G. | 12 | 32% |
| 8 | Ridgeway, C. | 11 | 30% |
| 9 | Carruthers, B. | 10 | 27% |
| 10 | Weber, M. | 10 | 27% |

## Topic Modeling

To explore the latent structure of the corpus, I used structural topic modeling (STM), which differs from standard LDA in allowing covariates—here, publication year—to influence topic prevalence. I selected K = 5 topics based on where semantic coherence peaked. I label the five topics as: (1) finance and governance (32%), (2) gender and evaluation (22%), (3) occupations, inequality, and social mobility (18%), (4) racial and urban inequality (15%), and (5) the moral economy of care work (13%).

<img src="/images/stm_top_words_bar.png" style="width: 78%;">

**Figure 1.**
{: .figure-label}

Top 10 FREX-weighted words per topic. FREX balances word frequency within a topic against exclusivity to that topic.
{: .figure-desc}

**Table 3. Topics and examples**
{: .table-label}

| Topic | Key words | Example article | School |
|-------|-----------|----------------|--------|
| (1) Finance and governance | bank; imf; asset; monetari- | "Sectors versus borders" (Voss 2024) | Business / Political economy |
| (2) Gender and evaluation | women; perform; task; stereotype | "The Task Bind" (Feldberg 2023) | Cultural |
| (3) Occupations, inequality, and social mobility | tax; migrat-; germani-; web | "Rediscovering the 1%" (Hirschman 2021) | Political economy |
| (4) Racial and urban inequality | unemploy-; hous-; nonprofit; parent; racial | "Making Markets on the Margins" (Robinson 2020) | Political economy |
| (5) The moral economy of care work | consum-; moral; nurs-; insur- | "The Moral Limits of Predictive Practices" (Kiviat 2019) | Cultural |

Mapping these onto the three-school framework: finance and governance sits at the intersection of the business and political economy schools; gender and evaluation fits the cultural school's concern with symbolic classification and categorical boundaries; occupations and racial inequality fall squarely in the political economy tradition; and the moral economy of care work is the most clearly "cultural school" topic. Together, Topics 1 and 4 account for nearly half the corpus—suggesting that political economy and finance-adjacent work are more institutionally central than the cultural school's dominance in citation counts might imply.

The topic trends over time are broadly insignificant (only 37 papers), but two patterns are worth flagging. Topic 5 (the moral economy of care work) shows a declining trajectory, consistent with the intuition that "cultural" work on morality and embedded exchange was more central to prize-winning work in the early 2010s than it is today. Topic 4 (racial and urban inequality) trends modestly upward, consistent with the growing visibility of race and place-based inequality in American sociology over the decade.

<img src="/images/stm_topics_estimateeffect.png" style="width: 78%;">

**Figure 2.**
{: .figure-label}

Predicted topic share per year via estimateEffect, averaged across documents, with 95% confidence intervals.
{: .figure-desc}

## Co-Authorship Networks

As a complement to the text analysis, I pulled co-authorship data from OpenAlex for all 56 prize-winning authors and constructed a first-degree network, spanning 2,960 nodes (scholars) and 3,075 edges (co-authorship ties). The network reveals one dominant connected component and several smaller isolated clusters, suggesting the field is organized around a core insider group with a few more peripheral figures. About 18% of prize-winning authors had a prior documented co-authorship tie to a previous winner—consistent with some degree of intellectual diffusion, or network effects in prize selection.

![Co-authorship networks among prize-winning economic sociologists](/images/coauthor_network.png)

**Figure 3.**
{: .figure-label}

Node size reflects degree centrality; edge width and opacity reflect the number of co-authored papers. Colors denote Louvain community membership.
{: .figure-desc}

## A Few Takeaways

Overall, economic sociology still differentiates itself from economics by the prominence of qualitative methods and an emphasis on symbolic meaning-making processes, represented by the older "cultural school." An innovation in economic sociology is therefore rarely a methodological contribution in the quantitative sense, unlike in economics; rather, the discipline tends to borrow methods and instead focuses its impact on reframing how we understand social and economic reality. Topics related to finance and monetary governance remain comparatively dominant, reflecting the stronger influence of political economy and business school traditions within the field. Gender also seems to be playing an interesting role. Although the most frequently cited economic sociologists in this sample are women, such as Zelizer and Fourcade, most contemporary prize winners are men: 73.2 percent of winners between 2012 and 2025 were male, with no statistically significant change in gender composition over the period. Although these findings are not inherently problematic and should be situated within a more thoughtful analysis, they nonetheless point to the importance of reflecting on potential biases within the discipline.

*Replication code and data available on request. Any suggestions or critiques are welcome!*  
*[lydia.cp02@gmail.com](mailto:lydia.cp02@gmail.com)*

[^1]: This may partly reflect lower rates of self-nomination among women rather than bias in selection.

---

<details markdown="1">
<summary><strong>Appendix: Full corpus (N = 37)</strong></summary>

<br>

| Author(s) | Title | Journal | Year |
|-----------|-------|---------|------|
| Donald MacKenzie | The Credit Crisis as a Problem in the Sociology of Knowledge | AJS | 2012 |
| Lauren Rivera | Hiring as Cultural Matching: The Case of Elite Professional Service Firms | ASR | 2013 |
| Patrick Hamm et al. | Mass Privatization, State Capacity, and Economic Growth in Post-Communist Countries | ASR | 2014 |
| András Tilcsik | Imprint-environment fit and performance | ASQ | 2015 |
| Delia Baldassarri | Cooperative Networks: Altruism, Group Solidarity, Reciprocity, and Sanctioning in Ugandan Producer Organizations | AJS | 2016 |
| Christopher Yenkey | Mobilizing a Market: Ethnic Segmentation and Investor Recruitment into the Nairobi Securities Exchange | ASQ | 2017 |
| Cristobal Young et al. | Millionaire Migration and Taxation of the Elite: Evidence from Administrative Data | ASR | 2017 |
| Nathan Wilmers | Does Consumer Demand Reproduce Inequality? High-Income Consumers, Vertical Differentiation, and the Wage Structure | AJS | 2018 |
| Angèle Christin | Counting Clicks: Quantification and Variation in Web Journalism in the United States and France | AJS | 2019 |
| Emily Erikson & Mark Hamilton | Companies and the Rise of Economic Thought: The Institutional Foundations of Early Economics in England, 1550–1720 | AJS | 2019 |
| Patrick Park et al. | The strength of long-range ties in population-scale social networks | Science | 2019 |
| Barbara Kiviat | The Moral Limits of Predictive Practices: The Case of Credit-Based Insurance Scores | ASR | 2020 |
| Christof Brandtner et al. | Spatial Mismatch and Youth Unemployment in US Cities: Public Transportation as a Labor Market Institution | SER | 2020 |
| Lauren Rivera & András Tilcsik | Scaling Down Inequality: Rating Scales, Gender Bias, and the Architecture of Evaluation | ASR | 2020 |
| Lukas Haffert | Permanent Budget Surpluses as a Fiscal Regime | SER | 2020 |
| John Robinson | Making markets on the margins: Housing finance agencies and the racial politics of credit expansion | AJS | 2021 |
| Mabel Abraham | Gender-role incongruity and audience-based gender bias: An examination of networking among entrepreneurs | ASQ | 2021 |
| Ryan Calder | Halalization: Religious Product Certification in Secular Markets | Soc. Theory | 2021 |
| Stefano Pagliari et al. | The Financialization of Policy Preferences | SER | 2021 |
| Adam Goldstein & Charlie Eaton | Asymmetry by Design? Identity Obfuscation, Reputational Pressure, and Consumer Predation in U.S. For-Profit Higher Education | AJS | 2022 |
| Bernhard Reinsberg et al. | Creating Crony Capitalism: Neoliberal Globalization and the Fuelling of Corruption | SER | 2022 |
| Dan Hirschman | Rediscovering the 1%: Knowledge Infrastructure and the Stylized Facts of Inequality | AJS | 2022 |
| Alexandra Feldberg | The Task Bind: Explaining Gender Differences in Managerial Tasks and Performance | ASQ | 2023 |
| Grégoire Mallard & Jin Sun | Viral Governance: How Unilateral U.S. Sanctions Changed the Rules of Financial Capitalism | AJS | 2023 |
| Maximilian Sprengholz et al. | Gender identity and wives' labor market outcomes in West and East Germany between 1983 and 2016 | SER | 2023 |
| Roi Livne | Toward a Sociology of Finitude: Life, Death, and the Question of Limits | Theory & Society | 2023 |
| Aaron Horvath | Organizational Supererogation and the Transformation of Nonprofit Accountability | AJS | 2024 |
| Alexander Horn et al. | The Paternalist Politics of Punitive and Enabling Workfare | SER | 2024 |
| Aliya Hamid Rao | Relational Work in the Family: The Gendered Microfoundation of Parents' Economic Decisions | ASR | 2024 |
| Carly Knight | Classifying the Corporation: The Role of Naturalizing Analogies in American Corporate Development, 1870–1930 | SER | 2024 |
| Niall Reddy | Liberalization, Democratization and the Remaking of the South African Corporate Network 1993–2020 | SER | 2024 |
| Pablo Gastón | Moralizing the Strike: Nurses Associations and the Justification of Workplace Conflict in California Hospitals | AJS | 2024 |
| Dustin Voss | Sectors versus borders: interest group cleavages and struggles over corporate governance in the age of asset management | SER | 2025 |
| Mary-Collier Wilks | The Logic of Patronage: Relational Work in Cambodian International Nongovernmental Organizations | SER | 2025 |
| Matthew Soener | Are IMF programs raising greenhouse gas emissions in the Global South? | SER | 2025 |
| Shay O'Brien | The family web: Multigenerational class persistence in elite populations | SER | 2025 |
| Steffen Murau & Matteo Giordano | Forging monetary unification through novation: the TARGET system and the politics of central banking in Europe | SER | 2025 |

</details>
