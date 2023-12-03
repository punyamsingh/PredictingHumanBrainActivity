# PredictingHumanBrainActivity

This project explores the possibility of predicting the word or category a person is thinking about based on functional MRI (fMRI) data. The inspiration for this project comes from the paper by Tom Mitchell et al., titled 'Predicting Human Brain Activity Associated with the Meanings of Nouns' published in Science (vol 320, pp1191-1195, May 30, 2008).

## Objective

The main goal of this project is to build a model that can predict the word or category a subject is thinking about using fMRI data. While brain-computer interfaces (BCIs) have been successfully employed for tasks like wheelchair locomotion and screen pointing, this project aims to extend the prediction to the language/semantic domain.

## Data

The fMRI data for each of the nine subjects, along with additional details, is available in the repository. The data is provided in .mat (Matlab) files, and the scipy Python library can be used to read these files.

## Implementation

The project involves loading and preprocessing the fMRI data, designing a machine learning model, and training it to predict the subject's thoughts based on the provided data structure. The reverse engineering of predicting thoughts from brain activity is a challenging and intriguing aspect of the project.

## Repository Structure

The repository is organized as follows:

- **`datasets/ML_brainData`**: Contains the fMRI data files in .mat format.
- **`datasets/`**: Contains the all data files in .mat format.

## Getting Started

1. Clone the repository:

    ```bash
    git clone https://github.com/kartheekkotha/readBrainfMRI.git 
    ```

2. Install dependencies:

    ```bash
    pip install -r requirements.txt
    ```

3. Explore the Jupyter notebooks in the `notebooks/` directory for a detailed walkthrough of the project.

## Contributions

Contributions are welcome! If you find improvements or have suggestions, please open an issue or create a pull request.

## License

This project is licensed under the [MIT License](LICENSE).


