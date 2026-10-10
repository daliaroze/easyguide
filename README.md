# EasyGuide

EasyGuide is a mobile-first web application for creating and sharing visual, step-by-step guides.

The project aims to make everyday digital tasks easier to understand, especially for people who are less comfortable with technology.

## Planned Features

- Create, view, edit, and delete guides.
- Organize guides into ordered steps.
- Add images to guide steps.
- Read guides one step at a time.
- Organize guides using libraries and folders.
- Manage guides for family members through managed profiles.
- Share guides using read-only links.

## Tech Stack

**Backend**
- Java 21
- Spring Boot
- Spring Data JPA
- PostgreSQL
- Maven

**Frontend**
- React
- Vite
- JavaScript

**Development Tools**
- Git and GitHub
- IntelliJ IDEA

## Project Structure

```text
easyguide/
├── backend/       # Spring Boot application
├── frontend/      # React application
├── tasks.md       # Development roadmap
└── README.md      # Project documentation
```

## Running Locally

### Backend

The backend requires Java 21, PostgreSQL, and a configured `easyguide_db` database.

Set the `DB_PASSWORD` environment variable to the password of your local database user.

From the `backend` directory, run:

```powershell
.\mvnw.cmd spring-boot:run
```

The backend runs at `http://localhost:8080`.

### Frontend

The frontend requires Node.js and npm.

From the `frontend` directory, run:

```powershell
npm install
npm run dev
```

Open the local address displayed by Vite, usually `http://localhost:5173`.

## Development Status

EasyGuide is currently under active development. The initial backend, database connection, and React development environment have been set up.

The next phase focuses on implementing the Guides backend.

## Roadmap

See [tasks.md](tasks.md) for the development phases and task checklist.