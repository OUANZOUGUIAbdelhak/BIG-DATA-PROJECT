# Big Data – Linked Open Data & SPARQL

## 📌 Project Overview

This project is a **Big Data practical assignment** focused on **Linked Open Data (LOD)** and the **SPARQL query language**, using **DBpedia** and other open linked data sources.

The main objective is to explore RDF data, understand semantic web concepts, and write SPARQL queries to extract meaningful information from large, structured knowledge graphs.

This work is based on a practical lab designed by **Stéphane Derrode & Lamia Derrode (Centrale Lyon – Dept. Mathematics & Computer Science)**.

---

## 🎯 Objectives

* Answer **14 SPARQL queries** using the DBpedia Linked Open Data base
* Learn how to navigate RDF vocabularies and ontologies
* Use a SPARQL client to query remote endpoints
* Design **one original SPARQL query** on a Linked Open Data source **other than DBpedia**

---

## 🛠️ Technologies & Tools

* **SPARQL 1.1** – Query language for RDF
* **DBpedia** – Linked Open Data knowledge base
* **RDF / RDFS / OWL** – Semantic Web standards
* **YASGUI** – Lightweight SPARQL web client
* **diagram.net** – RDF graph visualization

---

## 🌐 SPARQL Endpoints

* **DBpedia**: [http://dbpedia.org/sparql](http://dbpedia.org/sparql)
* **Nobel Prize Dataset**: [http://data.nobelprize.org/sparql](http://data.nobelprize.org/sparql)
* **YAGO**: [https://yago-knowledge.org/sparql](https://yago-knowledge.org/sparql)
* **Wikidata**: [https://query.wikidata.org/](https://query.wikidata.org/)
* **Other endpoints** are listed in the resources section below

---

## 📚 RDF Prefixes Used

```sparql
PREFIX foaf: <http://xmlns.com/foaf/0.1/>
PREFIX rdf:  <http://www.w3.org/1999/02/22-rdf-syntax-ns#>
PREFIX rdfs: <http://www.w3.org/2000/01/rdf-schema#>
PREFIX dbo:  <http://dbpedia.org/ontology/>
PREFIX dbr:  <http://dbpedia.org/resource/>
PREFIX xsd:  <http://www.w3.org/2001/XMLSchema#>
```

---

## 🧪 Practical Work – DBpedia Queries

The following SPARQL queries are implemented in this project:

1. Retrieve all **people born in Lyon**
2. Retrieve **names and URLs** of people born in Lyon (alphabetical order)
3. Filter names **without commas**
4. Display **names and birth dates**
5. People born **after 1900**
6. People born after 1900 with **optional death date**
7. People **born and dead in Lyon**
8. People born in Lyon but **dead outside France**
9. French cities whose **mayor is native**
10. French mayors **born outside France**
11. Mayors born **outside the country they govern**
12. Count of French mayors born outside France
13. Number of natives per French city (sample of 10)
14. Top 10 French cities with the **highest number of natives** in DBpedia

Each query respects SPARQL 1.1 standards and can be tested directly on the DBpedia endpoint.

---

## ✨ Original Query (Linked Open Data)

In addition to DBpedia queries, this project includes **one original SPARQL query** designed on a different Linked Open Data base.

### Requirements:

* Use a **non-DBpedia LOD dataset** (e.g. Nobel Prize, YAGO, DBLP, BNF, OpenStreetMap, etc.)
* Clearly specify:

  * The SPARQL endpoint
  * The RDF schema used
  * The SPARQL query
  * A sample of results

---

## 📝 Project Structure (Suggested)

```
├── queries/
│   ├── query01_lyon_birth.sparql
│   ├── query02_names.sparql
│   ├── ...
│   └── query14_top_cities.sparql
├── original_query/
│   ├── endpoint.txt
│   ├── schema.png
│   └── query.sparql
├── report/
│   └── report.pdf
└── README.md
```

---

## 🔎 Useful Resources

* DBpedia: [https://www.dbpedia.org/](https://www.dbpedia.org/)
* SPARQL 1.1 Specification: [https://www.w3.org/TR/sparql11-query/](https://www.w3.org/TR/sparql11-query/)
* SPARQL Cheat Sheet: [https://www.iro.umontreal.ca/~lapalme/ift6281/sparql-1_1-cheat-sheet.pdf](https://www.iro.umontreal.ca/~lapalme/ift6281/sparql-1_1-cheat-sheet.pdf)
* YASGUI SPARQL Client: [https://yasgui.triply.cc/](https://yasgui.triply.cc/)
* Prefix lookup: [http://prefix.cc/](http://prefix.cc/)
* Linked Open Data Cloud: [https://lod-cloud.net/](https://lod-cloud.net/)

---

## 👤 Author

* **Course authors**: Stéphane Derrode & Lamia Derrode (Centrale Lyon)
* **Student project**: *Your Name*

---

## 📜 License

This project is intended for **educational purposes only**.

---

## ✅ Notes

* All queries follow SPARQL 1.1 standards
* The project emphasizes **query correctness**, **readability**, and **originality**
* Any form of plagiarism may result in a zero grade

---

Happy querying 🚀
