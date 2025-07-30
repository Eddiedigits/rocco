# Rocco
Rocco is an AI assistant / project manager using Google Calendar, OpenAI Api and WeKan to summarise, prioritise and organise tasks across projects and including day-to-day tasks.

The middleware will run as a py4web app this allows making an API available and still being able to log in to the middleware for admin or user tasks.

Apart from the OpenAi API this should be a self hostable project using a few docker containers.
- Py4web + Celery + Celery-Redbeat
- Database not decided yet, for simple Auth a Sqlite database will be fine, if the functions expand in future I will switch to a Postgres container.
- WeKan + Mongo (Chosen for it's API Access and hostability)
- Redis (for redbeat schedules)

I am just making this for myself, if someone else finds it useful... wonderful.
