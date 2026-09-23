# sistemas-distribuidos-aula-4
Qual processo possui as funções soma(), subtracao() e multiplicacao()?​
R=As três funções estão no processo servidor, no arquivo servidor_rpc.py
O cliente possui o código dessas operações?
​
R=não, apenas faz chamadas para elas através do ServerProxy

Qual endereço e porta identificam o serviço?​
R=localhost:8000

Quem inicia a chamada?​
R=o cliente

O resultado foi calculado no cliente ou no servidor?​
R=o resultado é calculado no servidor

Qual diferença você percebe em relação ao código de sockets TCP da Aula 2?​
R=XML-RPC é quase automática pela sua biblioteca, o cliente só prescisa chamar.
sockets TCP é mais manual, prescisa cuidar diretamente da comunicação
