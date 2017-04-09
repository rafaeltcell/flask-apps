# Flask Apps

## Testing Goodness

### Quokka

`docker-compose -f docker-compose.quokka.yml build`
`docker-compose -f docker-compose.quokka.yml run --service-ports web bash`
    - `$ manage accounts_createsuperuser`
    - `$ manage populate`
`docker-compose -f docker-compose.quokka.yml run --service-ports web`
`docker-compose -f docker-compose.quokka.yml run --service-ports tcell_local_web`
`docker-compose -f docker-compose.quokka.yml run --service-ports tcell_local_web_newrelic`
