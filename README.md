## This repo contains standard basic demo assests for demo of Fugue

**1. FugueDemo.lw -** Composition uses policies in DemoPolicies directory and throws 3 validation errors (Region, Instance size and missing Name tag for SG) 

**2. FugueDemo-fixed.lw -** Fixed Composition of the example above

**3. CFnvsFugue -** Example of CloudFormation template and what it looks like with Fugue with additional Validations for tagging. Template created using CloudFormation designer and only contains 1 VPC, 1 Subnet, 1 SG and 1 EC2 instance with a bunch of parameters for regions, HVMs and AMIS

**4. fugue-policy -** Git Submodule for CIS and future GDPR Validations. Repo can be accessed at https://github.com/LuminalHQ/fugue-policy. See below to update this submodule to pull latest version

**5. sample-gdpr-policies -** Git Submodule for a very small subset of basic policies mapping to GDPR requirements for demo needs only. Repo can be accessed at https://github.com/fugue-ankush/sample-gdpr-policies. See below to update this submodule to pull latest version

**6. validation-index -** Git Submodule for initial version of HIPAA and NIST policies. Repo can be accessed at https://github.com/LuminalHQ/validation-index. See below to update this submodule to pull latest version

### Instructions to work with this repo and submodules:
1. Clone main repo: `git clone --recurse-submodules https://github.com/fugue-ankush/demo-assests.git`
2. Update submodules to pull latest build: `git submodule update --remote`
> This points to `master` branch of each submodule 



