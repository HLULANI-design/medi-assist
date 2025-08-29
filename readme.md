# 🏥 MediAssist - Healthcare Management System

MediAssist is a comprehensive healthcare management dashboard designed to streamline patient care, track performance metrics, and improve healthcare delivery.  

Built with an **AWS Summit-inspired design**, it offers a professional and intuitive interface for managing patient intake, feedback systems, and follow-up care.

![MediAssist Dashboard](https://via.placeholder.com/800x400/232f3e/ffffff?text=MediAssist+Dashboard)

---

## ✨ Features

### 🏥 Patient Intake System
- Multi-step form for collecting patient information  
- Symptom tracking with severity assessment  
- Medical history recording  
- Responsive design for all devices  

### ⭐ Feedback & Rating System
- 5-star rating system for consultations  
- Comment system for detailed feedback  
- Automatic quality review triggering for low ratings  
- Historical feedback tracking  

### 📊 Follow-up Care Management
- Interactive care plan checklist  
- Symptom severity tracking over time  
- Alert system for worsening symptoms  
- Progress tracking with visual indicators  

### 📈 Dashboard & Analytics
- Real-time metrics display  
- Patient satisfaction tracking  
- Staff performance monitoring  
- Recent activity timeline  

---

## 🛠 Technology Stack
- **Frontend:** HTML5, CSS3, JavaScript (ES6+)  
- **UI Framework:** Bootstrap 5.3.0  
- **Icons:** Bootstrap Icons  
- **Storage:** Browser localStorage API  
- **Design:** AWS Summit-inspired theme  

---

## 🚀 Installation
No installation required! MediAssist runs directly in any modern web browser:

1. Download the `index.html` file  
2. Open it in your preferred browser (Chrome, Firefox, Safari, Edge)  
3. The application will load with sample data  

---

## 📖 Usage

### For Patients:
1. Navigate to the **Patient Intake** page to submit your information  
2. Use the **Feedback** page to rate your consultation experience  
3. Access the **Follow-up** page to track symptoms and care plan progress  

### For Healthcare Providers:
1. Monitor the **Dashboard** for real-time metrics  
2. Review patient feedback and ratings  
3. Track follow-up care adherence  
4. Identify staff members needing quality reviews  

### For Administrators:
1. View overall performance analytics  
2. Monitor patient satisfaction trends  
3. Identify areas for service improvement  
4. Track quality assurance metrics  

---

## 💾 Data Persistence
MediAssist uses the browser's **localStorage API** to save all data locally:  
- Data persists between browser sessions  
- No server or internet connection required  
- All information remains on the user's device  
- Data can be cleared via browser settings  

---

## 🌐 Browser Compatibility
MediAssist is compatible with:  
- Chrome 60+  
- Firefox 55+  
- Safari 12+  
- Edge 79+  

---

## 🎨 Customization
You can customize the theme by modifying the CSS variables:

```css
:root {
    --aws-orange: #ff9900;      /* Primary accent color */
    --aws-dark-blue: #232f3e;   /* Primary dark color */
    --aws-light-blue: #0073bb;  /* Primary light color */
    --aws-background: #f2f3f3;  /* Background color */
}
