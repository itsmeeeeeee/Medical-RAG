**Title:**  
Retrieval Augmented Generation (RAG) System mit medizinischen Daten

**Überblick:**  
Dieses Projekt implementiert ein Retrieval Augmented Generation (RAG) Question/Answering (QA) System zur Verarbeitung und Analyse von medizinischen Daten. Es verwendet fortschrittliche Textextraktions- und Verarbeitungstechnologien, um wertvolle Einblicke aus medizinischen Dokumenten zu gewinnen.

**Hauptmerkmale:**  
- **Datenextraktion:** Nutzung des "llmsherpa" Frameworks und des "LayoutPDFReader" zur präzisen Textextraktion.
- **Textverarbeitung:** Erkennung und Strukturierung von Textelementen über verschiedene PDF-Seiten hinweg.

**Voraussetzungen:**  
Installieren Sie die notwendigen Python-Bibliotheken mit folgenden Befehlen:
```
pip install trulens_eval llama_index openai
pip install llama-index-embeddings-openai
```

**Indexierung mit Lamma Index:**  
Dieser Abschnitt des Systems nutzt den "Lamma Index" zur effizienten Indexierung der extrahierten Daten, wodurch die Datenabfrage und -analyse beschleunigt wird.

**Integration der OpenAI GPT-Turbo 3.5 API:**  
Das System verwendet das OpenAI GPT-Chatmodell, um präzise und kontextbezogene Antworten auf Benutzeranfragen zu generieren, basierend auf indizierten Daten. Durch den Einsatz von prompt-based querying und der umfangreichen Trainingsdatenbasis des Modells liefert das System hochrelevante Informationen, die speziell auf die individuellen Bedürfnisse der Nutzer zugeschnitten sind.

**Evaluation mit TruLens:**  
Das System verwendet "TruLens" zur Evaluierung der Modellinterpretationen, um die Entscheidungsfindungsprozesse des Modells transparent zu machen und zu verbessern.

**Quick Start:**  
Führen Sie das Jupyter Notebook `medical_RAG` aus, um das System zu starten und die Daten zu verarbeiten.
