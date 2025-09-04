<h1 align="center">Coderr – Full-stack Service Platform</h1>

<p align="center">
A modular full-stack web application designed to connect service providers and customers through profile management, offer listings, and secure user authentication.
</p>

---

<h2 align="center">Project Overview</h2>

<p align="center">
This project was developed as part of a training module at the **Developer Akademie**.  
The **entire frontend** was provided by the academy, while the **backend was independently designed and implemented by me**.

The application consists of two separate repositories:
</p>

<table align="center">
  <tr>
    <th>Section</th>
    <th>Technologies</th>
    <th>Repository</th>
  </tr>
  <tr>
    <td>Frontend</td>
    <td>HTML, CSS, JavaScript</td>
    <td><a href="https://github.com/M-Nafi/Coderr-Frontend">Coderr-Frontend</a></td>
  </tr>
  <tr>
    <td>Backend</td>
    <td>Python, Django REST Framework, PostgreSQL</td>
    <td><a href="https://github.com/M-Nafi/Coderr-Backend">Coderr-Backend</a></td>
  </tr>
</table>

---

<h2 align="center">Backend Highlights</h2>

- Custom Django models for users, offers, reviews, and profiles  
- JWT-based authentication and secure session handling  
- RESTful API endpoints for frontend integration  
- PostgreSQL database for scalable data storage  
- Modular app structure with clear separation of concerns  
- Media file handling and environment configuration via `.env`

---

<h2 align="center">Architecture</h2>

<p align="center">
<code>[Frontend]</code> → <code>[REST API]</code> → <code>[Database]</code><br>
<code>HTML/CSS/JS</code> → <code>Django DRF</code> → <code>PostgreSQL</code>
</p>

---

<h2 align="center">Getting Started</h2>

<h3>Backend Setup</h3>

```bash
git clone https://github.com/M-Nafi/Coderr-Backend
cd Coderr-Backend
python -m venv venv
source venv/bin/activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
