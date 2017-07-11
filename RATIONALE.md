This file should be a journal of design decisions.

E-bergi code will change many, many hands so it should be super easy to read and maintain.

## Why are articles in /y/?

To keep compatibility with old e-bergi links.

## Hugo documentation says you should use `singular = "plural"` notation for taxonomies...

That gets hairy too quickly, especially with two languages in place. Let's keep yazar = "yazar" and be fine with it.

The only drawback about this approach is that it breaks the convention about all code being in English and outfacing strings Turkish. Authors of an article are in `.Params.yazar` and author data is kept in `Site.Data.authors`. See `layouts/index.html` and `layouts/taxonomy/yazar.html` for their usage.
