# nodeless
primeira funcao lambda na aws

CRIANDO PROJETO >>>>>>>>>>>>
serverless create --template aws-nodejs --path nodeless

CONFIGURANDO ACESSO A AWS >>>>> 
serverless config credentials -o --provider aws --key AKIAVZ26VVN3JHPHW75A --secret 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

DEPLOY / SUBIR PRA AWS >>>>>
serverless deploy

RODAR >>>>>
serverless invoke -f hello -l
