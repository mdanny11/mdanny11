<p align="center">
  <img src="banner1.png" alt="Mazimpaka Danny Banner" />
</p>
<h1 align="center">Hi 👋, I'm Mazimpaka Danny</h1>
<h3 align="center">Software Engineering Student | Backend Developer | Open to Opportunities</h3>

---

- 🎓 3rd Year Software Engineering Student at **Adventist University of Central Africa**
- 💼 Currently working as a **Data Moderator at Temu**, previously at **MTN as Customer Executive**
- 🌱 Learning and building projects with **Spring Boot**, **React**, **Linux**, and **Cloud Tools (Azure & Docker)**
- 👯 I’m looking to collaborate on open-source projects and real-world applications
- 🚀 Actively developing a **Sports League Management System** with Spring Boot and React
- ⚡ Fun fact: I love building tools that solve real problems — and I drink a *lot* of coffee ☕

---

### 🛠️ Tech Stack

![Java](https://img.shields.io/badge/Java-ED8B00?style=for-the-badge&logo=java&logoColor=white)
![Spring Boot](https://img.shields.io/badge/SpringBoot-6DB33F?style=for-the-badge&logo=springboot&logoColor=white)
![React](https://img.shields.io/badge/React-20232A?style=for-the-badge&logo=react&logoColor=61DAFB)
![Flutter](https://img.shields.io/badge/Flutter-02569B?style=for-the-badge&logo=flutter&logoColor=white)
![PostgreSQL](https://img.shields.io/badge/PostgreSQL-316192?style=for-the-badge&logo=postgresql&logoColor=white)
![MongoDB](https://img.shields.io/badge/MongoDB-4EA94B?style=for-the-badge&logo=mongodb&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black)
![Azure](https://img.shields.io/badge/Azure-0078D4?style=for-the-badge&logo=azure-devops&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white)

---

### 📌 Featured Projects
Here are some of my highlighted works. Visit my pinned repos to explore more!

- 🏟️ **Sports League Management System** – Backend system for managing teams, matches, and ticketing.
- 📱 **Mobile App with Calculator, Login & Signup Screens** – Built with Flutter.
- 🔐 **Linux Security Automation Scripts** – Automating firewall rules, Suricata IDS, and system monitoring.

---

### 📬 Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-blue?style=flat-square&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/your-linkedin-here)
[![Email](https://img.shields.io/badge/Email-grey?style=flat-square&logo=gmail&logoColor=white)](mailto:mdanny892@gmail.com)

---

> “Code is like humor. When you have to explain it, it’s bad.” – Cory House

Thanks for stopping by! 😊

import qrcode
from PIL import Image

# Define the GitHub profile URL
github_url = "https://github.com/mdanny11"

# Generate QR code
qr = qrcode.QRCode(
    version=1,
    error_correction=qrcode.constants.ERROR_CORRECT_H,
    box_size=10,
    border=4,
)
qr.add_data(github_url)
qr.make(fit=True)

# Create the image
img = qr.make_image(fill_color="black", back_color="white")

# Save the image
qr_path = "/mnt/data/mdanny11_github_qr.png"
img.save(qr_path)

qr_path

