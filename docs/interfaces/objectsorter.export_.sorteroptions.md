[Node object hash - v2.2.0](../README.md) / [objectSorter](../modules/objectsorter.md) / [export%3D](../modules/objectsorter.export_.md) / SorterOptions

# Interface: SorterOptions

[objectSorter](../modules/objectsorter.md).[export=](../modules/objectsorter.export_.md).SorterOptions

Object sorter options

## Hierarchy

- **SorterOptions**

  ↳ [_HasherOptions_](hasher.export_.hasheroptions.md)

  ↳ [_HasherOptions_](hasher.hasheroptions.md)

## Table of contents

### Properties

- [coerce](objectsorter.export_.sorteroptions.md#coerce)
- [sort](objectsorter.export_.sorteroptions.md#sort)
- [trim](objectsorter.export_.sorteroptions.md#trim)

## Properties

### coerce

• `Optional` **coerce**: _undefined_ | _boolean_ | [_CoerceOptions_](objectsorter.export_.coerceoptions.md)

If `true` enables type coercion.
Advanced coerce options could be provided as object

**`default`** true

Defined in: [objectSorter.ts:171](https://github.com/SkeLLLa/node-object-hash/blob/28d5344/src/objectSorter.ts#L171)

---

### sort

• `Optional` **sort**: _undefined_ | _boolean_ | [_SortOptions_](objectsorter.export_.sortoptions.md)

If `true` enables sorting.
Advanced sorting options could be provided as object

**`default`** true

Defined in: [objectSorter.ts:177](https://github.com/SkeLLLa/node-object-hash/blob/28d5344/src/objectSorter.ts#L177)

---

### trim

• `Optional` **trim**: _undefined_ | _boolean_ | [_TrimOptions_](objectsorter.export_.trimoptions.md)

If `true` enables trimming and multiple whitespace replacement.
Advanced sorting options could be provided as object.

**`default`** false

Defined in: [objectSorter.ts:183](https://github.com/SkeLLLa/node-object-hash/blob/28d5344/src/objectSorter.ts#L183)
