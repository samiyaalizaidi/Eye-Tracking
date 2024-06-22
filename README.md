# Identifying ASD Symptoms using Eye Tracking Techniques

Autism Spectrum Disorder (ASD) affects millions of children globally, impacting their social interaction, communication skills, and behavior. Early diagnosis (ideally before age 3) is essential for maximizing the effectiveness of interventions and improving long-term outcomes. However, current diagnostic methods often rely on behavioral observations, which can be subjective and time-consuming.

This project focuses on exploring the potential of eye-tracking technology combined with deep learning for early detection of ASD. Eye movements provide valuable insights into an individual’s visual attention and information processing. Studies suggest that children with ASD exhibit atypical gaze patterns, including reduced attention to faces and social cues.

## Project Goals

1. **Develop a Generic Eye Tracking Model:**
   - Implement a baseline model using existing eye-tracking datasets.

2. **Analyze ASD-Specific Patterns:**
   - Identify and analyze unique eye movement patterns in ASD patients.

3. **Fine-Tune Model for ASD Detection:**
   - Adjust the generic model to better detect ASD-specific patterns.

4. **Evaluate and Iterate:**
   - Assess the performance of the fine-tuned model and continuously improve it.

## Repository Structure

- `data/`: Contains eye-tracking datasets used for training and evaluation.
- `notebooks/`: Jupyter notebooks with exploratory data analysis, model development, and evaluation.
- `models/`: Saved models and training logs.
- `scripts/`: Python scripts for data preprocessing, model training, and evaluation.
- `results/`: Evaluation metrics, plots, and findings from the experiments.
- `README.md`: Project overview and instructions.

## Getting Started

### Prerequisites

- Python 3.x
- Jupyter Notebook
- Libraries: TensorFlow, Keras, Pandas, NumPy, Matplotlib, Scikit-learn

### Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/ASD-Eye-Tracking.git
   cd ASD-Eye-Tracking
   ```

2. Create and activate a virtual environment:
   ```sh
   python -m venv venv
   source venv/bin/activate   # On Windows use `venv\Scripts\activate`
   ```

3. Install the required libraries:
   ```sh
   pip install -r requirements.txt
   ```

## Contributing
Contributions are welcome! Please follow these steps:

1. Fork the repository.
2. Create a new branch (`git checkout -b feature-branch`).
3. Commit your changes (`git commit -m 'Added some feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a pull request.
