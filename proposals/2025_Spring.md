# Spring 2025 Thesis Proposals

---

## Proposal #1: Επεξεργασία σημάτων μεταβλητότητας καρδιακών παλμών (HRV) μεγάλης διάρκειας για την ανάπτυξη ψηφιακών βιοδεικτών

**Supervisor**: Georgios Apostolidis  
**Semester**: Spring 2025  
**Duration**: 6–12 months  
**Students**: 1  
**Status**: Available

### Description

Η επεξεργασία σημάτων μεταβλητότητας καρδιακών παλμών (heart rate variability, HRV) παράγει μετρικές HRV οι οποίες βοηθούν σημαντικά στην κατανόηση της κατάστασης του οργανισμού και της αντίδρασης σε εσωτερικούς ή εξωτερικούς στρεσογόνους παράγοντες. Οι μετρικές HRV παράγονται μετά από επεξεργασία σημάτων beat-beat intervals (BBI). 

Διαφορετικές διεργασίες του οργανισμού εμφανίζονται σε διαφορετικές χρονικές κλίμακες, άρα και συχνότητες, σε μία καταγραφή BBI. Ως εκ τούτου, αναλύοντας το σήμα BBI σε διαφορετικές συχνότητες, και παράγοντας διάφορες μετρικές, έχουμε τη δυνατότητα παρακολουθήσουμε διαφορετικές διεργασίες του οργανισμού. Σημαντικό παράγοντα στην ανάλυση αποτελεί η διάρκεια της καταγραφής. Γενικά, οι περισσότερες μελέτες στην βιβλιογραφία αφορούν μικρά στιγμιότυπα καταγραφών, το πολύ 24 ωρών. Ως εκ τούτου, η ανάλυση καταγραφών μεγάλης διάρκειας, δηλαδή μεγαλύτερων της μία ημέρες, είναι σχετικά υπομελετημένη.

Σκοπός της εργασίας είναι η ανάπτυξη τεχνικών ανάλυσης σημάτων για παρακολούθηση δυναμικών αλλαγών στο HRV σε μεγάλης διάρκειας καταγραφές. Οι τεχνικές αυτές θα αποτελούνται από 1) τα παραδοσιακά στάδια προ-επεξεργασίας σημάτων BBI, 2) την κατασκευή επικαλυπτόμενων παραθύρων καταγραφών, 3) υπολογισμός των παραδοσιακών μετρικών HRV για κάθε παράθυρο, και 4) τον υπολογισμό μετρικών παρακολούθησης των αλλαγών στο HRV από όλα τα παράθυρα της καταγραφής. Μία γραφική αναπαράσταση της συνολικής ανάλυσης παρουσιάζεται στο παρακάτω σχήμα.

![HRV Signal Processing Pipeline](../../assets/images/hrv-pipeline.png)

*Figure: Overview of the data processing and feature generation pipeline for HRV analysis.*

### Prerequisites

- Εξοικείωση με προγραμματισμό σε περιβάλλον Python
- Εξοικείωση με αναγνώριση προτύπων – μηχανική μάθηση
- Επαρκής γνώση βασικών εννοιών στατιστικής
- Επαρκής γνώση προηγμένων τεχνικών επεξεργασίας σήματος

### Application

To apply for this topic, please use the main form and select **Proposal #1**.  
[Form Link Placeholder]

###  References

[1] Acar, B., Savelieva, I., Hemingway, H., & Malik, M. (2000). Automatic ectopic beat elimination in short-term heart rate variability measurement. Computer methods and programs in biomedicine, 63(2), 123-131  
[2] Bent, B., Goldstein, B. A., Kibbe, W. A., & Dunn, J. P. (2020). Investigating sources of inaccuracy in wearable optical heart rate sensors. NPJ digital medicine, 3(1), 18.
[3] Karlsson, M., Hörnsten, R., Rydberg, A., & Wiklund, U. (2012). Automatic filtering of outliers in RR intervals before analysis of heart rate variability in Holter recordings: a comparison with carefully edited data. Biomedical engineering online, 11, 1-12.  
[4] Malik, M. (1996). Heart rate variability: Standards of measurement, physiological interpretation, and clinical use: Task force of the European Society of Cardiology and the North American Society for Pacing and Electrophysiology. Annals of Noninvasive Electrocardiology, 1(2), 151-181. 
[5] Sassi, R., Cerutti, S., Lombardi, F., Malik, M., Huikuri, H. V., Peng, C. K., ... & Macfadyen, R. (2015). Advances in heart rate variability signal analysis: joint position statement by the e-Cardiology ESC Working Group and the European Heart Rhythm Association co-endorsed by the Asia Pacific Heart Rhythm Society. Ep Europace, 17(9), 1341-1353.
[6] Shaffer, F., & Ginsberg, J. P. (2017). An overview of heart rate variability metrics and norms. Frontiers in public health, 258.

