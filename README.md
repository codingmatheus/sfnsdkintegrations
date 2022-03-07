# AWS Step Functions AWS SDK Integrations Demos

Simple workflow facilitating the showcase of differences between using Optimized and AWS SDK integrations to invoke an AWS Lambda function.
## Notes

- All SAM templates will have a samconfig.toml file containing defaults for the SAM build and deployment. Feel free to update those parameters to your convenience, however, do not change the stack name as it may be used by other scripts and could break the build and deploy process.

- **All stacks will deploy by defaul to the eu-west-1 (Ireland) region.** You can easily change that in the samconfig.toml file included or use ```sam deploy --guided``` to override it.

## **Demos**

### **Lambda Optimized Integration vs AWS SDK Integration**
#### Usage Guide
- ![#f03c15](https://via.placeholder.com/15/f03c15/000000?text=+)  **Build requirements**
    - AWS SAM CLI installed (instructions: https://docs.aws.amazon.com/serverless-application-model/latest/developerguide/serverless-sam-cli-install.html)

- ![#1589F0](https://via.placeholder.com/15/1589F0/000000?text=+) **Artifacts**
    - SAM template
        - deploys an AWS Step Functions workflow and an AWS Lambda function

- ![#c5f015](https://via.placeholder.com/15/c5f015/000000?text=+) **Instructions**
    - navigate to lambda/optimized_vs_sdk folder
    - run: ```sam build```
    - run: ```sam deploy```
