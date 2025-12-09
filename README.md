# Automation Website for St. Xavier’s Catholic College of Engineering

I developed an automation website for **St. Xavier’s Catholic College of Engineering** that allows students to easily access their academic information.

---

## 🔑 Key Features

### **📱 Phone Number Login**
- Students can log in using their **10-digit mobile number**.
- No password is required, making access simple and fast.

### **🗂️ Local Authentication Storage**
- The phone number is stored **only in the user’s browser** (Local Storage).
- On logout, the stored number is **immediately erased** for privacy.

### **🌐 100% Static Frontend (HTML-based)**
- The entire website frontend is built using **pure HTML**.
- Lightweight and fast-loading.

### **🔒 Secure Data Access**
- Even though the website is static, all student data is securely fetched from the **college database server**.
- The **phone number acts as the key** to access academic details and marks.

### **📡 Direct Data Fetching**
- The browser sends the phone number (key) to the college server.
- The server returns the student’s data, which is displayed instantly in the browser.
- Data transfer is secure and always specific to the authenticated student.

### **🔁 End-to-End Flow**
- The process begins with the user and ends in the user’s browser.
- No data is stored permanently on the website or by the developer.
- Everything is handled securely between the **college server** and the **student’s device**.

---

