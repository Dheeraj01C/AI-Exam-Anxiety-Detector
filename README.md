After mapping the original mental-health labels into anxiety levels (Low, Moderate, High), the dataset was validated to ensure the correctness of the mapping.

Two validation checks were performed:

1. Checking for missing values in the 'anxiety_level' column using:
df['anxiety_level'].isnull().sum()

2. Checking the distribution of anxiety levels using:
df['anxiety_level'].value_counts()

The results confirmed that no missing values were present and all labels were successfully mapped. The distribution of anxiety levels across the dataset was also verified, ensuring that the dataset is ready for further preprocessing and model training.
