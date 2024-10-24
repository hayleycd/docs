---
type: docs
category: JavaScript
menuTitle: rekor-types
title: rekor-types
weight: 60
---
@sigstore/rekor-types is a library of TypeScript types for the Sigstore [Rekor][1] REST API.

## Updating Rekor Types

Update the git `REF` in `hack/generate-rekor-types` from the [sigstore/rekor][1] repository.

Generate TypeScript types (should update files in scr/\_\_generated\_\_):

```
npm run codegen
```

[1]: https://github.com/sigstore/rekor