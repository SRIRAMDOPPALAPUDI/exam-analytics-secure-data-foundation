## IAM Roles (Least Privilege)

### ExamIngestionRole
- Write access to raw bucket
- s3:PutObject on arn:aws:s3:::exam-analytics-raw-dev/*

### ExamProcessingRole
- Read raw bucket, write processed bucket
- s3:GetObject on raw/*
- s3:PutObject on processed/*

### ExamCurationRole
- Read processed bucket, write curated bucket
- s3:GetObject on processed/*
- s3:PutObject on curated/*

### ExamAnalyticsRole
- Read-only curated bucket
- s3:GetObject on curated/*
