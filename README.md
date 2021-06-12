# MercadoLibre Forecasting Analysis & Prophet Model Predictions

## *Introduction*

This **Jupyter notebook** will used **unsupervised learning** to scale down a DataFrame of cryptocurrency price percentage changes, and it will create a scatter plot grouped by resulting cluster groups created by the **K-Means algorithm**.

---

## Technologies

**Python 3.7.9** was used to code this **Jupyter notebook** application, but was run in **Google Colab**. In order for this notebook to run properly, the following Python libararies need to be installed in the notebook: **Pandas**, **PyStan**, **FBProphet**, **HvPlot**, **Holoviews**, **Datetime**, and **MatPlotLib**.

---

## Installation Guide

To run this **Jupyter notebook** specifically in **Google Colab**, go to **colab.research.google.com**.  From there, you can upload the notebook once prompted:

![step1](https://user-images.githubusercontent.com/80929342/121786666-42123100-cb76-11eb-834a-1ab2d3258704.JPG)

Another important thing to note: in order for the **HvPlot visualizations** to display correctly in **Google Colab**, the following line of code should be run:

```python
hv.extension('bokeh')
```

![step2](https://user-images.githubusercontent.com/80929342/121786698-81408200-cb76-11eb-8f3f-525a02470773.JPG)

---

## Examples & Usage

The notebook will start off by importing and installing all the required libraries and dependencies to run to the analysis:

![step3](https://user-images.githubusercontent.com/80929342/121786792-0a57b900-cb77-11eb-8d28-242cbb680154.JPG)

---

Since this notebook is run in **Google Colab**, we will use this line of code to upload the appropriate CSV files to create DataFrames:

```python
from google.colab import files
uploaded = files.upload()
```

![step6](https://user-images.githubusercontent.com/80929342/121787637-0b3f1980-cb7c-11eb-9995-26214e3aece8.JPG)

The other option to import the CSV files is to simply navigate to the folder icon on the left hand side menu, and drag and drop the CSV file in the session:

![step7](https://user-images.githubusercontent.com/80929342/121787678-5822f000-cb7c-11eb-944d-e85b45018358.JPG)

---

Using **groupby**, we will be able to run analysis on the search trends for MercadoLibre:

![step4](https://user-images.githubusercontent.com/80929342/121786999-56efc400-cb78-11eb-96df-d0c5f329e3e9.JPG)

---

Multiple visualizations are utilized, one of them being **Heatmaps** to get a gauge on search trends:

![step5](https://user-images.githubusercontent.com/80929342/121787565-a08dde00-cb7b-11eb-8a6c-6d331abcdaff.JPG)

---

A **correlation table** is created to help us forecast any relationships between Stock Volatility, Search Trends, and Hourly Stock Returns:

![step8](https://user-images.githubusercontent.com/80929342/121787706-8e606f80-cb7c-11eb-88ae-ca67bdcc85e9.JPG)

---
Finally, we will create a **Prophet** model to help forecast the popularity and success of MercadoLibre's operations:

![step9](https://user-images.githubusercontent.com/80929342/121787741-d5e6fb80-cb7c-11eb-95fa-1da45aa3303f.JPG)

---

## Contributors

**I would like to thank and acknowledge my UCB FINTECH Class for their questions and input that contribute to the success and knowledge base for the class!**

---

## License

No license is needed to use this app.
