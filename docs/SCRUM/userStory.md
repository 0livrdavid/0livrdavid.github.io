# User Story

<hr>

## <b>Introdução</b>

- <b>Tema</b> - Coleção geral de épicos
- <b>Épicos</b> - Quando uma história de usuário é muito grande para ser completada em um único Sprint, é necessário quebrá-la em pedaços menores, conhecidos como "épicos". Esses épicos podem ser divididos em histórias de usuários menores que são estimáveis, priorizáveis e entregues em um único Sprint. Essa abordagem permite que o Time Scrum gerencie melhor o trabalho e se concentre em entregar valor ao cliente, preservando a integridade da história original do usuário.
- <b>Recurso</b> - O objetivo principal de um recurso é alcançar o resultado desejado de um épico. Um único épico pode conter um ou mais recursos, que são compostos por uma ou muitas histórias de usuário, cada uma correspondendo a um requisito funcional. O recurso serve para contextualizar e priorizar essas User Stories para que o Time Scrum possa focar melhor na entrega de valor ao cliente. Ao agrupar histórias de usuário relacionadas em um recurso, a equipe pode gerenciar o trabalho com mais eficiência e garantir que cada incremento do produto atinja o objetivo maior do épico.
- <b>História do Usuário</b> - User Story ou “história de usuário” é uma descrição concisa de uma necessidade do usuário do produto (ou seja, de um “requisito”) sob o ponto de vista desse usuário. A User Story busca descrever essa necessidade de uma forma simples e leve.

<br>

## <b>Legenda</b>

<br>

## <b>Tabela de User Story</b>

<style>
    .column {
        text-align: center !important;
        vertical-align: middle !important; 
        border-right: 1px solid hsla(0,0%,0%,0.07);
    }
    .hr {
        border-bottom: .05rem solid hsla(0,0%,0%,0.07) !important;
        margin: 10px 2px !important;
    }
    .ul {
        margin-top: 3px !important;
    }
</style>

<table>
    <thead>
        <tr>
            <th>Épico</th>
            <th>Funcionalidade</th>
            <th>ID</th>
            <th>Descrição | Critérios de Aceitação</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Cadastro de Usuário</td>
            <td>Criar formulário de cadastro</td>
            <td>FTD001</td>
            <td>Usuário deve ser capaz de inserir nome, e-mail, telefone, endereço e criar senha. Os dados devem ser validados e gravados no banco de dados do sistema.</td>
        </tr>
        <tr>
            <td>Cadastro de Serviço</td>
            <td>Criar formulário de cadastro de serviço</td>
            <td>FTD002</td>
            <td>Usuário deve ser capaz de inserir informações sobre o serviço que deseja oferecer, incluindo descrição, preço, horários disponíveis e localização. Os dados devem ser validados e gravados no banco de dados do sistema.</td>
        </tr>
        <tr>
            <td>Busca de Serviços</td>
            <td>Criar função de busca</td>
            <td>FTD003</td>
            <td>Usuário deve ser capaz de buscar serviços por palavra-chave, localização, preço e horários disponíveis. O sistema deve retornar resultados relevantes e atualizados.</td>
        </tr>
        <tr>
            <td>Solicitação de Serviço</td>
            <td>Criar função de solicitação</td>
            <td>FTD004</td>
            <td>Usuário deve ser capaz de solicitar um serviço especificando o horário e data desejados. O prestador de serviço deve ser notificado da solicitação e ter a opção de aceitar ou rejeitar a solicitação.</td>
        </tr>
        <tr>
            <td>Gerenciamento de Pagamentos</td>
            <td>Criar função de pagamento</td>
            <td>FTD005</td>
            <td>O sistema deve ser capaz de gerenciar pagamentos entre usuários e prestadores de serviços. O sistema deve armazenar informações de pagamento de forma segura e garantir que as transações sejam concluídas com sucesso.</td>
        </tr>
    </tbody>
</table>


<br>

