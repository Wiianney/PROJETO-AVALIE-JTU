<h1 align = "center"> PROJETO AVALIE JTU </h1>
<h1 align = "cneter" >OBJETIVO DO PROJETO</h1>

<p>Temos como objetivo desenvolver um aplicativo mobile em que a comunidade de Jacareí de faz uso do transporte público, possa avaliar as situações dos ôibus da empresa JTU, podendo avaliar, linha, motorista e fazer reclamações ou denúncias.</p>
<h1 align="center"> PROJETO AVALIE </h1>
<p align="center">Um trabalho para a disciplina de Desenvolvimento de Dispositivos Móveis - 4º Ano Informática do IFSP Câmpus Jacareí</p>
<br>
<p align="center">

<img loading="cozy" src="http://img.shields.io/static/v1?label=STATUS&message=%20CARREGANDO&-8a2BE2color=BLUE&style=for-the-badge"/>

<h1>👨‍🏫 Professor responsável </h1> 

Carlos Eduardo Duque Polito 

<h1>🎯 Objetivo do aplicação</h1> 
Temos como objetivo desenvolver um aplicativo mobile em que a comunidade de Jacareí de faz uso do transporte público, possa avaliar as situações dos ôibus da empresa JTU, podendo avaliar, linha, motorista e fazer reclamações ou denúncias.
<br>

<h1>👥 Público-alvo</h2>
Nosso público alvo é toda a população que usa o transporte público da cidade de Jacareí.

<h1><span style='font-size:100px;'>&#128311;</span>Funcionalidades do Projeto:</h2>

- `Registro de Usuários`: Um sistema de cadastro de usuários onde seus dados serão enviados a um banco de dados.
- `Autenticação de Conta`: Uma vez já cadastrado e tendo seus dados autenticados, o usuário poderá realizar seu login no aplicativo. 
- `Avaliação do Transporte Público`: O usuário terá a possibilidade de fazer avaliações sobre o transporte público oferecido, por meio de preenchimmento de formulários.
- `Visualização de Avaliações de Outros Usuários`: O usuário poderá visualizar as avaliações de outros usuários.
- `Informações Sobre o Perfil`: Nessas abas o usuário poderá visualizar/alterar informações sobre seu perfil e visualizar suas avaliações anteriores
<h1><span style='font-size:100px;'>&#128203;</span> Requisitos não funcionais para o site</h1> 
Para o funcionamento, a aplicação deve conter:

- `Responsividade`: Capacidade de responder a algo de forma rápida e adequada, adaptando-se às circunstâncias.
- `Acessibilidade`: Capacidade de ser acessível a todo o público alvo, que incluí pessoas sem familiaridade com tecnologia e pessoas idosas.
- `Desempenho`: O APP deverá funcionar com o melhor desempenho possível.
- `Segurança`: O APP deve garantir que os dados do usuário estejam em segurança.

<h1><span style='font-size:100px;'>&#128203;</span>Matrizes de Requisitos Gerais</h1>

<h2>Matriz de Requisitos Gerais</h2>

<img src="https://github.com/user-attachments/assets/309a10a7-3bc2-421c-aef0-bc90c1c63c7f" width = 1000>

<h2>Matriz de Requisitos Funcionais</h2>

<img src="https://github.com/user-attachments/assets/8635abbf-4613-4142-a51a-b4eb92c5fd1d" width = 1000>


<h1>📊 Relacionamento de Dados </h1> 
<img src="https://github.com/user-attachments/assets/ee8a10bd-e70a-46fb-821f-281ceb881b3d" width=1000> 

<h1>📖 Dicionário de Dados</h1> 

Esse projeto contará com as seguintes Entidades e atributos

<h2>Entidade Usuário</h2>
 Essa entidade é necessária para cadastrar o cliente e seus respectivos dados.
 <br><br>
 
- `nome`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. Ele armazena o nome que o usuário cadastrará.
- `e-mail`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar o e-mail que o usuário cadastrou.
- `senha`: É um atributo do tipo VARCHAR com um tamanho de 45 caracteres. É o responsável por armazenar a senha que o usuário cadastrou.

<h2>Entidade Avaliação</h2>
 Essa entidade é necessária para cadastrar a avaliação que o usuário deseja fazer. 
 <br><br>
 
- `id_avaliacao`: É um atributo do tipo INT responsável por criar uma identidade única para cada avaliação feita pelos usuários.
- `linha`: É um atributo do tipo VARCHAR com um tamanho de 2 caracteres. É o responsável por armazenar que linha será avaliada.
- `horário`É um atributo do tipo DATETIME. Para armazenar o dia e a hora pelo qual a avaliação será realizada.

<h2>Entidade Antes do Embarque</h2>
 Essa entidade é necessária para armazenar os dados da avaliação. 
 <br><br>
 
