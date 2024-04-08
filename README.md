# Medicine_recommendation_system

This Python script provides a medicine recommendation system based on patient symptoms and medical history data. It utilizes the Apriori algorithm from the mlxtend library to extract frequent itemsets and association rules from the medical dataset. These association rules are then used to recommend medicines for a given set of patient symptoms.

Features:

  - Data Preprocessing:
    
      * Cleans the data by removing unnecessary columns and handling missing values.
        
      * Encodes symptoms, medicines, and diseases into binary features for association rule mining.
        
  - Association Rule Mining:
    
      * Utilizes the Apriori algorithm to discover frequent itemsets in the dataset.
   
      * Generates association rules with specified metrics such as support, confidence, and lift.

  - User Input:

      * Accepts patient information and symptoms as input from the user.
      
  - Medicine Recommendation:

      * Filters association rules based on the input symptoms provided by the user.
      
      * Recommends medicines associated with the input symptoms along with their confidence levels.
         
  - Dependencies:
      * mlxtend.
      
      * pandas.

Usage:

  1-Ensure that the required Python libraries are installed (`mlxtend`, `pandas`).
  
  2-Prepare a CSV file containing medical data with columns for symptoms, medicines, and diseases.
  
  3-Run the script and input patient information along with symptoms when prompted.
  
  4-The system will provide recommendations for medicines and diseases based on the input symptoms.

Note: 

  * The system recommends medicines and diseases based on association rules derived from the provided medical dataset. Users should consult medical professionals for accurate diagnosis and treatment recommendations.
