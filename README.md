<pre>
+----------------------------------------------------------------------------+
| b5463                                                                      |
| Alexander Jakub Moravčík                                                   |
+----------------------------------------------------------------------------+

$ profile
current          KINO D4
also             SYSTEMS.
work             hardware / web software / self-hosted infrastructure

$ project kino-d4
status           D4-V1 prototype
purpose          four-camera synchronized capture
repository       <a href="https://github.com/b5463/kino-d4">github.com/b5463/kino-d4</a>

[CAM 1]---[CAM 2]----[CAM 3]-----+-->[ESP32-P4]-->[microSD originals]
[CAM 4]----/
             shared sync

hardware         ESP32-P4 / 4x ESP32-S3 camera nodes
software         KDP / Studio / schemas / simulator / API
capture          4 viewpoints / 1 shutter

$ project systems
status           2.0 release candidate
purpose          self-hosted application deployment
repository       <a href="https://github.com/b5463/systems">github.com/b5463/systems</a>

[ZIP]-->[BUILD]-->[DOCKER]-->[CADDY]-->[HTTPS]

services         deploys / logs / health / rollback / backups
access           admin only
runtime          Vue / Fastify / Docker / Caddy / PostgreSQL

$ stack
hardware         ESP32-P4 / ESP32-S3 / UART / Web Serial
application      TypeScript / React / Vue / Node.js / Fastify
infrastructure   PostgreSQL / Redis / Docker / Caddy / S3

$ links
projects         <a href="https://github.com/b5463?tab=repositories">github.com/b5463?tab=repositories</a>
sponsors         <a href="https://github.com/sponsors/b5463">github.com/sponsors/b5463</a>

$ _
</pre>