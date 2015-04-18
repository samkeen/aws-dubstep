# aws-dubstep



## Examples

```
aws --profile=test cloudformation create-stack \
  --template-body file://poc/single-instance.cft.json \
  --parameters file://cft-params/single-instance.json \
  --stack-name testing-cf
```

## ELBs

### VPC

http://docs.aws.amazon.com/ElasticLoadBalancing/latest/DeveloperGuide/UserScenariosForVPC.html

### Classic

http://docs.aws.amazon.com/ElasticLoadBalancing/latest/DeveloperGuide/UserScenariosForEC2.html
