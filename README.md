# IA - Robots Assistencials 🤖🧠

**Treball de Recerca de Batxillerat (2n BAT B, Curs 2024-2025)**  
**Centre Educatiu:** La Salle Manresa  
**Autor:** Arnau Castells Cañadas   

---

## 📌 Descripció del Projecte

Aquest projecte explora les aplicacions pràctiques de la Intel·ligència Artificial i la robòtica assistencial orientada a l'àmbit social i sanitari. 

El projecte consta de dues fases de desenvolupament pràctic:
1. **Robot 1 (Reconeixement d'objectes i cares):** Desenvolupament d'un prototip amb Raspberry Pi 4 i Google Coral USB Accelerator per a la identificació visual d'objectes, formes, colors i reconeixement facial.
2. **Robot 2 (Detecció d'emocions):** Sistema optimitzat basat en un model entrenat (`emotion-ferplus-8.onnx`) per interpretar l'estat d'ànim i les expressions facials (alegria, tristesa, sorpresa, etc.) en temps real.

---

## 🛠️ Maquinari utilitzat

- **Microprocessador:** 2× Raspberry Pi 4
- **Accelerador d'IA:** Google Coral USB Accelerator
- **Captura d'imatge:** Raspberry Pi Camera
- **Perifèrics:** LEDs, botons de pressió (pushbuttons) i resistències
- **Estructura:** Peces de suport i impressió 3D

---

## 💻 Entorn de programació i llibreries

- **Llenguatge:** Python 3.x
- **Editor:** Visual Studio Code
- **Llibreries principals:**
  - `OpenCV` (`cv2`) - Processament d'imatge i vídeo
  - `NumPy` - Manipulació de matrius de dades
  - `ONNX Runtime` - Execució del model de detecció d'emocions

---

## 🚀 Instal·lació i configuració

1. **Clonar el repositori:**
   ```bash
   git clone [https://github.com/EL_TEU_USUARI/ia-robots-assistencials.git](https://github.com/EL_TEU_USUARI/ia-robots-assistencials.git)
   cd ia-robots-assistencials
