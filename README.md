# ma-documentation-pr3
RAPPEL DU CONTEXTE 
Issu de la fusion de PRO-IT (infogérance, 35 personnes) et NET-SOLUTIONS (réseaux & 
cybersécurité, 15 personnes), le groupe NEXA-CLOUD a pour ambition de lancer une 
offre de Cloud Privé Managé destinée aux PME et ETI régionales, dans un délai de 6 
mois, avec un budget global de 850 000 € et un SLA cible de 99,9 %. 
En tant que Responsable des Opérations / Chef de Projet SI, la mission consiste à 
structurer, planifier et piloter cette transformation selon 4 dimensions : stratégiques, 
techniques, organisationnelles et humaines. 
PARTIE 1 — NOTE DE CADRAGE SYNTHÉTIQUE DU PROJET (C25) 
1.1 Objectifs et Exigences du Projet 
Objectif stratégique principal : Créer et commercialiser une offre Cloud Privé Managé 
souverain à destination des PME/ETI régionales sous la marque NEXA-CLOUD. 
Objectifs opérationnels : 
• Déployer une infrastructure cloud privée hautement disponible (SLA 99,9 %) 
• Mettre en place une supervision 24/7 des systèmes hébergés 
• Industrialiser les processus via Infrastructure as Code (IaC) 
• Fusionner les cultures et les équipes issues de PRO-IT et NET-SOLUTIONS 
• Former les collaborateurs aux nouvelles technologies cloud 
Exigences principales : 
• SLA contractuel ≥ 99,9 % de disponibilité 
• Conformité RGPD et sécurité des données souveraines 
• Mise en production officielle en 6 mois (date de démarrage : Février 2026) 
• Budget maximum : 850 000 € (dérive > 5 % soumise à arbitrage direction) 
1.2 Périmètre du Projet 
Dans le périmètre (inclus) : 
• Conception et déploiement de l’architecture cloud privée 
• Mise en place des outils d’automatisation (IaC, Terraform, Ansible) 
• Déploiement d’une supervision 24h/24 (surveillance continue) 
• Structuration de la gouvernance et des processus 
• Formation et montée en compétences des équipes 
• Recrutement d’un Lead Architecte Cloud & Automatisation 
Hors périmètre (exclusions) : 
• Migration des clients existants PRO-IT (hors périmètre phase 1) 
• Développement d’une offre Cloud Public 
• Refonte complète du SI interne des entités fusionnées 
• Intégration de sites multi-régionaux (périmètre régional uniquement) 
1.3 Contraintes du Projet — Triangle Projet 
Dimension 
Contrainte 
Délais 
Détail 
6 mois maximum 
Coûts 
Mise en production 
officielle à M+6 (août 2026) 
850 000 € 
Périmètre 
Réserve de risque incluse ; 
dérive >5 % Arbitrée 
Direction 
PME/ETI régionales 
1.4 Méthodologie de Gestion de Projet 
Méthode retenue : Hybride (Prédictif + Agile) 
Cloud privé souverain 
uniquement, pas d’offre 
publique 
Justification : Le projet NEXA-CLOUD présente deux natures distinctes : 
• Les phases de cadrage, infrastructure et déploiement physique ont une 
nature prédictive (jalons fixes, dépendances séquentielles, contrainte 
budgétaire forte). 
• Les phases d’automatisation, de tests et de mise au point requièrent 
une agilité (itérations courtes, ajustements fréquents, équipes techniques 
autonomes). 
La méthode hybride permet d’allier la rigueur du cycle prédictif (respect du délai de 6 
mois) à la flexibilité agile pour les sprints de développement IaC. 
Date de démarrage : Février 2026 
1.5 Macro-Planification du Projet 
Phase 
Activité principale 
Jalon 
Durée 
Phase 1 
Cadrage & structuration de la 
gouvernance 
Gouvernance validée 
Mois 1 
Phase 2 
Design technique & architecture cible Architecture validée 
Mois 2 
Phase 3 
Déploiement de l'infrastructure 
Infra déployée 
Mois 3 
Phase 4 
Automatisation & supervision 
IaC + supervision 
opérationnels 
Phase 5 
Mois 4 
Tests & validation SLA + Exploitation 
(formation, documentation) 
SLA ≥ 99,9% + équipes 
prêtes 
Mois 5 
Phase 6 
Mise en production officielle 
Go/No Go → MEP 
Mois 6 
1.6 Gouvernance du Projet 
Ressources identifiées : 
• 1 Chef de Projet SI / Responsable des Opérations (rôle candidat) 
• 1 Architecte Lead Cloud & Automatisation (à recruter) 
• Équipes techniques PRO-IT (infrastructure on-premise → reconversion cloud) 
• Équipes réseau & sécurité NET-SOLUTIONS 
• Direction générale NEXA-CLOUD (projet sponsor) 
• Cabinet externe STRAT-IT Consulting (conseil) 
Matrice RACI — Responsabilités clés : 
Livrable / 
Activité 
Chef de 
Projet 
Architecte 
principal 
Équipe 
Technique Réalisation Conseil 
Note de 
cadrage R/A C I A C 
WBS & 
Planification R/A C C I I 
Déploiement 
infra I R/A R I C 
Supervision 
24h/24 et 
7j/7 
A R R/C I C 
Équipes de 
formation A R C I I 
Mise en 
production R/A R R A C 
 
