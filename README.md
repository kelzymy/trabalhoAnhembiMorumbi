# trabalhoAnhembiMorumbi
Atividade 1de HTML e CSS. Analise e desenvolvimento de sistema, Anhembi Morumbi DESENVOLVIMENTO DE SOFTWARE PARA WEB 
<!DOCTYPE html>
<html lang="pt-BR">
<head>
  <meta charset="UTF-8">
  <link rel="stylesheet" type="text/css"
  href="stylesheet.css">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">
  <title>HOSPEDAGEM E CRECHE PARA PET </title>
</head>
<body>
  
  <div>
    <div>
      <a href="#">HOSPEDAGEM <span>E BANHO E TOSA </span></a>

      <div>
        <a href="#ANA">ANA  </a>
        <a href="#PET">PET</a>
        <a href="quartos/index.html">SITTER</a>
      </div>
    </div>
  </div>

  <div>
    <div>
      <div>
        <h1>ANA PET SITTER</h1>
        <p>HOSPEDAGEM, CRECHE,BANHO E TOSA PARA SEU PET</p>
      </div>
    </div>

    <div>
      <h2>
        Seja bem-vindo(a)!
      </h2>

      <p>
        Espaço para seu Pet brincar, aos cuidados de profissionais.
      </p>

      <p>
        Temos recreação banho e tosa.
      </p>
    </div>

    <div>
      <a href="#">
        <img src="imagens/imagens banho e tosa/02.png " width="150px" height="150px" alt="Banho e Tosa" title="img01">
        <p>Banho e Tosa</p>
      </a>

       <a href="#">
        <img src="imagens/Recreação/Faisca.png.png" 
        width="150px" height="150px"alt="Recreação" title="Recreação">
        <p>Recreação</p>
      </a>

      <a href="#">
        <img src="imagens/Recreação/03.png" 
        width="150px" height="150px"alt="Disponiveis para adoção" title="Disponiveis para adoção">
        <p>Disponiveis para adoção</p>
      </a>
    </div>

    <div id="rota">
      <h2>
        Rota
      </h2>

      <p>
        Veja como chegar até a hospedagem.
      </p>
    </div>

    <div>
      <iframe src="https://www.google.com/maps/vt/data=YfMRsTAx1-o1KqrTEBKcAnuknx6cOX09P3MOKii8KZHi6gYLGiJa45u55G07qKU3pc90_4pjxF5TPPP2xF8XQtmVO-FmrA9fGORcE3dxfcY2Dokhhj-aPZD1SH0ILmdP2wM0cTTM80LFpovu59Gmr7AFb1PH52k" width="50%" height="100" frameborder="0" style="border:0" allowfullscreen></iframe>
    </div>

    <div id="sobre">
      <h2>
        Sobre a Hospedagem!
      </h2>

      <p>
        Conheça um pouco sobre nossa hospedagem.
      </p>
    </div>

    <div>
      <div>
        <div>
          <h3>A Hospedagem</h3>
          <p>
            A hospedagem dispoem de espaço recreativo, dormitorio. Banho e tosa e monitoramento por insntrutores capacitados. 
          </p>
        </div>

        <img src="assets/img1.jpg" alt="Faixada" title="Faixada"/>
      </div>

      <div>
        <div>
          <h3>Nossa Equipe </h3>
          <p>
           Apresentando a Equipe.
          </p>
        </div>

        <img src="assets/img2.jpg" alt="equipes" title="equipes"/>
      </div>

      

      <div>
        <div>
          <h3>Atendimento</h3>
          <p>
            Nosso atendimento é das 8H da manhã as 7h da noite.
          </p>
        </div>

        <img src="assets/img5.jpg" alt="Recepção" title="Recepção"/>
      </div>
    </div>
  </div>

  <div>
    <div>
      <div>
        <h4>Entre em contato conosco:</h4>
      </div>

      <a target="_blank" href="https://goo.gl/maps/wPAS58QxiTopxK6w7">
        <img src="assets/icones/endereco.png" alt="Ícone endereco" title="Ícone endereco"/>

        <p>
          Endereço
          Av. 123, 222 - Rio de Janeiro RJ
        </p>
      </a>

      <div>
        <img src="assets/icones/telefone.png" alt="Ícone telefone" title="Ícone telefone"/>

        <p>
          Cel: 5521000000000
        </p>
      </div>

      <a target="_blank" href="https://www.booking.com/searchresults.pt-br.html?aid=375635;label=msn-wLZ0m4wRNI00wFHQAaaO3w-79920787059858%3Atikwd-79920803013016%3Aaud-808219487%3Aloc-20%3Aneo%3Amte%3Adec%3Aqsbooking;sid=9ca5cbe6c9db71b34b98c0738ea780f4;dest_id=-666610;dest_type=city&">
        <img src="assets/icones/calendario.png" alt="Ícone calendario" title="Ícone calendario"/>

        <p>
          Faça sua reserva pelo Booking.com
        </p>
      </a>

      <div>
        © Copyright - PousadaDev
      </div>
    </div>
  </div>
  <form method="POST" action="http://arquivo.devmedia.com.br/projeto/requisicao.php">
    <h2>FORMULARIO DE ADOÇÃO</h2>
    <div>
      <fieldset>
        <legend>Conta:</legend>
        <div>
          <label>Email:</label>
          <input type="email" name="email" minlength="6" multiple required />
        </div>
        <div>
          <label>Senha:</label>
          <input type="password" name="senha" required />
        </div>
      </fieldset>
      <fieldset>
        <legend>Pessoal</legend>
        <div>
          <label>Nome:</label>
          <input type="text" name="nome" placeholder="Ex: Bruno" required autocomplete />
        </div>
        <div>
          <label>Telefone:</label>
          <input type="tel" name="telefone" placeholder="(99)999999999"  />
        </div>
        <div>
          Sexo:
          <input type="radio" name="sexo" value="masculino" checked>
          <label>Masculino</label>
          <input type="radio" name="sexo" value="feminino">
          <label>Feminino</label>
        </div>
        <div>
          <label>Data de nascimento:</label>
          <input type="date" name="data" required />
        </div>
        <div>
          <label>Comprovante de residencia:</label>
          <input type="file" accept="image/*" />
        </div>
      </fieldset>
      <fieldset>
          <legend>Endereço:</legend>
          <div>
            <label>Rua</label>
            <input type="text" name="endereco_rua" required />
          </div>
          <div>
            <label>Numero</label>
            <input type="number" name="endereco_numero" min="1" max="1000" value="0" required />
          </div>
          <div>
            <label>Complemento</label>
            <input type="text" name="endereco_complemento" required />
          </div>
          <div>
            <label>Cidade</label>
            <input type="text" name="endereco_cidade" required />
          </div>
          <div>
            <label>Estado</label>
            <select name="endereco_estado">
              <option value="SC">Santa Catarina </option>
              <option value="SC">Santa Catarina</option>
            </select>
          </div>
      </fieldset>
      <fieldset>
        <legend>Anuncio:</legend>
        <div>
          <label>Como conheceu A ANAPETSITTER:</label>
          <textarea placeholder="Conte um pouco sobre você. E nos diga qual animal se entereçou para adoção" name="adicional" rows="10" cols="20"></textarea>
        </div>
        <div>
          <input type="checkbox" name="utilizou" value="sim" checked>
          <label>Desejo receber ofertas por e-mail</label>
        </div>
      </fieldset>
    </div>
    <input type="submit" value="Finalizar cadastro" />
  </form>

</body>
</html>
