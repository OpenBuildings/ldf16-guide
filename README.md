# LDF16 guide

To run locally on https:

1. Add ldf16.dev to your `/etc/hosts` file pointing to `127.0.0.1`.
2. Trust `./scripts/ldf16.dev.crt` file on your system.
3. Run the following command:

        bundle exec jekyll s -H ldf16.dev --ssl-cert certs/ldf16.dev.crt --ssl-key certs/ldf16.dev.key -o
