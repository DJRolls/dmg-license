<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [dmg-license](./dmg-license.md) &gt; [Labels](./dmg-license.labels.md) &gt; [map](./dmg-license.labels.map_1.md)

## Labels.map() function

<b>Signature:</b>

```typescript
function map<T, U>(labels: Labels.WithoutLanguageName<T>, fun: (label: T, key: keyof Labels, labels: Labels<T>) => U, options?: MapOptions<T, U> & {
        onNoLanguageName?: never;
    }): Labels.WithoutLanguageName<U>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  labels | <code>Labels.WithoutLanguageName&lt;T&gt;</code> |  |
|  fun | <code>(label: T, key: keyof Labels, labels: Labels&lt;T&gt;) =&gt; U</code> |  |
|  options | <code>MapOptions&lt;T, U&gt; &amp; {</code><br/><code>        onNoLanguageName?: never;</code><br/><code>    }</code> |  |

<b>Returns:</b>

`Labels.WithoutLanguageName<U>`
