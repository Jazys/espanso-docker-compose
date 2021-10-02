---
package_name: "docker-compose"
package_title: "docker-compose"
package_desc: "Docker compose command"
package_version: "1.0.0"
package_author: "Jazys"
package_repo: "https://github.com/Jazys/espanso-docker-compose"
---

Espanso package containing docker-compose command.

Really usefull for devOps.

When you need to deploy stack and debug, you run several time the same command.

With these shortcuts command, earn time !


## Installation

Make sure you have already installed [Espanso](https://espanso.org/install/) first.

```sh
espanso install docker-compose
espanso restart
```

Or with external link :

```sh
espanso install -e docker-compose https://github.com/Jazys/espanso-docker-compose
```

### List of available command

| Shortcut | Command
| - | -
| :dbuild | docker-compose build
| :dup | docker-compose up
| :dupd | docker-compose up -d
| :ddown | docker-compose down
| :dlogs | docker-compose logs
| :dlogsf | docker-compose logs -f
| :dexec | docker-compose exec
| :drestart | docker-compose restart

