# 🌟 NeonCode.Ai

<div align="center">


### Modern Django-based AI Image Generator with Interactive 3D Experience

[![Python](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/downloads/)
[![Django](https://img.shields.io/badge/Django-4.0+-green.svg)](https://www.djangoproject.com/)
[![Three.js](https://img.shields.io/badge/Three.js-Latest-orange.svg)](https://threejs.org/)
[![License](https://img.shields.io/badge/License-MIT-purple.svg)](LICENSE)

[Live Demo](https://neoncode.ai) • [Documentation](docs/) • [Report Bug](issues/) • [Request Feature](issues/)

![NeonCode.Ai Demo](screenshots/demo.gif)

</div>

## ✨ Features

<div align="center">

| Feature | Description |
|---------|-------------|
| 🎨 AI Generation | State-of-the-art AI image generation with Django backend |
| 🤖 3D Interface | Interactive robot model with Three.js integration |
| 🌓 Theme Switching | Django session-based theme management |
| 💫 Shine Effects | Dynamic lighting with Three.js and Django templates |
| 📱 Responsive | Django template-based responsive design |
| 🔒 Authentication | Django built-in authentication system |
| 💾 History & Favorites | Django ORM-based data management |

</div>

## 🚀 Quick Start

### Prerequisites

Before you begin, ensure you have:

- Python 3.8 or higher installed
- pip (Python package manager)
- virtualenv or venv for isolation
- Git installed
- PostgreSQL (recommended for production)

### Dependencies

```txt
Django>=4.0.0
django-environ>=0.10.0
django-crispy-forms>=2.0
Pillow>=9.0.0
psycopg2-binary>=2.9.0
whitenoise>=6.0.0
gunicorn>=21.0.0
```

### Manual Setup

1. **Clone & Navigate** 📂
```bash
git clone https://github.com/yourusername/NeonCode.Ai.git
cd NeonCode.Ai
```

2. **Set Up Virtual Environment** 🏗️
```bash
# Windows
python -m venv venv
.\venv\Scripts\activate

# macOS/Linux
python3 -m venv venv
source venv/bin/activate
```

3. **Install Dependencies** 📦
```bash
pip install -r requirements.txt
```

4. **Environment Setup** ⚙️
Create a `.env` file in the root directory:
```env
DEBUG=True
SECRET_KEY=your-secret-key-here
ALLOWED_HOSTS=localhost,127.0.0.1
DATABASE_URL=sqlite:///db.sqlite3
STATIC_ROOT=staticfiles
MEDIA_ROOT=media
```

5. **Django Setup** 🗃️
```bash
# Create database tables
python manage.py migrate

# Create static files directory
python manage.py collectstatic

# Create a superuser (admin account)
python manage.py createsuperuser
```

6. **Launch Development Server** 🚀
```bash
python manage.py runserver
```

7. **Access the App** 🌐
   - Main site: `http://127.0.0.1:8000`
   - Admin panel: `http://127.0.0.1:8000/admin`

## 🎮 Django Apps Structure

```
NeonCode.Ai/
├── 📁 generator/                  # Main Django app
│   ├── 📁 migrations/            # Database migrations
│   ├── 📁 static/               # App-specific assets
│   │   ├── 📁 css/             # Stylesheets
│   │   ├── 📁 js/              # JavaScript files
│   │   └── 📁 models/          # 3D model files
│   ├── 📁 templates/            # Django templates
│   │   └── 📁 generator/       # App templates
│   ├── 📄 admin.py             # Admin interface
│   ├── 📄 apps.py              # App configuration
│   ├── 📄 forms.py             # Form definitions
│   ├── 📄 models.py            # Database models
│   ├── 📄 urls.py              # URL patterns
│   ├── 📄 views.py             # View logic
│   └── 📄 tests.py             # Unit tests
├── 📁 neoncode/                  # Project settings
│   ├── 📄 settings.py          # Django settings
│   ├── 📄 urls.py              # Root URL conf
│   └── 📄 wsgi.py              # WSGI config
├── 📁 static/                    # Global static files
├── 📁 media/                     # User uploads
├── 📁 templates/                 # Global templates
├── 📄 manage.py                 # Django CLI
├── 📄 requirements.txt          # Python dependencies
└── 📄 .env                      # Environment variables
```

## 🚀 Deployment

### Production Settings
Update `.env` for production:
```env
DEBUG=False
ALLOWED_HOSTS=your-domain.com
DATABASE_URL=postgres://user:password@localhost:5432/dbname
```


## 👏 Acknowledgments

- [Django](https://www.djangoproject.com/) - The web framework for perfectionists with deadlines
- [Three.js](https://threejs.org/) - 3D graphics library
- [Bootstrap](https://getbootstrap.com/) - Frontend toolkit
- [Font Awesome](https://fontawesome.com/) - Icon toolkit

## 📞 Contact & Support

- Email - amitkumar378054@gmail.com

---

<div align="center">

Made with ❤️ by Amit kumar

⭐️ Star us on GitHub — it motivates us a lot!

</div> 