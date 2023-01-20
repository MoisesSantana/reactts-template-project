O commit semântico possui os elementos estruturais abaixo (tipos), que informam a intenção do seu commit ao utilizador(a) de seu código.
- `feature`- Commits do tipo feature indicam que seu trecho de código está incluindo um **novo recurso** (se relaciona com o MINOR do versionamento semântico).
- `hotfix` - Commits do tipo hotfix indicam que seu trecho de código commitado está **solucionando um problema** (bug fix), (se relaciona com o PATCH do versionamento semântico).
- `release` - Commits do tipo release indicam que essa ramificação é criada e usada quando os recursos são concluídos e finalizados para uma versão com versão **nova versão do app**.
- `docs` - Commits do tipo docs indicam que houveram **mudanças na documentação**, como por exemplo no Readme do seu repositório. (Não inclui alterações em código).
- `test` - Commits do tipo test são utilizados quando são realizadas **alterações em testes**, seja criando, alterando ou excluindo testes unitários. (Não inclui alterações em código)
- `build` - Commits do tipo build são utilizados quando são realizadas modificações em **arquivos de build e dependências**.
- `perf` - Commits do tipo perf servem para identificar quaisquer alterações de código que estejam relacionadas a **performance**.
- `style` - Commits do tipo style indicam que houveram alterações referentes a **formatações de código**, semicolons, trailing spaces, lint... (Não inclui alterações em código).
- `refactor` - Commits do tipo refactor referem-se a mudanças devido a **refatorações que não alterem sua funcionalidade**, como por exemplo, uma alteração no formato como é processada determinada parte da tela, mas que manteve a mesma funcionalidade, ou melhorias de performance devido a um code review.
- `chore` - Commits do tipo chore indicam **atualizações de tarefas** de build, configurações de administrador, pacotes... como por exemplo adicionar um pacote no gitignore. (Não inclui alterações em código)
- `ci` - Commits do tipo ci indicam mudanças relacionadas a **integração contínua** (*continuous integration*).
## :ballot_box_with_check: Recomendações
- Adicione um título consistente com o título do conteúdo;
- Recomendamos que na primeira linha deve ter no máximo 4 palavras;
- Para descrever com detalhes, usar a descrição do commit;
- Usar um emoji no início da mensagem de commit representando sobre o commit;
- Um link precisa ser adicionado em sua forma mais autêntica, ou seja: sem encurtadores de link e links afiliados;
## :barber: Padrões de emojis
<table>
  <thead>
    <tr>
      <th>Tipo de commit</th>
      <th>Emojis</th>
      <th>Palavra-chave</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>Acessibilidade</td>
      <td>:wheelchair: <code>:wheelchair:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Adicionando um teste</td>
      <td>:white_check_mark: <code>:white_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Adicionando uma dependência</td>
      <td>:heavy_plus_sign: <code>:heavy_plus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Alterações de revisão de código</td>
      <td>:ok_hand: <code>:ok_hand:</code></td>
      <td><code>style</code></td>
    </tr>
    <tr>
      <td>Animações e transições</td>
      <td>:dizzy: <code>:dizzy:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Bugfix</td>
      <td>:bug: <code>:bug:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Comentários</td>
      <td>:bulb: <code>:bulb:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Commit inicial</td>
      <td>:tada: <code>:tada:</code></td>
      <td><code>init</code></td>
    </tr>
    <tr>
      <td>Configuração</td>
      <td>:wrench: <code>:wrench:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Deploy</td>
      <td>:rocket: <code>:rocket:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Documentação</td>
      <td>:books: <code>:books:</code></td>
      <td><code>docs</code></td>
    </tr>
    <tr>
      <td>Em progresso</td>
      <td>:construction: <code>:construction:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Estilização de interface</td>
      <td>:lipstick: <code>:lipstick:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Infraestrutura</td>
      <td>:bricks: <code>:bricks:</code></td>
      <td><code>ci</code></td>
    </tr>
    <tr>
      <td>Lista de ideias (tasks)</td>
      <td>:soon: <code> :soon: </code></td>
      <td></td>
    </tr>
    <tr>
      <td>Mover/Renomear</td>
      <td>:truck: <code>:truck:</code></td>
      <td><code>chore</code></td>
    </tr>
    <tr>
      <td>Novo recurso</td>
      <td>:sparkles: <code>:sparkles:</code></td>
      <td><code>feat</code></td>
    </tr>
    <tr>
      <td>Package.json em JS</td>
      <td>:package: <code>:package:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Performance</td>
      <td>:zap: <code>:zap:</code></td>
      <td><code>perf</code></td>
    </tr>
    <tr>
        <td>Refatoração</td>
        <td>:recycle: <code>:recycle:</code></td>
        <td><code>refactor</code></td>
    </tr>
    <tr>
      <td>Removendo um arquivo</td>
      <td>:fire: <code>:fire:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Removendo uma dependência</td>
      <td>:heavy_minus_sign: <code>:heavy_minus_sign:</code></td>
      <td><code>build</code></td>
    </tr>
    <tr>
      <td>Responsividade</td>
      <td>:iphone: <code>:iphone:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Revertendo mudanças</td>
      <td>:boom: <code>:boom:</code></td>
      <td><code>fix</code></td>
    </tr>
    <tr>
      <td>Segurança</td>
      <td>:lock:️ <code>:lock:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>SEO</td>
      <td>:mag:️ <code>:mag:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tag de versão</td>
      <td>:bookmark: <code>:bookmark:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Teste de aprovação</td>
      <td>:heavy_check_mark: <code>:heavy_check_mark:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Testes</td>
      <td>:test_tube: <code>:test_tube:</code></td>
      <td><code>test</code></td>
    </tr>
    <tr>
      <td>Texto</td>
      <td>:memo: <code>:memo:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tipagem</td>
      <td>:label: <code>:label:</code></td>
      <td></td>
    </tr>
    <tr>
      <td>Tratamento de erros</td>
      <td>:goal_net: <code>:goal_net:</code></td>
      <td></td>
    </tr>
  </tbody>
