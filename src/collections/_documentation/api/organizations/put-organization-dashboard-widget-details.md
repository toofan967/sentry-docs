---
# This file is automatically generated from the API using `sentry/api-docs/generator.py.`
# Do not manually edit this file.
{
  "api_path": "/api/0/organizations/{organization_slug}/dashboards/{dashboard_id}/widgets/{widget_id}", 
  "authentication": "required", 
  "description": "Edit a widget on an organization's dashboard.", 
  "example_request": "", 
  "example_response": "", 
  "method": "PUT", 
  "parameters": [
    {
      "description": "the title of the widget.", 
      "name": "title", 
      "type": "string"
    }, 
    {
      "description": "the widget display type (i.e. line or table).", 
      "name": "displayType", 
      "type": "string"
    }, 
    {
      "description": "the widget display options are special variables necessary to displaying the widget correctly.", 
      "name": "displayOptions", 
      "type": "array"
    }, 
    {
      "description": "the sources of data for the widget to display. If supplied the entire set of data sources will be deleted and replaced with the input provided.", 
      "name": "dataSources", 
      "type": "array"
    }
  ], 
  "path_parameters": [
    {
      "description": "the slug of the organization the dashboard belongs to.", 
      "name": "organization_slug", 
      "type": "string"
    }, 
    {
      "description": "the id of the dashboard.", 
      "name": "dashboard_id", 
      "type": "int"
    }, 
    {
      "description": "the id of the widget.", 
      "name": "widget_id", 
      "type": "int"
    }
  ], 
  "query_parameters": null, 
  "sidebar_order": 12, 
  "title": "Edit a Widget on an Organization's Dashboard", 
  "warning": null
}
---