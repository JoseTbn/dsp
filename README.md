### **Objectifs du cours:**
- Comprendre les principes fondamentaux de DevSecOps et comment il s'intègre dans la culture DevOps.
- Apprendre des méthodes pratiques pour intégrer la sécurité tout au long du cycle de vie du développement logiciel.
- Acquérir une expérience pratique dans la mise en place de pipelines DevSecOps, de tests de sécurité automatisés et de modélisation des menaces.
- Discuter des études de cas du monde réel et des défis dans la mise en œuvre des pratiques DevSecOps.

### **Agenda du cours:**

#### **Session 1 : Introduction à DevSecOps (1 heure)**
- Vue d'ensemble de DevOps et DevSecOps***.
  - DevOps vs. DevSecOps : Principales différences
  - Importance du "Shift Left" en matière de sécurité
  - Avantages et défis de l'adoption de DevSecOps
- La culture de la sécurité dans le DevOps**
  - Casser les silos entre les équipes de développement, d'exploitation et de sécurité

#### **Session 2 : Pratiques de sécurité à travers le SDLC (1,5 heures)**
- Développement sécurisé
  - Pratiques de codage sécurisées et OWASP Top 10
  - Intégration des tests statiques de sécurité des applications (SAST) dans les pipelines CI/CD
- Modélisation des menaces
  - Comment effectuer une modélisation des menaces au début du cycle de développement durable (SDLC)
  - Exercice pratique : Construction d'un modèle de menace pour un exemple d'application


#### **Session 3 : Sécurité du pipeline CI/CD (1,5 heure)**
- Sécuriser le pipeline CI/CD**
  - Vulnérabilités courantes dans les environnements CI/CD
  - Outils pour la sécurité du pipeline : Jenkins, GitLab, GitHub Actions
- Tests de sécurité automatisés
  - Test dynamique de la sécurité des applications (DAST)
  - Intégration de l'analyse des vulnérabilités dans CI/CD
- Laboratoire pratique
  - Mettre en place un pipeline CI/CD de base avec des contrôles de sécurité en utilisant Jenkins et OWASP ZAP.

#### **Session 4 : Sécurité des conteneurs et Infrastructure as Code (1.5 heures)**
- **Sécurité des conteneurs**
  - Introduction à la conteneurisation et à la sécurité de Docker
  - Vulnérabilités dans les images de conteneurs et remédiation
  - Outils : Clair, Trivy
- Infrastructure en tant que code (IaC)**
  - Considérations de sécurité dans l'IaC (Terraform, Ansible)
  - Laboratoire pratique : Ecrire des scripts Terraform sécurisés


#### **Session 5 : Surveillance, réponse aux incidents et conformité (1,5 heure)**
- **Surveillance de la sécurité et réponse aux incidents**
  - Importance de la journalisation et de la surveillance pour la sécurité
  - Travaux pratiques : Configuration des alertes de sécurité à l'aide de la pile ELK
- Conformité et gouvernance
  - Normes de conformité courantes (GDPR, PCI-DSS, HIPAA)
  - Automatisation des contrôles de conformité dans les pipelines DevSecOps

#### **Session 6 : Études de cas et défis du monde réel (1 heure)**
- Études de cas
  - Analyse d'implémentations DevSecOps réussies et échouées.
- Discussion
  - Défis liés à l'adoption de DevSecOps dans différentes cultures organisationnelles
  - Activité de groupe : Identifier les principaux défis en matière de sécurité et proposer des solutions DevSecOps

### Récapitulation du cours (30 minutes)**
- Résumé et questions-réponses
  - Récapitulation des concepts clés
  - Questions et discussions ouvertes
- Ressources pour un apprentissage plus approfondi
  - Livres, cours et ressources en ligne recommandés

### **Méthodes d'enseignement:**
- Cours magistraux et présentations** pour les connaissances de base.
- **Laboratoires pratiques** pour une expérience pratique des outils et des concepts.
- Discussions en groupe et études de cas** pour relier la théorie aux scénarios du monde réel.

### **Outils utilisés:**
- Jenkins, GitLab/GitHub Actions pour CI/CD
- OWASP ZAP, Clair, Trivy pour les tests de sécurité
- Terraform pour l'IaC
- ELK stack pour la surveillance et la réponse aux incidents

### **Pré-requis:**
- Connaissance de base des processus DevOps et des outils CI/CD.
- Familiarité avec la programmation et les scripts.
