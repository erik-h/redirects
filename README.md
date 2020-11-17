# redirects

[This article](https://prince.dev/netlify-redirects) was the original inspiration for this repo.

Netlify's [`_redirects` file](https://docs.netlify.com/routing/redirects/#syntax-for-the-redirects-file) is used to quickly and easily create personal short URLs off of the erik.lol domain. For example, https://erik.lol/github redirects to my GitHub account profile.

## email

Netlify doesn't seem to support `mailto:` links for their HTTP 301 redirects. To get around this, I have a little HTTP `<meta>` refresh HTML page setup at https://erik.lol/email to perform the "redirect" to send me an email.
