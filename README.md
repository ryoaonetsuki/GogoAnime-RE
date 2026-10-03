# GogoAnime-RE

A vanilla PHP CMS for building anime streaming platforms with external video embedding.

## Overview

The project provides an anime content management system with an admin panel, anime detail pages, external video embeds, and deployment tooling.

## Requirements

- PHP-compatible web server
- MySQL/MariaDB if required by the current configuration
- Apache with `.htaccess` support, or an equivalent configured server
- Required PHP extensions for the installed application

## Installation

Clone or download the repository to your web server:

```bash
git clone https://github.com/ryoaonetsuki/GogoAnime-RE.git
```

Place the project in the server's document root and follow the repository's installation/configuration documentation.

## Configuration

Review `INSTALLATION.md` and `CONFIGURATION.md` before starting the application. Configure database credentials and any external services through the supported configuration files.

Never commit production passwords, API keys, or database credentials.

## Admin Panel

The project includes an administration interface for managing anime content. Follow `ADMIN_GUIDE.md` for the current workflow and configuration.

## Documentation

- `ADMIN_GUIDE.md` — admin panel usage
- `ARCHITECTURE.md` — system architecture
- `INSTALLATION.md` — installation
- `CONFIGURATION.md` — configuration
- `SECURITY.md` — security guidance
- `TROUBLESHOOTING.md` — troubleshooting

## Deployment

After configuring PHP and the database, deploy the application to a compatible web server and verify rewrite rules, permissions, and external embeds.

## Troubleshooting

Check `TROUBLESHOOTING.md` and the server/PHP logs when pages or database operations fail.

## Notes

Only use external media and embeds that you are authorized to display.
