## Server Access Logging

Enabled server access logging for:
- exam-analytics-raw-dev → s3://exam-analytics-logs-dev/raw/
- exam-analytics-processed-dev → s3://exam-analytics-logs-dev/processed/
- exam-analytics-curated-dev → s3://exam-analytics-logs-dev/curated/

Notes:
- S3 access log delivery is asynchronous and may be delayed.
- Logs appear only after access events occur.
