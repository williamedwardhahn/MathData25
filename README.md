# Links
## Notebooks
[Load Data from Github](https://colab.research.google.com/drive/1ntd-gp2X1rplBODZOs1tAE-3BqqvxSS1?usp=sharing)

## Video Links
[The Computer Programme (1): It's Happening Now](https://www.youtube.com/watch?v=jtMWEiCdsfc)

[The Computer Programme (2): Just One Thing After Another](https://www.youtube.com/watch?v=OFUHjDhTIJg)

[The Computer Programme (3): Talking To A Machine (Programming Languages)](https://www.youtube.com/watch?v=7Mr3Csyb0Qw)

[Mathematics](https://www.youtube.com/watch?v=gV67Sj2jkVg)

[Alexnet](https://www.youtube.com/watch?v=AgkfIQ4IGaM)

[The Computer Programme (4): It's on the Computer](https://clp.bbcrewind.co.uk/e2b5dd518bb6fca385dbc4368148bdc1)



## Demos
[Demos 1](https://docs.google.com/document/d/1xf0PaTv_Pc2hxcHCOmVNEVzL_oX9RWF4T6JbAlzSiU8/edit?usp=sharing)



# Mathematics of Data Science – Tool Setup Guide 

Welcome to the Mathematics of Data Science course!  
This guide will help you set up all the tools we will use this semester:

- **ChatGPT** – for AI-assisted learning, coding help, and conceptual questions.
- **Google Colab** – for Python coding, data analysis, and visualization.
- **GitHub** – for version control, collaboration, and hosting a simple website.

---

## 1. Setting Up ChatGPT

### Steps
1. Go to [https://chat.openai.com](https://chat.openai.com).
2. Sign up with your email or Google account.
3. Familiarize yourself with the interface:
   - Left sidebar: Access chat history and settings.
   - Main window: Chat with the model.
4. (Optional) Enable **Custom Instructions** in settings to let ChatGPT know your learning goals.

### Simple Conversation Task
Open ChatGPT and try asking:
> "Explain what Data Science is in simple terms."

Then ask:
> "Write a small Python script to print the first 5 even numbers."

---

## 2. Setting Up Google Colab

### Steps
1. Go to [https://colab.research.google.com](https://colab.research.google.com).
2. Sign in with your Google account.
3. Click **New Notebook**.
4. Make sure the runtime is set to **Python 3**:  
   `Runtime → Change runtime type → Python 3`.

### Task – Create a Simple Scatter Plot
1. In a Colab cell, paste the following code:
   ```python
   import matplotlib.pyplot as plt

   # Sample data
   x = [1, 2, 3, 4, 5]
   y = [2, 4, 1, 8, 7]

   # Create scatter plot
   plt.scatter(x, y, color='blue')
   plt.title("Simple Scatter Plot")
   plt.xlabel("X-axis")
   plt.ylabel("Y-axis")
   plt.show()
   ```
2. Run the cell and verify the plot appears.

---

## 3. Setting Up GitHub

### Steps
1. Go to [https://github.com](https://github.com) and sign up.
2. Choose a username, email, and password.
3. Verify your email.
4. Install **Git** (if working locally) from [https://git-scm.com](https://git-scm.com).

### Create a Repository
1. On GitHub, click **New** (top-right).
2. Repository name: `my-first-website`.
3. Description: `A simple Hello World site for Mathematics of Data Science`.
4. Check **Public**.
5. Check **Add a README file**.
6. Click **Create repository**.

### Add a Simple Hello World Page
1. In your new repository, click **Add file → Create new file**.
2. Name it `index.html`.
3. Paste this HTML:
   ```html
   <!DOCTYPE html>
   <html>
   <head>
       <title>Hello World</title>
   </head>
   <body>
       <h1>Hello, World!</h1>
       <p>This is my first GitHub Pages website for Mathematics of Data Science.</p>
   </body>
   </html>
   ```
4. Commit changes.

### Enable GitHub Pages
1. Go to your repository **Settings → Pages**.
2. Under **Source**, choose `main` branch and `/ (root)`.
3. Click **Save**.
4. Your site will be available at:
   ```
   https://<your-username>.github.io/my-first-website/
   ```

---

## 4. Summary of Tasks
- **ChatGPT:** Ask a question about Data Science, then ask for a Python script.
- **Colab:** Create and run a scatter plot.
- **GitHub:** Create a repo, add an HTML file, and publish it via GitHub Pages.

