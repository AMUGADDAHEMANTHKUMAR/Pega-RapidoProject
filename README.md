# 🛵 Rapido Insurance Application – Pega Project

An end-to-end **Insurance System** built using the **Pega Platform**, designed to manage the complete lifecycle of insurance—from policy creation to claims and renewals—with personalized recommendations and real-time notifications.

---

## 📌 Project Overview

The **Rapido Insurance Application** offers a streamlined and intelligent solution for managing vehicle insurance. It leverages Pega's powerful rule engine and case lifecycle to automate tasks, personalize policy offerings, and enhance customer communication.

---

## 🧱 Built Using Pega Rules & Capabilities

### 🧭 Flow Rules
- Designed custom flows to handle:
  - **Policy Creation**
  - **Claims Processing**
  - **Policy Renewal**
- These flows manage the step-by-step orchestration of user actions and approvals.

### 🧠 Decision Rules & Strategies
- Implemented **Decision Tables** and **Decision Strategies** to:
  - Recommend insurance plans based on vehicle type, usage, and customer history
  - Support real-time decisioning for personalized experiences

### 🔗 Integration Rules (Connect SOAP/REST)
- Used **Connect REST** to:
  - Update policy data in external systems
  - Trigger notifications (e.g., email/SMS) upon case creation, approval, or renewal

### ⚙️ Declare Expressions
- Configured **Declare Expressions** to:
  - Automatically calculate premium amounts based on user inputs
  - Determine policy renewal dates without manual intervention

---

## 💡 Key Features

✅ Policy generation and renewal through intuitive case types  
✅ Premium calculation using real-time declared expressions  
✅ Automated claim lifecycle with conditional processing  
✅ Personalized plan recommendations using decision rules  
✅ Seamless integrations for communication and backend updates  
✅ Responsive and dynamic UI designed in App Studio  

---

## 📸 Application Screenshots

A quick preview of how the **Rapido Insurance Application** looks and works:

### 🏠 Home Screen

🖼️ Below are some screenshots of the Lodo Hostel application interface.
You can download the full project and explore all features in a fully functional Pega environment.

Application In Screenshots

<img src="https://github.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/blob/main/Screenshot%20(1931).png" width="800" height="800"> 

<img src="https://github.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/blob/main/Screenshot%20(1932).png" width="800" height="800"> 

<img src="https://github.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/blob/main/Screenshot%20(1933).png" width="800" height="800"> 

<img src="https://github.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/blob/main/Screenshot%20(1934).png" width="800" height="800"> 

<img src="https://github.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/blob/main/Screenshot%20(1935).png" width="800" height="800"> 

<img src="https://github.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/blob/main/Screenshot%20(1936).png" width="800" height="800"> 



### 🧑‍💼 Operator ID Management  
Displays a list of all operator accounts configured in the application, with their work groups and access groups.  
![Operator ID](https://raw.githubusercontent.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/main/Screenshot%20(1939).png)

### 🔗 SOAP Connector Activity  
Activity named `CallConnectSoapAct` which connects to an external SOAP service, sets properties, and parses XML responses.  
![SOAP Connector Activity](https://raw.githubusercontent.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/main/Screenshot%20(1940).png)

### 🕵️ Declare OnChange Rule  
This rule (`WatchAgencyCode`) monitors changes to the `AgencyCode` property and calls an activity dynamically when the condition is met.  
![Declare OnChange Rule](https://raw.githubusercontent.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/main/Screenshot%20(1941).png)

### 📄 PEGA Log Viewer  
Filtered server logs for the operator `rapido@impl.com`, useful for identifying runtime errors and debugging.  
![PEGA Log Viewer](https://raw.githubusercontent.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/main/Screenshot%20(1942).png)

## 🔧 How to Deploy

> Requires Pega Personal Edition or a cloud environment

📥 **Import the Application:**  
[🔗 Download Project File](https://github.com/AMUGADDAHEMANTHKUMAR/Pega-RapidoProject/blob/main/PegaRapidoProjectFile.zip)  

1.Then, import the file via **Designer Studio → Application → Distribution → Import** 
2. Check and validate all **case types**, **data types**, and **rulesets**  
3. Test each flow from **App Studio**  
4. Verify premium and date calculations via **Declare Expressions**  
5. Trigger REST APIs and check the response using **Connect REST rules**

---
## 🧑‍💻 Author

**Amugadda Hemanth Kumar**
*Pega Developer | Enthusiastic fresher passionate about building smart digital solutions.*

## 📬 Contact

Feel free to reach out via [LinkedIn](https://www.linkedin.com/in/amugaddahemanthkumar/) or email if you'd like to collaborate or have questions.

---

> 🚀 Built on Pega to revolutionize the insurance experience with smart automation and user-focused design.
