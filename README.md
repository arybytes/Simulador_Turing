
<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
</head>
 
<body>
    <h2> Simulação da Máquina Enigma e Bombe em Python </h2>
    <h3>Descrição:</h3>
    <p>
    Bem-vindo ao repositório que apresenta uma simulação da Máquina Enigma e do dispositivo Bombe, ambos utilizados durante a Segunda Guerra Mundial para cifrar e decifrar mensagens secretas. Este 
    programa em Python é uma homenagem à história da criptografia e à contribuição vital de Alan Turing e sua equipe na quebra do código Enigma.     
    </p>
    <h3>Funcionalidades Principais:</h3>
    <ul>
        <li>
            <strong>Comunicação via Protocolo TCP:</strong> O programa consiste em dois arquivos: <code>bombe_Machine.py</code> (servidor) e <code>enigma_Machine.py</code> (cliente), que estabelecem uma conexão TCP para enviar mensagens cifradas e decifradas entre si.
        </li>
    </ul>
     <h3>Execução do Programa:</h3>
    <ul>
    <li>  
    Primeiro, o arquivo do servidor (<code>bombe_Machine.py</code>) deve ser executado. Ele aguardará a conexão do cliente.
    </li>
     <div>
      <img src="https://github.com/arybytes/Simulador_Turing/assets/165725554/aa39e895-5bf6-4ef0-972e-3f93781d926f" width="500" height="200" alt="Execucao_Bombe">
        </div>
    <li>
    Em seguida, execute o arquivo cliente (<code>enigma_Machine.py</code>). Ele estabelecerá a conexão com o servidor e abrirá uma interface para o usuário digitar uma mensagem que será criptografada e               enviada para o servidor  </li>
    O exemplo da mensagem abaixo cifrada pela Máquina Enigma pode representar um mandato crucial emitido pelos líderes do Eixo para dar início à Operação Barbarossa, o ataque à União Soviética.  
          <div aling="center">
      <img src="https://github.com/arybytes/Simulador_Turing/assets/165725554/f94286dd-6219-472d-8a9e-eaa3db9a768b" width="500" height="333" alt="Interface_Enigma"/>
        </div>
    <li>
    Máquina Enigma (Cliente): O arquivo <code>enigma_Machine.py</code> simula a funcionalidade da Máquina Enigma, utilizada pelos alemães para criptografar mensagens durante a guerra. Ao reaizar o comando 
    anterior o arquivo <code>enigma_Machine.py</code> gera a mensagem cifradas e envia para o servidor.
         <div aling="center">
      <img src="https://github.com/arybytes/Simulador_Turing/assets/165725554/3b03f6ba-6840-48f8-8fd3-df28b88d99fd" width="500" height="200" alt="Execucao_Enigma"/>
        </div>
    </li>
    <li>
    Máquina Bombe (Servidor):  O arquivo <code>bombe_Machine.py</code> atua como servidor, recebendo mensagens criptografadas do cliente e aplicando o processo de descriptografia. O resultado é exibido no 
    terminal, revelando o conteúdo original da mensagem.
         <div aling="center">
      <img src="https://github.com/arybytes/Simulador_Turing/assets/165725554/929975e8-4443-4fd1-ac9c-434508094c57" width="500" height="200" alt="Terminal_Bombe"/>
        </div>
    </li>
   </ul>
    <h3>Importância Histórica:</h3>
   <li> 
    Esta simulação, embora simplificada, procura recriar de maneira modesta as complexas operações envolvidas na descriptografia da Máquina Enigma. O processo real de descriptografia era muito mais sofisticado e 
    demandava um alto nível de expertise técnica. A genialidade de Alan Turing e sua equipe foi fundamental para a vitória dos Aliados na Segunda Guerra Mundial e teve um impacto significativo no desenvolvimento 
    subsequente da computação e da criptografia.
    
Este repositório é uma oportunidade para os entusiastas da história e da programação explorarem e compreenderem melhor o papel dessas tecnologias pioneiras no contexto histórico da Segunda Guerra Mundial.
       <div aling="center">
      <img src="https://github.com/arybytes/Simulador_Turing/assets/165725554/24e51687-8328-4a9f-8589-ccaa3a6c9b8e" width="500" height="333" alt="Alan_Turing"/>
      </div>
   </li>

</body>
