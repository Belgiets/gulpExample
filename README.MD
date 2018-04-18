## Gulp configuration example ##

### Project setup ###
- install deps:  
npm install
- compile assets once:  
./node_modules/.bin/gulp
- recompile assets automatically when files change:  
./node_modules/.bin/gulp watch
- compile assets, but also minify & optimize them:  
./node_modules/.bin/gulp --env production