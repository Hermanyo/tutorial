@Em relação as configurações internas:

Crie um arquivo com o nome de <code>local.properties</code> na pasta <code>/../PASTA_DO_APP/android</code> dentro dele coloque o seguinte caminho, <code>sdk.dir = /home/nome_de_usuario/pasta_do_sdk/sdk</code>, geralmente o caminho tem como padrão a pasta android, ex.: <code>sdk.dir = /home/nome_de_usuario/Android/Sdk</code> 


@Em relação ao ambiente de desenvolvimento: 

<strong>#1.</strong> Conecte seu celular ao PC usando USB ou pelo Wi-Fi. Caso seja USB vá para o passo #3.

<strong>#2.</strong>  Para conectar seu celular pelo Wi-Fi, existem duas formas.

&ensp;<strong>#2.1.</strong> Se você tem o adb network no menu basta fazer 

 &ensp;&ensp;<strong>#2.1.1</strong><code>adb connect <IP_do_adb network> </code>
 
 &ensp;&ensp;<strong>#2.1.2</strong><code>react-native run-android</code>
 
 na pasta do projeto. Caso contrário vá para o passo <strong>#2.2.</strong>

&ensp;<strong>#2.2.</strong> Alternativas ->
<a href="https://stackoverflow.com/a/53038954/10531643">CLIQUE AQUI</a> 

&ensp;<strong>#2.3.</strong> Ignore os próximos passos. Se tudo ocorreu bem, você já estará com o ambiente de dev pronto.

<strong>#3.</strong>Na pasta do projeto execute o comando  <code>$ react-native run-android </code>

Se tudo ocorrer bem no passo <strong>#3</strong>, um apk já estará instalado no seu celular.
   
Caso não consiga conectar, acesse o menu - Balançando o celular - e acesse <strong>Dev. Settings -> Debug server host & port for device</strong> coloque o IP da sua conexão ex.: 10.1.1.0:8081, e execute novamente o passo #5, em  seguida dê reload no app.  
