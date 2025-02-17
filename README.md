# 📚 Neurosymbolic AI and the Logic-Knowledge Graph Spectrum
Comparisons, Integrations, and Real-World Trade-offs

---

## 🗒️ Abstract
Neurosymbolic AI is a rapidly evolving and emerging field. In recent works, researchers have proposed several conceptualizations of neurosymbolic AI, yet the field still lacks a unified perspective on how different symbolic formalisms, ranging from traditional predicate logic to description logics and knowledge graph–based models, can effectively integrate with neural networks. This tutorial aims to clarify these options by comparing their relative merits in terms of interpretability, computational feasibility, and real-world scalability. We will show how purely logical systems (e.g., Prolog, Markov Logic), description logics (e.g., OWL-based reasoning), and knowledge graphs (e.g., RDF, property graphs) each contribute distinct advantages in neurosymbolic pipelines, especially in conjunction with large language models (LLMs). By systematically analyzing these approaches through case studies and code demonstrations, attendees will gain a deeper understanding of when, why, and how to integrate logic or KG-based techniques within modern AI applications.

---

## 💡 Intellectual Contributions

* **Knowledge Graphs (KGs)**: Demonstrating how RDF, property graphs, and embeddings handle large-scale, heterogeneous data, offering flexible, machine-friendly interfaces that integrate smoothly with neural encoders and LLMs.
* **Logic-Based Reasoning**: Introducing formalisms (e.g., first-order logic, Markov Logic Networks) that provide strong semantics and provable inference rules, albeit with potential computational overhead for large-scale tasks.
* **Description Logics**: Explaining how OWL and other restricted logics balance expressive power with tractable inference, important for enterprise ontology engineering and domain-specific knowledge representation.

By placing these perspectives side by side, we address a recurring philosophical underpinning –  _symbolic formalisms such as logic, description logics, and KGs as a candidate for hybridization with neural networks, are competing paradigms_, when in fact, they often operate as complementary layers for domain modeling, semantic constraints, and scalable data handling.

---

## 🎯 Tutorial Focus

### 1. Comparitive Foundations
* Overview of multiple frameworks under the neurosymbolic AI umbrella
* Clarification of overlapping theoretical underpinnings (e.g., shared roots in logic), and key differences in practical workflows

### 2. Case Studies and Hands-On Demos on Neurosymbolic AI Implementations
* Healthcare diagnostics (regulatory compliance, patient safety)
* Nutrition recommendation (managing dietary constraints)
* Creative text generation (consistency and narrative logic)
* Each domain demonstrated twice: once with a logic-based solution, once with a KG-based approach, highlighting performance trade-offs and required domain knowledge integration

### 3. Integration with Neural Architectures
* Strategies for bridging neural networks (focused on LLMs) with logical constraints, embeddings, or symbolic queries.
* Discussion of best practices for interpretability, compliance, and extension to real-world tasks and use-case scenarios.

### 4. Common Pitfalls and Future Trends
* Limitations of purely symbolic or purely neural solutions
* Emerging research in neural theorem proving, large-scale knowledge maintenance, and incremental logic/KG updates

---

## 📑 Tutorial Organization and Expected Background

### Timeline
Designed as a 2-hour session, with approximately 10–15 minutes reserved for interactive Q&A, clarifications, and in-depth discussion of attendee queries. If scheduling permits, an extended hands-on demonstration session can be added immediately after, allowing participants to experiment with code examples. Below is a detailed breakdown:

* **Introduction (10 minutes)**
 Historical context of neurosymbolic AI, motivations, relevant literature

* **Logic-Based Methods (20 minutes)**
 Predicate logic, Prolog, Markov Logic Networks. Strengths (formal guarantees) vs. weaknesses (scalability, complexity)

* **Description Logics (15 minutes)**
 OWL profiles, reasoning complexity, enterprise-level ontology management. Trade-offs between expressive power and tractable inference

