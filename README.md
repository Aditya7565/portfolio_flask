```portfolio-website/
│
├── static/                         # Static assets like CSS, JS, and images
│   ├── static.css                  # Main CSS file
│   └── images/                     # All images used in the project
│       ├── about/                  # Images for About section
│       ├── certificate/            # Images for Certifications
│       ├── footer/                 # Images for Footer section
│       ├── project/                # Images for Projects
│       └── skills/                 # Images for Skills section
│
├── templates/                      # HTML templates rendered by Flask
│   ├── base.html                   # Base template (layout)
│   ├── index.html                  # Home page
│   ├── blog.html                   # Blog page
│   ├── certifications.html          # Certifications page
│   ├── contact.html                # Contact form page
│   ├── education.html              # Education details
│   ├── project.html                # Projects showcase
│   ├── skill.html                  # Skills page
│
├── app.py                          # Main Flask application
├── requirements.txt                # Python dependencies
├── README.md                       # Project documentation
└── .gitignore                      # Files/folders to ignore in Git  ```

💡 Features of project
🔥 Animated typing effect for job roles
💼 Projects section with hover animations
🎨 Responsive design using TailwindCSS
📄 Resume download button
🧭 Smooth navigation bar with anchor links
⚡ Flask-powered backend for future enhancements
🛠️ Technologies Used
💻 Frontend
HTML5
TailwindCSS
JavaScript
🔙 Backend
Python
Flask
⚙️ Tools Used
Git & GitHub
VS Code
📦 Python Dependencies
Make sure you have Python installed (preferably 3.10+). These libraries are required:

🚀 How to Run Locally

Clone the repository

git clone https://github.com/Krishna471/portfolio-website.git
cd portfolio-website
Create a virtual environment

python -m venv venv
Activate the virual environment

venv\Scripts\activate # On Windows
source venv/bin/activate # On Mac/Linux
Install flask

pip install flask
Run the Flask app

python app.py
Visit your browser

http://127.0.0.1:5000/