R = Réalisateur, A = Approbateur, C = Consulté, I = Informé 
Tableau de gouvernance : 
Instance Fréquence Participants Objectif 
Comité Stratégique Mensuel 
Direction + Chef de 
Projet 
Décisions et 
arbitrages 
Comité de Pilotage Bi-mensuelle 
Chef de Projet + 
Leads 
Suivi avancement, 
risques 
Comité Projet 
(opérationnel) Hebdomadaire 
Techniques des 
équipes 
Coordination 
opérationnelle 
 
1.7 Analyse des Risques (6 risques identifiés) 
1.8 Budget Prévisionnel (Postes Principaux) 
Poste de coût 
Estimation 
Serveurs d’infrastructure & matériel 
280 000 € 
Licences logicielles (hyperviseur, 
supervision, IaC) 
120 000 € 
Architecte principal du recrutement 
45 000 € 
Techniques des équipes de formation 
60 000 € 
Conseil / accompagnement externe 
80 000 € 
Réseau & sécurité (pare-feu, 
interconnexions) 
100 000 € 
Frais divers et coordination projet 80 000 € 
Réserve de risque (10 %) 85 000 € 
TOTAL 850 000 € 
 
PARTIE 2 — PLAN PROJET : DISPOSITIF DE PILOTAGE ET CONTRÔLE (C25 & C26) 
2.1 Structure de décomposition du travail (WBS — 3 niveaux maximum) 
 
Lot (N1) Sous-lot (N2) Activités (N3) 
1. Cadrage & 
Gouvernance 
1.1 Analyse & validation des 
objectifs 
Analyse du contexte, validation des objectifs 
stratégiques 
 1.2 Structuration de la 
gouvernance 
Définition RACI, organigramme, rôles et 
responsabilités 
 1.3 Note de cadrage Rédaction et validation de la note de cadrage 
2. Architecture 2.1 Conception architecture 
cible 
Conception de l'architecture cloud privée 
 2.2 Exigences sécurité & 
RGPD 
Définition des exigences sécurité et conformité 
RGPD 
 2.3 Validation architecture Validation de l'architecture par les parties prenantes 
3. Infrastructure 3.1 Extension datacenter Extension et configuration du datacenter 
 3.2 Équipements réseau Installation des équipements réseau 
 3.3 Virtualisation Déploiement de la virtualisation 
4. 
Automatisation 
4.1 IaC Mise en place de l'Infrastructure as Code (Terraform, 
Ansible) 
 4.2 Supervision 24/7 Déploiement de la supervision 24/7 (Zabbix, 
Prometheus, Grafana) 
 4.3 Alertes & escalade Configuration des alertes et procédures d'escalade 
