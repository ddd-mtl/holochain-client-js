<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@holochain/client](./client.md) &gt; [RawSignal](./client.rawsignal.md)

## RawSignal type


**Signature:**

```typescript
export type RawSignal = {
    type: SignalType.App;
    value: EncodedAppSignal;
} | {
    type: SignalType.System;
    value: SystemSignal;
};
```
**References:** [SignalType.App](./client.signaltype.md)<!-- -->, [EncodedAppSignal](./client.encodedappsignal.md)<!-- -->, [SignalType.System](./client.signaltype.md)<!-- -->, [SystemSignal](./client.systemsignal.md)

