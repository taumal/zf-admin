# zf-admin
 ZF-Admin is a simple starter template for building admin or dashboard interfaces.

## Motivation
I wanted a Zurb Foundation based template with just a minimum amount of features and a proper build system.

![](assets/images/zf-admin-1.png)

## Features
* Plugins: Datepickers, graphs, notifications e.t.c
* Asset managememt using <a href="https://bower.io/">Bower</a>
* Build system using <a href="http://gulpjs.com/">Gulp</a></li>
* Templating system using <a href="https://github.com/codepb/jquery-template"> Jquery.loadTemplate</a></li>

<p>
These features can be configured and are not mandatory.
</p>
<p>
  You can view the dashboard examples by changing intto the "examples" folder and running a server application like <a href="https://www.npmjs.com/package/http-server">http-server</a> or <a href="http://tapiov.net/live-server/">live-server</a>.
</p>

## Usage
Clone this repository or
npm install zf-admin or
bower install zf-admin

## Using the zf-admin template with the dev/ build system
1. Run "npm install".
2. Run "bower install".
3. Modify the gulpfile.js as needed.
4. Modify the source SASS and JS files as needed.
5. Run Gulp to build assets.

## Using the admin template with default dependencies.
<p>
Check out the example folder to see how to use the template as is. You can still
customize as you see fit. It just would not be as flexible.
</p>

## Provided plugins
1. Charting. <a href="http://www.chartjs.org/docs/">chart.js</a>
2. Animated counters. <a href="http://inorganik.github.io/countUp.js/">countup.js</a>
3. Date/ Time picker. <a href="https://github.com/chmln/flatpickr">flatpickr</a>
4. Notifications. <a href="https://github.com/needim/noty">Noty</a>
5. Simple templating. <a href="https://github.com/codepb/jquery-template">jQuery.loadTemplate</a>
6. Lightbox. <a href="https://github.com/duncanmcdougall/Responsive-Lightbox">Responsive-Lightbox</a>
7. Alerts and modal dialogs. <a href="https://github.com/limonte/sweetalert2">sweetalert2</a>
8. Data tables. <a href="https://datatables.net/">datatables</a>

## Available build tasks
<p>
Run "gulp help" to see a list of all the available build tasks:

#### Main Tasks
------------------------------
    default
    help

#### Sub Tasks
------------------------------
    build-all
    build-js
    build-sass
    copy-fonts
    lint-js
    prepare-default-images
    prepare-example-assets
