# Azure_ML
 Predicting, House Price using Azure ML Studio with Python scripting and using Azure Databricks Spark compute Cluster





Learn how companies such as Zillow predict your home's value by building a predictive model using Azure Machine Learning. In this process, we use the Ames housing dataset, comprising 81 features and 1460 observations, each representing a home sale.

To follow along, clone the experiment from the Cortana Intelligence Gallery. The initial steps involve preprocessing and data exploration:

    Drop Low-Value Columns:
    Identify and remove features with little predictive value, such as "Id," "Street," etc., to enhance the model's performance.

    Define Categorical Variables:
    Categorize non-continuous values using the metadata editor, ensuring proper treatment by the machine learning algorithm.

    Clean Missing Data:
    Address missing values by replacing them with appropriate statistical values, such as mean for numerical and mode for categorical.

Moving on to model building:

    Statistical Feature Selection:
    Perform Pearson correlation to filter out features with low predictive strength, selecting the top X features for the model.

    Select an Algorithm:
    Identify the machine learning problem as regression, and use a linear regression model with regularization to prevent overfitting.

    Model Training and Evaluation:
    Implement cross-validation to assess predictive performance and stability across ten models, averaging metrics and analyzing standard deviation.

    Parameter Tuning:
    Optimize the regression model by adjusting parameters, such as lowering L2 regularization weight and increasing training epochs, to improve accuracy and stability.

Finally, the deployment phase involves:

    Deployment:
    Choose the algorithm with the best results (the final tuned model) and retrain it using 100% of the data, as cross-validation leaves 10% out for validation.

This comprehensive process ensures the development of an accurate and stable predictive model for real estate sales prices using Azure Machine Learning.
![Azure_Ml_dataset_dealing_page-0003](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/7cd55049-2f29-4868-a670-d96e72a5759c)





![Azure_Ml_dataset_dealing_page-0004](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/4596938a-8598-481b-b988-890e7b801c44)




![Azure_Ml_dataset_dealing_page-0004](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/6ab1b40c-5e03-4c20-a74b-e3b75b6a7627)

![Azure_Ml_dataset_dealing_page-0009](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/5dc98819-49b8-453d-bc9a-80dac4412d89)




![Azure_Ml_dataset_dealing_page-0001](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/10bc4e95-ee0b-4d58-86e8-2eafecf3282b)
![Azure_Ml_dataset_dealing_page-0002](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/2fb3392d-6464-4648-b20b-1bd2e6c788cb)


![Azure_Ml_dataset_dealing_page-0003](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/08f77d7b-5042-4091-a7b8-e08026b92fb4)
![Azure_Ml_dataset_dealing_page-0005](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/f44fd7e6-fd12-48d4-949c-4429a351dc18)
![Azure_Ml_dataset_dealing_page-0006](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/6869518a-4d56-430f-9f02-5eec2783ac76)
![Azure_Ml_dataset_dealing_page-0007](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/bd1fe33c-5fd2-412c-8128-57e9c7555833)

![Azure_Ml_dataset_dealing_page-0008](https://github.com/rbhardwaj2186/Azure_ML/assets/143745073/c40bfc89-4c76-4202-bb4f-6481da01ecc9)








