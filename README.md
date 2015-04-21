# aws-dubstep



## Examples

```
aws --profile=test cloudformation create-stack \
  --template-body file://poc/app_stack/web_server/elb-single.cft.json \
  --parameters file://cft-params/single-instance-with-elb.json \
  --stack-name testing-cf
```

## ELBs

### VPC

http://docs.aws.amazon.com/ElasticLoadBalancing/latest/DeveloperGuide/UserScenariosForVPC.html

### Classic

http://docs.aws.amazon.com/ElasticLoadBalancing/latest/DeveloperGuide/UserScenariosForEC2.html
