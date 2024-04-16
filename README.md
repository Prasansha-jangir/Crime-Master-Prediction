# Crime-Master-Prediction
A crime prediction tool based on Heterogeneous Clustering and an original evaluation metric.
This tool presents a crime prediction solution built upon heterogeneous clustering and a novel evaluation metric. Developed in collaboration with the Data Science Lab at USC (http://dslab.usc.edu/), this algorithm offers insights into crime patterns within a geographical context.

Getting Started
To utilize this tool, ensure you have Python installed on your system. Optionally, if you wish to visualize the results, you can install Jupyter Notebook.

After installation, proceed to install the required packages listed in packages.txt using pip. Next, configure the parameters in config.py according to your preferences and requirements.

Once configured, you can utilize the tool for forecasting and evaluation. A sample usage is provided below

python parse_data.py DPSdata.pkl DPSUSC.pkl
python make_predictions.py LAdata.pkl
python calculate_resource_allocation.py
python plot_allocations.py

Explore the functionalities and adapt the tool to your specific crime prediction needs.
