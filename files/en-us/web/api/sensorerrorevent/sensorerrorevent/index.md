---
title: SensorErrorEvent()
slug: Web/API/SensorErrorEvent/SensorErrorEvent
tags:
  - API
  - Constructor
  - Error
  - Generic Sensor API
  - Reference
  - Sensor
  - Sensor APIs
  - SensorErrorEvent
  - Sensors
browser-compat: api.SensorErrorEvent.SensorErrorEvent
---
{{APIRef("Sensor API")}}

The **`SensorErrorEvent`** constructor
creates a new {{domxref("SensorErrorEvent")}} object which provides information about
errors thrown by any of the interfaces based on {{domxref('Sensor')}}.

## Syntax

```js
new SensorErrorEvent(type);
new SensorErrorEvent(type, {error: domException});
```

### Parameters

- `type`
  - : Will always be `'SensorErrorEvent'`.
- `options` {{optional_inline}}

  - : Currently only one option is supported:

    - `error`
      - : An instance of {{jsxref('DOMException')}}.

## Specifications

{{Specifications}}

## Browser compatibility

{{Compat}}
