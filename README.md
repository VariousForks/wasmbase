# Base module for WASDK experiment

## Install wasdk and other dependencies.

npm install

## Build wasmbase

node_modules/.bin/wasdk ez lib/wasmbase.json

## Build test

Most of the code in 'test/' is generated by the `wasdk idl test.idl` command.

node_modules/.bin/wasdk ez test/test.json

## Run test example

Open test.html in the browser.
