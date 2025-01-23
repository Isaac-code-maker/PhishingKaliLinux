# Projeto de Phishing para Captura de Senhas do Facebook

## Descrição

Este projeto tem como objetivo demonstrar a criação de um ataque de phishing para captura de senhas do Facebook utilizando ferramentas do Kali Linux. Inicialmente, o ataque foi configurado com a ferramenta `setoolkit`, mas, devido a dificuldades encontradas durante a execução, a ferramenta `zphisher` foi adotada como alternativa para facilitar a realização do ataque e garantir o sucesso do projeto.

## Ferramentas Utilizadas

- **Kali Linux**: Sistema operacional utilizado como base.
- **zphisher**: Ferramenta de phishing utilizada para capturar credenciais de login.
- **setoolkit**: Ferramenta originalmente escolhida para o ataque, mas substituída devido a problemas técnicos.

## Justificativa para a Mudança de Ferramenta

Embora o `setoolkit` seja uma ferramenta poderosa para ataques de engenharia social, encontrei dificuldades técnicas para configurar corretamente o ataque e obter as informações desejadas. A mudança para o `zphisher` foi feita devido à sua interface mais intuitiva e fácil configuração, além de uma maior taxa de sucesso na execução do ataque de phishing, conforme os resultados obtidos durante os testes.

## Como Executar o Projeto

1. Clone o repositório:
   ```bash
   git clone https://github.com/seu-usuario/seu-repositorio.git
Navegue até o diretório do projeto:

bash
Copiar
Editar
cd nome-do-diretorio
Instale o zphisher:

bash
Copiar
Editar
git clone https://github.com/htr-tech/zphisher
cd zphisher
bash zphisher.sh
Escolha o vetor de ataque para o Facebook e siga as instruções para configurar o phishing.

Como Funciona
Configuração do Ataque: O zphisher automatiza o processo de criação de uma página de phishing, com a opção de clonar sites como o Facebook.
Captura de Credenciais: Quando a vítima tenta acessar o site falso, as credenciais de login são capturadas e registradas.
Licença
Este projeto está licenciado sob a Licença MIT, sinta-se à vontade para usá-lo de acordo com os termos.
