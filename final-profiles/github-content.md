# Phase 3: GitHub Enhancement & Open Source Engagement

**Profile:** github.com/0xlislim
**Goal:** Optimize GitHub presence for DevOps & Full-Stack visibility

---

## 1. PROFILE README (Create `0xlislim/0xlislim` repository)

Create a new repository named exactly `0xlislim` and add this README.md:

```markdown
# Hi, I'm Ali Es-slimani

**Full-Stack Developer** transitioning to **DevOps & Systems Programming**

Currently building scalable applications at Zone01 Oujda | CP Club President | CTF Winner

---

## What I Build

**Microservices & Full-Stack**
- Production applications with Angular + Spring Boot
- REST APIs handling 100+ concurrent users
- 85% test coverage with CI/CD pipelines

**Real-Time Systems**
- WebSocket applications in Go (500+ req/sec)
- Concurrent backends with connection pooling
- 40% server load reduction through optimization

**Systems Programming**
- Unix shell implementation in Rust
- Direct Linux kernel system calls
- Memory-safe process management

---

## Tech Stack

**Frontend:** Angular | TypeScript | JavaScript

**Backend:** Java | Spring Boot | Go | Node.js | GraphQL

**Systems:** Rust | C | Linux | Bash

**DevOps:** Docker | Kubernetes | CI/CD | GitLab CI/CD | AWS

**Databases:** PostgreSQL | MySQL | SQLite

---

## Featured Projects

| Project | Description | Tech |
|---------|-------------|------|
| [01Blog](https://github.com/0xlislim/01blog) | Microservices blogging platform | Angular, Spring Boot, Docker |
| [Real-Time Forum](https://github.com/0xlislim/real-time-forum) | WebSocket chat with 500+ req/sec | Go, WebSockets, SQLite |
| [0-Shell](https://github.com/0xlislim/0-shell) | Unix shell from scratch | Rust, Linux System Calls |

---

## Currently Learning

- Advanced Kubernetes orchestration
- Terraform & Infrastructure as Code
- AWS Cloud Architecture
- Site Reliability Engineering (SRE)

---

## GitHub Stats

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api?username=0xlislim&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
</p>

<p align="center">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=0xlislim&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</p>

---

## Let's Connect

[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](https://linkedin.com/in/ali-esslimani)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white)](https://github.com/0xlislim)

---

*"Systems programming isn't just about performance—it's about understanding what your code actually does."*
```

---

## 2. PROFILE BIO (160 characters max)

**Option A - DevOps Focus:**
```
Full-Stack Developer | DevOps Enthusiast | Angular | Spring Boot | Go | Rust | Building scalable systems at Zone01
```

**Option B - Achievement Focus:**
```
Software Engineer | CTF Winner | CP Club President | Docker | Kubernetes | Microservices | Systems Programming
```

**Option C - Transitioning:**
```
Full-Stack Dev -> DevOps | Angular + Spring Boot + Go + Rust | Zone01 Oujda | Open to opportunities
```

---

## 3. PROFILE SETTINGS TO UPDATE

| Setting | Value |
|---------|-------|
| **Name** | Ali Es-slimani |
| **Bio** | (Choose from above) |
| **Company** | @Zone01-Oujda |
| **Location** | Oujda, Morocco |
| **Website** | linkedin.com/in/ali-esslimani |
| **Twitter** | (Add if you have one) |
| **Pronouns** | (Optional) |

---

## 4. PINNED REPOSITORIES (Pin exactly 6)

### Recommended Order:

| Pin # | Repository | Why Pin It |
|-------|-----------|------------|
| 1 | **01Blog** | Flagship - Microservices, Angular, Spring Boot, Docker |
| 2 | **real-time-forum** | Go + WebSockets - DevOps relevant language |
| 3 | **0-shell** | Rust systems programming - impressive |
| 4 | **groupie-tracker** | Go HTTP server + API consumption |
| 5 | **atm-management-system** | C systems programming foundation |
| 6 | (Future) **devops-project** | Docker/K8s/Terraform project |

### Projects to Unpin:
- piscine-js (learning exercises)
- Bomberman-Dom (less relevant to DevOps)
- Any incomplete projects

---

## 5. README TEMPLATES FOR PINNED PROJECTS

### Template for 01Blog:

