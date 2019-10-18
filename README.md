# ljr
<!DOCTYPE html>
<html>
  <head>
    <meta charset="utf-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <title>Landy: Bootstrap 4 landing page template</title>
    <meta name="description" content="">
    <meta name="viewport" content="width=device-width, initial-scale=1">
    <meta name="robots" content="all,follow">
    <!-- Bootstrap CSS-->
    <style>
      @charset "UTF-8";

@font-face {
  font-family: "landy";
  src:url("../fonts/landy.eot");
  src:url("../fonts/landy.eot?#iefix") format("embedded-opentype"),
    url("../fonts/landy.woff") format("woff"),
    url("../fonts/landy.ttf") format("truetype"),
    url("../fonts/landy.svg#landy") format("svg");
  font-weight: normal;
  font-style: normal;

}

[data-icon]:before {
  font-family: "landy" !important;
  content: attr(data-icon);
  font-style: normal !important;
  font-weight: normal !important;
  font-variant: normal !important;
  text-transform: none !important;
  speak: none;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

[class^="icon-"]:before,
[class*=" icon-"]:before {
  font-family: "landy" !important;
  font-style: normal !important;
  font-weight: normal !important;
  font-variant: normal !important;
  text-transform: none !important;
  speak: none;
  line-height: 1;
  -webkit-font-smoothing: antialiased;
  -moz-osx-font-smoothing: grayscale;
}

.icon-abc:before {
  content: "\61";
}
.icon-add-user:before {
  content: "\62";
}
.icon-admin:before {
  content: "\63";
}
.icon-alarm:before {
  content: "\64";
}
.icon-analytics:before {
  content: "\65";
}
.icon-analytics-1:before {
  content: "\66";
}
.icon-arrow:before {
  content: "\67";
}
.icon-backup:before {
  content: "\68";
}
.icon-bank:before {
  content: "\69";
}
.icon-bar-chart:before {
  content: "\6a";
}
.icon-bar-chart-1:before {
  content: "\6b";
}
.icon-bar-chart-2:before {
  content: "\6c";
}
.icon-bar-chart-3:before {
  content: "\6d";
}
.icon-bar-chart-4:before {
  content: "\6e";
}
.icon-bar-chart-5:before {
  content: "\6f";
}
.icon-book:before {
  content: "\70";
}
.icon-boss:before {
  content: "\71";
}
.icon-box:before {
  content: "\72";
}
.icon-boy:before {
  content: "\73";
}
.icon-briefcase:before {
  content: "\74";
}
.icon-browser:before {
  content: "\75";
}
.icon-browser-1:before {
  content: "\76";
}
.icon-browser-2:before {
  content: "\77";
}
.icon-browser-3:before {
  content: "\78";
}
.icon-bug:before {
  content: "\79";
}
.icon-bug-1:before {
  content: "\7a";
}
.icon-building:before {
  content: "\41";
}
.icon-bullhorn:before {
  content: "\42";
}
.icon-businessman:before {
  content: "\43";
}
.icon-businessman-1:before {
  content: "\44";
}
.icon-captain:before {
  content: "\45";
}
.icon-career:before {
  content: "\46";
}
.icon-cash-point:before {
  content: "\47";
}
.icon-chart:before {
  content: "\48";
}
.icon-chat:before {
  content: "\49";
}
.icon-chat-1:before {
  content: "\4a";
}
.icon-clipboard:before {
  content: "\4b";
}
.icon-cloud:before {
  content: "\4c";
}
.icon-cloud-computing:before {
  content: "\4d";
}
.icon-cloud-computing-1:before {
  content: "\4e";
}
.icon-cloud-computing-2:before {
  content: "\4f";
}
.icon-cloud-computing-3:before {
  content: "\50";
}
.icon-cloud-computing-4:before {
  content: "\51";
}
.icon-cloud-computing-5:before {
  content: "\52";
}
.icon-cloud-computing-6:before {
  content: "\53";
}
.icon-coin:before {
  content: "\54";
}
.icon-computer:before {
  content: "\55";
}
.icon-computer-1:before {
  content: "\56";
}
.icon-cooperation:before {
  content: "\57";
}
.icon-cpu:before {
  content: "\58";
}
.icon-credit:before {
  content: "\59";
}
.icon-crown:before {
  content: "\5a";
}
.icon-curriculum:before {
  content: "\30";
}
.icon-customer-service:before {
  content: "\31";
}
.icon-data:before {
  content: "\32";
}
.icon-database:before {
  content: "\33";
}
.icon-decrease:before {
  content: "\34";
}
.icon-desk:before {
  content: "\35";
}
.icon-desk-chair:before {
  content: "\36";
}
.icon-diagram:before {
  content: "\37";
}
.icon-diagram-1:before {
  content: "\38";
}
.icon-diagram-2:before {
  content: "\39";
}
.icon-dialog:before {
  content: "\21";
}
.icon-dialog-1:before {
  content: "\22";
}
.icon-diploma:before {
  content: "\23";
}
.icon-dollar:before {
  content: "\24";
}
.icon-dollar-1:before {
  content: "\25";
}
.icon-dollar-2:before {
  content: "\26";
}
.icon-dossier:before {
  content: "\27";
}
.icon-dossier-1:before {
  content: "\28";
}
.icon-email:before {
  content: "\29";
}
.icon-employee:before {
  content: "\2a";
}
.icon-employee-1:before {
  content: "\2b";
}
.icon-employee-2:before {
  content: "\2c";
}
.icon-employee-3:before {
  content: "\2d";
}
.icon-employee-4:before {
  content: "\2e";
}
.icon-employee-5:before {
  content: "\2f";
}
.icon-employee-6:before {
  content: "\3a";
}
.icon-employee-7:before {
  content: "\3b";
}
.icon-employees:before {
  content: "\3c";
}
.icon-employees-1:before {
  content: "\3d";
}
.icon-employees-2:before {
  content: "\3e";
}
.icon-error-404:before {
  content: "\3f";
}
.icon-eye:before {
  content: "\40";
}
.icon-firewall:before {
  content: "\5b";
}
.icon-flag:before {
  content: "\5d";
}
.icon-flags:before {
  content: "\5e";
}
.icon-folder:before {
  content: "\5f";
}
.icon-folder-1:before {
  content: "\60";
}
.icon-folder-2:before {
  content: "\7b";
}
.icon-folders:before {
  content: "\7c";
}
.icon-gauge:before {
  content: "\7d";
}
.icon-gears:before {
  content: "\7e";
}
.icon-goal:before {
  content: "\5c";
}
.icon-group:before {
  content: "\e000";
}
.icon-growth:before {
  content: "\e001";
}
.icon-growth-1:before {
  content: "\e002";
}
.icon-hierarchical-structure:before {
  content: "\e003";
}
.icon-hierarchical-structure-1:before {
  content: "\e004";
}
.icon-house:before {
  content: "\e005";
}
.icon-human-resources:before {
  content: "\e006";
}
.icon-human-resources-1:before {
  content: "\e007";
}
.icon-id-card:before {
  content: "\e008";
}
.icon-idea:before {
  content: "\e009";
}
.icon-idea-2:before {
  content: "\e00a";
}
.icon-improve:before {
  content: "\e00b";
}
.icon-increase:before {
  content: "\e00c";
}
.icon-index:before {
  content: "\e00d";
}
.icon-infographic:before {
  content: "\e00e";
}
.icon-infographic-1:before {
  content: "\e00f";
}
.icon-internet:before {
  content: "\e010";
}
.icon-investment:before {
  content: "\e011";
}
.icon-investment-1:before {
  content: "\e012";
}
.icon-investment-2:before {
  content: "\e013";
}
.icon-investment-3:before {
  content: "\e014";
}
.icon-job:before {
  content: "\e015";
}
.icon-job-search:before {
  content: "\e016";
}
.icon-keyword:before {
  content: "\e017";
}
.icon-laptop:before {
  content: "\e018";
}
.icon-leader:before {
  content: "\e019";
}
.icon-leader-1:before {
  content: "\e01a";
}
.icon-leader-2:before {
  content: "\e01b";
}
.icon-leader-3:before {
  content: "\e01c";
}
.icon-leader-4:before {
  content: "\e01d";
}
.icon-leader-5:before {
  content: "\e01e";
}
.icon-leader-6:before {
  content: "\e01f";
}
.icon-like:before {
  content: "\e020";
}
.icon-line-graph:before {
  content: "\e021";
}
.icon-link:before {
  content: "\e022";
}
.icon-list:before {
  content: "\e023";
}
.icon-loupe:before {
  content: "\e024";
}
.icon-loupe-1:before {
  content: "\e025";
}
.icon-magnet:before {
  content: "\e026";
}
.icon-mail:before {
  content: "\e027";
}
.icon-man:before {
  content: "\e028";
}
.icon-man-1:before {
  content: "\e029";
}
.icon-man-2:before {
  content: "\e02a";
}
.icon-management:before {
  content: "\e02b";
}
.icon-management-1:before {
  content: "\e02c";
}
.icon-map:before {
  content: "\e02d";
}
.icon-matrix:before {
  content: "\e02e";
}
.icon-medal:before {
  content: "\e02f";
}
.icon-message:before {
  content: "\e030";
}
.icon-monitor:before {
  content: "\e031";
}
.icon-monitor-1:before {
  content: "\e032";
}
.icon-monitoring:before {
  content: "\e033";
}
.icon-network:before {
  content: "\e034";
}
.icon-networking:before {
  content: "\e035";
}
.icon-notification:before {
  content: "\e036";
}
.icon-padlock:before {
  content: "\e037";
}
.icon-pendrive:before {
  content: "\e038";
}
.icon-percentage:before {
  content: "\e039";
}
.icon-person:before {
  content: "\e03a";
}
.icon-petals:before {
  content: "\e03b";
}
.icon-pie-chart:before {
  content: "\e03c";
}
.icon-pie-chart-1:before {
  content: "\e03d";
}
.icon-pie-chart-2:before {
  content: "\e03e";
}
.icon-piggybank:before {
  content: "\e03f";
}
.icon-piggybank-1:before {
  content: "\e040";
}
.icon-placeholder:before {
  content: "\e041";
}
.icon-plant:before {
  content: "\e042";
}
.icon-plant-1:before {
  content: "\e043";
}
.icon-pointer:before {
  content: "\e044";
}
.icon-premium:before {
  content: "\e045";
}
.icon-presentation:before {
  content: "\e046";
}
.icon-presentation-1:before {
  content: "\e047";
}
.icon-presentation-2:before {
  content: "\e048";
}
.icon-presentation-3:before {
  content: "\e049";
}
.icon-profits:before {
  content: "\e04a";
}
.icon-promotion:before {
  content: "\e04b";
}
.icon-puzzle:before {
  content: "\e04c";
}
.icon-pyramid-chart:before {
  content: "\e04d";
}
.icon-quality:before {
  content: "\e04e";
}
.icon-question:before {
  content: "\e04f";
}
.icon-radial:before {
  content: "\e050";
}
.icon-rating:before {
  content: "\e051";
}
.icon-ratio:before {
  content: "\e052";
}
.icon-relations:before {
  content: "\e053";
}
.icon-responsive:before {
  content: "\e054";
}
.icon-reunion:before {
  content: "\e055";
}
.icon-reunion-1:before {
  content: "\e056";
}
.icon-review:before {
  content: "\e057";
}
.icon-saving:before {
  content: "\e058";
}
.icon-saving-1:before {
  content: "\e059";
}
.icon-scales:before {
  content: "\e05a";
}
.icon-schedule:before {
  content: "\e05b";
}
.icon-search:before {
  content: "\e05c";
}
.icon-server:before {
  content: "\e05d";
}
.icon-server-1:before {
  content: "\e05e";
}
.icon-server-2:before {
  content: "\e05f";
}
.icon-server-3:before {
  content: "\e060";
}
.icon-server-4:before {
  content: "\e061";
}
.icon-settings:before {
  content: "\e062";
}
.icon-share:before {
  content: "\e063";
}
.icon-shield:before {
  content: "\e064";
}
.icon-shopping-cart:before {
  content: "\e065";
}
.icon-smartphone:before {
  content: "\e066";
}
.icon-speech:before {
  content: "\e067";
}
.icon-speech-bubble:before {
  content: "\e068";
}
.icon-speedometer:before {
  content: "\e069";
}
.icon-star:before {
  content: "\e06a";
}
.icon-startup:before {
  content: "\e06b";
}
.icon-stopwatch:before {
  content: "\e06c";
}
.icon-support:before {
  content: "\e06d";
}
.icon-tag:before {
  content: "\e06e";
}
.icon-target:before {
  content: "\e06f";
}
.icon-target-1:before {
  content: "\e070";
}
.icon-tasks:before {
  content: "\e071";
}
.icon-tasks-1:before {
  content: "\e072";
}
.icon-team:before {
  content: "\e073";
}
.icon-team-1:before {
  content: "\e074";
}
.icon-teamwork:before {
  content: "\e075";
}
.icon-teamwork-1:before {
  content: "\e076";
}
.icon-teamwork-2:before {
  content: "\e077";
}
.icon-teamwork-3:before {
  content: "\e078";
}
.icon-telemarketer:before {
  content: "\e079";
}
.icon-telemarketer-1:before {
  content: "\e07a";
}
.icon-timeline:before {
  content: "\e07b";
}
.icon-timeline-1:before {
  content: "\e07c";
}
.icon-traffic:before {
  content: "\e07d";
}
.icon-trophy:before {
  content: "\e07e";
}
.icon-upload-file:before {
  content: "\e07f";
}
.icon-video-call:before {
  content: "\e080";
}
.icon-video-call-1:before {
  content: "\e081";
}
.icon-video-call-2:before {
  content: "\e082";
}
.icon-video-call-3:before {
  content: "\e083";
}
.icon-vision:before {
  content: "\e084";
}
.icon-visualization:before {
  content: "\e085";
}
.icon-woman:before {
  content: "\e086";
}
.icon-woman-1:before {
  content: "\e087";
}
.icon-woman-2:before {
  content: "\e088";
}
.icon-woman-3:before {
  content: "\e089";
}
.icon-woman-4:before {
  content: "\e08a";
}
.icon-woman-5:before {
  content: "\e08b";
}
.icon-worldwide:before {
  content: "\e08c";
}
.icon-worldwide-1:before {
  content: "\e08d";
}
.icon-yen:before {
  content: "\e08e";
}

/*
* ==========================================================
*     GENERAL
* ==========================================================
*/
body {
  padding-top: 80px;
  position: relative;
  overflow-x: hidden;
}

section {
  padding: 150px 0;
  overflow: hidden;
}

a {
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  display: inline-block;
}

p {
  line-height: 1.7rem;
}

button {
  cursor: pointer;
}

i,
span,
strong {
  display: inline-block;
}

.bg-gray, section.browser .nav-tabs a.active {
  background: #f5f5f5;
}

.no-padding {
  padding: 0 !important;
}

.no-padding-top {
  padding-top: 0 !important;
}

.no-padding-bottom {
  padding-bottom: 0 !important;
}

.no-margin {
  margin: 0 !important;
}

.no-margin-top {
  margin-top: 0 !important;
}

.no-margin-bottom {
  margin-bottom: 0 !important;
}

.hero-text {
  font-size: 1.1rem;
  font-weight: 400;
  color: #777;
  line-height: 1.5rem;
}

.btn {
  font-size: 0.9em !important;
}

.btn-primary:focus {
  color: #fff;
}

.btn-shadow {
  -webkit-box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
  box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
}

.btn-gradient, section.browser .nav-tabs span.number {
  background-color: #5989e5;
  background-image: -webkit-gradient(linear, left top, right top, from(#5989e5), to(#37cfdc));
  background-image: linear-gradient(to right, #5989e5, #37cfdc);
  border: none !important;
  text-transform: uppercase;
  color: #fff;
  overflow: hidden;
  position: relative;
  z-index: 1;
  -webkit-transition: all 0.3s !important;
  transition: all 0.3s !important;
}

.btn.btn-gradient:hover, section.browser .nav-tabs span.btn.number:hover {
  opacity: 0.85;
}

.has-shadow {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.owl-theme .owl-nav {
  margin-top: 0;
}

.owl-theme .owl-nav [class*='owl-'] {
  background: none;
  color: #222;
  font-size: 2rem;
  margin: 0 20px;
}

.owl-theme .owl-nav [class*='owl-'].disabled {
  color: #aaa;
}

.owl-theme .owl-nav [class*='owl-']:hover {
  background: none;
  color: #333;
}

section header {
  margin-bottom: 70px;
}

.scrollUp {
  -webkit-transform: translateY(-105%);
  transform: translateY(-105%);
}

.breadcrumb {
  background: none;
  padding: 0;
  margin-bottom: 20px;
}

.breadcrumb a {
  color: #222;
  text-decoration: none !important;
}

.breadcrumb li {
  color: #aaa;
}

.block {
  margin-bottom: 50px;
}

/* Browser mockup code
 * Contribute: https://gist.github.com/jarthod/8719db9fef8deb937f4f
 * Live example: https://updown.io
 */
.browser-mockup {
  border-top: 50px solid #f7f7f7;
  position: relative;
  border-radius: 3px 3px 0 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.browser-mockup:before {
  display: block;
  position: absolute;
  content: '';
  top: -29px;
  left: 30px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: #f44;
  -webkit-box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
  box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
}

.browser-mockup.with-tab:after {
  display: block;
  position: absolute;
  content: '';
  top: -50px;
  left: 115px;
  width: 20%;
  height: 0rem;
  border-bottom: 50px solid white;
  border-left: 1.5em solid transparent;
  border-right: 1.5em solid transparent;
}

.browser-mockup.with-url:after {
  display: block;
  position: absolute;
  content: '';
  top: -1.6rem;
  left: 5.5rem;
  width: calc(100% - 6em);
  height: 1.2rem;
  border-radius: 2px;
  background-color: white;
}

.browser-mockup > * {
  display: block;
}

.blockquote {
  line-height: 1.7rem;
  color: #656565;
  padding: 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.blockquote p::first-letter {
  font-size: 2.5rem;
  color: #5989e5;
  font-weight: 800;
}

.modal {
  background: rgba(0, 0, 0, 0.8);
}

.modal button.close {
  width: 40px;
  height: 40px;
  line-height: 40px;
  color: #fff;
  text-align: center;
  background-color: #5989e5;
  background-image: -webkit-gradient(linear, left top, right top, from(#5989e5), to(#37cfdc));
  background-image: linear-gradient(to right, #5989e5, #37cfdc);
  position: absolute;
  top: 0;
  right: 0;
  opacity: 1;
}

.modal-content {
  border-radius: 0;
}

.modal-header,
.modal-body {
  padding: 20px 30px;
  border: none;
}

#signupform .form-group {
  margin-bottom: 20px;
}

#signupform label {
  display: block;
  padding-left: 10px;
  color: #656565;
  font-family: "Open Sans", sans-serif;
}

#signupform input {
  width: 100%;
  display: block;
  padding: 10px 20px;
  border-radius: 50px;
  border: 1px solid #eee;
  outline: none;
}

#signupform input:focus {
  border-color: #5989e5;
}

#signupform input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

/* General Media Query ---------------------------------- */
@media (max-width: 991px) {
  section {
    padding: 100px 0;
  }
}

/*
* ==========================================================
*     NAVBAR
* ==========================================================
*/
nav.navbar {
  padding-top: 15px;
  padding-bottom: 15px;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  background: #fff;
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

nav.navbar .navbar-brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
}

nav.navbar a.nav-link {
  color: #333;
  font-size: 1.1rem;
}

nav.navbar a.nav-link:hover, nav.navbar a.nav-link.active {
  color: #5989e5;
}

nav.navbar .navbar-btn {
  margin-left: 15px;
}

nav.navbar .navbar-toggler {
  outline: none;
}

nav.navbar .navbar-toggler span {
  width: 25px;
  margin: 5px;
  display: block;
  height: 2px;
  background: #333;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
}

nav.navbar .navbar-toggler.active span:first-of-type {
  -webkit-transform: rotate(45deg) translate(10px);
  transform: rotate(45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:last-of-type {
  -webkit-transform: rotate(-45deg) translate(10px);
  transform: rotate(-45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:nth-of-type(2) {
  opacity: 0;
}

/* Navbar Mediaquery ----------------------------------- */
@media (max-width: 1199px) {
  nav.navbar .navbar-btn {
    margin-left: 0;
  }
}

@media (min-width: 992px) {
  nav.navbar {
    padding-left: 3rem;
    padding-right: 3rem;
  }
}

/*
* ==========================================================
*     HERO SECTION
* ==========================================================
*/
section.hero p {
  margin: 20px 0;
}

section.hero .CTA {
  margin-top: 40px;
}

section.hero .CTA a {
  margin-right: 10px;
  margin-bottom: 10px;
}

/*
* ==========================================================
*     BROWSER SECTION
* ==========================================================
*/
section.browser .nav-tabs {
  margin-top: 80px;
  border: none;
}

section.browser .nav-tabs span.number {
  width: 50px;
  height: 50px;
  line-height: 50px;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  display: block;
  position: absolute;
  left: calc(50% - 25px);
  top: -25px;
  font-size: 1.4rem;
  font-weight: 700;
}

section.browser .nav-tabs a {
  border: none;
  background: none;
  border-right: 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  padding: 50px 50px 40px;
  text-align: center;
  color: #333;
}

section.browser .nav-tabs a.active {
  -webkit-transform: translateY(-20px);
  transform: translateY(-20px);
}

/* Browser Section Mediaquery --------------------------- */
@media (max-width: 767px) {
  section.browser .nav-tabs a {
    margin-bottom: 50px;
  }
  section.browser .nav-tabs a.active {
    -webkit-transform: none;
    transform: none;
  }
  section.browser .nav-tabs .row div:last-of-type a {
    margin-bottom: 0;
  }
}

/*
* ==========================================================
*     ABOUT US
* ==========================================================
*/
section.about-us p {
  margin: 30px 0;
}

/*
* ==========================================================
*     FEATURES SECTION
* ==========================================================
*/
section.features .row {
  margin-bottom: 40px;
}

section.features .row:last-of-time {
  margin-bottom: 0;
}

section.features .icon {
  width: 50px;
  height: 50px;
  margin-bottom: 30px;
}

section.features .text p {
  line-height: 1.8rem;
  font-size: 0.95rem;
  color: #656565;
  margin: 20px 0 25px;
}

/* Features Section Mediaquery -------------------------- */
@media (max-width: 1199px) {
  section.features .text {
    margin-bottom: 50px;
  }
}

/*
* ==========================================================
*     EXTRA SECTION
* ==========================================================
*/
section.extra-features {
  color: #fff;
}

section.extra-features h2,
section.extra-features h3 {
  color: inherit;
}

section.extra-features .icon {
  font-size: 2.7rem;
  margin-bottom: 20px;
}

section.extra-features .item {
  padding: 50px 30px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  cursor: default;
}

section.extra-features .item:hover {
  background: #4c80e3;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

section.extra-features .item p {
  font-weight: 300;
  margin: 20px 0;
}

/*
* ==========================================================
*     TESTIMONIALS SECTION
* ==========================================================
*/
section.testimonials .owl-carousel .owl-stage-outer {
  padding: 70px 0 50px;
}

section.testimonials .item-holder {
  padding-right: 40px;
  padding-left: 40px;
}

section.testimonials .quote {
  width: 40px;
  height: 40px;
  margin-bottom: 20px;
}

section.testimonials .item {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 0 30px;
  margin-right: 0;
  padding: 70px 50px;
  padding-left: 70px;
}

section.testimonials .item p {
  line-height: 1.8rem;
  font-size: 0.9rem;
  line-height: 1.7rem;
  color: #656565;
}

section.testimonials .avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  overflow: hidden;
  position: absolute;
  top: 50%;
  left: 0;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

/* Testimonials Media Query ------------------------- */
@media (max-width: 1199px) {
  section.testimonials .item {
    -webkit-box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    padding: 60px 40px 40px;
  }
  section.testimonials .item .avatar {
    position: absolute;
    top: 0;
    left: 50%;
  }
}

/*
* ==========================================================
*     NEWSLETTER SECTION
* ==========================================================
*/
section.newsletter .form-holder {
  padding: 70px 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  margin-top: 70px;
}

section.newsletter .form-group {
  position: relative;
  margin-bottom: 0;
}

section.newsletter .form-group input {
  width: 100%;
  height: 68px;
  line-height: 68px;
  border: 1px solid #ddd;
  border-radius: 50px;
  background: none;
  outline: none;
  padding: 0 30px;
  font-family: "Open Sans", sans-serif;
}

section.newsletter .form-group input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group .submit {
  height: 54px;
  line-height: 54px;
  padding-top: 0;
  padding-bottom: 0;
  position: absolute;
  top: 7px;
  right: 7px;
}

/* Newsletter Section Mediaquery -------------------------- */
@media (max-width: 991px) {
  section.newsletter .form-group input {
    width: 100%;
  }
  section.newsletter .form-group .submit {
    width: 100%;
    position: static;
    margin-top: 15px;
  }
}

/*
* ==========================================================
*     FOOTER
* ==========================================================
*/
footer.main-footer {
  padding: 150px 0 0;
  overflow-x: hidden;
}

footer.main-footer a {
  color: inherit;
  text-decoration: none;
}

footer.main-footer .brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
  margin-bottom: 20px;
}

footer.main-footer ul.contact-info {
  color: #444;
}

footer.main-footer ul.contact-info a {
  margin-bottom: 5px;
}

footer.main-footer ul.contact-info a:hover {
  color: #5989e5;
}

footer.main-footer h5 {
  margin-bottom: 30px;
}

footer.main-footer ul.links {
  color: #888;
}

footer.main-footer ul.links a {
  margin-bottom: 8px;
}

footer.main-footer ul.links a:hover {
  color: #5989e5;
}

footer.main-footer ul.social-icons {
  margin-top: 15px;
  margin-bottom: 50px;
}

footer.main-footer ul.social-icons a {
  width: 26px;
  height: 26px;
  line-height: 26px;
  background: #222;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  font-size: 0.8rem;
}

footer.main-footer ul.social-icons a:hover {
  background: #5989e5;
}

footer.main-footer .copyrights {
  margin-top: 150px;
}

footer.main-footer .copyrights .container {
  padding: 30px 0;
  border-top: 1px solid #ddd;
}

footer.main-footer .copyrights p {
  margin-bottom: 0;
}

footer.main-footer .copyrights a:hover {
  color: #5989e5;
}

/* Footer Mediaquery -------------------------- */
@media (max-width: 991px) {
  footer.main-footer {
    padding: 100px 0 0;
  }
  footer.main-footer .copyrights {
    margin-top: 100px;
  }
  footer.main-footer .copyrights div[class*="col-"] {
    text-align: center !important;
  }
}

/* ===================================================================
    SCROLL TO TOP BUTTON
===================================================================  */
#scrollTop {
  width: 80px;
  height: 40px;
  position: fixed;
  right: -90px;
  bottom: 50%;
  background-color: #5989e5;
  background-image: -webkit-gradient(linear, left top, right top, from(#5989e5), to(#37cfdc));
  background-image: linear-gradient(to right, #5989e5, #37cfdc);
  color: #fff;
  text-align: center;
  line-height: 40px;
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
  -webkit-box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  font-size: 0.7rem;
  cursor: pointer;
  z-index: 9998;
  padding-right: 10px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

#scrollTop.active {
  right: -50px;
}

#scrollTop i {
  font-size: 1.1rem;
  margin-right: 10px;
}

#scrollTop:hover {
  right: 0;
}

/* Scroll Top Media Query ------------------------- */
@media (max-width: 1199px) {
  #scrollTop {
    display: none !important;
  }
}

/*

=====================
STYLE SWITCHER FOR DEMO
=====================

*/
#style-switch-button {
  position: fixed;
  top: 120px;
  left: 0px;
  border-radius: 0;
  z-index: 2;
}

#style-switch {
  width: 300px;
  padding: 20px;
  position: fixed;
  top: 160px;
  left: 0;
  background: #fff;
  border: solid 1px #ced4da;
  z-index: 2000;
}

#style-switch h4 {
  color: #495057;
}

/* =========================================
   THEMING OF BOOTSTRAP COMPONENTS
   ========================================= */
/*
 * 1. NAVBAR
 */
.navbar {
  padding: 0.5rem 1rem;
}

.navbar-brand {
  display: inline-block;
  padding-top: 0.3125rem;
  padding-bottom: 0.3125rem;
  margin-right: 1rem;
  font-size: 1.25rem;
}

.navbar-toggler {
  padding: 0.25rem 0.75rem;
  font-size: 1.25rem;
  line-height: 1;
  border: 1px solid transparent;
  border-radius: 50px;
}

.navbar-light .navbar-brand {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-brand:focus, .navbar-light .navbar-brand:hover {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-nav .nav-link:focus, .navbar-light .navbar-nav .nav-link:hover {
  color: rgba(0, 0, 0, 0.7);
}

.navbar-light .navbar-nav .nav-link.disabled {
  color: rgba(0, 0, 0, 0.3);
}

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0.5);
  border-color: rgba(0, 0, 0, 0.1);
}

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-light .navbar-text {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-dark .navbar-brand {
  color: white;
}

.navbar-dark .navbar-brand:focus, .navbar-dark .navbar-brand:hover {
  color: white;
}

.navbar-dark .navbar-nav .nav-link {
  color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
  color: rgba(255, 255, 255, 0.75);
}

.navbar-dark .navbar-nav .nav-link.disabled {
  color: rgba(255, 255, 255, 0.25);
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: white;
}

.navbar-dark .navbar-toggler {
  color: rgba(255, 255, 255, 0.5);
  border-color: rgba(255, 255, 255, 0.1);
}

.navbar-dark .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-dark .navbar-text {
  color: rgba(255, 255, 255, 0.5);
}

/*
 * 2. BUTTONS
 */
.btn {
  font-weight: 400;
  border: 1px solid transparent;
  padding: 0.6rem 3rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 50px;
  -webkit-transition: all 0.15s ease-in-out;
  transition: all 0.15s ease-in-out;
}

.btn:focus, .btn.focus {
  outline: 0;
  -webkit-box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.25);
  box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.25);
}

.btn:active, .btn.active {
  background-image: none;
}

.btn-primary {
  color: #fff;
  background-color: #5989e5;
  border-color: #5989e5;
}

.btn-primary:hover {
  color: #fff;
  background-color: #3871e0;
  border-color: #2d6ade;
}

.btn-primary:focus, .btn-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.5);
  box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.5);
}

.btn-primary.disabled, .btn-primary:disabled {
  background-color: #5989e5;
  border-color: #5989e5;
}

.btn-primary:active, .btn-primary.active,
.show > .btn-primary.dropdown-toggle {
  background-color: #3871e0;
  background-image: none;
  border-color: #2d6ade;
}

.btn-secondary {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:hover {
  color: #fff;
  background-color: #727b84;
  border-color: #6c757d;
}

.btn-secondary:focus, .btn-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-secondary.disabled, .btn-secondary:disabled {
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:active, .btn-secondary.active,
.show > .btn-secondary.dropdown-toggle {
  background-color: #727b84;
  background-image: none;
  border-color: #6c757d;
}

.btn-success {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:hover {
  color: #fff;
  background-color: #218838;
  border-color: #1e7e34;
}

.btn-success:focus, .btn-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-success.disabled, .btn-success:disabled {
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:active, .btn-success.active,
.show > .btn-success.dropdown-toggle {
  background-color: #218838;
  background-image: none;
  border-color: #1e7e34;
}

.btn-info {
  color: #111;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:hover {
  color: #111;
  background-color: #23bcc9;
  border-color: #21b2bf;
}

.btn-info:focus, .btn-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-info.disabled, .btn-info:disabled {
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:active, .btn-info.active,
.show > .btn-info.dropdown-toggle {
  background-color: #23bcc9;
  background-image: none;
  border-color: #21b2bf;
}

.btn-warning {
  color: #111;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:hover {
  color: #111;
  background-color: #e0a800;
  border-color: #d39e00;
}

.btn-warning:focus, .btn-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-warning.disabled, .btn-warning:disabled {
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:active, .btn-warning.active,
.show > .btn-warning.dropdown-toggle {
  background-color: #e0a800;
  background-image: none;
  border-color: #d39e00;
}

.btn-danger {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:hover {
  color: #fff;
  background-color: #c82333;
  border-color: #bd2130;
}

.btn-danger:focus, .btn-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-danger.disabled, .btn-danger:disabled {
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:active, .btn-danger.active,
.show > .btn-danger.dropdown-toggle {
  background-color: #c82333;
  background-image: none;
  border-color: #bd2130;
}

.btn-light {
  color: #111;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:hover {
  color: #111;
  background-color: #e2e6ea;
  border-color: #dae0e5;
}

.btn-light:focus, .btn-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-light.disabled, .btn-light:disabled {
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:active, .btn-light.active,
.show > .btn-light.dropdown-toggle {
  background-color: #e2e6ea;
  background-image: none;
  border-color: #dae0e5;
}

.btn-dark {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:hover {
  color: #fff;
  background-color: #23272b;
  border-color: #1d2124;
}

.btn-dark:focus, .btn-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-dark.disabled, .btn-dark:disabled {
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:active, .btn-dark.active,
.show > .btn-dark.dropdown-toggle {
  background-color: #23272b;
  background-image: none;
  border-color: #1d2124;
}

.btn-outline-primary {
  color: #5989e5;
  background-color: transparent;
  background-image: none;
  border-color: #5989e5;
}

.btn-outline-primary:hover {
  color: #fff;
  background-color: #5989e5;
  border-color: #5989e5;
}

.btn-outline-primary:focus, .btn-outline-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.5);
  box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.5);
}

.btn-outline-primary.disabled, .btn-outline-primary:disabled {
  color: #5989e5;
  background-color: transparent;
}

.btn-outline-primary:active, .btn-outline-primary.active,
.show > .btn-outline-primary.dropdown-toggle {
  color: #fff;
  background-color: #5989e5;
  border-color: #5989e5;
}

.btn-outline-secondary {
  color: #868e96;
  background-color: transparent;
  background-image: none;
  border-color: #868e96;
}

.btn-outline-secondary:hover {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-secondary:focus, .btn-outline-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
  color: #868e96;
  background-color: transparent;
}

.btn-outline-secondary:active, .btn-outline-secondary.active,
.show > .btn-outline-secondary.dropdown-toggle {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-success {
  color: #28a745;
  background-color: transparent;
  background-image: none;
  border-color: #28a745;
}

.btn-outline-success:hover {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-success:focus, .btn-outline-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-outline-success.disabled, .btn-outline-success:disabled {
  color: #28a745;
  background-color: transparent;
}

.btn-outline-success:active, .btn-outline-success.active,
.show > .btn-outline-success.dropdown-toggle {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-info {
  color: #37cfdc;
  background-color: transparent;
  background-image: none;
  border-color: #37cfdc;
}

.btn-outline-info:hover {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-info:focus, .btn-outline-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-outline-info.disabled, .btn-outline-info:disabled {
  color: #37cfdc;
  background-color: transparent;
}

.btn-outline-info:active, .btn-outline-info.active,
.show > .btn-outline-info.dropdown-toggle {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-warning {
  color: #ffc107;
  background-color: transparent;
  background-image: none;
  border-color: #ffc107;
}

.btn-outline-warning:hover {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-warning:focus, .btn-outline-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-outline-warning.disabled, .btn-outline-warning:disabled {
  color: #ffc107;
  background-color: transparent;
}

.btn-outline-warning:active, .btn-outline-warning.active,
.show > .btn-outline-warning.dropdown-toggle {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-danger {
  color: #dc3545;
  background-color: transparent;
  background-image: none;
  border-color: #dc3545;
}

.btn-outline-danger:hover {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-danger:focus, .btn-outline-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-outline-danger.disabled, .btn-outline-danger:disabled {
  color: #dc3545;
  background-color: transparent;
}

.btn-outline-danger:active, .btn-outline-danger.active,
.show > .btn-outline-danger.dropdown-toggle {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-light {
  color: #f8f9fa;
  background-color: transparent;
  background-image: none;
  border-color: #f8f9fa;
}

.btn-outline-light:hover {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-light:focus, .btn-outline-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-outline-light.disabled, .btn-outline-light:disabled {
  color: #f8f9fa;
  background-color: transparent;
}

.btn-outline-light:active, .btn-outline-light.active,
.show > .btn-outline-light.dropdown-toggle {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-dark {
  color: #343a40;
  background-color: transparent;
  background-image: none;
  border-color: #343a40;
}

.btn-outline-dark:hover {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-outline-dark:focus, .btn-outline-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-outline-dark.disabled, .btn-outline-dark:disabled {
  color: #343a40;
  background-color: transparent;
}

.btn-outline-dark:active, .btn-outline-dark.active,
.show > .btn-outline-dark.dropdown-toggle {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-lg {
  padding: 0.8rem 3.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 50px;
}

.btn-sm {
  padding: 0.4rem 1.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 50px;
}

/*
 * 3. TYPE
 */
body {
  font-family: "Open Sans", sans-serif;
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
}

a {
  color: #5989e5;
  text-decoration: none;
}

a:focus, a:hover {
  color: #215dd1;
  text-decoration: underline;
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  margin-bottom: 0.5rem;
  font-family: inherit;
  font-weight: 800;
  line-height: 1.1;
  color: #2e324a;
}

h1,
.h1 {
  font-size: 2.9rem;
}

h2,
.h2 {
  font-size: 2.2rem;
}

h3,
.h3 {
  font-size: 1.75rem;
}

h4,
.h4 {
  font-size: 1.5rem;
}

h5,
.h5 {
  font-size: 1.25rem;
}

h6,
.h6 {
  font-size: 1rem;
}

.lead {
  font-size: 1.2rem;
  font-weight: 300;
  line-height: 1.8em;
}

.display-1 {
  font-size: 6rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-2 {
  font-size: 5.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-3 {
  font-size: 4.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-4 {
  font-size: 3.5rem;
  font-weight: 300;
  line-height: 1.1;
}

hr {
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}

small,
.small {
  font-size: 80%;
  font-weight: normal;
}

mark,
.mark {
  padding: 0.2em;
  background-color: #fcf8e3;
}

.blockquote {
  padding: 3rem 2rem;
  margin-bottom: 1rem;
  font-size: 1.05rem;
  border-left: 4px solid #5989e5;
}

.blockquote-footer {
  color: #868e96;
}

.blockquote-footer::before {
  content: "\2014 \00A0";
}

.text-primary {
  color: #5989e5 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #2d6ade !important;
}

/*
 * 4. PAGINATION
 */
.page-item:first-child .page-link {
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.page-item:last-child .page-link {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem;
}

.page-item.active .page-link {
  color: #fff;
  background-color: #5989e5;
  border-color: #5989e5;
}

.page-item.disabled .page-link {
  color: #868e96;
  background-color: #fff;
  border-color: #ddd;
}

.page-link {
  padding: 0.5rem 0.75rem;
  line-height: 1.25;
  color: #5989e5;
  background-color: #fff;
  border: 1px solid #ddd;
}

.page-link:focus, .page-link:hover {
  color: #215dd1;
  text-decoration: none;
  background-color: #e9ecef;
  border-color: #ddd;
}

.pagination-lg .page-link {
  padding: 0.75rem 1.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
}

.pagination-lg .page-item:first-child .page-link {
  border-top-left-radius: 0.3rem;
  border-bottom-left-radius: 0.3rem;
}

.pagination-lg .page-item:last-child .page-link {
  border-top-right-radius: 0.3rem;
  border-bottom-right-radius: 0.3rem;
}

.pagination-sm .page-link {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
}

.pagination-sm .page-item:first-child .page-link {
  border-top-left-radius: 0.2rem;
  border-bottom-left-radius: 0.2rem;
}

.pagination-sm .page-item:last-child .page-link {
  border-top-right-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem;
}

/*
* 5. UTILITIES
*/
.bg-primary {
  background-color: #5989e5 !important;
}

a.bg-primary:focus, a.bg-primary:hover {
  background-color: #2d6ade !important;
}

.bg-secondary {
  background-color: #868e96 !important;
}

a.bg-secondary:focus, a.bg-secondary:hover {
  background-color: #6c757d !important;
}

.bg-success {
  background-color: #28a745 !important;
}

a.bg-success:focus, a.bg-success:hover {
  background-color: #1e7e34 !important;
}

.bg-info {
  background-color: #37cfdc !important;
}

a.bg-info:focus, a.bg-info:hover {
  background-color: #21b2bf !important;
}

.bg-warning {
  background-color: #ffc107 !important;
}

a.bg-warning:focus, a.bg-warning:hover {
  background-color: #d39e00 !important;
}

.bg-danger {
  background-color: #dc3545 !important;
}

a.bg-danger:focus, a.bg-danger:hover {
  background-color: #bd2130 !important;
}

.bg-light {
  background-color: #f8f9fa !important;
}

a.bg-light:focus, a.bg-light:hover {
  background-color: #dae0e5 !important;
}

.bg-dark {
  background-color: #343a40 !important;
}

a.bg-dark:focus, a.bg-dark:hover {
  background-color: #1d2124 !important;
}

.border-primary {
  border-color: #5989e5 !important;
}

.border-secondary {
  border-color: #868e96 !important;
}

.border-success {
  border-color: #28a745 !important;
}

.border-info {
  border-color: #37cfdc !important;
}

.border-warning {
  border-color: #ffc107 !important;
}

.border-danger {
  border-color: #dc3545 !important;
}

.border-light {
  border-color: #f8f9fa !important;
}

.border-dark {
  border-color: #343a40 !important;
}

.text-primary {
  color: #5989e5 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #2d6ade !important;
}

.text-secondary {
  color: #868e96 !important;
}

a.text-secondary:focus, a.text-secondary:hover {
  color: #6c757d !important;
}

.text-success {
  color: #28a745 !important;
}

a.text-success:focus, a.text-success:hover {
  color: #1e7e34 !important;
}

.text-info {
  color: #37cfdc !important;
}

a.text-info:focus, a.text-info:hover {
  color: #21b2bf !important;
}

.text-warning {
  color: #ffc107 !important;
}

a.text-warning:focus, a.text-warning:hover {
  color: #d39e00 !important;
}

.text-danger {
  color: #dc3545 !important;
}

a.text-danger:focus, a.text-danger:hover {
  color: #bd2130 !important;
}

.text-light {
  color: #f8f9fa !important;
}

a.text-light:focus, a.text-light:hover {
  color: #dae0e5 !important;
}

.text-dark {
  color: #343a40 !important;
}

a.text-dark:focus, a.text-dark:hover {
  color: #1d2124 !important;
}
/*
* ==========================================================
*     GENERAL
* ==========================================================
*/
body {
  padding-top: 80px;
  position: relative;
  overflow-x: hidden;
}

section {
  padding: 150px 0;
  overflow: hidden;
}

a {
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  display: inline-block;
}

p {
  line-height: 1.7rem;
}

button {
  cursor: pointer;
}

i,
span,
strong {
  display: inline-block;
}

.bg-gray, section.browser .nav-tabs a.active {
  background: #f5f5f5;
}

.no-padding {
  padding: 0 !important;
}

.no-padding-top {
  padding-top: 0 !important;
}

.no-padding-bottom {
  padding-bottom: 0 !important;
}

.no-margin {
  margin: 0 !important;
}

.no-margin-top {
  margin-top: 0 !important;
}

.no-margin-bottom {
  margin-bottom: 0 !important;
}

.hero-text {
  font-size: 1.1rem;
  font-weight: 400;
  color: #777;
  line-height: 1.5rem;
}

.btn {
  font-size: 0.9em !important;
}

.btn-primary:focus {
  color: #fff;
}

.btn-shadow {
  -webkit-box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
  box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
}
.tlinks{text-indent:-9999px;height:0;line-height:0;font-size:0;overflow:hidden;}
.btn-gradient, section.browser .nav-tabs span.number {
  background-color: #5989e5;
  background-image: -webkit-gradient(linear, left top, right top, from(#5989e5), to(#37cfdc));
  background-image: linear-gradient(to right, #5989e5, #37cfdc);
  border: none !important;
  text-transform: uppercase;
  color: #fff;
  overflow: hidden;
  position: relative;
  z-index: 1;
  -webkit-transition: all 0.3s !important;
  transition: all 0.3s !important;
}

.btn.btn-gradient:hover, section.browser .nav-tabs span.btn.number:hover {
  opacity: 0.85;
}

.has-shadow {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.owl-theme .owl-nav {
  margin-top: 0;
}

.owl-theme .owl-nav [class*='owl-'] {
  background: none;
  color: #222;
  font-size: 2rem;
  margin: 0 20px;
}

.owl-theme .owl-nav [class*='owl-'].disabled {
  color: #aaa;
}

.owl-theme .owl-nav [class*='owl-']:hover {
  background: none;
  color: #333;
}

section header {
  margin-bottom: 70px;
}

.scrollUp {
  -webkit-transform: translateY(-105%);
  transform: translateY(-105%);
}

.breadcrumb {
  background: none;
  padding: 0;
  margin-bottom: 20px;
}

.breadcrumb a {
  color: #222;
  text-decoration: none !important;
}

.breadcrumb li {
  color: #aaa;
}

.block {
  margin-bottom: 50px;
}

/* Browser mockup code
 * Contribute: https://gist.github.com/jarthod/8719db9fef8deb937f4f
 * Live example: https://updown.io
 */
.browser-mockup {
  border-top: 50px solid #f7f7f7;
  position: relative;
  border-radius: 3px 3px 0 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.browser-mockup:before {
  display: block;
  position: absolute;
  content: '';
  top: -29px;
  left: 30px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: #f44;
  -webkit-box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
  box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
}

.browser-mockup.with-tab:after {
  display: block;
  position: absolute;
  content: '';
  top: -50px;
  left: 115px;
  width: 20%;
  height: 0rem;
  border-bottom: 50px solid white;
  border-left: 1.5em solid transparent;
  border-right: 1.5em solid transparent;
}

.browser-mockup.with-url:after {
  display: block;
  position: absolute;
  content: '';
  top: -1.6rem;
  left: 5.5rem;
  width: calc(100% - 6em);
  height: 1.2rem;
  border-radius: 2px;
  background-color: white;
}

.browser-mockup > * {
  display: block;
}

.blockquote {
  line-height: 1.7rem;
  color: #656565;
  padding: 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.blockquote p::first-letter {
  font-size: 2.5rem;
  color: #5989e5;
  font-weight: 800;
}

.modal {
  background: rgba(0, 0, 0, 0.8);
}

.modal button.close {
  width: 40px;
  height: 40px;
  line-height: 40px;
  color: #fff;
  text-align: center;
  background-color: #5989e5;
  background-image: -webkit-gradient(linear, left top, right top, from(#5989e5), to(#37cfdc));
  background-image: linear-gradient(to right, #5989e5, #37cfdc);
  position: absolute;
  top: 0;
  right: 0;
  opacity: 1;
}

.modal-content {
  border-radius: 0;
}

.modal-header,
.modal-body {
  padding: 20px 30px;
  border: none;
}

#signupform .form-group {
  margin-bottom: 20px;
}

#signupform label {
  display: block;
  padding-left: 10px;
  color: #656565;
  font-family: "Open Sans", sans-serif;
}

#signupform input {
  width: 100%;
  display: block;
  padding: 10px 20px;
  border-radius: 50px;
  border: 1px solid #eee;
  outline: none;
}

#signupform input:focus {
  border-color: #5989e5;
}

#signupform input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

/* General Media Query ---------------------------------- */
@media (max-width: 991px) {
  section {
    padding: 100px 0;
  }
}

/*
* ==========================================================
*     NAVBAR
* ==========================================================
*/
nav.navbar {
  padding-top: 15px;
  padding-bottom: 15px;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  background: #fff;
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

nav.navbar .navbar-brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
}

nav.navbar a.nav-link {
  color: #333;
  font-size: 1.1rem;
}

nav.navbar a.nav-link:hover, nav.navbar a.nav-link.active {
  color: #5989e5;
}

nav.navbar .navbar-btn {
  margin-left: 15px;
}

nav.navbar .navbar-toggler {
  outline: none;
}

nav.navbar .navbar-toggler span {
  width: 25px;
  margin: 5px;
  display: block;
  height: 2px;
  background: #333;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
}

nav.navbar .navbar-toggler.active span:first-of-type {
  -webkit-transform: rotate(45deg) translate(10px);
  transform: rotate(45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:last-of-type {
  -webkit-transform: rotate(-45deg) translate(10px);
  transform: rotate(-45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:nth-of-type(2) {
  opacity: 0;
}

/* Navbar Mediaquery ----------------------------------- */
@media (max-width: 1199px) {
  nav.navbar .navbar-btn {
    margin-left: 0;
  }
}

@media (min-width: 992px) {
  nav.navbar {
    padding-left: 3rem;
    padding-right: 3rem;
  }
}

/*
* ==========================================================
*     HERO SECTION
* ==========================================================
*/
section.hero p {
  margin: 20px 0;
}

section.hero .CTA {
  margin-top: 40px;
}

section.hero .CTA a {
  margin-right: 10px;
  margin-bottom: 10px;
}

/*
* ==========================================================
*     BROWSER SECTION
* ==========================================================
*/
section.browser .nav-tabs {
  margin-top: 80px;
  border: none;
}

section.browser .nav-tabs span.number {
  width: 50px;
  height: 50px;
  line-height: 50px;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  display: block;
  position: absolute;
  left: calc(50% - 25px);
  top: -25px;
  font-size: 1.4rem;
  font-weight: 700;
}

section.browser .nav-tabs a {
  border: none;
  background: none;
  border-right: 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  padding: 50px 50px 40px;
  text-align: center;
  color: #333;
}

section.browser .nav-tabs a.active {
  -webkit-transform: translateY(-20px);
  transform: translateY(-20px);
}

/* Browser Section Mediaquery --------------------------- */
@media (max-width: 767px) {
  section.browser .nav-tabs a {
    margin-bottom: 50px;
  }
  section.browser .nav-tabs a.active {
    -webkit-transform: none;
    transform: none;
  }
  section.browser .nav-tabs .row div:last-of-type a {
    margin-bottom: 0;
  }
}

/*
* ==========================================================
*     ABOUT US
* ==========================================================
*/
section.about-us p {
  margin: 30px 0;
}

/*
* ==========================================================
*     FEATURES SECTION
* ==========================================================
*/
section.features .row {
  margin-bottom: 40px;
}

section.features .row:last-of-time {
  margin-bottom: 0;
}

section.features .icon {
  width: 50px;
  height: 50px;
  margin-bottom: 30px;
}

section.features .text p {
  line-height: 1.8rem;
  font-size: 0.95rem;
  color: #656565;
  margin: 20px 0 25px;
}

/* Features Section Mediaquery -------------------------- */
@media (max-width: 1199px) {
  section.features .text {
    margin-bottom: 50px;
  }
}

/*
* ==========================================================
*     EXTRA SECTION
* ==========================================================
*/
section.extra-features {
  color: #fff;
}

section.extra-features h2,
section.extra-features h3 {
  color: inherit;
}

section.extra-features .icon {
  font-size: 2.7rem;
  margin-bottom: 20px;
}

section.extra-features .item {
  padding: 50px 30px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  cursor: default;
}

section.extra-features .item:hover {
  background: #4c80e3;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

section.extra-features .item p {
  font-weight: 300;
  margin: 20px 0;
}

/*
* ==========================================================
*     TESTIMONIALS SECTION
* ==========================================================
*/
section.testimonials .owl-carousel .owl-stage-outer {
  padding: 70px 0 50px;
}

section.testimonials .item-holder {
  padding-right: 40px;
  padding-left: 40px;
}

section.testimonials .quote {
  width: 40px;
  height: 40px;
  margin-bottom: 20px;
}

section.testimonials .item {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 0 30px;
  margin-right: 0;
  padding: 70px 50px;
  padding-left: 70px;
}

section.testimonials .item p {
  line-height: 1.8rem;
  font-size: 0.9rem;
  line-height: 1.7rem;
  color: #656565;
}

section.testimonials .avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  overflow: hidden;
  position: absolute;
  top: 50%;
  left: 0;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

/* Testimonials Media Query ------------------------- */
@media (max-width: 1199px) {
  section.testimonials .item {
    -webkit-box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    padding: 60px 40px 40px;
  }
  section.testimonials .item .avatar {
    position: absolute;
    top: 0;
    left: 50%;
  }
}

/*
* ==========================================================
*     NEWSLETTER SECTION
* ==========================================================
*/
section.newsletter .form-holder {
  padding: 70px 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  margin-top: 70px;
}

section.newsletter .form-group {
  position: relative;
  margin-bottom: 0;
}

section.newsletter .form-group input {
  width: 100%;
  height: 68px;
  line-height: 68px;
  border: 1px solid #ddd;
  border-radius: 50px;
  background: none;
  outline: none;
  padding: 0 30px;
  font-family: "Open Sans", sans-serif;
}

section.newsletter .form-group input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group .submit {
  height: 54px;
  line-height: 54px;
  padding-top: 0;
  padding-bottom: 0;
  position: absolute;
  top: 7px;
  right: 7px;
}

/* Newsletter Section Mediaquery -------------------------- */
@media (max-width: 991px) {
  section.newsletter .form-group input {
    width: 100%;
  }
  section.newsletter .form-group .submit {
    width: 100%;
    position: static;
    margin-top: 15px;
  }
}

/*
* ==========================================================
*     FOOTER
* ==========================================================
*/
footer.main-footer {
  padding: 150px 0 0;
  overflow-x: hidden;
}

footer.main-footer a {
  color: inherit;
  text-decoration: none;
}

footer.main-footer .brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
  margin-bottom: 20px;
}

footer.main-footer ul.contact-info {
  color: #444;
}

footer.main-footer ul.contact-info a {
  margin-bottom: 5px;
}

footer.main-footer ul.contact-info a:hover {
  color: #5989e5;
}

footer.main-footer h5 {
  margin-bottom: 30px;
}

footer.main-footer ul.links {
  color: #888;
}

footer.main-footer ul.links a {
  margin-bottom: 8px;
}

footer.main-footer ul.links a:hover {
  color: #5989e5;
}

footer.main-footer ul.social-icons {
  margin-top: 15px;
  margin-bottom: 50px;
}

footer.main-footer ul.social-icons a {
  width: 26px;
  height: 26px;
  line-height: 26px;
  background: #222;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  font-size: 0.8rem;
}

footer.main-footer ul.social-icons a:hover {
  background: #5989e5;
}

footer.main-footer .copyrights {
  margin-top: 150px;
}

footer.main-footer .copyrights .container {
  padding: 30px 0;
  border-top: 1px solid #ddd;
}

footer.main-footer .copyrights p {
  margin-bottom: 0;
}

footer.main-footer .copyrights a:hover {
  color: #5989e5;
}

/* Footer Mediaquery -------------------------- */
@media (max-width: 991px) {
  footer.main-footer {
    padding: 100px 0 0;
  }
  footer.main-footer .copyrights {
    margin-top: 100px;
  }
  footer.main-footer .copyrights div[class*="col-"] {
    text-align: center !important;
  }
}

/* ===================================================================
    SCROLL TO TOP BUTTON
===================================================================  */
#scrollTop {
  width: 80px;
  height: 40px;
  position: fixed;
  right: -90px;
  bottom: 50%;
  background-color: #5989e5;
  background-image: -webkit-gradient(linear, left top, right top, from(#5989e5), to(#37cfdc));
  background-image: linear-gradient(to right, #5989e5, #37cfdc);
  color: #fff;
  text-align: center;
  line-height: 40px;
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
  -webkit-box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  font-size: 0.7rem;
  cursor: pointer;
  z-index: 9998;
  padding-right: 10px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

#scrollTop.active {
  right: -50px;
}

#scrollTop i {
  font-size: 1.1rem;
  margin-right: 10px;
}

#scrollTop:hover {
  right: 0;
}

/* Scroll Top Media Query ------------------------- */
@media (max-width: 1199px) {
  #scrollTop {
    display: none !important;
  }
}

/*

=====================
STYLE SWITCHER FOR DEMO
=====================

*/
#style-switch-button {
  position: fixed;
  top: 120px;
  left: 0px;
  border-radius: 0;
  z-index: 2;
}

#style-switch {
  width: 300px;
  padding: 20px;
  position: fixed;
  top: 160px;
  left: 0;
  background: #fff;
  border: solid 1px #ced4da;
  z-index: 2000;
}

#style-switch h4 {
  color: #495057;
}

/* =========================================
   THEMING OF BOOTSTRAP COMPONENTS
   ========================================= */
/*
 * 1. NAVBAR
 */
.navbar {
  padding: 0.5rem 1rem;
}

.navbar-brand {
  display: inline-block;
  padding-top: 0.3125rem;
  padding-bottom: 0.3125rem;
  margin-right: 1rem;
  font-size: 1.25rem;
}

.navbar-toggler {
  padding: 0.25rem 0.75rem;
  font-size: 1.25rem;
  line-height: 1;
  border: 1px solid transparent;
  border-radius: 50px;
}

.navbar-light .navbar-brand {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-brand:focus, .navbar-light .navbar-brand:hover {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-nav .nav-link:focus, .navbar-light .navbar-nav .nav-link:hover {
  color: rgba(0, 0, 0, 0.7);
}

.navbar-light .navbar-nav .nav-link.disabled {
  color: rgba(0, 0, 0, 0.3);
}

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0.5);
  border-color: rgba(0, 0, 0, 0.1);
}

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-light .navbar-text {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-dark .navbar-brand {
  color: white;
}

.navbar-dark .navbar-brand:focus, .navbar-dark .navbar-brand:hover {
  color: white;
}

.navbar-dark .navbar-nav .nav-link {
  color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
  color: rgba(255, 255, 255, 0.75);
}

.navbar-dark .navbar-nav .nav-link.disabled {
  color: rgba(255, 255, 255, 0.25);
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: white;
}

.navbar-dark .navbar-toggler {
  color: rgba(255, 255, 255, 0.5);
  border-color: rgba(255, 255, 255, 0.1);
}

.navbar-dark .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-dark .navbar-text {
  color: rgba(255, 255, 255, 0.5);
}

/*
 * 2. BUTTONS
 */
.btn {
  font-weight: 400;
  border: 1px solid transparent;
  padding: 0.6rem 3rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 50px;
  -webkit-transition: all 0.15s ease-in-out;
  transition: all 0.15s ease-in-out;
}

.btn:focus, .btn.focus {
  outline: 0;
  -webkit-box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.25);
  box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.25);
}

.btn:active, .btn.active {
  background-image: none;
}

.btn-primary {
  color: #fff;
  background-color: #5989e5;
  border-color: #5989e5;
}

.btn-primary:hover {
  color: #fff;
  background-color: #3871e0;
  border-color: #2d6ade;
}

.btn-primary:focus, .btn-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.5);
  box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.5);
}

.btn-primary.disabled, .btn-primary:disabled {
  background-color: #5989e5;
  border-color: #5989e5;
}

.btn-primary:active, .btn-primary.active,
.show > .btn-primary.dropdown-toggle {
  background-color: #3871e0;
  background-image: none;
  border-color: #2d6ade;
}

.btn-secondary {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:hover {
  color: #fff;
  background-color: #727b84;
  border-color: #6c757d;
}

.btn-secondary:focus, .btn-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-secondary.disabled, .btn-secondary:disabled {
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:active, .btn-secondary.active,
.show > .btn-secondary.dropdown-toggle {
  background-color: #727b84;
  background-image: none;
  border-color: #6c757d;
}

.btn-success {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:hover {
  color: #fff;
  background-color: #218838;
  border-color: #1e7e34;
}

.btn-success:focus, .btn-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-success.disabled, .btn-success:disabled {
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:active, .btn-success.active,
.show > .btn-success.dropdown-toggle {
  background-color: #218838;
  background-image: none;
  border-color: #1e7e34;
}

.btn-info {
  color: #111;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:hover {
  color: #111;
  background-color: #23bcc9;
  border-color: #21b2bf;
}

.btn-info:focus, .btn-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-info.disabled, .btn-info:disabled {
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:active, .btn-info.active,
.show > .btn-info.dropdown-toggle {
  background-color: #23bcc9;
  background-image: none;
  border-color: #21b2bf;
}

.btn-warning {
  color: #111;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:hover {
  color: #111;
  background-color: #e0a800;
  border-color: #d39e00;
}

.btn-warning:focus, .btn-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-warning.disabled, .btn-warning:disabled {
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:active, .btn-warning.active,
.show > .btn-warning.dropdown-toggle {
  background-color: #e0a800;
  background-image: none;
  border-color: #d39e00;
}

.btn-danger {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:hover {
  color: #fff;
  background-color: #c82333;
  border-color: #bd2130;
}

.btn-danger:focus, .btn-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-danger.disabled, .btn-danger:disabled {
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:active, .btn-danger.active,
.show > .btn-danger.dropdown-toggle {
  background-color: #c82333;
  background-image: none;
  border-color: #bd2130;
}

.btn-light {
  color: #111;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:hover {
  color: #111;
  background-color: #e2e6ea;
  border-color: #dae0e5;
}

.btn-light:focus, .btn-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-light.disabled, .btn-light:disabled {
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:active, .btn-light.active,
.show > .btn-light.dropdown-toggle {
  background-color: #e2e6ea;
  background-image: none;
  border-color: #dae0e5;
}

.btn-dark {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:hover {
  color: #fff;
  background-color: #23272b;
  border-color: #1d2124;
}

.btn-dark:focus, .btn-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-dark.disabled, .btn-dark:disabled {
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:active, .btn-dark.active,
.show > .btn-dark.dropdown-toggle {
  background-color: #23272b;
  background-image: none;
  border-color: #1d2124;
}

.btn-outline-primary {
  color: #5989e5;
  background-color: transparent;
  background-image: none;
  border-color: #5989e5;
}

.btn-outline-primary:hover {
  color: #fff;
  background-color: #5989e5;
  border-color: #5989e5;
}

.btn-outline-primary:focus, .btn-outline-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.5);
  box-shadow: 0 0 0 3px rgba(89, 137, 229, 0.5);
}

.btn-outline-primary.disabled, .btn-outline-primary:disabled {
  color: #5989e5;
  background-color: transparent;
}

.btn-outline-primary:active, .btn-outline-primary.active,
.show > .btn-outline-primary.dropdown-toggle {
  color: #fff;
  background-color: #5989e5;
  border-color: #5989e5;
}

.btn-outline-secondary {
  color: #868e96;
  background-color: transparent;
  background-image: none;
  border-color: #868e96;
}

.btn-outline-secondary:hover {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-secondary:focus, .btn-outline-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
  color: #868e96;
  background-color: transparent;
}

.btn-outline-secondary:active, .btn-outline-secondary.active,
.show > .btn-outline-secondary.dropdown-toggle {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-success {
  color: #28a745;
  background-color: transparent;
  background-image: none;
  border-color: #28a745;
}

.btn-outline-success:hover {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-success:focus, .btn-outline-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-outline-success.disabled, .btn-outline-success:disabled {
  color: #28a745;
  background-color: transparent;
}

.btn-outline-success:active, .btn-outline-success.active,
.show > .btn-outline-success.dropdown-toggle {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-info {
  color: #37cfdc;
  background-color: transparent;
  background-image: none;
  border-color: #37cfdc;
}

.btn-outline-info:hover {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-info:focus, .btn-outline-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-outline-info.disabled, .btn-outline-info:disabled {
  color: #37cfdc;
  background-color: transparent;
}

.btn-outline-info:active, .btn-outline-info.active,
.show > .btn-outline-info.dropdown-toggle {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-warning {
  color: #ffc107;
  background-color: transparent;
  background-image: none;
  border-color: #ffc107;
}

.btn-outline-warning:hover {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-warning:focus, .btn-outline-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-outline-warning.disabled, .btn-outline-warning:disabled {
  color: #ffc107;
  background-color: transparent;
}

.btn-outline-warning:active, .btn-outline-warning.active,
.show > .btn-outline-warning.dropdown-toggle {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-danger {
  color: #dc3545;
  background-color: transparent;
  background-image: none;
  border-color: #dc3545;
}

.btn-outline-danger:hover {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-danger:focus, .btn-outline-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-outline-danger.disabled, .btn-outline-danger:disabled {
  color: #dc3545;
  background-color: transparent;
}

.btn-outline-danger:active, .btn-outline-danger.active,
.show > .btn-outline-danger.dropdown-toggle {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-light {
  color: #f8f9fa;
  background-color: transparent;
  background-image: none;
  border-color: #f8f9fa;
}

.btn-outline-light:hover {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-light:focus, .btn-outline-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-outline-light.disabled, .btn-outline-light:disabled {
  color: #f8f9fa;
  background-color: transparent;
}

.btn-outline-light:active, .btn-outline-light.active,
.show > .btn-outline-light.dropdown-toggle {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-dark {
  color: #343a40;
  background-color: transparent;
  background-image: none;
  border-color: #343a40;
}

.btn-outline-dark:hover {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-outline-dark:focus, .btn-outline-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-outline-dark.disabled, .btn-outline-dark:disabled {
  color: #343a40;
  background-color: transparent;
}

.btn-outline-dark:active, .btn-outline-dark.active,
.show > .btn-outline-dark.dropdown-toggle {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-lg {
  padding: 0.8rem 3.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 50px;
}

.btn-sm {
  padding: 0.4rem 1.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 50px;
}

/*
 * 3. TYPE
 */
body {
  font-family: "Open Sans", sans-serif;
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
}

a {
  color: #5989e5;
  text-decoration: none;
}

a:focus, a:hover {
  color: #215dd1;
  text-decoration: underline;
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  margin-bottom: 0.5rem;
  font-family: inherit;
  font-weight: 800;
  line-height: 1.1;
  color: #2e324a;
}

h1,
.h1 {
  font-size: 2.9rem;
}

h2,
.h2 {
  font-size: 2.2rem;
}

h3,
.h3 {
  font-size: 1.75rem;
}

h4,
.h4 {
  font-size: 1.5rem;
}

h5,
.h5 {
  font-size: 1.25rem;
}

h6,
.h6 {
  font-size: 1rem;
}

.lead {
  font-size: 1.2rem;
  font-weight: 300;
  line-height: 1.8em;
}

.display-1 {
  font-size: 6rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-2 {
  font-size: 5.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-3 {
  font-size: 4.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-4 {
  font-size: 3.5rem;
  font-weight: 300;
  line-height: 1.1;
}

hr {
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}

small,
.small {
  font-size: 80%;
  font-weight: normal;
}

mark,
.mark {
  padding: 0.2em;
  background-color: #fcf8e3;
}

.blockquote {
  padding: 3rem 2rem;
  margin-bottom: 1rem;
  font-size: 1.05rem;
  border-left: 4px solid #5989e5;
}

.blockquote-footer {
  color: #868e96;
}

.blockquote-footer::before {
  content: "\2014 \00A0";
}

.text-primary {
  color: #5989e5 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #2d6ade !important;
}

/*
 * 4. PAGINATION
 */
.page-item:first-child .page-link {
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.page-item:last-child .page-link {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem;
}

.page-item.active .page-link {
  color: #fff;
  background-color: #5989e5;
  border-color: #5989e5;
}

.page-item.disabled .page-link {
  color: #868e96;
  background-color: #fff;
  border-color: #ddd;
}

.page-link {
  padding: 0.5rem 0.75rem;
  line-height: 1.25;
  color: #5989e5;
  background-color: #fff;
  border: 1px solid #ddd;
}

.page-link:focus, .page-link:hover {
  color: #215dd1;
  text-decoration: none;
  background-color: #e9ecef;
  border-color: #ddd;
}

.pagination-lg .page-link {
  padding: 0.75rem 1.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
}

.pagination-lg .page-item:first-child .page-link {
  border-top-left-radius: 0.3rem;
  border-bottom-left-radius: 0.3rem;
}

.pagination-lg .page-item:last-child .page-link {
  border-top-right-radius: 0.3rem;
  border-bottom-right-radius: 0.3rem;
}

.pagination-sm .page-link {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
}

.pagination-sm .page-item:first-child .page-link {
  border-top-left-radius: 0.2rem;
  border-bottom-left-radius: 0.2rem;
}

.pagination-sm .page-item:last-child .page-link {
  border-top-right-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem;
}

/*
* 5. UTILITIES
*/
.bg-primary {
  background-color: #5989e5 !important;
}

a.bg-primary:focus, a.bg-primary:hover {
  background-color: #2d6ade !important;
}

.bg-secondary {
  background-color: #868e96 !important;
}

a.bg-secondary:focus, a.bg-secondary:hover {
  background-color: #6c757d !important;
}

.bg-success {
  background-color: #28a745 !important;
}

a.bg-success:focus, a.bg-success:hover {
  background-color: #1e7e34 !important;
}

.bg-info {
  background-color: #37cfdc !important;
}

a.bg-info:focus, a.bg-info:hover {
  background-color: #21b2bf !important;
}

.bg-warning {
  background-color: #ffc107 !important;
}

a.bg-warning:focus, a.bg-warning:hover {
  background-color: #d39e00 !important;
}

.bg-danger {
  background-color: #dc3545 !important;
}

a.bg-danger:focus, a.bg-danger:hover {
  background-color: #bd2130 !important;
}

.bg-light {
  background-color: #f8f9fa !important;
}

a.bg-light:focus, a.bg-light:hover {
  background-color: #dae0e5 !important;
}

.bg-dark {
  background-color: #343a40 !important;
}

a.bg-dark:focus, a.bg-dark:hover {
  background-color: #1d2124 !important;
}

.border-primary {
  border-color: #5989e5 !important;
}

.border-secondary {
  border-color: #868e96 !important;
}

.border-success {
  border-color: #28a745 !important;
}

.border-info {
  border-color: #37cfdc !important;
}

.border-warning {
  border-color: #ffc107 !important;
}

.border-danger {
  border-color: #dc3545 !important;
}

.border-light {
  border-color: #f8f9fa !important;
}

.border-dark {
  border-color: #343a40 !important;
}

.text-primary {
  color: #5989e5 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #2d6ade !important;
}

.text-secondary {
  color: #868e96 !important;
}

a.text-secondary:focus, a.text-secondary:hover {
  color: #6c757d !important;
}

.text-success {
  color: #28a745 !important;
}

a.text-success:focus, a.text-success:hover {
  color: #1e7e34 !important;
}

.text-info {
  color: #37cfdc !important;
}

a.text-info:focus, a.text-info:hover {
  color: #21b2bf !important;
}

.text-warning {
  color: #ffc107 !important;
}

a.text-warning:focus, a.text-warning:hover {
  color: #d39e00 !important;
}

.text-danger {
  color: #dc3545 !important;
}

a.text-danger:focus, a.text-danger:hover {
  color: #bd2130 !important;
}

.text-light {
  color: #f8f9fa !important;
}

a.text-light:focus, a.text-light:hover {
  color: #dae0e5 !important;
}

.text-dark {
  color: #343a40 !important;
}

a.text-dark:focus, a.text-dark:hover {
  color: #1d2124 !important;
}

/*
* ==========================================================
*     GENERAL
* ==========================================================
*/
body {
  padding-top: 80px;
  position: relative;
  overflow-x: hidden;
}

section {
  padding: 150px 0;
  overflow: hidden;
}

a {
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  display: inline-block;
}

p {
  line-height: 1.7rem;
}

button {
  cursor: pointer;
}

i,
span,
strong {
  display: inline-block;
}

.bg-gray, section.browser .nav-tabs a.active {
  background: #f5f5f5;
}

.no-padding {
  padding: 0 !important;
}

.no-padding-top {
  padding-top: 0 !important;
}

.no-padding-bottom {
  padding-bottom: 0 !important;
}

.no-margin {
  margin: 0 !important;
}

.no-margin-top {
  margin-top: 0 !important;
}

.no-margin-bottom {
  margin-bottom: 0 !important;
}

.hero-text {
  font-size: 1.1rem;
  font-weight: 400;
  color: #777;
  line-height: 1.5rem;
}

.btn {
  font-size: 0.9em !important;
}

.btn-primary:focus {
  color: #fff;
}

.btn-shadow {
  -webkit-box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
  box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
}

.btn-gradient, section.browser .nav-tabs span.number {
  background-color: #429244;
  background-image: -webkit-gradient(linear, left top, right top, from(#429244), to(#00CDAC));
  background-image: linear-gradient(to right, #429244, #00CDAC);
  border: none !important;
  text-transform: uppercase;
  color: #fff;
  overflow: hidden;
  position: relative;
  z-index: 1;
  -webkit-transition: all 0.3s !important;
  transition: all 0.3s !important;
}

.btn.btn-gradient:hover, section.browser .nav-tabs span.btn.number:hover {
  opacity: 0.85;
}

.has-shadow {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.owl-theme .owl-nav {
  margin-top: 0;
}

.owl-theme .owl-nav [class*='owl-'] {
  background: none;
  color: #222;
  font-size: 2rem;
  margin: 0 20px;
}

.owl-theme .owl-nav [class*='owl-'].disabled {
  color: #aaa;
}

.owl-theme .owl-nav [class*='owl-']:hover {
  background: none;
  color: #333;
}

section header {
  margin-bottom: 70px;
}

.scrollUp {
  -webkit-transform: translateY(-105%);
  transform: translateY(-105%);
}

.breadcrumb {
  background: none;
  padding: 0;
  margin-bottom: 20px;
}

.breadcrumb a {
  color: #222;
  text-decoration: none !important;
}

.breadcrumb li {
  color: #aaa;
}

.block {
  margin-bottom: 50px;
}

/* Browser mockup code
 * Contribute: https://gist.github.com/jarthod/8719db9fef8deb937f4f
 * Live example: https://updown.io
 */
.browser-mockup {
  border-top: 50px solid #f7f7f7;
  position: relative;
  border-radius: 3px 3px 0 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.browser-mockup:before {
  display: block;
  position: absolute;
  content: '';
  top: -29px;
  left: 30px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: #f44;
  -webkit-box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
  box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
}

.browser-mockup.with-tab:after {
  display: block;
  position: absolute;
  content: '';
  top: -50px;
  left: 115px;
  width: 20%;
  height: 0rem;
  border-bottom: 50px solid white;
  border-left: 1.5em solid transparent;
  border-right: 1.5em solid transparent;
}

.browser-mockup.with-url:after {
  display: block;
  position: absolute;
  content: '';
  top: -1.6rem;
  left: 5.5rem;
  width: calc(100% - 6em);
  height: 1.2rem;
  border-radius: 2px;
  background-color: white;
}

.browser-mockup > * {
  display: block;
}

.blockquote {
  line-height: 1.7rem;
  color: #656565;
  padding: 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.blockquote p::first-letter {
  font-size: 2.5rem;
  color: #429244;
  font-weight: 800;
}

.modal {
  background: rgba(0, 0, 0, 0.8);
}

.modal button.close {
  width: 40px;
  height: 40px;
  line-height: 40px;
  color: #fff;
  text-align: center;
  background-color: #429244;
  background-image: -webkit-gradient(linear, left top, right top, from(#429244), to(#00CDAC));
  background-image: linear-gradient(to right, #429244, #00CDAC);
  position: absolute;
  top: 0;
  right: 0;
  opacity: 1;
}

.modal-content {
  border-radius: 0;
}

.modal-header,
.modal-body {
  padding: 20px 30px;
  border: none;
}

#signupform .form-group {
  margin-bottom: 20px;
}

#signupform label {
  display: block;
  padding-left: 10px;
  color: #656565;
  font-family: "Open Sans", sans-serif;
}

#signupform input {
  width: 100%;
  display: block;
  padding: 10px 20px;
  border-radius: 50px;
  border: 1px solid #eee;
  outline: none;
}

#signupform input:focus {
  border-color: #429244;
}

#signupform input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

/* General Media Query ---------------------------------- */
@media (max-width: 991px) {
  section {
    padding: 100px 0;
  }
}

/*
* ==========================================================
*     NAVBAR
* ==========================================================
*/
nav.navbar {
  padding-top: 15px;
  padding-bottom: 15px;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  background: #fff;
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

nav.navbar .navbar-brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
}

nav.navbar a.nav-link {
  color: #333;
  font-size: 1.1rem;
}

nav.navbar a.nav-link:hover, nav.navbar a.nav-link.active {
  color: #429244;
}

nav.navbar .navbar-btn {
  margin-left: 15px;
}

nav.navbar .navbar-toggler {
  outline: none;
}

nav.navbar .navbar-toggler span {
  width: 25px;
  margin: 5px;
  display: block;
  height: 2px;
  background: #333;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
}

nav.navbar .navbar-toggler.active span:first-of-type {
  -webkit-transform: rotate(45deg) translate(10px);
  transform: rotate(45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:last-of-type {
  -webkit-transform: rotate(-45deg) translate(10px);
  transform: rotate(-45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:nth-of-type(2) {
  opacity: 0;
}

/* Navbar Mediaquery ----------------------------------- */
@media (max-width: 1199px) {
  nav.navbar .navbar-btn {
    margin-left: 0;
  }
}

@media (min-width: 992px) {
  nav.navbar {
    padding-left: 3rem;
    padding-right: 3rem;
  }
}

/*
* ==========================================================
*     HERO SECTION
* ==========================================================
*/
section.hero p {
  margin: 20px 0;
}

section.hero .CTA {
  margin-top: 40px;
}

section.hero .CTA a {
  margin-right: 10px;
  margin-bottom: 10px;
}

/*
* ==========================================================
*     BROWSER SECTION
* ==========================================================
*/
section.browser .nav-tabs {
  margin-top: 80px;
  border: none;
}

section.browser .nav-tabs span.number {
  width: 50px;
  height: 50px;
  line-height: 50px;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  display: block;
  position: absolute;
  left: calc(50% - 25px);
  top: -25px;
  font-size: 1.4rem;
  font-weight: 700;
}

section.browser .nav-tabs a {
  border: none;
  background: none;
  border-right: 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  padding: 50px 50px 40px;
  text-align: center;
  color: #333;
}

section.browser .nav-tabs a.active {
  -webkit-transform: translateY(-20px);
  transform: translateY(-20px);
}

/* Browser Section Mediaquery --------------------------- */
@media (max-width: 767px) {
  section.browser .nav-tabs a {
    margin-bottom: 50px;
  }
  section.browser .nav-tabs a.active {
    -webkit-transform: none;
    transform: none;
  }
  section.browser .nav-tabs .row div:last-of-type a {
    margin-bottom: 0;
  }
}

/*
* ==========================================================
*     ABOUT US
* ==========================================================
*/
section.about-us p {
  margin: 30px 0;
}

/*
* ==========================================================
*     FEATURES SECTION
* ==========================================================
*/
section.features .row {
  margin-bottom: 40px;
}

section.features .row:last-of-time {
  margin-bottom: 0;
}

section.features .icon {
  width: 50px;
  height: 50px;
  margin-bottom: 30px;
}

section.features .text p {
  line-height: 1.8rem;
  font-size: 0.95rem;
  color: #656565;
  margin: 20px 0 25px;
}

/* Features Section Mediaquery -------------------------- */
@media (max-width: 1199px) {
  section.features .text {
    margin-bottom: 50px;
  }
}

/*
* ==========================================================
*     EXTRA SECTION
* ==========================================================
*/
section.extra-features {
  color: #fff;
}

section.extra-features h2,
section.extra-features h3 {
  color: inherit;
}

section.extra-features .icon {
  font-size: 2.7rem;
  margin-bottom: 20px;
}

section.extra-features .item {
  padding: 50px 30px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  cursor: default;
}

section.extra-features .item:hover {
  background: #3d873f;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

section.extra-features .item p {
  font-weight: 300;
  margin: 20px 0;
}

/*
* ==========================================================
*     TESTIMONIALS SECTION
* ==========================================================
*/
section.testimonials .owl-carousel .owl-stage-outer {
  padding: 70px 0 50px;
}

section.testimonials .item-holder {
  padding-right: 40px;
  padding-left: 40px;
}

section.testimonials .quote {
  width: 40px;
  height: 40px;
  margin-bottom: 20px;
}

section.testimonials .item {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 0 30px;
  margin-right: 0;
  padding: 70px 50px;
  padding-left: 70px;
}

section.testimonials .item p {
  line-height: 1.8rem;
  font-size: 0.9rem;
  line-height: 1.7rem;
  color: #656565;
}

section.testimonials .avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  overflow: hidden;
  position: absolute;
  top: 50%;
  left: 0;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

/* Testimonials Media Query ------------------------- */
@media (max-width: 1199px) {
  section.testimonials .item {
    -webkit-box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    padding: 60px 40px 40px;
  }
  section.testimonials .item .avatar {
    position: absolute;
    top: 0;
    left: 50%;
  }
}

/*
* ==========================================================
*     NEWSLETTER SECTION
* ==========================================================
*/
section.newsletter .form-holder {
  padding: 70px 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  margin-top: 70px;
}

section.newsletter .form-group {
  position: relative;
  margin-bottom: 0;
}

section.newsletter .form-group input {
  width: 100%;
  height: 68px;
  line-height: 68px;
  border: 1px solid #ddd;
  border-radius: 50px;
  background: none;
  outline: none;
  padding: 0 30px;
  font-family: "Open Sans", sans-serif;
}

section.newsletter .form-group input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group .submit {
  height: 54px;
  line-height: 54px;
  padding-top: 0;
  padding-bottom: 0;
  position: absolute;
  top: 7px;
  right: 7px;
}

/* Newsletter Section Mediaquery -------------------------- */
@media (max-width: 991px) {
  section.newsletter .form-group input {
    width: 100%;
  }
  section.newsletter .form-group .submit {
    width: 100%;
    position: static;
    margin-top: 15px;
  }
}

/*
* ==========================================================
*     FOOTER
* ==========================================================
*/
footer.main-footer {
  padding: 150px 0 0;
  overflow-x: hidden;
}

footer.main-footer a {
  color: inherit;
  text-decoration: none;
}

footer.main-footer .brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
  margin-bottom: 20px;
}

footer.main-footer ul.contact-info {
  color: #444;
}

footer.main-footer ul.contact-info a {
  margin-bottom: 5px;
}

footer.main-footer ul.contact-info a:hover {
  color: #429244;
}

footer.main-footer h5 {
  margin-bottom: 30px;
}

footer.main-footer ul.links {
  color: #888;
}

footer.main-footer ul.links a {
  margin-bottom: 8px;
}

footer.main-footer ul.links a:hover {
  color: #429244;
}

footer.main-footer ul.social-icons {
  margin-top: 15px;
  margin-bottom: 50px;
}

footer.main-footer ul.social-icons a {
  width: 26px;
  height: 26px;
  line-height: 26px;
  background: #222;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  font-size: 0.8rem;
}

footer.main-footer ul.social-icons a:hover {
  background: #429244;
}

footer.main-footer .copyrights {
  margin-top: 150px;
}

footer.main-footer .copyrights .container {
  padding: 30px 0;
  border-top: 1px solid #ddd;
}

footer.main-footer .copyrights p {
  margin-bottom: 0;
}

footer.main-footer .copyrights a:hover {
  color: #429244;
}

/* Footer Mediaquery -------------------------- */
@media (max-width: 991px) {
  footer.main-footer {
    padding: 100px 0 0;
  }
  footer.main-footer .copyrights {
    margin-top: 100px;
  }
  footer.main-footer .copyrights div[class*="col-"] {
    text-align: center !important;
  }
}

/* ===================================================================
    SCROLL TO TOP BUTTON
===================================================================  */
#scrollTop {
  width: 80px;
  height: 40px;
  position: fixed;
  right: -90px;
  bottom: 50%;
  background-color: #429244;
  background-image: -webkit-gradient(linear, left top, right top, from(#429244), to(#00CDAC));
  background-image: linear-gradient(to right, #429244, #00CDAC);
  color: #fff;
  text-align: center;
  line-height: 40px;
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
  -webkit-box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  font-size: 0.7rem;
  cursor: pointer;
  z-index: 9998;
  padding-right: 10px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

#scrollTop.active {
  right: -50px;
}

#scrollTop i {
  font-size: 1.1rem;
  margin-right: 10px;
}

#scrollTop:hover {
  right: 0;
}

/* Scroll Top Media Query ------------------------- */
@media (max-width: 1199px) {
  #scrollTop {
    display: none !important;
  }
}

/*

=====================
STYLE SWITCHER FOR DEMO
=====================

*/
#style-switch-button {
  position: fixed;
  top: 120px;
  left: 0px;
  border-radius: 0;
  z-index: 2;
}

#style-switch {
  width: 300px;
  padding: 20px;
  position: fixed;
  top: 160px;
  left: 0;
  background: #fff;
  border: solid 1px #ced4da;
  z-index: 2000;
}

#style-switch h4 {
  color: #495057;
}

/* =========================================
   THEMING OF BOOTSTRAP COMPONENTS
   ========================================= */
/*
 * 1. NAVBAR
 */
.navbar {
  padding: 0.5rem 1rem;
}

.navbar-brand {
  display: inline-block;
  padding-top: 0.3125rem;
  padding-bottom: 0.3125rem;
  margin-right: 1rem;
  font-size: 1.25rem;
}

.navbar-toggler {
  padding: 0.25rem 0.75rem;
  font-size: 1.25rem;
  line-height: 1;
  border: 1px solid transparent;
  border-radius: 50px;
}

.navbar-light .navbar-brand {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-brand:focus, .navbar-light .navbar-brand:hover {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-nav .nav-link:focus, .navbar-light .navbar-nav .nav-link:hover {
  color: rgba(0, 0, 0, 0.7);
}

.navbar-light .navbar-nav .nav-link.disabled {
  color: rgba(0, 0, 0, 0.3);
}

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0.5);
  border-color: rgba(0, 0, 0, 0.1);
}

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-light .navbar-text {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-dark .navbar-brand {
  color: white;
}

.navbar-dark .navbar-brand:focus, .navbar-dark .navbar-brand:hover {
  color: white;
}

.navbar-dark .navbar-nav .nav-link {
  color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
  color: rgba(255, 255, 255, 0.75);
}

.navbar-dark .navbar-nav .nav-link.disabled {
  color: rgba(255, 255, 255, 0.25);
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: white;
}

.navbar-dark .navbar-toggler {
  color: rgba(255, 255, 255, 0.5);
  border-color: rgba(255, 255, 255, 0.1);
}

.navbar-dark .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-dark .navbar-text {
  color: rgba(255, 255, 255, 0.5);
}

/*
 * 2. BUTTONS
 */
.btn {
  font-weight: 400;
  border: 1px solid transparent;
  padding: 0.6rem 3rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 50px;
  -webkit-transition: all 0.15s ease-in-out;
  transition: all 0.15s ease-in-out;
}

.btn:focus, .btn.focus {
  outline: 0;
  -webkit-box-shadow: 0 0 0 3px rgba(66, 146, 68, 0.25);
  box-shadow: 0 0 0 3px rgba(66, 146, 68, 0.25);
}

.btn:active, .btn.active {
  background-image: none;
}

.btn-primary {
  color: #fff;
  background-color: #429244;
  border-color: #429244;
}

.btn-primary:hover {
  color: #fff;
  background-color: #367838;
  border-color: #326f34;
}

.btn-primary:focus, .btn-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(66, 146, 68, 0.5);
  box-shadow: 0 0 0 3px rgba(66, 146, 68, 0.5);
}

.btn-primary.disabled, .btn-primary:disabled {
  background-color: #429244;
  border-color: #429244;
}

.btn-primary:active, .btn-primary.active,
.show > .btn-primary.dropdown-toggle {
  background-color: #367838;
  background-image: none;
  border-color: #326f34;
}

.btn-secondary {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:hover {
  color: #fff;
  background-color: #727b84;
  border-color: #6c757d;
}

.btn-secondary:focus, .btn-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-secondary.disabled, .btn-secondary:disabled {
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:active, .btn-secondary.active,
.show > .btn-secondary.dropdown-toggle {
  background-color: #727b84;
  background-image: none;
  border-color: #6c757d;
}

.btn-success {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:hover {
  color: #fff;
  background-color: #218838;
  border-color: #1e7e34;
}

.btn-success:focus, .btn-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-success.disabled, .btn-success:disabled {
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:active, .btn-success.active,
.show > .btn-success.dropdown-toggle {
  background-color: #218838;
  background-image: none;
  border-color: #1e7e34;
}

.btn-info {
  color: #111;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:hover {
  color: #111;
  background-color: #23bcc9;
  border-color: #21b2bf;
}

.btn-info:focus, .btn-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-info.disabled, .btn-info:disabled {
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:active, .btn-info.active,
.show > .btn-info.dropdown-toggle {
  background-color: #23bcc9;
  background-image: none;
  border-color: #21b2bf;
}

.btn-warning {
  color: #111;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:hover {
  color: #111;
  background-color: #e0a800;
  border-color: #d39e00;
}

.btn-warning:focus, .btn-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-warning.disabled, .btn-warning:disabled {
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:active, .btn-warning.active,
.show > .btn-warning.dropdown-toggle {
  background-color: #e0a800;
  background-image: none;
  border-color: #d39e00;
}

.btn-danger {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:hover {
  color: #fff;
  background-color: #c82333;
  border-color: #bd2130;
}

.btn-danger:focus, .btn-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-danger.disabled, .btn-danger:disabled {
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:active, .btn-danger.active,
.show > .btn-danger.dropdown-toggle {
  background-color: #c82333;
  background-image: none;
  border-color: #bd2130;
}

.btn-light {
  color: #111;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:hover {
  color: #111;
  background-color: #e2e6ea;
  border-color: #dae0e5;
}

.btn-light:focus, .btn-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-light.disabled, .btn-light:disabled {
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:active, .btn-light.active,
.show > .btn-light.dropdown-toggle {
  background-color: #e2e6ea;
  background-image: none;
  border-color: #dae0e5;
}

.btn-dark {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:hover {
  color: #fff;
  background-color: #23272b;
  border-color: #1d2124;
}

.btn-dark:focus, .btn-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-dark.disabled, .btn-dark:disabled {
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:active, .btn-dark.active,
.show > .btn-dark.dropdown-toggle {
  background-color: #23272b;
  background-image: none;
  border-color: #1d2124;
}

.btn-outline-primary {
  color: #429244;
  background-color: transparent;
  background-image: none;
  border-color: #429244;
}

.btn-outline-primary:hover {
  color: #fff;
  background-color: #429244;
  border-color: #429244;
}

.btn-outline-primary:focus, .btn-outline-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(66, 146, 68, 0.5);
  box-shadow: 0 0 0 3px rgba(66, 146, 68, 0.5);
}

.btn-outline-primary.disabled, .btn-outline-primary:disabled {
  color: #429244;
  background-color: transparent;
}

.btn-outline-primary:active, .btn-outline-primary.active,
.show > .btn-outline-primary.dropdown-toggle {
  color: #fff;
  background-color: #429244;
  border-color: #429244;
}

.btn-outline-secondary {
  color: #868e96;
  background-color: transparent;
  background-image: none;
  border-color: #868e96;
}

.btn-outline-secondary:hover {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-secondary:focus, .btn-outline-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
  color: #868e96;
  background-color: transparent;
}

.btn-outline-secondary:active, .btn-outline-secondary.active,
.show > .btn-outline-secondary.dropdown-toggle {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-success {
  color: #28a745;
  background-color: transparent;
  background-image: none;
  border-color: #28a745;
}

.btn-outline-success:hover {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-success:focus, .btn-outline-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-outline-success.disabled, .btn-outline-success:disabled {
  color: #28a745;
  background-color: transparent;
}

.btn-outline-success:active, .btn-outline-success.active,
.show > .btn-outline-success.dropdown-toggle {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-info {
  color: #37cfdc;
  background-color: transparent;
  background-image: none;
  border-color: #37cfdc;
}

.btn-outline-info:hover {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-info:focus, .btn-outline-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-outline-info.disabled, .btn-outline-info:disabled {
  color: #37cfdc;
  background-color: transparent;
}

.btn-outline-info:active, .btn-outline-info.active,
.show > .btn-outline-info.dropdown-toggle {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-warning {
  color: #ffc107;
  background-color: transparent;
  background-image: none;
  border-color: #ffc107;
}

.btn-outline-warning:hover {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-warning:focus, .btn-outline-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-outline-warning.disabled, .btn-outline-warning:disabled {
  color: #ffc107;
  background-color: transparent;
}

.btn-outline-warning:active, .btn-outline-warning.active,
.show > .btn-outline-warning.dropdown-toggle {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-danger {
  color: #dc3545;
  background-color: transparent;
  background-image: none;
  border-color: #dc3545;
}

.btn-outline-danger:hover {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-danger:focus, .btn-outline-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-outline-danger.disabled, .btn-outline-danger:disabled {
  color: #dc3545;
  background-color: transparent;
}

.btn-outline-danger:active, .btn-outline-danger.active,
.show > .btn-outline-danger.dropdown-toggle {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-light {
  color: #f8f9fa;
  background-color: transparent;
  background-image: none;
  border-color: #f8f9fa;
}

.btn-outline-light:hover {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-light:focus, .btn-outline-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-outline-light.disabled, .btn-outline-light:disabled {
  color: #f8f9fa;
  background-color: transparent;
}

.btn-outline-light:active, .btn-outline-light.active,
.show > .btn-outline-light.dropdown-toggle {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-dark {
  color: #343a40;
  background-color: transparent;
  background-image: none;
  border-color: #343a40;
}

.btn-outline-dark:hover {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-outline-dark:focus, .btn-outline-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-outline-dark.disabled, .btn-outline-dark:disabled {
  color: #343a40;
  background-color: transparent;
}

.btn-outline-dark:active, .btn-outline-dark.active,
.show > .btn-outline-dark.dropdown-toggle {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-lg {
  padding: 0.8rem 3.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 50px;
}

.btn-sm {
  padding: 0.4rem 1.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 50px;
}

/*
 * 3. TYPE
 */
body {
  font-family: "Open Sans", sans-serif;
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
}

a {
  color: #429244;
  text-decoration: none;
}

a:focus, a:hover {
  color: #2a5d2b;
  text-decoration: underline;
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  margin-bottom: 0.5rem;
  font-family: inherit;
  font-weight: 800;
  line-height: 1.1;
  color: #2e324a;
}

h1,
.h1 {
  font-size: 2.9rem;
}

h2,
.h2 {
  font-size: 2.2rem;
}

h3,
.h3 {
  font-size: 1.75rem;
}

h4,
.h4 {
  font-size: 1.5rem;
}

h5,
.h5 {
  font-size: 1.25rem;
}

h6,
.h6 {
  font-size: 1rem;
}

.lead {
  font-size: 1.2rem;
  font-weight: 300;
  line-height: 1.8em;
}

.display-1 {
  font-size: 6rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-2 {
  font-size: 5.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-3 {
  font-size: 4.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-4 {
  font-size: 3.5rem;
  font-weight: 300;
  line-height: 1.1;
}

hr {
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}

small,
.small {
  font-size: 80%;
  font-weight: normal;
}

mark,
.mark {
  padding: 0.2em;
  background-color: #fcf8e3;
}

.blockquote {
  padding: 3rem 2rem;
  margin-bottom: 1rem;
  font-size: 1.05rem;
  border-left: 4px solid #429244;
}

.blockquote-footer {
  color: #868e96;
}

.blockquote-footer::before {
  content: "\2014 \00A0";
}

.text-primary {
  color: #429244 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #326f34 !important;
}

/*
 * 4. PAGINATION
 */
.page-item:first-child .page-link {
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.page-item:last-child .page-link {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem;
}

.page-item.active .page-link {
  color: #fff;
  background-color: #429244;
  border-color: #429244;
}

.page-item.disabled .page-link {
  color: #868e96;
  background-color: #fff;
  border-color: #ddd;
}

.page-link {
  padding: 0.5rem 0.75rem;
  line-height: 1.25;
  color: #429244;
  background-color: #fff;
  border: 1px solid #ddd;
}

.page-link:focus, .page-link:hover {
  color: #2a5d2b;
  text-decoration: none;
  background-color: #e9ecef;
  border-color: #ddd;
}

.pagination-lg .page-link {
  padding: 0.75rem 1.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
}

.pagination-lg .page-item:first-child .page-link {
  border-top-left-radius: 0.3rem;
  border-bottom-left-radius: 0.3rem;
}

.pagination-lg .page-item:last-child .page-link {
  border-top-right-radius: 0.3rem;
  border-bottom-right-radius: 0.3rem;
}

.pagination-sm .page-link {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
}

.pagination-sm .page-item:first-child .page-link {
  border-top-left-radius: 0.2rem;
  border-bottom-left-radius: 0.2rem;
}

.pagination-sm .page-item:last-child .page-link {
  border-top-right-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem;
}

/*
* 5. UTILITIES
*/
.bg-primary {
  background-color: #429244 !important;
}

a.bg-primary:focus, a.bg-primary:hover {
  background-color: #326f34 !important;
}

.bg-secondary {
  background-color: #868e96 !important;
}

a.bg-secondary:focus, a.bg-secondary:hover {
  background-color: #6c757d !important;
}

.bg-success {
  background-color: #28a745 !important;
}

a.bg-success:focus, a.bg-success:hover {
  background-color: #1e7e34 !important;
}

.bg-info {
  background-color: #37cfdc !important;
}

a.bg-info:focus, a.bg-info:hover {
  background-color: #21b2bf !important;
}

.bg-warning {
  background-color: #ffc107 !important;
}

a.bg-warning:focus, a.bg-warning:hover {
  background-color: #d39e00 !important;
}

.bg-danger {
  background-color: #dc3545 !important;
}

a.bg-danger:focus, a.bg-danger:hover {
  background-color: #bd2130 !important;
}

.bg-light {
  background-color: #f8f9fa !important;
}

a.bg-light:focus, a.bg-light:hover {
  background-color: #dae0e5 !important;
}

.bg-dark {
  background-color: #343a40 !important;
}

a.bg-dark:focus, a.bg-dark:hover {
  background-color: #1d2124 !important;
}

.border-primary {
  border-color: #429244 !important;
}

.border-secondary {
  border-color: #868e96 !important;
}

.border-success {
  border-color: #28a745 !important;
}

.border-info {
  border-color: #37cfdc !important;
}

.border-warning {
  border-color: #ffc107 !important;
}

.border-danger {
  border-color: #dc3545 !important;
}

.border-light {
  border-color: #f8f9fa !important;
}

.border-dark {
  border-color: #343a40 !important;
}

.text-primary {
  color: #429244 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #326f34 !important;
}

.text-secondary {
  color: #868e96 !important;
}

a.text-secondary:focus, a.text-secondary:hover {
  color: #6c757d !important;
}

.text-success {
  color: #28a745 !important;
}

a.text-success:focus, a.text-success:hover {
  color: #1e7e34 !important;
}

.text-info {
  color: #37cfdc !important;
}

a.text-info:focus, a.text-info:hover {
  color: #21b2bf !important;
}

.text-warning {
  color: #ffc107 !important;
}

a.text-warning:focus, a.text-warning:hover {
  color: #d39e00 !important;
}

.text-danger {
  color: #dc3545 !important;
}

a.text-danger:focus, a.text-danger:hover {
  color: #bd2130 !important;
}

.text-light {
  color: #f8f9fa !important;
}

a.text-light:focus, a.text-light:hover {
  color: #dae0e5 !important;
}

.text-dark {
  color: #343a40 !important;
}

a.text-dark:focus, a.text-dark:hover {
  color: #1d2124 !important;
}

/*
* ==========================================================
*     GENERAL
* ==========================================================
*/
body {
  padding-top: 80px;
  position: relative;
  overflow-x: hidden;
}

section {
  padding: 150px 0;
  overflow: hidden;
}

a {
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  display: inline-block;
}

p {
  line-height: 1.7rem;
}

button {
  cursor: pointer;
}

i,
span,
strong {
  display: inline-block;
}

.bg-gray, section.browser .nav-tabs a.active {
  background: #f5f5f5;
}

.no-padding {
  padding: 0 !important;
}

.no-padding-top {
  padding-top: 0 !important;
}

.no-padding-bottom {
  padding-bottom: 0 !important;
}

.no-margin {
  margin: 0 !important;
}

.no-margin-top {
  margin-top: 0 !important;
}

.no-margin-bottom {
  margin-bottom: 0 !important;
}

.hero-text {
  font-size: 1.1rem;
  font-weight: 400;
  color: #777;
  line-height: 1.5rem;
}

.btn {
  font-size: 0.9em !important;
}

.btn-primary:focus {
  color: #fff;
}

.btn-shadow {
  -webkit-box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
  box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
}

.btn-gradient, section.browser .nav-tabs span.number {
  background-color: #ef5285;
  background-image: -webkit-gradient(linear, left top, right top, from(#ef5285), to(#7F00FF));
  background-image: linear-gradient(to right, #ef5285, #7F00FF);
  border: none !important;
  text-transform: uppercase;
  color: #fff;
  overflow: hidden;
  position: relative;
  z-index: 1;
  -webkit-transition: all 0.3s !important;
  transition: all 0.3s !important;
}

.btn.btn-gradient:hover, section.browser .nav-tabs span.btn.number:hover {
  opacity: 0.85;
}

.has-shadow {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.owl-theme .owl-nav {
  margin-top: 0;
}

.owl-theme .owl-nav [class*='owl-'] {
  background: none;
  color: #222;
  font-size: 2rem;
  margin: 0 20px;
}

.owl-theme .owl-nav [class*='owl-'].disabled {
  color: #aaa;
}

.owl-theme .owl-nav [class*='owl-']:hover {
  background: none;
  color: #333;
}

section header {
  margin-bottom: 70px;
}

.scrollUp {
  -webkit-transform: translateY(-105%);
  transform: translateY(-105%);
}

.breadcrumb {
  background: none;
  padding: 0;
  margin-bottom: 20px;
}

.breadcrumb a {
  color: #222;
  text-decoration: none !important;
}

.breadcrumb li {
  color: #aaa;
}

.block {
  margin-bottom: 50px;
}

/* Browser mockup code
 * Contribute: https://gist.github.com/jarthod/8719db9fef8deb937f4f
 * Live example: https://updown.io
 */
.browser-mockup {
  border-top: 50px solid #f7f7f7;
  position: relative;
  border-radius: 3px 3px 0 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.browser-mockup:before {
  display: block;
  position: absolute;
  content: '';
  top: -29px;
  left: 30px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: #f44;
  -webkit-box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
  box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
}

.browser-mockup.with-tab:after {
  display: block;
  position: absolute;
  content: '';
  top: -50px;
  left: 115px;
  width: 20%;
  height: 0rem;
  border-bottom: 50px solid white;
  border-left: 1.5em solid transparent;
  border-right: 1.5em solid transparent;
}

.browser-mockup.with-url:after {
  display: block;
  position: absolute;
  content: '';
  top: -1.6rem;
  left: 5.5rem;
  width: calc(100% - 6em);
  height: 1.2rem;
  border-radius: 2px;
  background-color: white;
}

.browser-mockup > * {
  display: block;
}

.blockquote {
  line-height: 1.7rem;
  color: #656565;
  padding: 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.blockquote p::first-letter {
  font-size: 2.5rem;
  color: #ef5285;
  font-weight: 800;
}

.modal {
  background: rgba(0, 0, 0, 0.8);
}

.modal button.close {
  width: 40px;
  height: 40px;
  line-height: 40px;
  color: #fff;
  text-align: center;
  background-color: #ef5285;
  background-image: -webkit-gradient(linear, left top, right top, from(#ef5285), to(#7F00FF));
  background-image: linear-gradient(to right, #ef5285, #7F00FF);
  position: absolute;
  top: 0;
  right: 0;
  opacity: 1;
}

.modal-content {
  border-radius: 0;
}

.modal-header,
.modal-body {
  padding: 20px 30px;
  border: none;
}

#signupform .form-group {
  margin-bottom: 20px;
}

#signupform label {
  display: block;
  padding-left: 10px;
  color: #656565;
  font-family: "Open Sans", sans-serif;
}

#signupform input {
  width: 100%;
  display: block;
  padding: 10px 20px;
  border-radius: 50px;
  border: 1px solid #eee;
  outline: none;
}

#signupform input:focus {
  border-color: #ef5285;
}

#signupform input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

/* General Media Query ---------------------------------- */
@media (max-width: 991px) {
  section {
    padding: 100px 0;
  }
}

/*
* ==========================================================
*     NAVBAR
* ==========================================================
*/
nav.navbar {
  padding-top: 15px;
  padding-bottom: 15px;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  background: #fff;
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

nav.navbar .navbar-brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
}

nav.navbar a.nav-link {
  color: #333;
  font-size: 1.1rem;
}

nav.navbar a.nav-link:hover, nav.navbar a.nav-link.active {
  color: #ef5285;
}

nav.navbar .navbar-btn {
  margin-left: 15px;
}

nav.navbar .navbar-toggler {
  outline: none;
}

nav.navbar .navbar-toggler span {
  width: 25px;
  margin: 5px;
  display: block;
  height: 2px;
  background: #333;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
}

nav.navbar .navbar-toggler.active span:first-of-type {
  -webkit-transform: rotate(45deg) translate(10px);
  transform: rotate(45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:last-of-type {
  -webkit-transform: rotate(-45deg) translate(10px);
  transform: rotate(-45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:nth-of-type(2) {
  opacity: 0;
}

/* Navbar Mediaquery ----------------------------------- */
@media (max-width: 1199px) {
  nav.navbar .navbar-btn {
    margin-left: 0;
  }
}

@media (min-width: 992px) {
  nav.navbar {
    padding-left: 3rem;
    padding-right: 3rem;
  }
}

/*
* ==========================================================
*     HERO SECTION
* ==========================================================
*/
section.hero p {
  margin: 20px 0;
}

section.hero .CTA {
  margin-top: 40px;
}

section.hero .CTA a {
  margin-right: 10px;
  margin-bottom: 10px;
}

/*
* ==========================================================
*     BROWSER SECTION
* ==========================================================
*/
section.browser .nav-tabs {
  margin-top: 80px;
  border: none;
}

section.browser .nav-tabs span.number {
  width: 50px;
  height: 50px;
  line-height: 50px;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  display: block;
  position: absolute;
  left: calc(50% - 25px);
  top: -25px;
  font-size: 1.4rem;
  font-weight: 700;
}

section.browser .nav-tabs a {
  border: none;
  background: none;
  border-right: 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  padding: 50px 50px 40px;
  text-align: center;
  color: #333;
}

section.browser .nav-tabs a.active {
  -webkit-transform: translateY(-20px);
  transform: translateY(-20px);
}

/* Browser Section Mediaquery --------------------------- */
@media (max-width: 767px) {
  section.browser .nav-tabs a {
    margin-bottom: 50px;
  }
  section.browser .nav-tabs a.active {
    -webkit-transform: none;
    transform: none;
  }
  section.browser .nav-tabs .row div:last-of-type a {
    margin-bottom: 0;
  }
}

/*
* ==========================================================
*     ABOUT US
* ==========================================================
*/
section.about-us p {
  margin: 30px 0;
}

/*
* ==========================================================
*     FEATURES SECTION
* ==========================================================
*/
section.features .row {
  margin-bottom: 40px;
}

section.features .row:last-of-time {
  margin-bottom: 0;
}

section.features .icon {
  width: 50px;
  height: 50px;
  margin-bottom: 30px;
}

section.features .text p {
  line-height: 1.8rem;
  font-size: 0.95rem;
  color: #656565;
  margin: 20px 0 25px;
}

/* Features Section Mediaquery -------------------------- */
@media (max-width: 1199px) {
  section.features .text {
    margin-bottom: 50px;
  }
}

/*
* ==========================================================
*     EXTRA SECTION
* ==========================================================
*/
section.extra-features {
  color: #fff;
}

section.extra-features h2,
section.extra-features h3 {
  color: inherit;
}

section.extra-features .icon {
  font-size: 2.7rem;
  margin-bottom: 20px;
}

section.extra-features .item {
  padding: 50px 30px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  cursor: default;
}

section.extra-features .item:hover {
  background: #ee447b;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

section.extra-features .item p {
  font-weight: 300;
  margin: 20px 0;
}

/*
* ==========================================================
*     TESTIMONIALS SECTION
* ==========================================================
*/
section.testimonials .owl-carousel .owl-stage-outer {
  padding: 70px 0 50px;
}

section.testimonials .item-holder {
  padding-right: 40px;
  padding-left: 40px;
}

section.testimonials .quote {
  width: 40px;
  height: 40px;
  margin-bottom: 20px;
}

section.testimonials .item {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 0 30px;
  margin-right: 0;
  padding: 70px 50px;
  padding-left: 70px;
}

section.testimonials .item p {
  line-height: 1.8rem;
  font-size: 0.9rem;
  line-height: 1.7rem;
  color: #656565;
}

section.testimonials .avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  overflow: hidden;
  position: absolute;
  top: 50%;
  left: 0;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

/* Testimonials Media Query ------------------------- */
@media (max-width: 1199px) {
  section.testimonials .item {
    -webkit-box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    padding: 60px 40px 40px;
  }
  section.testimonials .item .avatar {
    position: absolute;
    top: 0;
    left: 50%;
  }
}

/*
* ==========================================================
*     NEWSLETTER SECTION
* ==========================================================
*/
section.newsletter .form-holder {
  padding: 70px 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  margin-top: 70px;
}

section.newsletter .form-group {
  position: relative;
  margin-bottom: 0;
}

section.newsletter .form-group input {
  width: 100%;
  height: 68px;
  line-height: 68px;
  border: 1px solid #ddd;
  border-radius: 50px;
  background: none;
  outline: none;
  padding: 0 30px;
  font-family: "Open Sans", sans-serif;
}

section.newsletter .form-group input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group .submit {
  height: 54px;
  line-height: 54px;
  padding-top: 0;
  padding-bottom: 0;
  position: absolute;
  top: 7px;
  right: 7px;
}

/* Newsletter Section Mediaquery -------------------------- */
@media (max-width: 991px) {
  section.newsletter .form-group input {
    width: 100%;
  }
  section.newsletter .form-group .submit {
    width: 100%;
    position: static;
    margin-top: 15px;
  }
}

/*
* ==========================================================
*     FOOTER
* ==========================================================
*/
footer.main-footer {
  padding: 150px 0 0;
  overflow-x: hidden;
}

footer.main-footer a {
  color: inherit;
  text-decoration: none;
}

footer.main-footer .brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
  margin-bottom: 20px;
}

footer.main-footer ul.contact-info {
  color: #444;
}

footer.main-footer ul.contact-info a {
  margin-bottom: 5px;
}

footer.main-footer ul.contact-info a:hover {
  color: #ef5285;
}

footer.main-footer h5 {
  margin-bottom: 30px;
}

footer.main-footer ul.links {
  color: #888;
}

footer.main-footer ul.links a {
  margin-bottom: 8px;
}

footer.main-footer ul.links a:hover {
  color: #ef5285;
}

footer.main-footer ul.social-icons {
  margin-top: 15px;
  margin-bottom: 50px;
}

footer.main-footer ul.social-icons a {
  width: 26px;
  height: 26px;
  line-height: 26px;
  background: #222;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  font-size: 0.8rem;
}

footer.main-footer ul.social-icons a:hover {
  background: #ef5285;
}

footer.main-footer .copyrights {
  margin-top: 150px;
}

footer.main-footer .copyrights .container {
  padding: 30px 0;
  border-top: 1px solid #ddd;
}

footer.main-footer .copyrights p {
  margin-bottom: 0;
}

footer.main-footer .copyrights a:hover {
  color: #ef5285;
}

/* Footer Mediaquery -------------------------- */
@media (max-width: 991px) {
  footer.main-footer {
    padding: 100px 0 0;
  }
  footer.main-footer .copyrights {
    margin-top: 100px;
  }
  footer.main-footer .copyrights div[class*="col-"] {
    text-align: center !important;
  }
}

/* ===================================================================
    SCROLL TO TOP BUTTON
===================================================================  */
#scrollTop {
  width: 80px;
  height: 40px;
  position: fixed;
  right: -90px;
  bottom: 50%;
  background-color: #ef5285;
  background-image: -webkit-gradient(linear, left top, right top, from(#ef5285), to(#7F00FF));
  background-image: linear-gradient(to right, #ef5285, #7F00FF);
  color: #fff;
  text-align: center;
  line-height: 40px;
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
  -webkit-box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  font-size: 0.7rem;
  cursor: pointer;
  z-index: 9998;
  padding-right: 10px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

#scrollTop.active {
  right: -50px;
}

#scrollTop i {
  font-size: 1.1rem;
  margin-right: 10px;
}

#scrollTop:hover {
  right: 0;
}

/* Scroll Top Media Query ------------------------- */
@media (max-width: 1199px) {
  #scrollTop {
    display: none !important;
  }
}

/*

=====================
STYLE SWITCHER FOR DEMO
=====================

*/
#style-switch-button {
  position: fixed;
  top: 120px;
  left: 0px;
  border-radius: 0;
  z-index: 2;
}

#style-switch {
  width: 300px;
  padding: 20px;
  position: fixed;
  top: 160px;
  left: 0;
  background: #fff;
  border: solid 1px #ced4da;
  z-index: 2000;
}

#style-switch h4 {
  color: #495057;
}

/* =========================================
   THEMING OF BOOTSTRAP COMPONENTS
   ========================================= */
/*
 * 1. NAVBAR
 */
.navbar {
  padding: 0.5rem 1rem;
}

.navbar-brand {
  display: inline-block;
  padding-top: 0.3125rem;
  padding-bottom: 0.3125rem;
  margin-right: 1rem;
  font-size: 1.25rem;
}

.navbar-toggler {
  padding: 0.25rem 0.75rem;
  font-size: 1.25rem;
  line-height: 1;
  border: 1px solid transparent;
  border-radius: 50px;
}

.navbar-light .navbar-brand {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-brand:focus, .navbar-light .navbar-brand:hover {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-nav .nav-link:focus, .navbar-light .navbar-nav .nav-link:hover {
  color: rgba(0, 0, 0, 0.7);
}

.navbar-light .navbar-nav .nav-link.disabled {
  color: rgba(0, 0, 0, 0.3);
}

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0.5);
  border-color: rgba(0, 0, 0, 0.1);
}

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-light .navbar-text {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-dark .navbar-brand {
  color: white;
}

.navbar-dark .navbar-brand:focus, .navbar-dark .navbar-brand:hover {
  color: white;
}

.navbar-dark .navbar-nav .nav-link {
  color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
  color: rgba(255, 255, 255, 0.75);
}

.navbar-dark .navbar-nav .nav-link.disabled {
  color: rgba(255, 255, 255, 0.25);
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: white;
}

.navbar-dark .navbar-toggler {
  color: rgba(255, 255, 255, 0.5);
  border-color: rgba(255, 255, 255, 0.1);
}

.navbar-dark .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-dark .navbar-text {
  color: rgba(255, 255, 255, 0.5);
}

/*
 * 2. BUTTONS
 */
.btn {
  font-weight: 400;
  border: 1px solid transparent;
  padding: 0.6rem 3rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 50px;
  -webkit-transition: all 0.15s ease-in-out;
  transition: all 0.15s ease-in-out;
}

.btn:focus, .btn.focus {
  outline: 0;
  -webkit-box-shadow: 0 0 0 3px rgba(239, 82, 133, 0.25);
  box-shadow: 0 0 0 3px rgba(239, 82, 133, 0.25);
}

.btn:active, .btn.active {
  background-image: none;
}

.btn-primary {
  color: #fff;
  background-color: #ef5285;
  border-color: #ef5285;
}

.btn-primary:hover {
  color: #fff;
  background-color: #ec2f6c;
  border-color: #eb2364;
}

.btn-primary:focus, .btn-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(239, 82, 133, 0.5);
  box-shadow: 0 0 0 3px rgba(239, 82, 133, 0.5);
}

.btn-primary.disabled, .btn-primary:disabled {
  background-color: #ef5285;
  border-color: #ef5285;
}

.btn-primary:active, .btn-primary.active,
.show > .btn-primary.dropdown-toggle {
  background-color: #ec2f6c;
  background-image: none;
  border-color: #eb2364;
}

.btn-secondary {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:hover {
  color: #fff;
  background-color: #727b84;
  border-color: #6c757d;
}

.btn-secondary:focus, .btn-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-secondary.disabled, .btn-secondary:disabled {
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:active, .btn-secondary.active,
.show > .btn-secondary.dropdown-toggle {
  background-color: #727b84;
  background-image: none;
  border-color: #6c757d;
}

.btn-success {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:hover {
  color: #fff;
  background-color: #218838;
  border-color: #1e7e34;
}

.btn-success:focus, .btn-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-success.disabled, .btn-success:disabled {
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:active, .btn-success.active,
.show > .btn-success.dropdown-toggle {
  background-color: #218838;
  background-image: none;
  border-color: #1e7e34;
}

.btn-info {
  color: #111;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:hover {
  color: #111;
  background-color: #23bcc9;
  border-color: #21b2bf;
}

.btn-info:focus, .btn-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-info.disabled, .btn-info:disabled {
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:active, .btn-info.active,
.show > .btn-info.dropdown-toggle {
  background-color: #23bcc9;
  background-image: none;
  border-color: #21b2bf;
}

.btn-warning {
  color: #111;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:hover {
  color: #111;
  background-color: #e0a800;
  border-color: #d39e00;
}

.btn-warning:focus, .btn-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-warning.disabled, .btn-warning:disabled {
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:active, .btn-warning.active,
.show > .btn-warning.dropdown-toggle {
  background-color: #e0a800;
  background-image: none;
  border-color: #d39e00;
}

.btn-danger {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:hover {
  color: #fff;
  background-color: #c82333;
  border-color: #bd2130;
}

.btn-danger:focus, .btn-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-danger.disabled, .btn-danger:disabled {
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:active, .btn-danger.active,
.show > .btn-danger.dropdown-toggle {
  background-color: #c82333;
  background-image: none;
  border-color: #bd2130;
}

.btn-light {
  color: #111;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:hover {
  color: #111;
  background-color: #e2e6ea;
  border-color: #dae0e5;
}

.btn-light:focus, .btn-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-light.disabled, .btn-light:disabled {
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:active, .btn-light.active,
.show > .btn-light.dropdown-toggle {
  background-color: #e2e6ea;
  background-image: none;
  border-color: #dae0e5;
}

.btn-dark {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:hover {
  color: #fff;
  background-color: #23272b;
  border-color: #1d2124;
}

.btn-dark:focus, .btn-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-dark.disabled, .btn-dark:disabled {
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:active, .btn-dark.active,
.show > .btn-dark.dropdown-toggle {
  background-color: #23272b;
  background-image: none;
  border-color: #1d2124;
}

.btn-outline-primary {
  color: #ef5285;
  background-color: transparent;
  background-image: none;
  border-color: #ef5285;
}

.btn-outline-primary:hover {
  color: #fff;
  background-color: #ef5285;
  border-color: #ef5285;
}

.btn-outline-primary:focus, .btn-outline-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(239, 82, 133, 0.5);
  box-shadow: 0 0 0 3px rgba(239, 82, 133, 0.5);
}

.btn-outline-primary.disabled, .btn-outline-primary:disabled {
  color: #ef5285;
  background-color: transparent;
}

.btn-outline-primary:active, .btn-outline-primary.active,
.show > .btn-outline-primary.dropdown-toggle {
  color: #fff;
  background-color: #ef5285;
  border-color: #ef5285;
}

.btn-outline-secondary {
  color: #868e96;
  background-color: transparent;
  background-image: none;
  border-color: #868e96;
}

.btn-outline-secondary:hover {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-secondary:focus, .btn-outline-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
  color: #868e96;
  background-color: transparent;
}

.btn-outline-secondary:active, .btn-outline-secondary.active,
.show > .btn-outline-secondary.dropdown-toggle {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-success {
  color: #28a745;
  background-color: transparent;
  background-image: none;
  border-color: #28a745;
}

.btn-outline-success:hover {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-success:focus, .btn-outline-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-outline-success.disabled, .btn-outline-success:disabled {
  color: #28a745;
  background-color: transparent;
}

.btn-outline-success:active, .btn-outline-success.active,
.show > .btn-outline-success.dropdown-toggle {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-info {
  color: #37cfdc;
  background-color: transparent;
  background-image: none;
  border-color: #37cfdc;
}

.btn-outline-info:hover {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-info:focus, .btn-outline-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-outline-info.disabled, .btn-outline-info:disabled {
  color: #37cfdc;
  background-color: transparent;
}

.btn-outline-info:active, .btn-outline-info.active,
.show > .btn-outline-info.dropdown-toggle {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-warning {
  color: #ffc107;
  background-color: transparent;
  background-image: none;
  border-color: #ffc107;
}

.btn-outline-warning:hover {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-warning:focus, .btn-outline-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-outline-warning.disabled, .btn-outline-warning:disabled {
  color: #ffc107;
  background-color: transparent;
}

.btn-outline-warning:active, .btn-outline-warning.active,
.show > .btn-outline-warning.dropdown-toggle {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-danger {
  color: #dc3545;
  background-color: transparent;
  background-image: none;
  border-color: #dc3545;
}

.btn-outline-danger:hover {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-danger:focus, .btn-outline-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-outline-danger.disabled, .btn-outline-danger:disabled {
  color: #dc3545;
  background-color: transparent;
}

.btn-outline-danger:active, .btn-outline-danger.active,
.show > .btn-outline-danger.dropdown-toggle {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-light {
  color: #f8f9fa;
  background-color: transparent;
  background-image: none;
  border-color: #f8f9fa;
}

.btn-outline-light:hover {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-light:focus, .btn-outline-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-outline-light.disabled, .btn-outline-light:disabled {
  color: #f8f9fa;
  background-color: transparent;
}

.btn-outline-light:active, .btn-outline-light.active,
.show > .btn-outline-light.dropdown-toggle {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-dark {
  color: #343a40;
  background-color: transparent;
  background-image: none;
  border-color: #343a40;
}

.btn-outline-dark:hover {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-outline-dark:focus, .btn-outline-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-outline-dark.disabled, .btn-outline-dark:disabled {
  color: #343a40;
  background-color: transparent;
}

.btn-outline-dark:active, .btn-outline-dark.active,
.show > .btn-outline-dark.dropdown-toggle {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-lg {
  padding: 0.8rem 3.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 50px;
}

.btn-sm {
  padding: 0.4rem 1.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 50px;
}

/*
 * 3. TYPE
 */
body {
  font-family: "Open Sans", sans-serif;
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
}

a {
  color: #ef5285;
  text-decoration: none;
}

a:focus, a:hover {
  color: #e01557;
  text-decoration: underline;
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  margin-bottom: 0.5rem;
  font-family: inherit;
  font-weight: 800;
  line-height: 1.1;
  color: #2e324a;
}

h1,
.h1 {
  font-size: 2.9rem;
}

h2,
.h2 {
  font-size: 2.2rem;
}

h3,
.h3 {
  font-size: 1.75rem;
}

h4,
.h4 {
  font-size: 1.5rem;
}

h5,
.h5 {
  font-size: 1.25rem;
}

h6,
.h6 {
  font-size: 1rem;
}

.lead {
  font-size: 1.2rem;
  font-weight: 300;
  line-height: 1.8em;
}

.display-1 {
  font-size: 6rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-2 {
  font-size: 5.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-3 {
  font-size: 4.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-4 {
  font-size: 3.5rem;
  font-weight: 300;
  line-height: 1.1;
}

hr {
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}

small,
.small {
  font-size: 80%;
  font-weight: normal;
}

mark,
.mark {
  padding: 0.2em;
  background-color: #fcf8e3;
}

.blockquote {
  padding: 3rem 2rem;
  margin-bottom: 1rem;
  font-size: 1.05rem;
  border-left: 4px solid #ef5285;
}

.blockquote-footer {
  color: #868e96;
}

.blockquote-footer::before {
  content: "\2014 \00A0";
}

.text-primary {
  color: #ef5285 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #eb2364 !important;
}

/*
 * 4. PAGINATION
 */
.page-item:first-child .page-link {
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.page-item:last-child .page-link {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem;
}

.page-item.active .page-link {
  color: #fff;
  background-color: #ef5285;
  border-color: #ef5285;
}

.page-item.disabled .page-link {
  color: #868e96;
  background-color: #fff;
  border-color: #ddd;
}

.page-link {
  padding: 0.5rem 0.75rem;
  line-height: 1.25;
  color: #ef5285;
  background-color: #fff;
  border: 1px solid #ddd;
}

.page-link:focus, .page-link:hover {
  color: #e01557;
  text-decoration: none;
  background-color: #e9ecef;
  border-color: #ddd;
}

.pagination-lg .page-link {
  padding: 0.75rem 1.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
}

.pagination-lg .page-item:first-child .page-link {
  border-top-left-radius: 0.3rem;
  border-bottom-left-radius: 0.3rem;
}

.pagination-lg .page-item:last-child .page-link {
  border-top-right-radius: 0.3rem;
  border-bottom-right-radius: 0.3rem;
}

.pagination-sm .page-link {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
}

.pagination-sm .page-item:first-child .page-link {
  border-top-left-radius: 0.2rem;
  border-bottom-left-radius: 0.2rem;
}

.pagination-sm .page-item:last-child .page-link {
  border-top-right-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem;
}

/*
* 5. UTILITIES
*/
.bg-primary {
  background-color: #ef5285 !important;
}

a.bg-primary:focus, a.bg-primary:hover {
  background-color: #eb2364 !important;
}

.bg-secondary {
  background-color: #868e96 !important;
}

a.bg-secondary:focus, a.bg-secondary:hover {
  background-color: #6c757d !important;
}

.bg-success {
  background-color: #28a745 !important;
}

a.bg-success:focus, a.bg-success:hover {
  background-color: #1e7e34 !important;
}

.bg-info {
  background-color: #37cfdc !important;
}

a.bg-info:focus, a.bg-info:hover {
  background-color: #21b2bf !important;
}

.bg-warning {
  background-color: #ffc107 !important;
}

a.bg-warning:focus, a.bg-warning:hover {
  background-color: #d39e00 !important;
}

.bg-danger {
  background-color: #dc3545 !important;
}

a.bg-danger:focus, a.bg-danger:hover {
  background-color: #bd2130 !important;
}

.bg-light {
  background-color: #f8f9fa !important;
}

a.bg-light:focus, a.bg-light:hover {
  background-color: #dae0e5 !important;
}

.bg-dark {
  background-color: #343a40 !important;
}

a.bg-dark:focus, a.bg-dark:hover {
  background-color: #1d2124 !important;
}

.border-primary {
  border-color: #ef5285 !important;
}

.border-secondary {
  border-color: #868e96 !important;
}

.border-success {
  border-color: #28a745 !important;
}

.border-info {
  border-color: #37cfdc !important;
}

.border-warning {
  border-color: #ffc107 !important;
}

.border-danger {
  border-color: #dc3545 !important;
}

.border-light {
  border-color: #f8f9fa !important;
}

.border-dark {
  border-color: #343a40 !important;
}

.text-primary {
  color: #ef5285 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #eb2364 !important;
}

.text-secondary {
  color: #868e96 !important;
}

a.text-secondary:focus, a.text-secondary:hover {
  color: #6c757d !important;
}

.text-success {
  color: #28a745 !important;
}

a.text-success:focus, a.text-success:hover {
  color: #1e7e34 !important;
}

.text-info {
  color: #37cfdc !important;
}

a.text-info:focus, a.text-info:hover {
  color: #21b2bf !important;
}

.text-warning {
  color: #ffc107 !important;
}

a.text-warning:focus, a.text-warning:hover {
  color: #d39e00 !important;
}

.text-danger {
  color: #dc3545 !important;
}

a.text-danger:focus, a.text-danger:hover {
  color: #bd2130 !important;
}

.text-light {
  color: #f8f9fa !important;
}

a.text-light:focus, a.text-light:hover {
  color: #dae0e5 !important;
}

.text-dark {
  color: #343a40 !important;
}

a.text-dark:focus, a.text-dark:hover {
  color: #1d2124 !important;
}

/*
* ==========================================================
*     GENERAL
* ==========================================================
*/
body {
  padding-top: 80px;
  position: relative;
  overflow-x: hidden;
}

section {
  padding: 150px 0;
  overflow: hidden;
}

a {
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  display: inline-block;
}

p {
  line-height: 1.7rem;
}

button {
  cursor: pointer;
}

i,
span,
strong {
  display: inline-block;
}

.bg-gray, section.browser .nav-tabs a.active {
  background: #f5f5f5;
}

.no-padding {
  padding: 0 !important;
}

.no-padding-top {
  padding-top: 0 !important;
}

.no-padding-bottom {
  padding-bottom: 0 !important;
}

.no-margin {
  margin: 0 !important;
}

.no-margin-top {
  margin-top: 0 !important;
}

.no-margin-bottom {
  margin-bottom: 0 !important;
}

.hero-text {
  font-size: 1.1rem;
  font-weight: 400;
  color: #777;
  line-height: 1.5rem;
}

.btn {
  font-size: 0.9em !important;
}

.btn-primary:focus {
  color: #fff;
}

.btn-shadow {
  -webkit-box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
  box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
}

.btn-gradient, section.browser .nav-tabs span.number {
  background-color: #E04444;
  background-image: -webkit-gradient(linear, left top, right top, from(#E04444), to(#DD2476));
  background-image: linear-gradient(to right, #E04444, #DD2476);
  border: none !important;
  text-transform: uppercase;
  color: #fff;
  overflow: hidden;
  position: relative;
  z-index: 1;
  -webkit-transition: all 0.3s !important;
  transition: all 0.3s !important;
}

.btn.btn-gradient:hover, section.browser .nav-tabs span.btn.number:hover {
  opacity: 0.85;
}

.has-shadow {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.owl-theme .owl-nav {
  margin-top: 0;
}

.owl-theme .owl-nav [class*='owl-'] {
  background: none;
  color: #222;
  font-size: 2rem;
  margin: 0 20px;
}

.owl-theme .owl-nav [class*='owl-'].disabled {
  color: #aaa;
}

.owl-theme .owl-nav [class*='owl-']:hover {
  background: none;
  color: #333;
}

section header {
  margin-bottom: 70px;
}

.scrollUp {
  -webkit-transform: translateY(-105%);
  transform: translateY(-105%);
}

.breadcrumb {
  background: none;
  padding: 0;
  margin-bottom: 20px;
}

.breadcrumb a {
  color: #222;
  text-decoration: none !important;
}

.breadcrumb li {
  color: #aaa;
}

.block {
  margin-bottom: 50px;
}

/* Browser mockup code
 * Contribute: https://gist.github.com/jarthod/8719db9fef8deb937f4f
 * Live example: https://updown.io
 */
.browser-mockup {
  border-top: 50px solid #f7f7f7;
  position: relative;
  border-radius: 3px 3px 0 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.browser-mockup:before {
  display: block;
  position: absolute;
  content: '';
  top: -29px;
  left: 30px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: #f44;
  -webkit-box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
  box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
}

.browser-mockup.with-tab:after {
  display: block;
  position: absolute;
  content: '';
  top: -50px;
  left: 115px;
  width: 20%;
  height: 0rem;
  border-bottom: 50px solid white;
  border-left: 1.5em solid transparent;
  border-right: 1.5em solid transparent;
}

.browser-mockup.with-url:after {
  display: block;
  position: absolute;
  content: '';
  top: -1.6rem;
  left: 5.5rem;
  width: calc(100% - 6em);
  height: 1.2rem;
  border-radius: 2px;
  background-color: white;
}

.browser-mockup > * {
  display: block;
}

.blockquote {
  line-height: 1.7rem;
  color: #656565;
  padding: 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.blockquote p::first-letter {
  font-size: 2.5rem;
  color: #E04444;
  font-weight: 800;
}

.modal {
  background: rgba(0, 0, 0, 0.8);
}

.modal button.close {
  width: 40px;
  height: 40px;
  line-height: 40px;
  color: #fff;
  text-align: center;
  background-color: #E04444;
  background-image: -webkit-gradient(linear, left top, right top, from(#E04444), to(#DD2476));
  background-image: linear-gradient(to right, #E04444, #DD2476);
  position: absolute;
  top: 0;
  right: 0;
  opacity: 1;
}

.modal-content {
  border-radius: 0;
}

.modal-header,
.modal-body {
  padding: 20px 30px;
  border: none;
}

#signupform .form-group {
  margin-bottom: 20px;
}

#signupform label {
  display: block;
  padding-left: 10px;
  color: #656565;
  font-family: "Open Sans", sans-serif;
}

#signupform input {
  width: 100%;
  display: block;
  padding: 10px 20px;
  border-radius: 50px;
  border: 1px solid #eee;
  outline: none;
}

#signupform input:focus {
  border-color: #E04444;
}

#signupform input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

/* General Media Query ---------------------------------- */
@media (max-width: 991px) {
  section {
    padding: 100px 0;
  }
}

/*
* ==========================================================
*     NAVBAR
* ==========================================================
*/
nav.navbar {
  padding-top: 15px;
  padding-bottom: 15px;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  background: #fff;
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

nav.navbar .navbar-brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
}

nav.navbar a.nav-link {
  color: #333;
  font-size: 1.1rem;
}

nav.navbar a.nav-link:hover, nav.navbar a.nav-link.active {
  color: #E04444;
}

nav.navbar .navbar-btn {
  margin-left: 15px;
}

nav.navbar .navbar-toggler {
  outline: none;
}

nav.navbar .navbar-toggler span {
  width: 25px;
  margin: 5px;
  display: block;
  height: 2px;
  background: #333;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
}

nav.navbar .navbar-toggler.active span:first-of-type {
  -webkit-transform: rotate(45deg) translate(10px);
  transform: rotate(45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:last-of-type {
  -webkit-transform: rotate(-45deg) translate(10px);
  transform: rotate(-45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:nth-of-type(2) {
  opacity: 0;
}

/* Navbar Mediaquery ----------------------------------- */
@media (max-width: 1199px) {
  nav.navbar .navbar-btn {
    margin-left: 0;
  }
}

@media (min-width: 992px) {
  nav.navbar {
    padding-left: 3rem;
    padding-right: 3rem;
  }
}

/*
* ==========================================================
*     HERO SECTION
* ==========================================================
*/
section.hero p {
  margin: 20px 0;
}

section.hero .CTA {
  margin-top: 40px;
}

section.hero .CTA a {
  margin-right: 10px;
  margin-bottom: 10px;
}

/*
* ==========================================================
*     BROWSER SECTION
* ==========================================================
*/
section.browser .nav-tabs {
  margin-top: 80px;
  border: none;
}

section.browser .nav-tabs span.number {
  width: 50px;
  height: 50px;
  line-height: 50px;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  display: block;
  position: absolute;
  left: calc(50% - 25px);
  top: -25px;
  font-size: 1.4rem;
  font-weight: 700;
}

section.browser .nav-tabs a {
  border: none;
  background: none;
  border-right: 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  padding: 50px 50px 40px;
  text-align: center;
  color: #333;
}

section.browser .nav-tabs a.active {
  -webkit-transform: translateY(-20px);
  transform: translateY(-20px);
}

/* Browser Section Mediaquery --------------------------- */
@media (max-width: 767px) {
  section.browser .nav-tabs a {
    margin-bottom: 50px;
  }
  section.browser .nav-tabs a.active {
    -webkit-transform: none;
    transform: none;
  }
  section.browser .nav-tabs .row div:last-of-type a {
    margin-bottom: 0;
  }
}

/*
* ==========================================================
*     ABOUT US
* ==========================================================
*/
section.about-us p {
  margin: 30px 0;
}

/*
* ==========================================================
*     FEATURES SECTION
* ==========================================================
*/
section.features .row {
  margin-bottom: 40px;
}

section.features .row:last-of-time {
  margin-bottom: 0;
}

section.features .icon {
  width: 50px;
  height: 50px;
  margin-bottom: 30px;
}

section.features .text p {
  line-height: 1.8rem;
  font-size: 0.95rem;
  color: #656565;
  margin: 20px 0 25px;
}

/* Features Section Mediaquery -------------------------- */
@media (max-width: 1199px) {
  section.features .text {
    margin-bottom: 50px;
  }
}

/*
* ==========================================================
*     EXTRA SECTION
* ==========================================================
*/
section.extra-features {
  color: #fff;
}

section.extra-features h2,
section.extra-features h3 {
  color: inherit;
}

section.extra-features .icon {
  font-size: 2.7rem;
  margin-bottom: 20px;
}

section.extra-features .item {
  padding: 50px 30px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  cursor: default;
}

section.extra-features .item:hover {
  background: #de3737;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

section.extra-features .item p {
  font-weight: 300;
  margin: 20px 0;
}

/*
* ==========================================================
*     TESTIMONIALS SECTION
* ==========================================================
*/
section.testimonials .owl-carousel .owl-stage-outer {
  padding: 70px 0 50px;
}

section.testimonials .item-holder {
  padding-right: 40px;
  padding-left: 40px;
}

section.testimonials .quote {
  width: 40px;
  height: 40px;
  margin-bottom: 20px;
}

section.testimonials .item {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 0 30px;
  margin-right: 0;
  padding: 70px 50px;
  padding-left: 70px;
}

section.testimonials .item p {
  line-height: 1.8rem;
  font-size: 0.9rem;
  line-height: 1.7rem;
  color: #656565;
}

section.testimonials .avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  overflow: hidden;
  position: absolute;
  top: 50%;
  left: 0;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

/* Testimonials Media Query ------------------------- */
@media (max-width: 1199px) {
  section.testimonials .item {
    -webkit-box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    padding: 60px 40px 40px;
  }
  section.testimonials .item .avatar {
    position: absolute;
    top: 0;
    left: 50%;
  }
}

/*
* ==========================================================
*     NEWSLETTER SECTION
* ==========================================================
*/
section.newsletter .form-holder {
  padding: 70px 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  margin-top: 70px;
}

section.newsletter .form-group {
  position: relative;
  margin-bottom: 0;
}

section.newsletter .form-group input {
  width: 100%;
  height: 68px;
  line-height: 68px;
  border: 1px solid #ddd;
  border-radius: 50px;
  background: none;
  outline: none;
  padding: 0 30px;
  font-family: "Open Sans", sans-serif;
}

section.newsletter .form-group input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group .submit {
  height: 54px;
  line-height: 54px;
  padding-top: 0;
  padding-bottom: 0;
  position: absolute;
  top: 7px;
  right: 7px;
}

/* Newsletter Section Mediaquery -------------------------- */
@media (max-width: 991px) {
  section.newsletter .form-group input {
    width: 100%;
  }
  section.newsletter .form-group .submit {
    width: 100%;
    position: static;
    margin-top: 15px;
  }
}

/*
* ==========================================================
*     FOOTER
* ==========================================================
*/
footer.main-footer {
  padding: 150px 0 0;
  overflow-x: hidden;
}

footer.main-footer a {
  color: inherit;
  text-decoration: none;
}

footer.main-footer .brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
  margin-bottom: 20px;
}

footer.main-footer ul.contact-info {
  color: #444;
}

footer.main-footer ul.contact-info a {
  margin-bottom: 5px;
}

footer.main-footer ul.contact-info a:hover {
  color: #E04444;
}

footer.main-footer h5 {
  margin-bottom: 30px;
}

footer.main-footer ul.links {
  color: #888;
}

footer.main-footer ul.links a {
  margin-bottom: 8px;
}

footer.main-footer ul.links a:hover {
  color: #E04444;
}

footer.main-footer ul.social-icons {
  margin-top: 15px;
  margin-bottom: 50px;
}

footer.main-footer ul.social-icons a {
  width: 26px;
  height: 26px;
  line-height: 26px;
  background: #222;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  font-size: 0.8rem;
}

footer.main-footer ul.social-icons a:hover {
  background: #E04444;
}

footer.main-footer .copyrights {
  margin-top: 150px;
}

footer.main-footer .copyrights .container {
  padding: 30px 0;
  border-top: 1px solid #ddd;
}

footer.main-footer .copyrights p {
  margin-bottom: 0;
}

footer.main-footer .copyrights a:hover {
  color: #E04444;
}

/* Footer Mediaquery -------------------------- */
@media (max-width: 991px) {
  footer.main-footer {
    padding: 100px 0 0;
  }
  footer.main-footer .copyrights {
    margin-top: 100px;
  }
  footer.main-footer .copyrights div[class*="col-"] {
    text-align: center !important;
  }
}

/* ===================================================================
    SCROLL TO TOP BUTTON
===================================================================  */
#scrollTop {
  width: 80px;
  height: 40px;
  position: fixed;
  right: -90px;
  bottom: 50%;
  background-color: #E04444;
  background-image: -webkit-gradient(linear, left top, right top, from(#E04444), to(#DD2476));
  background-image: linear-gradient(to right, #E04444, #DD2476);
  color: #fff;
  text-align: center;
  line-height: 40px;
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
  -webkit-box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  font-size: 0.7rem;
  cursor: pointer;
  z-index: 9998;
  padding-right: 10px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

#scrollTop.active {
  right: -50px;
}

#scrollTop i {
  font-size: 1.1rem;
  margin-right: 10px;
}

#scrollTop:hover {
  right: 0;
}

/* Scroll Top Media Query ------------------------- */
@media (max-width: 1199px) {
  #scrollTop {
    display: none !important;
  }
}

/*

=====================
STYLE SWITCHER FOR DEMO
=====================

*/
#style-switch-button {
  position: fixed;
  top: 120px;
  left: 0px;
  border-radius: 0;
  z-index: 2;
}

#style-switch {
  width: 300px;
  padding: 20px;
  position: fixed;
  top: 160px;
  left: 0;
  background: #fff;
  border: solid 1px #ced4da;
  z-index: 2000;
}

#style-switch h4 {
  color: #495057;
}

/* =========================================
   THEMING OF BOOTSTRAP COMPONENTS
   ========================================= */
/*
 * 1. NAVBAR
 */
.navbar {
  padding: 0.5rem 1rem;
}

.navbar-brand {
  display: inline-block;
  padding-top: 0.3125rem;
  padding-bottom: 0.3125rem;
  margin-right: 1rem;
  font-size: 1.25rem;
}

.navbar-toggler {
  padding: 0.25rem 0.75rem;
  font-size: 1.25rem;
  line-height: 1;
  border: 1px solid transparent;
  border-radius: 50px;
}

.navbar-light .navbar-brand {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-brand:focus, .navbar-light .navbar-brand:hover {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-nav .nav-link:focus, .navbar-light .navbar-nav .nav-link:hover {
  color: rgba(0, 0, 0, 0.7);
}

.navbar-light .navbar-nav .nav-link.disabled {
  color: rgba(0, 0, 0, 0.3);
}

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0.5);
  border-color: rgba(0, 0, 0, 0.1);
}

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-light .navbar-text {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-dark .navbar-brand {
  color: white;
}

.navbar-dark .navbar-brand:focus, .navbar-dark .navbar-brand:hover {
  color: white;
}

.navbar-dark .navbar-nav .nav-link {
  color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
  color: rgba(255, 255, 255, 0.75);
}

.navbar-dark .navbar-nav .nav-link.disabled {
  color: rgba(255, 255, 255, 0.25);
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: white;
}

.navbar-dark .navbar-toggler {
  color: rgba(255, 255, 255, 0.5);
  border-color: rgba(255, 255, 255, 0.1);
}

.navbar-dark .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-dark .navbar-text {
  color: rgba(255, 255, 255, 0.5);
}

/*
 * 2. BUTTONS
 */
.btn {
  font-weight: 400;
  border: 1px solid transparent;
  padding: 0.6rem 3rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 50px;
  -webkit-transition: all 0.15s ease-in-out;
  transition: all 0.15s ease-in-out;
}

.btn:focus, .btn.focus {
  outline: 0;
  -webkit-box-shadow: 0 0 0 3px rgba(224, 68, 68, 0.25);
  box-shadow: 0 0 0 3px rgba(224, 68, 68, 0.25);
}

.btn:active, .btn.active {
  background-image: none;
}

.btn-primary {
  color: #fff;
  background-color: #E04444;
  border-color: #E04444;
}

.btn-primary:hover {
  color: #fff;
  background-color: #da2424;
  border-color: #cf2222;
}

.btn-primary:focus, .btn-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(224, 68, 68, 0.5);
  box-shadow: 0 0 0 3px rgba(224, 68, 68, 0.5);
}

.btn-primary.disabled, .btn-primary:disabled {
  background-color: #E04444;
  border-color: #E04444;
}

.btn-primary:active, .btn-primary.active,
.show > .btn-primary.dropdown-toggle {
  background-color: #da2424;
  background-image: none;
  border-color: #cf2222;
}

.btn-secondary {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:hover {
  color: #fff;
  background-color: #727b84;
  border-color: #6c757d;
}

.btn-secondary:focus, .btn-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-secondary.disabled, .btn-secondary:disabled {
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:active, .btn-secondary.active,
.show > .btn-secondary.dropdown-toggle {
  background-color: #727b84;
  background-image: none;
  border-color: #6c757d;
}

.btn-success {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:hover {
  color: #fff;
  background-color: #218838;
  border-color: #1e7e34;
}

.btn-success:focus, .btn-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-success.disabled, .btn-success:disabled {
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:active, .btn-success.active,
.show > .btn-success.dropdown-toggle {
  background-color: #218838;
  background-image: none;
  border-color: #1e7e34;
}

.btn-info {
  color: #111;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:hover {
  color: #111;
  background-color: #23bcc9;
  border-color: #21b2bf;
}

.btn-info:focus, .btn-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-info.disabled, .btn-info:disabled {
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:active, .btn-info.active,
.show > .btn-info.dropdown-toggle {
  background-color: #23bcc9;
  background-image: none;
  border-color: #21b2bf;
}

.btn-warning {
  color: #111;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:hover {
  color: #111;
  background-color: #e0a800;
  border-color: #d39e00;
}

.btn-warning:focus, .btn-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-warning.disabled, .btn-warning:disabled {
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:active, .btn-warning.active,
.show > .btn-warning.dropdown-toggle {
  background-color: #e0a800;
  background-image: none;
  border-color: #d39e00;
}

.btn-danger {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:hover {
  color: #fff;
  background-color: #c82333;
  border-color: #bd2130;
}

.btn-danger:focus, .btn-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-danger.disabled, .btn-danger:disabled {
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:active, .btn-danger.active,
.show > .btn-danger.dropdown-toggle {
  background-color: #c82333;
  background-image: none;
  border-color: #bd2130;
}

.btn-light {
  color: #111;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:hover {
  color: #111;
  background-color: #e2e6ea;
  border-color: #dae0e5;
}

.btn-light:focus, .btn-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-light.disabled, .btn-light:disabled {
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:active, .btn-light.active,
.show > .btn-light.dropdown-toggle {
  background-color: #e2e6ea;
  background-image: none;
  border-color: #dae0e5;
}

.btn-dark {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:hover {
  color: #fff;
  background-color: #23272b;
  border-color: #1d2124;
}

.btn-dark:focus, .btn-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-dark.disabled, .btn-dark:disabled {
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:active, .btn-dark.active,
.show > .btn-dark.dropdown-toggle {
  background-color: #23272b;
  background-image: none;
  border-color: #1d2124;
}

.btn-outline-primary {
  color: #E04444;
  background-color: transparent;
  background-image: none;
  border-color: #E04444;
}

.btn-outline-primary:hover {
  color: #fff;
  background-color: #E04444;
  border-color: #E04444;
}

.btn-outline-primary:focus, .btn-outline-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(224, 68, 68, 0.5);
  box-shadow: 0 0 0 3px rgba(224, 68, 68, 0.5);
}

.btn-outline-primary.disabled, .btn-outline-primary:disabled {
  color: #E04444;
  background-color: transparent;
}

.btn-outline-primary:active, .btn-outline-primary.active,
.show > .btn-outline-primary.dropdown-toggle {
  color: #fff;
  background-color: #E04444;
  border-color: #E04444;
}

.btn-outline-secondary {
  color: #868e96;
  background-color: transparent;
  background-image: none;
  border-color: #868e96;
}

.btn-outline-secondary:hover {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-secondary:focus, .btn-outline-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
  color: #868e96;
  background-color: transparent;
}

.btn-outline-secondary:active, .btn-outline-secondary.active,
.show > .btn-outline-secondary.dropdown-toggle {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-success {
  color: #28a745;
  background-color: transparent;
  background-image: none;
  border-color: #28a745;
}

.btn-outline-success:hover {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-success:focus, .btn-outline-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-outline-success.disabled, .btn-outline-success:disabled {
  color: #28a745;
  background-color: transparent;
}

.btn-outline-success:active, .btn-outline-success.active,
.show > .btn-outline-success.dropdown-toggle {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-info {
  color: #37cfdc;
  background-color: transparent;
  background-image: none;
  border-color: #37cfdc;
}

.btn-outline-info:hover {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-info:focus, .btn-outline-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-outline-info.disabled, .btn-outline-info:disabled {
  color: #37cfdc;
  background-color: transparent;
}

.btn-outline-info:active, .btn-outline-info.active,
.show > .btn-outline-info.dropdown-toggle {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-warning {
  color: #ffc107;
  background-color: transparent;
  background-image: none;
  border-color: #ffc107;
}

.btn-outline-warning:hover {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-warning:focus, .btn-outline-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-outline-warning.disabled, .btn-outline-warning:disabled {
  color: #ffc107;
  background-color: transparent;
}

.btn-outline-warning:active, .btn-outline-warning.active,
.show > .btn-outline-warning.dropdown-toggle {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-danger {
  color: #dc3545;
  background-color: transparent;
  background-image: none;
  border-color: #dc3545;
}

.btn-outline-danger:hover {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-danger:focus, .btn-outline-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-outline-danger.disabled, .btn-outline-danger:disabled {
  color: #dc3545;
  background-color: transparent;
}

.btn-outline-danger:active, .btn-outline-danger.active,
.show > .btn-outline-danger.dropdown-toggle {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-light {
  color: #f8f9fa;
  background-color: transparent;
  background-image: none;
  border-color: #f8f9fa;
}

.btn-outline-light:hover {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-light:focus, .btn-outline-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-outline-light.disabled, .btn-outline-light:disabled {
  color: #f8f9fa;
  background-color: transparent;
}

.btn-outline-light:active, .btn-outline-light.active,
.show > .btn-outline-light.dropdown-toggle {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-dark {
  color: #343a40;
  background-color: transparent;
  background-image: none;
  border-color: #343a40;
}

.btn-outline-dark:hover {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-outline-dark:focus, .btn-outline-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-outline-dark.disabled, .btn-outline-dark:disabled {
  color: #343a40;
  background-color: transparent;
}

.btn-outline-dark:active, .btn-outline-dark.active,
.show > .btn-outline-dark.dropdown-toggle {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-lg {
  padding: 0.8rem 3.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 50px;
}

.btn-sm {
  padding: 0.4rem 1.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 50px;
}

/*
 * 3. TYPE
 */
body {
  font-family: "Open Sans", sans-serif;
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
}

a {
  color: #E04444;
  text-decoration: none;
}

a:focus, a:hover {
  color: #b91f1f;
  text-decoration: underline;
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  margin-bottom: 0.5rem;
  font-family: inherit;
  font-weight: 800;
  line-height: 1.1;
  color: #2e324a;
}

h1,
.h1 {
  font-size: 2.9rem;
}

h2,
.h2 {
  font-size: 2.2rem;
}

h3,
.h3 {
  font-size: 1.75rem;
}

h4,
.h4 {
  font-size: 1.5rem;
}

h5,
.h5 {
  font-size: 1.25rem;
}

h6,
.h6 {
  font-size: 1rem;
}

.lead {
  font-size: 1.2rem;
  font-weight: 300;
  line-height: 1.8em;
}

.display-1 {
  font-size: 6rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-2 {
  font-size: 5.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-3 {
  font-size: 4.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-4 {
  font-size: 3.5rem;
  font-weight: 300;
  line-height: 1.1;
}

hr {
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}

small,
.small {
  font-size: 80%;
  font-weight: normal;
}

mark,
.mark {
  padding: 0.2em;
  background-color: #fcf8e3;
}

.blockquote {
  padding: 3rem 2rem;
  margin-bottom: 1rem;
  font-size: 1.05rem;
  border-left: 4px solid #E04444;
}

.blockquote-footer {
  color: #868e96;
}

.blockquote-footer::before {
  content: "\2014 \00A0";
}

.text-primary {
  color: #E04444 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #cf2222 !important;
}

/*
 * 4. PAGINATION
 */
.page-item:first-child .page-link {
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.page-item:last-child .page-link {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem;
}

.page-item.active .page-link {
  color: #fff;
  background-color: #E04444;
  border-color: #E04444;
}

.page-item.disabled .page-link {
  color: #868e96;
  background-color: #fff;
  border-color: #ddd;
}

.page-link {
  padding: 0.5rem 0.75rem;
  line-height: 1.25;
  color: #E04444;
  background-color: #fff;
  border: 1px solid #ddd;
}

.page-link:focus, .page-link:hover {
  color: #b91f1f;
  text-decoration: none;
  background-color: #e9ecef;
  border-color: #ddd;
}

.pagination-lg .page-link {
  padding: 0.75rem 1.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
}

.pagination-lg .page-item:first-child .page-link {
  border-top-left-radius: 0.3rem;
  border-bottom-left-radius: 0.3rem;
}

.pagination-lg .page-item:last-child .page-link {
  border-top-right-radius: 0.3rem;
  border-bottom-right-radius: 0.3rem;
}

.pagination-sm .page-link {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
}

.pagination-sm .page-item:first-child .page-link {
  border-top-left-radius: 0.2rem;
  border-bottom-left-radius: 0.2rem;
}

.pagination-sm .page-item:last-child .page-link {
  border-top-right-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem;
}

/*
* 5. UTILITIES
*/
.bg-primary {
  background-color: #E04444 !important;
}

a.bg-primary:focus, a.bg-primary:hover {
  background-color: #cf2222 !important;
}

.bg-secondary {
  background-color: #868e96 !important;
}

a.bg-secondary:focus, a.bg-secondary:hover {
  background-color: #6c757d !important;
}

.bg-success {
  background-color: #28a745 !important;
}

a.bg-success:focus, a.bg-success:hover {
  background-color: #1e7e34 !important;
}

.bg-info {
  background-color: #37cfdc !important;
}

a.bg-info:focus, a.bg-info:hover {
  background-color: #21b2bf !important;
}

.bg-warning {
  background-color: #ffc107 !important;
}

a.bg-warning:focus, a.bg-warning:hover {
  background-color: #d39e00 !important;
}

.bg-danger {
  background-color: #dc3545 !important;
}

a.bg-danger:focus, a.bg-danger:hover {
  background-color: #bd2130 !important;
}

.bg-light {
  background-color: #f8f9fa !important;
}

a.bg-light:focus, a.bg-light:hover {
  background-color: #dae0e5 !important;
}

.bg-dark {
  background-color: #343a40 !important;
}

a.bg-dark:focus, a.bg-dark:hover {
  background-color: #1d2124 !important;
}

.border-primary {
  border-color: #E04444 !important;
}

.border-secondary {
  border-color: #868e96 !important;
}

.border-success {
  border-color: #28a745 !important;
}

.border-info {
  border-color: #37cfdc !important;
}

.border-warning {
  border-color: #ffc107 !important;
}

.border-danger {
  border-color: #dc3545 !important;
}

.border-light {
  border-color: #f8f9fa !important;
}

.border-dark {
  border-color: #343a40 !important;
}

.text-primary {
  color: #E04444 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #cf2222 !important;
}

.text-secondary {
  color: #868e96 !important;
}

a.text-secondary:focus, a.text-secondary:hover {
  color: #6c757d !important;
}

.text-success {
  color: #28a745 !important;
}

a.text-success:focus, a.text-success:hover {
  color: #1e7e34 !important;
}

.text-info {
  color: #37cfdc !important;
}

a.text-info:focus, a.text-info:hover {
  color: #21b2bf !important;
}

.text-warning {
  color: #ffc107 !important;
}

a.text-warning:focus, a.text-warning:hover {
  color: #d39e00 !important;
}

.text-danger {
  color: #dc3545 !important;
}

a.text-danger:focus, a.text-danger:hover {
  color: #bd2130 !important;
}

.text-light {
  color: #f8f9fa !important;
}

a.text-light:focus, a.text-light:hover {
  color: #dae0e5 !important;
}

.text-dark {
  color: #343a40 !important;
}

a.text-dark:focus, a.text-dark:hover {
  color: #1d2124 !important;
}

/*
* ==========================================================
*     GENERAL
* ==========================================================
*/
body {
  padding-top: 80px;
  position: relative;
  overflow-x: hidden;
}

section {
  padding: 150px 0;
  overflow: hidden;
}

a {
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  display: inline-block;
}

p {
  line-height: 1.7rem;
}

button {
  cursor: pointer;
}

i,
span,
strong {
  display: inline-block;
}

.bg-gray, section.browser .nav-tabs a.active {
  background: #f5f5f5;
}

.no-padding {
  padding: 0 !important;
}

.no-padding-top {
  padding-top: 0 !important;
}

.no-padding-bottom {
  padding-bottom: 0 !important;
}

.no-margin {
  margin: 0 !important;
}

.no-margin-top {
  margin-top: 0 !important;
}

.no-margin-bottom {
  margin-bottom: 0 !important;
}

.hero-text {
  font-size: 1.1rem;
  font-weight: 400;
  color: #777;
  line-height: 1.5rem;
}

.btn {
  font-size: 0.9em !important;
}

.btn-primary:focus {
  color: #fff;
}

.btn-shadow {
  -webkit-box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
  box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
}

.btn-gradient, section.browser .nav-tabs span.number {
  background-color: #4CB8C4;
  background-image: -webkit-gradient(linear, left top, right top, from(#4CB8C4), to(#3CD3AD));
  background-image: linear-gradient(to right, #4CB8C4, #3CD3AD);
  border: none !important;
  text-transform: uppercase;
  color: #fff;
  overflow: hidden;
  position: relative;
  z-index: 1;
  -webkit-transition: all 0.3s !important;
  transition: all 0.3s !important;
}

.btn.btn-gradient:hover, section.browser .nav-tabs span.btn.number:hover {
  opacity: 0.85;
}

.has-shadow {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.owl-theme .owl-nav {
  margin-top: 0;
}

.owl-theme .owl-nav [class*='owl-'] {
  background: none;
  color: #222;
  font-size: 2rem;
  margin: 0 20px;
}

.owl-theme .owl-nav [class*='owl-'].disabled {
  color: #aaa;
}

.owl-theme .owl-nav [class*='owl-']:hover {
  background: none;
  color: #333;
}

section header {
  margin-bottom: 70px;
}

.scrollUp {
  -webkit-transform: translateY(-105%);
  transform: translateY(-105%);
}

.breadcrumb {
  background: none;
  padding: 0;
  margin-bottom: 20px;
}

.breadcrumb a {
  color: #222;
  text-decoration: none !important;
}

.breadcrumb li {
  color: #aaa;
}

.block {
  margin-bottom: 50px;
}

/* Browser mockup code
 * Contribute: https://gist.github.com/jarthod/8719db9fef8deb937f4f
 * Live example: https://updown.io
 */
.browser-mockup {
  border-top: 50px solid #f7f7f7;
  position: relative;
  border-radius: 3px 3px 0 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.browser-mockup:before {
  display: block;
  position: absolute;
  content: '';
  top: -29px;
  left: 30px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: #f44;
  -webkit-box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
  box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
}

.browser-mockup.with-tab:after {
  display: block;
  position: absolute;
  content: '';
  top: -50px;
  left: 115px;
  width: 20%;
  height: 0rem;
  border-bottom: 50px solid white;
  border-left: 1.5em solid transparent;
  border-right: 1.5em solid transparent;
}

.browser-mockup.with-url:after {
  display: block;
  position: absolute;
  content: '';
  top: -1.6rem;
  left: 5.5rem;
  width: calc(100% - 6em);
  height: 1.2rem;
  border-radius: 2px;
  background-color: white;
}

.browser-mockup > * {
  display: block;
}

.blockquote {
  line-height: 1.7rem;
  color: #656565;
  padding: 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.blockquote p::first-letter {
  font-size: 2.5rem;
  color: #4CB8C4;
  font-weight: 800;
}

.modal {
  background: rgba(0, 0, 0, 0.8);
}

.modal button.close {
  width: 40px;
  height: 40px;
  line-height: 40px;
  color: #fff;
  text-align: center;
  background-color: #4CB8C4;
  background-image: -webkit-gradient(linear, left top, right top, from(#4CB8C4), to(#3CD3AD));
  background-image: linear-gradient(to right, #4CB8C4, #3CD3AD);
  position: absolute;
  top: 0;
  right: 0;
  opacity: 1;
}

.modal-content {
  border-radius: 0;
}

.modal-header,
.modal-body {
  padding: 20px 30px;
  border: none;
}

#signupform .form-group {
  margin-bottom: 20px;
}

#signupform label {
  display: block;
  padding-left: 10px;
  color: #656565;
  font-family: "Open Sans", sans-serif;
}

#signupform input {
  width: 100%;
  display: block;
  padding: 10px 20px;
  border-radius: 50px;
  border: 1px solid #eee;
  outline: none;
}

#signupform input:focus {
  border-color: #4CB8C4;
}

#signupform input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

/* General Media Query ---------------------------------- */
@media (max-width: 991px) {
  section {
    padding: 100px 0;
  }
}

/*
* ==========================================================
*     NAVBAR
* ==========================================================
*/
nav.navbar {
  padding-top: 15px;
  padding-bottom: 15px;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  background: #fff;
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

nav.navbar .navbar-brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
}

nav.navbar a.nav-link {
  color: #333;
  font-size: 1.1rem;
}

nav.navbar a.nav-link:hover, nav.navbar a.nav-link.active {
  color: #4CB8C4;
}

nav.navbar .navbar-btn {
  margin-left: 15px;
}

nav.navbar .navbar-toggler {
  outline: none;
}

nav.navbar .navbar-toggler span {
  width: 25px;
  margin: 5px;
  display: block;
  height: 2px;
  background: #333;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
}

nav.navbar .navbar-toggler.active span:first-of-type {
  -webkit-transform: rotate(45deg) translate(10px);
  transform: rotate(45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:last-of-type {
  -webkit-transform: rotate(-45deg) translate(10px);
  transform: rotate(-45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:nth-of-type(2) {
  opacity: 0;
}

/* Navbar Mediaquery ----------------------------------- */
@media (max-width: 1199px) {
  nav.navbar .navbar-btn {
    margin-left: 0;
  }
}

@media (min-width: 992px) {
  nav.navbar {
    padding-left: 3rem;
    padding-right: 3rem;
  }
}

/*
* ==========================================================
*     HERO SECTION
* ==========================================================
*/
section.hero p {
  margin: 20px 0;
}

section.hero .CTA {
  margin-top: 40px;
}

section.hero .CTA a {
  margin-right: 10px;
  margin-bottom: 10px;
}

/*
* ==========================================================
*     BROWSER SECTION
* ==========================================================
*/
section.browser .nav-tabs {
  margin-top: 80px;
  border: none;
}

section.browser .nav-tabs span.number {
  width: 50px;
  height: 50px;
  line-height: 50px;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  display: block;
  position: absolute;
  left: calc(50% - 25px);
  top: -25px;
  font-size: 1.4rem;
  font-weight: 700;
}

section.browser .nav-tabs a {
  border: none;
  background: none;
  border-right: 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  padding: 50px 50px 40px;
  text-align: center;
  color: #333;
}

section.browser .nav-tabs a.active {
  -webkit-transform: translateY(-20px);
  transform: translateY(-20px);
}

/* Browser Section Mediaquery --------------------------- */
@media (max-width: 767px) {
  section.browser .nav-tabs a {
    margin-bottom: 50px;
  }
  section.browser .nav-tabs a.active {
    -webkit-transform: none;
    transform: none;
  }
  section.browser .nav-tabs .row div:last-of-type a {
    margin-bottom: 0;
  }
}

/*
* ==========================================================
*     ABOUT US
* ==========================================================
*/
section.about-us p {
  margin: 30px 0;
}

/*
* ==========================================================
*     FEATURES SECTION
* ==========================================================
*/
section.features .row {
  margin-bottom: 40px;
}

section.features .row:last-of-time {
  margin-bottom: 0;
}

section.features .icon {
  width: 50px;
  height: 50px;
  margin-bottom: 30px;
}

section.features .text p {
  line-height: 1.8rem;
  font-size: 0.95rem;
  color: #656565;
  margin: 20px 0 25px;
}

/* Features Section Mediaquery -------------------------- */
@media (max-width: 1199px) {
  section.features .text {
    margin-bottom: 50px;
  }
}

/*
* ==========================================================
*     EXTRA SECTION
* ==========================================================
*/
section.extra-features {
  color: #fff;
}

section.extra-features h2,
section.extra-features h3 {
  color: inherit;
}

section.extra-features .icon {
  font-size: 2.7rem;
  margin-bottom: 20px;
}

section.extra-features .item {
  padding: 50px 30px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  cursor: default;
}

section.extra-features .item:hover {
  background: #40b3c0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

section.extra-features .item p {
  font-weight: 300;
  margin: 20px 0;
}

/*
* ==========================================================
*     TESTIMONIALS SECTION
* ==========================================================
*/
section.testimonials .owl-carousel .owl-stage-outer {
  padding: 70px 0 50px;
}

section.testimonials .item-holder {
  padding-right: 40px;
  padding-left: 40px;
}

section.testimonials .quote {
  width: 40px;
  height: 40px;
  margin-bottom: 20px;
}

section.testimonials .item {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 0 30px;
  margin-right: 0;
  padding: 70px 50px;
  padding-left: 70px;
}

section.testimonials .item p {
  line-height: 1.8rem;
  font-size: 0.9rem;
  line-height: 1.7rem;
  color: #656565;
}

section.testimonials .avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  overflow: hidden;
  position: absolute;
  top: 50%;
  left: 0;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

/* Testimonials Media Query ------------------------- */
@media (max-width: 1199px) {
  section.testimonials .item {
    -webkit-box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    padding: 60px 40px 40px;
  }
  section.testimonials .item .avatar {
    position: absolute;
    top: 0;
    left: 50%;
  }
}

/*
* ==========================================================
*     NEWSLETTER SECTION
* ==========================================================
*/
section.newsletter .form-holder {
  padding: 70px 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  margin-top: 70px;
}

section.newsletter .form-group {
  position: relative;
  margin-bottom: 0;
}

section.newsletter .form-group input {
  width: 100%;
  height: 68px;
  line-height: 68px;
  border: 1px solid #ddd;
  border-radius: 50px;
  background: none;
  outline: none;
  padding: 0 30px;
  font-family: "Open Sans", sans-serif;
}

section.newsletter .form-group input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group .submit {
  height: 54px;
  line-height: 54px;
  padding-top: 0;
  padding-bottom: 0;
  position: absolute;
  top: 7px;
  right: 7px;
}

/* Newsletter Section Mediaquery -------------------------- */
@media (max-width: 991px) {
  section.newsletter .form-group input {
    width: 100%;
  }
  section.newsletter .form-group .submit {
    width: 100%;
    position: static;
    margin-top: 15px;
  }
}

/*
* ==========================================================
*     FOOTER
* ==========================================================
*/
footer.main-footer {
  padding: 150px 0 0;
  overflow-x: hidden;
}

footer.main-footer a {
  color: inherit;
  text-decoration: none;
}

footer.main-footer .brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
  margin-bottom: 20px;
}

footer.main-footer ul.contact-info {
  color: #444;
}

footer.main-footer ul.contact-info a {
  margin-bottom: 5px;
}

footer.main-footer ul.contact-info a:hover {
  color: #4CB8C4;
}

footer.main-footer h5 {
  margin-bottom: 30px;
}

footer.main-footer ul.links {
  color: #888;
}

footer.main-footer ul.links a {
  margin-bottom: 8px;
}

footer.main-footer ul.links a:hover {
  color: #4CB8C4;
}

footer.main-footer ul.social-icons {
  margin-top: 15px;
  margin-bottom: 50px;
}

footer.main-footer ul.social-icons a {
  width: 26px;
  height: 26px;
  line-height: 26px;
  background: #222;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  font-size: 0.8rem;
}

footer.main-footer ul.social-icons a:hover {
  background: #4CB8C4;
}

footer.main-footer .copyrights {
  margin-top: 150px;
}

footer.main-footer .copyrights .container {
  padding: 30px 0;
  border-top: 1px solid #ddd;
}

footer.main-footer .copyrights p {
  margin-bottom: 0;
}

footer.main-footer .copyrights a:hover {
  color: #4CB8C4;
}

/* Footer Mediaquery -------------------------- */
@media (max-width: 991px) {
  footer.main-footer {
    padding: 100px 0 0;
  }
  footer.main-footer .copyrights {
    margin-top: 100px;
  }
  footer.main-footer .copyrights div[class*="col-"] {
    text-align: center !important;
  }
}

/* ===================================================================
    SCROLL TO TOP BUTTON
===================================================================  */
#scrollTop {
  width: 80px;
  height: 40px;
  position: fixed;
  right: -90px;
  bottom: 50%;
  background-color: #4CB8C4;
  background-image: -webkit-gradient(linear, left top, right top, from(#4CB8C4), to(#3CD3AD));
  background-image: linear-gradient(to right, #4CB8C4, #3CD3AD);
  color: #fff;
  text-align: center;
  line-height: 40px;
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
  -webkit-box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  font-size: 0.7rem;
  cursor: pointer;
  z-index: 9998;
  padding-right: 10px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

#scrollTop.active {
  right: -50px;
}

#scrollTop i {
  font-size: 1.1rem;
  margin-right: 10px;
}

#scrollTop:hover {
  right: 0;
}

/* Scroll Top Media Query ------------------------- */
@media (max-width: 1199px) {
  #scrollTop {
    display: none !important;
  }
}

/*

=====================
STYLE SWITCHER FOR DEMO
=====================

*/
#style-switch-button {
  position: fixed;
  top: 120px;
  left: 0px;
  border-radius: 0;
  z-index: 2;
}

#style-switch {
  width: 300px;
  padding: 20px;
  position: fixed;
  top: 160px;
  left: 0;
  background: #fff;
  border: solid 1px #ced4da;
  z-index: 2000;
}

#style-switch h4 {
  color: #495057;
}

/* =========================================
   THEMING OF BOOTSTRAP COMPONENTS
   ========================================= */
/*
 * 1. NAVBAR
 */
.navbar {
  padding: 0.5rem 1rem;
}

.navbar-brand {
  display: inline-block;
  padding-top: 0.3125rem;
  padding-bottom: 0.3125rem;
  margin-right: 1rem;
  font-size: 1.25rem;
}

.navbar-toggler {
  padding: 0.25rem 0.75rem;
  font-size: 1.25rem;
  line-height: 1;
  border: 1px solid transparent;
  border-radius: 50px;
}

.navbar-light .navbar-brand {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-brand:focus, .navbar-light .navbar-brand:hover {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-nav .nav-link:focus, .navbar-light .navbar-nav .nav-link:hover {
  color: rgba(0, 0, 0, 0.7);
}

.navbar-light .navbar-nav .nav-link.disabled {
  color: rgba(0, 0, 0, 0.3);
}

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0.5);
  border-color: rgba(0, 0, 0, 0.1);
}

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-light .navbar-text {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-dark .navbar-brand {
  color: white;
}

.navbar-dark .navbar-brand:focus, .navbar-dark .navbar-brand:hover {
  color: white;
}

.navbar-dark .navbar-nav .nav-link {
  color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
  color: rgba(255, 255, 255, 0.75);
}

.navbar-dark .navbar-nav .nav-link.disabled {
  color: rgba(255, 255, 255, 0.25);
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: white;
}

.navbar-dark .navbar-toggler {
  color: rgba(255, 255, 255, 0.5);
  border-color: rgba(255, 255, 255, 0.1);
}

.navbar-dark .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-dark .navbar-text {
  color: rgba(255, 255, 255, 0.5);
}

/*
 * 2. BUTTONS
 */
.btn {
  font-weight: 400;
  border: 1px solid transparent;
  padding: 0.6rem 3rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 50px;
  -webkit-transition: all 0.15s ease-in-out;
  transition: all 0.15s ease-in-out;
}

.btn:focus, .btn.focus {
  outline: 0;
  -webkit-box-shadow: 0 0 0 3px rgba(76, 184, 196, 0.25);
  box-shadow: 0 0 0 3px rgba(76, 184, 196, 0.25);
}

.btn:active, .btn.active {
  background-image: none;
}

.btn-primary {
  color: #111;
  background-color: #4CB8C4;
  border-color: #4CB8C4;
}

.btn-primary:hover {
  color: #111;
  background-color: #3aa4b0;
  border-color: #379ba6;
}

.btn-primary:focus, .btn-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(76, 184, 196, 0.5);
  box-shadow: 0 0 0 3px rgba(76, 184, 196, 0.5);
}

.btn-primary.disabled, .btn-primary:disabled {
  background-color: #4CB8C4;
  border-color: #4CB8C4;
}

.btn-primary:active, .btn-primary.active,
.show > .btn-primary.dropdown-toggle {
  background-color: #3aa4b0;
  background-image: none;
  border-color: #379ba6;
}

.btn-secondary {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:hover {
  color: #fff;
  background-color: #727b84;
  border-color: #6c757d;
}

.btn-secondary:focus, .btn-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-secondary.disabled, .btn-secondary:disabled {
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:active, .btn-secondary.active,
.show > .btn-secondary.dropdown-toggle {
  background-color: #727b84;
  background-image: none;
  border-color: #6c757d;
}

.btn-success {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:hover {
  color: #fff;
  background-color: #218838;
  border-color: #1e7e34;
}

.btn-success:focus, .btn-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-success.disabled, .btn-success:disabled {
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:active, .btn-success.active,
.show > .btn-success.dropdown-toggle {
  background-color: #218838;
  background-image: none;
  border-color: #1e7e34;
}

.btn-info {
  color: #111;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:hover {
  color: #111;
  background-color: #23bcc9;
  border-color: #21b2bf;
}

.btn-info:focus, .btn-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-info.disabled, .btn-info:disabled {
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:active, .btn-info.active,
.show > .btn-info.dropdown-toggle {
  background-color: #23bcc9;
  background-image: none;
  border-color: #21b2bf;
}

.btn-warning {
  color: #111;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:hover {
  color: #111;
  background-color: #e0a800;
  border-color: #d39e00;
}

.btn-warning:focus, .btn-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-warning.disabled, .btn-warning:disabled {
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:active, .btn-warning.active,
.show > .btn-warning.dropdown-toggle {
  background-color: #e0a800;
  background-image: none;
  border-color: #d39e00;
}

.btn-danger {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:hover {
  color: #fff;
  background-color: #c82333;
  border-color: #bd2130;
}

.btn-danger:focus, .btn-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-danger.disabled, .btn-danger:disabled {
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:active, .btn-danger.active,
.show > .btn-danger.dropdown-toggle {
  background-color: #c82333;
  background-image: none;
  border-color: #bd2130;
}

.btn-light {
  color: #111;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:hover {
  color: #111;
  background-color: #e2e6ea;
  border-color: #dae0e5;
}

.btn-light:focus, .btn-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-light.disabled, .btn-light:disabled {
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:active, .btn-light.active,
.show > .btn-light.dropdown-toggle {
  background-color: #e2e6ea;
  background-image: none;
  border-color: #dae0e5;
}

.btn-dark {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:hover {
  color: #fff;
  background-color: #23272b;
  border-color: #1d2124;
}

.btn-dark:focus, .btn-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-dark.disabled, .btn-dark:disabled {
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:active, .btn-dark.active,
.show > .btn-dark.dropdown-toggle {
  background-color: #23272b;
  background-image: none;
  border-color: #1d2124;
}

.btn-outline-primary {
  color: #4CB8C4;
  background-color: transparent;
  background-image: none;
  border-color: #4CB8C4;
}

.btn-outline-primary:hover {
  color: #fff;
  background-color: #4CB8C4;
  border-color: #4CB8C4;
}

.btn-outline-primary:focus, .btn-outline-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(76, 184, 196, 0.5);
  box-shadow: 0 0 0 3px rgba(76, 184, 196, 0.5);
}

.btn-outline-primary.disabled, .btn-outline-primary:disabled {
  color: #4CB8C4;
  background-color: transparent;
}

.btn-outline-primary:active, .btn-outline-primary.active,
.show > .btn-outline-primary.dropdown-toggle {
  color: #fff;
  background-color: #4CB8C4;
  border-color: #4CB8C4;
}

.btn-outline-secondary {
  color: #868e96;
  background-color: transparent;
  background-image: none;
  border-color: #868e96;
}

.btn-outline-secondary:hover {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-secondary:focus, .btn-outline-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
  color: #868e96;
  background-color: transparent;
}

.btn-outline-secondary:active, .btn-outline-secondary.active,
.show > .btn-outline-secondary.dropdown-toggle {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-success {
  color: #28a745;
  background-color: transparent;
  background-image: none;
  border-color: #28a745;
}

.btn-outline-success:hover {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-success:focus, .btn-outline-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-outline-success.disabled, .btn-outline-success:disabled {
  color: #28a745;
  background-color: transparent;
}

.btn-outline-success:active, .btn-outline-success.active,
.show > .btn-outline-success.dropdown-toggle {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-info {
  color: #37cfdc;
  background-color: transparent;
  background-image: none;
  border-color: #37cfdc;
}

.btn-outline-info:hover {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-info:focus, .btn-outline-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-outline-info.disabled, .btn-outline-info:disabled {
  color: #37cfdc;
  background-color: transparent;
}

.btn-outline-info:active, .btn-outline-info.active,
.show > .btn-outline-info.dropdown-toggle {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-warning {
  color: #ffc107;
  background-color: transparent;
  background-image: none;
  border-color: #ffc107;
}

.btn-outline-warning:hover {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-warning:focus, .btn-outline-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-outline-warning.disabled, .btn-outline-warning:disabled {
  color: #ffc107;
  background-color: transparent;
}

.btn-outline-warning:active, .btn-outline-warning.active,
.show > .btn-outline-warning.dropdown-toggle {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-danger {
  color: #dc3545;
  background-color: transparent;
  background-image: none;
  border-color: #dc3545;
}

.btn-outline-danger:hover {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-danger:focus, .btn-outline-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-outline-danger.disabled, .btn-outline-danger:disabled {
  color: #dc3545;
  background-color: transparent;
}

.btn-outline-danger:active, .btn-outline-danger.active,
.show > .btn-outline-danger.dropdown-toggle {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-light {
  color: #f8f9fa;
  background-color: transparent;
  background-image: none;
  border-color: #f8f9fa;
}

.btn-outline-light:hover {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-light:focus, .btn-outline-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-outline-light.disabled, .btn-outline-light:disabled {
  color: #f8f9fa;
  background-color: transparent;
}

.btn-outline-light:active, .btn-outline-light.active,
.show > .btn-outline-light.dropdown-toggle {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-dark {
  color: #343a40;
  background-color: transparent;
  background-image: none;
  border-color: #343a40;
}

.btn-outline-dark:hover {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-outline-dark:focus, .btn-outline-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-outline-dark.disabled, .btn-outline-dark:disabled {
  color: #343a40;
  background-color: transparent;
}

.btn-outline-dark:active, .btn-outline-dark.active,
.show > .btn-outline-dark.dropdown-toggle {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-lg {
  padding: 0.8rem 3.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 50px;
}

.btn-sm {
  padding: 0.4rem 1.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 50px;
}

/*
 * 3. TYPE
 */
body {
  font-family: "Open Sans", sans-serif;
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
}

a {
  color: #4CB8C4;
  text-decoration: none;
}

a:focus, a:hover {
  color: #308993;
  text-decoration: underline;
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  margin-bottom: 0.5rem;
  font-family: inherit;
  font-weight: 800;
  line-height: 1.1;
  color: #2e324a;
}

h1,
.h1 {
  font-size: 2.9rem;
}

h2,
.h2 {
  font-size: 2.2rem;
}

h3,
.h3 {
  font-size: 1.75rem;
}

h4,
.h4 {
  font-size: 1.5rem;
}

h5,
.h5 {
  font-size: 1.25rem;
}

h6,
.h6 {
  font-size: 1rem;
}

.lead {
  font-size: 1.2rem;
  font-weight: 300;
  line-height: 1.8em;
}

.display-1 {
  font-size: 6rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-2 {
  font-size: 5.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-3 {
  font-size: 4.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-4 {
  font-size: 3.5rem;
  font-weight: 300;
  line-height: 1.1;
}

hr {
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}

small,
.small {
  font-size: 80%;
  font-weight: normal;
}

mark,
.mark {
  padding: 0.2em;
  background-color: #fcf8e3;
}

.blockquote {
  padding: 3rem 2rem;
  margin-bottom: 1rem;
  font-size: 1.05rem;
  border-left: 4px solid #4CB8C4;
}

.blockquote-footer {
  color: #868e96;
}

.blockquote-footer::before {
  content: "\2014 \00A0";
}

.text-primary {
  color: #4CB8C4 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #379ba6 !important;
}

/*
 * 4. PAGINATION
 */
.page-item:first-child .page-link {
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.page-item:last-child .page-link {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem;
}

.page-item.active .page-link {
  color: #fff;
  background-color: #4CB8C4;
  border-color: #4CB8C4;
}

.page-item.disabled .page-link {
  color: #868e96;
  background-color: #fff;
  border-color: #ddd;
}

.page-link {
  padding: 0.5rem 0.75rem;
  line-height: 1.25;
  color: #4CB8C4;
  background-color: #fff;
  border: 1px solid #ddd;
}

.page-link:focus, .page-link:hover {
  color: #308993;
  text-decoration: none;
  background-color: #e9ecef;
  border-color: #ddd;
}

.pagination-lg .page-link {
  padding: 0.75rem 1.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
}

.pagination-lg .page-item:first-child .page-link {
  border-top-left-radius: 0.3rem;
  border-bottom-left-radius: 0.3rem;
}

.pagination-lg .page-item:last-child .page-link {
  border-top-right-radius: 0.3rem;
  border-bottom-right-radius: 0.3rem;
}

.pagination-sm .page-link {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
}

.pagination-sm .page-item:first-child .page-link {
  border-top-left-radius: 0.2rem;
  border-bottom-left-radius: 0.2rem;
}

.pagination-sm .page-item:last-child .page-link {
  border-top-right-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem;
}

/*
* 5. UTILITIES
*/
.bg-primary {
  background-color: #4CB8C4 !important;
}

a.bg-primary:focus, a.bg-primary:hover {
  background-color: #379ba6 !important;
}

.bg-secondary {
  background-color: #868e96 !important;
}

a.bg-secondary:focus, a.bg-secondary:hover {
  background-color: #6c757d !important;
}

.bg-success {
  background-color: #28a745 !important;
}

a.bg-success:focus, a.bg-success:hover {
  background-color: #1e7e34 !important;
}

.bg-info {
  background-color: #37cfdc !important;
}

a.bg-info:focus, a.bg-info:hover {
  background-color: #21b2bf !important;
}

.bg-warning {
  background-color: #ffc107 !important;
}

a.bg-warning:focus, a.bg-warning:hover {
  background-color: #d39e00 !important;
}

.bg-danger {
  background-color: #dc3545 !important;
}

a.bg-danger:focus, a.bg-danger:hover {
  background-color: #bd2130 !important;
}

.bg-light {
  background-color: #f8f9fa !important;
}

a.bg-light:focus, a.bg-light:hover {
  background-color: #dae0e5 !important;
}

.bg-dark {
  background-color: #343a40 !important;
}

a.bg-dark:focus, a.bg-dark:hover {
  background-color: #1d2124 !important;
}

.border-primary {
  border-color: #4CB8C4 !important;
}

.border-secondary {
  border-color: #868e96 !important;
}

.border-success {
  border-color: #28a745 !important;
}

.border-info {
  border-color: #37cfdc !important;
}

.border-warning {
  border-color: #ffc107 !important;
}

.border-danger {
  border-color: #dc3545 !important;
}

.border-light {
  border-color: #f8f9fa !important;
}

.border-dark {
  border-color: #343a40 !important;
}

.text-primary {
  color: #4CB8C4 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #379ba6 !important;
}

.text-secondary {
  color: #868e96 !important;
}

a.text-secondary:focus, a.text-secondary:hover {
  color: #6c757d !important;
}

.text-success {
  color: #28a745 !important;
}

a.text-success:focus, a.text-success:hover {
  color: #1e7e34 !important;
}

.text-info {
  color: #37cfdc !important;
}

a.text-info:focus, a.text-info:hover {
  color: #21b2bf !important;
}

.text-warning {
  color: #ffc107 !important;
}

a.text-warning:focus, a.text-warning:hover {
  color: #d39e00 !important;
}

.text-danger {
  color: #dc3545 !important;
}

a.text-danger:focus, a.text-danger:hover {
  color: #bd2130 !important;
}

.text-light {
  color: #f8f9fa !important;
}

a.text-light:focus, a.text-light:hover {
  color: #dae0e5 !important;
}

.text-dark {
  color: #343a40 !important;
}

a.text-dark:focus, a.text-dark:hover {
  color: #1d2124 !important;
}

/*
* ==========================================================
*     GENERAL
* ==========================================================
*/
body {
  padding-top: 80px;
  position: relative;
  overflow-x: hidden;
}

section {
  padding: 150px 0;
  overflow: hidden;
}

a {
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  display: inline-block;
}

p {
  line-height: 1.7rem;
}

button {
  cursor: pointer;
}

i,
span,
strong {
  display: inline-block;
}

.bg-gray, section.browser .nav-tabs a.active {
  background: #f5f5f5;
}

.no-padding {
  padding: 0 !important;
}

.no-padding-top {
  padding-top: 0 !important;
}

.no-padding-bottom {
  padding-bottom: 0 !important;
}

.no-margin {
  margin: 0 !important;
}

.no-margin-top {
  margin-top: 0 !important;
}

.no-margin-bottom {
  margin-bottom: 0 !important;
}

.hero-text {
  font-size: 1.1rem;
  font-weight: 400;
  color: #777;
  line-height: 1.5rem;
}

.btn {
  font-size: 0.9em !important;
}

.btn-primary:focus {
  color: #fff;
}

.btn-shadow {
  -webkit-box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
  box-shadow: 0 10px 20px rgba(109, 109, 109, 0.16) !important;
}

.btn-gradient, section.browser .nav-tabs span.number {
  background-color: #9055A2;
  background-image: -webkit-gradient(linear, left top, right top, from(#9055A2), to(#3750D1));
  background-image: linear-gradient(to right, #9055A2, #3750D1);
  border: none !important;
  text-transform: uppercase;
  color: #fff;
  overflow: hidden;
  position: relative;
  z-index: 1;
  -webkit-transition: all 0.3s !important;
  transition: all 0.3s !important;
}

.btn.btn-gradient:hover, section.browser .nav-tabs span.btn.number:hover {
  opacity: 0.85;
}

.has-shadow {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.owl-theme .owl-nav {
  margin-top: 0;
}

.owl-theme .owl-nav [class*='owl-'] {
  background: none;
  color: #222;
  font-size: 2rem;
  margin: 0 20px;
}

.owl-theme .owl-nav [class*='owl-'].disabled {
  color: #aaa;
}

.owl-theme .owl-nav [class*='owl-']:hover {
  background: none;
  color: #333;
}

section header {
  margin-bottom: 70px;
}

.scrollUp {
  -webkit-transform: translateY(-105%);
  transform: translateY(-105%);
}

.breadcrumb {
  background: none;
  padding: 0;
  margin-bottom: 20px;
}

.breadcrumb a {
  color: #222;
  text-decoration: none !important;
}

.breadcrumb li {
  color: #aaa;
}

.block {
  margin-bottom: 50px;
}

/* Browser mockup code
 * Contribute: https://gist.github.com/jarthod/8719db9fef8deb937f4f
 * Live example: https://updown.io
 */
.browser-mockup {
  border-top: 50px solid #f7f7f7;
  position: relative;
  border-radius: 3px 3px 0 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.browser-mockup:before {
  display: block;
  position: absolute;
  content: '';
  top: -29px;
  left: 30px;
  width: 8px;
  height: 8px;
  border-radius: 50%;
  background-color: #f44;
  -webkit-box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
  box-shadow: 0 0 0 2px #f44, 1.5em 0 0 2px #9b3, 3em 0 0 2px #fb5;
}

.browser-mockup.with-tab:after {
  display: block;
  position: absolute;
  content: '';
  top: -50px;
  left: 115px;
  width: 20%;
  height: 0rem;
  border-bottom: 50px solid white;
  border-left: 1.5em solid transparent;
  border-right: 1.5em solid transparent;
}

.browser-mockup.with-url:after {
  display: block;
  position: absolute;
  content: '';
  top: -1.6rem;
  left: 5.5rem;
  width: calc(100% - 6em);
  height: 1.2rem;
  border-radius: 2px;
  background-color: white;
}

.browser-mockup > * {
  display: block;
}

.blockquote {
  line-height: 1.7rem;
  color: #656565;
  padding: 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

.blockquote p::first-letter {
  font-size: 2.5rem;
  color: #9055A2;
  font-weight: 800;
}

.modal {
  background: rgba(0, 0, 0, 0.8);
}

.modal button.close {
  width: 40px;
  height: 40px;
  line-height: 40px;
  color: #fff;
  text-align: center;
  background-color: #9055A2;
  background-image: -webkit-gradient(linear, left top, right top, from(#9055A2), to(#3750D1));
  background-image: linear-gradient(to right, #9055A2, #3750D1);
  position: absolute;
  top: 0;
  right: 0;
  opacity: 1;
}

.modal-content {
  border-radius: 0;
}

.modal-header,
.modal-body {
  padding: 20px 30px;
  border: none;
}

#signupform .form-group {
  margin-bottom: 20px;
}

#signupform label {
  display: block;
  padding-left: 10px;
  color: #656565;
  font-family: "Open Sans", sans-serif;
}

#signupform input {
  width: 100%;
  display: block;
  padding: 10px 20px;
  border-radius: 50px;
  border: 1px solid #eee;
  outline: none;
}

#signupform input:focus {
  border-color: #9055A2;
}

#signupform input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

#signupform input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
  color: #aaa;
  font-style: italic;
  font-size: 0.9em;
}

/* General Media Query ---------------------------------- */
@media (max-width: 991px) {
  section {
    padding: 100px 0;
  }
}

/*
* ==========================================================
*     NAVBAR
* ==========================================================
*/
nav.navbar {
  padding-top: 15px;
  padding-bottom: 15px;
  -webkit-box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  box-shadow: 0 2px 3px rgba(0, 0, 0, 0.1);
  background: #fff;
  -webkit-transition: all 0.5s;
  transition: all 0.5s;
}

nav.navbar .navbar-brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
}

nav.navbar a.nav-link {
  color: #333;
  font-size: 1.1rem;
}

nav.navbar a.nav-link:hover, nav.navbar a.nav-link.active {
  color: #9055A2;
}

nav.navbar .navbar-btn {
  margin-left: 15px;
}

nav.navbar .navbar-toggler {
  outline: none;
}

nav.navbar .navbar-toggler span {
  width: 25px;
  margin: 5px;
  display: block;
  height: 2px;
  background: #333;
  -webkit-transition: all 0.2s;
  transition: all 0.2s;
}

nav.navbar .navbar-toggler.active span:first-of-type {
  -webkit-transform: rotate(45deg) translate(10px);
  transform: rotate(45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:last-of-type {
  -webkit-transform: rotate(-45deg) translate(10px);
  transform: rotate(-45deg) translate(10px);
}

nav.navbar .navbar-toggler.active span:nth-of-type(2) {
  opacity: 0;
}

/* Navbar Mediaquery ----------------------------------- */
@media (max-width: 1199px) {
  nav.navbar .navbar-btn {
    margin-left: 0;
  }
}

@media (min-width: 992px) {
  nav.navbar {
    padding-left: 3rem;
    padding-right: 3rem;
  }
}

/*
* ==========================================================
*     HERO SECTION
* ==========================================================
*/
section.hero p {
  margin: 20px 0;
}

section.hero .CTA {
  margin-top: 40px;
}

section.hero .CTA a {
  margin-right: 10px;
  margin-bottom: 10px;
}

/*
* ==========================================================
*     BROWSER SECTION
* ==========================================================
*/
section.browser .nav-tabs {
  margin-top: 80px;
  border: none;
}

section.browser .nav-tabs span.number {
  width: 50px;
  height: 50px;
  line-height: 50px;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  display: block;
  position: absolute;
  left: calc(50% - 25px);
  top: -25px;
  font-size: 1.4rem;
  font-weight: 700;
}

section.browser .nav-tabs a {
  border: none;
  background: none;
  border-right: 0;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  padding: 50px 50px 40px;
  text-align: center;
  color: #333;
}

section.browser .nav-tabs a.active {
  -webkit-transform: translateY(-20px);
  transform: translateY(-20px);
}

/* Browser Section Mediaquery --------------------------- */
@media (max-width: 767px) {
  section.browser .nav-tabs a {
    margin-bottom: 50px;
  }
  section.browser .nav-tabs a.active {
    -webkit-transform: none;
    transform: none;
  }
  section.browser .nav-tabs .row div:last-of-type a {
    margin-bottom: 0;
  }
}

/*
* ==========================================================
*     ABOUT US
* ==========================================================
*/
section.about-us p {
  margin: 30px 0;
}

/*
* ==========================================================
*     FEATURES SECTION
* ==========================================================
*/
section.features .row {
  margin-bottom: 40px;
}

section.features .row:last-of-time {
  margin-bottom: 0;
}

section.features .icon {
  width: 50px;
  height: 50px;
  margin-bottom: 30px;
}

section.features .text p {
  line-height: 1.8rem;
  font-size: 0.95rem;
  color: #656565;
  margin: 20px 0 25px;
}

/* Features Section Mediaquery -------------------------- */
@media (max-width: 1199px) {
  section.features .text {
    margin-bottom: 50px;
  }
}

/*
* ==========================================================
*     EXTRA SECTION
* ==========================================================
*/
section.extra-features {
  color: #fff;
}

section.extra-features h2,
section.extra-features h3 {
  color: inherit;
}

section.extra-features .icon {
  font-size: 2.7rem;
  margin-bottom: 20px;
}

section.extra-features .item {
  padding: 50px 30px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
  cursor: default;
}

section.extra-features .item:hover {
  background: #875098;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

section.extra-features .item p {
  font-weight: 300;
  margin: 20px 0;
}

/*
* ==========================================================
*     TESTIMONIALS SECTION
* ==========================================================
*/
section.testimonials .owl-carousel .owl-stage-outer {
  padding: 70px 0 50px;
}

section.testimonials .item-holder {
  padding-right: 40px;
  padding-left: 40px;
}

section.testimonials .quote {
  width: 40px;
  height: 40px;
  margin-bottom: 20px;
}

section.testimonials .item {
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  position: relative;
  margin: 0 30px;
  margin-right: 0;
  padding: 70px 50px;
  padding-left: 70px;
}

section.testimonials .item p {
  line-height: 1.8rem;
  font-size: 0.9rem;
  line-height: 1.7rem;
  color: #656565;
}

section.testimonials .avatar {
  width: 80px;
  height: 80px;
  border-radius: 50%;
  overflow: hidden;
  position: absolute;
  top: 50%;
  left: 0;
  -webkit-transform: translate(-50%, -50%);
  transform: translate(-50%, -50%);
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
}

/* Testimonials Media Query ------------------------- */
@media (max-width: 1199px) {
  section.testimonials .item {
    -webkit-box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    box-shadow: -5.665px 9.429px 25px 0px rgba(0, 0, 0, 0.2);
    padding: 60px 40px 40px;
  }
  section.testimonials .item .avatar {
    position: absolute;
    top: 0;
    left: 50%;
  }
}

/*
* ==========================================================
*     NEWSLETTER SECTION
* ==========================================================
*/
section.newsletter .form-holder {
  padding: 70px 40px;
  background: #fff;
  -webkit-box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  box-shadow: -5.665px 9.429px 35px 0px rgba(0, 0, 0, 0.2);
  margin-top: 70px;
}

section.newsletter .form-group {
  position: relative;
  margin-bottom: 0;
}

section.newsletter .form-group input {
  width: 100%;
  height: 68px;
  line-height: 68px;
  border: 1px solid #ddd;
  border-radius: 50px;
  background: none;
  outline: none;
  padding: 0 30px;
  font-family: "Open Sans", sans-serif;
}

section.newsletter .form-group input::-moz-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input::-webkit-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group input:-ms-input-placeholder {
  font-family: "Open Sans", sans-serif;
  font-weight: 300;
}

section.newsletter .form-group .submit {
  height: 54px;
  line-height: 54px;
  padding-top: 0;
  padding-bottom: 0;
  position: absolute;
  top: 7px;
  right: 7px;
}

/* Newsletter Section Mediaquery -------------------------- */
@media (max-width: 991px) {
  section.newsletter .form-group input {
    width: 100%;
  }
  section.newsletter .form-group .submit {
    width: 100%;
    position: static;
    margin-top: 15px;
  }
}

/*
* ==========================================================
*     FOOTER
* ==========================================================
*/
footer.main-footer {
  padding: 150px 0 0;
  overflow-x: hidden;
}

footer.main-footer a {
  color: inherit;
  text-decoration: none;
}

footer.main-footer .brand {
  font-weight: 800;
  font-size: 1.7rem;
  color: #222;
  margin-bottom: 20px;
}

footer.main-footer ul.contact-info {
  color: #444;
}

footer.main-footer ul.contact-info a {
  margin-bottom: 5px;
}

footer.main-footer ul.contact-info a:hover {
  color: #9055A2;
}

footer.main-footer h5 {
  margin-bottom: 30px;
}

footer.main-footer ul.links {
  color: #888;
}

footer.main-footer ul.links a {
  margin-bottom: 8px;
}

footer.main-footer ul.links a:hover {
  color: #9055A2;
}

footer.main-footer ul.social-icons {
  margin-top: 15px;
  margin-bottom: 50px;
}

footer.main-footer ul.social-icons a {
  width: 26px;
  height: 26px;
  line-height: 26px;
  background: #222;
  color: #fff;
  text-align: center;
  border-radius: 50%;
  font-size: 0.8rem;
}

footer.main-footer ul.social-icons a:hover {
  background: #9055A2;
}

footer.main-footer .copyrights {
  margin-top: 150px;
}

footer.main-footer .copyrights .container {
  padding: 30px 0;
  border-top: 1px solid #ddd;
}

footer.main-footer .copyrights p {
  margin-bottom: 0;
}

footer.main-footer .copyrights a:hover {
  color: #9055A2;
}

/* Footer Mediaquery -------------------------- */
@media (max-width: 991px) {
  footer.main-footer {
    padding: 100px 0 0;
  }
  footer.main-footer .copyrights {
    margin-top: 100px;
  }
  footer.main-footer .copyrights div[class*="col-"] {
    text-align: center !important;
  }
}

/* ===================================================================
    SCROLL TO TOP BUTTON
===================================================================  */
#scrollTop {
  width: 80px;
  height: 40px;
  position: fixed;
  right: -90px;
  bottom: 50%;
  background-color: #9055A2;
  background-image: -webkit-gradient(linear, left top, right top, from(#9055A2), to(#3750D1));
  background-image: linear-gradient(to right, #9055A2, #3750D1);
  color: #fff;
  text-align: center;
  line-height: 40px;
  border-top-left-radius: 50px;
  border-bottom-left-radius: 50px;
  -webkit-box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  box-shadow: 0 3px 10px rgba(0, 0, 0, 0.2);
  font-size: 0.7rem;
  cursor: pointer;
  z-index: 9998;
  padding-right: 10px;
  -webkit-transition: all 0.3s;
  transition: all 0.3s;
}

#scrollTop.active {
  right: -50px;
}

#scrollTop i {
  font-size: 1.1rem;
  margin-right: 10px;
}

#scrollTop:hover {
  right: 0;
}

/* Scroll Top Media Query ------------------------- */
@media (max-width: 1199px) {
  #scrollTop {
    display: none !important;
  }
}

/*

=====================
STYLE SWITCHER FOR DEMO
=====================

*/
#style-switch-button {
  position: fixed;
  top: 120px;
  left: 0px;
  border-radius: 0;
  z-index: 2;
}

#style-switch {
  width: 300px;
  padding: 20px;
  position: fixed;
  top: 160px;
  left: 0;
  background: #fff;
  border: solid 1px #ced4da;
  z-index: 2000;
}

#style-switch h4 {
  color: #495057;
}

/* =========================================
   THEMING OF BOOTSTRAP COMPONENTS
   ========================================= */
/*
 * 1. NAVBAR
 */
.navbar {
  padding: 0.5rem 1rem;
}

.navbar-brand {
  display: inline-block;
  padding-top: 0.3125rem;
  padding-bottom: 0.3125rem;
  margin-right: 1rem;
  font-size: 1.25rem;
}

.navbar-toggler {
  padding: 0.25rem 0.75rem;
  font-size: 1.25rem;
  line-height: 1;
  border: 1px solid transparent;
  border-radius: 50px;
}

.navbar-light .navbar-brand {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-brand:focus, .navbar-light .navbar-brand:hover {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-nav .nav-link {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-light .navbar-nav .nav-link:focus, .navbar-light .navbar-nav .nav-link:hover {
  color: rgba(0, 0, 0, 0.7);
}

.navbar-light .navbar-nav .nav-link.disabled {
  color: rgba(0, 0, 0, 0.3);
}

.navbar-light .navbar-nav .show > .nav-link,
.navbar-light .navbar-nav .active > .nav-link,
.navbar-light .navbar-nav .nav-link.show,
.navbar-light .navbar-nav .nav-link.active {
  color: rgba(0, 0, 0, 0.9);
}

.navbar-light .navbar-toggler {
  color: rgba(0, 0, 0, 0.5);
  border-color: rgba(0, 0, 0, 0.1);
}

.navbar-light .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(0, 0, 0, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-light .navbar-text {
  color: rgba(0, 0, 0, 0.5);
}

.navbar-dark .navbar-brand {
  color: white;
}

.navbar-dark .navbar-brand:focus, .navbar-dark .navbar-brand:hover {
  color: white;
}

.navbar-dark .navbar-nav .nav-link {
  color: rgba(255, 255, 255, 0.5);
}

.navbar-dark .navbar-nav .nav-link:focus, .navbar-dark .navbar-nav .nav-link:hover {
  color: rgba(255, 255, 255, 0.75);
}

.navbar-dark .navbar-nav .nav-link.disabled {
  color: rgba(255, 255, 255, 0.25);
}

.navbar-dark .navbar-nav .show > .nav-link,
.navbar-dark .navbar-nav .active > .nav-link,
.navbar-dark .navbar-nav .nav-link.show,
.navbar-dark .navbar-nav .nav-link.active {
  color: white;
}

.navbar-dark .navbar-toggler {
  color: rgba(255, 255, 255, 0.5);
  border-color: rgba(255, 255, 255, 0.1);
}

.navbar-dark .navbar-toggler-icon {
  background-image: url("data:image/svg+xml;charset=utf8,%3Csvg viewBox='0 0 30 30' xmlns='http://www.w3.org/2000/svg'%3E%3Cpath stroke='rgba(255, 255, 255, 0.5)' stroke-width='2' stroke-linecap='round' stroke-miterlimit='10' d='M4 7h22M4 15h22M4 23h22'/%3E%3C/svg%3E");
}

.navbar-dark .navbar-text {
  color: rgba(255, 255, 255, 0.5);
}

/*
 * 2. BUTTONS
 */
.btn {
  font-weight: 400;
  border: 1px solid transparent;
  padding: 0.6rem 3rem;
  font-size: 1rem;
  line-height: 1.5;
  border-radius: 50px;
  -webkit-transition: all 0.15s ease-in-out;
  transition: all 0.15s ease-in-out;
}

.btn:focus, .btn.focus {
  outline: 0;
  -webkit-box-shadow: 0 0 0 3px rgba(144, 85, 162, 0.25);
  box-shadow: 0 0 0 3px rgba(144, 85, 162, 0.25);
}

.btn:active, .btn.active {
  background-image: none;
}

.btn-primary {
  color: #fff;
  background-color: #9055A2;
  border-color: #9055A2;
}

.btn-primary:hover {
  color: #fff;
  background-color: #7a4889;
  border-color: #724381;
}

.btn-primary:focus, .btn-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(144, 85, 162, 0.5);
  box-shadow: 0 0 0 3px rgba(144, 85, 162, 0.5);
}

.btn-primary.disabled, .btn-primary:disabled {
  background-color: #9055A2;
  border-color: #9055A2;
}

.btn-primary:active, .btn-primary.active,
.show > .btn-primary.dropdown-toggle {
  background-color: #7a4889;
  background-image: none;
  border-color: #724381;
}

.btn-secondary {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:hover {
  color: #fff;
  background-color: #727b84;
  border-color: #6c757d;
}

.btn-secondary:focus, .btn-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-secondary.disabled, .btn-secondary:disabled {
  background-color: #868e96;
  border-color: #868e96;
}

.btn-secondary:active, .btn-secondary.active,
.show > .btn-secondary.dropdown-toggle {
  background-color: #727b84;
  background-image: none;
  border-color: #6c757d;
}

.btn-success {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:hover {
  color: #fff;
  background-color: #218838;
  border-color: #1e7e34;
}

.btn-success:focus, .btn-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-success.disabled, .btn-success:disabled {
  background-color: #28a745;
  border-color: #28a745;
}

.btn-success:active, .btn-success.active,
.show > .btn-success.dropdown-toggle {
  background-color: #218838;
  background-image: none;
  border-color: #1e7e34;
}

.btn-info {
  color: #111;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:hover {
  color: #111;
  background-color: #23bcc9;
  border-color: #21b2bf;
}

.btn-info:focus, .btn-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-info.disabled, .btn-info:disabled {
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-info:active, .btn-info.active,
.show > .btn-info.dropdown-toggle {
  background-color: #23bcc9;
  background-image: none;
  border-color: #21b2bf;
}

.btn-warning {
  color: #111;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:hover {
  color: #111;
  background-color: #e0a800;
  border-color: #d39e00;
}

.btn-warning:focus, .btn-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-warning.disabled, .btn-warning:disabled {
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-warning:active, .btn-warning.active,
.show > .btn-warning.dropdown-toggle {
  background-color: #e0a800;
  background-image: none;
  border-color: #d39e00;
}

.btn-danger {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:hover {
  color: #fff;
  background-color: #c82333;
  border-color: #bd2130;
}

.btn-danger:focus, .btn-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-danger.disabled, .btn-danger:disabled {
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-danger:active, .btn-danger.active,
.show > .btn-danger.dropdown-toggle {
  background-color: #c82333;
  background-image: none;
  border-color: #bd2130;
}

.btn-light {
  color: #111;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:hover {
  color: #111;
  background-color: #e2e6ea;
  border-color: #dae0e5;
}

.btn-light:focus, .btn-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-light.disabled, .btn-light:disabled {
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-light:active, .btn-light.active,
.show > .btn-light.dropdown-toggle {
  background-color: #e2e6ea;
  background-image: none;
  border-color: #dae0e5;
}

.btn-dark {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:hover {
  color: #fff;
  background-color: #23272b;
  border-color: #1d2124;
}

.btn-dark:focus, .btn-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-dark.disabled, .btn-dark:disabled {
  background-color: #343a40;
  border-color: #343a40;
}

.btn-dark:active, .btn-dark.active,
.show > .btn-dark.dropdown-toggle {
  background-color: #23272b;
  background-image: none;
  border-color: #1d2124;
}

.btn-outline-primary {
  color: #9055A2;
  background-color: transparent;
  background-image: none;
  border-color: #9055A2;
}

.btn-outline-primary:hover {
  color: #fff;
  background-color: #9055A2;
  border-color: #9055A2;
}

.btn-outline-primary:focus, .btn-outline-primary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(144, 85, 162, 0.5);
  box-shadow: 0 0 0 3px rgba(144, 85, 162, 0.5);
}

.btn-outline-primary.disabled, .btn-outline-primary:disabled {
  color: #9055A2;
  background-color: transparent;
}

.btn-outline-primary:active, .btn-outline-primary.active,
.show > .btn-outline-primary.dropdown-toggle {
  color: #fff;
  background-color: #9055A2;
  border-color: #9055A2;
}

.btn-outline-secondary {
  color: #868e96;
  background-color: transparent;
  background-image: none;
  border-color: #868e96;
}

.btn-outline-secondary:hover {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-secondary:focus, .btn-outline-secondary.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
  box-shadow: 0 0 0 3px rgba(134, 142, 150, 0.5);
}

.btn-outline-secondary.disabled, .btn-outline-secondary:disabled {
  color: #868e96;
  background-color: transparent;
}

.btn-outline-secondary:active, .btn-outline-secondary.active,
.show > .btn-outline-secondary.dropdown-toggle {
  color: #fff;
  background-color: #868e96;
  border-color: #868e96;
}

.btn-outline-success {
  color: #28a745;
  background-color: transparent;
  background-image: none;
  border-color: #28a745;
}

.btn-outline-success:hover {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-success:focus, .btn-outline-success.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(40, 167, 69, 0.5);
}

.btn-outline-success.disabled, .btn-outline-success:disabled {
  color: #28a745;
  background-color: transparent;
}

.btn-outline-success:active, .btn-outline-success.active,
.show > .btn-outline-success.dropdown-toggle {
  color: #fff;
  background-color: #28a745;
  border-color: #28a745;
}

.btn-outline-info {
  color: #37cfdc;
  background-color: transparent;
  background-image: none;
  border-color: #37cfdc;
}

.btn-outline-info:hover {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-info:focus, .btn-outline-info.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
  box-shadow: 0 0 0 3px rgba(55, 207, 220, 0.5);
}

.btn-outline-info.disabled, .btn-outline-info:disabled {
  color: #37cfdc;
  background-color: transparent;
}

.btn-outline-info:active, .btn-outline-info.active,
.show > .btn-outline-info.dropdown-toggle {
  color: #fff;
  background-color: #37cfdc;
  border-color: #37cfdc;
}

.btn-outline-warning {
  color: #ffc107;
  background-color: transparent;
  background-image: none;
  border-color: #ffc107;
}

.btn-outline-warning:hover {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-warning:focus, .btn-outline-warning.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
  box-shadow: 0 0 0 3px rgba(255, 193, 7, 0.5);
}

.btn-outline-warning.disabled, .btn-outline-warning:disabled {
  color: #ffc107;
  background-color: transparent;
}

.btn-outline-warning:active, .btn-outline-warning.active,
.show > .btn-outline-warning.dropdown-toggle {
  color: #fff;
  background-color: #ffc107;
  border-color: #ffc107;
}

.btn-outline-danger {
  color: #dc3545;
  background-color: transparent;
  background-image: none;
  border-color: #dc3545;
}

.btn-outline-danger:hover {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-danger:focus, .btn-outline-danger.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
  box-shadow: 0 0 0 3px rgba(220, 53, 69, 0.5);
}

.btn-outline-danger.disabled, .btn-outline-danger:disabled {
  color: #dc3545;
  background-color: transparent;
}

.btn-outline-danger:active, .btn-outline-danger.active,
.show > .btn-outline-danger.dropdown-toggle {
  color: #fff;
  background-color: #dc3545;
  border-color: #dc3545;
}

.btn-outline-light {
  color: #f8f9fa;
  background-color: transparent;
  background-image: none;
  border-color: #f8f9fa;
}

.btn-outline-light:hover {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-light:focus, .btn-outline-light.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
  box-shadow: 0 0 0 3px rgba(248, 249, 250, 0.5);
}

.btn-outline-light.disabled, .btn-outline-light:disabled {
  color: #f8f9fa;
  background-color: transparent;
}

.btn-outline-light:active, .btn-outline-light.active,
.show > .btn-outline-light.dropdown-toggle {
  color: #fff;
  background-color: #f8f9fa;
  border-color: #f8f9fa;
}

.btn-outline-dark {
  color: #343a40;
  background-color: transparent;
  background-image: none;
  border-color: #343a40;
}

.btn-outline-dark:hover {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-outline-dark:focus, .btn-outline-dark.focus {
  -webkit-box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
  box-shadow: 0 0 0 3px rgba(52, 58, 64, 0.5);
}

.btn-outline-dark.disabled, .btn-outline-dark:disabled {
  color: #343a40;
  background-color: transparent;
}

.btn-outline-dark:active, .btn-outline-dark.active,
.show > .btn-outline-dark.dropdown-toggle {
  color: #fff;
  background-color: #343a40;
  border-color: #343a40;
}

.btn-lg {
  padding: 0.8rem 3.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
  border-radius: 50px;
}

.btn-sm {
  padding: 0.4rem 1.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
  border-radius: 50px;
}

/*
 * 3. TYPE
 */
body {
  font-family: "Open Sans", sans-serif;
  font-size: 1rem;
  font-weight: normal;
  line-height: 1.5;
  color: #212529;
  background-color: #fff;
}

a {
  color: #9055A2;
  text-decoration: none;
}

a:focus, a:hover {
  color: #633b70;
  text-decoration: underline;
}

h1,
h2,
h3,
h4,
h5,
h6,
.h1,
.h2,
.h3,
.h4,
.h5,
.h6 {
  margin-bottom: 0.5rem;
  font-family: inherit;
  font-weight: 800;
  line-height: 1.1;
  color: #2e324a;
}

h1,
.h1 {
  font-size: 2.9rem;
}

h2,
.h2 {
  font-size: 2.2rem;
}

h3,
.h3 {
  font-size: 1.75rem;
}

h4,
.h4 {
  font-size: 1.5rem;
}

h5,
.h5 {
  font-size: 1.25rem;
}

h6,
.h6 {
  font-size: 1rem;
}

.lead {
  font-size: 1.2rem;
  font-weight: 300;
  line-height: 1.8em;
}

.display-1 {
  font-size: 6rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-2 {
  font-size: 5.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-3 {
  font-size: 4.5rem;
  font-weight: 300;
  line-height: 1.1;
}

.display-4 {
  font-size: 3.5rem;
  font-weight: 300;
  line-height: 1.1;
}

hr {
  border-top: 1px solid rgba(0, 0, 0, 0.1);
}

small,
.small {
  font-size: 80%;
  font-weight: normal;
}

mark,
.mark {
  padding: 0.2em;
  background-color: #fcf8e3;
}

.blockquote {
  padding: 3rem 2rem;
  margin-bottom: 1rem;
  font-size: 1.05rem;
  border-left: 4px solid #9055A2;
}

.blockquote-footer {
  color: #868e96;
}

.blockquote-footer::before {
  content: "\2014 \00A0";
}

.text-primary {
  color: #9055A2 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #724381 !important;
}

/*
 * 4. PAGINATION
 */
.page-item:first-child .page-link {
  border-top-left-radius: 0.25rem;
  border-bottom-left-radius: 0.25rem;
}

.page-item:last-child .page-link {
  border-top-right-radius: 0.25rem;
  border-bottom-right-radius: 0.25rem;
}

.page-item.active .page-link {
  color: #fff;
  background-color: #9055A2;
  border-color: #9055A2;
}

.page-item.disabled .page-link {
  color: #868e96;
  background-color: #fff;
  border-color: #ddd;
}

.page-link {
  padding: 0.5rem 0.75rem;
  line-height: 1.25;
  color: #9055A2;
  background-color: #fff;
  border: 1px solid #ddd;
}

.page-link:focus, .page-link:hover {
  color: #633b70;
  text-decoration: none;
  background-color: #e9ecef;
  border-color: #ddd;
}

.pagination-lg .page-link {
  padding: 0.75rem 1.5rem;
  font-size: 1.25rem;
  line-height: 1.5;
}

.pagination-lg .page-item:first-child .page-link {
  border-top-left-radius: 0.3rem;
  border-bottom-left-radius: 0.3rem;
}

.pagination-lg .page-item:last-child .page-link {
  border-top-right-radius: 0.3rem;
  border-bottom-right-radius: 0.3rem;
}

.pagination-sm .page-link {
  padding: 0.25rem 0.5rem;
  font-size: 0.875rem;
  line-height: 1.5;
}

.pagination-sm .page-item:first-child .page-link {
  border-top-left-radius: 0.2rem;
  border-bottom-left-radius: 0.2rem;
}

.pagination-sm .page-item:last-child .page-link {
  border-top-right-radius: 0.2rem;
  border-bottom-right-radius: 0.2rem;
}

/*
* 5. UTILITIES
*/
.bg-primary {
  background-color: #9055A2 !important;
}

a.bg-primary:focus, a.bg-primary:hover {
  background-color: #724381 !important;
}

.bg-secondary {
  background-color: #868e96 !important;
}

a.bg-secondary:focus, a.bg-secondary:hover {
  background-color: #6c757d !important;
}

.bg-success {
  background-color: #28a745 !important;
}

a.bg-success:focus, a.bg-success:hover {
  background-color: #1e7e34 !important;
}

.bg-info {
  background-color: #37cfdc !important;
}

a.bg-info:focus, a.bg-info:hover {
  background-color: #21b2bf !important;
}

.bg-warning {
  background-color: #ffc107 !important;
}

a.bg-warning:focus, a.bg-warning:hover {
  background-color: #d39e00 !important;
}

.bg-danger {
  background-color: #dc3545 !important;
}

a.bg-danger:focus, a.bg-danger:hover {
  background-color: #bd2130 !important;
}

.bg-light {
  background-color: #f8f9fa !important;
}

a.bg-light:focus, a.bg-light:hover {
  background-color: #dae0e5 !important;
}

.bg-dark {
  background-color: #343a40 !important;
}

a.bg-dark:focus, a.bg-dark:hover {
  background-color: #1d2124 !important;
}

.border-primary {
  border-color: #9055A2 !important;
}

.border-secondary {
  border-color: #868e96 !important;
}

.border-success {
  border-color: #28a745 !important;
}

.border-info {
  border-color: #37cfdc !important;
}

.border-warning {
  border-color: #ffc107 !important;
}

.border-danger {
  border-color: #dc3545 !important;
}

.border-light {
  border-color: #f8f9fa !important;
}

.border-dark {
  border-color: #343a40 !important;
}

.text-primary {
  color: #9055A2 !important;
}

a.text-primary:focus, a.text-primary:hover {
  color: #724381 !important;
}

.text-secondary {
  color: #868e96 !important;
}

a.text-secondary:focus, a.text-secondary:hover {
  color: #6c757d !important;
}

.text-success {
  color: #28a745 !important;
}

a.text-success:focus, a.text-success:hover {
  color: #1e7e34 !important;
}

.text-info {
  color: #37cfdc !important;
}

a.text-info:focus, a.text-info:hover {
  color: #21b2bf !important;
}

.text-warning {
  color: #ffc107 !important;
}

a.text-warning:focus, a.text-warning:hover {
  color: #d39e00 !important;
}

.text-danger {
  color: #dc3545 !important;
}

a.text-danger:focus, a.text-danger:hover {
  color: #bd2130 !important;
}

.text-light {
  color: #f8f9fa !important;
}

a.text-light:focus, a.text-light:hover {
  color: #dae0e5 !important;
}

.text-dark {
  color: #343a40 !important;
}

a.text-dark:focus, a.text-dark:hover {
  color: #1d2124 !important;
}
 <style/>
    
        <script src="https://oss.maxcdn.com/html5shiv/3.7.3/html5shiv.min.js"></script>
        <script src="https://oss.maxcdn.com/respond/1.4.2/respond.min.js"></script><![endif]-->
  </head>
  <body>
    <!-- navbar-->
    <header class="header">
      <nav class="navbar navbar-expand-lg fixed-top"><a href="index.html" class="navbar-brand">Landy</a>
        <button type="button" data-toggle="collapse" data-target="#navbarSupportedContent" aria-controls="navbarSupportedContent" aria-expanded="false" aria-label="Toggle navigation" class="navbar-toggler navbar-toggler-right"><span></span><span></span><span></span></button>
        <div id="navbarSupportedContent" class="collapse navbar-collapse">
          <ul class="navbar-nav ml-auto align-items-start align-items-lg-center">
            <li class="nav-item"><a href="#about-us" class="nav-link link-scroll">About Us</a></li>
            <li class="nav-item"><a href="#features" class="nav-link link-scroll">Features</a></li>
            <li class="nav-item"><a href="#testimonials" class="nav-link link-scroll">Testimonials</a></li>
            <li class="nav-item"><a href="text.html" class="nav-link">Text Page</a></li>
          </ul>
          <div class="navbar-text">   
            <!-- Button trigger modal--><a href="#" data-toggle="modal" data-target="#exampleModal" class="btn btn-primary navbar-btn btn-shadow btn-gradient">Sign Up</a>
          </div>
        </div>
      </nav>
    </header>
    <!-- Modal-->
    <div id="exampleModal" tabindex="-1" role="dialog" aria-labelledby="exampleModalLabel" aria-hidden="true" class="modal fade">
      <div role="document" class="modal-dialog">
        <div class="modal-content">
          <div class="modal-header">
            <h5 id="exampleModalLabel" class="modal-title">Sign Up Modal</h5>
            <button type="button" data-dismiss="modal" aria-label="Close" class="close"><span aria-hidden="true">×</span></button>
          </div>
          <div class="modal-body">
            <form id="signupform" action="#">
              <div class="form-group">
                <label for="fullname">Full Name</label>
                <input type="text" name="fullname" placeholder="Full Name" id="fullname">
              </div>
              <div class="form-group">
                <label for="username">User Name</label>
                <input type="text" name="username" placeholder="User Name" id="username">
              </div>
              <div class="form-group">
                <label for="email">Email Address</label>
                <input type="text" name="email" placeholder="Email Address" id="email">
              </div>
              <div class="form-group">
                <button type="submit" class="submit btn btn-primary btn-shadow btn-gradient">Signup</button>
              </div>
            </form>
          </div>
        </div>
      </div>
    </div>
    <section id="hero" class="hero hero-home bg-gray">
      <div class="container">
        <div class="row d-flex">
          <div class="col-lg-6 text order-2 order-lg-1">
            <h1>Landy &mdash; Bootstrap&nbsp;4 landing page</h1>
            <p class="hero-text">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour</p>
            <div class="CTA"><a href="#features" class="btn btn-primary btn-shadow btn-gradient link-scroll">Discover More</a><a href="#" class="btn btn-outline-primary">Sign Up Now</a></div>
          </div>
          <div class="col-lg-6 order-1 order-lg-2"><img src="img/Macbook.png" alt="..." class="img-fluid"></div>
        </div>
      </div>
    </section>
    <section id="browser" class="browser">
      <div class="container">
        <div class="row d-flex justify-content-center"> 
          <div class="col-lg-8 text-center">
            <h2 class="h3 mb-5">How it works</h2>
            <div class="browser-mockup">
              <div id="nav-tabContent" class="tab-content">
                <div id="nav-first" role="tabpanel" aria-labelledby="nav-first-tab" class="tab-pane fade show active"><img src="img/preview-3.png" alt="..." class="img-fluid"></div>
                <div id="nav-second" role="tabpanel" aria-labelledby="nav-second-tab" class="tab-pane fade"><img src="img/preview-2.png" alt="..." class="img-fluid"></div>
                <div id="nav-third" role="tabpanel" aria-labelledby="nav-third-tab" class="tab-pane fade"><img src="img/preview-1.png" alt="..." class="img-fluid"></div>
              </div>
            </div>
          </div>
        </div>
        <div id="myTab" role="tablist" class="nav nav-tabs">
          <div class="row">
            <div class="col-md-4"><a id="nav-first-tab" data-toggle="tab" href="#nav-first" role="tab" aria-controls="nav-first" aria-expanded="true" class="nav-item nav-link active"> <span class="number">1</span>Choose any website to turn into an interactive pinboard for feedback</a></div>
            <div class="col-md-4"><a id="nav-second-tab" data-toggle="tab" href="#nav-second" role="tab" aria-controls="nav-second" class="nav-item nav-link"> <span class="number">2</span>Choose any website to turn into an interactive pinboard for feedback</a></div>
            <div class="col-md-4"><a id="nav-third-tab" data-toggle="tab" href="#nav-third" role="tab" aria-controls="nav-third" class="nav-item nav-link"> <span class="number">3</span>Choose any website to turn into an interactive pinboard for feedback</a></div>
          </div>
        </div>
      </div>
    </section>
    <section id="about-us" class="about-us bg-gray">
      <div class="container">
        <h2>About Us</h2>
        <div class="row">
          <p class="lead col-lg-10">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. If you are going to use a passage of Lorem Ipsum, you need to be sure there isn't anything embarrassing hidden in the middle of text. or randomised words which don't look even slightly believable. </p>
        </div><a href="#" class="btn btn-primary btn-shadow btn-gradient">Discover More</a>
      </div>
    </section>
    <section id="features" class="features">
      <div class="container">
        <div class="row d-flex align-items-center">
          <div class="text col-lg-6 order-2 order-lg-1">
            <div class="icon"><img src="img/medal.svg" alt="..." class="img-fluid"></div>
            <h4>Your peace of mind is our business</h4>
            <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. </p><a href="#" class="btn btn-primary btn-shadow btn-gradient">View More</a>
          </div>
          <div class="image col-lg-6 order-1 order-lg-2"><img src="img/feature-1.png" alt="..." class="img-fluid"></div>
        </div>
        <div class="row d-flex align-items-center">
          <div class="image col-lg-6"><img src="img/feature-2.png" alt="..." class="img-fluid"></div>
          <div class="text col-lg-6">
            <div class="icon"><img src="img/hourglass.svg" alt="..." class="img-fluid"></div>
            <h4>Your peace of mind is our business</h4>
            <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. </p><a href="#" class="btn btn-primary btn-shadow btn-gradient">View More</a>
          </div>
        </div>
        <div class="row d-flex align-items-center">
          <div class="text col-lg-6 order-2 order-lg-1">
            <div class="icon"><img src="img/cup.svg" alt="..." class="img-fluid"></div>
            <h4>Your peace of mind is our business</h4>
            <p>There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour, or randomised words which don't look even slightly believable. </p><a href="#" class="btn btn-primary btn-shadow btn-gradient">View More</a>
          </div>
          <div class="image col-lg-6 order-1 order-lg-2"><img src="img/feature-3.png" alt="..." class="img-fluid"></div>
        </div>
      </div>
    </section>
    <section id="extra-features" class="extra-features bg-primary">
      <div class="container text-center">
        <header>
          <h2>More great features             </h2>
          <div class="row">
            <p class="lead col-lg-8 mx-auto">There are many variations of passages of Lorem Ipsum available, but the majority have suffered alteration in some form.</p>
          </div>
        </header>
        <div class="grid row">
          <div class="item col-lg-4 col-md-6">
            <div class="icon"> <i class="icon-diploma"></i></div>
            <h3 class="h5">Lorem Ipsum Dolor</h3>
            <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour.</p>
          </div>
          <div class="item col-lg-4 col-md-6">
            <div class="icon"> <i class="icon-folder-1"></i></div>
            <h3 class="h5">Lorem Ipsum Dolor</h3>
            <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour.</p>
          </div>
          <div class="item col-lg-4 col-md-6">
            <div class="icon"> <i class="icon-gears"></i></div>
            <h3 class="h5">Lorem Ipsum Dolor</h3>
            <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour.</p>
          </div>
          <div class="item col-lg-4 col-md-6">
            <div class="icon"> <i class="icon-management"></i></div>
            <h3 class="h5">Lorem Ipsum Dolor</h3>
            <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour.</p>
          </div>
          <div class="item col-lg-4 col-md-6">
            <div class="icon"> <i class="icon-pie-chart"></i></div>
            <h3 class="h5">Lorem Ipsum Dolor</h3>
            <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour.</p>
          </div>
          <div class="item col-lg-4 col-md-6">
            <div class="icon"> <i class="icon-quality"></i></div>
            <h3 class="h5">Lorem Ipsum Dolor</h3>
            <p>Lorem Ipsum available, but the majority have suffered alteration in some form, by injected humour.</p>
          </div>
        </div>
      </div>
    </section>
    <div class="tlinks">Collect from <a href="http://www.cssmoban.com/"  title="网站模板">网站模板</a></div>
    <section id="testimonials" class="testimonials">
      <div class="container">
        <header class="text-center no-margin-bottom">   
          <h2>Happy Clients</h2>
          <p class="lead">There are many variations of passages of Lorem Ipsum available, but the majority have</p>
        </header>
        <div class="owl-carousel owl-theme testimonials-slider"> 
          <div class="item-holder">
            <div class="item">
              <div class="avatar"><img src="img/avatar-3.jpg" alt="..." class="img-fluid"></div>
              <div class="text">
                <div class="quote"><img src="img/quote.svg" alt="..." class="img-fluid"></div>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever</p><strong class="name">Jessica Watson</strong>
              </div>
            </div>
          </div>
          <div class="item-holder">
            <div class="item">
              <div class="avatar"><img src="img/avatar-5.jpg" alt="..." class="img-fluid"></div>
              <div class="text">
                <div class="quote"><img src="img/quote.svg" alt="..." class="img-fluid"></div>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever</p><strong class="name">Sarrah Wood</strong>
              </div>
            </div>
          </div>
          <div class="item-holder">
            <div class="item">
              <div class="avatar"><img src="img/avatar-3.jpg" alt="..." class="img-fluid"></div>
              <div class="text">
                <div class="quote"><img src="img/quote.svg" alt="..." class="img-fluid"></div>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever</p><strong class="name">Jessica Watson</strong>
              </div>
            </div>
          </div>
          <div class="item-holder">
            <div class="item">
              <div class="avatar"><img src="img/avatar-5.jpg" alt="..." class="img-fluid"></div>
              <div class="text">
                <div class="quote"><img src="img/quote.svg" alt="..." class="img-fluid"></div>
                <p>Lorem Ipsum is simply dummy text of the printing and typesetting industry. Lorem Ipsum has been the industry's standard dummy text ever</p><strong class="name">Sarrah Wood</strong>
              </div>
            </div>
          </div>
        </div>
      </div>
    </section>
    <section id="newsletter" class="newsletter bg-gray">
      <div class="container text-center">
        <h2>Subscribe to Newsletter</h2>
        <p class="lead">There are many variation passages of lorem ipsum, but the majority have</p>
        <div class="form-holder">
          <form id="newsletterForm" action="#">
            <div class="form-group">
              <input type="email" name="email" id="email" placeholder="Enter Your Email Address">
              <button type="submit" class="btn btn-primary btn-gradient submit">Subscribe</button>
            </div>
          </form>
        </div>
      </div>
    </section>
    <div id="scrollTop">
      <div class="d-flex align-items-center justify-content-end"><i class="fa fa-long-arrow-up"></i>To Top</div>
    </div>
    <footer class="main-footer">
      <div class="container">
        <div class="row">
          <div class="col-lg-3 col-md-6"><a href="#" class="brand">Landy</a>
            <ul class="contact-info list-unstyled">
              <li><a href="mailto:sales@landy.com">Sales@Landy.com</a></li>
              <li><a href="tel:123456789">+00 123 456 789</a></li>
            </ul>
            <ul class="social-icons list-inline">
              <li class="list-inline-item"><a href="#" target="_blank" title="Facebook"><i class="fa fa-facebook"></i></a></li>
              <li class="list-inline-item"><a href="#" target="_blank" title="Twitter"><i class="fa fa-twitter"></i></a></li>
              <li class="list-inline-item"><a href="#" target="_blank" title="Instagram"><i class="fa fa-instagram"></i></a></li>
              <li class="list-inline-item"><a href="#" target="_blank" title="Pinterest"><i class="fa fa-pinterest"></i></a></li>
            </ul>
          </div>
          <div class="col-lg-3 col-md-6">
            <h5>Selected Cases</h5>
            <ul class="links list-unstyled">
              <li> <a href="#">Guess Conntect</a></li>
              <li> <a href="#">Postly</a></li>
              <li> <a href="#">Iris Vor Arnim</a></li>
              <li> <a href="#">Yapital</a></li>
            </ul>
          </div>
          <div class="col-lg-3 col-md-6">
            <h5>Selected Cases</h5>
            <ul class="links list-unstyled">
              <li> <a href="#">Guess Conntect</a></li>
              <li> <a href="#">Postly</a></li>
              <li> <a href="#">Iris Vor Arnim</a></li>
              <li> <a href="#">Yapital</a></li>
            </ul>
          </div>
          <div class="col-lg-3 col-md-6">
            <h5>Selected Cases</h5>
            <ul class="links list-unstyled">
              <li> <a href="#">Guess Conntect</a></li>
              <li> <a href="#">Postly</a></li>
              <li> <a href="#">Iris Vor Arnim</a></li>
              <li> <a href="#">Yapital</a></li>
            </ul>
          </div>
        </div>
      </div>
      <div class="copyrights">
        <div class="container">
          <div class="row">
            <div class="col-md-7">
              <p>&copy; 2017 Bootstrapious. All rights reserved.                        </p>
            </div>
            <div class="col-md-5 text-right">
              <p>More Templates <a href="http://www.cssmoban.com/" target="_blank" title="模板之家">模板之家</a> - Collect from <a href="http://www.cssmoban.com/" title="网页模板" target="_blank">网页模板</a> </p>
              
            </div>
          </div>
        </div>
      </div>
    </footer>
    <!-- Javascript files-->
    <script src="https://code.jquery.com/jquery-3.2.1.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js"> </script>
    <script src="vendor/bootstrap/js/bootstrap.min.js"></script>
    <script src="vendor/jquery.cookie/jquery.cookie.js"> </script>
    <script src="vendor/owl.carousel/owl.carousel.min.js"></script>
    <script src="js/front.js"></script>
      </body>
</html>
