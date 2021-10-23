# design-tokens
![Release](https://github.com/remindle/design-tokens/actions/workflows/release.yml/badge.svg)

## What are Design Tokens?
Design tokens are all the values needed to construct and maintain a design system — spacing, color, typography, object styles, animation, etc. — represented as data. These can represent anything defined by design: a color as a RGB value, an opacity as a number, an animation ease as Bezier coordinates. They’re used in place of hard-coded values in order to ensure flexibility and unity across all product experiences.
[Adobe](https://spectrum.adobe.com/page/design-tokens/)

## Tech used
Building components
- 📚 [Style Dictionary](https://github.com/amzn/style-dictionary) A Style Dictionary uses design tokens to define styles once and use those styles on any platform or language.

Maintaining the package
- 📦 [GitHub Package Registry](https://github.com/orgs/remindle/packages?repo_name=design-tokens) for [packaging and distribution](https://docs.github.com/en/packages)
- 🚢 [semantic-release-action](https://github.com/cycjimmy/semantic-release-action) semantic-release action to publish a npm package [see here for more info](https://github.com/semantic-release/semantic-release)
- 🚥 [GitHub Actions](https://github.com/remindle/design-tokens/actions) Continuous integration
