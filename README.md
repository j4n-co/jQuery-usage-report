## jQuery usage reports for MFE & MinervaNeue

> What's our jQuery footprint?

In an attempt to answer this question. I've generated a few reports which estimate
jQuery usage in MobileFrontEnd and MinervaNeue.

Using eslint-plugin-jquery and a forked version of eslint-detailed-reporter, I've
generated a few reports which show the jQuery functions we're using **which can be
replaced with native DOM APIs**. This represents a limited set of jQuery methods, and
also does not include methods which have been chained together, like `$().show().hide()`.
It might catch the first method in the chain though.

- [MobileFrontend jQuery Report](https://j4n-co.github.io/jQuery-usage-report/mobilefrontend.html)
- [Minerva jQuery Report](https://j4n-co.github.io/jQuery-usage-report/minerva.html)
