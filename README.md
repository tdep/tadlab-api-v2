# Tadlab API-v2
A Python/Django application to serve my personal website API endpoints for handling a PostgreSQL database.

## Details
The third iteration of my personal website used a Java/Springboot backend API hosted on Heroku to serve data, but when I built the
fourth iteration, I removed the dependency for that API in favor of serving static content. This works fine (and certainly
is faster since I was using the least expensive tier on Heroku, which means a delay when restarting the dyno), but I would
like to have more functionality and modularity.

So, I decided to rebuild the backend API using Python and Django to be hosted on Render.com. This also allows me to build
more applications into the same API if I want to add a blog, or a more robust project gallery, etc.

## Running Locally
If for whatever reason you wish to run this API locally, start your own `venv` install the dependencies use the following:
`python -m pip install -r requirements.txt`

## Changelog
Updates can be found in `CHANGELOG.md`.

## License
Tadlab API is licensed under the MIT license (see `LICENSE`).