---

## Proposal #2: Ανίχνευση καρδιαγγειακών παθήσεων από φωτογραφίες και βίντεο προσώπου

**Supervisor**: Georgios Apostolidis  
**Semester**: Spring 2025  
**Duration**: 9–12 months  
**Students**: 1-2
**Status**: Available

### Description

Η χρήση φωτογραφιών/βίντεο προσώπου μπορεί να οδηγήσει στην ανάπτυξη απλών, αλλά και αποτελεσματικών, μεθόδων ανίχνευσης καρδιοαγγειακών νοσημάτων στα πλαίσια προσυμπτωματικού ελέγχου στον γενικό πληθυσμό. Η ιδέα στηρίζεται στο γεγονός ότι κάποια χαρακτηριστικά του προσώπου συνδέονται με αυξημένο ρίσκο καρδιαγγειακών παθήσεων. Συγκεκριμένα, τέτοια χαρακτηριστικά είναι αραίωση ή γκριζάρισμα μαλλιών, ρυτίδες, πτυχή στο λοβό του αυτιού, ξανθελάσματα (μικρές, κίτρινες εναποθέσεις χοληστερόλης κάτω από το δέρμα, συνήθως γύρω από τα βλέφαρα) και το «γεροντικό» τόξο (arcus senilis) (αποθέσεις λίπους και χοληστερόλης που εμφανίζονται ως θολό λευκό, γκρι ή μπλε αδιαφανές δακτύλιο τα εξωτερικά άκρα του κερατοειδούς).

Ο σκοπός της εργασίας είναι η συλλογή δεδομένων και η ανάπτυξη μοντέλων τεχνητής νοημοσύνης για την ανίχνευση καρδιαγγειακών προβλημάτων από φωτογραφίες/βίντεο προσώπου. Για την ανάπτυξη των μοντέλων θα ακολουθηθούν προσεγγίσεις από την βιβλιογραφία, οι οποίες θα επεκταθούν με σκοπό την βελτίωση της απόδοσης αλλά και την ενίσχυση της ιδιωτικότητας.

### Prerequisites

- Εξοικείωση με προγραμματισμό σε περιβάλλον Python
- Εξοικείωση με αναγνώριση προτύπων – μηχανική μάθηση
- Επαρκής γνώση βασικών εννοιών στατιστικής
- Επαρκής γνώση προηγμένων τεχνικών επεξεργασίας σήματος

### Application

To apply for this topic, please use the main form and select **Proposal #2**.  
[Form Link Placeholder]

### References

[1] Lin, S., Li, Z., Fu, B., Chen, S., Li, X., Wang, Y., ... & Zheng, Z. (2020). Feasibility of using deep learning to detect coronary artery disease based on facial photo. European heart journal, 41(46), 4400-4411.  
[2] Kotanidis, C. P., & Antoniades, C. (2020). Selfies in cardiovascular medicine: welcome to a new era of medical diagnostics. European Heart Journal, 41(46), 4412-4414.
[3] Wen, Y., Liu, B., Ding, M., Xie, R., & Song, L. (2022). Identitydp: Differential private identification protection for face images. Neurocomputing, 501, 197-211.

--
##  Proposal #3: Ανάπτυξη ψηφιακών βιοδεικτών για  ρευματικές και μυοσκελετικές παθήσεις με δεδομένα έξυπνου τηλεφώνου

**Supervisor**: Eleni Vasileiou
**Semester**: Spring 2025  
**Duration**: 6–12 months  
**Students**: 1  
**Status**: Available

### Description