```markdown
# 01Blog - Microservices Blogging Platform

A full-stack blogging platform built with microservices architecture, demonstrating modern web development practices.

## Features

- Microservices architecture separating frontend, backend, and database
- JWT authentication with role-based access control
- RESTful APIs following OpenAPI specifications
- Support for 100+ concurrent users
- 85% test coverage

## Tech Stack

| Layer | Technology |
|-------|------------|
| Frontend | Angular 17+, TypeScript |
| Backend | Java 21, Spring Boot 3 |
| Database | PostgreSQL |
| DevOps | Docker, Docker Compose, GitLab CI/CD |

## Architecture

```
┌─────────────┐     ┌─────────────┐     ┌─────────────┐
│   Angular   │────▶│ Spring Boot │────▶│ PostgreSQL  │
│  Frontend   │     │   Backend   │     │  Database   │
└─────────────┘     └─────────────┘     └─────────────┘
```

## Quick Start

### Prerequisites
- Docker & Docker Compose
- Java 21+ (for local development)
- Node.js 18+ (for local development)

### Run with Docker
```bash
git clone https://github.com/0xlislim/01blog.git
cd 01blog
docker-compose up -d
```

Access the application at `http://localhost:4200`

### Local Development
```bash
# Backend
cd backend
./mvnw spring-boot:run

# Frontend
cd frontend
npm install
ng serve
```

## API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| POST | /api/auth/register | User registration |
| POST | /api/auth/login | User login |
| GET | /api/articles | List all articles |
| POST | /api/articles | Create article |
| GET | /api/articles/{id} | Get article by ID |

## Testing

```bash
# Run backend tests
./mvnw test

# Run frontend tests
ng test
```

## Author

