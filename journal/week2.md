# Week 2 — Distributed Tracing

#  Instrument backend flask application to use Open Telemetry (OTEL) with Honeycomb.io as the provider
- Configured our backend flask application to use Open Telemetry (OTEL) with Honeycomb.io as the provider to enable distributed tracing and performance monitoring. Used the Open Telemetry Python library to instrument the application and integrated it with the Honeycomb.io platform to view and analyze traces.

# Run queries to explore traces within Honeycomb.io
- Used the Honeycomb.io platform to run queries and explore traces collected from our backend flask application using Open Telemetry. Analyzed the data to identify bottlenecks and optimize performance.

# Instrument AWS X-Ray into backend flask application
- Configured our backend flask application to use AWS X-Ray to enable distributed tracing and performance monitoring. Used the AWS X-Ray SDK for Python to instrument the application and send trace data to the X-Ray daemon.

# Configure and provision X-Ray daemon within docker-compose and send data back to X-Ray API
- Configured and provisioned the X-Ray daemon within our docker-compose file to collect trace data from our backend flask application. Configured the daemon to send the data back to the X-Ray API for analysis and monitoring.

# Observe X-Ray traces within the AWS Console
- Used the AWS Console to observe and analyze traces collected from our backend flask application using AWS X-Ray. Analyzed the data to identify bottlenecks and optimize performance.

# Integrate Rollbar for Error Logging
- Integrated Rollbar into our backend flask application to monitor and track errors. Configured the Rollbar SDK for Python to send error data to the Rollbar platform for analysis and monitoring.

# Trigger an error and observe an error with Rollbar
- Triggered an error within our backend flask application and observed the error data collected by Rollbar. Analyzed the data to identify the root cause of the error and implement a fix.

# Install WatchTower and write a custom logger to send application log data to CloudWatch Log group
- Installed WatchTower to collect application log data and wrote a custom logger to send the data to a CloudWatch Log group for analysis and monitoring. Configured the logger to include relevant metadata such as request ID and user ID for easy traceability.

# Github Tags 
- I was able to add tags to my commits with the following commands
- git tag <tagname> => create a new tag
- git tag -a <tagname> -m "Your tag message here" => creates a new annotated tag with message
- git tag => lists all tags
- git push origin <tagname> => Push a tag to a remote respository
- git push --tags => push all tags
- git tag -d <tagname> => delete a tag locally
- git push --delete origin <tagname> => delete a tag on the remote repository