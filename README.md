# inspire [![Deno](https://github.com/sant123/inspire/actions/workflows/deno.yml/badge.svg)](https://github.com/sant123/inspire/actions/workflows/deno.yml) [![](https://badgen.net/badge/Open%20with/Runme/5B3ADF?icon=https://runme.dev/img/logo.svg)](https://www.runme.dev/api/runme?repository=git%40github.com%3Astateful%2Flinkerd-website.git&fileToOpen=tests/runme/README.md)

Based on the inspire Artisan command from
[Laravel](https://github.com/laravel/framework/blob/10.x/src/Illuminate/Foundation/Inspiring.php).

## Installation

To test if you already have Deno installed run:
If this prints the Deno version to the console the installation was successful.

```sh { closeTerminalOnSuccess=false interactive=false }
deno --version
```

To update a previously installed version of Deno, run:

```sh
deno upgrade
```

To install Deno via homebrew on macOS:

```sh
# macOS
brew bundle --no-lock
```

Or the installer which also works on Linux:

```sh
# macOS or Linux
curl -fsSL https://deno.land/x/install/install.sh | sh
```

Add Deno to your path:

```sh
export DENO_INSTALL="$HOME/.deno"
export PATH="$DENO_INSTALL/bin:$PATH"
```

## Use the inspire module

```bash { background=true interactive=false }
deno install -fq https://deno.land/x/inspire/mod.ts
```

<img src="./images/inspire.png">

## Usage

```ts
// example.ts
import { quotes } from "https://deno.land/x/inspire/mod.ts";
console.log(quotes);
// Your code here...
```

## Run an example

```bash { background=true closeTerminalOnSuccess=false }
deno run example/demo.ts
```

## Credits

https://laravel.com/
