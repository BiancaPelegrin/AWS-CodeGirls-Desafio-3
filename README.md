# AWS-CodeGirls-Desafio-3



## AWS CloudFormation — Automatizando Infraestrutura com Código
Nesta fase do meu aprendizado em AWS, explorei o CloudFormation, uma ferramenta que permite construir e organizar toda a infraestrutura na nuvem usando arquivos de configuração. Com ela, é possível definir recursos como redes, servidores e armazenamento de forma automatizada e consistente.

## 🧠 O que é o CloudFormation?
O AWS CloudFormation é um serviço que transforma arquivos escritos em YAML ou JSON em ambientes completos na AWS. Em vez de configurar tudo manualmente pelo console, você descreve os recursos em um template e deixa o CloudFormation cuidar do resto.

Essa prática segue o conceito de Infraestrutura como Código (IaC), que facilita a reprodução, controle de versões e automação de ambientes.

## 🛠️ O que aprendi ao criar uma Stack
Durante o desafio, simulei a criação de uma Stack no CloudFormation, documentando cada etapa sem realizar o deploy real. Isso me ajudou a entender o fluxo completo de provisionamento.

Etapas que segui:
Planejamento dos recursos
Listei os componentes necessários (como VPC, EC2, RDS, S3, etc.) e suas relações.

Criação do template
Estruturei o arquivo com seções como Parameters, Resources, Outputs e Conditions, tornando-o reutilizável e flexível.

Validação do template
Testei a estrutura e lógica do arquivo para garantir que tudo estava correto antes de qualquer execução.

Preparação para o deploy
Revisei parâmetros, tags e permissões, simulando o processo de criação via console e CLI.

Monitoramento da Stack
Estudei como acompanhar os eventos de criação e como usar o CloudWatch para identificar falhas ou confirmar sucesso.

Atualizações seguras com Change Sets
Aprendi a revisar alterações antes de aplicá-las, evitando impactos inesperados.

Rollback e exclusão
Entendi como o CloudFormation lida com falhas e como remover stacks de forma segura.

## 📦 Por que usar Stacks?
Agrupam recursos relacionados para facilitar o gerenciamento.
Permitem criar ambientes idênticos (dev, test, prod) com rapidez.
Facilitam o versionamento e auditoria da infraestrutura.
Automatizam processos e integram com pipelines de CI/CD.
Reduzem erros manuais e garantem consistência entre ambientes.
