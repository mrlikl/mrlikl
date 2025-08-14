# Hi there 👋

<a href="https://www.linkedin.com/in/gosolo/" target="_blank">
  <img src="https://img.shields.io/badge/🔗_LinkedIn-Connect-00d4aa?style=for-the-badge&logo=linkedin&logoColor=white&labelColor=1a1a1a&color=00d4aa" alt="LinkedIn">
</a> 
<a href="mailto:mrlikrsh@gmail.com">
  <img src="https://img.shields.io/badge/📧_Email-Transmit-ff6b6b?style=for-the-badge&logo=gmail&logoColor=white&labelColor=1a1a1a&color=ff6b6b" alt="Email">
</a>
<a href="https://github.com/mrlikl">
  <img src="https://img.shields.io/badge/👾_GitHub-Follow-4ecdc4?style=for-the-badge&logo=github&logoColor=white&labelColor=1a1a1a&color=4ecdc4" alt="GitHub">
</a>

I'm a Cloud Support Engineer (DevOps) with expertise in AWS, Kubernetes, and Infrastructure as Code. I am interested in automating infrastructure at scale, and creating self-service solutions that enable teams to deploy faster and more reliably.

## 🔭 Currently Working On
- Enhancing [spotter](https://github.com/mrlikl/spotter) with Kubernetes-native pod scheduling optimization
- Contributing to open-source CDK

## 🚀 Featured Projects

### Platform Engineering

#### [spotter](https://github.com/mrlikl/spotter)

Production-grade spot instance scheduling system for EKS worker nodes. Intelligently finds the cheapest ARM64 spot instances across availability zones, handles spot interruptions gracefully, and maintains cluster capacity with smart fallback mechanisms.

**Tech Stack**: AWS CDK, Lambda, EventBridge, EKS, CloudFormation, Kubernetes  
**Key Features**: 70-80% cost savings, multi-AZ optimization, intelligent interruption handling, ARM64 focus

#### [db-migration-sample](https://github.com/mrlikl/db-migration-sample)

Complete RDS migration solution demonstrating the transition from Aurora Serverless v1 to v2 using AWS CDK. Includes infrastructure provisioning, data migration strategies, and rollback procedures.

**Tech Stack**: AWS CDK, RDS Aurora, Lambda, CloudFormation  
**Key Features**: Zero-downtime migration, automated rollback, cost optimization

#### [mrlikl.github.io](https://github.com/mrlikl/mrlikl.github.io)

A static website that displays current AWS EC2 Linux On-Demand pricing information across multiple regions. The site is automatically updated weekly using AWS CodeBuild and EventBridge scheduling.

**Tech Stack**: Python, GitHub Pages, AWS CodeBuild, EventBridge  
**Key Features**: Automated weekly updates, multi-region pricing data, serverless automation

### Python Packages & CLI Tools

<div align="center">
<table>
<tr>
<th>Package</th>
<th>Purpose</th>
<th>Links</th>
</tr>
<tr>
<td><strong>cfn2iam</strong></td>
<td>Tool to automatically generate minimal IAM policy to deploy a CloudFormation stack from its template</td>
<td><a href="https://github.com/mrlikl/cfn2iam">GitHub</a> | <a href="https://pypi.org/project/cfn2iam/">PyPI</a></td>
</tr>
<tr>
<td><strong>cfn-cur</strong></td>
<td>Tool to generate CLI commands to recover CloudFormation stacks stuck in <strong>UPDATE_ROLLBACK_FAILED</strong> state</td>
<td><a href="https://github.com/mrlikl/continue-update-rollback">GitHub</a> | <a href="https://pypi.org/project/cfn-cur/">PyPI</a></td>
</tr>
</table>
</div>

**Tech Stack**: Python, Boto3, AWS

## 📝 Technical Blog Posts

#### [How to make AWS SDK calls from AWS CDK using AwsSdkCall](https://repost.aws/knowledge-center/cdk-sdk-calls-awssdkcall)

Comprehensive guide on integrating AWS SDK calls within CDK applications using the AwsSdkCall construct. Covers best practices, error handling, and practical implementation examples for common use cases.

**Topics**: AWS CDK, SDK Integration, Custom Resources, Infrastructure as Code

#### [How to troubleshoot a Windows EC2 instance that failed to signal CloudFormation](https://repost.aws/knowledge-center/cfn-windows-failed-signal-error)

Detailed troubleshooting guide for resolving CloudFormation signal failures on Windows EC2 instances. Includes diagnostic steps, common root causes, and resolution strategies for cfn-signal issues.

**Topics**: CloudFormation, Windows EC2, Troubleshooting, cfn-signal, Instance Initialization

#### [How do I identify resources for CloudFormation to skip for the continue-update-rollback AWS CLI command?](https://repost.aws/knowledge-center/cloudformation-identify-skip-resources)

Guide on identifying resources that can be skipped during a continue-update-rollback operation

**Topics**: CloudFormation, Troubleshooting, update-rollbacks

## 🛠️ Technical Expertise

- **AWS**: EC2, RDS, Lambda, S3, CloudFormation, CDK, CodePipeline, EKS, ECS
- **Kubernetes**: Cluster management, workload deployment, monitoring, troubleshooting
- **AWS CDK**: TypeScript/Python, custom constructs, pipeline automation
- **Terraform**: Resource provisioning, state management, modules

## 📊 GitHub Statistics

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=mrlikl&show_icons=true&theme=synthwave&hide_border=true&bg_color=0d1117&title_color=00d4aa&text_color=4ecdc4&icon_color=ff6b6b)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=mrlikl&layout=compact&theme=synthwave&hide_border=true&bg_color=0d1117&title_color=00d4aa&text_color=4ecdc4)

