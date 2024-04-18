# 'Impact Database' - Project Outline

- *In plain language.*

## 💡The 'Big Idea'

Impact investing is a field that aims to bring radical new thinking that touches upon a few fields:

- Development finance 
- Social finance 
- Climate finance
- The investment industry 

**Some of these approaches pose big questions that could radically alter the way in which government and businesses operate:**

- *What if instead of paying for social services, governments paid only for specific defined outcomes ('pay for success, pay for outcomes')?*
- *If we could create the right set of incentives, could governments and private investors pool their resources to achieve more good (social impact bonds and variants)?*
- *We want to lend money to businesses and governments that act sustainably. What if we could agree upon a system that linked the rate of borrowing to the achievement of independently audited objectives (sustainability-linked bonds, sustainability-linked loans)?*
- *What if we could find a way to calculate businesses' impacts on societies and the planet and express them in monetary terms - like financial line items (impact-weighted accounting)?*

To test how well these ideas work, and encourage adoption, the generation and analysis of data is critical!

## 📝 The Little Idea (This One)

**The 'Impact Database' (ImpactDB) will be a data publishing portal that aggregates and presents datasets that are of interest to the impact investing community.** It might also publish analysis based upon those datasets. The Impact Database is not planned as a profit-making entity. 

### Website features (planned, roadmap):

- **Data publication:** Publishing (with permission!) datasets of interest published by third parties. Adding categorisation and tagging for easy navigation. 
- **Versioning**: Tagging the release of third-party datasets according to their release date for those interested in comparing currently-released and historic datasets. 
- **Data dictionaries:** Impact-related data is commonly created by overburdened and understaffed entities who may not have had the time to describe all the variables in their released data. Where this hasn't been undertaken, ImpactDB will try to provide links between datasets and research methodologies. 
- **Data descriptions:** Tagging of data according to file format.
- **Data enrichment:** 1.0 - Suggesting connections between static datasets and dynamic datasets that can be accessed by public APIs (such as Google Finance APIs). 2.0 - Hosting enriched datasets live.
- **Visualisations and blogs**: Sharing visualisations and blogs based on analysed data. 
- **Attribution**: Link to original authors and full attribution.
- **Github ingestion:** Creating a Github repository where those with datasets to share can open pull requests for ingestion into the backend. 

**URL:** Redacted while in staging and under development.

## Platform Evaluation (Ongoing)

Evaluating solutions and installing them is tough work and limited by technical constraints and budget, but this list reflects progress so far in trying to find solutions to integrate (tick = evaluated, probably excluded. There can be only one winner!):

Open-source / self-hosted:

- [x] CKAN
- [x] DKAN
- [ ] Invenio Framework 
- [ ] Amundsen
- [ ] Atlas
- [ ] DataHub
- [ ] Marque
- [x] Open Data Discovery
- [x] Open Metadata 
- [ ] Datasette
- [x] Dataverse

SaaS

## Other Steps To Take 

- [ ] Requesting permission from dataset publishers 
- [ ] Identification of datasets of interest 

## Notes 

I can think of a few ways in which interested data publishers could "self service" the process of syndicating data to the platform:

- Chained database integration
- Direct database access
- Shared backend access