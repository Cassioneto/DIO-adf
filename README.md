# DIO-adf
 Exercise create a data factory of data bricks course

#  Falta de imagens ou screenshot
 Não tenho como obter uma conta Azure, por falta de um cartão internacional ou uma conta estudante (sou de Angola).

 #  Dashboard
 o Dashboard é uma visualização do Azure, totalmente personalizável onde podemos "pinar" o que queremos ver sobre recursos, custos, métricas sobre recursos...
 Podemos ter mais de um Dashboard, onde podemos personalizar todos de maneira independente.
 Também podemos fazer ações rápidas sobre um recurso desde que esteja "pinado" no nosso Dashboard.

 #  Criar recurso
 Seja pesquisando o recurso, que no caso será o Azure data factory, na barra superior ou na opção criar recurso e nesta página buscar o recurso:
 *+ Deve ter um nome
  Embora não obrigatório, é altamente recomendado seguir a convenção de nomenclatura disponível em https://learn.microsoft.com/pt-br/azure/cloud-adoption-framework/ready/azure-best-practices/resource-abbreviations, que no caso do Azure Data factory é "adf".
*+ Subscrição associada ao recurso a criar,
 Todo recurso deve ter uma subscrição, onde serão descontados os custos financeiros gastos pelo recurso.
 Mesmo uma conta para estudante ou uma conta Azure gratuita, é disponibilizada uma subscrição ou assinatura. Uma conta Azure pode ter mais de uma subscrição.
 *+ Grupo de recurso
  Todo recurso deve estar associado exclusivamente a um grupo de recurso.
  o grupo é utilizado para associar, organizar e monitorar recursos, seja para operações rápidas, como para controle de custos e outros.
*+ Marcas
 As marcas podem ser definidas de forma opcional, sua aplicação é quase semelhante ao grupo de recursos, embora não ser de definição obrigatória e poder ser atribuída mais de uma marca.
 Por exemplo podemos ter uma marca para todos os recursos de todos departamentos, como o de vendas, e visualizar todos os recursos de vendas através dessa marca, bem como desligar esses recursos asociados a ela.

*+ Template AML 
 Todo recurso ao ser criado podemos salvar um template JSON onde descreve todas as características citadas para recriar o mesmo recurso mantendo toda as configurações selecionadas.
 É útil para recriar o mesmo recurso ou para criação de recurso do mesmo tipo em massa, mudando o nome apenas por exemplo.

 #   Outras interfaces de criação\manipulação aos recursos
 Além do painel web do Azure, podemos gerir os recursos pelo Azure cloud shell onde através de comandos bash ou comandos "power-shell" criar um recurso por exemplo, e os SDK de linguagem de programação, como por exemplo Python, C#, Java e outras, criar scripts onde podemos replicar todas as ações disponíveis no painel web.