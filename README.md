# Guide to Comparing Domestic Franchises — Korean Coffee Brands

**Creator:** Samyam Poudel  
**Project type:** Student mission / bilingual comparison webpage  
**Industry:** Coffee franchises in South Korea  
**Comparison subjects:** MEGA MGC COFFEE (메가MGC커피), COMPOSE COFFEE (컴포즈커피), PAIK'S COFFEE (빽다방)

## Project description
A responsive, single-file webpage that introduces three Korean coffee franchises in simple English with Korean translations. It compares one metric only: the number of franchise locations at year-end 2024. The page includes ascending and descending sort buttons, four search queries with explanations of how search results differ, and source links.

## Metric and base year
- **Metric:** Franchise-store count (not annual revenue and not company-owned store count).
- **Base year:** Year-end 2024.
- **Unit:** Stores / locations.
- **Values shown provisionally:** MEGA MGC COFFEE 3,325; COMPOSE COFFEE 2,649; PAIK'S COFFEE 1,712.
- **Data-quality note:** The counts are listed in a secondary comparison table that says it uses KFTC franchise-disclosure data. The page explicitly says the brand-specific counts still need confirmation in the original KFTC disclosure records; they are not described as independently verified.

## Tools used
- ChatGPT: drafted the bilingual explanatory content and webpage structure.
- Perplexity / web search: research workflow recommended for cross-checking original sources before submission.
- HTML, CSS, JavaScript: responsive single-file webpage and client-side sorting.
- GitHub: source control and hosting repository.
- Vercel: static website deployment workflow.

## Research sources
1. Korea Fair Trade Commission franchise disclosure system: https://franchise.ftc.go.kr/
2. Francha coffee franchise comparison (secondary table of 2024 year-end counts): https://francha.craftspace.co.kr/sector/coffee
3. MEGA MGC COFFEE official website: https://mega-mgccoffee.com/
4. COMPOSE COFFEE official website: https://composecoffee.com/
5. PAIK'S COFFEE official website: https://paikdabang.com/
6. KFTC announcement on 2024 franchise statistics: https://www.ftc.go.kr/www/selectBbsNttView.do?bordCd=3&key=12&nttSn=45987&pageIndex=1&pageUnit=10&searchCnd=all&searchCtgry=01%2C02

## Three specific details verified or modified
1. Chose three brands from the same industry: Korean coffee franchises.
2. Kept the comparison to one metric and one base year: franchise locations at year-end 2024; did not mix in revenue figures.
3. Added ascending/descending sort buttons that sort numeric store counts, four search-query explanations, bilingual content, and a clear note that exact counts should be checked against the original KFTC disclosures before formal submission.

## Run and deploy
- Open `index.html` in a modern browser. The webpage uses no external APIs or build tools.
- For Vercel, connect this repository, select **Other** as the framework preset, leave the build command empty, and keep `index.html` in the repository root.
- After deployment, test both sorting buttons on desktop and mobile and open the source links.
