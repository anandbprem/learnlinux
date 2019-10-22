Real Time Examples
------------------

> ** How to add existing user to an existing group? **
```
sudo usermod -a -G groupName userName

```

The **user will need to log out and log back**in to see their new group added.

    1. The -a (append) switch is essential. Otherwise, the user will be removed from any groups, not in the list.

    2. The -G switch takes a (comma-separated) list of additional groups to assign the user to.
