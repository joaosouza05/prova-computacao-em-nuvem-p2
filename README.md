# prova-computacao-em-nuvem-p2

Questões:Nome João Gabriel de Souza Lima 

1. Fundamentos da computação em nuvem
   
1. Qual a diferença entre IaaS e SaaS? Cite um exemplo de utilização de cada modelo.


IaaS (Infraestrutura como Serviço): oferece recursos de infraestrutura pela internet, como servidores, armazenamento e redes. O usuário pode configurar e administrar esses 

recursos. Exemplo: Amazon EC2, utilizado para criar e gerenciar máquinas virtuais na nuvem.

SaaS (Software como Serviço): oferece programas prontos para utilização pela internet, sem precisar instalar ou administrar toda a infraestrutura. Exemplo: Google Drive,

utilizado para armazenar e compartilhar arquivos.

2. Uma empresa utiliza servidores próprios e também recursos de um provedor de nuvem pública. Qual modelo de implantação em nuvem essa empresa utiliza?

A empresa utiliza o modelo de nuvem híbrida, pois combina sua infraestrutura própria (nuvem privada) com recursos de um provedor de nuvem pública.

3. Qual é a principal diferença entre uma máquina virtual e um contêiner?

A máquina virtual possui um sistema operacional próprio, funcionando de maneira independente sobre um servidor físico. Já o contêiner compartilha o kernel do sistema 

operacional do servidor, sendo mais leve e rápido para executar aplicações.

6. Interpretação dos resultados
   
1. Qual a diferença entre uma imagem Docker e um contêiner em execução?

A imagem Docker é um modelo que contém os arquivos, dependências e configurações necessários para executar uma aplicação. O contêiner é a instância criada a partir dessa

imagem, onde a aplicação é executada.

2. Qual é a função de um Deployment no Kubernetes?

O Deployment é responsável por gerenciar os Pods, garantindo que a quantidade de réplicas configurada esteja funcionando. Também permite atualizar aplicações e recriar Pods 

quando necessário.

3. O que aconteceu quando você excluiu um Pod? Por que isso aconteceu?

Quando excluí um Pod, o Kubernetes criou automaticamente outro para substituí-lo. Isso aconteceu porque o Deployment estava configurado para manter três réplicas da

aplicação, garantindo que a quantidade desejada continuasse funcionando.

4. Qual a finalidade de um Service no Kubernetes?

O Service permite a comunicação entre aplicações dentro do cluster Kubernetes. Ele fornece um endereço estável para acessar os Pods, mesmo quando eles são excluídos ou 

recriados.

No exercício, foi criado o Service comunicado-service, do tipo ClusterIP, permitindo acessar a aplicação Nginx pela porta 80.

7. Conclusão
   
Durante essa atividade prática, aprendi os conceitos básicos de computação em nuvem e a diferença entre máquinas virtuais e contêineres. Também aprendi a utilizar o Docker 

para trabalhar com imagens e contêineres e o Kubernetes para criar e gerenciar aplicações.