Τα ρευματικά και μυοσκελετικά νοσήματα (ΡΜΝ) αντιπροσωπεύουν ένα ευρύ φάσμα παθήσεων που επηρεάζουν σημαντικά ένα μεγάλο μέρος του πληθυσμού, οδηγώντας συχνά σε χρόνιο πόνο, αναπηρία και μειωμένη ποιότητα ζωής. Η παραδοσιακή περίθαλψη των ασθενών με ΡΜΝ περιλαμβάνει συνήθως αραιές επισκέψεις σε γιατρούς, γεγονός που καθιστά δύσκολη τη συνεχή αξιολόγηση και παρακολούθηση της εξέλιξης της νόσου. Η εμφάνιση ψηφιακών εργαλείων υγείας, όπως τα smartphones και οι αισθητήρες (wearables), προσφέρει την ευκαιρία να καλυφθεί αυτό το κενό, επιτρέποντας την παθητική, συνεχή παρακολούθηση της κατάστασης των ασθενών. Οι ψηφιακοί βιοδείκτες, οι οποίοι είναι αντικειμενικά, ποσοτικοποιήσιμα δεδομένα που συλλέγονται από αυτά τα εργαλεία, θα μπορούσαν να προσφέρουν μια πιο δυναμική και ακριβή αναπαράσταση της κατάστασης της υγείας ενός ασθενούς, μετασχηματίζοντας ενδεχομένως τη διαχείριση των ΡΜΝ και βελτιώνοντας την ποιότητα της περίθαλψης των ατόμων με ΡΜΝ.

Ο σκοπός της εργασίας είναι η ανάπτυξη ψηφιακών βιοδεικτών για τα ΡΜΝ χρησιμοποιώντας μοντέλα μηχανικής μάθησης που συνδυάζουν πολυδιάστατα δεδομένα από smartphones για τη μελέτη της κινητικότητας, των κινητικών δεξιοτήτων και της ψυχικής υγείας, ώστε να καταστεί δυνατή η έγκαιρη διάγνωση και η συνεχής παρακολούθηση των ΡΜΝ. Για την ανάπτυξη των ψηφιακών βιοδεικτών θα χρησιμοποιηθεί το σύνολο δεδομένων COTIDIANA [1].

### Prerequisites

- Εξοικείωση με προγραμματισμό σε περιβάλλον Python
- Εξοικείωση με αναγνώριση προτύπων – μηχανική μάθηση
- Επαρκής γνώση βασικών εννοιών στατιστικής
- Επαρκής γνώση προηγμένων τεχνικών επεξεργασίας σήματος

###  Application

To apply for this topic, please use the main form and select the appropriate proposal number.  
[Form Link Placeholder]

###  References

[1] Matias, P., Araújo, R., Graça, R., Henriques, A. R., Belo, D., Valada, M., ... & Nunes, F. (2024). COTIDIANA Dataset–Smartphone-Collected Data on the Mobility, Finger Dexterity, and Mental Health of People With Rheumatic and Musculoskeletal Diseases. IEEE Journal of Biomedical and Health Informatics.
[2] Hamy, V., Garcia-Gancedo, L., Pollard, A., Myatt, A., Liu, J., Howland, A., ... & Crouthamel, M. (2020). Developing smartphone-based objective assessments of physical function in rheumatoid arthritis patients: the PARADE study. Digital biomarkers, 4(1), 26-44.
[3] Creagh, A. P., Hamy, V., Yuan, H., Mertes, G., Tomlinson, R., Chen, W. H., ... & Clifton, D. A. (2024). Digital health technologies and machine learning augment patient reported outcomes to remotely characterise rheumatoid arthritis. npj Digital Medicine, 7(1), 33.

--

##  Proposal #4: DΜελέτη και ανάπτυξη ψηφιακών βιοδεικτών για καρδιακά συμπτώματα της νόσου του Πάρκινσον

**Supervisor**: Ioannis Gerasimou
**Semester**: Spring 2025  
**Duration**: 9–12 months  
**Students**: 1  
**Status**: Available

### Description

