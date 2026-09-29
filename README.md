# Al Ishaque Public School, Kamber – School Website (Flat Structure)

**Koi folder banane ki zaroorat nahi.** Saari files ek hi folder mein upload karo.

## Files (sab root mein)

```
index.html
about.html
academics.html
admissions.html
contact.html
events.html
gallery.html
notices.html
login.html
admin-dashboard.html
student-dashboard.html
teacher-dashboard.html
styles.css
main.js
README.md
```

## Demo Login

| Role    | Username | Password   |
|---------|----------|------------|
| Admin   | admin    | admin123   |
| Teacher | teacher  | teacher123 |
| Student | student  | student123 |
| Parent  | parent   | parent123  |

## Kaise Upload karein (GitHub Pages)

1. GitHub pe naya repo banao (ya purana use karo)
2. **Saari files seedha root mein upload karo** – koi `css/`, `js/`, `admin/` folder mat banao
3. Settings → Pages → Source = `main` branch, folder = `/ (root)`
4. 1-2 minute wait karke site open karo

## Mobile pe CSS nahi aa rahi thi?

Ab paths flat hain (`styles.css` aur `main.js`), isliye mobile aur computer dono pe same tarah kaam karega.

## Features

- Home, About, Academics, Admissions (working form), Events, Gallery, Notices, Contact
- Portal Login (Student / Parent / Teacher / Admin)
- Dark / Light theme
- Responsive design
- Admission applications localStorage mein save hote hain aur Admin dashboard mein dikhte hain