5. Tests & 
Validation 
5.1 Tests techniques Tests techniques (charge, performance, sécurité) 
 5.2 Tests supervision Tests de supervision et continuité de service 
 5.3 Validation SLA Validation SLA ≥ 99,9% 
6. Exploitation 6.1 Formation équipes Formation des équipes exploitation 
 6.2 Documentation Documentation technique et opérationnelle 
7. MEP 7.1 Go/No Go Réunion de validation Go/No Go officielle 
 7.2 Mise en production Bascule en production et activation supervision 
 
2.2 Planning Gantt — Représentation sur 6 Mois 
Activité M1 M2 M3 M4 M5 M6 
Note de cadrage & gouvernance ██      
Technique de conception ██ ██     
Architecte principal du recrutement ██ ██     
Équipes de formation  ██ ██    
Infrastructures de déploiement   ██ ██   
Automatisation IaC    ██ ██  
Supervision 24h/24 et 7j/7    ██ ██  
Conduite du changement ██ ██ ██ ██ ██  
Phase pilote & tests     ██  
Go/No Go & MEP officielle      ██ 
Jalons clés : ◆M+1 Gouvernance validée | ◆M+2 Conception approuvée | ◆M+4 Infra 
déployée | ◆M+5 Pilote validé | ◆M+6 MEP officielle 
2.3 Dispositif de Suivi Budgétaire 
Le suivi budgétaire repose sur un mécanisme de Earned Value Management 
(EVM) simplifié, avec les indicateurs suivants : 
Indicateur Formule Seuil d’alerte 
Taux de consommation 
budgétaire 
Dépenses réelles / Total du 
budget 
> 110 % du prévu à 
date 
Variance de coût (CV) Valeur acquise – Coût réel Négatif = dépassement 
Indice de performance coût (CPI) Valeur acquise / Coût réel < 0,95 = alerte 
 
