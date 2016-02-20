mac-service
===========

`service`-like frontend for launchd, for people who've spent too long doing
CentOS system administration. And for everyone else too.

How to use
----------

### Listing services

List non-Apple services:

```bash
mac-service list
```

![Screenshot](screenshots/list.png?raw=true)

List all services:

```bash
mac-service list-all
```

![Screenshot](screenshots/list-all.png?raw=true)

### Controlling services

Start a service:

```bash
mac-service ssh-agent start
```

![Screenshot](screenshots/start.png?raw=true)

Restart a service:

```bash
mac-service ssh-agent restart
```

![Screenshot](screenshots/restart.png?raw=true)

Stop a service:

```bash
mac-service ssh-agent stop
```

![Screenshot](screenshots/stop.png?raw=true)

### Service info

Show a service's status:

```bash
mac-servce ssh-agent status
```

![Screenshot](screenshots/status.png)
