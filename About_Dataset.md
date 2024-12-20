
# **About the Dataset**

This synthetic dataset generation is carefully designed to mimic real-world scenarios in Bangladesh, inspired by Data, News, Trends and Information foound on Govt/Non-govt organizations, particularly focusing on smoking behaviors. The features and values reflect practical and realistic trends inspired by research, demographics, and global data like FDA and WHO. Here's how the realism is embedded into the dataset:

---

## **Realism of Dataset Features and Values**

### 1. **Age Distribution**
- **Generated Range**: 18 to 71 years.
- **Realistic Justification**:
  - In Bangladesh, the average age of smokers starts from around 14 years and peaks in adulthood, declining slightly in later years.
  - By focusing on the 18–71 range, the dataset avoids edge cases (like children) while representing the majority of the smoking population realistically.

---

### 2. **Gender Distribution**
- **Categories**: "Male" and "Female."
- **Probabilities**: 60% Male, 40% Female.
- **Realistic Justification**:
  - According to data from Bangladesh and global trends, male smokers significantly outnumber female smokers.
  - Women smokers are less prevalent due to cultural and social factors, aligning the dataset with ground realities.

---

### 3. **Professions**
- **List of Professions**:
  ```text
  "Student", "Agricultural Worker", "Teacher", "Healthcare Professional",
  "Textile Worker", "Shopkeeper/Trader", "Driver", "Construction Worker",
  "Housewife", "Freelancer/IT Professional", "Artisan/Craftsperson",
  "Unemployed/Dependent", "Others"
  ```
- **Realistic Justification**:
  - The professions selected reflect a wide spectrum of Bangladesh’s workforce. For instance:
    - "Agricultural Worker" is highly relevant, as a significant portion of Bangladesh's workforce is involved in agriculture.
    - "Textile Worker" is a key category due to Bangladesh's large garment industry.
    - Inclusion of "Housewife" accounts for non-working women exposed to secondhand smoke at home.
  - Probabilities assigned to each profession are based on occupational prevalence in Bangladesh.

---

### 4. **Geographical Data (Districts)**
- **Districts**: All 64 districts of Bangladesh are included.
- **Even Distribution**:
  - Every district has an equal probability of being selected.
  - This reflects national-level data without biasing towards urban or rural areas, enabling balanced geographic analysis.
- **District IDs**:
  - Numerical IDs assigned to each district allow easier integration with mapping and visualization tools, such as choropleth maps.

---

### 5. **Smoking Status**
- **Categories**: `"Never Smoked"`, `"Former Smoker"`, `"Light Smoker"`, `"Medium Smoker"`, `"Heavy Smoker"`.
- **Probabilities**:
  - "Never Smoked" has the highest probability (50%), reflecting non-smokers as the majority.
  - "Light Smoker," "Medium Smoker," and "Heavy Smoker" are distributed to mirror real-world prevalence, where heavy smoking is less common.
- **Realistic Justification**:
  - These categories align with WHO's classification and reflect smoking habits in Bangladesh, where light to medium smoking is more prevalent than heavy smoking.

---

### 6. **Age at Smoking Initiation**
- **Generated Values**:
  - Randomly assigned between 10 years and the individual’s current age for smokers.
- **Realistic Justification**:
  - Early initiation is a concern in Bangladesh, with many smokers starting in their teens. The dataset captures this trend while omitting cases of smoking starting before age 10, which are statistically negligible.

---

### 7. **Exposure to Secondhand Smoke**
- **Categories**: `"Yes"`, `"No"`.
- **Probabilities**: 65% Yes, 35% No.
- **Realistic Justification**:
  - Bangladesh has a high prevalence of secondhand smoke exposure, especially in households and workplaces. The dataset reflects this trend.

---

### 8. **Awareness of Smoking Risks**
- **Categories**: `"High"`, `"Moderate"`, `"Low"`, `"No Awareness"`.
- **Probabilities**:
  - Higher probabilities for "Moderate" and "Low" awareness categories reflect the average public understanding in Bangladesh, where anti-smoking campaigns are increasing but not yet fully effective.

---

### 9. **Pocket Money**
- **Categories**: `"High"`, `"Medium"`, `"Low"`.
- **Realistic Justification**:
  - Stratified based on professions, reflecting income disparity in Bangladesh.
  - For example:
    - "Healthcare Professional" and "Freelancer/IT Professional" are likely to have high pocket money.
    - "Agricultural Worker" and "Teacher" fall into the medium range.
    - "Students" and "Artisan/Craftsperson" typically have low pocket money.

---

### 10. **Health Symptoms**
- **Included Symptoms**:
  ```text
  "Cough", "Shortness of Breath", "Chest Pain", "Fatigue", "Persistent Cough", "Wheezing"
  ```
- **Linked Probabilities**:
  - Symptoms are correlated with smoking intensity, based on established medical research (e.g., WHO data on smoking-related diseases).
- **Realistic Justification**:
  - Heavy smokers have a higher likelihood of experiencing these symptoms, while non-smokers rarely report them. This alignment reflects real health outcomes.

---

### **Synthetic Yet Realistic**
- Although this dataset is synthetic, it is designed to mimic real-world scenarios:
  - Probabilities are inspired by global data (FDA, WHO) and tailored to Bangladesh’s unique cultural, occupational, and demographic landscape.
  - This makes the dataset highly representative of smoking trends in the country.

---

## **Please Note**
This dataset provides a realistic and practical foundation for analyzing smoking behaviors in Bangladesh. The alignment of features and values with ground realities ensures its applicability in research, policymaking, and public health initiatives.
