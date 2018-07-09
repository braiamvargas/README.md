# README.md
Meu trabalho da faculdade

Aluno: Braiam Rafael Vargas
RA:09012377
<<!DOCTYPE html>
 
<html>
 <head>
 <title> Gerador De Curriculum  </title>

 <meta name="description" content="Meu site">
 <meta http-equiv="Content-Type" content="text/html; charset=utf-8">
 </head>

 <body bgcolor="white">
  <h1>  <b> <center>Bem vindo ao gerador de curriculos</center> </b>                 </h1> 
  <h2>  <b> <center>Preencha o formulario com seus dados reais</center> </b>                </h2><br />
  
<form action="Script_do_Formulario.php" method="post">

<!-- DADOS PESSOAIS-->
<fieldset>
 <legend>Dados Pessoais</legend>
 <table cellspacing="10">
  <tr>
   <td>
    <label for="nome">Nome: </label>
   </td>
   <td align="left">
    <input type="text" name="email">
   </td>
   <td>
    <label for="sobrenome">Sobrenome: </label>
   </td>
   <td align="left">
    <input type="text" name="sobrenome">
   </td>]
  </tr>

    <tr>
   <td>
    <label for="imagem">Foto: </label>
   </td>
   <td>
    <input type="file" name="imagem" >

   </td>
  </tr>

  <td>
    <label for="email">E-mail: </label>
   </td>
   <td align="left">
    <input type="text" name="email">
  <tr>
   <td>
    <label>Nascimento: </label>
   </td>
   <td align="left">
    <input type="text" name="dia" size="2" maxlength="2" value="dd"> 
   <input type="text" name="mes" size="2" maxlength="2" value="mm"> 
   <input type="text" name="ano" size="4" maxlength="4" value="aaaa">
   </td>

   <td>
    <label for="sexo">Sexo:</label>
   </td>
   <td align="left">
    <select name="Sexo"> 
    <option value="M">Masculino</option> 
    <option value="F">Feminino</option> 

  </tr>

  <tr>
  <td>
    <label for="Nacionalidade">Nacionalidade: </label>
   </td>
   <td align="left">
    <input type="text" name="email">
   </td>
    
<td>
    <label for="EC">Estado Civil:</label>
   </td>
   <td align="left">
    <select name="Estado Civil"> 
    <option value=""></option>
<option value="1">Solteiro(a)</option>
<option value="2">Casado(a)</option>
<option value="3">União Estável</option>
<option value="4">Separado(a)</option>
<option value="5">Divorciado(a)</option>
<option value="6">Viúvo(a)</option> 
   </td>
  </tr>
 </table>
</fieldset>

<br />
<!-- ENDEREÇO -->
<fieldset>
 <legend>Dados de Endereço</legend>
 <table cellspacing="10">

  <tr>
   <td>
    <label for="rua">Rua:</label>
   </td>
   <td align="left">
    <input type="text" name="rua">
   </td>
   <td>
    <label for="numero">Numero:</label>
   </td>
   <td align="left">
    <input type="text" name="numero" size="4">
   </td>
  </tr>
  <tr>
   <td>
    <label for="bairro">Bairro: </label>
   </td>
   <td align="left">
    <input type="text" name="bairro">
   </td>
  </tr>
  <tr>
   <td>
    <label for="estado">Estado:</label>
   </td>

   <td align="left">
    <select name="estado"> 
    <option value="ac">Acre</option> 
    <option value="al">Alagoas</option> 
    <option value="am">Amazonas</option> 
    <option value="ap">Amapá</option> 
    <option value="ba">Bahia</option> 
    <option value="ce">Ceará</option> 
    <option value="df">Distrito Federal</option> 
    <option value="es">Espírito Santo</option> 
    <option value="go">Goiás</option> 
    <option value="ma">Maranhão</option> 
    <option value="mt">Mato Grosso</option> 
    <option value="ms">Mato Grosso do Sul</option> 
    <option value="mg">Minas Gerais</option> 
    <option value="pa">Pará</option> 
    <option value="pb">Paraíba</option> 
    <option value="pr">Paraná</option> 
    <option value="pe">Pernambuco</option> 
    <option value="pi">Piauí</option> 
    <option value="rj">Rio de Janeiro</option> 
    <option value="rn">Rio Grande do Norte</option> 
    <option value="ro">Rondônia</option> 
    <option value="rs">Rio Grande do Sul</option> 
    <option value="rr">Roraima</option> 
    <option value="sc">Santa Catarina</option> 
    <option value="se">Sergipe</option> 
    <option value="sp">São Paulo</option> 
    <option value="to">Tocantins</option> 
   </select>
   </td>
  </tr>
  <tr>
   <td>
    <label for="cidade">Cidade: </label>
   </td>
   <td align="left">
    <input type="text" name="cidade">
   </td>
  </tr>
  <tr>
   <td>
    <label for="cep">CEP: </label>
   </td>
   <td align="left">
    <input type="text" name="cep" size="5" maxlength="5"> - <input type="text" name="cep2" size="3" maxlength="3">
   </td>
  </tr>
 </table>
</fieldset>
<br />

<!-- Dados Academicos -->
<fieldset>
 <legend>Formacao Academica</legend>
 <table cellspacing="10">

<br/>
 
    <body>
    <input type="submit" name="BT" value="Enviar">  
    <input type="reset" value="Limpar">
    </form>
    </body>
</html>




 
