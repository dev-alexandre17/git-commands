<h1> Fundamentos do Git </h1>

<div>
  <table>
    <tr>
      <th> Comandos </td>
      <th> Descrições </th>
    </tr>
    <tr>
      <td> git init </td>
      <td> Incializa um repositório .git no diretório. </td>
    </tr>
    <tr>
      <td> git add </td>
      <td> Adiciona arquivos/diretórios para o estado staged. </td>
    </tr>
    <tr>
      <td> git commit -m "mensagem" </td>
      <td> Salva as alterações dentro de uma mensagem, o próprio commit. </td>
    </tr>
    <tr>
      <td> ls -a </td>
      <td> Verifica se o repositório .git foi inicializado. </td>
    </tr>
    <tr>
      <td> git config --global user.email "e-mail" </td>
      <td> Configurar o e-mail associado ao da conta GitHub. </td>
    </tr>
    <tr>
      <td> git config --global user.name "nome" </td>
      <td> Configurar o nome associado ao da conta GitHub. </td>
    </tr>
    <tr>
      <td> git status </td>
      <td> Verifica o status do repostirório, untracked, modified e afins. </td>
    </tr>
    <tr>
      <td> git config --list </td>
      <td> Configurações do git na máquina, incluíndo e-mail, nome entre outros. </td>
    </tr>
    <tr>
      <td> git config --global unset user.email "e-mail" </td>
      <td> Deleta o e-mail configurado no git. </td>
    </tr>
    <tr>
      <td> git config --global --unset user.name "nome" </td>
      <td> Deleta o nome configurado no git. </td>
    </tr>
    <tr>
      <td> git push origin master </td>
      <td> Enviando as alterações da máquina para o repositório no GitHub, referente a sua branch. </td>
    </tr>
    <tr>
      <td> git remote -v </td>
      <td> Dados de origens do repostirório. </td>
    </tr>
    <tr>
      <td> git clone </td>
      <td> Clonando repositório do GitHub na máquina. </td>
    </tr>
  </table>
</div>

<h2> Trabalhando com Branches </h2>

<div>
  <table>
    <tr>
      <th> Comandos </th>
      <th> Descrições </th>
    </tr>
    <tr>
      <td> git branch </td>
      <td> Visualizar em qual branch você está localizado. </td>
    </tr>
    <tr>
      <td> git checkout -b branch </td>
      <td> Cria uma nova branch e move-se para ela simultaneamente. </td>
    </tr>
    <tr>
      <td> git checkout branch </td>
      <td> Troca de branch. </td>
    </tr>
    <tr>
      <td> git merge </td>
      <td> União das modificações com outra branch paralela. </td>
    </tr>
  </table>
</div>
