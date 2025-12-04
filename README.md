Accès aux données et ressources eMOB
Ressources accessibles
1. Drive UCA — Bibliothèque eMOB‑data
→ Acquisition_jan22_Montluçon

    CapteurBergeret (CSV)
        → Didier
        → Jean‑Marie
        → Corinne
        → Emmanuel
        → Anthony
        → Ala
        → Alexis
        → Francis
        → Alexis_2
        → Cédric
        → Bastien
        → Didier_2
        → Corinne_2

    Étiquettes
        → méthode d'étiquetage

    LIPC_Dataset
        → Qualisys_3D_Videos
        → RGB_videos
        → CSV participants

    Qualisys
        → raw_data (.tsv)
        → vidéos

    resultats_csv
        → fichiers CSV et TXT

    test_etiquetage_bras
        → scripts .py

    UKK

    vidéos_3D_Qualisys
        → exemple : patient1_26jan20 (1).mp4

→ Acquisition_mai21_Montluçon (31 mai – 1 juin)

    CapteurBergeret_31mai21
    CapteurFavreau_31mai21
    CapteurFavreau_31mai21_complet
    Capteurs_Bergeret_31mai21_complet
    data_qualisys
    fichier_tags_revision2022
    resultats_2022
    videos_etiquetees_corrigees
    Vidéos
    Vidéos étiquetées
        → Axel
        → Issam
        → Jean‑Marie
        → Quentin
        → Saut corrigé
    acquisition_31mai21.ods
    qualite_donnes_31mai1juin.ods

→ Mouvements élémentaires

    RUN_mouvements_elementaires_1
    RUN_mouvements_elementaires_2

→ Dataset public UTD‑MHAD

    Depth.zip
    Inertial.zip
    RGB.zip
    Sample_Code.zip
    Skeleton.zip

→ Scripts (utils)

    consolidate-taxonomy.py
    generate_srt.sh
    tags2srt.py

→ Tuto

    tutoriels vidéos (Tofu)

→ UKK

    données capteurs UKK

→ WANG (travaux Jingyao Wang)

    data
    EfficientGCN
    EfficientGCN_new
    output
    output_100epochs_selective
    ST‑TR
    transfer
    config.xlsx
    Classeur1.xlsx
    Data qualisys.pptx
    tem.jpg

2. Forge GitLab (limos.fr)

Projets accessibles :

    → app E‑santé
    → esante‑labelling
    → RM42 log parser
    → esante_presentations
    → tofu_video_labeller
    → autres codes internes

3. VM emob-data.limos.fr

Structure :

text

/
├── capture_2021-05-31/
├── capture_2022-01-26/
├── run1/
├── run2/
├── README.md
└── etiquetage.ods

Données disponibles :

    → vidéos
    → CSV mouvement
    → accélérométries
    → mouvements élémentaires
    → vie quotidienne

Ressources non accessibles (ou en attente d'activation)
→ VM CHU (accès SSH requis)

    données capteurs réels (binaire)
    vidéos associées
    dépôt automatique par le CHU
    ⚠️ accès seulement après création de compte

→ emob‑analyzer

    nécessite un compte
    permet de visualiser les données CHU déchiffrées (graphiques)

Résumé : où trouver quoi ?
✅ Données accessibles
Source	Contenu
Drive UCA	→ toutes acquisitions, Qualisys, RUN, UKK, WANG, UTD‑MHAD
VM emob-data.limos.fr	→ captures 2021/2022 + mouvements élémentaires
✅ Outils accessibles

    → scripts (utils)
    → GitLab limos (labellers, parsers, apps)
    → modèles & code (EfficientGCN, ST‑TR…) via dossier WANG

❌ Données nécessitant accès

    → VM CHU
    → emob‑analyzer
