## RSS Deployment

#### Lenka Ivanová

Build a Deployment je vytvorený pomocou Github Actions a Github Pages.

Repozitár sa nazýva "deploy" a pozostáva z "master" branch a "lenka-rss-deploy" branch.  
Yml súbor s jednotlivými krokmi jobu sú v lenka-rss-deploy -> .github/workflows -> devops.yml
Po zbuildovaní je spa presunutá do priečinku docs na master branchi.  
Hosting poskytuje Github Pages.

Deploynuté RSS je možné nájsť tu: https://lenkaivanova.github.io/deploy/#/

