# AI in Healthcare - Course Materials

This repository contains comprehensive course materials for the **AI in Healthcare** class at aSSIST. The materials include lecture notes, assignments, prompt examples for working with AI systems, and synthetic patient data for hands-on learning.

## 📚 Repository Contents

### 1. Course Materials (`/course_materials`)
Structured educational content for the course:

#### Lectures (`/course_materials/lectures`)
- **Lecture 1**: Introduction to AI in Healthcare
  - AI fundamentals and healthcare applications
  - Benefits, challenges, and ethical considerations
  - Case studies and real-world examples

- **Lecture 2**: Machine Learning Fundamentals for Healthcare
  - Core ML concepts and algorithms
  - Healthcare data types
  - ML pipeline from data to deployment
  - Hands-on diabetes prediction exercise

- **Lecture 3**: Deep Learning and Medical Imaging
  - Neural networks and CNNs
  - Medical imaging modalities
  - Image segmentation and analysis
  - Explainable AI for medical imaging

#### Assignments (`/course_materials/assignments`)
- **Assignment 1**: Exploratory Data Analysis of Healthcare Data
- **Assignment 2**: Predictive Modeling for Disease Risk
- **Assignment 3**: AI Healthcare Application Proposal

### 2. Prompt Examples (`/prompt_examples`)
Practical examples for prompting AI systems in healthcare contexts:
- **Diagnosis Assistant**: Symptom analysis and differential diagnosis
- **Treatment Planning**: Comprehensive treatment plan development
- **Medical Education**: Case studies and teaching materials
- **Patient Communication**: Clear health communication examples

See the [Prompt Examples README](./prompt_examples/README.md) for detailed usage guidelines.

### 3. Synthetic Patient Data (`/data/synthetic_patients`)
Educational datasets for hands-on learning:
- `patients_basic.csv` - Demographics and vital signs (20 patients)
- `patients_diabetes.json` - Detailed diabetes patient records (5 patients)
- `patients_cardiology.json` - Cardiology patient data (5 patients)
- `lab_results.csv` - Laboratory test results (50+ tests)

**⚠️ Important**: All patient data is synthetic and generated for educational purposes only. Do not use for actual clinical decisions.

## 🎯 Learning Objectives

By completing this course, students will be able to:
1. Understand fundamental concepts of AI and machine learning in healthcare
2. Apply ML algorithms to healthcare datasets
3. Build and evaluate predictive models for clinical outcomes
4. Analyze medical images using deep learning
5. Consider ethical, legal, and practical implications of healthcare AI
6. Design AI-powered healthcare applications
7. Effectively prompt and interact with medical AI systems

## 🚀 Getting Started

### Prerequisites
- Basic programming knowledge (Python recommended)
- Understanding of basic statistics
- Interest in healthcare and technology
- Access to a computer with Python 3.7+ installed

### Setup Instructions

1. **Clone the repository**
   ```bash
   git clone https://github.com/jaeyong8687/AI-in-healthcare.git
   cd AI-in-healthcare
   ```

2. **Install required packages** (recommended: use virtual environment)
   ```bash
   # Create virtual environment
   python -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   
   # Install packages
   pip install pandas numpy matplotlib seaborn scikit-learn jupyter
   ```

3. **Explore the materials**
   - Start with Lecture 1 in `/course_materials/lectures`
   - Review prompt examples in `/prompt_examples`
   - Load and explore synthetic data in `/data/synthetic_patients`

4. **Run Jupyter Notebook** (for assignments)
   ```bash
   jupyter notebook
   ```

## 📖 Course Structure

### Week 1-2: Foundations
- Introduction to AI in Healthcare
- Healthcare data types and sources
- Ethical considerations

### Week 3-4: Machine Learning Basics
- Supervised and unsupervised learning
- Feature engineering for healthcare
- Model evaluation metrics
- **Assignment 1 Due**: EDA of Healthcare Data

