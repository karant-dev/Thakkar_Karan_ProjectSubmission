# Screenshots Overview

This document describes the contents of the `../Screenshots/` folder recursively, grouped by subfolder.

## app/

- `Screenshots/app/valid.jpg`: Chat app with an accepted (valid) prompt.
- `Screenshots/app/invalid.jpg`: Chat app showing rejected prompts (fails validation).
- `Screenshots/app/sources.jpg`: Extra feature: Response with extracted source document citations.

## base-infra-creation/

- `Screenshots/base-infra-creation/bedrock-integration-table.jpg`: Aurora PostgreSQL `bedrock_integration.bedrock_kb` table schema with pgvector column and indexes.
- `Screenshots/base-infra-creation/pg-extension.jpg`: PostgreSQL extensions view showing `vector` (pgvector) enabled.
- `Screenshots/base-infra-creation/secrets-manager.jpg`: AWS Secrets Manager entry storing Aurora credentials for Data API access.
- `Screenshots/base-infra-creation/stack1-tf-output.jpg`: Terraform apply outputs for Stack 1 (Aurora, VPC, subnets, bucket).
- `Screenshots/base-infra-creation/stack2-tf-output.jpg`: Terraform apply outputs for Stack 2 (Bedrock Knowledge Base identifiers).

## kb-deployment-and-data-sync/

- `Screenshots/kb-deployment-and-data-sync/bedrock-knowledge-base.jpg`: Bedrock Knowledge Base configuration page (RDS-backed vector store).
- `Screenshots/kb-deployment-and-data-sync/s3-to-kb-sync.jpg`: Data source sync from S3 to the Knowledge Base.

## python-integration-with-kb/

- `Screenshots/python-integration-with-kb/generate-response.jpg`: Model generation step using retrieved context.
- `Screenshots/python-integration-with-kb/query-knowledge-base.jpg`: Knowledge Base retrieval request and results.
- `Screenshots/python-integration-with-kb/valid-prompt.jpg`: Prompt validation classification pathway (Category E allowed).
