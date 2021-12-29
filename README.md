# covidsgen
## Overview
This repository contains the tools used to create 2D model of Compound Eye Vision.

The basis is an application written using the Python framework called Flask. Deployment:

<pre><code>pip install -r requirements.txt<br>python app/db_create.py<br>flask db upgrade<br>python main.py
</code></pre>
Also there are some Jupiter notebooks used during research:
<ul>
<li>Datasets_Generator.ipynb - used for generation datasets for training NN</li>
<li>Train_distance_model.ipynb - used for training model for distance detection</li>
<li>Train_angle_model.ipynb - used for training model for azimuth detection</li>
<li>Test_models.ipynb - used for testing resulting models</li>
</ul>
Jupiter notebooks uses Wandb platform API 
