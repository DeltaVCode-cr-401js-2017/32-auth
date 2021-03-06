![DV](https://www.deltavcodeschool.com/wp-content/uploads/DeltaV.png) 33: Photo Uploads
======

## Submission Instructions
* continue working on the fork you created from lab 32
* open a **new branch** for today's assignment
* upon completion, create a **new pull request** in github
* submit a link to your PR in canvas

## Learning Objectives
* students will be able to upload images (and other assets) on the client side
* students will be able to use the `FileReader` API to preview files

## Requirements
#### Configuration
#### backend
* Use a [Git submodule](https://git-scm.com/docs/git-submodule) to bring a backend into your project
  * `git submodule add https://github.com/DeltaVCode-cr-401js-2017/19-deployment-demo.git backend`

##### frontend
* `README.md`
* `.babelrc`
* `.gitignore`
* `package.json`
* `webpack.config.js`
* `src/**`
* `src/main.js`
* `src/style`
* `src/style/main.scss`
* `src/style/lib`
  * `_vars.scss`
* `src/style/base`
  * `_base.scss`
  * `_reset.scss`
* `src/style/layout`
  * `_header.scss`
  * `_footer.scss`
  * `_content.scss`

#### Feature Tasks
* create a `SettingsContainer`
  * give the user the ability to create and update their profile
* **optional:** create a `DashboardContainer`
  * give the user the ability to create, read, update and delete photos as part of their photo gallery

#### Test
* test your redux reducers
* test your `util` methods
