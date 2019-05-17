@Em relação as configurações internas:

Crie um arquivo com o nome de <code>local.properties</code> na pasta <code>/../GuiaUFS/android</code> dentro dele coloque o seguinte caminho, <code>sdk.dir = /home/nome_de_usuario/pasta_do_sdk/sdk</code>, geralmente o caminho tem como padrão a pasta android, ex.: <code>sdk.dir = /home/nome_de_usuario/Android/Sdk</code> 


@Em relação ao ambiente de desenvolvimento: 

<strong>#1.</strong> Conecte seu celular ao PC usando USB ou pelo Wi-Fi. Caso seja USB vá para o passo #3.

<strong>#2.</strong>  Para conectar seu celular pelo Wi-Fi, é preciso duas etapas.

&ensp;<strong>#2.1.</strong>  Siga os passos ->
<a href="https://stackoverflow.com/a/53038954/10531643">CLIQUE AQUI</a>
(Nota: os passos estão inglês, pois é uma resposta no fórum oficial do Javascript do StackOverFlow)

&ensp;<strong>#2.2.</strong> Ignore os próximos passos. Se tudo ocorreu bem, você já estará com o ambiente de dev pronto.

<strong>#3.</strong> . Na pasta do projeto execute o comando  <code>$ react-native run-android </code>

Se tudo ocorrer bem no passo <strong>#3</strong>, um apk já estará instalado no seu celular.

<strong>#4.</strong>  Caso o processo do passo <strong>#3.</strong>  ainda esteja em execução depois do <strong>BUILD SUCESSFULLY</strong>
 mate o processo usando <strong> Ctrl+C </strong>

<strong>#5.</strong> Finalmente, execute no local do projeto o comando <code>$ react-native start</code>
Se tudo ocorreu bem, você já estará com o ambiente de dev pronto.

Caso não consiga conectar, acesse o menu - Balançando o celular - e acesse <strong>Dev. Settings -> Debug server host & port for device</strong> coloque o IP da sua conexão ex.: 10.1.1.0:8081, e execute novamente o passo #5, em  seguida dê reload no app.

<p align="center">
  <img src="https://github.com/Hermanyo/GuiaUFS/blob/features-%26-improments%2C-LocalStorage-etc/assets/GuiaUFSInterface.png"> 
</p>
