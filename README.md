# Movie Magic — Data-Driven Insights for Indie Filmmakers & Investors  
**Capstone Project | Data Analytics | November 2025**

[![Python](https://img.shields.io/badge/Python-3776AB?logo=python&logoColor=white)](https://www.python.org/)
[![Pandas](https://img.shields.io/badge/Pandas-150458?logo=pandas&logoColor=white)](https://pandas.pydata.org/)
[![Tableau](https://img.shields.io/badge/Tableau-E97627?logo=tableau&logoColor=white)](https://www.tableau.com/)
[![TMDB](https://img.shields.io/badge/Data-TMDB-01D277?logo=themoviedatabase&logoColor=white)](https://www.themoviedb.org/)

Live Site → https://movie-magic.lovable.app  
Interactive Dashboard → https://public.tableau.com/app/profile/brendachebyte/viz/MovieMagic-IndieFilmROI/Dashboard1  

## Project Overview
Independent filmmakers in Kenya and across the world struggle to secure funding because they pitch passion without proof.  
**Movie Magic** changes that: a full data analytics playbook that answers every investor question with hard numbers from 12,000+ films (2018 – Nov 2025).

## Problem Statement
Investors always ask the same 6 questions most indie filmmakers cannot answer with data:

1. Which genres actually deliver the highest ROI?  
2. Which directors consistently make money across ≥3 films?  
3. Which actors repeatedly appear in high-ROI projects?  
4. Which genres are oversaturated vs underserved goldmines?  
5. Why did animation ROI crash in 2021 and explode again in 2023–2025?  
6. Where should I put my $5M–$50M budget for maximum return?

This project gives clear, visual, investor-ready answers.

## Objectives
- Identify the most profitable & audience-loved genres 2018–2025  
- Highlight directors & actors with proven, repeatable ROI  
- Map genre saturation vs opportunity to find market gaps  
- Deliver a clean dataset + interactive dashboard  
- Empower indie filmmakers to pitch like studio executives

## Data Sources & Tools
| Category      | Tool / Source                  | Purpose                              |
|---------------|--------------------------------|--------------------------------------|
| Data          | TMDB API (12k+ films)          | Budgets, revenue, cast, genres       |
| Processing    | Python • Pandas • Jupyter      | Cleaning & feature engineering       |
| Storage       | Google BigQuery                | Fast querying                        |
| Visualization | Tableau Public                 | Investor-grade interactive dashboard |
| Website       | Lovable.dev                    | Beautiful cinematic portfolio site   |
| Hosting       | GitHub                         | Version control & public showcase    |

## Methodology
1. Collected 2018–2025 theatrical releases via TMDB API  
2. Cleaned: removed duplicates, missing revenue/budget, re-releases  
3. Exploded multi-value fields (genres, cast, directors)  
4. Engineered: ROI, Saturation Score, Opportunity Score  
5. Filtered talent: Directors ≥3 films, Actors ≥4 films  
6. Built interactive Tableau dashboard + portfolio site

## Key Insights (2018 – Nov 2025)
- Horror → 5.05× average ROI → still the indie king  
- Animation → crashed to ~1× in 2021 (hybrid releases) → exploded to 12×+ in 2023–2025  
- Mystery & Sci-Fi/Fantasy → severely underserved but rising fast  
- Top ROI actors = supporting/voice roles in MCU & Illumination films (5–7×)  
- Action & Comedy → most oversaturated, mediocre returns  
- Weak correlation between IMDb rating and ROI → marketing > reviews

## Business Value
| Stakeholder         | Benefit                                      |
|---------------------|----------------------------------------------|
| Indie Filmmakers    | Pitch with data → higher funding success     |
| Investors           | Spot 5–10× opportunities early             |
| Producers           | Justify genre & casting in seconds           |
| Talent Agents       | Prove clients’ real ROI value                |

## Live Links
- Portfolio Website: https://movie-magic.lovable.app  
- Tableau Dashboard: https://public.tableau.com/app/profile/brendachebyte  
- GitHub Repo: https://github.com/brendachebyte/Movie-Magic-Capstone  
- Blog Write-up: https://brendachebyte.hashnode.dev/movie-magic-a-data-driven-approach-to-maximizing-roi-for-indie-filmmakers

## Future Improvements
- Add ML prediction model for new film ROI  
- Include regional performance (Africa, Asia, LatAm)  
- Build budget simulator tool

**Built with passion in Nairobi, Kenya • November 2025**  
Brenda Chepteek • Data Analyst | Filmmaker | Storyteller

Movie Magic — Because great African stories deserve great returns.
