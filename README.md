# SQL|PGSQL
- Matar sesiones o procesos:
  - `
    SELECT  * FROM pg_stat_activity WHERE datname='database';
    SELECT pg_terminate_backend(pid);
  `
- permission denied for sequence "NAME_SEQ"
  - `GRANT USAGE, SELECT ON SEQUENCE cities_id_seq TO www;`
  - `GRANT USAGE, SELECT ON ALL SEQUENCES IN SCHEMA public TO www;`
