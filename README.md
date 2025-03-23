# EC1B1 Coursework Group 28

# Contributors:
1. Matthew Thoomkuzhy (m.thoomkuzhy@lse.ac.uk)
2. Jay Desai (j.desai3@lse.ac.uk)
3. Xinyan Liao (x.liao10@lse.ac.uk)
4. Joshua Jooste (j.jooste@lse.ac.uk)

# How to Run This Project

### 1. Clone the Repository  
Clone this repository to your local machine:  
```bash
git clone git@github.com:lse-ds105/ds105a-2024-project-good_gamblers.git
cd ds105a-2024-project-good_gamblers

```
### 2. Set Up the Python Environment  
Use **conda** or **pyenv** to create and activate the environment.

#### With Conda:  
```bash
conda create -n good-gamblers python=3.9 -y
conda activate good-gamblers
pip install -r requirements.txt
```

#### With Pyenv + Virtualenv:
``` bash
python -m venv .venv
.venv\Scripts\activate # If on Windows
source .venv/bin/activate # If on macOS/Linux
pip install -r requirements.txt
```

### 3. Set Up API Plan

![api_plan](./misc/api_plan.png)

The historical odds data is behind a paywall at the Odds API. We purchased a one-month plan and obtained our client credentials, to which we then stored in a `.env` file locally.

If you would like to obtain data yourself, you would have to follow the steps we mentioned. Else, you can work directly with the historical odds data we have already collected in `./data/CSV's`

Here are some reasons as to why we selected the Odds API:
1. Access to Real-Time and Historical Odds
2. Offers Odds from Various Bookmakers to Better Investigate Arbitrage Opportunities
3. Data Reliability and Authenticity

---

### 4. Run the Code  

#### Notebook 1: Data Collection  
Navigate to the `code/` directory and open `NB01 - Data Collection.ipynb`.  
This notebook collects raw data from the Historical Odds API and saves it in the `data/raw/` folder. 

Note: The code here will not run as the data collected was collected using a paid API key.

#### Notebook 2: Data Processing  
Run `NB02 - Data Processing.ipynb` to process the raw data and merge it into an SQL database along with historical outcome data.  

#### Notebook 3: Simple Betting Strategies  
Execute `NB03 - Simple Betting Strategies.ipynb` to explore various basic betting strategies and backtest their performance.  

#### Notebook 4: Arbitrage Betting Strategies  
Run `NB04 - Arbitrage Betting Strategies.ipynb` to investigate both biased and unbiased arbitrage betting strategies and backtest them.  




