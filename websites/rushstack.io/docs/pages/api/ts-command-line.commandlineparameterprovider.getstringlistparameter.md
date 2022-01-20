---
hide_title: true
custom_edit_url: null
pagination_prev: null
pagination_next: null
---
<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@rushstack/ts-command-line](./ts-command-line.md) &gt; [CommandLineParameterProvider](./ts-command-line.commandlineparameterprovider.md) &gt; [getStringListParameter](./ts-command-line.commandlineparameterprovider.getstringlistparameter.md)

## CommandLineParameterProvider.getStringListParameter() method

Returns the CommandLineStringListParameter with the specified long name.

<b>Signature:</b>

```typescript
getStringListParameter(parameterLongName: string): CommandLineStringListParameter;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  parameterLongName | string |  |

<b>Returns:</b>

[CommandLineStringListParameter](./ts-command-line.commandlinestringlistparameter.md)

## Remarks

This method throws an exception if the parameter is not defined.
