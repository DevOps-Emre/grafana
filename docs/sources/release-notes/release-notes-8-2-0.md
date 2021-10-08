+++
title = "Release notes for Grafana 8.2.0"
[_build]
list = false
+++

<!-- Auto generated by update changelog github action -->

# Release notes for Grafana 8.2.0

### Features and enhancements

- **AWS:** Updated AWS authentication documentation. [#39236](https://github.com/grafana/grafana/pull/39236), [@sunker](https://github.com/sunker)
- **Alerting:** Added support Alertmanager data source for upstream Prometheus AM implementation. [#39775](https://github.com/grafana/grafana/pull/39775), [@domasx2](https://github.com/domasx2)
- **Alerting:** Allows more characters in label names so notifications are sent. [#38629](https://github.com/grafana/grafana/pull/38629), [@gotjosh](https://github.com/gotjosh)
- **Alerting:** Get alert rules for a dashboard or a panel using /api/v1/rules endpoints. [#39476](https://github.com/grafana/grafana/pull/39476), [@gerobinson](https://github.com/gerobinson)
- **Annotations:** Improved rendering performance of event markers. [#39984](https://github.com/grafana/grafana/pull/39984), [@torkelo](https://github.com/torkelo)
- **CloudWatch Logs:** Skip caching for log queries. [#39860](https://github.com/grafana/grafana/pull/39860), [@aocenas](https://github.com/aocenas)
- **Explore:** Added an opt-in configuration for Node Graph in Jaeger, Zipkin, and Tempo. [#39958](https://github.com/grafana/grafana/pull/39958), [@connorlindsey](https://github.com/connorlindsey)
- **Prometheus:** Metrics browser can now handle label values with special characters. [#39713](https://github.com/grafana/grafana/pull/39713), [@gabor](https://github.com/gabor)

### Bug fixes

- **CodeEditor:** Ensure that we trigger the latest onSave callback provided to the component. [#39835](https://github.com/grafana/grafana/pull/39835), [@mckn](https://github.com/mckn)
- **DashboardList/AlertList:** Fix for missing All folder value. [#39772](https://github.com/grafana/grafana/pull/39772), [@hugohaggmark](https://github.com/hugohaggmark)

### Plugin development fixes & changes

- **Plugins:** Create a mock icon component to prevent console errors. [#39901](https://github.com/grafana/grafana/pull/39901), [@jackw](https://github.com/jackw)