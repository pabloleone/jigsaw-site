---
extends: _layouts.documentation
section: documentation_content
---

## Installation

### Installing Globally

1. Install Jigsaw globally via Composer:

    ```
    $ composer global require jigsaw/jigsaw
    ```

    > Make sure `~/.composer/vendor/bin` is in your `$PATH`.


2. Initialize a new project:
    
    ```
    $ jigsaw init my-site
    ```

### Installing Locally

If you run into dependency conflicts when trying to install Jigsaw globally, you can always install it locally on a per site basis.

1. Create a folder for your site:

    ```
    $ mkdir my-site && cd my-site
    ```

2. Install Jigsaw via Composer:

    ```
    $ composer require jigsaw/jigsaw
    ```

3. Initialize a new project in the current folder:

    ```
    $ ./vendor/bin/jigsaw init
    ```