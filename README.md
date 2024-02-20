# Hugo: broken anchor links (hugo v.0.123.0)

Description: Hugo v0.123.0: broken anchor links are demonstrated

## Instructions

Clone the branch `broken-anchor-links` of the repository and build the site.

```text
git clone --single-branch -b broken-anchor-links https://github.com/deining/hugo-test hugo-broken-anchor-links
cd hugo-broken-anchor-links
hugo server
```

In your browser, invoke:

```text
http://localhost:1313/en/s1/p1/
```

Click on the link at the top of the page. You are redirected to the site root, where the anchor link cannot be found

The anchor links work fine with hugo v.0.123.0.
