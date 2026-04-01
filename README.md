# JAIPLAN

**Plataforma de gestión de eventos**  

JAIPLAN es una aplicación full-stack que permite a los usuarios **explorar eventos existentes**, **crear sus propios eventos** y gestionar entradas. Ideal para organizaciones y usuarios que desean centralizar la información de sus eventos de manera fácil y eficiente.  

- **Frontend:** Vue + Vite + Pinia + Axios  
- **Backend:** Laravel 

---

##  Estructura del proyecto
JAIPLAN/
├─ backend-banana/ ← Laravel (API, base de datos, modelos, controladores)
└─ frontend-banana/ ← Vue 3 + Vite (interfaz de usuario)


---

## ⚙️ Instalación y ejecución

### Frontend
```bash
cd frontend-banana
npm install
npm run dev

Servidor frontend: http://localhost:5173/
```

### Backend 

```bash
cd backend-banana
composer install
cp .env.example .env
php artisan key:generate
php artisan migrate --seed
php artisan serve

Servidor backend: http://127.0.0.1:8000/

