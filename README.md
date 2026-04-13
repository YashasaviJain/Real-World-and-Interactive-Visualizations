# 📊 Experiment 19 – Real-World and Interactive Visualizations

## 🧪 Aim
The aim of this experiment is to explore **real-world and interactive data visualization techniques** using advanced Python libraries. The focus is on representing complex datasets in interactive and multi-dimensional formats to improve data interpretation and decision-making.

---

## 📘 Theory

Modern data visualization goes beyond static graphs and includes **interactive and hierarchical visualizations** that help in analyzing real-world scenarios. This experiment uses libraries like **Plotly**, **Matplotlib**, **Pandas**, **NumPy**, and **SciPy** to create dynamic and insightful visualizations.

### Key Visualization Techniques Used:

1. **Treemap**
   - Represents hierarchical data using nested rectangles.
   - Useful for comparing proportions across categories.

2. **Dendrogram**
   - Used in hierarchical clustering.
   - Shows relationships and grouping between data points.

3. **Venn Diagram**
   - Illustrates logical relationships between sets.
   - Highlights intersections and unique elements.

4. **Sankey Diagram**
   - Visualizes flow of data or resources between stages.
   - Width of flow represents quantity.

5. **3D Scatter Plot**
   - Displays relationships among three variables.
   - Useful for multi-dimensional analysis.

6. **Radar Chart (Spider Chart)**
   - Displays multi-variable data in a circular format.
   - Commonly used for performance or skill comparison.

---

## ⚙️ Algorithm

1. Import required libraries: Pandas, Plotly, NumPy, Matplotlib, SciPy.
2. Create a dataset representing departmental budgets.
3. Generate Treemap to visualize budget distribution.
4. Create sample numerical data for clustering.
5. Perform hierarchical clustering using linkage method.
6. Plot Dendrogram to show cluster relationships.
7. Define two sets for comparison.
8. Generate Venn Diagram to visualize set intersections.
9. Create Sankey Diagram representing flow of students.
10. Prepare dataset for student performance analysis.
11. Generate 3D Scatter Plot for multi-variable comparison.
12. Define skill categories and corresponding values.
13. Create Radar Chart to represent skill assessment.
14. Display all visualizations interactively.

---

## 🛠️ Commands Used and Their Features

### 📦 Libraries
- `pandas`
  - Used for creating and managing datasets in tabular format.

- `plotly.express`
  - High-level interface for creating interactive visualizations.
  - Supports treemaps, scatter plots, and 3D charts.

- `plotly.graph_objects`
  - Provides detailed control over interactive plots.
  - Used for Sankey and Radar charts.

- `matplotlib.pyplot`
  - Used for static plotting and customization.

- `numpy`
  - Used for numerical operations and data generation.

- `scipy.cluster.hierarchy`
  - Used for hierarchical clustering and dendrogram visualization.

- `matplotlib_venn`
  - Used to create Venn diagrams for set relationships.

---

### 🔧 Functions and Methods

- `pd.DataFrame()`
  - Creates structured datasets.

- `px.treemap()`
  - Generates interactive treemap visualizations.

- `linkage()`
  - Performs hierarchical clustering on data.

- `dendrogram()`
  - Plots hierarchical clustering structure.

- `venn2()`
  - Creates Venn diagram for two sets.

- `go.Sankey()`
  - Generates Sankey diagrams showing flow between nodes.

- `go.Figure()`
  - Initializes a Plotly figure object.

- `px.scatter_3d()`
  - Creates interactive 3D scatter plots.

- `go.Scatterpolar()`
  - Generates radar (polar) charts.

- `fig.show()`
  - Displays interactive Plotly visualizations.

---

## ✅ Conclusion

This experiment demonstrates the power of **interactive and real-world data visualization techniques**. Unlike basic plots, these visualizations allow:

- Better understanding of hierarchical and relational data.
- Interactive exploration of datasets.
- Representation of multi-dimensional and flow-based data.
- Enhanced user engagement and analytical clarity.

Using advanced tools like Plotly and SciPy, complex datasets can be visualized effectively, making this approach highly valuable in real-world applications such as business analytics, clustering analysis, and performance evaluation.

---
