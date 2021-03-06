# CSS Architecture setup

#Docs
- [CSS Architecture](src/scss/_docs/architecture.md)
- [CSS Development Procedure](src/scss/_docs/development-procedure.md)
- [CSS Deprecation Procedure](src/scss/_docs/deprecation-procedure.md)
- [CSS UI Library](src/scss/_docs/ui-library.md)
- [CSS Test](src/scss/_docs/test.md)
- [CSS Tools](src/scss/_docs/tools.md)

## Setup
`npm install`
`bower install`

## Run server:
* `gulp`
* `gulp --sm`

* http://localhost:8080/
* http://localhost:3001/compare/
* http://localhost:8080/styleguide/

## Run test
* `gulp css-reference`
* `gulp css-test`

## List features
- sass
- postcss
- stylelint (linting)
- doiuse (check support)
- symdiff (check unused classes)
- css style guide (use comment inside css)
- css deprecation tool (class deprecated)
- css backstopjs (visual regression tool)
- mdcss, styleguide generated by css comment

## TODO
- problem at scale sharable component
- test should be on the parent element
- [uCss](https://github.com/oyvindeh/ucss)