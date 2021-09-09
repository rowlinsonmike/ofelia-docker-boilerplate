# OFELIA + DOCKER BOILERPLATE

## how to use

1. clone directory
2. `docker-compose -f docker-compose.yml build`
3. `docker-compose -f docker-compose.yml up -d`


This will stand up 2 containers. 1 sample container, `cron`, and ofelia. Ofelia will start the `cron` container every 5s and run the `cmd.py` file.

# cleanup

1. `docker-compose -f docker-compose.yml down`