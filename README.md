# directus

![directus](https://user-images.githubusercontent.com/522079/158864859-0fbeae62-9d7a-4619-b35e-f8fa5f68e0c8.png)

## with PostGIS and Redis

---

<img src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" data-canonical-src="https://www.docker.com/wp-content/uploads/2022/03/Moby-logo.png" width="260" />

### Make sure to change sensitive values (KEY, SECRET, ...) in production 🧐

#### Build and run your app with Compose

```
docker compose up -d
```

and shut down

```
docker compose down
```

Update your admin user password:

```
npx directus users passwd --email user-email --password new-password
```

#### Import snapshot at startup:

When the container is started, the data is automatically imported from snapshot.yml

Create snapshot.yaml:

```
npx directus schema snapshot ./snapshot.yaml
```

**Directus CLI-Documentation:**

[https://docs.directus.io/self-hosted/cli.html](https://docs.directus.io/self-hosted/cli.html)
