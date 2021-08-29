# WP Docker

Pull the docker-compose.yml.
`git clone https://github.com/rangequest/wp-docker-compose.git`

create a `wp-content` folder for persistent data.

Docker compose up.
`docker-compose up -d`

`wp-content` folder data will persist even after decompose. mysql data will persist in a volume name `db_data`.