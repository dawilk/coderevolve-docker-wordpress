# WordPress in Docker
This repo is the companion to [this blog post](https://coderevolve.com/wordpress-in-docker).

## Usage

1. Install Docker
   Linux Users: Also install docker-compose
2. Clone this repo: `git clone https://github.com/dawilk/coderevolve-docker-wordpress.git`
3. [optional] Change the website name and password variables in the _.env_ file (please do it)
4. Execute `docker-compose up -d` from the directory with the _docker-compose.yml_ file.
5. [optional] Remove the `environment` sections from the _docker-compose.yml_ and the wordpress variables from the _.env_ file after first launch.

For more information and a tutorial based on this repo, check out the blog post!
