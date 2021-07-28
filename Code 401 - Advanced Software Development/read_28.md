# Configuring Django Settings: Best Practices

## Managing Django Settings: Issues :

**Different environments:**

> _Usually, you have several environments: local, dev, ci, qa, staging, production, etc. Each environment can have its own specific settings (for example: DEBUG = True, more verbose logging, additional apps, some mocked data, etc). You need an approach that allows you to keep all these Django setting configurations._

**Sensitive data:**

> _You have `SECRET_KEY` in each Django project. This data **CANNOT** be stored in VCS._

**Sharing settings between team members:**

> _You need a general approach to eliminate human error when working with the settings._

---

## Setting Configuration: Different Approaches

> _There is no built-in universal way to configure Django settings without hardcoding them._

### `settings_local.py`

_The basic idea of this method is to extend all **environment-specific** settings in the `settings_local.py` file, which is ignored by VCS._

- **Pros:** Secrets not in VCS.

- **Cons:**

        1. settings_local.py is not in VCS, so you can lose some of your Django environment settings.

        2. The Django settings file is a Python code, so settings_local.py can have some non-obvious logic.

        3. You need to have settings_local.example (in VCS) to share the default configurations for developers.

## Separate settings file for each environment

> _An extension that allows you to keep all configurations in VCS and to share default settings between developers._

---

---

---

# SSH

## What is SSH

> _SSH, or Secure Shell, is a remote administration protocol that allows users to control and modify their remote servers over the Internet_

## How Does SSH Work

_The SSH key command instructs your system that you want to open an encrypted Secure Shell Connection._

**`{user}`:** _represents the account you want to access._

```
For example, you may want to access the root user, which is
basically synonymous for system administrator with complete rights to
modify anything on the system.
```

**`{host}`:** _refers to the computer you want to access._

```
This can be an IP Address (e.g. 244.235.23.19) or a domain name (e.g. www.xyzdomain.com).
```
