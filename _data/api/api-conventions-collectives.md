---
title: API Conventions collectives
tagline: Retrouvez les conventions collectives d'une entreprise à partir de son numéro SIRET
is_open: 1 # 1 means API is fully open
producer: mtei
keywords:
  - conventions
  - travail
  - entreprise
  - contrat
  - legifrance
  - DSN
  - NAF
  - Sirene
  - Accord
  - droits
  - salarié
  - social
  - établissement
#rate_limiting_resume: 
themes:
  - Entreprise
  - Emploi
  - Administration & législation
contact_link: codedutravailnumerique@travail.gouv.fr
doc_tech_link: https://raw.githubusercontent.com/SocialGouv/recherche-entreprises/master/api/openapi.yaml
datagouv_uuid:
  - 5b7ffc618b4c4169d30727e0
  - 5e7201d522f2a43e9f736a9a
  - 5b7ffc618b4c4169d30727e0
last_update: 23/12/2021
---

L'API Conventions collectives permet de rechercher les conventions collectives d'une entreprise à partir de son SIRET, SIREN ou raison sociale.

### À quoi sert l’API Conventions collectives ?

Chaque entreprise applique des [conventions collectives propres à son secteur d'activité](https://www.service-public.fr/particuliers/vosdroits/F78) (contrat de travail, congés, salaires, hygiène, licenciement, etc...).
Conclues par les organisations syndicales et les groupements d'employeurs, elles varient selon le secteur d'activité et donc selon les entreprises. Cette API permet d'associer une entreprise à des conventions collectves.

<Button href="https://recherche-entreprises.fabrique.social.gouv.fr/">Voir le démonstrateur</Button>

### Quelles sont les données contenues dans l'API Structures de l'inclusion ?

| Donnée                                                                                                                                                                        | usage                                                    |
| ------------------------------------------------------------------------------------------------------------------------------------------------------------------------------ | -------------------------------------------------------- |
| [geo-sirene](https://www.data.gouv.fr/fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/#resource-community-c6006b4d-0b4b-4504-a762-1efe69c7ed18) | Version géocodée du stock des établiseement              |
| [insee-sirene](https://www.data.gouv.fr/fr/datasets/base-sirene-des-entreprises-et-de-leurs-etablissements-siren-siret/)                                                       | Base Sirene des entreprises et de leurs établissements   |
| [siret2idcc](https://www.data.gouv.fr/fr/datasets/liste-des-conventions-collectives-par-entreprise-siret/#_)                                                                   | Lien vers la convention collective                       |
| [kali-data](https://github.com/SocialGouv/kali-data)                                                                                                                           | Informations sur les conventions collectives             |
| [codes-naf](https://github.com/SocialGouv/codes-naf)                                                                                                                           | Liste des codes NAF (Nomenclature d’activités française) |
