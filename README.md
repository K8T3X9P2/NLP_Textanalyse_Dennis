# NLP Textanalyse – Themenextraktion mittels Topic Modelling

Dieses Projekt dient der Analyse einer Sammlung von Texten mithilfe von NLP-Techniken. Ziel ist es, häufig diskutierte Themen aus unstrukturierten Texten zu identifizieren und methodisch aufzubereiten.

---

Datensatz

Verwendeter Datensatz: *Women's E-Commerce Clothing Reviews*  
Quelle: nicapotato, 2017, Kaggle: https://www.kaggle.com/datasets/nicapotato/womens-ecommerce-clothing-reviews/data

Der Datensatz enthält Nutzerbewertungen zu Kleidung und eignet sich zur exemplarischen Anwendung von Textanalyse- und Topic-Modelling-Verfahren.

---

Vorgehensweise (Konzeptionsphase)

1. **Vorverarbeitung der Texte**  
   - Umwandlung in Kleinschreibung  
   - Entfernen von Sonderzeichen, Zahlen und überflüssigen Leerzeichen  
   - Tokenisierung mittels `nltk`

2. **Vektorisierung**  
   - Bag-of-Words (Häufigkeitsmodell)  
   - TF-IDF (gewichtetes Modell)  
   → Umsetzung mit `pandas` und `scikit-learn`

3. **Themenextraktion**  
   - Latent Dirichlet Allocation (LDA)  
   - Latent Semantic Analysis (LSA)  
   → Umsetzung über Topic-Modelling-Module aus `scikit-learn`

4. **Bestimmung der optimalen Topic-Anzahl**  
   - In Phase 2 werden mehrere LDA-Modelle mit variierenden Topic-Zahlen trainiert  
   - Vergleich mithilfe des Coherence Score (`gensim`)  
   - Auswahl der Topic-Anzahl mit höchster Kohärenz

---


