# Why School Uniforms Make Sense

A small, one-page website that explains why school uniforms can help make the school day easier. It is written for a general school audience and keeps the argument practical: uniforms may simplify mornings, reduce some clothing pressure, and give students a visible sense of belonging. The page also notes that uniform options should be comfortable and affordable.

## View the page

Open `index.html` in a web browser. The page is self-contained, so it needs no installation, build step, or internet connection.

To preview it through a local web server instead:

```sh
cd outputs/uniforms-page
python3 -m http.server 8000
```

Then visit [http://localhost:8000](http://localhost:8000).

## Page contents

- A short introduction to the case for uniforms
- Three everyday benefits: easier mornings, less clothing pressure, and school belonging
- A practical note on comfort and affordability
- A closing summary

## Project files

```text
uniforms-page/
├── index.html   # Page content, styles, and inline SVG illustrations
└── README.md    # Project notes and viewing instructions
```

The site uses plain HTML and CSS, with no JavaScript or third-party dependencies. Its layout adapts to smaller screens, includes a keyboard skip link and visible focus styles, and respects reduced-motion preferences.

## Make changes

- Edit the page copy in `index.html`.
- Change the colors and font stacks in the `:root` CSS rules near the top of the file.
- Update the uniform illustration by editing the inline SVG inside `.hero-art`.

There is no build or test command for this static page.
