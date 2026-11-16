# Redlime Linux Practical Task

Four websites served by Nginx on one Ubuntu server, each on its own port with HTTPS.

| Folder | Port | Description |
|---|---|---|
| website1 | 7071 | HexaShop template |
| website2 | 7072 | Basic HTML page |
| website3 | 7073 | Basic HTML page |
| website4 | 7074 | Basic HTML page |

## Setup summary
- OS: Ubuntu Server 24.04 LTS
- Web server: Nginx (one server block per port)
- SSL: Self-signed certificate (no domain available)
- Database: MySQL (database: redlime_db)
