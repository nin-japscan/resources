## (∩｀-´)⊃・ﾟ✦ Resources

`config` – App configuration that is required to run the app. Assume the following structure:

```json
{
  "domain": "japscan.si",
  "endpoints": {
    "search": ...,
    "manga": ...,
    "bds": ...
  },
  "maintenance": false,
  "minVersion": "0.0.1",
  "updatedAt": 1756393252338
}
```

`payload` – JS code to be injected, which will be used to extract data from the `japscan` website. The code is encrypted
to avoid easy RE.
