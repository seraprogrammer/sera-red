# Sera Programmer redirect site

Deploy this directory as a static site and connect both:

- `seraprogrammer.com`
- `www.seraprogrammer.com`

The HTML redirects visitors to `https://peermeld.com/feed`. The `_redirects`
file additionally provides an HTTP 301 redirect on hosting platforms that
support the common redirects-file format, including Cloudflare Pages.

For Cloudflare Pages, create a Pages project using direct upload and upload the
contents of this directory. After deployment, add both old domains under the
Pages project's **Custom domains** settings.
