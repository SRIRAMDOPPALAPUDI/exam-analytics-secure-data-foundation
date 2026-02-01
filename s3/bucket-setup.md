## S3 Buckets Created (us-east-1)

- exam-analytics-raw-dev
- exam-analytics-processed-dev
- exam-analytics-curated-dev
- exam-analytics-logs-dev

## Folder/Prefix Design
Raw:
- exam-logs/
- student-data/
- proctoring-feeds/

Processed:
- exam-logs/
- student-data/
- proctoring-feeds/

Curated:
- kpis/
- reporting/
- ml-ready/

## Security Configuration
- Block public access enabled
- Default encryption enabled (SSE-S3 or SSE-KMS)
- Versioning enabled
- HTTPS-only bucket policy applied
