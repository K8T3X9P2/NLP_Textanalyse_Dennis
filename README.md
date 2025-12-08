NLP Textanalyse – Topic Modelling auf Kundenrezensionen

Dieses Repository enthält eine Textanalyse auf Basis des Datensatzes Women’s E-Commerce Clothing Reviews (Kaggle, 2017). Ziel der Untersuchung ist es, wiederkehrende Themen in Kundenbewertungen zu identifizieren und exemplarisch moderne Verfahren des Natural Language Processing (NLP) anzuwenden.

Der Datensatz umfasst mehrere tausend Rezensionen zu Damenbekleidung. Für die Analyse wurden die Texte bereinigt, tokenisiert und von Stopwörtern befreit. Anschließend wurden sie in numerische Darstellungen überführt, um Algorithmen zur Themenextraktion anwenden zu können. Hierzu kamen Bag-of-Words und TF-IDF als Vektorisierungsverfahren zum Einsatz.

Zur Modellierung der zugrunde liegenden Themenstruktur wurden Latent Dirichlet Allocation (LDA) sowie Latent Semantic Analysis (LSA) verwendet. Um die Anzahl sinnvoller Themen abzuschätzen, wurden mehrere Modelle trainiert und anhand eines Kohärenzwerts verglichen. Die beste Modellgüte ergab sich bei neun Themen, die u. a. Passform, Komfort, Material, Design, Pflegeaufwand und Nutzungserfahrungen widerspiegeln.

Das Jupyter Notebook dokumentiert die Umsetzung der Analyse, die verwendeten Codebausteine sowie die wichtigsten Ergebnisse.
