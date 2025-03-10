# Available Snyk Reports

## Issues Detail Report

The Issues Detail report displays all known issues in all of your Projects that are being monitored by Snyk. The report gives details about each issue and which of your Projects are affected, and provides links to fix information.

The Issues Detail report displays the number of issues as well as the number of unique vulnerabilities that make up the issues.

Quick aggregations are available by categories including **Severity**, **Product Name**, and **Issue Type**:

<figure><img src="../../../.gitbook/assets/reporting-beta-quick-aggregation-issues-detail-report.png" alt="Quick aggregation for Issues Detail report"><figcaption><p>Quick aggregation for Issues Detail Report</p></figcaption></figure>

Individual issues are then displayed in a table. You can modify columns as needed.

## Issues Summary Report

The Issues Summary report highlights the value that Snyk is providing by enabling both identification of issues and resolution of issues. The report provides a glimpse into how well teams are optimizing use of the Snyk platform for their workflow, and provides a means to measure and improve security.

This report enables you to easily understand the current state and trends of the highest security risk items. This report also provides a quick view into where risk is coming from and where remediation efforts are most and least effective.

Use the date filter in the upper right corner of the Issues Summary report to see key metrics and charts for a specified interval.

This report shows a number of key metrics associated with issues in that interval with a comparison to the same metrics in the previous period so you can get a quick understanding of trends. See tooltips in the app for definitions of the metrics.

Scroll down for additional charts that show trend information in greater detail.

Key metrics are then broken down to point out information at the Organization or Project level. You can drill down to see what new and resolved issues were introduced during the date range selected.

## Vulnerabilities Detail Report

The Vulnerabilities Detail report is similar to the Issues Detail report, but shows issues grouped by Snyk Problem ID ([see Snyk Vulnerability DB](https://security.snyk.io/vuln)). You can easily see how many instances of a vulnerability exist and how many projects are affected. Use this report to understand which vulnerabilities are most prevalent for both resolution and prevention use cases.

## Dependencies and Licenses tabs relocated

For customers who opted into Next Gen Reporting, the Dependencies and Licenses views remain available but in a new location in the Snyk App, in the Snyk navigation menu under **Dependencies**.

## Cloud Compliance Issues Report

{% hint style="info" %}
All users with access to Next Gen Reporting will see the Cloud Compliance Issues report. If [Snyk Cloud](../../../scan-cloud-configurations/integrated-iac-with-cloud-context/) or [Snyk Integrated IaC](broken-reference) or both are not enabled, or if they are enabled but no [environments](../../../scan-cloud-configurations/integrated-iac-with-cloud-context/key-concepts.md#environments) have issues, you will see the following message: “Snyk doesn’t detect any issues in your Organization that map to supported compliance standards. This is a capability for Snyk Cloud and Snyk IaC (integrated) customers. Please reach out to your account team if you are interested.”
{% endhint %}

The Cloud Compliance Issues report shows[ cloud and integrated IaC issues](../../../scan-cloud-configurations/integrated-iac-with-cloud-context/key-concepts.md#issues) for an entire Organization, organized by [compliance standard](../../../scan-cloud-configurations/integrated-iac-with-cloud-context/key-concepts.md#docs-internal-guid-e2e38027-7fff-9271-f2c0-e23677542f6e).

You can view a report for a single version of a compliance standard at a time (for example, CIS AWS Foundations Benchmark v1.4.0) by selecting the desired standard from the drop-down menu. Each report includes a list of compliance controls organized by control category, with corresponding issue counts.

Selecting an issue count lets you view the list of issues associated with that control in the [Cloud Issues UI](../../../scan-cloud-configurations/integrated-iac-with-cloud-context/cloud-and-integrated-iac-issues/view-cloud-and-integragted-iac-issues-in-the-snyk-web-ui.md), where you can view each issue in detail.

Use the information in the Cloud Compliance Issues report to investigate, triage, and fix cloud compliance issues.
