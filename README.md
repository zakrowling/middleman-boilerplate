# Moonshot Style Guide
A preliminary frontend style guide for Virgin Australia's new booking engine.

##To run:
bundle exec middleman

Now available on: 
http://localhost:4567/

## To build/compile a new static version:
bundle exec middleman build

This will add a "build" folder to root that is exported in vanilla HTML/CSS.

## How to push:
rsync -avz -e "ssh" /Users/Wilkinson/Development/virgin/moonshot-styleguide/build/ root@128.199.243.171:/var/www/html
