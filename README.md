# inspire [![Deno](https://github.com/sant123/inspire/actions/workflows/deno.yml/badge.svg)](https://github.com/sant123/inspire/actions/workflows/deno.yml) [![](https://badgen.net/badge/Open%20with/Runme/5B3ADF?icon=https://runme.dev/img/logo.svg)](https://www.runme.dev/api/runme?repository=git%40github.com%3Asant123%2Finspire.git)

Based on the inspire Artisan command from
[Laravel](https://github.com/laravel/framework/blob/10.x/src/Illuminate/Foundation/Inspiring.php).

## Installation

```sh { background=true interactive=false }
deno install -f https://deno.land/x/inspire/mod.ts
```

## Run it

```sh { background=true }
inspire
```

In case you're getting command not found error, please esnure you have deno added to your PATH

```sh
export DENO_INSTALL="$HOME/.deno"
export PATH="$DENO_INSTALL/bin:$PATH"
```

Try it without installing

```sh { background=true }
deno run https://deno.land/x/inspire/mod.ts
```

<img src="./images/inspire.png">

## Usage

You can use the quotes in your library if needed:

```ts
// example.ts
import { quotes } from "https://deno.land/x/inspire/mod.ts";
console.log(quotes);
// Your code here...
```

Run a demo

```sh { background=true closeTerminalOnSuccess=false }
deno run example/demo.ts
```

## Credits

https://laravel.com/
