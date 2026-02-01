# AWS Infrastructure & Architecture Portfolio

This portfolio documents my hands-on, build-as-I-learn journey while preparing
for the AWS Solutions Architect - Associate (SAA-C03), with a strong focus on
secure infrastructure design, least-privilege access, and architectural
decision-making.

## Focus Areas
- AWS Identity & Access Management (IAM)
- Secure EC2 baseline architectures
- Storage design and trade-offs (EBS, EFS, Instance Store)
- CLI-driven workflows and automation mindset

## Projects

#### aws-iam-basics-lab/
- **[aws-iam-foundations](https://github.com/caiofrnca/aws-iam-foundations)** - Identity design using users, groups, roles, policies, MFA, and IAM security tools

#### aws-ec2-alb-asg/
- **[aws-ec2-storage-decisions](https://github.com/caiofrnca/aws-ec2-storage-decisions)** - Architect-level storage decision-making and recovery patterns
- **[aws-ec2-baseline-architecture](https://github.com/caiofrnca/aws-ec2-baseline-architecture)** - Secure EC2 deployment with IAM roles, security groups, SSH access models, and instance selection
- build-03-alb-asg-ha-pattern/

#### aws-s3-security-lab/
- build-01-s3-secure-bucket-baseline/
- build-02-s3-lifecycle-and-cost/

## Structure overview
```bash
aws-portfolio/
│
├── aws-iam-basics-lab/             #COMPLETED
├── aws-vpc-foundations/ 
├── aws-ec2-alb-asg/
├── aws-s3-security-lab/
├── aws-database-design-notes/
├── aws-logging-and-monitoring/
├── aws-well-architected-review/
├── terraform-aws-vpc/
```
All builds emphasize *design intent*, *security rationale*, and *operational clarity*.
