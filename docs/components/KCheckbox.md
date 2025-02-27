---
title: KCheckbox
lang: en-US
---

# KCheckbox

A group of options for multiple choices.

## Install

::: code-group

```bash [pnpm]
pnpm add @ikun-ui/checkbox
```

```bash [yarn]
yarn add @ikun-ui/checkbox
```

```bash [npm]
npm install @ikun-ui/checkbox
```

:::

## Basic usage

Checkbox can be used alone to switch between two states.

<demo src="../../../../example/checkbox/basic.svelte" github="https://github.com/ikun-svelte/ikun-ui/tree/main/components/Checkbox"></demo>

## Disabled checkbox

Set the `disabled` attribute.

<demo src="../../../../example/checkbox/disabled.svelte" github="https://github.com/ikun-svelte/ikun-ui/tree/main/components/Checkbox"></demo>

## Checkbox Props

| Name     | Type      | Default | Description                      |
| -------- | --------- | ------- | -------------------------------- |
| label    | `string`  | `-`     | Label of the Checkbox            |
| disabled | `boolean` | `false` | Whether the Checkbox is disabled |
| value    | `boolean` | `false` | Binding value                    |
| cls      | `string`  | `-`     | Additional class                 |
| attrs    | `any`     | `{}`    | Additional attributes            |

## Checkbox Events

| Name        | Description                             | Type                    |
| ----------- | --------------------------------------- | ----------------------- |
| updateValue | Event fired when the `value` is changes | `(value: Event)=> void` |
