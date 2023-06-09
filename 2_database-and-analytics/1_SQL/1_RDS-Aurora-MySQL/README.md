# About AWS Aurora

## Use AWS RDS Aurora Serverless Query Editor

Setup your Database with these settings
- creation -> standard create
- configuration -> amazon aurora
- edition -> MySQL 5.6 or better
- instance size -> Serverless
- templates -> dev/test
- UNCHECK `terminatation protection` on

Wait for create to be `ready`, then `Modify`
- Network & Security -> enable `Data API`
- click `update`

Connect to RDS Query Editor
- query editor window will open

Best Practices
- for Aurora generally and also for Aurora MySQL or Aurora Postgres - https://docs.aws.amazon.com/AmazonRDS/latest/AuroraUserGuide/Aurora.BestPractices.html
- Compare RDS instance size capacity and pricing - https://instances.vantage.sh/rds/

---
## Aurora PostgreSQL Example

From the AWS Quickstarts - [here](https://aws.amazon.com/quickstart/architecture/aurora-postgresql/)

![Aurora-postgreSQL](https://github.com/lynnlangit/Hello-AWS-Data-Services/blob/master/images/aurora-postgresql.png)
