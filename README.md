# PHP - Getting Started
## Differences between PHP and Javascript
### Implementation
- XAMPP needs to be running in order for our PHP pages to execute. The web directory will be fixed, as opposed to Node where we can boot up a server where ever we want.
- PHP is a view compiling language very similar to EJS. Imagine a PHP file as an upgraded HTML file. The PHP run-time will ignore HTML and will only execute code between the `<?php` and `?>` tags. By default it will respond with the HTML and whatever the PHP resolved to (usually HTML).
- Although PHP pages will often represent an HTML page (including a `DOCTYPE` and elements such as `head`, `body`, etc), it doesn't have to. Some pages will only hold PHP code (still between `<?php` and `?>` tags) that do not output any HTML.
- Unlike Javascript, PHP files can be easily included in other PHP files using one of the following functions:
    - `include()`
    - `require()`
    - `include_once()`
    - `require_once()`
- There are no asynchronous events in PHP.
- Functions are not first-class, meaning there are no callback functions in PHP.

### Syntax (primary differences)
- Variables: There are no declaration keywords. Instead, variables are created and returned with the `$` symbol:

    ```php
    $day = 'Monday`;
    ```
- Arrays
- Objects