### Week 5-6: Advanced ML and Deep Learning
- Deep learning fundamentals
- CNNs for medical imaging
- Model interpretability
- **Assignment 2 Due**: Predictive Modeling

### Week 7-8: Specialized Topics
- Natural language processing for clinical notes
- Time-series analysis for patient monitoring
- Federated learning and privacy

### Week 9-10: Implementation and Ethics
- Regulatory considerations (FDA, HIPAA)
- Clinical workflow integration
- Bias and fairness in healthcare AI
- **Assignment 3 Due**: Application Proposal

### Week 11-12: Final Projects
- Student presentations
- Peer feedback
- Course wrap-up

## 🤝 How to Use This Repository

### For Students
- Follow lectures in sequence
- Complete assignments using provided data
- Practice with prompt examples
- Experiment with synthetic datasets
- Ask questions via course discussion forums

### For Instructors
- Adapt materials to your curriculum
- Use as templates for your own content
- Contribute improvements back to the repository
- Share feedback and suggestions

## 📊 Dataset Details

All datasets are synthetic and created following these principles:
- Realistic clinical scenarios
- Diverse patient demographics
- Common conditions and comorbidities
- Appropriate value ranges for lab tests
- Privacy-preserving by design

See [Data README](./data/synthetic_patients/README.md) for detailed information.

## ⚖️ Ethical Guidelines

When working with these materials:
1. **Privacy First**: Always treat synthetic data as if it were real
2. **No Clinical Use**: Never use AI outputs for actual patient care
3. **Verify Information**: Cross-check all medical facts
4. **Consider Bias**: Be aware of potential biases in AI systems
5. **Respect Regulations**: Understand HIPAA, GDPR, and other regulations

## 🛠️ Tools and Technologies

Recommended tools for this course:
- **Python**: Primary programming language
- **Jupyter**: Interactive notebooks
- **Pandas**: Data manipulation
- **Scikit-learn**: Machine learning
- **TensorFlow/PyTorch**: Deep learning
- **Matplotlib/Seaborn**: Visualization

## 📚 Additional Resources

### Recommended Reading
- Topol, E. "Deep Medicine" (2019)
- Rajkomar et al. "Machine Learning in Medicine" NEJM (2019)
- Yu et al. "Artificial Intelligence in Healthcare" Nature BME (2018)

### Online Resources
- [Stanford ML for Healthcare](https://ml4health.github.io/)
- [MIT Critical Data](https://criticaldata.mit.edu/)
- [Healthcare AI News](https://www.healthcareitnews.com/ai)

### Datasets for Further Learning
- MIMIC-III (ICU data)
- NIH ChestX-ray14
- UK Biobank
- TCGA (cancer genomics)

## 🤝 Contributing

Contributions are welcome! Please:
1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Submit a pull request

Areas for contribution:
- Additional lecture materials
- More prompt examples
- Expanded datasets
- Bug fixes and improvements
- Translation to other languages

## 📝 License

This educational material is provided for academic use. Please cite appropriately if using in your own courses or research.

## 👥 Contact

- **Instructor**: [Instructor Name]
- **Institution**: aSSIST
- **Course Website**: [Course URL]
- **Questions**: [Contact Email]

## 🙏 Acknowledgments

Special thanks to:
- aSSIST for supporting this course
- Healthcare professionals who provided domain expertise
- Students for feedback and contributions
- Open-source community for tools and libraries

## 📅 Updates

- **2024**: Initial repository creation with core materials
- Regular updates with new examples and datasets
- Student feedback incorporated continuously

---

**⚠️ Disclaimer**: This repository is for educational purposes only. All patient data is synthetic. Do not use AI-generated content for actual clinical decision-making without appropriate professional oversight and validation.

## 🎓 Getting Help

- Review lecture materials and assignments carefully
- Check the prompt examples for guidance
- Consult course discussion forums
- Attend office hours
- Reach out to teaching assistants
- Collaborate with classmates (following academic integrity policies)

**Happy Learning! 🚀**
