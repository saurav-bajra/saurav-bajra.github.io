# mysecondteacher.com.np

Wordpress theme and plugin files for [mysecondteacher.com.np](https://mysecondteacher.com.np/)


### Root Directory Structure
Contents of the repo should be inserted into the folowing path:

`WordpressRootDirectory/wp-content/[REPO HERE]`

The folder structure would look like this:

```
- WordpressRootDirectory
    - wp-content
        [REPO HERE]
        |- themes
        |    - mst-nepal-theme
        |        - ...
        |- plugins
        |    - plugin 1
        |    - plugin 2
        |    - plugin 3
```

### Development

The development environment uses [SASS](https://sass-lang.com/) CSS pre-processsor and [Nunjucks](https://mozilla.github.io/nunjucks/) for HTML templating. The automation is done by [gulp JS](https://gulpjs.com/). 

First goto the theme folder, then install the dependencies:

```
cd themes/mst-nepal-theme
npm install
```

After setting up, to start the development environment

```
gulp
```