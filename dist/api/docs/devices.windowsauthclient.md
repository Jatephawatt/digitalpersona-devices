<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@digitalpersona/devices](./devices.md) &gt; [WindowsAuthClient](./devices.windowsauthclient.md)

## WindowsAuthClient class

Integrated Windows Authentication API. An instance of this class allows internet browsers to authenticate in DigitalPersona servers using Integrated Windows Authentication. The IWA API uses DigitalPersona WebSDK to communicate with Windwows operating system and extract Windows account data for authentication.

<b>Signature:</b>

```typescript
export declare class WindowsAuthClient extends MultiCastEventSource implements IAuthenticationClient 
```

## Constructors

|  Constructor | Modifiers | Description |
|  --- | --- | --- |
|  [(constructor)(options)](./devices.windowsauthclient.(constructor).md) |  | Constructs a new IWA API object. |

## Properties

|  Property | Modifiers | Type | Description |
|  --- | --- | --- | --- |
|  [onCommunicationFailed](./devices.windowsauthclient.oncommunicationfailed.md) |  | <code>Handler&lt;CommunicationFailed&gt;</code> | A uni-cast event handler for the [CommunicationFailed](./devices.communicationfailed.md) event. |

## Methods

|  Method | Modifiers | Description |
|  --- | --- | --- |
|  [continue(handle, data)](./devices.windowsauthclient.continue.md) |  | Used internally. Do not call this method. |
|  [init()](./devices.windowsauthclient.init.md) |  | Used internally. Do not call this method. |
|  [off(event, handler)](./devices.windowsauthclient.off.md) |  | Deletes an event handler for the event. |
|  [on(event, handler)](./devices.windowsauthclient.on.md) |  | Adds an event handler for the event. This is a multicast subscription, i.e. many handlers can be registered at once. |
|  [term(handle)](./devices.windowsauthclient.term.md) |  | Used internally. Do not call this method. |

