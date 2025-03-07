npm install -g aws-cdk
cdk --version
-- 
cdk init app --language=typescript(Dir. must be empty)
npm install twilio (sms)
npm i aws-sdk
npm i aws-lambda
npm install --save-dev @types/aws-lambda
npm i class-validator
npm i class-transformer
npm i @sendgrid/mail

define stacks for notification
create lib/service-stack.ts
define lambda-function
mkdir src (inside noti-service)
mkdir dtos handlers providers utility (inside src)
