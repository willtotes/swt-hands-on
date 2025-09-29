# 🐞 Bug Report Summary


## 🧾 Student Details  
**Name**: Will Tsotetsi  
**Cohort**: July 2025  
**Date**: 19-09-2025


---


## ✅ Expected Behaviors  
List 3 things you expect the Weather Checker app to do correctly.


1. It should handle different letter cases for city names.
2. It should accept a valid city name and display correct weather information.
3. It should provide a clear error message if the input field is empty or the city name spelling is wrong when the button is clicked.


---


## 🐛 Reported Bugs  


### 🐞 BUG-001  
**Title**: App doesn’t handle uppercase city names  
**GitHub Link**: https://github.com/PLP-Database-DEPT/swt-hands-on.git
**Requirement Affected**: Input Validation
**Severity**: Medium  
**Summary**:  
The weather app only recognizes the names of cities typed in lowercase. If the user types "NAIROBI" or "Nairobi"; "City not fount" error is returned by the app. This creates a poor user experience for users because they don't usually pay attention to word cases when typing city names.


---


### 🐞 BUG-002  
**Title**: Weather app does nothing when the "Check Weather" button is clicked when input field is empty  
**GitHub Link**: https://github.com/PLP-Database-DEPT/swt-hands-on.git
**Requirement Affected**: Case Handling / UI Feedback  
**Severity**: low
**Summary**:  
When the user clicks the "Check Weather" button without entering a city name, no feedback is provided by the app. This can leave the user confused to whether the app is working or not. The app should alert the user that the input field cannot be blank.


---


## 💭 Reflection  


Answer briefly (1–2 paragraphs):


- What was your testing approach? - My testing approach was exploratory as I started by testing entering valid, lowercase city names to confirm the core function worked. Afterwards, I began testing various cases and invalid inputs such as using uppercase letters, mixed case, numbers, special characters, and leaving the input field empty.
- What did you find easy or difficult during the task? - I found identifying the main functional bug of case sensitivity was easy as it was a common logic error. What was more difficult was considering all the less obvious cases like spaces in the input. Reading the code helped pinpoint the potential problem,  
- How confident are you now in identifying and reporting bugs? - I feel more confident in my ability to systematically test an application and identify discrepancies between expected and actual behavior. Structuring my findings into a clear and concise bug report using the standard template is still a skill I still need to get used to using.