- `id_antes_do_embarque`: É um atributo do tipo INT responsável por criar uma especificação única para cada avaliação criada pelos usuários.
- `ponto`: É um atributo do tipo BINARY. É o responsável por armazenar se o ponto de ônibus será avaliado ou não.
- `atraso/adiantamento`: É um atributo do tipo BINARY. É o responsável por armazenar se o horário de cheagada do ônibus será avaliado ou não.
- `nota`: É um atributo do tipo DECIMAL. É o responsável por armazenar a nota da avaliação.
- `descrição`: É um atributodo tipo VARCHAR com um tamanho de 500 caracteres. É o responsável por armazenar a descrição da avaliação que o usuário ira fazer.

<h2>Entidade Condição do ônibus</h2>
 Essa entidade é necessária para armazenar os dados da avaliação. 
 <br><br>

- `id_condição_do_ônibus`: É um atributo do tipo INT responsável por criar uma especificação única para cada avaliação criada pelos usuários.
- `assentos`: É um atributo do tipo BINARY. É o responsável por armazenar se os assentos do ônibus seram avaliados ou não.
- `janelas`: É um atributo do tipo BINARY. É o responsável por armazenar se as janelas do ônibus seram avaliadas ou não.
- `botões`: É um atributo do tipo BINARY. É o responsável por armazenar se os botões do ônibus seram avaliados ou não.
- `catracas`: É um atributo do tipo BINARY. É o responsável por armazenar se as catracas do ônibus seram avaliadas ou não.
- `nota`: É um atributo do tipo DECIMAL. É o responsável por armazenar a nota da avaliação.
- `descrição`: É um atributodo tipo VARCHAR com um tamanho de 500 caracteres. É o responsável por armazenar a descrição da avaliação que o usuário ira fazer.

<h2>Entidade Condição do transporte</h2>
 Essa entidade é necessária para armazenar os dados da avaliação. 
 <br><br>

- `id_condição_do_transporte`: É um atributo do tipo INT responsável por criar uma especificação única para cada avaliação criada pelos usuários.
- `nota`: É um atributo do tipo DECIMAL. É o responsável por armazenar a nota da avaliação.
- `lotação`: É um atributo do tipo BINARY. É o responsável por armazenar se a lotação do ônibus será avaliada ou não.
- `nota_motorista`: É um atributo do tipo DECIMAL. É o responsável por armazenar a nota da avaliação referente ao motorista.
- `nota_cobrador`: É um atributo do tipo DECIMAL. É o responsável por armazenar a nota da avaliação referente ao cobrador.
- `descrição`: É um atributodo tipo VARCHAR com um tamanho de 500 caracteres. É o responsável por armazenar a descrição da avaliação que o usuário ira fazer.

<h1> <span style='font-size:100px;'>&#128200;</span> Plano de Capacidade</h1>
<p>Nosso sistema deverá ser capaz de armazenar uma grande quantidade de dados dos usuários, considerando que foi desenvolvido para atender um amplo público que utiliza o transporte público de Jacareí. Para isso, esperamos que as ferramentas escolhidas e sua implementação sejam adequadas para atender aos requisitos definidos, garantindo um funcionamento eficiente, livre de erros e com alto desempenho.</p>


<h1><span style='font-size:100px;'>&#128279;</span> Diagramas UML</h1>
<h2>Login/Cadastro</h2>
<img src="https://github.com/user-attachments/assets/7fdaa16e-c597-4709-b3a8-18f361c7affd" width=1000>

<h2>Perfil/Avaliação</h2>
<img src = "https://github.com/user-attachments/assets/cec8f8cc-db47-4cc8-b0de-c2ae7792bfe4" width=1000>

<h1> <span style='font-size:100px;'>&#129490;</span> Usuário </h1>
<img src = "" width=1000>

<h1><span style='font-size:100px;'>&#128281;</span> Backup e Recuperação </h1>
<p> Uma estratégia que combina o armazenamento local e na nuvem para proteger os dados. Ele é uma solução flexível  que pode ser usada por sitemas de todos os portes. O backup híbrido combina a vantagem do acesso rápido aos dados locais com a conveniência de acessá-los remotamente. Isso permite uma recuperação mais rápida em caso de falha no sistema local, ao mesmo tempo em que oferece a flexibilidade de acesso.
</p>


<h1><span style='font-size:100px;'>&#129521;</span> Arquitetura da Aplicação</h1> 
<h2>Frontend, Backend e Banco de Dados</h2>
<img src= "https://github.com/user-attachments/assets/eeea6941-7374-4c3e-8f1d-4675ada62701" width=1000> 

<h1>👥 Usuário</h2>

<p>Diagrama usuário 1</p>

![Image](https://github.com/user-attachments/assets/bc19d29b-b508-46bb-ba41-6048f886511b)

# <span style='font-size:100px;'>&#128101;</span> Desenvolvedores
<h2> Nícolas do Nascimento Ignacio e Maria Wianney de Almeida </h2>