Η νόσος του Πάρκινσον ως νευροεκφυλιστικό νόσημα επηρεάζει το Κεντρικό Αυτόνομο Νευρικό (ΚΑΝ) σύστημα προκαλώντας και μη-κινητικά συμπτώματα. Μια κατηγορία μη-κινητικών συμπτωμάτων οφείλεται στην καρδιακή δυσαυτονομία, η οποία είναι αποτέλεσμα της νευροπάθειας του ΚΑΝ. Τα συμπτώματα αυτά, μεταξύ άλλων, είναι η νευρογενής ορθοστατική υπόταση, η μη καταβύθιση της αρτηριακής πίεσης κατά την διάρκεια του ύπνου και η απόκλιση της μεταβλητότητας του καρδιακού ρυθμού (Heart rate variability) από τα φυσιολογικά επίπεδα. Καθώς τα συμπτώματα αυτά εμφανίζονται νωρίς στην πορεία της νόσου, η έγκαιρη αναγνώριση τους μπορεί να συμβάλλει στην αξιολόγηση του ρίσκου.

Ο σκοπός της εργασίας είναι η ανάπτυξη μοντέλων τεχνητής νοημοσύνης για την ανίχνευση των καρδιαγγειακών συμπτωμάτων της καρδιακής δυσαυτονομίας από σήματα φωτοπληθυσμογραφίας (PPG) έξυπνου ρολογιού (Smartwatch). Για την ανάπτυξη των μοντέλων θα ακολουθηθούν προσεγγίσεις κλασσικής μηχανικής μάθησης, οι οποίες μπορούν να επεκταθούν με πιο προηγμένες με σκοπό την βελτίωση της απόδοσης.

### Prerequisites

- Εξοικείωση με προγραμματισμό σε περιβάλλον Python
- Εξοικείωση με αναγνώριση προτύπων – μηχανική μάθηση
- Επαρκής γνώση βασικών εννοιών στατιστικής
- Επαρκής γνώση προηγμένων τεχνικών επεξεργασίας σήματος

###  Application

To apply for this topic, please use the main form and select the appropriate proposal number.  
[Form Link Placeholder]

###  References

[1] Alonso, A., Huang, X., Mosley, T. H., Heiss, G., & Chen, H. (2015). Heart rate variability and the risk of Parkinson disease: The Atherosclerosis Risk in Communities study. Annals of neurology, 77(5), 877–883. https://doi.org/10.1002/ana.24393
[2] Arnao, V., Cinturino, A., Mastrilli, S. et al. Impaired circadian heart rate variability in Parkinson’s disease: a time-domain analysis in ambulatory setting. BMC Neurol 20, 152 (2020). https://doi.org/10.1186/s12883-020-01722-3 
[3] Iniguez, M., Jimenez-Marin, A., Erramuzpe, A. et al. Heart-brain synchronization breakdown in Parkinson’s disease. npj Parkinsons Dis. 8, 64 (2022). https://doi.org/10.1038/s41531-022-00323-w

--

##  Proposal #5: Learning Joint Multimodal Representations within Diverse Affective Game Environments for Development of a Sensor-less Physiological Monitoring Tool

**Supervisor**: Ioannis Ziogas Efstratia Ganiti
**Semester**: Spring 2025  
**Duration**: 9–12 months  
**Students**: 1  
**Status**: Available

### Description

Daily interactions with digital platforms have ushered in a new phase in Human-Computer Interaction (HCI), with the development of video games integrated with affective computing, i.e. Affective Games (AGs). During gameplay, our physical entity immerses into a digital world, interacts with various game elements, and experiences real physiological changes. Accurately detecting and measuring these multimodal responses, and associating them with game parameters, poses a significant challenge.

Deep learning of multimodal representations, i.e. representations that express the dynamics of different sources of information that describe the same underlying process, and specifically self-supervised learning algorithms, a family of unsupervised techniques, demonstrates great promise in learning rich representations from data without the need of annotations. Methods such as Contrastive Language-Image Pretraining (CLIP), learn multimodal representations by utilizing one modality as the supervisory signal for the other modality (e.g. using language as a supervision for image). Other methods, such as Multimodal Masked Variational Autoencoders (M3VAE), apply augmentations (e.g. masking) to perturb the structure of the input, and then attempt to recover this information by reconstructing the unmasked input. Both approaches try to learn a latent space where semantically similar pairs of different modalities are also spatially affine. These methods have not been adapted to affective gaming and multimodal fusion of game logs and signals is relatively unexplored.

This thesis aims to develop deep learning and signal processing algorithms for the creation of a tool that explores the interplay between the modalities of game logs and biomedical signals, towards sensor-less monitoring of vital signs during HCI. The student(s) will have access to a publicly available affective computing dataset (see [1]). The developed algorithms will be based on existing implementations of similar deep models that have been used for other modalities and tasks. The developed models will be evaluated as per their capacity to perform modality retrieval (predicting one modality when knowing the other) and enhancement of performance in affective computing tasks (e.g. emotion recognition).

