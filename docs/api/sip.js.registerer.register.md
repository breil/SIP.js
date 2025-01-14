<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [sip.js](./sip.js.md) &gt; [Registerer](./sip.js.registerer.md) &gt; [register](./sip.js.registerer.register.md)

## Registerer.register() method

Sends the REGISTER request.

<b>Signature:</b>

```typescript
register(options?: RegistererRegisterOptions): Promise<OutgoingRegisterRequest>;
```

## Parameters

|  Parameter | Type | Description |
|  --- | --- | --- |
|  options | <code>RegistererRegisterOptions</code> |  |

<b>Returns:</b>

`Promise<OutgoingRegisterRequest>`

## Remarks

If successfull, sends re-REGISTER requests prior to registration expiration until `unsubscribe()` is called.

