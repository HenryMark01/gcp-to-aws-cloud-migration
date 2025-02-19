# AWS Migration from Google Cloud Platform (GCP)

## Overview
![](./media/architecture.png)
This repository documents my experience in successfully migrating virtual machines from Google Cloud Platform (GCP) to Amazon Web Services (AWS) using AWS Application Migration Service (AWS MGN). The goal was to ensure a smooth, automated, and efficient transition while minimizing downtime and operational disruption.

## Key Benefits
- **Seamless Migration:** I streamlined the process to move workloads from GCP to AWS with minimal configuration.
- **Business Continuity:** Ensured smooth operations with live migration and minimal downtime.
- **Automated Process:** Reduced manual intervention through automated replication and deployment.
- **Scalability:** Designed a flexible infrastructure to dynamically adapt based on business needs.
- **Security & Compliance:** Leveraged AWS’s robust security framework to safeguard critical workloads.

## Migration Process
1. **Initial Setup:**
   - Configured AWS MGN and established replication settings.
   - Installed the AWS replication agent on source GCP Compute Engine instances to facilitate migration.

2. **Data Replication:**
   - Enabled continuous block-level data replication.
   - Monitored real-time migration progress via AWS Management Console to ensure data integrity.

3. **Testing & Validation:**
   - Launched test instances to validate application performance on AWS.
     ![](./media/dashboard.png)
   - Ensured network connectivity and security settings were optimized for a smooth transition.

4. **Cutover Execution:**
   - Transitioned workloads to AWS by launching production instances.
   - Conducted rigorous verification to ensure operational stability before finalizing the migration.

5. **Post-Migration Optimization:**
   - Implemented cost-optimization strategies to enhance efficiency.
   - Decommissioned outdated GCP resources to prevent unnecessary costs and ensure a streamlined infrastructure.

## Prerequisites
- Active AWS and GCP accounts.
- Proper IAM permissions configured for AWS MGN.
- Network connectivity established between GCP and AWS environments.
