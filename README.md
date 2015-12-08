# snappy-cache-snappy-codec

An optional extension for snappy-cache to use snappy compression.

```
npm install snappy-cache
npm install snappy-cache-snappy-codec
```

```
var snappyCache = new SnappyCache({
  codec: require('snappy-cache-snappy-codec'),
  prefix: 'snappy-cache:'
});
```
