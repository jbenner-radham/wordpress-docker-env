wordpress-docker-env
====================
A basic WordPress environment in Docker.

How to Start
------------
1. From the CLI run `cp .env.example .env`.
2. Edit the `.env` file as desired.
3. Verify your config via `docker-compose config`.
4. From the CLI run `docker-compose up -d`.

How to Stop
--------------
1. From the CLI run `docker-compose stop`.

How to Destroy
--------------
1. From the CLI run `docker-compose down`.

See Also
--------
- [Environment Variables in Compose | Docker Documentation](https://docs.docker.com/compose/environment-variables/)
- [Declare Default Environment Variables in File | Docker Documentation](https://docs.docker.com/compose/env-file/)

License
-------
This project is licensed under the terms of the [MIT License (Expat)](https://tldrlegal.com/l/mit). You can view the full license [here](LICENSE).
