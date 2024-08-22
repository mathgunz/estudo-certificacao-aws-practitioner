# estudo-certificacao-aws-practitioner
Documento e projetos da aws

# LightSail
É um serviço que simplifica toda criação e gestão de containers, volumes, rede e segurança de forma pratica e intuitiva. Possui uma tabela de preço com planos.
É bem util para startups que precisam ter uma infraestrutura rapida para construção rapida de sistemas.

## Criação de instancias
 - Simples e instuitivo
 - Criar ip statico.

## Site para criar dominios baratos para estudos
www.namecheap.com
é necessario criar um IP estático na aws e usar esse ip e vincular com o dominio no namecheadp.

## Instancias
- "python3 -m http.server" na console da instancia para identificar qual porta uma aplicação está rodando.

### Loadbalancer - Criando um ambiente com alta disponibilidade.
Devemos criar um loadbalance e vinvular as instancias para ele poder cuidar.
Vinculamos um health check pra validar se está ativo.
É possivel olhar metricas e também lancar um email caso x instancias caiam.

