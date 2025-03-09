# python_arduino_uno
# 🔥 Contrôle de LED avec la caméra et les doigts ✋💡

## 📌 Description  
Ce projet permet de **contrôler l'intensité de 3 LED** à l'aide de **gestes de la main** captés par une **caméra**.  
Il utilise **Python (OpenCV + MediaPipe)** pour détecter les doigts levés et **Arduino** pour ajuster l'éclairage des LED.

---

## 🎯 Fonctionnalités  
✅ Détection des doigts levés avec **MediaPipe**  
✅ Transmission des valeurs d'intensité des LED à **l'Arduino** via **Serial**  
✅ Contrôle **ON/OFF** et **luminosité** des LED avec la main  
✅ Interface en **temps réel** avec affichage de la main détectée  

---

## 🛠️ Matériel requis  
🔹 **Arduino Uno**  
🔹 **3 LED**  
🔹 **3 Résistances 220Ω**  
🔹 **Câbles de connexion**  
🔹 **Caméra (Webcam ou module caméra)**  

---

## ⚡ Schéma de câblage  
Les LED sont connectées aux broches **9, 10 et 11** de l'Arduino.  

| **Broche Arduino** | **Composant** |
|------------------|-------------|
| 9  | LED 1 (via 220Ω) |
| 10 | LED 2 (via 220Ω) |
| 11 | LED 3 (via 220Ω) |
| GND | Cathodes des LED |

---

## 🚀 Installation et exécution  

### 1⃣ **Téléverser le code Arduino**  
- **Ouvre l'IDE Arduino**  
- **Charge le fichier `arduino_led.ino`**  
- **Sélectionne le bon port COM et téléverse le code**  

### 2⃣ **Installer les dépendances Python**  
Dans un terminal, exécute :  
```bash
pip install -r requirements.txt
```

### 3⃣ **Exécuter le script Python**  
```bash
python main.py
```

### 4⃣ **Contrôler les LED avec tes doigts !** ✋💡  
- **Index levé** → Allume la LED 1  
- **Majeur levé** → Allume la LED 2  
- **Annulaire levé** → Allume la LED 3  

Pour quitter, appuie sur **"q"**.

---

## 📷 Capture d'écran  
*(Ajoute ici une image du projet en action.)*

---

## 🤖 Développement  
👨‍💻 **Réalisé par** : **EL JAZOULY Mohamed**  
🏫 **École** : ENSAM Rabat  
📧 **Email** : mohamed.eljazouly@usmba.ac.ma  
📞 **Téléphone** : 0636603793  

---

## 📜 Licence  
Ce projet est en open-source. Tu peux le modifier et l'améliorer ! 🚀

