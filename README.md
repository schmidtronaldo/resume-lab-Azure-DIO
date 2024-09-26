
# Criar uma Conta no Azure
Acesse o Portal do Azure: Vá para portal.azure.com e faça login na sua conta. 

Se não tiver uma conta, crie uma.
# Criar uma Máquina Virtual
### No Portal do Azure:
Clique em "Criar um recurso" no canto superior esquerdo.

Selecione "Máquina Virtual".
### Configuração da Máquina Virtual:
- Assinatura: Escolha a assinatura que deseja usar.
- Grupo de Recursos: Selecione um grupo existente ou crie um novo.
- Nome da Máquina Virtual: Escolha um nome único.
- Região: Escolha a região onde a VM será hospedada.
- Imagem: Selecione o sistema operacional (por exemplo, Windows Server ou Ubuntu).
- Tamanho: Escolha o tamanho da VM com base nas suas necessidades (CPU, RAM).
### Configurações de Segurança:
- Nome de Usuário e Senha: Crie um nome de usuário e senha para acessar a máquina.
- Portas de Entrada: Selecione as portas que deseja abrir (por exemplo, RDP para Windows ou SSH para Linux).
### Configurações de Rede:
- Rede Virtual: Use uma rede existente ou crie uma nova.
- Grupo de Segurança da Rede: Configure as regras de segurança conforme necessário.
- Configurações Adicionais: (opcional)
Habilite opções como monitoramento, backups e criptografia, se desejar.
### Revisar e Criar:
- Revise todas as configurações e clique em "Criar". A VM será provisionada.
# Criar um Banco de Dados
### No Portal do Azure:
- Clique em "Criar um recurso" novamente.
- Selecione "Banco de Dados".
- Escolher o Tipo de Banco de Dados:
Selecione o tipo de banco de dados que deseja criar (por exemplo, Azure SQL Database, Cosmos DB, etc.).
### Configuração do Banco de Dados:
- Nome do Banco de Dados: Insira um nome para o banco de dados.
- Servidor: Crie um novo servidor ou selecione um existente.
- Se criar um novo servidor, defina o nome, localização, nome de administrador e senha.
- Recursos: Escolha a quantidade de recursos (DTUs ou vCores) conforme suas necessidades.
### Configurações Adicionais:
Configure opções como backup, geo-replicação, e firewall, se necessário.
### Revisar e Criar:
Revise as configurações e clique em "Criar". O banco de dados será provisionado.
# Conectar a Máquina Virtual ao Banco de Dados
### Acesse a Máquina Virtual:
 Use RDP ou SSH para acessar sua máquina virtual.
### Instale as Ferramentas Necessárias:
 Instale qualquer software necessário para acessar o banco de dados (por exemplo, SQL Server Management Studio para SQL).
### Conectar ao Banco de Dados:
 Utilize as credenciais que você configurou para conectar ao banco de dados a partir da sua VM.
### Monitorar e Gerenciar
Utilize o portal do Azure para monitorar o desempenho da máquina virtual e do banco de dados. Ajuste as configurações conforme necessário para otimizar os recursos.
# Dicas Finais
 Verifique se os grupos de segurança e as configurações de firewall estão permitindo as conexões necessárias entre a VM e o banco de dados.
 
 Considere usar Azure Resource Manager para organizar seus recursos de forma eficiente.
 
 Sempre que houver uma duvida não hesite em consultar a documentação.😄
