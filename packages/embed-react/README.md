# ⚛ synergetics React Embed Library

Embed library for [React](https://reactjs.org/).

## Installation

Requirements:

- node >= 18
- yarn or npm

Install as NPM package using your favourite package manager:

```shell
yarn add @synergetics/embed-react
```

or

```shell
npm install --save @synergetics/embed-react
```

## Usage

Import the component you want to use. Then render it in your React app:

```javascript
import { Widget } from '@synergetics/embed-react'

const MyComponent = () => {
  return <Widget id="<form-id>" style={{ width: '50%' }} className="my-form" />
}
```

Popup and slider components provide a button to open the embed:

```javascript
import { PopupButton } from '@synergetics/embed-react'

const MyComponent = () => {
  return (
    <PopupButton id="<form-id>" style={{ fontSize: 20 }} className="my-button">
      click to open form in popup
    </PopupButton>
  )
}
```

You can render popover and slider anywhere in your app (preferably at the end of the page):

```javascript
import { Sidetab } from '@synergetics/embed-react'

const MyComponent = () => {
  return <Sidetab id="<form-id>" buttonText="click to open" />
}
```

### How to get form id of your form?

You can find `<form-id>` from the public URL of your form:

- `https://form.synergetics.com/to/<form-id>`

Or from admin panel URL:

- `https://admin.synergetics.com/form/<form-id>/*`

## Configuration

### Options

Pass options as props to the component.

```javascript
<PopupButton
  id="<form-id>"
  size={60}
  hidden={{
    foo: 'Foo Value',
    bar: 'Bar Value',
  }}
  onReady={() => {
    console.log('form ready')
  }}
  enableSandbox
  transitiveSearchParams
>
  click to open
</PopupButton>
```

See all available options in [Vanilla JavaScript Embed Library README file](../embed/README.md#options). Make sure to pass props in camel case without the `data-tf-` prefix.

### CSP nonce support

If the global `__webpack_nonce__` is set, its value will be used for a `nonce` attribute on the inline `<style>` block. See [#458](https://github.com/synergetics/embed/issues/458) for details.

### Passing a custom ref as `embedRef`

For some custom use cases it may be convenient to open the popup programmatically (without the button being clicked).

To do this, pass an `embedRef` prop to `PopupButton`, `SliderButton`, `Popover` and `Sidetab` components and then use `ref.current.open()` to trigger the popup to open.

Example:

```javascript
const ref = useRef()
const openPopup = () => ref.current?.open()
// ...
<PopupButton
  id="<form-id>"
  embedRef={ref}
>
  click to open
</PopupButton>
```

### Examples

You can find examples for specific use-cases with React in our demos:

- [Next.js (React) demo](../../packages/demo-nextjs)
- [Codesandbox demo](https://github.com/synergetics/embed-demo#react-nextjs)

## Local setup and development

[Fork and clone](https://docs.github.com/en/github/getting-started-with-github/fork-a-repo) this Github repo: https://github.com/synergetics/embed

Requirements:

- node >= 18
- yarn

Install dependencies:

```bash
yarn
```

We recommend you work in a branch:

```bash
git checkout -b cool-new-feature
```

Build, watch for changes (in both `@synergetics/embed` and `@synergetics/embed-react` packages) and start a demo server too (using `demo-nextjs`):

```bash
yarn demo
```

Build and watch for changes (in `@synergetics/embed-react` only):

```bash
yarn dev
```

Run unit tests:

```bash
yarn test
```

See details on [contributing to this repo](https://github.com/synergetics/embed#contribution).