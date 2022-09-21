# multipart-file-upload

use to upload multipart file

## Install

```bash
npm install multipart-file-upload
npx cap sync
```

## API

<docgen-index>

* [`echo(...)`](#echo)
* [`uploadFile(...)`](#uploadfile)

</docgen-index>

<docgen-api>
<!--Update the source file JSDoc comments and rerun docgen to update the docs below-->

### echo(...)

```typescript
echo(options: { value: string; }) => Promise<{ value: string; }>
```

| Param         | Type                            |
| ------------- | ------------------------------- |
| **`options`** | <code>{ value: string; }</code> |

**Returns:** <code>Promise&lt;{ value: string; }&gt;</code>

--------------------


### uploadFile(...)

```typescript
uploadFile(options: { url: string; headers?: any; params: any; filePath: string; fileKey?: string; }) => Promise<{ output: { string: any; }; }>
```

| Param         | Type                                                                                          |
| ------------- | --------------------------------------------------------------------------------------------- |
| **`options`** | <code>{ url: string; headers?: any; params: any; filePath: string; fileKey?: string; }</code> |

**Returns:** <code>Promise&lt;{ output: { string: any; }; }&gt;</code>

--------------------

</docgen-api>
