🧠 NEXUS PREDICTIVE OOM KILLER
    Le Gestionnaire de Mémoire Souverain. Anticipez les pénuries de RAM avec la logique mathématique Lambert W.
https://img.shields.io/badge/Nexus-Quantum-00ff9d?style=for-the-badge&logo=target&logoColor=black
https://img.shields.io/badge/Bash-5.0+-4EAA25?style=for-the-badge&logo=gnu-bash&logoColor=white
https://img.shields.io/badge/Local--First-100%25-00d4ff?style=for-the-badge&logo=shield&logoColor=black
https://img.shields.io/badge/License-MIT-blue?style=for-the-badge
🧬 Overview
Le Nexus Predictive OOM Killer n'est pas un simple script de nettoyage de cache. C'est un gestionnaire de mémoire cognitif.
Là où le noyau Linux standard (OOM Killer) attend que la mémoire soit pleine pour tuer un processus au hasard (souvent votre IDE ou votre serveur d'IA), Nexus calcule une courbe exponentielle prédictive pour anticiper la saturation. Il purge les caches avant que le système ne devienne instable, et protège les processus vitaux (Ollama, Aether, Node.js).

Règle de Nexus : Ne tue pas quand c'est trop tard. Prédit et agis avant.
⚙️ L'Équation Mathématique

Le script utilise une fonction de puissance pour calculer un score de saturation SS basé sur le pourcentage de RAM utilisée (pp) :
S=(p100−p)3.9
S=(100−p​)3.9

Cette quation crée une courbe de résonance :
    À 20% de RAM, le score est proche de 0 (Système stable).

    À 80% de RAM, le score atteint ~10 (Mode Predict : purge des caches).

    À 90% de RAM, le score explose à ~122 (Mode Killer : prgraph TD
    A[Calcul de S] --> B{S < 10 ?}
    B -->|Oui| C[MODE NORMAL]
    B -->|Non| D{S < 100 ?}
    D -->|Oui| E[MODE PREDICT]
    E --> F[Purge des caches RAM]
    D -->|Non| G[MODE KILLER]
    G --> H[Protection de Ollama/Aether]
    G --> I[Ciblage des processus non-critiques]
    
    style C fill:#00ff9d,color:#000
    style E fill:#ffaa00,color:#000
    style G fill:#ff2d55,color:#fffotection absolue).

Le choix de l'exposant 3.9 est calibré pour déclencher l'alerte juste avant que le noyau Linux ne commence à swapper (ce qui ralentit tout le PC).
