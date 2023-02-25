# SQL|PGSQL
- Matar sesiones o procesos:
  - `
    SELECT  * FROM pg_stat_activity WHERE datname='database';
    SELECT pg_terminate_backend(pid);
  `
