# Pediatric-Sepsis-Data-Challenge

## Background 
Sepsis, a severe response to infection leading to organ dysfunction or death, is a leading cause of mortality in children, particularly in developing countries. In 2017, an estimated 48.9 million cases of sepsis were reported globally, with children accounting for over half of these cases. A staggering 85% of these cases occurred in low- and middle-income countries. Many sepsis-related deaths could be prevented with early detection and timely treatment using simple, highly effective interventions like antimicrobials and fluid resuscitation. The 2024 Pediatric Sepsis Data Challenge was created to help address this critical gap in healthcare.

## The dataset and challenge objective
The data for the 2024 Pediatric Sepsis Data Challenge comes from a deidentified, curated research dataset of a study called “Smart discharges to improve post-discharge health outcomes in children: A prospective before-after study with staggered implementation”. This study enrolled children under 5 years of age who were admitted with a proven or suspected infectious illness. This dataset is limited to the in-hospital period, and contains clinical, social and demographic data captured at the point of hospital admission. Participants will be provided with a synthetically generated training data set to reduce the risk of patient re-identification. The synthetic training set was generated from a random subset of the original data. Solutions will be evaluated against the remaining original dataset that will be unseen and unavailable to participants.
The challenge is to design and implement a working, open-source algorithm that can predict in-hospital mortality from routinely collected data at the time of presentation to a health facility in Uganda.

The solution is in an .ipynb file [Gut Health Classification notebook](https://github.com/edimaudo/Gut-Microbe-Disease-Classification/blob/main/Gut_Health_Classification.ipynb).

## How to run the file
Running a Jupyter Notebook (.ipynb file) can be achieved through several methods, primarily using Jupyter Notebook itself, cloud-based services like Google Colab, or integrated development environments (IDEs) like VS Code.

Using Jupyter Notebook (Local Installation):
Install Jupyter Notebook: If you don't have it, install Anaconda (which includes Jupyter) or install Jupyter Notebook directly via pip:
Code

```
    pip install notebook
```
Launch Jupyter Notebook: Open your terminal or Anaconda Prompt and type:
Code
```
    jupyter notebook
```
This will open a new tab in your web browser, displaying the Jupyter Notebook dashboard.
Navigate and Open: In the dashboard, navigate to the directory where your .ipynb file is located and click on the file name to open it.
Run Cells: Once the notebook is open, you can run individual cells by clicking the "Run" button or using keyboard shortcuts like Shift + Enter (run and move to next cell) or Ctrl + Enter (run and stay on current cell).
Stop the Server: Close the browser tab and then stop the server running in your terminal/command prompt (usually by pressing Ctrl + C).
