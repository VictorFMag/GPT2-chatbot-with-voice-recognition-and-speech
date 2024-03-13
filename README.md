<h3>Instalação</h3>
Digite o seguinte comando no terminal: "pip install -r requirements.txt"<br>
Tudo deverá ser instalado automaticamente.<br>
Caso o Jupyter Notebook não seja instalado, instale-o com o comando "pip install notebook" no terminal.
<hr>
<h3>Treinando o modelo</h3>
Infelizmente, o modelo treinado é muito pesado para ser armazenado no GitHub, portanto, treiná-lo novamente é a única opção.<br>
Para treinar um novo modelo, abra o arquivo Model_Training.ipynb e execute todas as células.<br>
Caso deseje, as configurações de treinamento podem ser alteradas, aumentando ou reduzindo a velocidade de treinamento, bem como a capacidade do modelo de responder corretamente.<br>
Os arquivos que servirão como datasets de treinamento devem ser colocados na pasta datasets em formato .txt.
<hr>
<h3>Testando o modelo</h3>
Abra o arquivo Chatbot.ipynb e execute todas as células de código anteriores ao título "Prompts".<br>
3 formas de prompts estão disponíveis:<br><br>
1) Apenas por texto<br>
2) Pergunta em texto e resposta em áudio<br>
3) Pergunta e resposta em áudio (necessário microfone)<br>
<hr>
<h4>Obs:</h4>
Esse projeto faz parte do meu aprendizado sobre LLMs - Large Language Models, portanto, podem surgir falhas ou melhorias futuras.<br>
Atualmente, o treinamento do modelo não está funcionando corretamente, um problema que ainda estou tentando corrigir.<br>
<hr>
<h3>A Fazer:</h3>
1) Corrigir o erro de treinamento do modelo;<br>
2) Criar uma interface amigável;<br>
3) Adicionar modulador de voz à resposta do modelo.