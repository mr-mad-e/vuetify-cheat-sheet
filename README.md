# Vuetify Cheat Sheet

## Styles

> breakpoint

- `xs`
- `sm`
- `md`
- `lg`
- `xl`

### Display

- `.d-{value}`
- `.d-{breakpoint}-{value}`

> value

- `none`
- `inline`
- `inline-block`
- `block`
- `table`
- `table-cell`
- `table-row`
- `flex`
- `inline-flex`

### Flex direction

- `.flex-{value}`
- `.flex-{breakpoint}-{value}`

> value

- `row`
- `row-reverse`
- `column`
- `column-reverse`

### Flex justify

- `.justify-{value}`
- `.justify-{breakpoint}-{value}`

> value

- `start`
- `end`
- `center`
- `space-between`
- `space-around`

### Flex align

- `.align-{value}`
- `.align-{breakpoint}-{value}`

> value

- `start`
- `end`
- `center`
- `baseline`
- `stretch`

### Flex align self

- `.align-self-{value}`
- `.align-self-{breakpoint}-{value}`

> value

- `start`
- `end`
- `center`
- `baseline`
- `stretch`/`auto`

### Flex wrap

- `.flex-{value}`
- `.flex-{breakpoint}-{value}`

> value

- `nowrap`
- `wrap`
- `wrap-reverse`

### Flex order

- `.order-{value}`
- `.order-{breakpoint}-{value}`

> value

- `first`
- `last`
- `0`
- `1`
- `2`
- `3`
- `4`
- `5`
- `6`
- `7`
- `8`
- `9`
- `10`
- `11`
- `12`

### Flex align content

- `.align-content-{value}`
- `.align-{breakpoint}-content-{value}`

> value

- `start`
- `end`
- `center`
- `space-between`
- `space-around`/`stretch`

### Flex grow and shrink

- `flex-{breakpoint}-{condition}-{state}`

> condition

- `grow`
- `shrink`

> state

- `0`
- `1`

### Float

- `.float-{value}`
- `.float-{breakpoint}-{value}`

> value

- `left`
- `right`
- `none`

### Spacing

- `.{property}{direction}-{size}`

> property

- `m` - applies margin
- `p` - applies padding

> direction

- `t` - applies the spacing for `margin-top` and `padding-top`
- `b` - applies the spacing for `margin-bottom` and `padding-bottom`
- `l` - applies the spacing for `margin-left` and `padding-left`
- `r` - applies the spacing for `margin-right` and `padding-right`
- `s` - applies the spacing for
  - `margin-left`/`padding-left` (in LTR mode) and
  - `margin-right`/`padding-right` (in RTL mode)
- `e` - applies the spacing for
  - `margin-right`/`padding-right` (in LTR mode) and
  - `margin-left`/`padding-left` (in RTL mode)
- `x` - applies the spacing for
  - `margin-left`/`padding-left` and
  - `margin-right`/`padding-right`
- `y` - applies the spacing for
  - `margin-top`/`padding-top` and
  - `margin-bottom`/`padding-bottom`
- `a` - applies the spacing for
  - `margin-left`/`padding-left` and
  - `margin-right`/`padding-right` and
  - `margin-top`/`padding-top` and
  - `margin-bottom`/`padding-bottom`

> size

- `0` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 0
- `1` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 4px
- `2` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 8px
- `3` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 12px
- `4` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 16px
- `5` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 20px
- `6` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 24px
- `7` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 28px
- `8` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 32px
- `9` &nbsp;&nbsp;&nbsp; - sets `margin` or `padding` to 36px
- `10` &nbsp;&nbsp; - sets `margin` or `padding` to 40px
- `11` &nbsp;&nbsp; - sets `margin` or `padding` to 44px
- `12` &nbsp;&nbsp; - sets `margin` or `padding` to 48px
- `13` &nbsp;&nbsp; - sets `margin` or `padding` to 52px
- `14` &nbsp;&nbsp; - sets `margin` or `padding` to 56px
- `15` &nbsp;&nbsp; - sets `margin` or `padding` to 60px
- `16` &nbsp;&nbsp; - sets `margin` or `padding` to 64px
- `n1` &nbsp;&nbsp; - sets `margin` to -4px
- `n2` &nbsp;&nbsp; - sets `margin` to -8px
- `n3` &nbsp;&nbsp; - sets `margin` to -12px
- `n4` &nbsp;&nbsp; - sets `margin` to -16px
- `n5` &nbsp;&nbsp; - sets `margin` to -20px
- `n6` &nbsp;&nbsp; - sets `margin` to -24px
- `n7` &nbsp;&nbsp; - sets `margin` to -28px
- `n8` &nbsp;&nbsp; - sets `margin` to -32px
- `n9` &nbsp;&nbsp; - sets `margin` to -36px
- `n10` &nbsp; - sets `margin` to -40px
- `n11` &nbsp; - sets `margin` to -44px
- `n12` &nbsp; - sets `margin` to -48px
- `n13` &nbsp; - sets `margin` to -52px
- `n14` &nbsp; - sets `margin` to -56px
- `n15` &nbsp; - sets `margin` to -60px
- `n16` &nbsp; - sets `margin` to -64px
- `auto` - sets `margin` to auto

### Typography

- `.text-{value}`
- `.text-{breakpoint}-{value}`

> value

- `h1` -> `{ font-size: 6rem; font-weight: 300; }`
- `h2` -> `{ font-size: 3.75rem; font-weight: 300; }`
- `h3` -> `{ font-size: 3rem; font-weight: 400; }`
- `h4` -> `{ font-size: 2.125rem; font-weight: 400; }`
- `h5` -> `{ font-size: 1.5rem; font-weight: 400; }`
- `h6` -> `{ font-size: 1.25rem; font-weight: 500; }`
- `subtitle-1`
- `subtitle-2`
- `body-1`
- `body-2`
- `button`
- `caption`
- `overline`

### Text alignment

- `.text-{value}`
- `.text-{breakpoint}-{value}`

> value

- `left`
- `center`
- `right`

### Text decoration

- `text-decoration-none`
- `text-decoration-overline`
- `text-decoration-underline`
- `text-decoration-line-through`

### Text wrapping and overflow

- `.text-wrap` &nbsp;&nbsp;&nbsp;&nbsp; -> `{ white-space: nowrap }`
- `.text-no-wrap` &nbsp; -> `{ white-space: nowrap; }`
- `.text-truncate` -> `{ white-space: nowrap; overflow: hidden; text-overflow: ellipsis; }`
- `.text-break` &nbsp;&nbsp;&nbsp; -> `{ overflow-wrap: break-word; word-break: break-word; }`

### Text transform

- `.text-none`
- `.text-lowercase`
- `.text-uppercase`
- `.text-capitalize`

### Text opacity

- `.text--primary` &nbsp;&nbsp;&nbsp;&nbsp; - **87%**
- `.text--secondary` - **60%**
- `.text--disabled` &nbsp;&nbsp; - **37%**

### Font weights

- `.font-weight-thin` &nbsp;&nbsp;&nbsp; - **100**
- `.font-weight-light` &nbsp;&nbsp; - **300**
- `.font-weight-regular` - **400**
- `.font-weight-medium` &nbsp; - **500**
- `.font-weight-bold` &nbsp;&nbsp;&nbsp; - **700**
- `.font-weight-black` &nbsp;&nbsp; - **900**
