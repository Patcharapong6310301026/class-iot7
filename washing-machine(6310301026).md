![Washing Machine](pictures/iot-machine.png)

## Get hardware level operations e.g. wash_count
```
Topic: v1cdti/hw/get/6310301026/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301026",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "firmware_Version",
    "value"     : "0Sgy083T"
}
```

## Get firmware version
```
Topic: v1cdti/hw/get/6310301026/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301026",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "wash_count",
    "value"     : "96"
}
```

## Get manufacture id and geo-location or location placement
```
Topic: v1cdti/hw/get/6310301026/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301026",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "location placement",
    "value"     : "Nonthaburi"
}
```

## Set geo-location or location placement
```
Topic: v1cdti/hw/set/6310301026/model-01/WSH-SN001
Payload: {
    "action"    : "set",
    "project"   : "6310301026",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "geo_location ",
    "value"     : "13.93, 100.39"
}
```

## Monitor machine sensor
```
Topic: v1cdti/app/monitor/6310301026/model-01/WSH-SN001
Payload: {
    "action"    : "monitor",
    "project"   : "6310301026",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "Each_of_spining",
    "value"     : "15"
}
```

## Set machie status to "maint" to indicate this machine need to be maintenance.
```
Topic: v1cdti/hw/get/6310301026/model-01/WSH-SN001
Payload: {
    "action"    : "get",
    "project"   : "6310301026",
    "model"     : "model-01",
    "serial"    : "WSH-SN01",
    "name"      : "status",
    "value"     : "maint"
}
```