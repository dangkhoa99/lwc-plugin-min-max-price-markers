# Min Max Price Markers - Lightweight Charts™ Plugin

A plugin to display min/max prices Markers.

- Developed for Lightweight Charts version: `v5.0.9`

## Installation

```bash
npm install lwc-plugin-min-max-price-markers
```

## Usage

```js
import { MinMaxPriceMarkers } from 'lwc-plugin-min-max-price-markers';

// Create the chart and series...
const chart = createChart(document.getElementById('container'));
const lineSeries = chart.addLineSeries();
const data = [
  { time: 1642425322, value: 123 },
  /* ... more data */
];

// Attach the utility to the series
const minMaxPriceMarkers = new MinMaxPriceMarkers();
lineSeries.attachPrimitive(minMaxPriceMarkers);
```

## Developing

### Running Locally

```shell
npm install
npm run dev
```

Visit `localhost:5173` in the browser.

### Compiling

```shell
npm run compile
```

Check the output in the `dist` folder.
