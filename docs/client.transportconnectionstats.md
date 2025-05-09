<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@holochain/client](./client.md) &gt; [TransportConnectionStats](./client.transportconnectionstats.md)

## TransportConnectionStats interface

Stats for a single transport connection.

**Signature:**

```typescript
export interface TransportConnectionStats 
```

## Properties

<table><thead><tr><th>

Property


</th><th>

Modifiers


</th><th>

Type


</th><th>

Description


</th></tr></thead>
<tbody><tr><td>

[is\_webrtc](./client.transportconnectionstats.is_webrtc.md)


</td><td>


</td><td>

boolean


</td><td>

True if this connection has successfully upgraded to webrtc.


</td></tr>
<tr><td>

[opened\_at\_s](./client.transportconnectionstats.opened_at_s.md)


</td><td>


</td><td>

number


</td><td>

UNIX epoch timestamp in seconds when this connection was opened.


</td></tr>
<tr><td>

[pub\_key](./client.transportconnectionstats.pub_key.md)


</td><td>


</td><td>

string


</td><td>

The public key of the remote peer.


</td></tr>
<tr><td>

[recv\_bytes](./client.transportconnectionstats.recv_bytes.md)


</td><td>


</td><td>

number


</td><td>

The bytes received on this connection


</td></tr>
<tr><td>

[recv\_message\_count](./client.transportconnectionstats.recv_message_count.md)


</td><td>


</td><td>

number


</td><td>

The message count received on this connection.


</td></tr>
<tr><td>

[send\_bytes](./client.transportconnectionstats.send_bytes.md)


</td><td>


</td><td>

number


</td><td>

The bytes sent on this connection.


</td></tr>
<tr><td>

[send\_message\_count](./client.transportconnectionstats.send_message_count.md)


</td><td>


</td><td>

number


</td><td>

The message count sent on this connection.


</td></tr>
</tbody></table>
