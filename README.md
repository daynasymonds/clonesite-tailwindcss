# clonesite-tailwindcss

This is a recreation of the freely available [Zeal Taste Webflow design template](https://webflow.com/templates/html/zealtaste-food-website-template) using [Tailwind CSS](https://tailwindcss.com/). 

Features:
* Tailwind CSS for css styling.
    * leverages `@theme` and `@component` directives alongside utility classes.
* Responsive mobile-first design.

* Note: javascript functionality from original Zeal Taste template is not functional in this demo.

Assets and fonts are all availble for free under the following licenses:
* [Freepik](https://www.freepik.com/legal/terms-of-use)
* [IconlyV3](https://piqodesign.gumroad.com/l/iconly)
* [UX Wing](https://uxwing.com/license/)
* [Sansita Font](https://fonts.google.com/specimen/Sansita?query=Sansita)
* [Lato Font](https://fonts.google.com/specimen/Lato)


To run locally:
```
$ npx @tailwindcss/cli -i ./public/styles.css -o ./public/output.css --watch
```

Deployed at [https://clonesite-tailwindcss.vercel.app/](https://clonesite-tailwindcss.vercel.app/).