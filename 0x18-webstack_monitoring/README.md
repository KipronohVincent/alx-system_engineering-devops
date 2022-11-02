# Webstack monitoring

This project invovled setting up Sumo Logic accounts to monitor server traffic


## Tasks :page_with_curl:

* **0. Sign up for Datadog and install datadog-agent**
-  my Sumo Logic access key.
    * First line: `Access ID`
    * Second line: `Access Key`

* **1. Monitor some metrics**
  * Among the litany of data your monitoring service can report to you are system metrics. You can use these metrics to determine statistics such as reads/writes per second, which can help your company determine if/how they should scale. Set up some monitors within the Datadog dashboard to monitor and alert you of a few. You can read about the various system metrics that you can monitor here:
* **2. Create a dashboard**
* [2-setup_datadog](2-setup_datadog) 
- Now create a dashboard with different metrics displayed in order to get a few different visualizations.
	* Create a new dashboard
	* Add at least 4 widgets to your dashboard. They can be of any type and monitor whatever you’d like
	* Create the answer file 2-setup_datadog which has the dashboard_id on the first line. Note: in order to get the id of your dashboard, you may need to use Datadog’s API