### Prerequisites

### Must-have
- Experience with Python and PyTorch
- Pattern Recognition – Machine Learning

### Good-to-have
- Basic understanding of self-supervised learning and unsupervised learning techniques
- Biomedical Signal Processing
- Experience with HuggingFace

###  Application

To apply for this topic, please use the main form and select the appropriate proposal number.  
[Form Link Placeholder]

###  References

[1] Kutt, K., Drążyk, D., Żuchowska, L. et al. BIRAFFE2, a multimodal dataset for emotion-based personalization in rich affective game environments. Sci Data 9, 274 (2022). https://doi.org/10.1038/s41597-022-01402-6
[2] E. Ganiti-Roumeliotou, S. B. Dias, K. Khalaf, H. F. Jelinek and L. J. Hadjileontiadis, "Beyond the Game: Multimodal Game-Experience Recognition During Dynamic Affective Game Environments," 2024 IEEE 22nd Mediterranean Electrotechnical Conference (MELECON), Porto, Portugal, 2024, pp. 1042-1047, doi: 10.1109/MELECON56669.2024.10608557.
[3]: Radford, Alec, et al. "Learning transferable visual models from natural language supervision." International conference on machine learning. PMLR, 2021.
[4]: Geng, Xinyang, et al. "Multimodal masked autoencoders learn transferable representations." arXiv preprint arXiv:2205.14204 (2022).

--

##  Proposal #6: Affective Game Design with Emotionally Adaptive Avatars

**Supervisor**: Sofia B. Dias, Efstratia Ganiti, Ioannis Ziogas
**Semester**: Spring 2025  
**Duration**: 9–12 months  
**Students**: 1
**Status**: Available

### Description

Emotions elicited in human beings during daily-life natural interactions are multimodal and complex due to interplays between current stimuli and past emotional experiences. Emotion recognition, as a facet of HCI, involves the interpretation of a user's emotional state, often through various physiological and behavioral signals. This recognition capability has profound implications across diverse domains, from serious games (SGs) to therapeutic interventions. This research explores the design of SGs where players interact with avatars that mirror their past emotional states, creating a platform for self-reflection and emotional growth. By using advances in affective computing and emotion recognition, the game will model and store emotional data from past emotional states, which will shape the behavior, appearance, and dialogue of in-game avatars, enabling players to engage with dynamic representations of their emotional trajectory. The project will focus on developing emotion modeling frameworks, adaptive avatar generation systems, and interactive game mechanics to encourage meaningful player-avatar interactions. By enabling players to interact with their emotional pasts, we foresee SGs that foster emotional intelligence, enhance self-awareness, and support therapeutic practices. Specifically we aim towards SGs, that support the rehabilitation of patients' who face difficulty in monitoring their emotions, such as children diagnosed with Autism Spectrum Disorder, leading to the development of more emotionally resonant (emo-games) and patient-centric SG.

The project will be divided between two students: one focusing on game design (ULisboa) and the other on game implementation (AUTh). The game design student will create the gameplay framework and scenarios, ensuring emotional interactions are meaningful and engaging. The implementation student will develop a machine learning model capable of recognizing and modeling emotional states from multimodal inputs, that will be then used as a pre-trained module to perform real-time tasks within the game environment [1]. This will involve setting up a database to store data, as well as building the front-end interface to integrate adaptive avatars and emotional interactions into gameplay.

### Prerequisites

### Must-have
- Knowledge of Game design
- Knowledge of pattern recognition and databases
- Knowledge of Game platforms (unity etc) programming languages

### Good-to-have
- Biomedical Signal Processing
- Understanding of VR settings

###  Application

To apply for this topic, please use the main form and select the appropriate proposal number.  
[Form Link Placeholder]

###  References

[1] Kutt, K., Drążyk, D., Żuchowska, L. et al. BIRAFFE2, a multimodal dataset for emotion-based personalization in rich affective game environments. Sci Data 9, 274 (2022). https://doi.org/10.1038/s41597-022-01402-6
[2] E. Ganiti-Roumeliotou, et al. “Beyond the Game: Multimodal Emotion Recognition Before, During, and After Gameplay”, In the Proceedings of the Annual International Conference of the IEEE Engineering in Medicine and Biology Society, EMBS, 2024.

