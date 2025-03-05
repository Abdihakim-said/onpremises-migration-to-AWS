
###  Part 2: Migration of a Workload running in a Corporate Data Center to AWS using the Amazon EC2 and RDS service



![1-PORTFOLIO PROJECTS_AWS - MODULE 3_THUMBNAIL](https://github.com/user-attachments/assets/1ad5b3af-4ded-4e0e-b19d-6d8e65b4280d)

### Problem

The existing application and database were running on a legacy system in a corporate data center. This setup posed several challenges, including high maintenance costs, limited scalability, and potential reliability issues. The legacy infrastructure was not able to keep up with the growing demands of the business, leading to performance bottlenecks and increased downtime.

### Reason for Migration

To address these challenges, we decided to migrate the workload to AWS. The key reasons for choosing AWS included:

1. **Scalability**: AWS provides the ability to scale resources up or down based on demand, ensuring that the application can handle varying loads efficiently.
2. **Cost Efficiency**: By moving to AWS, we could take advantage of the pay-as-you-go pricing model, reducing the overall infrastructure costs.
3. **Reliability**: AWS offers high availability and fault tolerance, which are critical for maintaining the uptime and performance of the application.
4. **Security**: AWS provides robust security features and compliance certifications, ensuring that the application and data are protected.

### Solution Provided by AWS Migration

To successfully migrate the workload to AWS, we implemented the following steps:

1. **Custom Network Configuration**: We created a custom VPC with specific subnets and security groups to mirror the on-premises network setup. This ensured that the application could operate in a familiar network environment.
2. **Security Adjustments**: We adjusted the security group rules to ensure that all necessary ports and protocols were allowed, matching the on-premises firewall settings. This helped maintain the security posture of the application.
3. **Resource Provisioning**: We set up Amazon EC2 instances for the application servers and Amazon RDS for the database, following best practices for performance and security.
4. **Dry-run Testing**: We conducted multiple dry-run tests to validate the network and security configurations before the final cutover. This helped identify and resolve any potential issues, ensuring a smooth migration.
5. **Final Migration (Cutover)**: We performed the final migration, switching the production environment to AWS with minimal downtime.

By leveraging AWS services, we were able to achieve improved scalability, cost efficiency, reliability, and security for the application, addressing the limitations of the legacy system.


![1-PORTFOLIO PROJECTS_AWS - MODULE 3_ARCHITECTURE](https://github.com/user-attachments/assets/c53e1483-2c46-4557-a897-d25c47e92599)

