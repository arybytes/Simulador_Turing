<!DOCTYPE html>
<html lang="pt">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <style>
        .center {
            text-align: center;
        }
    </style>
</head>
<body>
    <h2 class="center">Título: Simulação da Máquina Enigma e Bombe em Python</h2>
    <h3>Descrição:</h3>
    <p>
        Bem-vindo ao repositório que apresenta uma simulação da icônica Máquina Enigma e do dispositivo Bombe, ambos utilizados durante a Segunda Guerra Mundial para cifrar e decifrar mensagens secretas. Este programa em Python é uma homenagem à história da criptografia e à contribuição vital de Alan Turing e sua equipe na quebra do código Enigma.
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
            <div class="center">
                <img src="https://via.placeholder.com/500x200" alt="Execucao_Bombe">
            </div>
        </li>
        <li>
            Em seguida, execute o arquivo cliente (<code>enigma_Machine.py</code>). Ele estabelecerá a conexão com o servidor e abrirá uma interface para o usuário digitar uma mensagem que será criptografada e enviada para o servidor. O exemplo da mensagem abaixo cifrada pela Máquina Enigma pode representar um mandato crucial emitido pelos líderes do Eixo para dar início à Operação Barbarossa, o ataque à União Soviética.
            <div class="center">
                <img src="https://via.placeholder.com/500x333" alt="Interface_Enigma">
            </div>
        </li>
        <li>
            Máquina Enigma (Cliente): O arquivo <code>enigma_Machine.py</code> simula a funcionalidade da Máquina Enigma, utilizada pelos alemães para criptografar mensagens durante a guerra. Ao reaizar o comando anterior o arquivo <code>enigma_Machine.py</code> gera a mensagem cifradas e envia para o servidor.
            <div class="center">
                <img src="https://via.placeholder.com/500x200" alt="Execucao_Enigma">
            </div>
        </li>
        <li>
            Máquina Bombe (Servidor): O arquivo <code>bombe_Machine.py</code> atua como servidor, recebendo mensagens criptografadas do cliente e aplicando o processo de descriptografia. O resultado é exibido no terminal, revelando o conteúdo original da mensagem.
            <div class="center">
                <img src="https://via.placeholder.com/500x200" alt="Terminal_Bombe">
            </div>
        </li>
    </ul>
    <h3>Importância Histórica:</h3>
    <p>
        Esta simulação não apenas demonstra as habilidades técnicas necessárias para implementar uma versão virtual das máquinas Enigma e Bombe, mas também serve como um tributo à genialidade de Alan Turing e sua equipe. Seu trabalho na decifração do código Enigma foi fundamental para a vitória dos Aliados na Segunda Guerra Mundial e teve um impacto significativo no desenvolvimento subsequente da computação e da criptografia. Este repositório é uma oportunidade para os entusiastas da história e da programação explorarem e compreenderem melhor o papel dessas tecnologias pioneiras no contexto histórico da Segunda Guerra Mundial.
    </p>
    <div class="center">
        <img src="https://via.placeholder.com/500x333" alt="Alan_Turing">
    </div>
</body>
</html>
