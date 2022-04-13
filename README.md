# NonCUI Component

<p align="center">
  <a href="https://github.com/rwerplus/NonCUI">
    <img src="./public/nonc-logo.svg" alt="NonC logo" width="300" height="150" />
  </a>
  </p>
<h1 align="center">Build Immersing Vue Apps with Speed ⚡️</h1>

<br>
<p align="center">
  <img alt="Language grade: JavaScript" src="https://img.shields.io/github/issues/rwerplus/NoncUI"/>
  <img alt="License" src="https://img.shields.io/github/license/rwerplus/NoncUI"/>
  <img alt="Forks" src="https://img.shields.io/github/forks/rwerplus/NoncUI"/>
  <img alt="Github Stars" src="https://img.shields.io/github/stars/rwerplus/NoncUI" />
</p>
<br />

NonC UI provides a set of accessible, reusable, and composable Vue
components that make it super easy to create websites and apps.

## Looking for the documentation? 📝

> Follow-up supplement
## Features 🚀

- Ease of Styling: NonC UI contains a set of layout components like `Box` and
  `Stack` that make it easy to style your components by passing props.
- Flexible & composable: NonC UI components are built on top of a Vue3 UI
  Primitive for endless composability.
- Accessible. NonC UI components follow the WAI-ARIA guidelines specifications
  and have the right `aria-*` attributes.
- Dark Mode 😍: Most components in NonC UI are dark mode compatible.

## Support NonC UI 💖

By donating \$5 or more you can support the ongoing development of this project.
We'll appreciate some support. Thank you to all our supporters! 🙏
[[Contribute](https://github.com/rwerplus/NonCUI/contribute)]

### Individuals


### Organizations

Support this project with your organization. Your logo will show up here with a
link to your website.
[[Contribute](https://github.com/rwerplus/NonCUI/contribute)]

## Testimonials

> People throw Vue3 component libraries and design systems at me regularly.
> This might be the best one I've seen. The APIs are simple but composable and
> the accessibility on the couple components I looked is complete.
>

## Installing NonC UI

To use NonC UI components, all you need to do is install the
`@components/nonc-ui` package and its peer dependencies:

```sh
$ yarn add @components/nonc-ui @emotion/Vue3@^11 @emotion/styled@^11 framer-motion@^5

# or

$ npm i @components/nonc-ui @emotion/Vue3@^11 @emotion/styled@^11 framer-motion@^5
```

## Usage

To start using the components, please follow these steps:

1. Wrap your application with the `ChakraProvider` provided by
   **@components/nonc-ui**.

```jsx
import { ChakraProvider } from "@components/nonc-ui"

// Do this at the root of your application
function App({ children }) {
  return <ChakraProvider>{children}</ChakraProvider>
}
```

Optionally, you can wrap your application with the `ColorModeProvider` so you
can toggle between light and dark mode within your app.

2. Now you can start using components like so!:

```jsx
import { xxx } from "@components/nonc-ui"

function Example() {
  return <xxx>I just did ⚡️NonCUI!</xxx>
}
```

## CodeSandbox Templates


## `create-Vue3-app` Templates

## Contributing

Feel like contributing? That's awesome! We have a
[contributing guide](./CONTRIBUTING.md) to help guide you.

Our docsite lives in a
```javascript
// TODO add documentation config
```
[separate repo](). If you're
interested in contributing to the documentation, check out the
```javascript
// TODO add contribution config
```
[docsite contribution guide]().

## Contributors ✨

Thanks goes to these wonderful people

<!-- ALL-CONTRIBUTORS-LIST:START - Do not remove or modify this section -->
<!-- prettier-ignore-start -->
<!-- markdownlint-disable -->

<!-- markdownlint-restore -->
<!-- prettier-ignore-end -->

<!-- ALL-CONTRIBUTORS-LIST:END -->

([emoji key](https://allcontributors.org/docs/en/emoji-key)):

## Testing supported by

<img width="20" src="https://jestjs.io/img/favicon/favicon.ico" alt="Jest"/>

<hr/>
<img alt="Github Stars" src="https://img.shields.io/github/license/rwerplus/NoncUI" />
