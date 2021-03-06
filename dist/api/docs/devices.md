<!-- Do not edit this file. It is automatically generated by API Documenter. -->

[Home](./index.md) &gt; [@digitalpersona/devices](./devices.md)

## devices package

## Classes

|  Class | Description |
|  --- | --- |
|  [AcquisitionStarted](./devices.acquisitionstarted.md) | An event signaling that a fingerprint reader is ready and waiting to scan a finger. |
|  [AcquisitionStopped](./devices.acquisitionstopped.md) | An event signaling that a fingerprint reader has stopped waiting for a finger scan. |
|  [CardInserted](./devices.cardinserted.md) | An event signaling that a card was presented (inserted or touched) to a card reader. |
|  [CardRemoved](./devices.cardremoved.md) | An event signaling that a card was removed from a card reader. |
|  [CardsReader](./devices.cardsreader.md) | A card reader API class. An instance of this class allows to subscribe to card reader events and read card data. The card reader API uses DigitalPersona WebSDK to communicate with card reader drivers and hardware. |
|  [CommunicationFailed](./devices.communicationfailed.md) | An event signaling a problem with a device channel communication. |
|  [DeviceConnected](./devices.deviceconnected.md) | An event signaling that a device was connected. |
|  [DeviceDisconnected](./devices.devicedisconnected.md) | An event signaling that a device was disconnected. |
|  [DeviceEvent](./devices.deviceevent.md) | A base class for device events. |
|  [ErrorOccurred](./devices.erroroccurred.md) | An event reporting a fingerprint reader error. |
|  [Event](./devices.event.md) | A base class for DigitalPersona events. |
|  [FingerprintReader](./devices.fingerprintreader.md) | A fingerprint reader API. An instance of this class allows to subscribe to finerprint reader events and read fingerprint data. The fingerprint reader API uses DigitalPersona WebSDK to communicate with fingerprint reader drivers and hardware. |
|  [QualityReported](./devices.qualityreported.md) | An event reporting a quality of a fingerprint scan. |
|  [SamplesAcquired](./devices.samplesacquired.md) | An event signaling that a new fingerprint sample (or samples) was acquired during a scan. |
|  [WindowsAuthClient](./devices.windowsauthclient.md) | Integrated Windows Authentication API. An instance of this class allows internet browsers to authenticate in DigitalPersona servers using Integrated Windows Authentication. The IWA API uses DigitalPersona WebSDK to communicate with Windwows operating system and extract Windows account data for authentication. |

## Enumerations

|  Enumeration | Description |
|  --- | --- |
|  [CardAttributes](./devices.cardattributes.md) | Bitwise flags for attributes supported by a card. |
|  [CardType](./devices.cardtype.md) | Enumerates supported card types. |
|  [DeviceModality](./devices.devicemodality.md) | Fingerprint device modalities (how users should use they fingers to make a scan). |
|  [DeviceTechnology](./devices.devicetechnology.md) | A fingerprint reader technology (a method of scanning) |
|  [DeviceUidType](./devices.deviceuidtype.md) | Fingerprint device types. |
|  [QualityCode](./devices.qualitycode.md) | A figerprint image quality. |
|  [SampleFormat](./devices.sampleformat.md) | A fingerprint sample format. |

## Interfaces

|  Interface | Description |
|  --- | --- |
|  [Card](./devices.card.md) | A card information. |
|  [DeviceInfo](./devices.deviceinfo.md) | Fingerprint device information. |

