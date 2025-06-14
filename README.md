# Relatório de Sistema de Controle de Vagas de Estacionamento
Integrantes: Guilherme Alexandre Vilas Boas Melo /
            João Gabriel Cerqueira Marques /
            Pedro Henrique de Barros Góes / 
            Mateus Ferreira de Sá Macedo
            
-------------------Introdução ao projeto-------------------------------------------------------------------------------------------------------------

Nosso trabalho propõe a automação do controle de vagas em garagens urbanas. Atualmente, é comum que um funcionário precise verificar presencialmente a disponibilidade de vagas, o que é um processo ineficiente, sujeito a erros e que consome tempo. Nosso projeto não dependerá de funcionários, o sistema dependerá exclusivamente do cliente.

Para solucionar esse problema, desenvolvemos um sistema automatizado utilizando sensores e Arduino, capaz de monitorar em tempo real a ocupação das vagas. Com isso, eliminamos a necessidade de verificação manual, trazendo mais agilidade, precisão e praticidade tanto para os funcionários quanto para os usuários das garagens.
O funcionamento do nosso sistema baseia-se na utilização de sensores de proximidade estrategicamente posicionados em cada vaga da garagem. Esses sensores são responsáveis por detectar a presença ou ausência de um veículo, funcionando como os "olhos" do sistema. Sempre que um carro entra ou sai de uma vaga, o sensor IR capta essa mudança e envia as informações diretamente para o Arduino.

O Arduino processa esses dados em tempo real e atualiza o status de cada vaga, indicando se está livre ou ocupada. Essas informações são então exibidas de forma clara em um display, permitindo que o monitoramento seja feito de maneira rápida e eficiente.

Com essa automação, o cliente não precisará mais circular pela garagem para verificar a ocupação das vagas. Isso aumenta a eficiência, reduz o esforço manual e minimiza erros, além de contribuir para um melhor fluxo de entrada e saída de veículos.

Nosso sistema é uma solução prática e tecnológica para modernizar o controle de vagas em garagens urbanas, tornando o processo mais inteligente, seguro e eficiente.

-------------------Escolha do microcontrolador Arduino------------------------------------------------------------------------------------------------

O Arduino, mesmo em versões mais simples como o Arduino Uno, possui poder de processamento suficiente para executar a leitura simultânea de múltiplos sensores, processar essas informações e atualizar displays em tempo real. Como o nosso projeto não demanda cálculos complexos ou alta velocidade de processamento, o Arduino atende plenamente aos requisitos.

Ele oferece facilidade de expansão através de shields e módulos adicionais, permitindo a futura adição de funcionalidades como conectividade Wi-Fi, integração com aplicativos móveis ou sistemas de pagamento eletrônico e isso tudo sem a necessidade de trocar a plataforma base.

O arduino é totalmente compatível com todos os sensores que nosso projeto precisa e com muitos outros no mercado; é uma das melhores plataformas para possíveis upgrades e uso de sensores atualmente.

Ele se destaca pelo baixo custo, o que o torna uma solução viável economicamente, especialmente para implementação em grande escala, como seria o caso de uma garagem com várias vagas.

O Arduino possui uma vasta comunidade, bibliotecas prontas e uma IDE intuitiva, o que torna o desenvolvimento mais acessível, especialmente para projetos acadêmicos e protótipos. Sua simplicidade permite a rápida implementação e teste das funcionalidades desejadas.

-------------------Escolha dos sensores---------------------------------------------------------------------------------------------------------------

Basicamente nosso projeto usará apenas sensores de proximidade, quatro no total, um para cada vaga.

Com esses sensores, o sistema consegue identificar com precisão quais vagas estão livres ou ocupadas, sem risco de confusão entre posições.

Fácil integração com o Arduino.

Baixo custo e disponibilidade; esses sensores são amplamente disponíveis no mercado a um preço barato.




