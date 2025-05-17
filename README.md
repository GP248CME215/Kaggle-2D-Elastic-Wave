1. training_model-FNO-baseline-2.ipynb is the model that produces the baseline model uploaded by us in the kaggle contest
2. training_model_FNO_colab.ipynb is the model with using half of the dataset, smaller size FNO compared to the baseline model to avoid crashing Colab RAM.
3. You might want to use Colab to develope and debug your code, and use the virtual machine to train the model as you might easily crash your the Colab RAM with full dataset and large FNO model
4. In Colab, in the "Runtime" pannel, you will can go into "Change runtime type" to choose CPU, GPU or TPU. But make sure if you choose GPU, shut down the runtime to avoid wasting limited runtime resources. 
