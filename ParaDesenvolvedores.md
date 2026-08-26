# Atividade_AW_SIGEPP

## Commits

Para facilitar desenvolvimento, use mensagens descritivas nos commits, no inicio da mensagem use commits semanticos segundo o quadro abaixo:

<table>
  <thead>
    <tr>
      <th>Tipo do commit</th>
      <th>Codigo</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Bugfix</td>
      <td>🐛 <code>:bug: fix:</code></td>
    </tr>
    <tr>
      <td>Documentação</td>
      <td>📚 <code>:books: docs:</code></td>
    </tr>
    <tr>
      <td>Em progresso</td>
      <td>🚧 <code>:construction:</code></td>
    </tr>
    <tr>
      <td>Estilização de interface</td>
      <td>💄 <code>:lipstick: feat</code></td>
    </tr>
    <tr>
      <td>Mover/Renomear</td>
      <td>🚚 <code>:truck: chore:</code></td>
    </tr>
    <tr>
      <td>Novo recurso</td>
      <td>✨ <code>:sparkles: feat:</code></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td>⚡ <code>:zap: perf:</code></td>
    </tr>
    <tr>
        <td>Refatoração</td>
        <td>♻️ <code>:recycle: refactor:</code></td>
    </tr>
    <tr>
      <td>Removendo um arquivo</td>
      <td>🔥 <code>:fire:</code></td>
    </tr>
    <tr>
      <td>Revertendo mudanças</td>
      <td>💥 <code>:boom: fix:</code></td>
    </tr>
    <tr>
      <td>Testes</td>
      <td>🧪 <code>:test_tube: test:</code></td>
    </tr>
    <tr>
      <td>Tratamento de erros (exceptions)</td>
      <td>🥅 <code>:goal_net: fix:</code></td>
    </tr>
    <tr>
      <td>Mundança no Makefile e arquvos de build</td>
      <td>🔨 <code>:hammer: build:</code></td>
    </tr>
    <tr>
      <td>Dados</td>
      <td>🗃️ <code>:card_file_box: raw:</code></td>
    </tr>
  </tbody>
</table>

As palavras chaves são as seguintes:
- `feat`- Commits do tipo feat indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).

- `fix` - Commits do tipo fix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).

- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).

- `test` - Commits do tipo test são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)

- `build` - Commits do tipo build são utilizados quando são realizadas modificações em **arquivos de build e dependências**.

- `perf` - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.

- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).

- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.

- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)

- `raw` - Commits to tipo raw indicam mudanças relacionadas a arquivos de configurações, dados, features, parametros.

Exemplos:
- <code>git commit -m ":books: docs: Atualização do README"</code>
- <code>git commit -m ":construction: trabalhando na classe de interpretador"</code>
- <code>git commit -m ":sparkles: feat: interpretador terminado"</code>

## Como comittar

Inicialmente, crie uma branch pessoal, que vai conter o seu desenvolvimento em cada sprint. Esse projeto conta com 2 branches 'oficiais': a <code>main</code>, onde estará o produto final, as versões já testadas e mais atualizadas do nosso sistema; e a <code>dev</code>, que será sempre a primeira branch que receberá os commits. NUNCA DÊ COMMIT DIRETAMENTE NA <code>main</code>!

Assim que acabar de concluir a implementação que devia (sua branch pessoal), após os testes, abra um 'Pull Request' (PR) para a branch <code>dev</code>. Outro desenvolvedor vai avaliar suas implementações e, se corretas, aceitará seu PR. Após um sprint, se o sistema estiver funcional, o grupo pode decidir por atualizar os dados da branch <code>main</code>.

Desse modo, ficamos com os seguintes passos:

<ol>
  <li>Crie uma branch pessoal</li>
  <li>Faça suas implementações</li>
  <li>Faça commit para a sua branch pessoal</li>
  <li>Teste</li>
  <li>Abra um Pull Request para a branch <code>dev</code></li>
  <li>Aguarde revisão de outro desenvolvedor</li>
  <li>Pronto! Sua implementação foi aprovada e está na branch <code>dev</code></li>
</ol>

## Nomenclatura dos casos de uso

O projeto está dividido em dois times: o time A, que vai lidar, principalmente, com a gestão de ofertas de Extensão e Pesquisa; e o time B, que vai lidar com a gestão de ofertas de Estágio.

Desse modo, os casos de uso foram nomeados conforme o time. Ou seja, o Caso de Uso número x do time A deverá ser nomeado como <b>CDU xA</b> e o Caso de Uso y do time B deverá ser nomeado como <b>CDU yB</b>.

Os casos de uso com numeração de 1 a 5 serão implementados no primeiro sprint, enquanto aqueles com numeração de 6 a 10 serão implementados no segundo sprint.