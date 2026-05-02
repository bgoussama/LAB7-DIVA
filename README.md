# 🔐 Lab 7 — MobSF Dynamic Analysis avec DIVA
**Nom :**  Bagy Oussama
**Module :** Sécurité Mobile / Android

---

## ⚙️ Étape 1 — Lancement de l'Environnement

### 1.1 Émulateur Android démarré

<img width="714" height="128" alt="image" src="https://github.com/user-attachments/assets/43823683-8acf-493f-af71-f027bdfec615" />

### 1.2 ADB Devices connecté

<img width="1010" height="103" alt="image" src="https://github.com/user-attachments/assets/9be8d553-0eec-45e9-a4e9-a0891bf13182" />




### 1.3 MobSF lancé sur http://127.0.0.1:8000

<img width="570" height="542" alt="Capture d&#39;écran 2026-05-02 150749" src="https://github.com/user-attachments/assets/9dadc7c5-b2ed-45c1-97ed-f671fe7b9756" />



---

## 📤 Étape 2 — Upload DIVA APK

### 2.1 Upload diva-beta.apk dans MobSF

<img width="1593" height="951" alt="Capture d&#39;écran 2026-05-02 151003" src="https://github.com/user-attachments/assets/a7da000f-557f-41e2-af14-7ef09303300d" />




---

## 🔍 Étape 3 — Analyse Statique

### 3.1 Rapport Statique Global — Security Score 35/100

<img width="1719" height="832" alt="Capture d&#39;écran 2026-05-02 152408" src="https://github.com/user-attachments/assets/2bea0ca1-4b52-4d0f-8890-4a497c70421b" />



### 3.2 Manifest Analysis — Vulnérabilités détectées

<img width="1692" height="538" alt="Capture d&#39;écran 2026-05-02 152420" src="https://github.com/user-attachments/assets/451b8c44-4337-44ea-9a69-ee9cb59e2a26" />


### 3.3 Certificate Analysis — Debug Cert + Janus Vulnerability

<img width="1640" height="694" alt="Capture d&#39;écran 2026-05-02 152428" src="https://github.com/user-attachments/assets/118c6f6f-8cd5-46af-be85-26422b229927" />


---

## 🚀 Étape 4 — Analyse Dynamique

### 4.1 Dynamic Analyzer ouvert dans MobSF

<img width="950" height="845" alt="image" src="https://github.com/user-attachments/assets/8e04e22d-e7a6-4a18-973c-7d756262f23f" />


### 4.2 Application DIVA ouverte sur l'émulateur

<img width="529" height="708" alt="image" src="https://github.com/user-attachments/assets/87ba1069-3426-407a-a097-11ad0c1e20f6" />

<img width="448" height="946" alt="image" src="https://github.com/user-attachments/assets/fb8a7d63-1a08-445d-ac55-433ba012d256" />


---

## 🧪 Étape 5 — Challenges DIVA

### 5.1 Insecure Logging — Logcat Stream

<img width="946" height="533" alt="image" src="https://github.com/user-attachments/assets/754779a6-855a-40a0-8f3e-ba3bf45a65a8" />

### 5.2 Insecure Data Storage — Fichiers non chiffrés

<img width="468" height="966" alt="image" src="https://github.com/user-attachments/assets/3dbff2f7-c5c8-4ee9-a33e-9c8fc9f45463" />

<img width="894" height="534" alt="image" src="https://github.com/user-attachments/assets/c93cb257-d47d-4466-a49a-eb79ced97a3a" />

### 5.3 Input Validation — Injection SQL

<img width="451" height="948" alt="image" src="https://github.com/user-attachments/assets/49ce7068-8296-4e1f-8c57-357465f4a701" />


### 5.4 Access Control — Exported Activity Tester

<img width="452" height="922" alt="image" src="https://github.com/user-attachments/assets/1c381ed0-474a-44b4-b754-791037b4f5cb" />

<img width="474" height="980" alt="image" src="https://github.com/user-attachments/assets/c99cf9f2-d21b-425f-81fa-795baf9fd200" />



### 5.5 Network Traffic — Trafic intercepté via proxy 1337

<img width="460" height="933" alt="image" src="https://github.com/user-attachments/assets/fc5568b8-e89e-4038-a16f-eec7ce1101be" />

<img width="1025" height="343" alt="image" src="https://github.com/user-attachments/assets/a262816f-b7d2-4457-ad9a-5f3bac968445" />

<img width="475" height="979" alt="image" src="https://github.com/user-attachments/assets/3434a246-9cb1-4e00-9476-2bc9e0a2b977" />


<img width="487" height="616" alt="image" src="https://github.com/user-attachments/assets/ccae7859-6dd2-47f8-b48d-8d4071fc9d0d" />


