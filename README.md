# GenX: AI-Powered Genomic Hybridization Analysis and Prediction

GenX is an open-source computational framework for simulating, analyzing, and predicting the viability of hybrid genomes across species. Designed for researchers in genomics, evolutionary biology, conservation, and agriculture, GenX leverages biologically informed sequence fusion and machine learning to provide rapid, in silico insights into hybridization outcomes—reducing the need for resource-intensive laboratory experiments.

---

## 🚀 Key Features

- **Window-Based Hybrid Sequence Generation:**  
  Simulate realistic hybrid DNA by fusing parent genomes in configurable windows, preserving essential genetic elements (e.g., start codons), and introducing biologically plausible mutations.

- **Comprehensive Genomic Feature Extraction:**  
  Automatically compute critical sequence features, including GC/AT content, CG dinucleotide frequency, sequence length, complexity metrics, and codon usage patterns.

- **Machine Learning-Based Viability Prediction:**  
  Predict hybrid viability using a Random Forest classifier trained on simulated data, achieving over 85% accuracy with robust cross-validation.

- **Interactive Visualization Suite:**  
  Visualize feature distributions, inheritance patterns, crossover points, mutation events, and model confidence intervals for intuitive interpretation of results.

---

## 🧬 Typical Workflow

1. **Load Parental Genomes:**  
   Import FASTA files for two parent species.

2. **Hybrid Sequence Generation:**  
   Configure window size and mutation rate to generate synthetic hybrid genomes.

3. **Feature Extraction & Analysis:**  
   Automatically extract genomic features from parent and hybrid sequences.

4. **Viability Prediction & Visualization:**  
   Use the trained ML model to predict hybrid viability and generate interactive visual reports.

---

## 🛠️ Technologies Used

- **Python 3.11**: Core implementation language.
- **BioPython**: Sequence parsing and manipulation.
- **scikit-learn**: Machine learning (Random Forest, model evaluation).
- **pandas & NumPy**: Data management and numerical analysis.
- **Matplotlib & Seaborn**: Data visualization.

---

## 🧪 Methodology

- **Hybrid Sequence Generation**:  
  Window-based fusion algorithm with mutation injection and codon preservation.

- **Feature Extraction**:  
  Calculate nucleotide composition, dinucleotide frequencies, sequence entropy, and codon adaptation indices.

- **Predictive Modeling**:  
  Train and validate a Random Forest classifier on simulated hybrid data with stratified splits and balanced classes.

- **Inheritance & Visualization**:  
  Quantify parental contributions, map crossover events, and visualize results with confidence metrics.

---

## 🔭 Future Enhancements

- **Deep Learning Integration**:  
  Incorporate CNN/LSTM models to capture complex regulatory patterns and improve predictions.

- **Multi-Omics Data Support**:  
  Extend feature extraction to include transcriptomic and epigenomic data.

- **Expanded Training Data**:  
  Integrate empirical hybridization outcomes from diverse taxa for broader applicability.

- **User-Friendly Interface**:  
  Develop a GUI or web platform for non-technical users.

---

## 📈 Applications

- **Conservation Genetics**: Assess hybridization strategies for endangered species.
- **Agriculture**: Screen for promising hybrid crops with desired traits.
- **Evolutionary Biology**: Explore speciation and hybrid zone dynamics.
- **Synthetic Biology**: Design and evaluate synthetic genomes before laboratory synthesis.

---

## 📚 Getting Started

1. Clone the repository and install requirements.
2. Prepare your parental genome FASTA files.
3. Run the Jupyter notebook or Python scripts to generate and analyze hybrids.
4. Explore the visualizations and interpret the model’s predictions.

---

## 🤝 Contributing

We welcome contributions! Please open issues for bugs or feature requests, and submit pull requests for improvements.

---

## 📄 License

This project is released under the MIT License.

---

**GenX** empowers researchers to explore the genetic landscape of hybridization—safely, efficiently, and at scale.


---
