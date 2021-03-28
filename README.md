# parser-template

Given the input:
```
Random text
**Hello World**
Random text
```

This will parse the file for lines containing `**` and print them

## Why?

This is a template to be used for other parsers. I don't know rust at all so this is a learning process. This will eventually be used in a system where this will be in a container. The container will be passed a link to a file on s3. This will take a parse that file, then return the results to the calling system

## How?

`cargo run` will execute the program and let it parse `src/sample.log`