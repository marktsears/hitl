# HITL Python Library

HITL makes it easy and cost-effective to inject human cognition anywhere in a live production AI workflow and close the reliability gap.
With one API call you can resolve critical blockers or low-performance inferences in real-time using our last mile automation and managed workforce. 
We want to empower you to launch and scale revolutionary automation products faster than ever before.

Common ways engineering and product teams leverage HITL include:

Resolving low-confidence predictions, live in production
Launching new products and features with in-development AI models
Injecting additional human oversight for safety-critical systems
Real-time quality assurance of model outputs
Real-time system health checks & conditional escalation
Reinforcing or correcting confidence of AI-based decisions
Bootstrapping new models for evaluation with customers

# Quickstart

Get started with HITL in four steps:

1. First, sign up for a [free HITL account](https://wandb.ai/login?utm_source=github&utm_medium=code&utm_campaign=wandb&utm_content=quickstart).

2. Second, install the HITL SDK with [pip](https://pip.pypa.io/en/stable/). Navigate to your terminal and type the following command:

```bash
pip install hitl
```

3. Third, log into HITL:

```python
hitl.login()
```

4. Use the example code snippet below as a template to integrate HITL to your Python script:

```python
import hitl

# Start a HITL Run with hitl.init
run = hitl.init(project="my_first_project")

# Save model inputs and hyperparameters in a hitl.config object
config = run.config
config.learning_rate = 0.01

# Model training code here ...

import hitl.HitlCompletion
client = HitlCompletion('PROVIDED_API_KEY')
url = https://picsum.photos/200/300
instructions = 'Confirm this inference that the image contains a pylon'
token = client.create_engagement_from_image_url
hitl_completion = hitl.HitlCompletion.create_from_url(url, instructions=instructions)

```

That's it! Navigate to the HITL App to view a dashboard of your resolutions.

<p align='center'>
<img src="https://www.spark.ai/hs-fs/hubfs/exceptions-solved-feature-image-v2%20(1).jpg" width="100%">
</p>
<p align = "center">
Example HITL Dashboard that shows recent completions.
</p>


### Model Monitoring

 [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/newrelic-experimental/ml-performance-monitoring/blob/main/examples/XGBoost_on_California_housing_prices_dataset.ipynb) easily try an end-to-end example of model monitoring.

```python

# STEP 1: Initialize the monitoring
ml_monitor = MLPerformanceMonitoring(...)

# STEP 2: Add your algorithm
y = my_model.predict(X)

# STEP 3: Record your data
ml_monitor.record_inference_data(X, y)
```

Done! Check your real time data in the HITL App
<p align='center'>
<img src="https://newrelic.com/sites/default/files/styles/1200w/public/2021-12/model-performance-monitoring.png?itok=CvQuxw2S" width="100%">
</p>
<p align = "center">
to see the real time data.
</p>



[HITL UI]() to see the real time data.

