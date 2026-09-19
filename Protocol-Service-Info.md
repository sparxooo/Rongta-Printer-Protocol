# Protocol Service General information
The printer appears to support both USB and Bluetooth (LE). There is mention of Wifi support in the manual but it does not appear this is available on the printer itself. The app has information from the printer on printer events (paper out, lid open, etc) so must be data being sent in both directions.

### Advertised services (from BLEScanner)

#### Generic Access
0x1800
Primary Service: Device Name
UUID: 00002A00-0000-1000-8000-00805F9B34FB
Properties: READ

#### Custom Service
UUID: 0000FF00-0000-1000-8000-00805F9B34FB
Primary Service

##### Custom Characteristic 1
###### Info
UUID: 0000FF01-0000-1000-8000-00805F9B34FB
Properties: NOTIFY
###### Descriptors
Client Characteristic Configuration
UUID: 0x2902
##### Custom Characteristic 2

###### Info
UUID: 0000FF02-0000-1000-8000-00805F9B34FB
Properties: WRITE, WRITE NO RESPONSE
Write Type: WRITE REQUEST

##### Custom Characteristic 3

###### Info
UUID: 0000FF03-0000-1000-8000-00805F9B34FB
Properties: NOTIFY
###### Descriptors
Client Characteristic Configuration
UUID: 0x2902
