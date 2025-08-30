# 🏥 HealthStack System

**HealthStack** is a web-based platform designed to connect multiple hospitals, enabling **efficient tracking, monitoring, and sharing of patient health records** across institutions.  
Patients can browse hospitals/doctors, book appointments, pay for lab tests and medicines, access prescriptions/reports, and even **chat with their appointed doctors**.

> 📌 *Software Engineering Project — B.Sc. in Computer Science and Engineering (CSE)*

---

## 🚀 Features

### 👩‍⚕️ Patient
- Search hospitals → departments → doctors  
- View doctor profiles & book appointments  
- Online payments with email confirmation  
- Access & download prescriptions (PDF)  
- Book and pay for lab tests (cart system + email confirmation)  
- View/download lab reports (PDF)  
- Chat with appointed doctors  
- Review doctors  
- Purchase medicines online (cart system + payment)  

### 👨‍⚕️ Doctor
- Manage doctor profile settings  
- Register with hospitals & upload certificates  
- Accept/reject appointments (patient notified by email)  
- Search patient profiles → create/view prescriptions, view reports  
- Chat with appointed patients  

### 🏥 Hospital Admin
- Dashboard for hospital management  
- Review and approve/reject doctor registrations  
- CRUD operations for hospitals & departments  
- Manage lab workers and pharmacists  

### 🔬 Lab Worker
- Dashboard for lab management  
- Create patient reports  
- Define & manage hospital tests  

### 💊 Pharmacist
- Dashboard for pharmacy management  
- CRUD operations for medicines  
- Search medicines  

---

## 🛠️ Tech Stack

- **Frameworks/Libraries:** Django (Python), Django REST Framework, Bootstrap, JavaScript, AJAX  
- **Database:** SQLite  
- **Backend Services:** Django Channels (real-time chat), ngrok (HTTP tunneling)  
- **PDF Generation:** xhtml2pdf, Django PDF  
- **Environment Management:** django-environ  

---

## 🔌 APIs & Packages

- [Django REST Framework](https://www.django-rest-framework.org/) — Web API toolkit  
- [django-widget-tweaks](https://pypi.org/project/django-widget-tweaks/) — Template form customization  
- [Pillow](https://pillow.readthedocs.io/) — Image processing  
- [Mailtrap API](https://mailtrap.io/) — SMTP email testing  
- [django-environ](https://django-environ.readthedocs.io/) — Manage secrets via `.env`  
- [SSLCommerz API](https://github.com/sslcommerz/SSLCommerz-Python) — Payment gateway (Bangladesh)  
- [Django Debug Toolbar](https://django-debug-toolbar.readthedocs.io/) — Debugging tool  
- [xhtml2pdf](https://xhtml2pdf.readthedocs.io/) — PDF generation  

---

## 📸 Screenshots

### 🏠 Home Page
<img src="https://user-images.githubusercontent.com/64092765/191188204-39dc320f-ec0f-4634-a8db-4735fd89cec9.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191188212-a48d1616-42ec-4413-bb7f-cf0d6347b165.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191188230-2a57e567-a879-487f-a907-8e6add15c8ca.png" width="45%">  

### 👩‍⚕️ Patient
<img src="https://user-images.githubusercontent.com/64092765/191187372-0ea1bc75-aeee-4d2a-8624-27877d213753.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191187384-46f21266-3550-42a9-b3c9-17b19e870608.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191187390-b5dd8bbb-b7e6-4ba6-9423-71e93332e020.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191187405-73b06afa-10ac-46b2-9138-8eb077401d5b.png" width="45%">  

### 👨‍⚕️ Doctor
<img src="https://user-images.githubusercontent.com/64092765/191187476-aae75261-0298-4d13-bc19-d2db8918c1f6.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191187496-f1e0e7e4-ecd4-4c5d-8fdf-abc77a7d2031.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191187508-d03649a8-00ba-4c4c-a4a5-8a17a6fa196f.png" width="45%">  

### 🏥 Hospital Admin
<img src="https://user-images.githubusercontent.com/64092765/191187604-4985a19c-c292-47a9-a21b-befd03500dae.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191187692-05edf07b-a94f-4723-9e95-6b5c04cf03d8.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191187722-820d572b-2a20-4fd1-bc5b-70af699c43b7.png" width="45%">  

### 💊 Pharmacist
<img src="https://user-images.githubusercontent.com/64092765/191187822-6468adf2-c3ca-470a-87e7-1360e5415435.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191187869-24175b0d-38b2-41ff-9eb7-c793b8af0aa1.png" width="45%">  

### 🔬 Lab Worker
<img src="https://user-images.githubusercontent.com/64092765/191188113-f9bb37ae-30a2-46b3-a871-e3ca5aa3df47.png" width="45%">  
<img src="https://user-images.githubusercontent.com/64092765/191188138-2dd284c8-a815-4060-87f3-61ffd7c2300d.png" width="45%">  

---

## ⚙️ Installation & Setup

1. Clone this repository:
   ```bash
   git clone https://github.com/yourusername/healthstack-system.git
   cd healthstack-system
