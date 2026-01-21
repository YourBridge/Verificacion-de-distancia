<p align="center">
  <img src="logo.png" alt="Kleto Snack Corporate Logo" width="180">
</p>

# 📍 Kleto Geo Delivery  
### Enterprise Geospatial Verification Platform for Proximity-Based Delivery Validation

🔗 **Production Environment:**  
https://yourbridge.github.io/Verificacion-de-distancia/

---

## 🏢 Corporate Overview  
**Kleto Snack**  
Digital infrastructure for real-time, location-based promotion validation and operational analytics.

Kleto Geo Delivery is designed as a lightweight, secure, and scalable geospatial verification system that enables businesses to enforce geographic eligibility rules for promotional campaigns and delivery operations.

---

## 🧭 Executive Summary  
Kleto Geo Delivery is a browser-based enterprise system that automatically validates whether a customer is located within a predefined geographic perimeter of **500 meters** to qualify for **free delivery**.

The platform combines:
- Real-time browser geolocation
- Mathematical distance computation
- Cloud-based analytical logging
- Automated customer communication

This solution enables the business to:

▶ Eliminate human error in promotion validation  
▶ Generate territorial customer intelligence  
▶ Improve customer experience and conversion flow  
▶ Maintain auditability and legal consent traceability  
▶ Support operational and logistics decision-making  

---

## ⚙️ System Architecture  

### Frontend Layer  
- 🌐 HTML5  
- 🎨 CSS3  
- ⚡ JavaScript (Vanilla)  
- 📡 Web Geolocation API  

### Processing Layer  
- 📐 Haversine Formula for precise spherical distance calculation  

### Analytics Backend  
- 📊 Google Sheets (Cloud Data Store)  
- 🧠 Google Apps Script (Private Web App API Endpoint)  

### Integrations  
- 💬 WhatsApp Click-to-Chat API (Customer Engagement Channel)  
- ☁️ GitHub Pages (Secure HTTPS Hosting Layer)  

---

## 🔄 Operational Flow  

1️⃣ User accesses the web platform  
2️⃣ Browser requests explicit geolocation consent  
3️⃣ System retrieves GPS coordinates  
4️⃣ Distance is calculated against the business reference point  
5️⃣ The 500-meter eligibility perimeter is evaluated  
6️⃣ Visual compliance status is rendered in real time:  
   - 🟠 **Orange:** User inside promotional range  
   - 🔴 **Red:** User outside promotional range  
7️⃣ Automated WhatsApp Business message is generated  
8️⃣ Verification record is logged in Google Sheets for analytics and audit  

---

## 🎯 Corporate Objective  
To automate geographic promotion validation in order to ensure operational control, improve logistics efficiency, and generate strategic geospatial data for executive-level commercial decision-making.

---

## 👥 Technical & Operational Stakeholders  

▶ Systems Engineers  
▶ Web Developers  
▶ Data Analysts  
▶ Operations Administrators  
▶ Digital Marketing Teams  
▶ Compliance & Risk Officers  

---

## 📊 Analytical Data Registry  
Each validation event generates a structured record containing:

- 📅 Timestamp (Date & Time)  
- 📍 User Latitude  
- 📍 User Longitude  
- 📏 Distance from Business Location (Meters)  
- 🎯 Eligibility Status (Inside / Outside Perimeter)  
- 🧾 Data Consent Status (Accepted)  
- 🌐 Device / Browser Metadata (If Available)  

---

## 🔐 Legal Compliance & Privacy Framework  

✔ Explicit geolocation consent is required before data access  
✔ No personally identifiable information (PII) is collected  
✔ No phone numbers, names, or direct identifiers are stored  
✔ Data is used exclusively for operational and analytical purposes  
✔ Designed to comply with responsible data handling principles and regional digital privacy standards (Dominican Republic and international best practices)  

---

## 🚀 Project Status  

- [x] Real-time geolocation system operational  
- [x] Distance computation validated  
- [x] Google Sheets analytics integration  
- [x] Automated WhatsApp message generation  
- [x] Secure HTTPS hosting (GitHub Pages)  
- [ ] Advanced analytics dashboard (Planned Phase)  

---

## 🛠️ Technical Deployment  

### Requirements  
- Google Account (Sheets & Apps Script Access)  
- GitHub Repository  
- Modern Browser with GPS Support  

### Deployment Steps  

1️⃣ Clone or download this repository  
2️⃣ Configure Google Apps Script as a Web App endpoint  
3️⃣ Link the Google Sheet as the analytics datastore  
4️⃣ Insert the Web App URL into `index.html`  
5️⃣ Publish the site using GitHub Pages  
6️⃣ Access from any device and validate system operation  

---

## 📌 Technical Considerations  

- iOS Safari requires HTTPS to enable geolocation services  
- Accuracy depends on GPS signal, device hardware, and user permissions  
- Chrome, Edge, or Safari (latest versions) are recommended for audit testing  

---

## 🧪 Audit & Validation Readiness  

This system supports technical and compliance audits through:

▶ Open-source codebase (GitHub Repository)  
▶ Analytical event logs (Google Sheets)  
▶ User consent flow verification  
▶ Mathematical validation model (Haversine Formula)  
▶ Messaging system integration (WhatsApp API)  

---

## ✨ Corporate Attribution  

Developed for **Kleto Snack** as a geospatial compliance and promotional automation platform supporting customer analytics, territorial intelligence, and logistics optimization.

---

## 🌎 Documentación en Español  

### Resumen Ejecutivo  
Kleto Geo Delivery es un sistema corporativo de verificación geoespacial que permite validar automáticamente si un cliente se encuentra dentro de un radio definido de **500 metros** para aplicar promociones de **delivery gratuito**.

El sistema integra geolocalización web, cálculo matemático de distancia y almacenamiento en la nube para garantizar trazabilidad, control operativo y generación de métricas estratégicas.

---

📎 **Official Repository:**  
https://github.com/YourBridge/Verificacion-de-distancia
