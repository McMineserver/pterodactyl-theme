# pterodactyl-theme

## Information

Panel version: `v1.8.1`

## Applying theme

1. put the `.patch` file into the root of your panel install
2. run `php artisan down` to prevent access when applying
3. run `git apply <name of pathc file>` to apply the theme to your install
4. run `yarn` to install all needed packages for building the panel
5. run `yarn build:production` to build the panel
6. run `php artisan up` to make the panel available again

   DONE!
