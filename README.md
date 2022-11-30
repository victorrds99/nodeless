# nodeless
primeira funcao lambda na aws

CRIANDO PROJETO >>>>>>>>>>>>
serverless create --template aws-nodejs --path nodeless

CONFIGURANDO ACESSO A AWS >>>>> 
serverless config credentials -o --provider aws --key SENHA_AWS --secret SECRET_AWS

DEPLOY / SUBIR PRA AWS >>>>>
serverless deploy

RODAR >>>>>
serverless invoke -f hello -l