<table>
    <table class="table table-striped table-hover">
    <thead>
        <tr>
            <th>Épico</th>
            <th>Recurso</th>
            <th>ID</th>
            <th>Descrição | Critérios de Aceitação</th>
        </tr>
    </thead><thead>
    </thead><tbody>
        <tr>
            <td rowspan="3" class="column">Acesso ao aplicativo</td>
            <td rowspan="1" class="column">Cadastro</td>
            <td class="column">US01</td>
            <td>
                <strong>Descrição</strong><br>
                <span>
                    Como usuário, quero me registrar no aplicativo para poder aproveitar todas as funcionalidades do aplicativo.
                </span>
                <hr class="hr">
                <strong>Critérios de aceitação</strong><br>
                O aplicativo deve:
                <ul class="ul">
                    <li>Apresentar um formulário de registro;</li>
                    <li>Envie um código de validação (via SMS).</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td rowspan="2" class="column">Login</td>      
            <td class="column">US02</td>
            <td>
                <strong>Descrição</strong><br>
                <span>
                    Como usuário, quero fazer login para poder aproveitar todas as funcionalidades do aplicativo.
                </span>
                <hr class="hr">
                <strong>Critérios de aceitação</strong><br>
                The application must: 
                <ul class="ul">
                    <li>Apresente um formulário de login;</li>
                    <li>Apresente uma opção para ver a senha;</li>
                    <li>Apresente uma opção para recuperar a senha;</li>
                    <li>Apresente uma opção para se registrar;</li>
                    <li>Apresente uma opção para "permanecer conectado".</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="column">US03</td>
            <td>
                <strong>Descrição</strong><br>
                <span>
                    Como usuário, quero recuperar minha senha para que eu possa aproveitar todas as funcionalidades do aplicativo novamente.
                </span>
                <hr class="hr">
                <strong>Critérios de aceitação</strong><br>
                O aplicativo deve: 
                <ul class="ul">
                    <li>Solicite o CPF do usuário;</li>
                    <li>Solicite o método de recuperação (código de recuperação que pode ser enviado para o email ou telefone registrado).</li>
                </ul>
            </td>
        </tr>                                                                             
    </tbody>
</table>


<br>
<br>

<table>
    <thead>
        <tr>
            <th>Épico</th>
            <th>Feature</th>
            <th>ID</th>
            <th>História de Usuário</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="1" class="column">Desenvolver um modelo de site para o InfoWorks</td>
            <td rowspan="1" class="column">Interface do Usuário</td>
            <td class="column">UI01</td>
            <td>A interface do usuário deve ser intuitiva e fácil de navegar, com uma navegação clara e lógica.</td>
        </tr>
        <tr>
            <td rowspan="1" class="column"></td>
            <td rowspan="1" class="column">Design</td>
            <td class="column">DS01</td>
            <td>O design do site deve ser atraente, moderno e consistente com a identidade visual da empresa. </td>
        </tr>
        <tr>
            <td rowspan="1" class="column"></td>
            <td rowspan="1" class="column">Experiência do Usuário</td>
            <td class="column">UX01</td>
            <td>A experiência do usuário deve ser satisfatória e atender a todas as necessidades do usuário, incluindo recursos e funcionalidades necessárias.</td>
        </tr>
    </tbody>
</table>

<br>

<table>
    <thead>
        <tr>
            <th>Épico</th>
            <th>Feature</th>
            <th>ID</th>
            <th>Descrição | Critérios de Aceitação</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="2" class="column">Registro e Login do Usuário</td>
            <td rowspan="1" class="column">Registro</td>
            <td class="column">US04</td>
            <td>
                <strong>Descrição</strong><br>
                <span>Como um usuário, eu quero criar uma conta na plataforma, para que eu possa acessar meus serviços e informações de conta.</span>
                <hr class="hr">
                <strong>Critérios de Aceitação</strong><br>
                A aplicação deve:
                <ul class="ul">
                    <li>Apresentar um formulário de registro;</li>
                    <li>Solicitar o nome completo, endereço de e-mail, senha e confirmação de senha;</li>
                    <li>Validar a entrada do usuário;</li>
                    <li>Enviar um e-mail de confirmação para o endereço de e-mail fornecido pelo usuário.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td rowspan="1" class="column">Login</td>
            <td class="column">US05</td>
            <td>
                <strong>Descrição</strong><br>
                <span>Como um usuário registrado, eu quero fazer login na plataforma, para que eu possa acessar meus serviços e informações de conta.</span>
                <hr class="hr">
                <strong>Critérios de Aceitação</strong><br>
                A aplicação deve:
                <ul class="ul">
                    <li>Apresentar um formulário de login;</li>
                    <li>Solicitar o endereço de e-mail e senha do usuário registrado;</li>
                    <li>Validar a entrada do usuário;</li>
                    <li>Redirecionar o usuário para a página inicial após o login bem-sucedido.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

<br>

<table>
    <thead>
        <tr>
            <th>Épico</th>
            <th>Feature</th>
            <th>ID</th>
            <th>Descrição | Critérios de Aceitação</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="1" class="column">Pesquisa de provedores de serviços</td>
            <td rowspan="1" class="column">Funcionalidade de pesquisa</td>
            <td class="column">US01</td>
            <td>
                <strong>Descrição</strong><br>
                Como usuário, eu quero ser capaz de pesquisar provedores de serviços na plataforma, para que eu possa encontrar os serviços que preciso.<br>
                <strong>Critérios de Aceitação</strong><br>
                A aplicação deve:
                <ul class="ul">
                    <li>Permitir que os usuários pesquisem provedores de serviços com base em critérios como localização, tipo de serviço e disponibilidade;</li>
                    <li>Retornar resultados precisos e relevantes com base na pesquisa do usuário;</li>
                    <li>Exibir os resultados em uma interface de usuário clara e fácil de usar.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

