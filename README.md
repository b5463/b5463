<pre>
 ____   ____    _  _     __     _____
| __ ) | ___|  | || |   / /_   |___ /
|  _  |___   | || |_ | '_     |_ | |_) | ___) | |__   _|| (_) |  ___) |
|____/ |____/     |_|   ___/  |____/

ALEXANDER JAKUB MORAVČÍK
hardware / software / self-hosted infrastructure
</pre>

<p align="center">
  <a href="https://github.com/b5463/kino-d4">[ kino-d4 ]</a>
  &nbsp;&nbsp;
  <a href="https://github.com/b5463/systems">[ systems ]</a>
  &nbsp;&nbsp;
  <a href="https://github.com/sponsors/b5463">[ sponsors ]</a>
</p>

## 00 / overview

<pre>
+-- active projects -----------------------------------------------------------+
|                                                                             |
|  01  KINO D4       D4-V1 prototype        hardware + application           |
|  02  SYSTEMS.      2.0 release candidate  deployment + operations          |
|                                                                             |
+-----------------------------------------------------------------------------+
</pre>

## 01 / [KINO D4](https://github.com/b5463/kino-d4)

<pre>
project       four-camera digital camera and USB workbench
hardware      D4-V1 prototype
studio        0.9.0
protocol      KDP 1
license       MIT software / CERN-OHL-S-2.0 hardware

[CAM 1]---[CAM 2]----[CAM 3]-----+-->[ESP32-P4]-->[microSD originals]
[CAM 4]----/
             shared sync

repository
  hardware documentation
  KDP wire protocol
  KINO Studio
  schemas and simulator
  API foundation

<a href="https://github.com/b5463/kino-d4">github.com/b5463/kino-d4</a>
</pre>

## 02 / [SYSTEMS.](https://github.com/b5463/systems)

<pre>
project       self-hosted deployment engine
version       2.0.0-rc.1
access        admin only
validation    Windows host pending
license       PolyForm Noncommercial 1.0.0

[ZIP]
  |
[BUILD]
  |
[DOCKER]-->[LOGS]-->[HEALTH]-->[ROLLBACK]
  |
[CADDY]
  |
[HTTPS]

repository
  Vue dashboard
  Fastify API
  Docker lifecycle
  Caddy routing
  health, backups, and recovery

<a href="https://github.com/b5463/systems">github.com/b5463/systems</a>
</pre>

## 03 / toolchain

<pre>
language        TypeScript / JavaScript
interface       React / Vue / Vite
services        Node.js / Fastify
data            PostgreSQL / Redis / S3 / SQLite
hardware        ESP32-P4 / ESP32-S3 / UART / Web Serial
operations      Docker / Caddy / GitHub Actions
</pre>

## 04 / links

<pre>
repositories    <a href="https://github.com/b5463?tab=repositories">github.com/b5463?tab=repositories</a>
kino-d4         <a href="https://github.com/b5463/kino-d4">github.com/b5463/kino-d4</a>
systems         <a href="https://github.com/b5463/systems">github.com/b5463/systems</a>
sponsors        <a href="https://github.com/sponsors/b5463">github.com/sponsors/b5463</a>
</pre>