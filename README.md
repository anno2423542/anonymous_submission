# anonymous_submission

Code for SEARL with TD3.

##### Easy setup:

```
git clone https://github.com/anno2423542/anonymous_submission.git
cd anonymous_submission
python3 -m venv venv
source venv/bin/activate
pip install -e .
```

Eventually, adjust PyTorch version for your personal Cuda setup. To repeat experiments a mujoco license is required. 
A free 30 days test license is available at https://www.roboti.us/license.html.  


##### Start training:

```
python searl/train_population.py --config=searl/config.yml --expt=experiment
```

All results will be written in the folder "experiment".
To change seed, environment or hyperparameters please edit `searl/config.yml`




