# directus

![directus](https://user-images.githubusercontent.com/522079/158864859-0fbeae62-9d7a-4619-b35e-f8fa5f68e0c8.png)

## with PostgreSQL and Redis (e.g. macOS with M1 and M2 CPUs)

---

<img src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" data-canonical-src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" width="260" />

### Make sure to change sensitive values (KEY, SECRET, ...) in production 🧐

#### Build and run your app with Compose

`docker-compose up -d`

#### and shut down

`docker-compose down`

**Don´t forget to change:**

```
ADMIN_EMAIL: your@mail.tld
```
in docker-compose.yml 😉

and update your admin user password:
```
npx directus users passwd --email user-email --password new-password
```

**Directus CLI-Documentation:**

https://docs.directus.io/self-hosted/cli.html
