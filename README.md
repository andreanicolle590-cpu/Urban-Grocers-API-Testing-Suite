# 🧪 Urban Grocers API Testing Suite

## 🎯 Project Overview
This project marks a key milestone in my career shift from Energy Engineer to QA Engineer.  
Urban Grocers is a grocery delivery platform where I had the opportunity to **design and execute manual tests** on two core features: **product kit management** and **delivery service calculations**.

Throughout this process, I applied structured testing techniques, documented real defects, and strengthened my skills using **Postman**, **Excel**, and **JIRA**.

---

## 🔍 Analysis Performed

### 🧩 Requirement 1: Product Kit Management
- Validated endpoints for adding products to kits.  
- Tested parameters such as `kitId`, `productId`, and `quantity`.  
- Checked limits in the `productsList` array structure.  
- Verified the maximum number of unique products per kit.  

### 🚚 Requirement 2: Delivery Services
- Tested shipping price calculations based on weight, quantity, and delivery time.  
- Validated parameters like `deliveryTime`, `productsWeight`, and `productsCount`.  
- Verified business logic across different delivery ranges.  

---

## 🧠 My Contribution

- ✍️ Designed **32+ test cases** covering positive, negative, equivalence class, and boundary value scenarios.  
- 🐞 Identified and documented **critical bugs** related to parameter validation and delivery fee logic.  
- 📊 Used **Excel** to organize test cases including ID, description, steps, expected and actual results.  
- 🗂️ Logged defects in **JIRA** with evidence and traceability.  
- 🏅 Earned a **QA certification badge**, marking the completion of this training stage.  

---

## 🧰 Tools & Techniques

**Tools**
- 🔧 Postman – API testing execution  
- 📋 Excel – Test case documentation  
- 🐛 JIRA – Defect tracking and reporting  

**Techniques**
- Equivalence partitioning  
- Boundary value analysis  

---

## 📦 Backend Functional Requirements – Urban Grocers

During system analysis, I reviewed technical documentation describing how the **kits** and **delivery services** endpoints operate. Based on this, I designed manual test cases to validate business logic, parameter limits, and expected responses for each service.

### 🔁 Endpoint: `/api/v1/kits/:id/products`

**Main Functionality:**  
Allows adding existing products to a specific kit in the Urban Grocers platform.

**Details:**
- **Method:** `POST`  
- **URL:** `{base_url}/api/v1/kits/:id/products`  
- **Parameter:** `:id` → the kit ID to which products are added  

📸 *API Documentation Example:* “Kit Management API”

<img width="1028" height="897" alt="image" src="https://github.com/user-attachments/assets/407b0d93-f244-4e64-a38c-82c10ba42e9c" />


## 📊 Delivery Service Constraints

Each delivery service includes specific rules for allowed weight, max item count, data format, and valid time ranges.  
This information was essential for creating tests that used **boundary values**, **equivalence classes**, and **negative scenarios**.

📸 *Example:* Delivery Rules and Calculation Logic Table  

<img width="894" height="780" alt="image" src="https://github.com/user-attachments/assets/60316c97-2056-4e03-a0aa-9d8b40c06014" />


## 🧪 Derived Test Cases

From these requirements, I designed **32+ manual test cases** that covered:

- ✅ Positive and ❌ negative scenarios  
- Validation of required and optional parameters  
- Out-of-range value testing  
- HTTP response and JSON structure verification  
- Test result tracking (`Passed` / `Failed`)  


👀 *Preview:* Test Case Excel Sheet  

<img width="1260" height="631" alt="image" src="https://github.com/user-attachments/assets/823b13f6-5af9-484c-a209-c6dc47d89889" />

## 🧭 My QA Journey

This project showed me that quality is not only inspected in a factory—it’s also **built into the code**.  
Every test case I designed and every bug I documented contributed to my growth as a technical professional.

---

