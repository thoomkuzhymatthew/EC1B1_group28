# EC1B1 Coursework Group 28

# Contributors:
1. Matthew Thoomkuzhy (m.thoomkuzhy@lse.ac.uk)
2. Jay Desai (j.desai3@lse.ac.uk)
3. Xinyan Liao (x.liao10@lse.ac.uk)
4. Joshua Jooste (j.jooste@lse.ac.uk)

# Note:
We had a discussion with David about our choice to use GitHub for ease of collaboration between us and he gave us the green light. We have provided instructions on how to run our code and all our resulting plots have been included in the PDF.

# How to Run This Project

### 1. Clone the Repository  
Clone this repository to your local machine:  
```bash
git clone https://github.com/thoomkuzhymatthew/EC1B1_group28
cd EC1B1_group 28

```
### 2. Set Up the Python Environment  
Use **conda** or **pyenv** to create and activate the environment.

#### With Conda:  
```bash
conda create -n group-28 python=3.9 -y
conda activate group-28
pip install -r requirements.txt
```

#### With Pyenv + Virtualenv:
``` bash
python -m venv .venv
.venv\Scripts\activate # If on Windows
source .venv/bin/activate # If on macOS/Linux
pip install -r requirements.txt
```
---

### 3. Run the Code  

#### Section_4.ipynb: Data Collection  
This notebook collects and cleans data from IMF to generate one final data frame `final_df` which forms the basis for subsequent analysis in Sections 5 and Sections 6.1.

#### Section_5.ipynb: Analysis  
This notebook addresses the requirements for Section 5 of the instructions, ranging from visualising time-series plots to volatility plots to regression analyses. 

#### Section_6.1.ipynb: Extension Part 1
This notebook investigates the average levels of nominal, real exchange rates, inflation and industrial production growth pre and post Bretton-Woods. 

#### Section_6.2.ipynb: Extension Part 2
This notebook analyses the impact of the UK joining the ERM on its economy.



