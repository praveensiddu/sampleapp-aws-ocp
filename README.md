# sampleapp-aws-ocp
https://docs.openshift.com/container-platform/4.10//backup_and_restore/application_backup_and_restore/installing/installing-oadp-aws.html#oadp-installing-dpa_installing-oadp-aws

aws s3api create-bucket --bucket $BUCKET --region $REGION
aws iam create-user --user-name velero
