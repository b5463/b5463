<pre>
b5463@github:~$ whoami
Alexander Jakub Moravčík

b5463@github:~$ focus --active
kino-d4    four-camera hardware + USB workbench
systems    self-hosted deployment engine
</pre>

<p align="center">
  <a href="https://github.com/b5463/kino-d4">[ KINO D4 ]</a>
  &nbsp;&nbsp;
  <a href="https://github.com/b5463/systems">[ SYSTEMS. ]</a>
  &nbsp;&nbsp;
  <a href="https://github.com/sponsors/b5463">[ SPONSOR ]</a>
</p>

Most of my work sits between a physical device and the software needed to configure, inspect, recover, and ship it.

## 00 / active

<pre>
+----+------------+-------------------+----------------------------------+
| ID | PROJECT    | STATE             | SCOPE                            |
+----+------------+-------------------+----------------------------------+
| 01 | KINO D4    | D4-V1 prototype   | camera hardware + application    |
| 02 | SYSTEMS.   | 2.0.0-rc.1        | deployment + host operations     |
+----+------------+-------------------+----------------------------------+
</pre>

## 01 / [KINO D4](https://github.com/b5463/kino-d4)

Four camera modules capture at the same instant. The originals stay intact; the software can turn them into a short parallax loop afterward.

<pre>
[CAM 01]--+
[CAM 02]--+
[CAM 03]--+-->[shared sync]-->[ESP32-P4]-->[microSD originals]
[CAM 04]--+                         |
                                   +-->[USB]-->[KINO Studio]

hardware      D4-V1 / prototype
studio        0.9.0
protocol      KDP 1
license       CERN-OHL-S-2.0 hardware / MIT software
</pre>

<details>
<summary>repository map</summary>

<pre>
hardware/       D4-V1 build files, manifest, revisions, ECNs
apps/studio/    USB control and capture interface
apps/api/       API foundation
packages/kdp/   KINO Device Protocol
packages/       schemas, simulator, and test fixtures
docs/           build, bring-up, recovery, and release notes
</pre>

</details>

[`OPEN KINO D4 ->`](https://github.com/b5463/kino-d4)

## 02 / [SYSTEMS.](https://github.com/b5463/systems)

A self-hosted deployment engine for taking a zip build through containers, HTTPS routing, checks, rollback, and backup.

<pre>
[ZIP]-->[BUILD]-->[DOCKER]-->[CADDY]-->[HTTPS]
                    |
                    +-->[LOGS]
                    +-->[HEALTH]
                    +-->[ROLLBACK]
                    +-->[BACKUPS]

release       2.0.0-rc.1
access        admin only
validation    Windows host pending
license       PolyForm Noncommercial 1.0.0
</pre>

<details>
<summary>repository map</summary>

<pre>
dashboard      Vue
api            Fastify / Node.js
data           PostgreSQL / Redis / S3
runtime        Docker / Caddy
operations     logs, health, rollback, and backup
</pre>

</details>

[`OPEN SYSTEMS. ->`](https://github.com/b5463/systems)

## 03 / workbench

<pre>
DEVICE ---> PROTOCOL ---> APPLICATION ---> DEPLOYMENT ---> OPERATIONS

ESP32        KDP            React / Vue      Docker          health checks
UART         Web Serial     TypeScript       Caddy           logs
microSD      JSON schemas   Node.js          HTTPS           recovery
</pre>

## 04 / links

<pre>
repos       <a href="https://github.com/b5463?tab=repositories">github.com/b5463?tab=repositories</a>
kino-d4     <a href="https://github.com/b5463/kino-d4">github.com/b5463/kino-d4</a>
systems     <a href="https://github.com/b5463/systems">github.com/b5463/systems</a>
sponsors    <a href="https://github.com/sponsors/b5463">github.com/sponsors/b5463</a>
</pre>