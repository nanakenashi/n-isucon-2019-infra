# n-isucon-2019-infra
Stack for n-isucon-2019

```
aws cloudformation create-stack \
  --stack-name n-isucon-2019 \
  --template-body file://`pwd`/template.yml \
  --parameters file://`pwd`/parameters/production.json

aws cloudformation update-stack \
  --stack-name n-isucon-2019 \
  --template-body file://`pwd`/template.yml \
  --parameters file://`pwd`/parameters/production.json

aws cloudformation delete-stack \
  --stack-name n-isucon-2019
```
