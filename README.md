# Airbnb Clone Frontend

Angular 17 frontend for an Airbnb-style accommodation booking platform. Connects to the [airbnb-clone-back](https://github.com/ythalorossy/airbnb-clone-back) REST API.

## Tech Stack

| Component | Technology |
|---|---|
| Framework | Angular 17.3.5 |
| Language | TypeScript |
| UI Library | Angular CLI |
| API Client | HttpClient |
| Build | Angular CLI |

## Project Structure

```
src/
├── app/
│   ├── listing/         # Listing pages and components
│   ├── booking/         # Booking flow components
│   ├── user/            # User/auth components
│   └── shared/          # Shared components, services
├── environments/        # Environment configs
└── assets/             # Static assets
```

## Getting Started

### Prerequisites
- Node.js 18+
- Angular CLI 17

```bash
npm install -g @angular/cli@17
```

### Development Server

```bash
ng serve
```

Navigate to `http://localhost:4200/`. The app will automatically reload on file changes.

### Build

```bash
ng build
```

Build artifacts are stored in `dist/`.

### Run Tests

```bash
ng test
```

## Environment

Environment files are in `src/environments/`:
- `environment.ts` — development
- `environment.prod.ts` — production

**Note:** Update the API base URL to point to your backend instance.

## Related Projects

- [airbnb-clone-back](https://github.com/ythalorossy/airbnb-clone-back) — Spring Boot REST API backend

---

**YRoss** · [LinkedIn](https://www.linkedin.com/in/ythalorossy/) · [GitHub Profile](https://github.com/ythalorossy)