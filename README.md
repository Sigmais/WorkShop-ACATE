# WorkShop-ACATE - Imersão SigFox
===================================


## Payload Custom Format
> temp::uint:16:little-endian pressure::uint:16:little-endian photo::uint:16:little-endian x_g::int:16:little-endian y_g::int:16:little-endian z_g::int:16:little-endian

## Callback E-mail body

~~~
Temp: {customData#temp}
Pressure: {customData#pressure}
Photo: {customData#photo}
X: {customData#x_g}
Y: {customData#y_g}
Z: {customData#z_g}
~~~

## Downlink Data

~~~

{"3DFF7B":{"downlinkData":"0101000000000000"}}

~~~


## Links
* http://backend.sigfox.com
* https://buy.sigfox.com/activate
* http://gist.github.com