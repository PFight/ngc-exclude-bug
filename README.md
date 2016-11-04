# ngc-exclude-bug

Minimal example to reproduce @angluar/compiler-cli bug

### Install

        npm install

### Run

        ngc -p tsconfig.ngc.json

### Bug

ngc ignores `exclude` option in tsconfig.ngc.json, and compiles all in `./` dirrectory, including everything in `node_modules`. See `aot` directory for output.
