# tela-de-login
Criei esse menu para praticar ainda mais meu HTML e CSS


HTML

<div class="form">
        <form method="post" action="index.php"><br>
        <h1>Sistema de Clientes</h1><br><br><br>
        <h2>Cadastro</h2><br>
        <label for="nome">Nome:</label>
        <input type="text" size="40" placeholder="Nome Completo"><br><br>
        <label for="cpf">Cpf:</label>
        <input type="text" size="40" placeholder="123.123.123-00"><br><br>
        <label for="email">Email:</label>
        <input type="text" size="40" placeholder="Email Válido"><br><br>
        <label for="email">RG:</label>
        <input type="text" size="40" placeholder="1234567"><br><br>
        <label for="sexo">Sexo:</label>
        <label for="mas">Masculino</label>
        <input type="radio" name="opcao" id="op1">
        <label for="fem">Feminino</label>
        <input type="radio" name="opcao" id="op1">
        <label for="outros">Outros</label>
        <input type="radio" name="opcao" id="op1"><br><br>
        <h2>Endereço</h2><br><br>
        <label for="uf">Estado:</label>
        <select name="estado" id="uf">
        <option value="0">Escolha sua Região</option>
        <optgroup label="Norte">
            <option value="1">Acre</option>
            <option value="2">Amazonas</option>
            <option value="3">Amapá</option>
            <option value="4">Pará</option>
            <option value="5">Rondônia</option>
            <option value="6">Roraima</option>
            <option value="7">Tocantins</option>
        </optgroup>
        <optgroup label="Nordeste">
            <option value="8">Alagoas</option>
            <option value="9">Bahia</option>
            <option value="10">Ceará</option>
            <option value="11">Maranhão</option>
            <option value="12">Piauí</option>
            <option value="13">Pernambuco</option>
            <option value="14">Paraiba</option>
            <option value="15">Rio Grande do Norte</option>
            <option value="16">sergipe</option>
        </optgroup>
        <optgroup label="Centro-oeste">
            <option value="17">Mato-Grosso</option>
            <option value="18">Mato-Grosso do Sul</option>
            <option value="19">Goiás</option>
            <option value="20">Distrito-Federal</option>
        </optgroup>
        <optgroup label="Sudeste">
            <option value="21">Espirito-Santo</option>
            <option value="22">Minas-Gerais</option>
            <option value="23">Rio de Janeiro</option>
            <option value="24">São-Paulo</option>
        </optgroup>
        <optgroup label="Sul">
            <option value="25">Paraná</option>
            <option value="26">Rio Grande do Sul</option>
            <option value="27">Santa Catarina</option>
        </select>
            <label for="cidade">Cidade:</label>
            <input type="text" placeholder="Cidade"><br><br>
            <label for="cep">Cep:</label>
            <input type="text" placeholder="Cep">
            <label for="Bairro">Bairro:</label>
            <input type="text" placeholder="Bairro"><br><br>
            <label for="rua">Rua:</label>
            <input type="text" placeholder="Rua">
            <label for="nu">Número:</label>
            <input type="text" placeholder="Número"><br><br>
            <label for="comp">Complemento:</label>
            <input type="text" placeholder="Andar, Apartamento,Bloco"><br><br>
            <input type="submit" value="Enviar"> &nbsp; &nbsp;
            <input type="button" value="Voltar">
            
            
        </optgroup>

    </form>
        
    </div>
</body>
</html>

CSS

*{
        margin: 0;
        padding: 0;
        box-sizing: 0;
        font-family: sans-serif;
    }
    body {
        background-image: url("img.jpeg");
        background-color: royalblue;
        background-repeat: no-repeat;
        background-attachment: fixed;
        background-size: 100% 100%;
    }
    .form{
        background: #d3d3d3;
        width: 50%;
        height: 50%;
        margin: 0 auto;
        text-align: center;
        border: 2px solid #069;
        border-radius: 20px;
        margin-top: 40px;
    }
    h1{
        background: #069;
    }
    input,select{
        border-radius: 10px;
        height: 30px;
        border: none;
    }
    input[type=submit]{
        cursor: pointer;
        border-radius: 5px;
        border: none;
        height: 35px;
        width: 80px;
    } 
    input[type=button]{
        cursor: pointer;
        border-radius: 5px;
        border: none;
        height: 35px;
        width: 80px;
    }
    input[type=button]:hover{
        background: #069;
        color: #fff;
    }
    input[type=submit]:hover{
        background: #069;
        color: #fff;
    }
