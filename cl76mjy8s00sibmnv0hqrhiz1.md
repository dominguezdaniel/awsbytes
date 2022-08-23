## Amazon RDS for Oracle now supports managed Oracle Data Guard Switchover and Automated Backups for read replicas

[Amazon Relational Database Service (Amazon RDS) for Oracle](https://aws.amazon.com/rds/oracle/) supports Oracle Data Guard Switchover and Automated Backups for read replica instances (read-only and mounted) deployed in separate AWS Regions, or in different Availability Zones of a given Region.  

The Oracle Data Guard Switchover feature allows you to reverse the roles between the primary database and one of its standby databases (replicas) with no data loss and a brief outage. It provides a complete automation to reliably perform periodic disaster recovery drills when the primary is active or any infrastructure maintenance of the primary environment. Once a switchover is initiated, the primary database transitions to a standby role, and the standby database transitions to the primary role. Bystander replicas that are not part of the switchover are reconfigured for replication from the new primary database.

Until today, with RDS for Oracle read and mounted replicas, in order to perform a disaster recovery drill, you needed to promote the replica as a new standalone database and then create a new replica to maintain the replication configuration. Managed Oracle Data Guard Switchover enhances the customer experience by simply reversing the roles of the databases without having to recreate the replicas.

You can also now create Automated Backups and manual DB snapshots of an RDS for Oracle replica, which reduces the time spent taking backups following a role transition. Furthermore, you can create a new DB instance by restoring from such DB snapshot or perform a point-in-time recovery.

Oracle Data Guard Switchover operation is available in all AWS Regions and incurs no additional cost. You will need an Oracle Enterprise Edition (EE) license to use read replicas in mounted mode, and an additional Oracle Active Data Guard license to use read replicas in read-only mode. Please check with your legal team or a licensing expert to confirm whether your Oracle license(s) cover your specific use case.

To learn more about these new features, please visit the Amazon RDS for Oracle [documentation](https://docs.aws.amazon.com/AmazonRDS/latest/UserGuide/oracle-replication-switchover.html) page.

> Source: https://aws.amazon.com/about-aws/whats-new/2022/08/amazon-rds-oracle-supports-managed-oracle-data-guard-switchover-automated-backups-replicas/