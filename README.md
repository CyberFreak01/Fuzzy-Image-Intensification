# 🚀 Fuzzy Intensification-Based Low Contrast Image Enhancement  
**Preserving Brightness While Enhancing Visibility with Fuzzy Logic**  

![Fuzzy Enhancement](https://github.com/user-attachments/assets/1245548f-acec-4c8d-90e1-47b3dde5ef80)

## 🌟 Why This Project Matters?  
In **medical imaging, surveillance, and satellite imagery**, low-contrast images often limit visibility and interpretation. Conventional enhancement methods can over-amplify noise or distort brightness.  

This project introduces a **Fuzzy Intensification-Based Enhancement Algorithm** that:  
✔ **Boosts visibility while preserving brightness**  
✔ **Handles uncertainty with Intuitionistic Fuzzy Sets (IFS)**  
✔ **Enhances image contrast without excessive noise amplification**  

🔍 **Used in:** Medical diagnostics, security surveillance, satellite imaging, and low-light photography.  

---

## 📌 Project Highlights  
- 🖼️ **Adaptive Image Enhancement** – Uses **fuzzy logic and histogram equalization** to enhance low-contrast images.  
- 🤖 **Intuitionistic Fuzzy Sets (IFS)** – Overcomes uncertainty by considering **membership, non-membership, and hesitation** degrees.  
- ⚡ **Real-Time Processing** – Optimized entropy calculations for adaptive image enhancement.  
- 📊 **Quantitative Evaluation** – Achieves **higher SSIM and lower brightness error** than traditional methods.  

---

## 🔬 How It Works?  
1️⃣ **Preprocessing:** Uses **Non-Local Means Filtering (NLMF)** to reduce noise.  
2️⃣ **Fuzzification:** Converts pixel intensities into fuzzy sets to handle uncertainties.  
3️⃣ **Entropy-Based Optimization:** Adjusts parameters dynamically to **maximize image clarity**.  
4️⃣ **Fusion & Enhancement:** Intuitionistic Fuzzy logic is applied to **integrate multiple modalities** (e.g., CT & MRI).  
5️⃣ **Quantitative Analysis:** Evaluates image enhancement with **SSIM, AMBE, Entropy, and FSIM**.  

---

## 📊 **Results & Evaluation**  
### **Performance Metrics** (Higher Entropy & SSIM, Lower AMBE = Better Enhancement)  

| Image  | AMBE (↓) | Entropy (↑) | SSIM (↑) | FSIM (↑) | GMSD (↓) |  
|--------|---------|------------|---------|---------|---------|  
| 1.jpg  | 12.49   | 7.99       | 0.80    | 0.85    | 0.13    |  
| 2.jpg  | 12.04   | 7.95       | 0.63    | 0.70    | 0.18    |  
| 3.jpg  | 36.38   | 7.67       | 0.38    | 0.43    | 0.17    |  

---

## 🛠 Tech Stack  
✅ Python 🐍  
✅ OpenCV & NumPy 🖼️  
✅ Matplotlib & Seaborn 📊  
✅ Fuzzy Logic & Intuitionistic Fuzzy Sets 🤖  

---

## 🚀 Get Started  
Clone the repository and run the enhancement script:  

```bash
git clone https://github.com/YOUR_USERNAME/fuzzy-enhancement.git
cd fuzzy-enhancement
python enhance.py --input image.jpg --output enhanced.jpg
