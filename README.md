<!-- tyhp-readme:start -->
# tyhpdef/fig-http-message-util

Tyhp type definitions for `fig/http-message-util` `1.1.5`.

```bash
composer require --dev tyhpdef/fig-http-message-util:1.1.5
```

This is a metapackage. Composer also installs `tyhpdef/fig-http-message-util-impl` (type files).
Require **this** name, not `tyhpdef/fig-http-message-util-impl`.

See https://tyhplang.com.

## Maintain `fig/http-message-util`? Ship the types yourself

If you are a Packagist maintainer of `fig/http-message-util`, you can take over these
types.

Copy `_tyhpdef/` from **`tyhpdef/fig-http-message-util-impl`** (Apache-2.0; keep the `NOTICE`).
Then either:

1. **Bundle** the files in `fig/http-message-util` and set `extra.tyhp.package` on
   that `composer.json`, plus
   `"replace": { "tyhpdef/fig-http-message-util": "self.version" }`, or
2. **Publish a sibling** types package under your vendor, versioned with
   `fig/http-message-util` (same `X.Y.Z`). Set `extra.tyhp.package` there,
   `require` `fig/http-message-util` with a real constraint,
   `"replace": { "tyhpdef/fig-http-message-util": "self.version" }`, and set
   `extra.tyhp.tyhpdef` on `fig/http-message-util` to your sibling’s Composer name.

Ship that to Packagist first, then open an issue:

https://github.com/tyhpproject/tyhp-runtime-src/issues/new?template=tyhpdef-ownership.yml

We verify Packagist ownership and that the types parse and cover the PHP
API, then stop publishing community tags for those versions. We do not
transfer the `tyhpdef/fig-http-message-util` Packagist name.

Full process: `TYHPDEF_OWNERSHIP.md` in
https://github.com/tyhpproject/tyhp-runtime-src
<!-- tyhp-readme:end -->
