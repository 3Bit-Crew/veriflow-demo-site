# Veriflow demo site

A made-up bakery landing page ("Hearth & Crumb"), used to demo **website jobs** in [Veriflow](https://github.com/3Bit-Crew/Veriflow) (PLAN.md section 10.1). Hosted on GitHub Pages:

| Version | URL | What's in it |
|---|---|---|
| Good | https://3bit-crew.github.io/veriflow-demo-site/good/ | Everything fits on a phone |
| Broken | https://3bit-crew.github.io/veriflow-demo-site/broken/ | On a 390px phone screen the "Sign up" button is cut off at the right edge |

Both pages have the headline "Fresh every morning", an email field (`input[type=email]`) and a "Sign up" button. Signing up shows a thank-you message in place of the form (there's no server, nothing is sent).

The two versions are the same except for the signup row in `style.css`. The good one wraps, and on a phone the button goes under the field. The broken one has a fixed width of `26rem`, wider than a phone, and the hero section crops anything that sticks out. On a desktop screen both look the same.

Plain HTML and CSS: no build step, nothing to install. To view it locally, open `good/index.html` or `broken/index.html` in a browser.
