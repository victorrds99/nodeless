# nodeless
primeira funcao lambda na aws

CRIANDO PROJETO >>>>>>>>>>>>
serverless create --template aws-nodejs --path nodeless

CONFIGURANDO ACESSO A AWS >>>>> 
serverless config credentials -o --provider aws --key KJSHFUHF --secret DFDFGFGTRGTRDG5

DEPLOY / SUBIR PRA AWS >>>>>
serverless deploy

RODAR >>>>>
serverless invoke -f hello -l
