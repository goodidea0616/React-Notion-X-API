<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [notion-utils](./notion-utils.md) &gt; [getBlockParentPage](./notion-utils.getblockparentpage.md)

## getBlockParentPage variable

Returns the parent page block containing a given page.

Note that many times this will not be the direct parent block since some non-page content blocks can contain sub-blocks.

<b>Signature:</b>

```typescript
getBlockParentPage: (block: types.Block, recordMap: types.ExtendedRecordMap) => types.PageBlock | null
```
