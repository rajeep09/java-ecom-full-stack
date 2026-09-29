# E-Shop

Full-stack e-commerce application built with React, Vite, and Spring Boot.

## Contact

- Owner: Rajeev Sardar
- Email: [rajeevsardar919@gmail.com](mailto:rajeevsardar919@gmail.com)
- Mobile: [+91 93017 48619](tel:+919301748619)

## Run the project

Start the backend from `sb-ecom`:

```powershell
.\\mvnw.cmd spring-boot:run
```

Create `ecom-frontend/.env` with:

```env
VITE_BACK_END_URL=http://localhost:8080
```

Then start the frontend from `ecom-frontend`:

```powershell
npm install
npm run dev
```

Open `http://localhost:5173`.

## Development login accounts

| Role | Username | Password |
| --- | --- | --- |
| Admin | `admin` | `adminPass` |
| Seller | `seller1` | `password2` |
| Customer | `user1` | `password1` |

These development accounts are seeded in `sb-ecom/src/main/java/com/ecommerce/project/security/WebSecurityConfig.java`.
