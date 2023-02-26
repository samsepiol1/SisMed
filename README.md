# SisMed
Para não sobrecarregar as responsabilidades realizdas pelo CCC (Controle de Centro Cirúrgico) resolvemos subdividir o sistema em três sistemas principais: Cadastro de Materiais, Cadastro de Médicos e Cadastro de Salas. Essas ações seriam realizadas por atores externos e não contemplados nos diagramas desenvolvidos. O CCC teria a mesma permissão desses atores, mas seu foco principal seria no agendamento da cirurgia juntamente com o médico e, seguidamente, paciente. Subdividir o sistema foi uma das melhores opções para um cenário de aplicação no sistema: Caso fosse um único sistema haveria o risco de sobrecarga de informação e de ações para o CCC. A adotação das tecnologias escritas na linguagem javascript foi pensada em um cenário onde as tecnologias poderiam ser integradas em outros dispositivos de IOT e, também, aplicar os conhecimentos adquiridos na disiciplina de programação de Sistemas para Internet.

## Tecnologias Utilizadas: Front/Back
<img src = "https://clinquant-sfogliatella-68dd08.netlify.app/imgs/tecs.jpg">
<br>
<img src = "https://clinquant-sfogliatella-68dd08.netlify.app/imgs/tecs1.jpg">

## Configurações dos Módulos
O sistema é puramente construido com a utilização de frameworks Javascript e cada módulo possui um framework chefe que por sua vez tem suas dependências gerenciadas pelo NPM. Por padrão, o NPM é instalado junto como o Node.js. Para verificar se tanto o Node.js quanto o NPM estão instalados basta utilizar o seguinte comando: npm --version e node --version. Uma vez feita a instalação do ambiente de desenvolvimento do NodeJs e do gerenciador de pacotes NPM um módulo de extrema importância para o funcionamento do programa é o Express que irá permitir com que as diversas partes da aplicação se comuniquem entre si e é o núcleo do nosso backend. Para instalação do express basta digitar o seguinte comando:

```console
$ npm install express
```
ou uma vez que você esteja na pasta do módulo a ser trabalhado

```console
$ npm install express --save
```


