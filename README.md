# Embro-Ease


Here's a refined version of the documentation with a focus on the design perspective:

---

## **System Documentation for Company Management Panel**

---

### **◉ Role Definitions**

1. **Super Admin**
   - Manages all companies (access-based).
   - Controls Prime bases and assigns Admins accordingly.

2. **Admin**
   - Manages specific companies (Prime base dependent).
   - Oversees operations, entries, and reports.

3. **Assistant**
   - Assists with specific company operations.
   - Limited access, focused on product and design data handling.

4. **Employee**
   - Minimal access for operational tasks.
   - No dashboard or management functionality.

---

### **◉ Role Permissions**

| **Feature**        | **Super Admin** | **Admin**       | **Assistant** | **Employee** |
| ------------------ | --------------- | --------------- | ------------- | ------------ |
| Login              | ✔               | ✔               | ✔             | ✔            |
| Dashboard Access   | All Companies   | Prime Companies | One Company   | No Access    |
| Manage Companies   | ✔               | ✔               | ✖             | ✖            |
| Add Machines       | ✔               | ✔               | ✖             | ✖            |
| View Reports       | ✔               | ✔               | ✔             | ✖            |
| Manage Products    | ✔               | ✔               | ✔             | ✖            |
| Manage Design Data | ✔               | ✔               | ✔             | ✖            |
| Manage Party Info  | ✔               | ✔               | ✖             | ✖            |
| Bill Management    | ✔               | ✔               | ✖             | ✖            |
| Receive Entries    | ✔               | ✔               | ✖             | ✖            |
| Delivery Entries   | ✔               | ✔               | ✖             | ✖            |

---

### **◉ Common Pages**

1. **Login**
2. **Sign Up**

---

### **◉ Panel Details**

#### **Super Admin Panel**
1. **Login Page**
2. **Home / Dashboard**
   - Displays all companies based on access level.
3. **Prime Base Management**
   - Manage companies assigned to each Prime base:
     - **1 Prime** → **1 Company**
     - **2 Prime** → **3 Companies**
     - **3 Prime** → **5-7 Companies**

---

#### **Admin Panel**
1. **Login Page**
2. **Home / Dashboard**
   - Displays specific companies managed by the Admin.
3. **Dashboard (One Company View)**
   - **All Over Report** – Monthly reports:
     - Total products
     - Total received items
     - Total deliveries
     - Total revenue

4. **Pages**
   - **All Employees Machine**
     - Admin can add, view, and assign machines.
     - Filed is machine number , employee name.
     - Displays machine information in a box format.
   - **Design Page**
     - Displays design data (image-type data).
   - **Party Entry**
     - Fields: Party Code, Name, GST Number, Address, Phone Number.
   - **Product Entry**
     - Fields: Product Code, Name, Status.
   - **Bill Selection**
     - Types of bills:
       1. **GST Bill**
       2. **Non-GST Bill**
       3. **Delivery Bill**
   - **Receive Entry**
     - Two types:
       1. **Material Bill** – Fields: Party Name, Received Date, Product Name, Quantity, Rate, Amount.
       2. **Product Bill** – Fields: Party Name,  Received Number , Received Date, Product Name, Design Number, Quantity, Rate, Amount.
   - **Delivery Entry**
     - Fields: Party Name,  Received Number , Received Date , Delivery Number , Delivery Date, Product Name, Design Number, Quantity, Rate, Amount.

---

#### **Assistant Panel**
1. **Sign Up Page**
2. **Login Page**
3. **Home**
   - Displays one company dashboard.
4. **Dashboard**
   - **All Over Report** – Monthly reports:
     - Total products
     - Total received items
     - Total deliveries
     - Total revenue

5. **Features**
   - **All Employees Machine**
     - View-only access.
   - **Design Page**
     - View-only access.
   - **Product Entry**
     - View-only access.

---

#### **Employee Panel**
- Minimal access, primarily for operational tasks.
- No dashboard or management functionality.

---

Let me know if you'd like further refinement or any specific adjustments!
