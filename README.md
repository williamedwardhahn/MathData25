# 📘 Project Deliverable Instructions

You’ll use **AlexNet** and apply it to a **problem of your choice**.

Your work will be completed and submitted in **five deliverables**, each building on the previous one.  
Follow the instructions carefully and submit all links on Canvas by the deadlines.

---

## 🧩 Deliverable 1: Google Slides Presentation

### 🎯 Goal
Create a professional **Google Slides presentation** that introduces your project idea and explains your technical approach using **AlexNet**.

### 🪜 Instructions
1. **Create a new Google Slides deck.**
2. Organize your presentation into two halves:
   - **Part 1 – Problem Overview (50%)**
     - Describe your chosen real-world problem and why it matters.
     - Include background, relevance, and example data or visuals.
   - **Part 2 – Technical Solution (50%)**
     - Explain **AlexNet’s architecture** layer by layer (convolution, pooling, fully connected, etc.).
     - Describe the **training process** — data input, loss function, optimizer, learning rate, epochs, etc.
     - Explain how your data fits into the model (input size, preprocessing).
3. Add diagrams, tables, or flowcharts to make concepts clear.
4. **Set sharing permissions** to “Anyone with the link can view.”
5. **Submit the Google Slides link** on Canvas.

---

## 🌐 Deliverable 2: GitHub Website

### 🎯 Goal
Publish your project as a **GitHub Pages website**, presenting your findings in a professional and public-facing format.

### 🪜 Instructions
1. **Create a GitHub repository** for your project.
2. Include:
   - A page describing your **problem and motivation**.
   - A page summarizing your **technical approach** with AlexNet.
   - Sections for **visualizations**, **results**, and **takeaways**.
3. Use simple HTML/CSS, Markdown, or Jekyll templates.
4. Add screenshots and plots from your Colab experiments.
5. Enable **GitHub Pages** to host your site.
6. **Submit both the repository URL and live website URL** on Canvas.

---

## 💻 Deliverable 3: Google Colab Notebook

### 🎯 Goal
Develop a **Google CoLaboratory notebook** that demonstrates your technical work — a full, working implementation of **AlexNet** trained on your dataset.  
You will also conduct **experiments** to explore model performance under different conditions.

### 🪜 Instructions
1. **Create a new Colab notebook** in Python (PyTorch or TensorFlow recommended).
2. **Implement AlexNet**, adapted to your dataset.
3. **Load your custom dataset** from Google Drive or GitHub.
   - Your dataset should relate to your chosen problem (e.g., medical images, animals, objects, etc.).
4. **Perform proper data preprocessing**, including:
   - Resizing images to the correct input size for AlexNet (usually 224×224).
   - Normalization and optional **data augmentation** (e.g., flips, rotations, color jitter).
5. **Train and validate** your model:
   - Split the data into training and validation sets.
   - Track **accuracy** and **loss** over epochs.
   - Save your trained model weights.
6. **Run multiple experiments** and document the effects:
   - 🔹 **Batch size experiments:** Test at least two batch sizes (e.g., 16, 64).
   - 🔹 **Learning rate experiments:** Compare at least two learning rates (e.g., 0.001 vs. 0.0001).
   - 🔹 **Data augmentation:** Train once with and once without augmentation.
   - 🔹 **Architecture comparison:** Try at least one alternative model (e.g., VGG16, ResNet18) for comparison.
7. Use **Weights & Biases (wandb)** to:
   - Log your runs and metrics.
   - Generate plots of accuracy, loss, and confusion matrices.
8. **Visualize and interpret results:**
   - Include plots of training vs. validation accuracy and loss.
   - Discuss what each experiment shows about model behavior.
9. Test that your notebook runs fully without errors.
10. Set permissions to “Anyone with the link can view.”
11. **Submit the Colab link** on Canvas.

---

## 📊 Deliverable 4: Scientific Poster

### 🎯 Goal
Create a **research-style academic poster** summarizing your project and experiments.  
Your poster should look professional and be suitable for an academic conference.

### 🪜 Instructions
1. Open **Google Slides** and **change the slide size** to poster dimensions (e.g., 48" × 36").
2. Organize your poster into clear sections:
   - **Title and Author Information**
     - Include project title, your name, course name, and semester.
   - **Problem Statement**
     - Describe your chosen problem and why you tackled it.
   - **Methods**
     - Summarize how you implemented and trained AlexNet.
     - Explain how you structured your experiments.
   - **Experiments and Results**
     - Present your key experimental findings, including:
       - Batch size comparison results.
       - Learning rate tuning results.
       - Data augmentation vs. no augmentation.
       - Network comparison (e.g., AlexNet vs. ResNet).
     - Include charts, tables, and plots from your Colab notebook.
   - **Discussion**
     - Interpret the results: What patterns did you observe? What improved accuracy the most?
     - Note challenges or surprising outcomes.
   - **Conclusions and Future Work**
     - Summarize what you learned.
     - Suggest next steps or improvements.
3. Use readable fonts, consistent colors, and logical flow.
4. You can find **FAU poster templates** by searching online for *“FAU Google Slides poster templates.”*
5. Set sharing permissions to “Anyone with the link can view.”
6. **Submit your poster link** on Canvas.

---

## 🎥 Deliverable 5: Presentation Video

### 🎯 Goal
Record a **3–8 minute screencast video** where you present your project “Shark Tank-style,” mixing enthusiasm, clarity, and technical detail.

### 🪜 Instructions
1. Use your **Google Slides presentation** as your visual guide.
2. Record your screen using:
   - Loom  
   - Zoom recording  
   - OBS Studio  
   - QuickTime or any other screen recorder
3. Structure your video in two parts:
   - **Part 1 – Pitch (Motivation and Problem)**
     - Explain your chosen problem and why it matters.
   - **Part 2 – Technical Overview**
     - Walk through your model, experiments, and results.
     - Show visualizations from your notebook or poster.
4. Keep the tone confident and engaging.
5. Duration: **3 to 8 minutes.**
6. Upload the video to **YouTube (unlisted)** or **Google Drive** and make sure it’s viewable.
7. **Submit the video link** on Canvas.

---

## ✅ Submission Summary

| Deliverable | What to Submit | Platform | Key Requirements |
|--------------|----------------|-----------|------------------|
| 1. Google Slides Presentation | Google Slides link | Google Slides | Problem overview + AlexNet explanation |
| 2. GitHub Website | GitHub Pages live site + repo URL | GitHub | Web version of your project |
| 3. Colab Notebook | Google Colab link | Colab | Full implementation + experiments + plots |
| 4. Scientific Poster | Google Slides poster link | Google Slides | Summarized results + visuals from experiments |
| 5. Presentation Video | YouTube or Drive link | Screencast | 3–8 min presentation |

---


[Alexnet Exp Notebook
](https://colab.research.google.com/drive/1eKlmWfS2Awu2AvDV4KSYFL5aWpEEVTce?usp=sharing)
