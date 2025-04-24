# formemail

- CRIANDO O FORM<br>
   Usei HMTL e CSS para criar e estilizar a página do formulário. No Html as principais tags utilizadas foram: form, input e label.

- TORNANDO O FORM FUNCIONAL<br>
  Para tornar o form funcional foi necessário a utilização de uma API chamada de "formsubmit.co".
  Sua utilização ocorre da seguinte forma dentro da tag form: action= "https://formsubmit.co/email@gmail.com" method="POST".
  <br> O email no comando é para onde o form deve ser enviado e o method deve ser, obrigatoriamente, POST.

- ESTILIZANDO MENSAGEM DE AGRADECIMENTO<br>
  Após o envio do formulário por parte do usuário a API exibe uma mensagem padrão de agradecimento, para estilizar essa mensagem foi necessário usar o seguinte comando dentro da tag input.
  type="hidden" name="_next" value="http://127.0.0.1:5500/formemail/form3.html".<br>
  Ele encaminha para o form3.html, que contém a página estilizada.

- COMANDOS GIT(BASH)
  Criei o repositório pelo github.<br>
  Fui até a pasta onde todos os arquivos do projeto estavam e abri o gitBASH lá.<br><br>
  EXECUTEI OS SEGUINTES COMANDOS:<br><
  git init <br>
  echo "# formemail" >> README.md<br>
  git config --global user.name<br>
  git config --global user.email<br>
  git branch -M main <br>
  git remote add origin https://linkdorepositorio.git<br>
  git add .<br>
  git commit -m "subindo arquivos"<br>
  git push -u origin main<br>
