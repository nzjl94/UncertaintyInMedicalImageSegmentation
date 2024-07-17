# UncertaintyInMedicalImageSegmentation


The Result.csv contains the results of all AI models used in the paper; the dataset contains the following columns:

-   img_id: Image IDs for each dataset; some IDs are repeated multiple times since they exist in multiple datasets.

-   dice_coefficient: The calculated value for the Gray-level Dice Coefficient (GDC) metric.

-   normalized_mutual_information: The calculated value for the Normalized Mutual Information (NMI) metric.

-   normalized_root_mse: The calculated value for the Normalized Root Mean Square Error (NRMSE) metric.

-   dataset: The datasets that the sample belongs to and the unique values are as follows: ['KNEE', 'SKB', 'LUNG', 'HEART_LUNGS', 'HEART_HEART'].

-   algorithm: The algorithm that produce the result, the unique values are as follows: ['M2' -> 'Monte Carlo Dropout 20%', 'M4' -> 'Monte Carlo Dropout 40%', 'M6' -> 'Monte Carlo Dropout 60%', 'M8' -> 'Monte Carlo Dropout 80%', 'REG' -> 'Regression', 'M0' -> 'Ensemble Multiple Annotations', 'SINGLE_ANNOTATION' -> 'Ensemble Single Annotation']
