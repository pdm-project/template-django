# Django Project Template

This is a basic template Django project using the latest template feature introduced in PDM 2.8.0.

[![pdm-managed](https://img.shields.io/badge/pdm-managed-blueviolet)](https://pdm.fming.dev)
[![Django Badge](https://img.shields.io/badge/django-4?logo=django&labelColor=%23092E20&color=white)](https://www.djangoproject.com/)

## Use this template

```bash
$ pdm init django
```

Or create a new project at the given path:

```bash
$ pdm init -p django_project django
```

Visit https://localhost:8000 to see the welcome page.

## Development

Create a new app:

```bash
$ pdm run manage.py startapp <app_name>
```

Migrate DB:

```bash
$ pdm migrate
```

Start development server:

```bash
$ pdm start
```

Call other `manage.py` commands:

```bash
$ pdm run manage.py <command> [options]
```

## License

This project is licensed under the terms of the MIT license.
