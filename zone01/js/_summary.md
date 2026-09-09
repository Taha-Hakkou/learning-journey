# JavaScript

## piscine-js

* js under the hood

## make-your-game

* [60 fps](https://www.algolia.com/blog/engineering/60-fps-performant-web-animations-for-optimal-ux)
* frame drops
* [RequestAnimationFrame](https://developer.mozilla.org/en-US/docs/Web/API/Window/requestAnimationFrame)
* layers
* css paint
* no canvas
* Developer Tools (using hot keys) -> [firefox](https://developer.mozilla.org/en-US/docs/Learn_web_development/Howto/Tools_and_setup/What_are_browser_developer_tools) + [chrome](https://developer.chrome.com/docs/devtools/)
  - Performance (record actions) -> drop frames (note: we disabled acceleration - gpu -, because campus posts gpu caused some dropped frames !)
  - ctrl+shift+p : command palette (fps + layers + Paint Flashing option...)
* [event loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Execution_model)

* noscript tag
* mime type
* window.dispatchEvent(new CustomEvent())
* esdoc
* commomjs (cjs)
* add a label to a loop to  break it whenever you need
* localStorage (types of browser storage)
* [junk/stutter animation](https://addyosmani.com/blog/making-a-site-jank-free/)

+ check bonuses:
  * score handling
    - Creating and using an API
      + POST requests
      + GET requests
    - JSON
    - Sorting algorithms
  * history
    - Game story mode
  * different-maps
    - [tile maps](https://developer.mozilla.org/en-US/docs/Games/Techniques/Tilemaps) + tile editors + tileset...
    - Image manipulation
    - Rendering

## real-time-forum

* sqlite (sql)
* [websockets](https://en.wikipedia.org/wiki/WebSocket) (golang: gorilla + js)
* [spa](https://en.wikipedia.org/wiki/Single-page_application)
* throttle, debounce
* bcrypt
* uuid
* go [routines](https://golangbot.com/goroutines/) + [channels](https://medium.com/rungo/anatomy-of-channels-in-go-concurrency-in-go-1ec336086adb)
* js event list, mainly the Keyboard events and the Focus events
* shared workers

+ check code

## graphql

* graphql (+ [graphiql](https://github.com/graphql/graphiql): introspecting the API)
  types of querying (normal, nested and using arguments)
* [svg](https://developer.mozilla.org/en-US/docs/Web/SVG)
* basic authentication + base64 (identifier + pawword)
* [jwt](https://www.jwt.io/introduction#what-is-json-web-token) (bearer authentication)
* browser storage types
* hosting services: netlify, vercel, github pages...

check code

## social network

* Some of the most known JS frameworks around are: Next.js, Vue.js, Svelte, Mithril...
* JS frameworks are different from JS libraries. JS libraries contain code snippets that are used to perform common JavaScript functions, while frameworks will help you by laying out the groundwork/building the bases for your JS project.
* swagger (for backend documentation)
* frontend & backend definitions
* since HTTP is a stateless protocol, we can use several ways to overcome and authenticate a client/user.
* image handlng in professional projects.
* [caddy](https://caddyserver.com/docs/) server (written in go)
* the database library [SQLite](https://www.sqlite.org/index.html).
* [erd](https://www.smartdraw.com/entity-relationship-diagram/)
* database migrations: e.g. [golang-migrate](https://github.com/golang-migrate/migrate)
* docker compose: [setting up docker](https://docs.docker.com/get-started/)
* authentication: sessions & cookies
* basics of encryption
* Next / NextAuth
* [sessions](https://cheatsheetseries.owasp.org/cheatsheets/Session_Management_Cheat_Sheet.html#session-management-waf-protections) and [cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)

check code (repository queries folder)

## mini-framework

* a framework is different from a library. When you call a method from a library, you are in control. But with a framework, the control is inverted: the framework calls you.
* [markdown](https://www.markdownguide.org/getting-started/)
* JS framework features:
  - Abstracting the DOM
  - Routing System
  - State Management
  - Event Handling
* framework documentation
* Abstracting the DOM (The DOM can be seen as a big object -> how different frameworks handle that ?!), for example:
  - [Virtual DOM](https://bitsofco.de/understanding-the-virtual-dom/) : to compare with the real DOM and change just what is needed.
  - [Data Binding](https://learn.microsoft.com/en-us/dotnet/desktop/wpf/data/?redirectedfrom=MSDN) : binds together two data sources and keeps them synchronized
  - [Templating](https://medium.com/@BuildMySite1/javascript-templating-what-is-templating-7ff49d97db6b) : refers to the client side data binding method implemented with the JavaScript language.
  - ...
  - have to take into account the events, children and attributes of each element of the DOM.
* Routing System (refers to the synchronization of the state of the app with the URL)
  - a simple way to change the URL through actions of the user that will also change the state.
* State Management (the outcome of all the actions that the user has taken since the page loaded)
* Event Handling
* [todoMVC](https://todomvc.com/examples/react/dist/) app examples with different frameworks.

* can see live dom changes in: dev tools > inspector

## bomberman-dom

- [`requestAnimationFrame`](https://developer.mozilla.org/en-US/docs/Web/API/window/requestAnimationFrame)
- [Event loop](https://developer.mozilla.org/en-US/docs/Web/JavaScript/EventLoop)
- FPS
- [Animation performance and frame rate](https://developer.mozilla.org/en-US/docs/Web/Performance/Animation_performance_and_frame_rate)
- webSockets
- Synchronization
- Developer Tools
  - [Firefox](https://developer.mozilla.org/en-US/docs/Learn/Common_questions/What_are_browser_developer_tools)
  - [Chrome](https://developers.google.com/web/tools/chrome-devtools)
- [Web-GL](https://get.webgl.org/)


==================================================================================================

### stock-exchange-sim

* Priority based project scheduling is a quick and easy heuristic scheduling technique that makes use of two components to construct a resource feasible project schedule, a [priority rule and a schedule generation scheme](http://www.pmknowledgecenter.com/node/256).

* Here are some ways to schedule a scheme:
  - [Serial schedule generation scheme](http://www.pmknowledgecenter.com/dynamic_scheduling/baseline/optimizing-regular-scheduling-objectives-schedule-generation-schemes): selects the activities one by one from the list and schedules them as-soon-as-possible in the schedule.

  - [Parallel schedule generation scheme](http://www.pmknowledgecenter.com/dynamic_scheduling/baseline/optimizing-regular-scheduling-objectives-schedule-generation-schemes): selects at each predefined time period the activities available to be scheduled and schedules them in the list as long as enough resources are available.
 

### mister-quiz

* php/laravel
* mvc design pattern
* blade templates
* php artisan
* XAMPP is the most popular PHP development environment and unites useful tools in order to make web development easier. It pretty much uses Apache2 (an http web server host), MySQL (a database management service) and phpMyAdmin (a web MySQL administration app).

### shop

* ruby/rails
* [Devise](https://github.com/heartcombo/devise) which is a flexible authentication solution for Rails based on Warden.
* Ruby on Rails:
  - Ruby is a programming language similar to Python and Perl. It is dynamically typed, interpreted, and can be modified at runtime (such as adding new methods to classes). It has many shortcuts that makes it very clean, methods are rarely over 10 lines. It has good RegEx support and works well for shell scripting.
  - Rails is a gem, or a Ruby library. Rails helps make web applications, providing classes for saving to the database, handling URLs and displaying html (along with a webserver, maintenance tasks, and much more).
* ruby bundle

### netfix

* python/django
* django templates