Mécanisme de reporting : 
• Tableau de bord mensuel présenté au Comité de Pilotage 
• Alerte immédiate si dérive budgétaire > 5 % (arbitrage direction) 
• Réserve de risque de 85 000 € mobilisable sur décision du Comité Stratégique 
Tableau de suivi budgétaire mensuel (modèle) : 
Poste Budget Initial M1 M2 M3 M4 M5 M6 Total Réel Écart 
Infrastructures 280 000 € - 30K 80K 120K 30K 20K — — 
Licences 120 000 € 10K 10K 30K 30K 20K 20K — — 
RH/Recrutement 105 000 € 20K 25K 20K 20K 10K 10K — — 
Conseil 80 000 € 20K 20K 15K 10K 10K 5K — — 
Réserve risquée 85 000 € — — — — — — — — 
 
 
2.4 Tableau de Bord de Pilotage (3 KPI Maximum) 
KPI 
Définition 
Mesure 
KPI 1 — % 
Avancement projet 
Rapport entre les 
livrables validés et les 
livrables totaux 
prévus 
Fréquence 
Cible 
(Livrables validés / 
Total livrables) × 
100 
KPI 2 — Taux de 
disponibilité infra 
pilote 
Disponibilité mesurée 
de la plateforme 
cloud en phase pilote 
Bi
mensuelle 
≥ 95 % 
à M+6 
Temps d’activité / 
Températures 
totales × 100 
KPI 3 — Indice de 
consommation 
budgétaire 
Rapport dépenses 
réelles / budget 
planifié à date 
Quotidien 
(dès M+5) 
≥ 99,9 
% 
Dépenses réelles / 
Budget planifié 
2.5 Instances de Pilotage (3 maximum) 
Instance 1 — Comité Stratégique (COSTRA) 
• Fréquence : Mensuel 
Mensuel 
• Participants : Direction NEXA-CLOUD, Chef de Projet, Architecte Principal 
• Objectif : Arbitrages budgétaires, décisions stratégiques (Go/No Go étapes), 
gestion des risques majeurs 
Instance 2 — Comité de Pilotage (COPIL) 
• Fréquence : Bi-mensuel (toutes les 2 semaines) 
• Participants : Chef de Projet, responsables de lots (infra, sécurité, formation) 
• Objectif : Suivi de l’avancement des livrables, gestion des risques opérationnels, 
revue des KPI 
Instance 3 — Rituels Opérationnels (technique debout) 
• Fréquence : Hebdomadaire 
• Participants : Équipes techniques (PRO-IT + NET-SOLUTIONS fusionnées) 
• Objectif : Coordination quotidienne des tâches, levée des blocages, 
synchronisation inter-équipes 
Entre 
0,95 et 
1,05 
2.6 Arbitrage Stratégique — Supervision 24/7 : Internaliser ou Externaliser ? 
Contexte : La supervision 24/7 est un élément critique pour garantir le SLA de 99,9 % de 
l’offre NEXA-CLOUD. 
Analyse des options : 
Critère Internalisation 
Externalisation (SOC/NOC 
externe) 
Coût initial Élevé (recrutements, outils) Moyen (abonnement mensuel) 
Coût récurrent Faible (équipe interne) Élevé (contrat SLA) 
Compétences 
disponibles 
    Insuffisantes (IaC, 
cloud)    Immédiatement disponibles 
Délai de déploiement Long (6-9 mois) Court (< 2 mois) 
SLA d’alignement 99,9 % Risqué à court terme Sécurisé immédiatement 
Souveraineté des 
données    Maximale     Paliers de dépendance 
Recommandation : Option hybride — Externalisation transitoire + internalisation 
progressive 
Compte tenu des contraintes calendaires (mise en production à M+6), du déficit de 
compétences cloud identifié dans les annexes, et des exigences SLA à 99,9 %, la 
solution recommandée est l’externalisation de la supervision 24/7 auprès d’un 
prestataire NOC certifié pour les 12 premiers mois, avec un objectif d’internalisation 
totale à 18-24 mois post-MEP, une fois les équipes formées et le Lead Architecte 
opérationnel. 
Avantages : garantie immédiate du SLA, réduction du risque projet, délai respecté. 
Limites : coût récurrent estimé à 8 000-12 000 €/mois, dépendance temporaire à un 
tiers. 
Risque : transfert de connaissance à organiser dès M+6 pour ne pas créer de 
dépendance pérenne. 
PARTIE 3 — CONDUITE DU CHANGEMENT ET MISE EN PRODUCTION (C27) 
3.1 Analyse des Impacts Organisationnels 
La transformation vers NEXA-CLOUD génère trois niveaux d’impact : 
Impact 1 — Fusion des équipes PRO-IT et NET-SOLUTIONS 
• Résistances potentielles : crainte de perte de poste, différences de culture 
d’entreprise (infogérance vs cybersécurité), méfiance inter-équipes 
• Risques organisationnels : conflits de gouvernance, silotage, perte de 
productivité pendant la transition 
• Impact sur les méthodes de travail : processus harmonisés à créer, outils 
communs à déployer 
Impact 2 — Évolution vers un modèle d’exploitation cloud 
• Résistances : équipes PRO-IT habituées au on-premise, réticences à apprendre 
IaC/Terraform 
• Risques : retards de déploiement si les équipes ne montent pas en compétences 
à temps 
• Impact : nouvelles pratiques DevOps à intégrer, fin du modèle « maintenance 
physique » 
Impact 3 — Introduction de la supervision 24h/24 et 7j/7 
• Résistances : astreintes et horaires atypiques non anticipés par les 
collaborateurs 
• Risques : turnover, épuisement, conflicts RH 
• Impact : organisation du travail à revoir (rotations, astreintes, contrats) 
3.2 Plan de Conduite du Changement 
Parties prenantes impactées : 
Partie Prenante 
Impact 
Niveau de résistance 
estimé 
Équipes techniques 
PRO-IT 
Fort 
Élevé 
Actions prioritaires 
Formation IaC, accompagnement 
individuel 
Équipes réseau NET
SOLUTIONS 
Moyen Moyen 
Intégration culturelle, partage de 
pratiques 
Partie Prenante Impact 
Niveau de résistance 
estimé Actions prioritaires 
Direction NEXA-CLOUD Faible Faible 
Communication régulière, 
reporting KPI 
Clients PRO-IT existants Moyen Faible 
Communication proactive, 
garantie continuité 
Actions de communication interne : 
1. Kick-off projet (M+1) : réunion plénière de lancement avec toutes les équipes, 
présentation de la vision NEXA-CLOUD 
2. Newsletter mensuelle : bilan d’avancement envoyé à tous les collaborateurs 
3. Ateliers de co-construction (M+2 à M+4) : ateliers inter-équipes pour définir les 
nouveaux processus ensemble 
4. Sessions Q&A bi-mensuelles : espace d’expression et de réponse aux 
inquiétudes 
Dispositifs d’accompagnement des équipes : 
• Désignation de Champions du changement dans chaque équipe 
(ambassadeurs internes) 
• Coaching individuel pour les collaborateurs les plus résistants 
• Création d’un groupe de travail fusion réunissant des membres PRO-IT et NET
SOLUTIONS 
3.3 Organisation de la Mise en Production 
Étapes clés de la MEP : 
Étape Synchronisation Responsable Validation 
Tests d’intégration 
complets M+5 semestre 1 Architecte principal Rapport de tests 
Tests de charge (SLA 99,9 
%) M+5 semestre.2 Technique d’équipe 
Métriques uptime > 
99,9 % 
Étape Synchronisation Responsable Validation 
Validation sécurité RGPD M+5 semestre 3 DSI + DPO Validation de l’audit 
Finale Go / No Go M+5 semestre Comité Stratégique Décision formelle 
Bascule en production M+6 semestre 1 Chef de Projet MEP en vigueur 
Clients de 
communication M+6 semestre 2 
Direction 
commerciale Annonce officielle 
Modalités de validation Go / No Go : 
• Go : SLA mesuré ≥ 99,9 %, zéro vulnérabilité critique, équipes formées, 
documentation livrée 
• No Go : Si l’un des critères ci-dessus n’est pas atteint → délai de 2 semaines 
supplémentaires maximum, puis arbitrage direction 
Modalités de coordination inter-équipes : 
• War room technique les 3 jours précédant la MEP 
• Astreinte de crise H24 pendant les 72h post-MEP 
• Plan de rollback documenté si incident critique 
PARTIE 4 — DÉVELOPPEMENT DE L’INFRASTRUCTURE (C28) 
4.1 Diagnostic des Écarts de Compétences 
À partir des annexes (Annexe 7 — Cartographie des compétences, Annexe 8 — Activités 
projet) : 
Compétence requise pour NEXA-CLOUD 
Présence 
PRO-IT 
Présence NET
SOLUTIONS Écart 
Compétence requise pour NEXA
CLOUD 
Présence 
PRO-IT 
Présence NET
SOLUTIONS Écart 
L’infrastructure en tant que code 
(Terraform/Ansible)   Absent   Absent 
  
