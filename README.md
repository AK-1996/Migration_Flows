# Migration Flows: An Overall Look

**Author:** Matteo Poirè  
**Institutional ID:** 529713  
**Contact:** matteo.poire01@universitadipavia.it  

## 📖 Project Summary
A network-science and econometric study of global migration flows (1990–2020, 5-year steps) across 237 countries.  
- **Network Analysis**  
  - Built directed, weighted graphs per period  
  - Computed centralities (betweenness, closeness, eigenvector, PageRank, hubs/authorities)  
  - Detected community structure via Louvain modularity  
- **Regression Modeling**  
  - Linear, interaction, quadratic and polynomial models vs. economic indicators (GDP ppp, HDI, Gini, unemployment, population)  
  - Fixed-effects panel models to control for country/time heterogeneity  
  - Gravity model incorporating distance, contiguity, language & colonial ties  

## 🚀 Key Findings & Takeaways
- **Stable network** with only minor decade-to-decade shifts in hubs/authorities.  
- **Economic indicators alone** explain only a small fraction of migration-network variation.  
- **Fixed-effects** highlight the role of inequality, unemployment and population in shaping centrality and flows.  
- **Gravity model** performs best: distance, shared border/language/colonial history are strong predictors; economic effects secondary.

## 🔧 Requirements
- **MATLAB** ≥ R2021a  
- **Toolboxes**:  
  - Statistics and Machine Learning  
  - Econometrics  
  - Graph & Network Algorithms  
- **Optional**: Parallel Computing Toolbox (for large-scale graphs)
