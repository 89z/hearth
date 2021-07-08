# Style reference

## Color

- <https://color.adobe.com>
- <https://colorhunt.co>
- <https://colorkoala.netlify.app>
- <https://tachyons.io>
- <https://tailwindcss.com/docs/customizing-colors>

## Data types

Avoid `ex` as it produces inconsistent results on mobile browsers. Use `em`
instead.

## link

~~~html
<link rel="icon" href="/repo/favicon.png">
~~~

Note that SVG favicons are not supported with mobile browser. Alternative is
PNG.

- <https://flaticon.com>
- <https://gauger.io/fonticon>
- <https://ikonate.com>
- <https://materialdesignicons.com>

~~~html
<link rel="stylesheet" href="style.css">
~~~

## meta

~~~html
<meta name="viewport" content="width=device-width, initial-scale=1">
~~~

`initial-scale` is needed for Chrome Android.

## References

- <https://validator.w3.org>
- <https://w3.org/tr/html5/syntax#optional-tags>
