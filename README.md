# aws-dubstep



## Examples

```
aws --profile=test cloudformation create-stack \
  --template-body file://poc/single-instance.cfm.json \
  --parameters file://cft-params/single-instance.json \
  --stack-name testing-cf
```
