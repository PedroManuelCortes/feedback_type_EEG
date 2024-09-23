# feedback_type_EEG

This repository contains raw data related to the article titled **"Interaction between feedback type and the stages of decision-making: cortical EEG connectivity"**. The data includes behavioral and EEG data collected from participants in a decision-making experiment.

## Description

The dataset focuses on exploring how different types of feedback affect the stages of decision-making, with a specific focus on EEG connectivity. The data is divided into two categories:

- **Behavioral Data**: This data includes participant responses and behavioral metrics during the decision-making tasks.
- **EEG Data**: Raw EEG recordings were collected during the decision-making tasks to analyze cortical connectivity patterns.

## Repository Structure

The dataset is structured as follows:

- `behavior_data/`: Contains behavioral data files in `.RES` format.
  - Each file follows a specific naming convention:
    - The first two digits represent the participant number.
    - The next four letters correspond to the experiment name.
    - The final two letters represent the experimental condition.

- `EEG_data/`: Contains EEG recordings in `.txt` format.
  - Each file follows a specific naming convention:
    - The first two digits represent the participant number.
    - The next two letters represent the experimental condition.
    - The final two digits represent the phase of the decision-making process.

## Nomenclature for Data Files

### Behavioral Data

Behavioral data files are named using the following structure:

- **[Participant Number] [Experiment Name] [Condition]**
  
  For example: `01EXPA01.RES` refers to participant 01, experiment "EXPA", and condition "01".

### EEG Data

EEG data files are named using the following structure:

- **[Participant Number] [Condition] [Phase]**

  For example: `01CA01.txt` refers to participant 01, condition "CA", and phase "01" of the decision-making process.

## System Requirements

### Software Dependencies

- **Operating System**: 
  - Windows 10 or higher
- **Data Processing Software**:
  - EEG data analysis tools (e.g., EEGLAB for MATLAB)
  - Any text editor or Python script for parsing `.txt` and `.RES` files.

## Usage

1. **Behavioral Data**:
   - Use the `.RES` files for analyzing participant behavior during the decision-making tasks.
   - Data can be loaded into Python, R, or other data analysis tools that support text file parsing.

2. **EEG Data**:
   - The raw EEG `.txt` files can be imported into EEG analysis software such as EEGLAB (MATLAB).
   - The files are structured with the naming convention mentioned above, so you can select files based on participant number, condition, and phase.

## Data Collection

- **Participants**: Each participant completed several decision-making tasks under different conditions, with their behavior and brain activity recorded.
- **Conditions**: The experiment was conducted under various feedback conditions, and the stages of decision-making were identified based on EEG recordings.

## Contact

For more information or questions, contact [pedro.cortes@tec.mx](mailto:pedro.cortes@tec.mx).

