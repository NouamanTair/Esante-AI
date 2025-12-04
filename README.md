# Accès aux données et ressources eMOB

## Ressources accessibles

### 1. Drive UCA — Bibliothèque eMOB‑data

#### Acquisition_jan22_Montluçon

**CapteurBergeret (CSV)**
- Didier
- Jean‑Marie
- Corinne
- Emmanuel
- Anthony
- Ala
- Alexis
- Francis
- Alexis_2
- Cédric
- Bastien
- Didier_2
- Corinne_2

**Étiquettes**
- Méthode d'étiquetage

**LIPC_Dataset**
- Qualisys_3D_Videos
- RGB_videos
- CSV participants

**Qualisys**
- raw_data (.tsv)
- vidéos

**resultats_csv**
- Fichiers CSV et TXT

**test_etiquetage_bras**
- Scripts .py

**UKK**

**vidéos_3D_Qualisys**
- Exemple : patient1_26jan20 (1).mp4

---

#### Acquisition_mai21_Montluçon (31 mai – 1 juin)

- CapteurBergeret_31mai21
- CapteurFavreau_31mai21
- CapteurFavreau_31mai21_complet
- Capteurs_Bergeret_31mai21_complet
- data_qualisys
- fichier_tags_revision2022
- resultats_2022
- videos_etiquetees_corrigees
- Vidéos

**Vidéos étiquetées**
- Axel
- Issam
- Jean‑Marie
- Quentin
- Saut corrigé

**Fichiers**
- acquisition_31mai21.ods
- qualite_donnes_31mai1juin.ods

---

#### Mouvements élémentaires

- RUN_mouvements_elementaires_1
- RUN_mouvements_elementaires_2

---

#### Dataset public UTD‑MHAD

- Depth.zip
- Inertial.zip
- RGB.zip
- Sample_Code.zip
- Skeleton.zip

---

#### Scripts (utils)

- `consolidate-taxonomy.py`
- `generate_srt.sh`
- `tags2srt.py`

---

#### Tuto

- Tutoriels vidéos (Tofu)

---

#### UKK

- Données capteurs UKK

---

#### WANG (travaux Jingyao Wang)

- data
- EfficientGCN
- EfficientGCN_new
- output
- output_100epochs_selective
- ST‑TR
- transfer
- config.xlsx
- Classeur1.xlsx
- Data qualisys.pptx
- tem.jpg

---

### 2. Forge GitLab (limos.fr)

**Projets accessibles :**
- app E‑santé
- esante‑labelling
- RM42 log parser
- esante_presentations
- tofu_video_labeller
- autres codes internes

---

### 3. VM emob-data.limos.fr

**Structure :**

/
├── capture_2021-05-31/
├── capture_2022-01-26/
├── run1/
├── run2/
├── README.md
└── etiquetage.ods

text


**Données disponibles :**
- Vidéos
- CSV mouvement
- Accélérométries
- Mouvements élémentaires
- Vie quotidienne

---

## Ressources non accessibles (ou en attente d'activation)

### VM CHU (accès SSH requis)

- Données capteurs réels (binaire)
- Vidéos associées
- Dépôt automatique par le CHU
- ⚠️ Accès seulement après création de compte

### emob‑analyzer

- Nécessite un compte
- Permet de visualiser les données CHU déchiffrées (graphiques)

---

## Résumé : où trouver quoi ?

### ✅ Données accessibles

| Source | Contenu |
|--------|---------|
| Drive UCA | Toutes acquisitions, Qualisys, RUN, UKK, WANG, UTD‑MHAD |
| VM emob-data.limos.fr | Captures 2021/2022 + mouvements élémentaires |

### ✅ Outils accessibles

- Scripts (utils)
- GitLab limos (labellers, parsers, apps)
- Modèles & code (EfficientGCN, ST‑TR…) via dossier WANG

### ❌ Données nécessitant accès

- VM CHU
- emob‑analyzer
