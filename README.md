# Activity-audit
# Name -Harish N

# Reg No. - 212225220037
Exp Auditing Cloud Activity Using AWS CloudTrail

# Aim
To enable and analyze AWS CloudTrail logs to audit user and resource activities in a cloud environment.

# Requirements
AWS Console access CloudTrail service enabled S3 bucket (for storing logs) IAM permissions to view audit logs

# Procedure
Step 1: Enable CloudTrail Go to CloudTrail from AWS Console Click Trails > Create trail Name: CloudAuditTrail Apply trail to all regions Log events:

# Management events:
Read & Write Data events: S3, Lambda (optional) Create or select an S3 bucket for log storage Enable CloudWatch Logs integration (optional) Step 2: Review Event History Go to Event history Filter events by:

Username (IAM role or user) Event name (e.g., CreateBucket, TerminateInstances) Date/Time Resource type (e.g., S3, EC2) Step 3: Download or Export Logs Use the Download CSV option to export logs Analyze logs in Excel/Sheets for reporting
# output:
<img width="1064" height="868" alt="640784496-96702f66-bf54-4f3a-a846-a96f21e4f017" src="https://github.com/user-attachments/assets/fa287b3e-b179-4043-91fd-850ac22104ea" />
<img width="1064" height="868" alt="640784441-949b5c90-4ee6-4a4f-841a-0fa3edf8213d" src="https://github.com/user-attachments/assets/0976f8d4-2010-432f-a924-9b044f246925" />