<br>

<table>
  <thead>
    <tr>
      <th>Épico</th>
      <th>Feature</th>
      <th>ID</th>
      <th>Descrição | Critérios de Aceitação</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td rowspan="2">Reservas</td>
      <td>Criação de Reservas</td>
      <td>US04</td>
      <td>
        <strong> Descrição </strong><br>
        <span>
          Como usuário, eu quero poder criar uma reserva para um serviço, para que eu possa agendar e receber o serviço desejado.
        </span>
        <hr class="hr">
        <strong> Critérios de Aceitação</strong><br>
        A aplicação deve: 
        <ul class="ul">
          <li>Permitir que o usuário selecione um provedor de serviços disponível;</li>
          <li>Permitir que o usuário selecione uma data e horário disponíveis para o serviço;</li>
          <li>Solicitar que o usuário confirme sua reserva antes de criar a reserva;</li>
          <li>Notificar o provedor de serviços quando uma nova reserva é criada.</li>
        </ul>
      </td>
    </tr>
    <tr>
      <td>Disponibilidade do provedor de serviços</td>
      <td>US05</td>
      <td>
        <strong> Descrição </strong><br>
        <span>
          Como provedor de serviços, eu quero poder definir minha disponibilidade, para que eu possa receber reservas em horários apropriados e me organizar.
        </span>
        <hr class="hr">
        <strong> Critérios de Aceitação</strong><br>
        A aplicação deve: 
        <ul class="ul">
          <li>Permitir que o provedor de serviços defina sua disponibilidade;</li>
          <li>Permitir que o provedor de serviços altere sua disponibilidade;</li>
          <li>Impedir que o provedor de serviços receba reservas em horários em que ele não está disponível;</li>
          <li>Notificar o provedor de serviços quando uma nova reserva é criada.</li>
        </ul>
      </td>
    </tr>
  </tbody>
</table>

<br>

<table>
    <thead>
        <tr>
            <th>Épico</th>
            <th>Feature</th>
            <th>ID</th>
            <th>Descrição | Critérios de Aceitação</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td rowspan="1" class="column">Sistema de classificação e revisão</td>
            <td rowspan="1" class="column">Classificação e revisão de provedores de serviços</td>
            <td class="column">US04</td>
            <td>
                <strong>Descrição</strong><br>
                <span>
                    Como usuário, eu quero poder classificar e revisar os provedores de serviços após receber seus serviços, para que outros usuários possam tomar decisões informadas ao selecionar provedores de serviços.
                </span>
                <hr class="hr">
                <strong>Critérios de Aceitação</strong><br>
                A aplicação deve permitir que os usuários:
                <ul class="ul">
                    <li>Classifiquem o provedor de serviços usando um sistema de estrelas;</li>
                    <li>Escrevam uma revisão do provedor de serviços (opcional);</li>
                    <li>Visualizem as classificações e revisões dos outros usuários para um provedor de serviços.</li>
                </ul>
            </td>
        </tr>
    </tbody>
</table>

<br>

<table>
  <tr>
    <th>Identificador da História</th>
    <th>Épico</th>
    <th>História de Usuário</th>
    <th>Feature</th>
  </tr>
  <tr>
    <td>HU06</td>
    <td>Gerenciamento de Perfis</td>
    <td>Como provedor de serviços, eu gostaria de poder criar um perfil na plataforma para mostrar meus serviços e informações de contato</td>
    <td>Criação de perfil de provedor de serviço</td>
  </tr>
  <tr>
    <td>HU07</td>
    <td>Gerenciamento de Perfis</td>
    <td>Como provedor de serviços, eu gostaria de poder atualizar e editar meu perfil na plataforma para manter minhas informações atualizadas</td>
    <td>Atualização de perfil de provedor de serviço</td>
  </tr>
  <tr>
    <td>HU08</td>
    <td>Gerenciamento de Disponibilidade</td>
    <td>Como provedor de serviços, eu gostaria de poder definir minha disponibilidade para que os clientes saibam quando estou disponível para trabalhar</td>
    <td>Definição de disponibilidade de provedor de serviço</td>
  </tr>
  <tr>
    <td>HU09</td>
    <td>Gerenciamento de Disponibilidade</td>
    <td>Como provedor de serviços, eu gostaria de poder visualizar minha disponibilidade em um calendário para que possa gerenciar meus compromissos</td>
    <td>Visualização de disponibilidade de provedor de serviço</td>
  </tr>
</table>