Critique 
Compétence requise pour NEXA
CLOUD 
Présence 
PRO-IT 
Présence NET
SOLUTIONS Écart 
Architecture Cloud Privée (KVM, 
Proxmox, VMware)     Partielle   Absent 
  
Critique 
Supervision 24h/24 / Surveillance 
(Zabbix, Prometheus)   Absent     Partielle 
  
Majeur 
Sécurité réseau & firewall   Absent    Présente 
   
Acquis 
Virtualisation sur site    Présente   Absent 
    
Partielle 
DevOps / CI-CD   Absent   Absent 
  
Critique 
4.2 Plan de Montée en Compétences 
Objectifs de formation : 
• Maîtriser Terraform et Ansible pour l’automatisation IaC 
• Acquérir les bases de l’architecture cloud privée 
• Opérer les outils de supervision (Zabbix / Prometheus / Grafana) 
• Comprendre les pratiques DevOps et CI/CD 
Plan de formation — Tableau de déploiement : 
Formation Profils concernés Modalité Calendrier 
Coût 
estimé 
Terraform & Ansible 
fondamentaux 
Équipes PRO-IT (6 
pers.) 
Externe 
certifiante M+2 à M+3 18 000 € 
Formation Profils concernés Modalité Calendrier 
Coût 
estimé 
Architecture Cloud Privée 
Techniques de 
direction (3 pers.) 
Externe + e
learning M+2 9 000 € 
Supervision 24h/24 
(Zabbix/Prometheus) 
Équipes mixtes (5 
pers.) 
Interne 
(Architecte 
principal) M+3 à M+4 5 000 € 
Sécurité Cloud & RGPD 
Tous les 
collaborateurs (10 
pers.) E-learning M+1 8 000 € 
DevOps & Initiation CI/CD 
Équipes techniques 
(8 pers.) Externe M+3 20 000 € 
Formation totale : ~60 000 € (cohérent avec le budget prévisionnel) 
4.3 Mesure de l’Efficacité des Actions 
Indicateur Description Cible Mesure 
Techniques de 
progression 
% de collaborateurs ayant validé leur 
certification/formation ≥ 80 % 
Aileron 
M+4 
Capacité à 
respecter les SLA 
Tests techniques de simulation SLA 
avant MEP SLA ≥ 99,9 % M+5 
Autonomie 
technique avant 
MEP 
Capacité des équipes à opérer sans 
prestataire externe 
100 % des 
opérations 
critiques M+6 
4.4 Dynamique managériale — 2 Rituels Proposés 
Rituel 1 — « Cloud Weekly » (Hebdomadaire) 
• Objectif : Renforcer la coordination technique entre les équipes fusionnées 
• Format : Réunion de 45 minutes chaque lundi matin, en présentiel ou visio 
• Contenu : Revue des tâches de la semaine, partage des blocages techniques, 
alternance de présentations courtes par les collaborateurs sur les nouvelles 
compétences acquises 
• Animateur : Lead Architecte Cloud & Automatisation en rotation avec Chef de 
Projet 
Rituel 2 — « Revue de Performance Collective » (Mensuel) 
• Objectif : Favoriser l’alignement et la performance collective, mesurer les progrès 
• Format : Réunion de 2h le dernier vendredi de chaque mois 
• Contenu : Présentation des KPI du mois, reconnaissance des succès collectifs, 
identification des axes d’amélioration, moment de cohésion inter-équipes (PRO
IT + NET-SOLUTIONS) 
• Animateur : Chef de Projet SI avec la Direction 
PARTIE 5 — RECRUTEMENT (C29) 
5.1 Justification du Besoin — Lead Architecte Cloud & Automatisation 
Écarts organisationnels et techniques identifiés : 
• Absence totale de compétence IaC au sein des deux entités fusionnées (Annexe 
7) 
• Impossibilité de déployer l’infrastructure NEXA-CLOUD dans les délais sans 
expertise cloud native 
• Besoin d’un référent technique pour piloter la formation des équipes en interne 
Exigences techniques du projet : 
• Architecture cloud privée multi-tenant : compétence non disponible en interne 
• Automatisation Terraform/Ansible : aucun profil qualifié dans les équipes 
actuelles 
• Supervision 24/7 (SLA 99,9 %) : expertise nécessaire dès la phase de conception 
Contraintes calendaires : 
• Recrutement à finaliser avant M+2 pour être opérationnel lors du déploiement 
(M+3 à M+4) 
• Sans ce recrutement, le délai de 6 mois ne peut être tenu 
5.2 Fiche de Poste — Architecte Lead Cloud & Automatisation 
Intitulé du poste : Architecte principal Cloud & automatisation 
Entreprise : NEXA-CLOUD (fusion PRO-IT + NET-SOLUTIONS) 
Localisation : Région [à préciser selon localisation réelle de NEXA-CLOUD] 
Type de contrat : CDI — Statut Cadre 
Rémunération : 55 000 – 70 000 € brut annuel selon expérience 
Missions principales : 
• Concevoir et déployer l’architecture cloud privée NEXA-CLOUD 
• Piloter la mise en place des outils IaC (Terraform, Ansible, CI/CD) 
• Définir et implémenter la stratégie de supervision 24/7 
• Former et accompagner les équipes techniques (PRO-IT & NET-SOLUTIONS) à la 
montée en compétences cloud 
• Garantir la conformité technique avec les objectifs SLA de 99,9 % 
• Participer aux instances de gouvernance du projet 
Compétences techniques attendues (compétences techniques) : 
• Maîtrise de Terraform et Ansible (IaC) 
• Expérience en architecture cloud privée (KVM, Proxmox, VMware vSphere ou 
OpenStack) 
• Compétences en supervision (Zabbix, Prometheus, Grafana) 
• Connaissance des architectures réseau et sécurité (VLAN, VPN, firewalling) 
• Pratiques DevOps et CI/CD (Jenkins, GitLab CI, ou équivalent) 
• Connaissance RGPD et sécurité des données 
Compétences comportementales : 
• Leadership technique et pédagogie (formation d’équipes) 
• Communication transversale (lien entre équipes techniques et direction) 
• Adaptabilité et gestion du changement 
• Rigueur, autonomie, sens des priorités 
Positionnement dans la gouvernance : 
• Rattachement direct au Responsable des Opérations / Chef de Projet SI 
• Rôle = Réalisateur (R) sur tous les livrables techniques 
• Membre permanent du Comité de Pilotage 
5.3 Processus de Sélection 
Étapes principales : 
1. Publication de l’offre (M+1, sem. 1) : Diffusion sur LinkedIn, APEC, Welcome to 
the Jungle, réseaux partenaires 
2. Tri des candidatures (M+1, sem. 2) : Pré-sélection sur CV (compétences IaC 
obligatoires) 
3. Entretien RH (M+1, semestre 3) : Validation des soft skills, motivation, 
adéquation culturelle 
4. Entretien technique (M+1, sem. 3-4) : Évaluation des compétences techniques 
avec le Chef de Projet SI 
5. Mise en situation professionnelle (M+1, sem. 4) : Étude de cas NEXA-CLOUD 
(proposition d’architecture et démarche IaC) 
6. Décision finale & offre (M+2, sem. 1) 
3 modalités d’évaluation : 
• Test technique écrit : QCM et questions ouvertes sur Terraform, Ansible, 
architecture cloud (durée : 1h) 
• Entretien technique approfondi : Questions sur des cas concrets liés au projet 
NEXA-CLOUD, discussion d’architecture 
• Mise en situation professionnelle : Présenter en 20 minutes une proposition 
d’architecture cloud privée pour NEXA-CLOUD avec une approche IaC 
5.4 Responsabilité Sociétale et Inclusion 
Adaptation aux candidats en situation de handicap : 
• Mise en accessibilité des locaux pour les entretiens (vérification auprès du 
référent handicap) 
• Adaptation des modalités d’évaluation : temps supplémentaire pour les tests 
écrits si nécessaire, format alternatif (oral au lieu d’écrit) selon le handicap 
• Mention RQTH dans l’offre d’emploi : « À compétences égales, priorité aux 
travailleurs handicapés » 
Conformité aux principes d’égalité des chances : 
• Anonymisation des CV lors de la pré-sélection (suppression du nom, âge, photo) 
• Grille d’évaluation standardisée pour tous les entretiens (mêmes critères, même 
pondération) 
• Mixité du jury de recrutement (au moins un homme et une femme dans le panel) 
Alignement avec la démarche RSE de NEXA-CLOUD : 
• Le recrutement d’un Lead Architecte Cloud contribue à la montée en 
compétences des équipes en interne → réduction de la dépendance aux 
prestataires externes 
• Priorité donnée aux profils locaux/régionaux pour ancrer NEXA-CLOUD dans son 
territoire 
• Formation continue post-recrutement intégrée au plan de développement des 
compétences de l’entreprise 
