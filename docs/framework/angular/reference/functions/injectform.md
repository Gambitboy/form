---
id: injectForm
title: injectForm
---

# Function: injectForm()

```ts
function injectForm<TFormData, TFormValidator>(opts?): FormApi<TFormData, TFormValidator>
```

## Type Parameters

• **TFormData**

• **TFormValidator** *extends* `undefined` \| `Validator`\<`TFormData`, `unknown`\> = `undefined`

## Parameters

• **opts?**: `FormOptions`\<`TFormData`, `TFormValidator`\>

## Returns

`FormApi`\<`TFormData`, `TFormValidator`\>

## Defined in

[inject-form.ts:4](https://github.com/TanStack/form/blob/782e82ea1fb36627b62d0f588484b4a9c3249fed/packages/angular-form/src/inject-form.ts#L4)