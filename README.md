# liquid-fill-gauge

This is a (slightly) modified version of Curtis Bratton's D3 Liquid Fill Gauge (http://bl.ocks.org/brattonc/5e5ce9beee483220e2f6)

When this repository is added through npm/yarn and imported, it exposes two functions that are used to display an svg animation as seen on the linked page above.

`liquidFillGaugeDefaultSettings()`

Returns an object that is used to create a liquid fill gauge animation. Typically, the returned object is overwritten and then passed to the function below to create the svg animation.

`loadLiquidFillGauge(elementId, value, config)`

Applies the `config` object along with the `value` to an svg element with the corresponding `elementId`
