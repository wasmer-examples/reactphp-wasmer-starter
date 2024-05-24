This is a simple [ReactPHP](https://reactphp.org/) application starter

## Getting Started

Modify the logic of your the PHP application in the `app/index.php` file.

You can run things locally with:

```
$ php app/index.php
```

Or you can also use `wasmer run` to run it locally (check out the [Wasmer install guide](https://docs.wasmer.io/install)):

```console
$ wasmer run . --net
```

Open [http://localhost:8080](http://localhost:8080) with your browser to see the result.


## Deploy on Wasmer Edge

The easiest way to deploy your PHP app is to use the [Wasmer Edge](https://wasmer.io/products/edge).

Live example: https://wordpress-php-starter.wasmer.app/

Run this commmand to deploy to Wasmer Edge:

```bash
wasmer deploy
```
