[![This project is using Percy.io for visual regression testing.](https://percy.io/static/images/percy-badge.svg)](https://percy.io/3e4901a1/tatsiana.ch)

# compass.travel
*Travel Concierge Guide*

##### Prerequisites
1. Configure Bundler gems path: `bundle config path 'vendor/bundle' --local`
1. Confirm Bundler gems install path: `bundle config path`
1. Install [Jekyll](https://jekyllrb.com/): `bundle add jekyll`
1. Install GEMs: `bundle install`

##### Run in development mode
1. Open terminal
2. Change directory to a project: `cd ~/Projects/compass.travel/`
3. Run web site: `bundle exec jekyll serve --incremental`
4. Go to http://localhost:4000/

##### Additional commands
- to terminate web server: `press ctrl-c to stop`
- to build web site: `bundle exec jekyll build`

##### Visual testing
1. Open terminal
2. Change directory to a project: `cd ~/Projects/compass.travel/`
3. Build web site: `bundle exec jekyll serve --incremental`
4. Export token: `export PERCY_TOKEN=1234567890`
5. Run regression testing: `npm run test`

##### YAML config for GitHub
```
baseurl: "/compass.travel"  
url: "https://lesch-xx.github.io"  
```
