# example-actions
- o valor da variavel TF_API_TOKEN, foi gerado pelo site app.terraform.io/app/settings/tokens
- para funcionar o actions, precisa criar um workspace orientado por API
- obs: precisamos configurar as variaveis de ambiente abaixo no workspace, afim do mesmo acessar nossa conta na aws
  - AWS_ACCESS_KEY_ID
  - AWS_SECRET_ACCESS_KEY
  - region
  - environment
- no arquivo gha.hcl, precisamos colocar a origanização configurada no site app.terraform.io e o workspace utilizado no mesmo