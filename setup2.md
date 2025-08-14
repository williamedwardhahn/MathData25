# Mathematics of Data Science – Follow-Up Lesson

This lesson builds on our initial setup with **ChatGPT**, **Google Colab**, and **GitHub**.  
We will do slightly more advanced tasks in each tool.

---

## 1. ChatGPT – Data Science and Python

### Goal
Use ChatGPT for more interactive and practical data science examples.

### Task
Ask ChatGPT:
> "Generate Python code that loads the Iris dataset from scikit-learn, trains a simple Decision Tree classifier, and prints the accuracy."

**Follow-up:** Ask ChatGPT to:
> "Modify the code to plot the decision boundaries for two features."

This helps you learn how to request code improvements and visualizations.

---

## 2. Google Colab – Data Visualization and Analysis

### Goal
Move from a simple scatter plot to a labeled and styled one, using random data.

### Task
In Colab, paste and run:
```python
import matplotlib.pyplot as plt
import numpy as np

# Generate random data
np.random.seed(42)
x = np.random.rand(50)
y = np.random.rand(50)
colors = np.random.rand(50)
sizes = 1000 * np.random.rand(50)

# Create styled scatter plot
plt.scatter(x, y, s=sizes, c=colors, alpha=0.5, cmap='viridis')
plt.title("Advanced Scatter Plot")
plt.xlabel("Random X")
plt.ylabel("Random Y")
plt.colorbar(label="Color scale")
plt.show()
```

**Follow-up:** Try changing the colormap from `'viridis'` to `'plasma'` or `'cool'`.

---

## 3. GitHub – Updating and Expanding Your Website

### Goal
Add an interactive table to your GitHub Pages website.

### Task
1. Open your `my-first-website` repository on GitHub.
2. Edit the `index.html` file.
3. Replace the body section with:
```html
<body>
    <h1>Hello, World!</h1>
    <p>This is my first GitHub Pages website for Mathematics of Data Science.</p>

    <h2>Sample Data Table</h2>
    <table border="1" cellpadding="5">
        <tr>
            <th>Name</th>
            <th>Score</th>
        </tr>
        <tr>
            <td>Alice</td>
            <td>95</td>
        </tr>
        <tr>
            <td>Bob</td>
            <td>87</td>
        </tr>
    </table>
</body>
```
4. Commit the changes.
5. Refresh your GitHub Pages site to see the update.

---

## 4. Summary of Tasks
- **ChatGPT:** Train a Decision Tree classifier and improve the code for visualization.
- **Colab:** Create a colorful, labeled scatter plot with random data.
- **GitHub:** Add a simple HTML data table to your website.

**Next Steps:** In future lessons, we will connect these tools by publishing Colab-generated plots and analyses directly to our GitHub Pages site.

Happy coding! 🚀
