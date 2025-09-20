# operacao-x
Painel de Gestão e Análise de Docas
Este projeto é um sistema web completo e autónomo para a gestão e automação do fluxo de descarga de camiões num centro de distribuição. A aplicação é executada inteiramente no navegador (frontend-only) e utiliza o localStorage para persistência de dados, o que significa que toda a informação é guardada no computador do utilizador.

O painel está dividido em duas secções principais, acessíveis por abas: Gestão de Docas e Análise de Duplas.

✨ Funcionalidades Principais
Gestão de Docas
Fila de Espera Automática: Adicione motoristas à fila e ative o sistema para chamar automaticamente o próximo veículo para a primeira doca livre.

Gestão de Carretas: Ocupe docas manualmente com carretas, que operam fora do fluxo da fila automática.

Visualização em Tempo Real: Acompanhe o status de 12 docas (Vaga, Chamado, Ocupada, Carreta), os temporizadores de descarga e a fila de espera, tudo atualizado a cada segundo.

Log de Eventos: Um registo cronológico de todas as ações importantes (entradas na fila, chamadas, finalizações).

Senha para Motoristas: Ao adicionar um motorista, é gerada uma "senha" (a sua posição na fila) para que ele possa tirar um print e aguardar a sua vez.

Análise de Duplas
Atribuição de Duplas Fixas: Atribua duplas a docas específicas para todo o expediente. O sistema associa-as automaticamente a cada nova operação naquela doca.

KPIs de Desempenho: Acompanhe métricas cruciais como Tempo Médio de Espera, Tempo Médio de Descarga e a Dupla Mais Rápida/Lenta.

Gamificação e Conquistas: Um sistema de conquistas que premeia as duplas por atingirem metas diárias de velocidade, volume e consistência, fomentando a competição saudável.

Gráficos Interativos:

Classificação de Eficiência: Um ranking visual das duplas mais produtivas.

Giro de Doca: Mostra quantos veículos cada doca processou.

Relatórios e Exportação: Exporte todos os dados detalhados das operações para um ficheiro Excel.

🛠️ Tecnologias Utilizadas
HTML5

Tailwind CSS para estilização.

JavaScript (Vanilla) para toda a lógica e interatividade.

Chart.js para a visualização de dados e gráficos.

html2canvas para a funcionalidade de captura de ecrã.

🚀 Como Usar
Como este é um projeto frontend-only, não é necessária qualquer instalação ou servidor.

Clone ou descarregue os ficheiros do repositório.

Abra o ficheiro dashboard.html em qualquer navegador de internet moderno (Chrome, Firefox, Edge).

Toda a informação será guardada localmente no seu navegador.
