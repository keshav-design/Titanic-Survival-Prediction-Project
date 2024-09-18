# Titanic-Survival-Prediction-Project
This project aims to predict the survival of passengers aboard the Titanic using machine learning techniques. By analyzing historical data from the Titanic dataset, we explore various factors such as age, gender, class, and fare to determine their influence on survival rates.


⁡⁣⁢⁢​‌‍‌*** 𝗠𝗟 𝗠𝗼𝗱𝗲𝗹𝗶𝗻𝗴 𝗙𝗹𝗼𝘄***​⁡
------------------------


​‌‌‍𝟭. 𝗗𝗮𝘁𝗮 𝗚𝗮𝘁𝗵𝗲𝗿𝗶𝗻𝗴:
​

​‌‌‍𝟮. 𝗗𝗮𝘁𝗮 𝗣𝗿𝗲𝗽𝗮𝗿𝗮𝘁𝗶𝗼𝗻:​ 

     ​‌‍‌𝗔. 𝗨𝗻𝗱𝗲𝗿𝘀𝘁𝗮𝗻𝗱𝗶𝗻𝗴 𝘆𝗼𝘂𝗿 𝗗𝗮𝘁𝗮​

		- How big is the data ?
		- How does the data look like ?
		- What are the data types of columns ?
		- Are there any missing values ?
		- How does the data look mathematically ?
		- Are there duplicate values in data (rows)?
		- How is the correlation between cols ?

  
	​‌‍‌𝗕. 𝗘𝗗𝗔:​
		- Univariate Analysis
		- Bivariate and Multivariate Analysis

  
	​‌‍‌𝗖. 𝗙𝗲𝗮𝘁𝘂𝗿𝗲 𝗘𝗻𝗴𝗶𝗻𝗲𝗲𝗿𝗶𝗻𝗴:​
		⁡⁢⁣⁣𝟭. 𝗙𝗲𝗮𝘁𝘂𝗿𝗲 𝗧𝗿𝗮𝗻𝘀𝗳𝗼𝗿𝗺𝗮𝘁𝗶𝗼𝗻⁡
			‍𝘢. 𝘔𝘪𝘴𝘴𝘪𝘯𝘨 𝘝𝘢𝘭𝘶𝘦 𝘐𝘮𝘱𝘶𝘵𝘢𝘵𝘪𝘰𝘯:
				a.1 Drop missing rows (CCA complete case analysis)
				b.2 Impute values with:
					a. Univariate(SimpleImputer class)
						- Mean
						- Median
						- Mode(categorical)
						- Random value
						- End of this
						- Write missing(categorical)
					b. Multivariate
						- MICE (Iterative imputer)
						- KNN imputer
					
			𝘣. 𝘏𝘢𝘯𝘥𝘭𝘪𝘯𝘨 𝘊𝘢𝘵𝘦𝘨𝘰𝘳𝘪𝘤𝘢𝘭 𝘍𝘦𝘢𝘵𝘶𝘳𝘦𝘴(𝘕𝘶𝘮𝘦𝘳𝘪𝘤𝘢𝘭 𝘢𝘯𝘥 𝘊𝘢𝘵𝘦𝘨𝘰𝘳𝘪𝘤𝘢𝘭)
				- Ordinal Encoding (For Ordinal Input features)
				- One hot Encoding (Nominal Data)
				- Label Encoding (Used for categorical output feature)
    
			𝘤. 𝘖𝘶𝘵𝘭𝘪𝘦𝘳 𝘋𝘦𝘵𝘦𝘤𝘵𝘪𝘰𝘯
				- Z-score
				- IQR
				- Percentile Approach (Trimming, Winsorization using capping)
				- Median Absolute Deviation (MAD)
    
			𝘥. 𝘍𝘦𝘢𝘵𝘶𝘳𝘦 𝘚𝘤𝘢𝘭𝘪𝘯𝘨
				- Standerdization(When to use, K-means, KNN, ANN, Gradient Discent)
				- Normalization(MinMaxScaler, StandardScaler, RobustScaler)


    
	
 ‍⁡⁢𝟮. 𝗙𝗲𝗮𝘁𝘂𝗿𝗲 𝗖𝗼𝗻𝘀𝘁𝗿𝘂𝗰𝘁𝗶𝗼𝗻:​⁡
 
			- Feature splitting
   
		⁡⁢
  𝟯. 𝗗𝗶𝗺𝗲𝗻𝘀𝗶𝗼𝗻𝗮𝗹𝗶𝘁𝘆 𝗥𝗲𝗱𝘂𝗰𝘁𝗶𝗼𝗻 (𝗯𝗲𝗰𝗮𝘂𝘀𝗲 𝗼𝗳 𝗰𝘂𝗿𝘀𝗲 𝗼𝗳 𝗱𝗶𝗺𝗲𝗻𝘀𝗶𝗼𝗻𝗮𝗹𝗶𝘁𝘆):⁡
  
			- Feature Selection (Forward, Backward)
			- Feature Extraction (PCA, LDA, T-sne)

​‌‌‍𝟯. 𝗠𝗼𝗱𝗲𝗹𝗶𝗻𝗴
​

​‌‌‍𝟰. 𝗠𝗼𝗱𝗲𝗹 𝗘𝘃𝗮𝗹𝘂𝗮𝘁𝗶𝗼𝗻 𝗮𝗻𝗱 𝗧𝗲𝘀𝘁𝗶𝗻𝗴(𝗔/𝗕 𝘁𝗲𝘀𝘁𝗶𝗻𝗴)
​

​‌‌‍𝟱. 𝗗𝗲𝗽𝗹𝗼𝘆𝗺𝗲𝗻𝘁​
