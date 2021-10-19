# IAC - Infraestructure as Code -Infraestrutura como Código
## Chega de criar tudo na mão, todas a vezes!
"Infraestrutura como Código é uma abordagem para automação de infraestrutura baseada em práticas do desenvolvimento de software. Enfatiza rotinas consistentes e repetíveis para provisionamento e mudança de sistemas e sua configuração. Você faz alterações no código e usa a automação para testar e aplicar essas alterações em seus sistemas." [Fonte.](https://www.oreilly.com/library/view/infrastructure-as-code/9781098114664/ch01.html)

## Provisionadores x Gerenciadores de Configurações
 **Gerenciadores de Configurações**
 Ferramentas de gerenciamento de configuração  podem instalar e configurar os aplicativos em infraestruturas existentes.
  **Provisionadores**
Eles podem ser usados para prover os servidores e outras infraestruturas, como balanceadores de carga, bancos de dados, configuração de rede, etc...

Exemplos:
| Provisionadores | Gerenciadores de Configurações |
| ------ | ------ |
|Terraform | Ansible|
|AWS CloudFormation| Chef |
|Pulumi |Puppet
Material: https://www.nexastack.com/en/blog/best-iac-tools

# Terraform
Terraform é a ferramenta mais popular e de código aberto para automação de infraestrutura desenvolvida e mantida pela HashiCorp. Ajuda na configuração, provisionamento e gerenciamento da infraestrutura como código. Com terraform,você pode facilmente planejar e criar IaC em vários provedores de infraestrutura com o mesmo fluxo de trabalho.

## Componentes
**Providers:**
Terraform depende de plug-ins chamados "provedores" para interagir com provedores de nuvem, provedores de SaaS e outras APIs.

**Resources:**
*Os recursos* são o elemento mais importante na linguagem Terraform. Cada bloco de recursos descreve um ou mais objetos de infraestrutura, como redes virtuais, instâncias de computação ou componentes de nível superior, como registros DNS.

**Data Sources:**
As *fontes de dados* permitem que o Terraform use informações definidas fora do Terraform, definidas por outra configuração separada do Terraform ou modificadas por funções

**Variables & Outputs:**
*As variáveis de entrada* servem como parâmetros para um módulo Terraform, para que os usuários possam personalizar o comportamento sem editar a fonte.
*Valores de saída* são como valores de retorno para um módulo Terraform.
**Locals:**
*Os locais* são valores nomeados aos quais você pode se referir em sua configuração. Você pode usar valores locais para simplificar a configuração do Terraform e evitar a repetição.

**Modules:**
*Módulos* são contêineres para vários recursos usados juntos. 
**States:**
O Terraform deve armazenar o *estado* sobre sua infraestrutura e configuração gerenciadas. Esse estado é usado pelo Terraform para mapear recursos do mundo real para sua configuração, controlar os metadados e melhorar o desempenho de grandes infraestruturas.
**Backend:**
Os backends são responsáveis por armazenar o estado em uma local remoto onde mais de uma pessoa possa trabalhar.

<div align=center>
    <img src="https://jloudon.com/assets/images/terraform4.png" />
</div>


## Heroku 

**Heroku** é uma [plataforma de](https://en.wikipedia.org/wiki/Platform_as_a_service "Plataforma como serviço") nuvem [como serviço](https://en.wikipedia.org/wiki/Platform_as_a_service "Plataforma como serviço") (PaaS) que suporta várias [linguagens de programação](https://en.wikipedia.org/wiki/Programming_language "Linguagem de programação") .
ster/plugins/googleanalytics/README.md>