* **Knowledge Graph Approaches (20 minutes)**
 RDF, property graph models, graph embeddings. Large-scale data handling, flexible queries, synergy with neural models

* **Case Studies (20 minutes)**
 Step-by-step comparisons in healthcare, regulatory compliance, and e-commerce. Live code demos showing logic-based vs. KG-based integrations with LLMs

* **Q&A and Discussion (15 minutes)**
 Summarizing design choices for each symbolic approach, open problems (bridging logic and KGs, neural theorem proving, dynamic knowledge updates)

### Expected Background and Pre-requisites
Attendees are expected to have a basic grounding in machine learning and neural networks, some familiarity with symbolic logic or knowledge representation (a primer will be given), and an interest in practical AI systems that combine data-driven and knowledge-driven methods. This tutorial is geared toward a broad AI audience, including those in NLP, knowledge engineering, and semantic technologies.

---

## 🔖 Presenter's Biographies
* **Yuxin Zi** is a Ph.D. candidate in neurosymbolic AI, focusing on how human intelligence would inspire AI systems. Towards this end, she has incorporated human-curated symbolic knowledge in neural network architectures through a functional modeling perspective. Her goal is to develop neuro-symbolic methods that closely resemble fundamental processes that drive human intelligence.
  
* **Kaushik Roy** is a Ph.D. candidate at the  Artificial Intelligence Institute, University of South Carolina. His research focuses on developing neurosymbolic methods for declarative and process knowledge-infused learning, reasoning, and sequential decision-making, with a particular emphasis on social good applications. His research interests span machine learning, artificial intelligence, and their application in social good settings.
  
* **Amit Sheth** is an educator, researcher, and entrepreneur. He is the founding director of the university-wide AI Institute at the University of South Carolina. He is a Fellow of the IEEE, AAAI, AAAS and ACM, elected for his pioneering and enduring contributions to information integration,  distributed workflow processes, semantics, knowledge-enhanced computing, etc. He has (co-)founded four companies, three of them by licensing his university research outcomes, including the first Semantic Search company in 1999 that pioneered technology similar to what is found today in Google Semantic Search and Knowledge Graph. He is particularly proud of the success of his 45 Ph.D. advisees and postdocs in academia, industry research, and entrepreneurs.
  
* **T.K. Prasad** is a full Professor at Wright State University. His research interests are in Semantic Analysis of Social, Text, and Sensor Data using AI/ML/NLP and Trust with applications to health care, medical informatics, disasters, online harassment, etc. His teaching interests are in Information Retrieval, Algorithms, Knowledge Representation and Reasoning, and Programming Languages. He has also published more than 130 peer-reviewed papers, co-wrote the research monograph “Semantics Empowered Web 3.0: Managing Enterprise, Social, Sensor and Cloud-based Data and Services for Advanced Applications,” and edited conference proceedings for three International Semantic Web Conferences.

---

## 🔗 References
* d’Garcez, A. S., & Lamb, L. C. (2023). Neurosymbolic AI: The 3rd wave. Artificial Intelligence Review.
* Besold, T. R., d’Garcez, A. S., et al. (2017). Neural-Symbolic Learning and Reasoning: A Survey and Interpretation. In Neural-Symbolic Learning and Reasoning (Springer).
* Sheth, A., Roy, K., & Gaur, M. (2023). Neurosymbolic AI: Why, What, and How. arXiv preprint.
* Roy, K., Gaur, M., & Sheth, A. (2022). Process Knowledge-Infused Learning for Suicidality Assessment on Social Media. arXiv preprint.
* Gaur, M., Faldu, K., & Sheth, A. (2021). Semantics of the black-box: Can knowledge graphs help make deep learning systems more interpretable and explainable? IEEE Internet Computing, 25(1), 51-59.
* d’Garcez, A. S., Gabbay, D. M., & others. (2008). Neural-Symbolic Cognitive Reasoning. Springer.
* Garcez, A. d., Broda, K., & Gabbay, D. (2002). Neural-Symbolic Learning Systems: Foundations and Applications. Springer.
