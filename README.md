# Teclado-com-defeito
problema tecmnico de teclado windows 11
Olá, WerlyR
Meu nome é Emilly, sou consultora independente e espero lhe auxiliar hoje.

Para tentarmos solucionar seu problema, deixarei alguns passos abaixo a serem seguidos, inclusive o procedimento de reversão e desisntalação de driver, caso não tenha feito da maneira correta.

Método 1

Como diagnóstico, teste um teclado externo USB.
Verifique se funcionou.

Método 2
Desinstale o driver do teclado:
1. Pressione simultaneamente as teclas Windows + X;
2. Clique sobre a opção Gerenciador de Dispositivos;
3. Clique na seta que aponta para Controladores USB;
4. Clique com o botão direito do mouse sobre o dispositivo instalado e clique em Desinstalar;
Reinicie o computador.
Dica: Também remova tudo que está relacionado a Barramento Universal e Composite device.

Método 3
Procurando um driver homologado com a Microsoft:
1. Pressione simultaneamente as teclas Windows + X;
2. Clique sobre a opção Gerenciador de Dispositivos;
3. Clique na seta que aponta para Controladores USB;
4. Clique com o botão direito do mouse sobre o dispositivo instalado e clique em Atualizar Driver, após Pesquisar automaticamente software de driver atualizado.
5. Reinicie o computador.

Método 4
Revertendo uma versão de driver instalado:
1. Pressione simultaneamente as teclas Windows + X;
2. Clique sobre a opção Gerenciador de Dispositivos;
3. Clique na seta que aponta para Controladores USB;
4. Clique com o botão direito do mouse sobre o dispositivo instalado e clique em Propriedades;
5. Clique na guia Driver e selecione a opção Reverter (se estiver disponível).
6. Reinicie o computador.

Método 5
Instalando outras versões de drivers:

1. Pressione as teclas Windows + X;
2. Clique sobre a opção Gerenciador de Dispositivos;
3. Clique na seta que aponta para Controladores USB;
4. Clique com o botão direito do mouse sobre o dispositivo instalado e clique em Propriedades;
5. Clique na aba Driver > Atualizar Driver em seguida Procurar Software de Driver no Computador;
6. Clique em Permitir que eu escolha em uma lista de drivers de dispositivo no Computador;
Em seguida irá listar as versões dos drivers que já foram instalados, instale um a um e verifique o seu funcionamento.
Ao finalizar, reinicie o sistema.

Método 6
1. Pressione as teclas Windows+R, digite Taskschd.msc e clique em Ok;
2. Clique em Biblioteca do Agendador de Tarefas > Microsoft > Windows > TextServicesFramework;
3. Clique com o botão direito do Mouse sobre a tarefa MsCtfMonitor clique em Habilitar
4. Reinicie o sistema.

Método 7
SFC, DISM e CHKDSK.
Utilizar a ferramenta de correção de disco, arquivos e imagem do Windows
1. Pressione as teclas Ctrl+Shift+ESC, clique em Arquivo;
2. Clique em Executar nova tarefa;
3. Marque a opção Criar essa tarefa com privilégios administrativos;
4. No campo abrir digite cmd, em seguida clique em OK;
5. Execute os seguinte comandos, uma linha de cada vez, seguida de Enter:
sfc /scannow
dism /online /cleanup-image /CheckHealth
dism /online /cleanup-image /restorehealth
chkdsk /f /r /b
Para agendar uma verificação de disco, confirme com a tecla S e pressione Enter, e reinicie o equipamento.

Método 8
Voltar o sistema a um momento anterior ao surgimento do problema
Esta opção reverte o computador para um ponto anterior no tempo, chamado de ponto de restauração do sistema. Os pontos de restauração são gerados quando você instala um novo aplicativo, driver ou uma atualização do Windows e também quando você cria um ponto de restauração do sistema manualmente. A restauração não afeta seus arquivos pessoais, mas remove os aplicativos, os drivers e as atualizações instalados após a criação do ponto de restauração.
1. Windows + X > Windows Powershell (Admin);
2. Digite:
rstrui
Aperte Enter;
2. Selecione Avançar;
3. Escolha o aplicativo, driver ou atualização na lista de resultados, mais recente, em seguida, selecione Procurar programas afetados. Você verá a lista de itens que serão excluídos se você remover esse ponto de restauração.
Se você estiver satisfeito com as exclusões, selecione Avançar > Concluir.
Ou, se necessário, selecione um ponto de restauração anterior antes de selecionar Avançar > Concluir.

Método 9
Restaurar o PC
1. Pressione Windows+I para abrir a janela de Configurações;
2. Selecione Atualização e Segurança;
3. Selecione Recuperação;
4. Em "Restauração do PC" clique em "Começar agora".

Método 10
Siga os procedimentos abaixo para reverter a última atualização.
Antes de prosseguir, é sempre recomendado que o usuário faça o backup dos seus arquivos mais importantes para evitar transtornos maiores. Embora a ferramenta que vamos utilizar prometa manter os dados pessoais intactos, é difícil garantir isso com toda certeza.
1. Aperte as teclas “Win + I” para acessar a tela de “Configurações” e vá em ''Atualização e Segurança”;
2. Acesse a guia “Recuperação” e em “Voltar para a versão anterior do Windows 10”, clique em “Começar agora”;
3. Marque a opção pela qual você está desinstalando a atualização e clique em “Avançar”;
4. O Windows agora oferecerá a opção de procurar por uma nova atualização, clique em “Não, obrigado”;
5. Agora, você receberá o aviso de que alguns apps novos podem ser perdidos, clique em “Avançar”, e na mensagem seguinte em “Avançar” novamente;
6. Por fim, clique em “Voltar para versão anterior”.
Após você completar o processo, a máquina será reiniciada e pode demorar um pouco até chegar ao Windows. Antes de efetuar todos estes passos, é recomendado que você faça um backup dos arquivos importantes em que tenha trabalhado após a atualização.

Caso tenha lhe auxiliado, favor marcar como resposta. Caso não, me retorne para solucionarmos o seu problema.
Att,
Emilly C.
