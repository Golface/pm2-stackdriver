# PM2 Stackdriver logging module

## Configuration

 * "pm2_stackdriver_enabled" Checks if the module is enabled or not (Default: false)
 * "pm2_stackdriver_on_google" Checks if we are on google cloud or not (Default: false)
 * "pm2_stackdriver_projectId" Set the project id when we are not google cloud 
 * "pm2_stackdriver_keyFile" Set the credentials for google cloud

```sh
pm2 set @golface/pm2-stackdriver:pm2_stackdriver_enabled true
pm2 set @golface/pm2-stackdriver:pm2_stackdriver_on_google true
pm2 set @golface/pm2-stackdriver:pm2_stackdriver_projectId <project id>
pm2 set @golface/pm2-stackdriver:pm2_stackdriver_keyFile <key path>
pm2 set @golface/pm2-stackdriver:pm2_stackdriver_log_name <log name>
pm2 set @golface/pm2-stackdriver:pm2_stackdriver_error_log_name <error log name>
```