**Ali Es-slimani** - [LinkedIn](https://linkedin.com/in/ali-esslimani) | [GitHub](https://github.com/0xlislim)

## License

MIT
```

---

### Template for Real-Time Forum:

```markdown
# Real-Time Forum

A WebSocket-powered forum application with live private messaging, built entirely in Go with vanilla JavaScript frontend.

## Features

- Real-time bidirectional communication via WebSockets
- Live private messaging between users
- User presence indicators (online/offline)
- Session-based authentication with bcrypt
- SQLite database for persistence
- Single-page application (no frameworks)

## Performance

- Optimized for **500+ requests/second**
- Connection pooling reduced server load by **40%**
- Efficient goroutine management for concurrent connections

## Tech Stack

| Component | Technology |
|-----------|------------|
| Backend | Go 1.21+, Gorilla WebSocket |
| Frontend | Vanilla JavaScript (ES6+) |
| Database | SQLite |
| Auth | bcrypt, Session Cookies |

## Architecture

```
┌─────────────────┐
│  Browser (JS)   │
└────────┬────────┘
         │ WebSocket
         ▼
┌─────────────────┐
│   Go Server     │
│  ┌───────────┐  │
│  │ WebSocket │  │
│  │  Handler  │  │
│  └─────┬─────┘  │
│        │        │
│  ┌─────▼─────┐  │
│  │  SQLite   │  │
│  └───────────┘  │
└─────────────────┘
```

## Quick Start

```bash
# Clone the repository
git clone https://github.com/0xlislim/real-time-forum.git
cd real-time-forum

# Run the server
go run .

# Or build and run
go build -o forum
./forum
```

Access at `http://localhost:8080`

## Project Structure

```
real-time-forum/
├── main.go              # Entry point
├── handlers/            # HTTP & WebSocket handlers
├── models/              # Data models
├── database/            # SQLite operations
├── static/              # Frontend assets
│   ├── js/
│   ├── css/
│   └── index.html
└── go.mod
```

## Key Learnings

- Go's goroutines enable efficient concurrent connections
- WebSocket connection lifecycle management
- Real-time state synchronization across clients
- Session management without external libraries

## Author

**Ali Es-slimani** - [LinkedIn](https://linkedin.com/in/ali-esslimani) | [GitHub](https://github.com/0xlislim)
```

---

### Template for 0-Shell:

```markdown
# 0-Shell - Unix Shell in Rust

A Unix shell implementation written from scratch in Rust, interfacing directly with the Linux kernel via system calls.

## Features

- Command execution with argument parsing
- Process management (fork, exec, wait)
- Signal handling (SIGINT, SIGTERM, etc.)
- I/O redirection (>, <, >>)
- Pipe support (|)
- Built-in commands (cd, exit, echo, etc.)
- Memory-safe design leveraging Rust's ownership model

## Why Rust?

Rust's ownership model catches memory bugs at compile time that would be runtime errors (or security vulnerabilities) in C. This shell demonstrates:
- Zero-cost abstractions
- Memory safety without garbage collection
- Direct system call interface

## Tech Stack

- **Language:** Rust
- **System Calls:** libc bindings
- **Target:** Linux x86_64

## Quick Start

```bash
# Clone and build
git clone https://github.com/0xlislim/0-shell.git
cd 0-shell
cargo build --release

# Run the shell
./target/release/0-shell
```

## Supported Features

| Feature | Status | Example |
|---------|--------|---------|
| Basic commands | Done | `ls -la` |
| Pipes | Done | `cat file \| grep pattern` |
| Redirection | Done | `echo "text" > file` |
| Background jobs | Done | `sleep 10 &` |
| Signal handling | Done | Ctrl+C, Ctrl+Z |
| Built-ins | Done | cd, exit, echo, pwd |

## Architecture

```
┌─────────────────────────────────────────┐
│              0-Shell                    │
├─────────────────────────────────────────┤
│  Input Parser  │  Command Executor      │
├────────────────┼────────────────────────┤
│      Rust Standard Library              │
├─────────────────────────────────────────┤
│           libc (System Calls)           │
├─────────────────────────────────────────┤
│            Linux Kernel                 │
└─────────────────────────────────────────┘
```

## Key System Calls Used

- `fork()` - Create child process
- `execve()` - Execute program
- `waitpid()` - Wait for child process
- `dup2()` - Duplicate file descriptors
- `pipe()` - Create pipe
- `signal()` - Set signal handlers

## Author

**Ali Es-slimani** - [LinkedIn](https://linkedin.com/in/ali-esslimani) | [GitHub](https://github.com/0xlislim)
```

---

## 6. REPOSITORIES TO FORK (5 minimum)

### DevOps & Infrastructure

| Repository | Why Fork It |
|------------|-------------|
| [kubernetes/kubernetes](https://github.com/kubernetes/kubernetes) | Industry standard, show interest |
| [hashicorp/terraform](https://github.com/hashicorp/terraform) | IaC is essential for DevOps |
| [argoproj/argo-cd](https://github.com/argoproj/argo-cd) | GitOps for Kubernetes |
| [traefik/traefik](https://github.com/traefik/traefik) | Cloud-native reverse proxy in Go |
| [prometheus/prometheus](https://github.com/prometheus/prometheus) | Monitoring - core DevOps tool |

### Go Projects (Your Primary Backend Language)

| Repository | Why Fork It |
|------------|-------------|
| [gin-gonic/gin](https://github.com/gin-gonic/gin) | Popular Go web framework |
| [gorilla/websocket](https://github.com/gorilla/websocket) | You used this! |
| [spf13/cobra](https://github.com/spf13/cobra) | CLI apps in Go |

### Rust Projects (Systems Programming)

| Repository | Why Fork It |
|------------|-------------|
| [BurntSushi/ripgrep](https://github.com/BurntSushi/ripgrep) | Excellent Rust codebase |
| [tokio-rs/tokio](https://github.com/tokio-rs/tokio) | Async runtime for Rust |

---

## 7. REPOSITORIES TO STAR (15 minimum)

### DevOps Essential (Star All)
- [ ] kubernetes/kubernetes
- [ ] hashicorp/terraform
- [ ] docker/compose
- [ ] argoproj/argo-cd
- [ ] prometheus/prometheus
- [ ] grafana/grafana

### Go Ecosystem
- [ ] golang/go
- [ ] gin-gonic/gin
- [ ] gorilla/websocket
- [ ] containerd/containerd

### Rust Ecosystem
- [ ] rust-lang/rust
- [ ] BurntSushi/ripgrep
- [ ] firecracker-microvm/firecracker

### Awesome Lists
- [ ] avelino/awesome-go
- [ ] rust-unofficial/awesome-rust
- [ ] wmariuss/awesome-devops

### Spring Boot / Java
- [ ] spring-projects/spring-boot
- [ ] iluwatar/java-design-patterns

---

## 8. DEVELOPERS TO FOLLOW (15 minimum)

### DevOps Leaders
| Username | Why Follow |
|----------|------------|
| kelseyhightower | Kubernetes pioneer, excellent content |
| jessfraz | Security + containers expert |
| ahmetb | Kubernetes tools creator |
| brendanburns | Kubernetes co-founder |

### Go Developers
| Username | Why Follow |
|----------|------------|
| spf13 | Creator of Hugo, Cobra, Viper |
| rakyll | Go team at Google |
| bradfitz | Go core team |

### Rust Developers
| Username | Why Follow |
|----------|------------|
| BurntSushi | ripgrep creator |
| dtolnay | Rust libraries maintainer |
| withoutboats | Rust async pioneer |

### Java/Spring
| Username | Why Follow |
|----------|------------|
| joshlong | Spring Developer Advocate |
| starbuxman | Spring ecosystem |

### Zone01/42 Network
- [ ] Follow 10+ peers from Zone01 Oujda
- [ ] Follow alumni from 1337 Coding School

---

## 9. COMMUNITIES TO JOIN (3 minimum)

### Discord Servers

| Community | Link | Action |
|-----------|------|--------|
| **Gophers** | discord.gg/golang | Go programming |
| **Rust Programming** | discord.gg/rust-lang | Rust community |
| **DevOps, Tech & Cloud** | Search on Discord | General DevOps |
| **Kubernetes** | kubernetes.io/community | K8s community |

### Reddit Communities

| Subreddit | Purpose |
|-----------|---------|
| r/devops | DevOps discussions, job posts |
| r/kubernetes | K8s help and news |
| r/golang | Go programming |
| r/rust | Rust programming |
| r/java | Java ecosystem |

### Other Platforms

| Platform | Action |
|----------|--------|
| **DEV.to** | Create account, follow DevOps tags |
| **Hashnode** | Technical blogging platform |
| **Stack Overflow** | Answer questions in your expertise |

---

## 10. COMMUNITY ENGAGEMENT (3 discussions minimum)

### Introduction Template (Post in each community)

```
Hey everyone!

I'm Ali, a Full-Stack Developer from Morocco transitioning into DevOps and systems programming.

Background:
- Currently at Zone01 Oujda (42 Network)
- Working with Angular + Spring Boot for full-stack
- Built a WebSocket forum in Go (500+ req/sec)
- Implemented a Unix shell in Rust

Currently learning:
- Kubernetes orchestration
- Terraform for IaC
- AWS cloud services

Looking forward to learning from this community and contributing where I can!

GitHub: github.com/0xlislim
```

### Engagement Ideas

1. **Answer a beginner question** about Go, Rust, or Spring Boot
2. **Share your 0-Shell project** in r/rust - ask for code review
3. **Post about your Real-Time Forum** performance optimizations in r/golang
4. **Ask a question** about Kubernetes best practices in r/devops
5. **Comment on interesting posts** with thoughtful responses

---

## 11. CHECKLIST

### Profile Setup
- [ ] Create `0xlislim/0xlislim` repository with README
- [ ] Update bio (choose from options above)
- [ ] Add location: Oujda, Morocco
- [ ] Add company: Zone01 Oujda
- [ ] Add website: linkedin.com/in/ali-esslimani
- [ ] Update profile picture (same as LinkedIn)

### Pinned Repositories
- [ ] Pin 01Blog (or equivalent microservices project)
- [ ] Pin real-time-forum
- [ ] Pin 0-shell (Rust project)
- [ ] Pin groupie-tracker (Go project)
- [ ] Pin atm-management-system (C project)
- [ ] Update READMEs for all pinned repos

### Open Source Engagement
- [ ] Fork 5 repositories (from list above)
- [ ] Star 15+ repositories (from list above)
- [ ] Follow 15+ developers (from list above)
- [ ] Follow 10+ Zone01/1337 peers

### Community
- [ ] Join 3 Discord/Reddit communities
- [ ] Introduce yourself in each community
- [ ] Engage in 3+ discussions
- [ ] Share one post about something learned

---

## 12. METRICS TO TRACK

| Metric | Before | After | Target |
|--------|--------|-------|--------|
| Followers | 14 | | 24+ |
| Following | 13 | | 28+ |
| Starred Repos | ? | | 15+ |
| Forked Repos | ? | | 5+ |
| Profile README | No | | Yes |
| Bio | No | | Yes |
| Community Memberships | 0 | | 3+ |

---

## NEXT PHASE

**Phase 4: Peer Collaboration**
- Peer review session with cohort members
- Endorse and recommend peers' profiles
- Support collective branding
- Share interesting repositories with cohort
