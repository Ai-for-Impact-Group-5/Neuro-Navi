# Neuro-Navi
AI-Based Career Guidance System for Personalized career guidance powered by AI combines machine learning and real-time job market data
![image](https://github.com/user-attachments/assets/f2fa696a-698e-4794-b264-84383948971f)

---
🧩 Problem Statement
-
Traditional career counseling often falls short in addressing the unique needs of individuals. These methods typically suffer from:

:- ❌ Lack of Personalization – One-size-fits-all advice that overlooks individual strengths and goals.


 ⚖️ Limited Scalability – Human counselors can’t efficiently cater to large, diverse audiences.


 

 🕒 Outdated Industry Insights – Guidance is rarely aligned with real-time job market trends.

 

 📄 Career Prep Gaps – Inadequate support for essential job-readiness components like resume building, cover letters, and interview preparation.

 ---

💡 How Neuro Navi Solves the Problem:
-
🎯 Personalized Career Guidance
-
Uses ML algorithms (Distance Vector & Random Forest) to recommend optimal career paths based on user skills, interests, and goals.

🧠 Skill Gap Analysis
-
Compares user profiles with industry standards to identify missing competencies and suggests learning resources to close the gap.

🌐 Real-Time Job Market Insights
-
Integrates APIs from Glassdoor and Indeed to deliver current job trends, in-demand roles, salary benchmarks, and skill requirements.

📝 Automated Career Document Generation
-
Generates professional resumes, cover letters, and interview preparation content tailored to each user.

---

✨ Features & Unique Selling Propositions (USPs)
-

Neuro Navi is an intelligent, end-to-end AI-Based Career Guidance System that transforms the way individuals navigate their professional journey. Here's what makes it powerful and unique:

🚀 Core Features
-
| Feature                                | Description                                                                                             |
| -------------------------------------- | ------------------------------------------------------------------------------------------------------- |
| 🎯 **AI Career Predictions**           | Suggests optimal career paths using Distance Vector and Random Forest ML models.                        |
| 🧠 **Skill Gap Analysis**              | Detects missing skills compared to market demands and helps users bridge the gap.                       |
| 📚 **Personalized Learning Paths**     | Recommends tailored courses and certifications to enhance career readiness.                             |
| 🌐 **Real-Time Job Market Insights**   | Live integrations with Glassdoor and Indeed to fetch up-to-date job trends, salaries, and skill demand. |
| 📝 **Resume & Cover Letter Generator** | Auto-generates professional documents personalized to user profiles and targeted roles.                 |
| 🗣️ **Interview Prep Tools**           | Offers mock questions, tips, and simulations for interview readiness.                                   |
| 🧪 **Quiz Generator with Analytics**   | Analyzes user interests and aptitude to further refine recommendations.                                 |
| 🔐 **Secure User Auth**                | User authentication powered by Clerk for privacy and data safety.                                       |


🌟 What Sets Neuro Navi Apart?
-
USP	Why It Matters
🧩 Complete Career Ecosystem	From assessment to job prep — all in one seamless platform.


🧠 AI + Real-Time Data Fusion	Combines machine learning with real-world market data for ultra-relevant suggestions.


🛠️ Hyper-Personalized Guidance	Every recommendation is data-driven and uniquely tailored to the user.

☁️ Cloud-Native & Scalable	Built using Next.js and Neon PostgreSQL for modern, scalable deployment.

🧑‍💼 For Students & Professionals	A universal tool usable across career stages and industries.

🌍 Future-Ready: Multilingual & Agentic AI	Roadmap includes multilingual support and smart AI agents for autonomous mentoring.

---
🔌 APIs & Integrations Used
-
| API / Service                                             | Purpose                                                                                                         |
| --------------------------------------------------------- | --------------------------------------------------------------------------------------------------------------- |
| 🔍 **Glassdoor API**                                      | Fetches real-time job trends, salary data, and company reviews for market insights.                             |
| 💼 **Indeed API**                                         | Supplies up-to-date job listings, role descriptions, and skill requirements.                                    |
| 🧠 **Gemini API (AI/NLP)**                                | Powers advanced natural language processing for resume generation, cover letters, and personalized suggestions. |
| 🔐 **Clerk Authentication**                               | Provides secure, modern user authentication and session management.                                             |
| 📊 **Custom ML Models (Distance Vector + Random Forest)** | Internally developed APIs used to generate career predictions and skill gap assessments.                        |

---
⚙️ Installation & Setup
-
Set up Neuro Navi on your local machine by following these steps:

🔗 1. Clone the Repository
         git clone https://github.com/your-username/neuro-navi.git
cd neuro-navi

📦 2. Install Frontend & Backend Dependencies

npm install
# or
yarn install

🧠 3. Set Up Python Environment (For ML Engine)

cd ml  # Go to the ML directory (if applicable)

# Create and activate virtual environment
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate

# Install required Python packages
pip install -r requirements.txt


🔐 4. Configure Environment Variables

Create a .env.local file in the root directory and add:

NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
CLERK_SECRET_KEY=your_clerk_secret_key
DATABASE_URL=your_postgresql_neon_url
GLASSDOOR_API_KEY=your_glassdoor_api_key
INDEED_API_KEY=your_indeed_api_key
GEMINI_API_KEY=your_gemini_api_key


🚀 5. Start the Application
-
Run the Next.js Dev Server

npm run dev
# or
yarn dev

🌐 6. Open in Browser

http://localhost:3000

Your Neuro Navi career guidance platform is now up and running! 🎉
-

![WhatsApp Image 2025-05-31 at 16 53 51_678daba4](https://github.com/user-attachments/assets/d487524b-ed7f-40c5-94f6-590b17935a36)

Landing Page 1 
 -
![landing page 1](https://github.com/user-attachments/assets/28c1ca22-656c-4492-9c8f-fe7e6fad3320)

Landing Page 2
-
![lp2](https://github.com/user-attachments/assets/ec9930e2-5ea8-4f20-b35f-15648b96ecb0)

Landing Page 3
-
![lp3](https://github.com/user-attachments/assets/f2b64705-8565-4319-93e3-78ba5a1fcf44)

Landing Page 4
-
![lp4](https://github.com/user-attachments/assets/3d688743-2fc1-453f-8db4-6f4345b1e58f)

Landing Page 5 
-
![lp5](https://github.com/user-attachments/assets/7c35a952-cab5-488c-b9b9-d5f8c29fda54)

Interview Preparation 
-
![interview prep](https://github.com/user-attachments/assets/800907ee-7ecf-43c7-883c-7ae0d9f53216)

Industry Insights
-
![industry i](https://github.com/user-attachments/assets/93c5a4ff-9ad8-4f75-bf98-e6bcde5ebece)

Resume Builder
-
![rb](https://github.com/user-attachments/assets/f5a34518-23f1-4863-b8be-97c504be9173)

Cover Letter Generator 
-
![clg](https://github.com/user-attachments/assets/0357a603-d8cb-4604-8344-30c092e65085)

Pipeline
-
![pipeline output](https://github.com/user-attachments/assets/18fa7513-f831-415f-9985-93c3234b6684)

Project Demo 
-
https://drive.google.com/drive/folders/1UZZLtJMCxjbeM80Te-9FymjtSNdfoZxV?usp=sharing






