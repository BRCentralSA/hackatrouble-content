# VPC

Para configurar uma VPC (Virtual Private Cloud) para criação dos máquinas virtuais (EC2) e Bancos de Dados (RDS), siga: 

- Baixe o seguinte template para sua máquina: [AQUI](https://github.com/mandalvesq/iac/blob/master/cf/vpc.template)

- Crie uma Stack de CloudFormation: 
    - Entre na console da AWS
    - Pesquise pelo serviço CloudFormation
    - Clique em Create Stack
    - Clique em Upload Template 
    - Faça upload do template que acabamos de salvar
    - Clique em Next
    - Coloque um nome na Stack, pode ser: VPC-Hackatrouble
    - Coloque um environment, pode ser: POC
    - Clique em Next, Next até Create Stack.

