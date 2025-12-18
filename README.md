# CloudOpsDec2025

## Access to labs and course materials
- [Access to labs and course materials](https://us-east-1.student.classrooms.aws.training/class/ilt%23fJrEwnzhvo87BwWmV7oMSE) . When you open this link, you will be prompted to signin. The preferred way is using "builder id". Problem is this tipically only works with personal emails. If you want to use your corporate account, choose One-time email password (preferred) or SSO. The SSO option eventually prevents us from working properly on the labs. Once registered, **you will get an access denied, saying "you don't have access to the class. please contaxt xyz for assistance"** error until I add you to the class. Please send me the email used to register through chat.

## Handy learning resources
- [Curated materials for preparing for the CloudOps Engineer exam](https://skillbuilder.aws/category/exam-prep/cloudops-engineer-associate-SOA-C03)
- [Skill builder, a learning platform with plenty of free content, and susbscription-based practical content](https://skillbuilder.aws/)
- [Tech essentials, an interesting pre-req for the class](https://skillbuilder.aws/learn/K8C2FNZM6X/aws-technical-essentials/N7Q3SXQCDY)

## Day 1 links
### Module 1 - Intro to cloudops on AWS
- [There's no place like production](https://imwrightshardcode.com/2010/12/theres-no-place-like-production/)
- [Well architected framework](https://docs.aws.amazon.com/wellarchitected/latest/framework/welcome.html)
- [AWS Post-event summaries](https://aws.amazon.com/premiumsupport/technology/pes/)
- [AWS Service health](https://health.aws.amazon.com/health/status)
- [AWS Cloud adoption framework ebook](https://d1.awsstatic.com/whitepapers/aws-caf-ebook.pdf)
- [Simian army, the precursor to chaos engineering](https://netflixtechblog.com/the-netflix-simian-army-16e57fbab116)
- [Fault injection simulator service in AWS](https://aws.amazon.com/fis/)
- [Security incident response service](https://docs.aws.amazon.com/security-ir/latest/userguide/what-is.html)
- [AWS Service quotas](https://docs.aws.amazon.com/general/latest/gr/aws-service-information.html)
- [FinOps framework](https://www.finops.org/framework/)
- [Customer Carbon Footprint tool documentation](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/ccft-overview.html?region=us-east-2)
### Module 2 - Access Management
- [Tasks that require root user credentials](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_root-user.html#root-user-tasks)
- [Managing access keys](https://docs.aws.amazon.com/IAM/latest/UserGuide/id_credentials_access-keys.html#securing_access-keys)
- [AWS Policy generator](https://awspolicygen.s3.amazonaws.com/policygen.html)
- [IAM global condition keys](https://docs.aws.amazon.com/IAM/latest/UserGuide/reference_policies_condition-keys.html)
- [AWS-managed job function policies](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_job-functions.html)
- [Best practices for a multi-account environment in AWS](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_ous_best_practices.html)
- [IAM policy simulator](https://docs.aws.amazon.com/IAM/latest/UserGuide/access_policies_testing-policies.html)
### Module 3 - System Discovery
- [Setting up session manager](https://docs.aws.amazon.com/systems-manager/latest/userguide/session-manager-getting-started.html)
- [Announcing support for Custom rules using guard](https://aws.amazon.com/blogs/mt/announcing-aws-config-custom-rules-using-guard-custom-policy/)
- [AWS Config conformance pack templates](https://docs.aws.amazon.com/config/latest/developerguide/conformancepack-sample-templates.html)
- [Some config custom rule using Guard](https://github.com/aws-samples/aws-config-custom-rule-cloudformation-guard)
- [Registry with a lot of guard rules](https://github.com/aws-cloudformation/aws-guard-rules-registry)
- [Landing page for documentation about tag policies](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_tag-policies.html)
### Module 4 - Deploy and update resources
- [Process to create an AMI from a Windows instance](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/ami-create-win-sysprep.html)
- [Activating cost-allocation tags](https://docs.aws.amazon.com/awsaccountbilling/latest/aboutv2/activating-tags.html)
- [Pre-requisites for tag policies in an organization](https://docs.aws.amazon.com/organizations/latest/userguide/services-that-can-integrate-tag-policies.html)
- [Best practices for tag policies](https://docs.aws.amazon.com/organizations/latest/userguide/orgs_manage_policies_tag-policies-best-practices.html)
- [Instance metadata service, has a lot of document categories with instance information - metadata, user data, and dynamic data](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/instancedata-data-retrieval.html)
- [EC2 image builder, service to create pipelines for image customization](https://docs.aws.amazon.com/imagebuilder/latest/userguide/what-is-image-builder.html)
## Day 2 links
### Module 5 - Automate Resource Deployment
- [cfn-signal, which allows us to define a more compelx sequence of resource creation](https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/cfn-signal.html)
- [WaitConditions allows us to put the whole stack in a create-in-progress state, until the condition is satisfied](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-waitcondition.html)
- [Using nested stacks](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-nested-stacks.html)
- [CreationPolicy attribute, can be used in some resources to make the resource remain in create-in-progress until it is satisfied](https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/aws-attribute-creationpolicy.html)
- [cfn-init, which takes the actions defined in the AWS::CloudFormation::Init section](https://docs.aws.amazon.com/AWSCloudFormation/latest/TemplateReference/cfn-init.html)
- [Stack sets, allowing us to deploy stacks across accounts and regions](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/what-is-cfnstacksets.html)
- [CloudFormation best practices](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/best-practices.html)
- [Using nested stacks](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-nested-stacks.html)
- [CloudFormation-specific parameter types](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/cloudformation-supplied-parameter-types.html)
- [TaskCat can test stacks across multiple regions](https://github.com/aws-ia/taskcat)

### Module 6 - Manage resources
- [Incident manager is no longer available. Similar functionality is now offered through OpsCenter, and third parties](https://docs.aws.amazon.com/incident-manager/latest/userguide/migration-guides.html)
- [Public parameters in Systems Manager parameter store](https://docs.aws.amazon.com/systems-manager/latest/userguide/parameter-store-public-parameters.html)
- [Defining runbooks](https://docs.aws.amazon.com/systems-manager/latest/userguide/automation-documents.html)
- [Actions available in Systems manager automation documents (runbooks)](https://docs.aws.amazon.com/systems-manager/latest/userguide/automation-actions.html)
- [Change manager is no no longer available. AWS has no equivalent service, recommending to browse the partner network](https://docs.aws.amazon.com/systems-manager/latest/userguide/change-manager-availability-change.html)
- [Some automation documents published by AWS](https://github.com/awslabs/aws-systems-manager/tree/master/Documents)
### Module 7 - Configure highly available systems
- [Announcement of gateway load balancer](https://aws.amazon.com/blogs/aws/introducing-aws-gateway-load-balancer-easy-deployment-scalability-and-high-availability-for-partner-appliances/)
- [Route 53 routing policies](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-policy.html)
- [Route 53 shuffle sharding](https://aws.amazon.com/blogs/architecture/shuffle-sharding-massive-and-magical-fault-isolation/)
- [Resource types supported as targets in route 53](https://docs.aws.amazon.com/Route53/latest/DeveloperGuide/routing-to-aws-resources.html)
### Module 8 - Automate scaling
- [Avaliable health check in autoscaling groups](https://docs.aws.amazon.com/autoscaling/ec2/userguide/ec2-auto-scaling-health-checks.html)
- [Allocation strategies for auto-scaling groups](https://docs.aws.amazon.com/autoscaling/ec2/userguide/allocation-strategies.html)
- [Only in Jan 2025, the STS global endpoint became really global. Until then, it was Virginia-based](https://aws.amazon.com/blogs/security/announcing-upcoming-changes-to-the-aws-security-token-service-global-endpoint/)
- Load testing tools
  - [JMeter](https://jmeter.apache.org/)
  - [Artillery](https://www.artillery.io/)
  - [The grinder](https://github.com/cossme/grinder)
- [Spot instance termination notices](https://docs.aws.amazon.com/AWSEC2/latest/UserGuide/spot-instance-termination-notices.html)
- [Node termination handler on EKS](https://github.com/aws/aws-node-termination-handler#aws-node-termination-handler)
- [Spot instance advisor](https://aws.amazon.com/ec2/spot/instance-advisor/)
- [BYOL for Windows servers licenses is supported with some constraints](https://aws.amazon.com/blogs/modernizing-with-aws/operating-byol-windows-server-workloads-effectively-on-aws/)
- [Managing Oracle licesnes using License Manager](https://aws.amazon.com/blogs/mt/tracking-your-oracle-licenses-using-aws-license-manager/)
### Module 9 - Monitor and Maintain System Health
- [Important announcements related to CloudOps from re:invent 2025](https://aws.amazon.com/blogs/mt/2025-top-10-announcements-for-aws-cloud-operations/)
- [Cloudwatch investigations](https://aws.amazon.com/blogs/aws/investigate-and-remediate-operational-issues-with-amazon-q-developer/)
- [Sample architecture to transform how cloud operations teams handle incidents using AI - AIOps](https://aws.amazon.com/blogs/mt/reimagine-aiops-with-amazon-cloudwatch-investigations-and-amazon-nova-sonic/)
- [Operationalizing CloudWatch Anomaly Detection](https://aws.amazon.com/blogs/mt/operationalizing-cloudwatch-anomaly-detection/)
- [CloudWatch outlier detection](https://docs.aws.amazon.com/AmazonCloudWatch/latest/monitoring/CloudWatch_Anomaly_Detection.html)
- [Advanced analytics using Amazon CloudWatch Logs Insights - using SQL](https://aws.amazon.com/blogs/mt/advanced-analytics-using-amazon-cloudwatch-logs-insights/)
- [EventBridge support for SaaS event sources - 9 partners when announced, 60 in December 2025](https://aws.amazon.com/blogs/aws/amazon-eventbridge-event-driven-aws-integration-for-your-saas-applications/)
- [Migrating from X-ray to OTel](https://docs.aws.amazon.com/xray/latest/devguide/xray-sdk-migration.html)
- [Cloudwatch application signals](https://aws.amazon.com/blogs/mt/amazon-cloudwatch-application-signals-new-enhancements-for-application-monitoring/)

## Day 3 links
### Module 10 - Data security and system auditing
- [When and where to use IAM permission boundaries](https://aws.amazon.com/blogs/security/when-and-where-to-use-iam-permissions-boundaries/)
- [Interesting examples about permission boundaries](https://github.com/aws-samples/example-permissions-boundary)
- [Inspector V2 does continuous scanning and scans ECR images](https://aws.amazon.com/blogs/aws/improved-automated-vulnerability-management-for-cloud-workloads-with-a-new-amazon-inspector/)
### Module 11 - Opeate secure and resilient networks
- [Introducing regional NAT gateway](https://aws.amazon.com/blogs/networking-and-content-delivery/introducing-amazon-vpc-regional-nat-gateway/)
