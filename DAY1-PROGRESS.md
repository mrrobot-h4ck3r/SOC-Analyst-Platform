# 📅 Day 1: Foundation Built - March 15, 2026

## ✅ What I Accomplished Today

### 1. Project Structure Created

sentinel-dash/
├── app.py # Main application
├── requirements.txt # Python dependencies
├── templates/ # HTML files
│ ├── base.html # Base template with navbar
│ ├── index.html # Landing page
│ ├── login.html # Login page
│ └── register.html # Registration page
└── static/ # CSS and assets
└── css/
└── style.css # Custom styling

### 2. Features Implemented
- ✅ User authentication system (login/register)
- ✅ Beautiful glass-morphism UI design
- ✅ MongoDB database connection
- ✅ Responsive mobile-friendly design
- ✅ Flash message system
- ✅ Navigation bar with conditional rendering
- ✅ Demo user account created

### 3. Technologies Used
| Tool | Purpose |
|------|---------|
| Python Flask | Web framework |
| MongoDB | Database |
| Bootstrap 5 | Frontend styling |
| Font Awesome | Icons |
| Google Fonts | Typography |

### 4. Challenges Faced & Solutions
| Challenge | Solution |
|-----------|----------|
| Setting up MongoDB on Kali | `sudo systemctl start mongodb` |
| Making UI look professional | Used glass-morphism effect |
| Password hashing security | Werkzeug security module |
  
### 5. Screenshots
- [ ]Landing page screenshot
      
- [ ] Login page screenshot
- [ ] Register page screenshot

### 6. Commands Used Today
```bash
# Start MongoDB
sudo systemctl start mongodb

# Create virtual environment
python3 -m venv venv
source venv/bin/activate

# Install dependencies
pip install -r requirements.txt

# Run the app
python3 app.py
