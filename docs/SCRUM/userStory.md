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
            <th>Feature</th>
            <th>ID</th>
            <th>Descrição | Critérios de Aceitação</th>
        </tr>
    <thead>
    <tbody>
        <tr>
            <td rowspan="3" class="column">Acesso à aplicação</td>
            <td rowspan="1" class="column">Cadastro</td>
            <td class="column">US01</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                    Como usuário, eu quero realizar o meu cadastro no app, para que eu possa usufruir todas as funcionalidades do app.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve:
                <ul class="ul">
                    <li>Apresentar um formulário de cadastro;</li>
                    <li>Enviar (por sms) um código de validação.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td rowspan="2" class="column">Login</td>      
            <td class="column">US02</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                    Como usuário, eu quero fazer login, para que eu possa usufruir todas as funcionalidades do app.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar formulário de login;</li>
                    <li>Apresentar opção de visualizar senha;</li>
                    <li>Apresentar opção de recuperar senha;</li>
                    <li>Apresentar opção de realizar cadastro;</li>
                    <li>Apresentar opção de "continuar conectado".</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="column">US03</td>
            <td>
                 <strong> Descrição </strong><br/>
                <span>
                    Como usuário, eu quero recuperar minha senha, para que eu possa usufruir todas as funcionalidades do app novamente.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Solicitar o cpf do usuário;</li>
                    <li>Solicitar a forma de recuperação(código de recuperação que pode ser envidado para o email ou telefone cadastrado).</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td rowspan="4" class="column">Conta pessoal</td>
            <td rowspan="1" class="column">Logout</td>
            <td class="column">US04</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                    Como usuário, eu quero fazer logout, para que eu possa utilizar outra conta e ter mais segurança e privacidade.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Possuir opção para sair da conta.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td rowspan="3" class="column">Manter conta</td>
            <td class="column">US05</td>
            <td>
              <strong> Descrição </strong><br/>
                <span>
                    Como usuário, eu quero cancelar a minha conta quando não precisar mais do app.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Alertar o usuário que o cancelamento é irreversível;</li>
                    <li>Botão de cancelar conta.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="column">US06</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero consultar os meus dados pessoais, para que eu possa verificar se eles estão corretos e atualizados.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar os dados pessoais de forma que o usuário consiga editá-los.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="column">US07</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                    Como usuário, eu quero alterar os meus dados pessoais, para que eu possa atualizar dados desatualizados.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar os dados pessoais de forma que o usuário consiga editá-los.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td rowspan="3" class="column">Pré-atendimento</td>
            <td rowspan="3" class="column">Manter pré-postagens</td>
            <td class="column">US08</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                    Como usuário, eu quero consultar as minhas pré-postagens, para que eu possa finalizar postagens futuramente.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar uma lista com as pré-postagens cadastradas;</li>
                    <li>Opção de busca de pré-postagens;</li>
                    <li>Opção de atualizar lista de pré-postagens;</li>
                    <li>Opção de adicionar pré-postagem;</li>
                    <li>Opção para excluir pré-postagem.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="column">US09</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                    Como usuário, eu quero cadastrar pré-postagens, para que eu possa agilizar o meu atendimento na agência.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Solicitar o endereço do destinatário e do remetente;</li>
                    <li>Solicitar a especificação do objeto(formato, dimensões e peso);</li>
                    <li>Solicitar quais serviços o usuário deseja incluir;</li>
                    <li>Apresentar o resumo da pré-postagem;</li>
                    <li>Apresentar opção de visualizar/imprimir rótulo;</li>
                    <li>Apresentar opção de visualizar/imprimir declaração de conteúdo;</li>
                    <li>Apresentar opção de busca de agências próximas.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="column">US10</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero excluir pré-postagens, para que eu possa visualizar apenas as pré-postagens não finalizadas.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Possuir opção de exclusão de pré-postagens;</li>
                    <li>Solicitar confirmação de exclusão.</li>
                </ul>
            </td>
        </tr>  
        <tr>
            <td rowspan="5" class="column">Acompanhar objetos</td>
            <td rowspan="4" class="column">Rastreamento de objetos</td>
            <td class="column">US11</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                    Como usuário, eu quero rastrear os meus objetos, para que eu possa saber o status de entrega dos meus objetos.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>
                        Possuir as seguintes opções para o usuário rastrear objetos: número de rastreamento; cpf/cnpj do usuário; código de barras.
                    </li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="column">US12</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero salvar objetos, para que eu possa consultar os meus objetos com mais facilidade posteriormente.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar opção de salvar objeto;</li>
                    <li>Solicitar o número de rastreio do objeto;</li>
                    <li>Solicitar descrição para o objeto;</li>
                    <li>Apresentar opção para habilitar/desabilitar notificações de entrega.</li>
                </ul>
            </td>
        </tr> 
        <tr>
            <td class="column">US13</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero consultar os objetos entregues, para que eu possa saber todo histórico dos objetos entregues.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar opção de consulta de objetos entregues;</li>
                    <li>Apresentar opção de visualizar histórico de entrega de um objeto.</li>
                </ul>
            </td>
        </tr> 
        <tr>
            <td class="column">US14</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero consultar os objetos em trânsito, para que eu possa acompanhar as entregas.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar opção de consulta de objetos em trânsito;</li>
                    <li>Apresentar opção de visualizar histórico de entrega de um objeto.</li>
                </ul>
            </td>
        </tr> 
        <tr>
            <td rowspan="1" class="column">Notificações de entrega</td>
            <td class="column">US15</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero ativar as notificações de entrega dos meus objetos, para que eu possa receber notificações sempre que ocorrer uma mudança de status de entrega dos meus objetos.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar opção de habilitar/desabilitar notificações de um objeto a ser salvo.</li>
                </ul>
            </td>
        </tr> 
        <tr>
            <td rowspan="1" class="column">Simulação</td>
            <td rowspan="1" class="column">Simular preços e prazos</td>
            <td class="column">US16</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero simular postagens, para que eu possa saber previamente os serviços disponíveis e os seus respectivos preços e prazos.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Solicitar o cep de origem e destino;</li>
                    <li>Solicitar a especificação do objeto(formato, dimensões e peso);</li>
                    <li>Apresentar os serviços disponíveis e os seus respectivos preços e prazos.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td rowspan="4" class="column">Meus endereços</td>
            <td rowspan="4" class="column">Manter endereços</td>
            <td class="column">US17</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero consultar endereços cadastrados, para que eu possa alterá-los e excluí-los posteriormente.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar lista de endereços cadastrados;</li>
                    <li>Apresentar opção de cadastro de endereços;</li>
                    <li>Apresentar opção de visualizar os dados de um endereço de forma que o usuário consiga editá-los;</li>
                    <li>Apresentar opção de exclusão de endereço.</li>
                </ul>
            </td>
        </tr> 
        <tr>
            <td class="column">US18</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero cadastrar endereços, para que eu possa reutilizá-los durante o cadastro de pré-postagens.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Solicitar os dados do destinatário/remetente;</li>
                    <li>Solicitar os dados de endereço.</li>
                </ul>
            </td>
        </tr> 
        <tr>
            <td class="column">US19</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero alterar endereços cadastrados, para que eu possa manter os endereços sempre atualizados.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar os dados do endereço de forma que o usuário consiga editá-los.</li>
                </ul>
            </td>
        </tr> 
        <tr>
            <td class="column">US20</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero excluir endereços cadastrados, para que eu possa utilizar apenas os endereços que preciso.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar opção de exclusão de endereços;</li>
                    <li> Solicitar confirmação de exclusão.</li> 
                </ul>
            </td>
        </tr>
        <tr>
            <td rowspan="5" class="column">Agências</td>
            <td rowspan="2" class="column">Encontrar agências próximas</td>
            <td class="column">US21</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero buscar agências, para que eu possa encontrar agências próximas de uma localização.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar opção de buscar agências próximas a partir da localização gps ou de um endereço;</li>
                    <li>Apresentar opção de raio de distância(máximo 10km);</li>
                    <li>Apresentar no mapa, por meio de marcadores, as agências próximas.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="column">US22</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero visualizar as informações de agências, para que eu possa saber o horário de atendimento ou meios de contato das agências.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Possibilitar que o usuário consiga clicar sobre o marcador;</li>
                    <li>Após o clique, apresentar as informações da agência clicada;</li>
                    <li>Apresentar opção de adicionar/remover a agência dos favoritos.</li>
                </ul>
            </td>
        </tr> 
        <tr>
            <td rowspan="3" class="column">Manter agências favoritas</td>
            <td class="column">US23</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero consultar as agências favoritas, para que eu possa acessar rapidamente as informações das agências.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>Apresentar lista de agências favoritas;</li>
                    <li>Permitir que o usuário visualize as informações de uma agência selecionada.</li>
                </ul>
            </td>
        </tr> 
        <tr>
            <td class="column">US24</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero adicionar agências aos favoritos, para que eu possa consultar rapidamente as informações das agências.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>A adição de agências dos favoritos deve ser feita durante busca de agências.</li>
                </ul>
            </td>
        </tr>
        <tr>
            <td class="column">US25</td>
            <td>
                <strong> Descrição </strong><br/>
                <span>
                   Como usuário, eu quero remover agências dos meus favoritos, para que eu possa consultar apenas as agências que preciso.
                </span>
                <hr class="hr"/>
                <strong> Critérios de Aceitação</strong><br/>
                A aplicação deve: 
                <ul class="ul">
                    <li>A remoção de dos favoritos deve ser feita durante a consulta ou a busca de agências.</li>
                </ul>
            </td>
        </tr>                                                                                   
    </tbody>
</table>
