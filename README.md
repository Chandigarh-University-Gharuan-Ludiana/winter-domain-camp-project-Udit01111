[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/uELM4yXj)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=17609917&assignment_repo_type=AssignmentRepo)
cat <<EOL > README.md
# Real-Time Surveillance System

**Focus:** Enhancing National Security

## Project Overview
The Real-Time Surveillance System leverages cutting-edge AI and the MERN stack to process live CCTV feeds, identify suspicious activities, and alert authorities in real-time. This system is designed to enhance surveillance capabilities and ensure proactive crime prevention.

---

## Features

1. **AI-Powered Threat Detection**:
   - Detect suspicious activities like unauthorized entries, abandoned objects, or unusual movements.
   - Real-time processing using TensorFlow and Coco-SSD.

2. **Real-Time Alerts**:
   - Instant notifications via email, SMS, or in-app alerts.
   - Alerts include screenshots or video clips of detected events.

3. **User-Friendly Dashboard**:
   - React-based interface for monitoring multiple CCTV feeds.
   - Logs of alerts and real-time activity statistics.

4. **Crime Heatmap and Predictive Analytics**:
   - Visual representation of high-risk areas based on historical data.
   - AI-driven suggestions for resource allocation.

5. **Role-Based Security and Scalability**:
   - Role-based authentication for secure access.
   - Support for multiple locations with low latency.

---

## Tech Stack

- **Frontend:** React.js, TailwindCSS, Next.js
- **Backend:** Node.js, Express
- **AI Models:** TensorFlow, Coco-SSD, OpenCV
- **Database:** MongoDB Atlas
- **Deployment:** Vercel, AWS, Docker

---

## Setup Instructions

1. **Clone the repository:**
   \`\`\`bash
   git clone https://github.com/udit40115/real-time-surveillance-system.git
   \`\`\`

2. **Install dependencies:**
   \`\`\`bash
   cd surveillance-system
   npm install
   \`\`\`

3. **Run the development server:**
   \`\`\`bash
   npm run dev
   \`\`\`
   Open [http://localhost:3000](http://localhost:3000) in your browser to view the application.


4. **Start AI Microservice:**
   \`\`\`bash
   python ai_service/app.py
   \`\`\`
   Ensure the AI microservice is running to process live feeds.

5. **Deployed project link :**
  [https://qadu6jfdwjmiol35.vercel.app/]([url](https://qadu6jfdwjmiol35.vercel.app/))

---

## Outcomes

- **Increased Threat Detection:** Identify suspicious activities faster.
- **Real-Time Response:** Enable immediate action by security forces.
- **Improved Crime Prevention:** Reduce crime rates with proactive monitoring.
- **Enhanced Security Coverage:** Expand surveillance across large areas.
- **Efficient Resource Allocation:** Optimize resource deployment using AI-driven insights.

---

## Developer Information

- **Name:** Udit
- **UID:** 22BCS16515

---

## Screenshots and Demo

### Live Dashboard
_Add screenshots of the live video dashboard here._

### Detection Alerts
_Add screenshots of alert notifications and logs here._

### Heatmap Analytics
_Add screenshots of the crime heatmap feature here._

---

## License
This project is licensed under the MIT License.

## Contact
For queries, contact **udit40115@gmail.com**.
EOL