</table>
## :computer: Exemplos
<table>
  <thead>
    <tr>
      <th>Comando git</th>
      <th>Resultado no GitHub</th>
    </tr>
  </thead>
 <tbody>
    <tr>
      <td>
        <code>git commit -m “:tada: Commit inicial”</code>
      </td>
      <td>:tada: Commit inicial</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:books: docs: Atualizaçao do README”</code>
      </td>
      <td>:books: docs: Atualizaçao do README</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:bug: fix: Loop infinito na linha 50”</code>
      </td>
      <td>:bug: fix: Loop infinito na linha 50</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:sparkles: feat: Pagina de login”</code>
      </td>
      <td>:sparkles: feat: Pagina de login</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:bricks: ci: Modificaçao no Dockerfile”</code>
      </td>
      <td>:bricks: ci: Modificaçao no Dockerfile</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:recycle: refactor: Passando para arrow functions”</code>
      </td>
      <td>:recycle: refactor: Passando para arrow functions</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:zap: perf: Melhoria no tempo de resposta”</code>
      </td>
      <td>:zap: perf: Melhoria no tempo de resposta</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:boom: fix: Revertendo mudanças ineficientes”</code>
      </td>
      <td>:boom: fix: Revertendo mudanças ineficientes</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:lipstick: feat: Estilizaçao CSS do formulario”</code>
      </td>
      <td>:lipstick: feat: Estilizaçao CSS do formulario</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:test_tube: test: Criando novo teste”</code>
      </td>
      <td>:test_tube: test: Criando novo teste</td>
    </tr>
    <tr>
      <td>
        <code>git commit -m “:bulb: docs: Comentários sobre a função LoremIpsum( )“</code>
      </td>
      <td>:bulb: docs: Comentários sobre a função LoremIpsum( )</td>
    </tr>
  </tbody>
</table>