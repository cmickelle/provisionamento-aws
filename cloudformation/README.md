aws cloudformation create-stack --stack-name create-repository --template-body file://cloudformation/ecr/repository.yaml  --capabilities CAPABILITY_NAMED_IAM

aws cloudformation create-stack --stack-name build-api --template-body file://cloudformation/build/build.yaml  --capabilities CAPABILITY_NAMED_IAM


./cloudformation\ecr\repository.yaml