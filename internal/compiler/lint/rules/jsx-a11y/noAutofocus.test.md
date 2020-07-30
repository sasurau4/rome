# `harness.test.ts`

**DO NOT MODIFY**. This file has been autogenerated. Run `rome test internal/compiler/lint/rules/harness.test.ts --update-snapshots` to update.

## `jsx-a11y/noAutofocus`

### `0`

```

 lint/jsx-a11y/noAutofocus/reject/1/file.tsx:1:7 lint/jsx-a11y/noAutofocus  FIXABLE  ━━━━━━━━━━━━━━━

  ✖ Avoid the autoFocus attribute.

    <input autoFocus />
           ^^^^^^^^^

  ℹ Automatically focusing elements overrides natural page content focus order, causing issues for
    keyboard-only navigation.

  ℹ Recommended fix

  - <input·autoFocus·/>
  + <input·/>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `0: formatted`

```
<input />;

```

### `1`

```

 lint/jsx-a11y/noAutofocus/reject/2/file.tsx:1:7 lint/jsx-a11y/noAutofocus  FIXABLE  ━━━━━━━━━━━━━━━

  ✖ Avoid the autoFocus attribute.

    <input autoFocus='true' />
           ^^^^^^^^^^^^^^^^

  ℹ Automatically focusing elements overrides natural page content focus order, causing issues for
    keyboard-only navigation.

  ℹ Recommended fix

  - <input·autoFocus="true"·/>
  + <input·/>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `1: formatted`

```
<input />;

```

### `2`

```

 lint/jsx-a11y/noAutofocus/reject/3/file.tsx:1:7 lint/jsx-a11y/noAutofocus  FIXABLE  ━━━━━━━━━━━━━━━

  ✖ Avoid the autoFocus attribute.

    <input autoFocus={"false"} />
           ^^^^^^^^^^^^^^^^^^^

  ℹ Automatically focusing elements overrides natural page content focus order, causing issues for
    keyboard-only navigation.

  ℹ Recommended fix

  - <input·autoFocus={"false"}·/>
  + <input·/>

━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━━

✖ Found 1 problem

```

### `2: formatted`

```
<input />;

```

### `3`

```
✔ No known problems!

```

### `3: formatted`

```
<input />;

```

### `4`

```
✔ No known problems!

```

### `4: formatted`

```
<input autoFocus={undefined} />;

```