## 🏆 AWS Certifications

<div align="left">
<a href="https://www.credly.com/badges/44cc653d-c033-40dd-9e8e-e907f8547b68/public_url" title="AWS Certified Cloud Practitioner">
  <img src="https://images.credly.com/size/340x340/images/00634f82-b07f-4bbd-a6bb-53de397fc3a6/image.png" alt="AWS Certified Cloud Practitioner" width="80" height="80" />
</a>
<a href="https://www.credly.com/badges/9a7d2898-fb0a-4af2-92d6-fa8cbc1dac08" title="AWS Certified AI Practitioner">
  <img src="https://images.credly.com/size/340x340/images/4d4693bb-530e-4bca-9327-de07f3aa2348/image.png" alt="AWS Certified AI Practitioner" width="80" height="80" />
</a>
<a href="https://www.credly.com/badges/fae723d0-d151-4fb9-9c4b-a02c7eaa8ecd/public_url" title="AWS Certified Solutions Architect – Associate">
  <img src="https://images.credly.com/size/340x340/images/0e284c3f-5164-4b21-8660-0d84737941bc/image.png" alt="AWS Certified Solutions Architect – Associate" width="80" height="80" />
</a>
<a href="https://www.credly.com/badges/7bcbd611-9adc-4412-bbcd-f10ac5ebbb6f/public_url" title="AWS Certified Solutions Architect – Professional">
  <img src="https://images.credly.com/size/340x340/images/2d84e428-9078-49b6-a804-13c15383d0de/image.png" alt="AWS Certified Solutions Architect – Professional" width="80" height="80" />
</a>
<a href="https://www.credly.com/badges/77a7e731-10e5-42ad-b667-b963d2498e3c/public_url" title="AWS Certified DevOps Engineer – Professional">
  <img src="https://images.credly.com/images/bd31ef42-d460-493e-8503-39592aaf0458/image.png" alt="AWS Certified DevOps Engineer – Professional" width="80" height="80" />
</a>
<a href="https://www.credly.com/badges/d93b77ab-220c-4048-8eba-fb6c56fca884/public_url" title="CloudFormation Subject Matter Expert">
  <img src="https://images.credly.com/images/1c465543-7926-48ef-8dd8-d88ca0a9debb/image.png" alt="CloudFormation Subject Matter Expert" width="80" height="80" />
</a>
<a href="https://www.credly.com/badges/70903ffb-615b-4154-b3a1-f9572c0012c8/public_url" title="CKA: Certified Kubernetes Administrator">
  <img src="https://images.credly.com/size/340x340/images/8b8ed108-e77d-4396-ac59-2504583b9d54/cka_from_cncfsite__281_29.png" alt="CKA: Certified Kubernetes Administrator" width="80" height="80" />
</a>
</div>

## 🤝 Let's Connect

I'm always interested in discussing AWS, Cloud Architecture, DevOps practices, and innovative solutions. Reach out to me at 📧 mrlikrsh@gmail.com
