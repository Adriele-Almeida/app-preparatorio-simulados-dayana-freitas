# DOSSIÊ DE SIMULADOS - DAYANA FREITAS
Data: 22-11-2026

## Objetivo
APP PREPARATÓRIO SIMULADOS - DAYANA FREITAS, com acesso público, sem cadastro, três dificuldades e questões de múltipla escolha.

## Referências recebidas
1. https://psicotecnico.simuladoprovadetran.com.br/
2. https://psicotecnico.simuladoprovadetran.com.br/teste/atencao
3. https://psicotecnico.simuladoprovadetran.com.br/teste/raciocinio
4. https://psicotecnico.simuladoprovadetran.com.br/teste/personalidade
5. https://psicotecnico.simuladoprovadetran.com.br/teste/coordenacao
6. https://www.beltraodespachante.com/post/como-se-preparar-para-ser-aprovado-no-exame-psicot%C3%A9cnico-do-detran

As páginas de testes são aplicações dinâmicas; os links indicam temas de estudo, não fornecem banco completo recuperável por leitura de texto.

## Anexos revisados
- simulado-cognitivo-psicotecnico.json: 8 questões de raciocínio, 6 comparações de códigos, 2 cenários de memória que contêm 5 perguntas e grade de atenção com 50 símbolos.
- simulado-cognitivo-psicotecnico-vigilante.md: conteúdos e explicações dos três módulos cognitivos, com geradores sugeridos.
- simulado-reciclagem-vigilante-patrimonial.md: 20 questões de legislação, combate a incêndios, primeiros socorros, armamento e segurança bancária.
- simulado-teorico-vigilante.json: versão estruturada das 20 questões teóricas.

## Dificuldades
FÁCIL: identificação, padrões simples, noções essenciais e autopercepção.
MÉDIO: comparação, raciocínio aplicado, memorização e interpretação.
DIFÍCIL: padrões complexos, sequência visuo-espacial, memória operacional e situações teóricas mais elaboradas.

## Áreas
1. Teoria: vigilância patrimonial, legislação, primeiros socorros, incêndios, armamento e segurança bancária.
2. Raciocínio: séries numéricas, padrões de símbolos, lógica dedutiva e orientação.
3. Atenção: comparação de códigos, contagem e discriminação.
4. Memória: recordação de detalhes e objetos de cenários e sequências.
5. Coordenação: exercícios didáticos de orientação e lateralidade.
6. Personalidade: autorrelato de preferências comportamentais sem respostas certas.

## Integridade editorial
- Duplicatas entre arquivos Markdown e JSON foram consolidadas, preservando perguntas e gabaritos da versão JSON.
- O arquivo Markdown cognitivo possui contagem conflitante sobre o caça-alvos. A conferência na grade JSON mostra 8 losangos ◆ e 7 estrelas ★ = 15 alvos; o aplicativo usa 15.
- Lei 7.102/1983 mencionada no banco teórico foi revogada pela Lei 14.967/2024. Algumas perguntas do acervo original exigem revisão especializada antes de serem tomadas como referência jurídica atual.
- As questões de personalidade têm respostas pessoais e não avaliam aptidão psicológica.
- As atividades de coordenação e memória no app são perguntas didáticas; não reproduzem instrumentos oficiais nem produzem laudo.
- Testes na web vinculada são referências temáticas; não foi efetuada cópia automatizada integral dos bancos de terceiros.

## Arquitetura
- Interface HTML/CSS/JavaScript responsiva.
- GitHub: Adriele-Almeida/app-preparatorio-simulados-dayana-freitas
- Vercel: publicação de produção por integração GitHub.
- Supabase: projeto Automações Estratégicas; tabelas dayana_simulados_questoes e dayana_simulados_tentativas.
- Acesso público à seleção e realização dos simulados.
- Registro anônimo de respostas, tempo e pontuação; sem login e sem leitura pública das tentativas.
- Identidade: #050505, #171717, #C2E300 e #FFFFFF.

## Limites do estado atual
- Contagem atual deve ser conferida no Supabase; o banco carrega dinamicamente.
- Os itens de memória e coordenação são de múltipla escolha e não incluem recursos motrices calibrados nem ocultação temporizada de cartões.
- O conteúdo de terceiros hospedado nas URLs não está reproduzido integralmente.
