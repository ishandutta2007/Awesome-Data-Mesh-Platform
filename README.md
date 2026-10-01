# Awesome-Data-Mesh-Platform

## Top Data Mesh Platforms Ecosystem

**Curated List of SaaS Products & Open-Source GitHub Projects**

*Focused on Domain-Oriented Data Products, Federated Governance, Self-Serve Platforms, Metadata & Mesh Enablement*

**Last updated: October 2026**



This repository tracks notable **SaaS platforms** and **open-source projects** that enable **Data Mesh**. Data mesh is an organizational and architectural approach—domain ownership, data as product, self-serve platform, and federated governance—supported by catalogs, query engines, observability, and product tooling.



**Examples** include Nextdata, Onehouse, Starburst, DataHub, Acryl, Atlan, Collibra, Monte Carlo, Bigeye, Secoda, Starburst Galaxy, DataKitchen, and Thoughtworks Data Mesh Accelerator (the category leaders and enablers).



**Open-source emphasis**: There is no single “data mesh product,” but strong open platforms underpin mesh implementations. **DataHub**, **OpenMetadata**, **Open Data Mesh** tooling, and open query/lineage stacks are central. This section is heavily expanded.



Contributions welcome! Open a PR to add/update entries. Keep descriptions factual and link to official sites.



## Table of Contents

- [SaaS/Hosted Platforms](#saas-products)

- [Open-Source GitHub Projects](#open-source-github-projects)

- [How to Contribute](#how-to-contribute)

- [Disclaimer](#disclaimer)



## SaaS/Hosted Platforms

- **[Nextdata](https://www.nextdata.com/)**  

  Platform oriented toward data products and mesh-style domain ownership and self-serve data delivery.



- **[Onehouse](https://www.onehouse.ai/)**  

  Lakehouse and data platform capabilities used to support domain data products and mesh architectures.



- **[Starburst / Starburst Galaxy](https://www.starburst.io/)**  

  Federated SQL (Trino-based) platform enabling self-serve access across distributed domain data sources without centralizing copies.



- **[DataHub (Managed / Acryl)](https://datahubproject.io/)**  

  Commercial and managed offerings around DataHub for metadata, lineage, and data product discovery in mesh environments.



- **[Acryl](https://www.acryldata.io/)**  

  Commercial steward of DataHub Cloud—metadata platform supporting discovery, governance, and mesh-scale operations.



- **[Atlan](https://atlan.com/)**  

  Active metadata platform widely used as the discovery and collaboration layer for data mesh and data products.



- **[Collibra](https://www.collibra.com/)**  

  Enterprise data governance platform supporting federated stewardship and policy in mesh operating models.



- **[Monte Carlo](https://www.montecarlodata.com/)**  

  Data observability platform that provides trust signals and reliability for domain data products.



- **[Bigeye](https://www.bigeye.com/)**  

  Data observability focused on monitoring quality and freshness across distributed data products.



- **[Secoda](https://www.secoda.co/)**  

  AI-assisted catalog and knowledge platform used for discovery and documentation in mesh-style teams.



- **[DataKitchen](https://datakitchen.io/)**  

  DataOps and mesh-oriented platform for orchestration, testing, and product lifecycle management.



- **[Thoughtworks Data Mesh Accelerator](https://www.thoughtworks.com/)**  

  Consulting-led accelerator and tooling patterns for adopting data mesh practices (not a single packaged product).



## Open-Source GitHub Projects

- **[DataHub](https://github.com/datahub-project/datahub)**  

  Leading open-source metadata platform for discovery, lineage, ownership, and data product context—core to many mesh implementations.



- **[OpenMetadata](https://github.com/open-metadata/OpenMetadata)**  

  Open-source context and catalog platform with data products, domains, contracts, lineage, and governance features.



- **[Open Data Mesh Platform](https://github.com/opendatamesh-initiative/odm-platform)**  

  Open platform for managing the lifecycle of data products in a mesh architecture using data product descriptors.



- **[Trino](https://github.com/trinodb/trino)**  

  Open-source distributed SQL engine (foundation of Starburst) enabling federated query across domain data sources.



- **[OpenLineage](https://github.com/OpenLineage/OpenLineage)**  

  Open standard for lineage collection that supports impact analysis and trust across domain pipelines.



- **[dbt](https://github.com/dbt-labs/dbt-core)**  

  Open transformation framework widely used by domain teams to build versioned, tested data products.



- **[Apache Iceberg / lakehouse open formats](https://github.com/apache/iceberg)**  

  Open table formats that enable domain teams to own data products on shared storage with interoperability.



- **[Documentation and DataHub / OpenMetadata mesh playbooks](https://datahubproject.io/docs/)**  

  Guides for modeling domains, data products, ownership, and federated governance on open platforms.



- **[Self-serve platform patterns](https://github.com/)**  

  Reference architectures combining catalog + federated query + observability for mesh foundations.



- **[Data product descriptor and contract open specs](https://github.com/)**  

  Community specifications for defining and publishing data products in a mesh.



### Additional Strong Open-Source Options

- Using **DataHub** or **OpenMetadata** as the mesh metadata and discovery backbone.

- Enabling federated access with **Trino**.

- Building domain data products with **dbt** and open table formats.

- Accepting that enterprise packaging, multi-domain operating models, and full commercial support still drive many organizations to Atlan, Collibra, Starburst Galaxy, Monte Carlo, Acryl, etc.

- Focusing open-source efforts on metadata ownership, federated query, and data product standards.



**Frameworks for building custom systems**: Catalog domains and products in DataHub/OpenMetadata → serve data via Trino or lakehouse → transform with dbt → monitor with open observability → govern via federated policies. Suitable for platform teams adopting mesh. Large enterprises often layer commercial governance and observability on top.



## How to Contribute

1. Fork the repo.

2. Add/edit entries in `README.md` (follow existing format).

3. Include: name, link, 1–2 sentence description, and whether it's SaaS or open-source.

4. Submit PR with a short explanation.



Star the repo if you find it useful!



## Disclaimer

- This is a **community-curated** list — not exhaustive and not an endorsement.

- Data mesh is primarily an operating model; tools enable but do not guarantee successful adoption. This list is not architectural or organizational advice.



---

**Made for data platform teams, domain owners, and open mesh advocates.**

Let's keep data products owned, discoverable, and as open as practical.
