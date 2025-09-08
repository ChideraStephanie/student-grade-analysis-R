# Student Performance Analysis with R

This project explores factors influencing student academic performance using the **Student-Mat dataset**.  
The analysis applies **statistical methods and data visualization in R** to uncover insights into study time, absences, internet access, gender, and prior grades.  

---

## Dataset
- Source: [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/student+performance)  
- Observations: **395 students**  
- Key variables:  
  - `studytime`: Weekly study hours  
  - `absences`: Number of school absences  
  - `internet`: Internet access (yes/no)  
  - `sex`: Gender (M/F)  
  - `G1`, `G2`: First and second period grades  
  - `G3`: Final grade  

---

## Methods
The analysis was conducted using **R** and the following approaches:
- Correlation analysis (study time vs grades)  
- Hypothesis testing (internet access, gender differences)  
- Visualization with **ggplot2**

---

## Key Results

### Study Time vs Final Grade
[Study Time vs Final Grade](studytime_vs_final.png)
🔹 *Weak positive correlation (~0.10). Study time has little effect on final performance compared to other factors.*  

---

### Absences vs Final Grade 
![Absences vs Final Grade](absences_vs_final.png)
🔹 *Negative relationship. Students with more absences tend to score lower.*  

---

### Gender vs Final Grade
![Gender vs Final Grade](gender_vs_final.png)
🔹 *Males scored slightly higher on average (p ≈ 0.04).*  

---

### Internet Access vs Final Grade
![Internet vs Final Grade](internet_vs_final.png)
🔹 *Students with internet access perform better (p ≈ 0.049). Access to resources seems beneficial.*  


---

## Conclusion
- Prior grades are the best predictor of student success.  
- Absences negatively impact outcomes.  
- Internet access supports better performance.  
- Gender differences exist but are small compared to academic factors.  

This project demonstrates how **R programming, statistical tests, and visualization** can be applied to educational data analysis.  

---

## Technologies Used
- **R** (ggplot2, dplyr, rstatix)  
- **R Markdown** for reproducible reporting  

---
##  Author

**Chidera Stephanie Ughamadu**  
Data Analyst


