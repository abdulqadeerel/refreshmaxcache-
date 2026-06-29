# Refresh Maximo Cache

Refresh the IBM Maximo cache without restarting the application or causing downtime.

Useful after making direct SQL changes to Maximo configuration tables such as:

* `MAXATTRIBUTE` / `MAXATTRIBUTECFG`
* `MAXOBJECT` / `MAXOBJECTCFG`
* `SYNONYMDOMAIN`
* `MAXLOOKUPMAP`

## Usage

Create and Call the script (refreshmaxcache) using your Maximo server URL:

```text
https://maximodeploy.com/maximo/oslc/script/refreshmaxcache
```

The cache is refreshed immediately, and the configuration changes become effective without restarting Maximo.
