# Parsons MPSCD

Production URL: https://mpscd.parsons.edu

## Developing
1. Install the [Jekyll gem] with `gem install jekyll bundler`
3. Navigate to root directory
4. Run `bundle install`
4. Run `bundle exec jekyll serve`
5. Compiles to `/_site`
6. Opens at 'http://localhost:4000'
7. Work on `develop` branch and merge into `master` when you want to deploy (see below)

Jekyll will compile your SCSS and changes to `application.js`. If you need to combine `.js` files, you can use Codekit to compile them.

## Deploying/Publishing
1. Merge your changes into `master` and push.
2. Check your changes on production by using the Preview link in Siteleaf.
3. When you’re ready, click Publish.

<hr>

- by tagging a project `important`, you can create a special announcement block in the Explore section
- you can choose whether a post should be a `text` or `image`

<hr>

## Typeface
The typeface is open-source and available here: https://github.com/XXIX/mps-typeface

To update the webfonts:
1. Follow directions in [the repo](https://github.com/XXIX/mps-typeface) to export from Glyphs
2. Replace the `.woff` files

## CMS and updating
- Year filter needs to be added manually to `_data/filters.yml`
- Countdown date needs to be formatted as `05/11/2021 7:01 PM EDT`. Do not use Siteleaf's date picker.
