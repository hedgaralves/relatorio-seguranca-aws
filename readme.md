## RELATÓRIO DE IMPLEMENTAÇÃO DE MEDIDAS DE SEGURANÇA

Data: 24/07/2023
Empresa: Abstergo Industries
Responsável: Hedgar Alves da Silva

# Introdução

Este relatório apresenta o processo de implementação de ferramentas na empresa Abstergo Industries, realizado por Hedgar Alves da Silva. O objetivo do projeto foi elencar 3 medidas de segurança em conjunto dos serviços da AWS, com a finalidade de realizar aumentar a segurança na empresa.

# Descrição do Projeto

O projeto de implementação de ferramentas foi dividido em 3 medidas de segurança. A seguir, serão descritas as etapas da implementação:

Medida 1: - Gerenciamento de Acesso e Identidade (IAM - Identity and Access Management)

Descrição do caso: O Gerenciamento de Acesso e Identidade é uma medida essencial para garantir que apenas as pessoas autorizadas tenham acesso aos recursos e serviços da AWS.

Uso: Ao implementar o IAM, a empresa pode criar e gerenciar identidades individuais para cada usuário, permitindo a definição precisa de permissões para acesso aos recursos. É possível conceder apenas as permissões necessárias para realizar suas tarefas, reduzindo os riscos de acesso não autorizado. O IAM também permite o uso de autenticação de fator duplo, aumentando ainda mais a segurança ao exigir um segundo método de autenticação além da senha para o acesso às contas.

----

Medida 2: - AWS Web Application Firewall (WAF)

Descrição do caso: O AWS WAF é uma solução de firewall que ajuda a proteger as aplicações web contra ataques cibernéticos e tentativas de exploração de vulnerabilidades.

Uso: Ao utilizar o AWS WAF, a empresa pode configurar regras personalizadas para filtrar e bloquear o tráfego mal-intencionado que tenta atingir as aplicações hospedadas na AWS. A ferramenta oferece proteção contra ataques comuns, como injeção de SQL, cross-site scripting (XSS) e ataques de força bruta. Dessa forma, a segurança das aplicações web é reforçada, mitigando riscos de violações de dados e indisponibilidade dos serviços.

----

Medida 3: - Amazon Virtual Private Cloud (VPC) com VPN (Virtual Private Network)

Descrição do caso: O Amazon VPC é um serviço que permite criar uma rede isolada e segura na AWS para executar recursos e serviços.

Uso: Ao configurar o Amazon VPC com VPN, a empresa pode criar uma conexão segura e criptografada entre sua infraestrutura local e a nuvem da AWS. Isso permite que os dados sejam transferidos de forma segura entre os dois ambientes, garantindo a integridade das informações durante o processo de migração e após a implantação na nuvem. Essa conexão também possibilita uma extensão da rede local para a nuvem, permitindo o acesso seguro aos recursos na AWS como se estivessem na mesma rede local.

Ao adotar essas três principais medidas de segurança - Gerenciamento de Acesso e Identidade (IAM), AWS Web Application Firewall (WAF) e Amazon Virtual Private Cloud (VPC) com VPN -, a empresa pode aumentar significativamente a segurança de seus recursos na nuvem AWS. Essas soluções ajudam a proteger as aplicações e dados contra ameaças cibernéticas, bem como a garantir o acesso controlado aos recursos, minimizando os riscos de violações de segurança e garantindo uma operação segura e confiável na nuvem.

# Conclusão

A implementação das três principais medidas de segurança durante o processo de migração para a AWS representou um passo crucial para a empresa Abstergo Industries em sua busca pela proteção dos recursos na nuvem e garantia da conformidade com as melhores práticas de segurança. Ao adotar o Gerenciamento de Acesso e Identidade (IAM), a empresa conseguiu estabelecer um controle granular sobre as permissões de acesso, mitigando riscos de acessos não autorizados e fortalecendo a segurança das contas dos usuários.

Além disso, a utilização do AWS Web Application Firewall (WAF) ofereceu uma camada adicional de proteção para as aplicações web da empresa, protegendo-as contra ataques cibernéticos comuns e tentativas de exploração de vulnerabilidades. Isso garantiu maior confiabilidade e integridade dos serviços oferecidos pela Abstergo Industries, minimizando o risco de exposição de dados sensíveis e evitando possíveis períodos de indisponibilidade.

A integração do Amazon Virtual Private Cloud (VPC) com VPN estabeleceu uma conexão segura e criptografada entre a infraestrutura local e a nuvem AWS, permitindo que a empresa transferisse dados sensíveis de maneira segura durante todo o processo de migração e operação contínua na nuvem. Essa abordagem demonstrou o comprometimento da Abstergo Industries em garantir que a privacidade e a confidencialidade de suas informações fossem preservadas, estabelecendo uma infraestrutura de rede altamente segura e confiável.

Com a adoção dessas medidas de segurança, a empresa está mais bem preparada para enfrentar os desafios em um ambiente cibernético cada vez mais complexo. A contínua busca por inovações tecnológicas e a adoção de melhores práticas de segurança são fundamentais para manter a segurança dos recursos na nuvem, bem como para garantir a conformidade com regulamentações e proteger a reputação da Abstergo Industries.

Links para a documentação das medidas de segurança:

AWS Identity and Access Management (IAM):
Documentação: https://aws.amazon.com/iam/
AWS Web Application Firewall (WAF):
Documentação: https://aws.amazon.com/waf/
Amazon Virtual Private Cloud (VPC):
Documentação: https://aws.amazon.com/vpc/

Assinatura do Responsável pelo Projeto: Hedgar Alves da Silva
