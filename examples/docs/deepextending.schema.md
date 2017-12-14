---
template: reference
foo: bar
---

# Custom Schema

```
https://example.com/schemas/deepextending
```

This is an extending schema. It is extending another extending schema. It pulls `definitions` from other schemas.

| Abstract | Extensible | Custom Properties | Defined In |
|----------|------------|-------------------|------------|
| Can be instantiated | Yes | Forbidden | [deepextending.schema.json](deepextending.schema.json) |

## Schema Hierarchy

* Custom `https://example.com/schemas/deepextending`
  * [Extensible](extensible.schema.md) `https://example.com/schemas/extensible`
  * [Definitions](definitions.schema.md) `https://example.com/schemas/definitions`
  * [Extending](extending.schema.md) `https://example.com/schemas/extending`

# Custom Properties

| Property | Type | Required | Defined by |
|----------|------|----------|------------|
| [bar](#bar) | `string` | Optional | [Extensible](extensible.schema.md#bar) |
| [id](#id) | `string` | Optional | [Definitions](definitions.schema.md#id) |
| [baz](#baz) | `string` | Optional | [Extending](extending.schema.md#baz) |
| [hey](#hey) | `string` | Optional | Custom (this schema) |

## bar

A horse walks into it.
`bar`
* is optional
* type: `string`
* defined in here
### Type

### Known Values

| Value | Description |
|-------|-------------|
| `hi`  | Welcome     |
| `bye` | Farewell    |

### bar Examples

```json
"whoo"
```

```json
"hoo"
```



## id

A unique identifier given to every addressable thing.
`id`
* is optional
* type: `string`
* defined in here
### Type

### Known Values

| Value | Description |
|-------|-------------|
| `hi`  | Welcome     |
| `bye` | Farewell    |



## baz
### BAAAZ!

This property has a unique name to demonstrate it&#39;s uniqueness.
`baz`
* is optional
* type: `string`
* defined in here
### Type

### Known Values

| Value | Description |
|-------|-------------|
| `hi`  | Welcome     |
| `bye` | Farewell    |

### baz Example

```json
"I'm just a humble example"
```


## hey

A unique identifier given to every addressable thing.
`hey`
* is optional
* type: `string`
* defined in here
### Type

### Known Values

| Value | Description |
|-------|-------------|
| `hi`  | Welcome     |
| `bye` | Farewell    |

