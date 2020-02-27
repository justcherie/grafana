+++
# -----------------------------------------------------------------------
# Do not edit this file. It is automatically generated by API Documenter.
# -----------------------------------------------------------------------
title = "FieldDisplayEditor"
keywords = ["grafana","documentation","sdk","@grafana/ui"]
type = "docs"
draft = true
+++

## FieldDisplayEditor class

<b>Signature</b>

```typescript
export declare class FieldDisplayEditor extends PureComponent<Props> 
```
<b>Import</b>

```typescript
import { FieldDisplayEditor } from '@grafana/ui';
```
<b>Properties</b>

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [onCalcsChange](#oncalcschange-property) |  | <code>(calcs: string[]) =&gt; void</code> |  |
|  [onDefaultsChange](#ondefaultschange-property) |  | <code>(value: FieldConfig) =&gt; void</code> |  |
|  [onLimitChange](#onlimitchange-property) |  | <code>(event: React.ChangeEvent&lt;HTMLInputElement&gt;) =&gt; void</code> |  |
|  [onShowValuesChange](#onshowvalueschange-property) |  | <code>(item: SelectableValue&lt;boolean&gt;) =&gt; void</code> |  |

<b>Methods</b>

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [render()](#render-method) |  |  |

### onCalcsChange property

<b>Signature</b>

```typescript
onCalcsChange: (calcs: string[]) => void;
```

### onDefaultsChange property

<b>Signature</b>

```typescript
onDefaultsChange: (value: FieldConfig) => void;
```

### onLimitChange property

<b>Signature</b>

```typescript
onLimitChange: (event: React.ChangeEvent<HTMLInputElement>) => void;
```

### onShowValuesChange property

<b>Signature</b>

```typescript
onShowValuesChange: (item: SelectableValue<boolean>) => void;
```

### render method

<b>Signature</b>

```typescript
render(): JSX.Element;
```
<b>Returns:</b>

`JSX.Element`
