# 📊 Titanic Dataset

The main goal is to predict whether a passenger survived the Titanic disaster based on personal and travel-related information.

---

## 📦 General Information
- **Number of instances (rows):** 891 passengers  
- **Number of features (columns):** 12 (including the target variable `Survived`)

---

## 🧾 Dataset Variables

### 1. Survived (target)
- **Description:** Indicates whether the passenger survived.  
  - 0 = Did not survive  
  - 1 = Survived  
- **Data Type:** Categorical
- **Keep/Drop:** **Keep**

---

### 2. Pclass
- **Description:** Ticket class (1st, 2nd, or 3rd class).  
- **Data Type:** Categorical
- **Keep/Drop:** **Keep**

---

### 3. Name
- **Description:** Full name of the passenger. 
- **Data Type:** Categorical
- **Keep/Drop:** **Drop** – No predictive information. 
---

### 4. Sex
- **Description:** Passenger’s gender (male/female).  
- **Data Type:** Categorical
- **Keep/Drop:** **Keep**

---

### 5. Age
- **Description:** Age in years.  
- **Data Type:** Numerical
- **Keep/Drop:** **Keep**
- **Note:** Contains missing values

---

### 6. SibSp
- **Description:** Number of siblings/spouses aboard.  
- **Data Type:** Numerical
- **Keep/Drop:** **Keep**

---

### 7. Parch
- **Description:** Number of parents/children aboard.  
- **Data Type:** Numerical
- **Keep/Drop:** **Keep**

---

### 8. Ticket
- **Description:** Ticket number. 
- **Data Type:** Categorical 
- **Keep/Drop:** **Drop** – No predictive information. 

---

### 9. Fare
- **Description:** Fare paid for the ticket.  
- **Data Type:** Numerical
- **Keep/Drop:** **Keep**

---

### 10. Cabin
- **Description:** Cabin code.  
- **Keep/Drop:** **Drop** – Not enought data to keep feature.

---

### 11. Embarked
- **Description:** Port of embarkation:  
  - C = Cherbourg  
  - Q = Queenstown  
  - S = Southampton  
- **Keep/Drop:** **Keep**

---

## ✅ Final Summary

| Feature    | Keep/Drop         | Reason |
|------------|-------------------|--------|
| Survived   | Keep              | Target variable |
| Pclass     | Keep              | Socioeconomic indicator |
| Name       | Drop              | Not useful |
| Sex        | Keep              | Critical survival factor |
| Age        | Keep              | Relevant, needs imputation |
| SibSp      | Keep              | Family relationships |
| Parch      | Keep              | Family relationships |
| Ticket     | Drop              | Mostly random number |
| Fare       | Keep              | Socioeconomic indicator |
| Cabin      | Drop              | Many nulls |
| Embarked   | Keep              | Geographic/social information |

---
