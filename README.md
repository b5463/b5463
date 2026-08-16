<pre>
b5463@github:~$ whoami
Alexander Jakub Moravčík

b5463@github:~$ cat about.txt
I build things that live somewhere between a workbench and a server rack.
The current one has four lenses and a lot of UART.

b5463@github:~$ ls -lah ./work
drwxr-xr-x  01  <a href="https://github.com/b5463/kino-d4">kino-d4/</a>    four-lens camera + USB workbench
drwxr-xr-x  02  <a href="https://github.com/b5463/systems">systems/</a>    self-hosted deployment engine

b5463@github:~$ ./work/kino-d4/status
revision    D4-V1
state       prototype
capture     4 viewpoints / 1 shutter
rule        originals first
stack       ESP32-P4 / 4x ESP32-S3 / TypeScript / Web Serial

b5463@github:~$ ./work/systems/status
version     2.0 release candidate
state       host validation
job         zip -> container -> HTTPS
rule        green only after a real health check
stack       Vue / Fastify / Docker / Caddy / PostgreSQL

b5463@github:~$ printenv BUILD_RULES
ORIGINALS_FIRST=true
LOCAL_CONTROL=true
OBSERVED_STATUS=true
REPAIRABLE_HARDWARE=true

b5463@github:~$ <a href="https://github.com/sponsors/b5463">support --next-build</a>
opening GitHub Sponsors...

b5463@github:~$ _
</pre>