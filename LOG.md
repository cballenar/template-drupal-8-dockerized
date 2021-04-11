# Captain's Log

## 2021-04-11
- A couple weeks ago I started relearning Docker and trying a few setups
- Finally settled on a setup that allows installation of a virtually empty image with everything docker needs
    + Custom image build from drupal:8
    + Drupal 8.9.13 via composer
    + MariaDB 10.3
- Upon running docker-compose up machine should be pretty much ready to go.
- Just don't forget to create `./db-data/` and `./docroot/`
