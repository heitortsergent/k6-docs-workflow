---
title: 'Gauge.add(value, [tags])'
excerpt: 'Set the value of the Gauge metric.'
---

# Gauge.add(value, [tags])

Set the value of the `Gauge` metric.

| Parameter | Type   | Description                                                                                                                                                   |
| --------- | ------ | ------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| value     | number | The value to set the gauge to.                                                                                                                                |
| tags      | object | Set of [tags](/using-k6/tags-and-groups) that will be tagged to the added data point (note that tags are added per data point and not for the entire metric). |

[Gauge examples](/javascript-api/k6-metrics/gauge#examples)