--

##  Proposal #7: Development of Smartphone-Based Serious Game Platform for supporting patients diagnosed with Psoriatic Arthritis

**Supervisor**: Sofia B. Dias, Efstratia Ganiti, Ioannis Ziogas
**Semester**: Spring 2025  
**Duration**: 9–12 months  
**Students**: 1-2
**Status**: Available

### Description

Psoriatic arthritis (PsA) is a chronic inflammatory disease affecting the musculoskeletal system, skin, and nails [1]. It often leads to joint pain, stiffness, and reduced hand strength, significantly impacting patients’ quality of life and ability to perform everyday tasks [1]. While advancements in diagnosis, treatment, and clinical assessment have improved PsA management, addressing the loss of grip strength and hand mobility remains a key challenge in rehabilitation [2]. Encouraging patients to engage in regular therapeutic exercises is critical for maintaining hand function and improving outcomes [3]. Serious games—digital games designed with therapeutic or educational objectives—offer an innovative approach, combining physical rehabilitation with gamified experiences that motivate and engage users [4], [5]. This research proposes the development of a smartphone-based serious game platform tailored to PsA patients. The game will simulate guitar playing through touchscreen interactions, encouraging hand movements and grip exercises. Additionally, the platform will utilize the smartphone's built-in sensors—such as the IMU (inertial measurement unit), microphone, and touch screen—to estimate grip force and interaction dynamics during gameplay [6]. These features will allow the game to serve not only as a tool for therapy but also as a platform for monitoring grip strength and tracking progress over time. By merging gamified interaction with grip force estimation, the proposed platform will serve as an engaging and accessible tool for therapeutic and monitoring purposes, towards patient-centric healthcare.

### Prerequisites

### Must-have
- Knowledge of Signal Processing
- Knowledge of Game design

### Good-to-have
- Knowledge of pattern recognition
- Knowledge of Game platforms (unity etc) programming languages

###  Application

To apply for this topic, please use the main form and select the appropriate proposal number.  
[[Form](https://docs.google.com/forms/d/e/1FAIpQLSe08hw9Z0LANej63cjehx1ELBqKeMNK7EtdYA9n1JgNS0-UAw/viewform?usp=sharing)]

###  References

[1] G. Schett, P. Rahman, C. Ritchlin, I. B. McInnes, D. Elewaut, and J. U. Scher, “Psoriatic arthritis from a mechanistic perspective,” Nat Rev Rheumatol, vol. 18, no. 6, pp. 311–325, 2022, doi: 10.1038/s41584-022-00776-6.
[2] I. Olivieri, S. D’Angelo, C. Palazzi, and A. Padula, “Advances in the management of psoriatic arthritis,” Nat Rev Rheumatol, vol. 10, no. 9, pp. 531–542, 2014, doi: 10.1038/nrrheum.2014.106.
[3] D. R. Jadon, C. Stober, S. R. Pennington, and O. FitzGerald, “Applying precision medicine to unmet clinical needs in psoriatic disease,” Nat Rev Rheumatol, vol. 16, no. 11, pp. 609–627, 2020, doi: 10.1038/s41584-020-00507-9.
[4] L. and others Argenton, “Serious Games as Positive Technologies,” Lecture Notes in Computer Science (including subseries Lecture Notes in Artificial Intelligence and Lecture Notes in Bioinformatics), vol. 8526 LNCS, no. PART 2, pp. 169–177, 2014, doi: 10.1007/978-3-319-07464-1_16.
[5] L. G. and B.-G. F. J. and B.-C. Á. and B. J. and S.-P. A. and H.-R. A. M. Rodríguez Sánchez-Laulhé Pablo and Luque-Romero, “An Exercise and Educational and Self-management Program Delivered With a Smartphone App (CareHand) in Adults With Rheumatoid Arthritis of the Hands: Randomized Controlled Trial,” JMIR Mhealth Uhealth, vol. 10, no. 4, p. e35462, Apr. 2022, doi: 10.2196/35462.
[6] K.-E. Kim et al., “Hand Grip Pattern Recognition for Mobile User Interfaces,” in Proceedings of the AAAI Conference on Artificial Intelligence, 2006. [Online]. Available: www.essd.com

--


