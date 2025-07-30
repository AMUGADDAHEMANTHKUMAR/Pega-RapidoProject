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

## 📸 Screenshots (Optional)

## 📸 Screenshots

A quick preview of how the **Rapido Insurance Application** looks and works:

### 🏠 Home Screen
![Home Screen](./Screenshot (1927).png)

### 📝 Policy Form
Users can enter vehicle and customer details to initiate policy creation.
![Policy Form](Screenshot (1928).png)

### 📊 Decision Table for Policy Suggestion
Premium logic and policy recommendations based on vehicle type, IDV, and duration.
![Decision Table](Screenshot (1930).png)

### 💰 Premium Calculation
Auto-calculated premium values using Declare Expressions.
![Premium Calculation](Screenshot (1931).png)

### ✅ Confirmation Screen
Once approved, the final policy is shown with all selected options.
![Confirmation Screen](Screenshot (1932).png)


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

## 📬 Contact

**Developer:** Amugadda Hemanth Kumar  
📧 Email: [your email here]  
🔗 LinkedIn: [your LinkedIn here]

---

> 🚀 Built on Pega to revolutionize the insurance experience with smart automation and user-focused design.
