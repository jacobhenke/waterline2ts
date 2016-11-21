# waterline2ts

Translates [Waterline ORM modules](http://sailsjs.org/documentation/concepts/models-and-orm/models) from Sails.js into [TypeScript interfaces](https://www.typescriptlang.org/docs/handbook/interfaces.html).

## Usage

```bash
npm -g install waterline2ts
cd /directory/containing/models
waterline2ts
```

By default, the script will use the current working directory as the waterline models and output the typescript interfaces to a new folder `ts/`, and will _not_ overwrite existing *.ts files.

See `waterline2ts -h` for more.

## License

MIT
