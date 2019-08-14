# Dashboard 5 channels 1000 pps

This demo application belongs to the set of examples for LightningChart JS, data visualization library for JavaScript.

LightningChart JS is entirely GPU accelerated and performance optimized charting library for presenting massive amounts of data. It offers an easy way of creating sophisticated and interactive charts and adding them to your website or web application.

The demo can be used as an example or a seed project. Local execution requires the following steps:

- Make sure that relevant version of [Node.js](https://nodejs.org/en/download/) is installed
- Open the project folder in a terminal:

        npm install              # fetches dependencies
        npm start                # builds an application and starts the development server

- The application is available at *http://localhost:8080* in your browser, webpack-dev-server provides hot reload functionality.

### Description 

This example shows a dashboard with multiple progressive channels of data points using progressive line series.

The dashboard allows rendering of multiple scenes in a single view port pane highly efficiently with minimal memory resources. In our case, the rows of dashboard grid are filled with individual charts, where each represents the data channel.

#### Progressive series

Progressive series are highly optimized series for the rendering of high-volume and high-density data while keeping full interactivity.
These optimizations are enabled by selecting a ***DataPattern***, which needs to be specified during the creation of the series instance and cannot be changed further for performance related reasons. *More detailed description was explained in previous examples.*

### API links

* Dashboard: [Dashboard][]
* XY cartesian chart: [ChartXY][]
* Axis: [Axis][]
* Progressive line series: [ProgressiveLineSeries][]
* Solid LineStyle: [SolidLine][]


### Support

If you notice an error in the example code, please open an issue on [GitHub][0] repository of the entire example.

Official [API documentation][1] can be found on [Arction][2] website.

If the docs and other materials do not solve your problem as well as implementation help is needed, ask on [StackOverflow][3] (tagged lightningchart).

If you think you found a bug in the LightningChart JavaScript library, please contact support@arction.com.

Direct developer email support can be purchased through a [Support Plan][4] or by contacting sales@arction.com.

© Arction Ltd 2009-2019. All rights reserved.

[0]: https://github.com/Arction/
[1]: https://www.arction.com/lightningchart-js-api-documentation/
[2]: https://www.arction.com
[3]: https://stackoverflow.com/questions/tagged/lightningchart
[4]: https://www.arction.com/support-services/

[Axis]: https://www.arction.com/lightningchart-js-api-documentation/v1.0.1/classes/axis.html
[ChartXY]: https://www.arction.com/lightningchart-js-api-documentation/v1.0.1/classes/chartxy.html
[Dashboard]: https://www.arction.com/lightningchart-js-api-documentation/v1.0.1/classes/dashboard.html
[ProgressiveLineSeries]: https://www.arction.com/lightningchart-js-api-documentation/v1.0.1/classes/progressivelineseries.html
[SolidLine]: https://www.arction.com/lightningchart-js-api-documentation/v1.0.1/classes/solidline.html