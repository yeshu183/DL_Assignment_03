# Deep Learning Assignment 03: Sequence-to-Sequence Transliteration

This repository contains the implementation of a sequence-to-sequence model for transliteration between Roman script and Hindi. The assignment explores various aspects of sequence-to-sequence models, including attention mechanisms and visualization techniques.

### wandb link : https://wandb.ai/yeshu183-indian-institute-of-technology-madras/DA6401_Assignment_03/reports/DA24M009-Assignment-3--VmlldzoxMjc3MzI4Mw?accessToken=hzfrpz3rx30uoot8v1p0v7fun1cc3jnylni81olhfmbklndk4t8zwuf7g1n3ytd9

## Repository Structure

The repository contains two main notebooks:
1. `dl-assign-03-v.ipynb`: Implements Questions 1-4, covering basic sequence-to-sequence models
2. `attention_model.ipynb`: Implements Questions 5-6, covering attention mechanisms and visualizations

## Requirements

- Python 3.8+
- PyTorch
- Pandas
- NumPy
- Matplotlib
- Bokeh (for Q6 visualization)
- Weights & Biases (wandb)
- Hindi font (included in the repository)

## Dataset

The assignment uses the Dakshina dataset for Hindi transliteration. The dataset contains pairs of words in Roman script and their corresponding Hindi transliterations.

## Implementation Details

### Questions 1-4 (Basic Seq2Seq)

- Question 1: Implementing the dataset class and sequence-to-sequence model
- Question 2: Hyperparameter tuning using WandB sweeps
- Question 3: Analysis of hyperparameter sweep results
- Question 4: Evaluation on test data and error analysis

### Questions 5-6 (Attention Mechanism and Visualization)

- Question 5: Implementation of an attention-based sequence-to-sequence model
- Question 6: Visualization of attention weights to understand model behavior

## How to Run

1. Clone the repository:
```bash
git clone https://github.com/yeshu183/DL_Assignment_03.git
cd DL_Assignment_03
```
2. Run the notebooks:
```bash
jupyter notebook
```

3. For Question 6 visualization:
   - Download the HTML files generated in the `attention_connectivity_visualizations` directory
   - Open the HTML files in a web browser to view the interactive attention visualizations
   - Alternatively, open the `index.html` file which provides links to all visualizations

## Attention Visualization

The attention visualization for Question 6 shows which input characters the model is focusing on when generating each output character. This is similar to the "Connectivity" figure in the [Distill article](https://distill.pub/2019/memorization-in-rnns/#appendix-autocomplete).

To view the visualizations:
1. Download the HTML file from the `attention_connectivity_visualizations` directory
2. Open the files in a web browser
3. Use the slider to see how attention shifts as different output characters are generated

## Results

The repository includes:
- Trained models for both vanilla and attention-based sequence-to-sequence architectures
- Analysis of hyperparameter tuning results
- Visualizations of model performance and attention weights
- Error analysis and comparisons between different model architectures

