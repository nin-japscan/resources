## (∩｀-´)⊃・ﾟ✦ Resources

`config` – App configuration that **is** required to run the app. It contains:

```dotenv
# Timestamp that indicates the last time the config was updated.
UPDATED_AT=1755165905000
# Domain of the Japscan website
DOMAIN=japscan.si
# Lifespan of a Cloudflare token in milliseconds.
TOKEN_EXP=1800000
# App availability flag.
# Pause all Japscan-related operations when MAINTENANCE=true
MAINTENANCE=true|false
```

`payload` – JS code to be injected, which will be used to extract data from the Japscan website. The code is encrypted
to avoid easy reverse engineering.
