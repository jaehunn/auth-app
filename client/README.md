no-standalone

- `docker build -t auth-app-client:0.1.0 .`
- image size: 684MB

- `docker run -d -p 3000:3000 auth-app-client:0.1.0`

---

standalone

- `docker build -t auth-app-client:0.1.1 .`
- image size: 196MB

- `docker run -d -p 3000:3000 auth-app-client:0.1.1`
