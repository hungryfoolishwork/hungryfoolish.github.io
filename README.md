# Hungry Foolish

## Setup

### Establiash Hugo instance

    > cd hungryfoolishwork
    > hugo new site . --force

### Add simple theme

    > git submodule add https://github.com/davidhampgonsalves/hugo-black-and-light-theme.git themes/black-and-light

### Build static site

    > hugo -D

### Run local server

    > hugo server -D

### Create new page

    > hugo new posts/hello-world.md