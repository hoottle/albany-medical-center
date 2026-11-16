# Albany Medical Center

Site institucional independente do Albany Medical Center, com identidade visual branca e vermelha e layout responsivo.

## Páginas e recursos
- Página inicial institucional (index.html) com busca, estatísticas, especialidades, clínicas em destaque, estrutura, salas/vagas, FAQ e contato.
- Diretório pesquisável das 50 clínicas e serviços (clinicas.html), com busca por nome, especialidade e localização da sala.
- Busca da página inicial conectada ao diretório de clínicas.
- Logo e imagem principal recuperadas das referências visuais aprovadas para o projeto.
- Arquivos de imagem armazenados como texto Base64 em assets/ e carregados no navegador; não dependem de banco de dados.

## Executar localmente
Abra o projeto em um servidor estático local. A página carrega os arquivos de marca e imagem a partir de /assets/, portanto recomenda-se usar um servidor local em vez de abrir diretamente pelo protocolo file://.

## Publicação
Projeto estático, sem etapa de build e sem dependência de Supabase. A raiz do projeto é /. O domínio pretendido é albany.hoottle.com.br; a implantação e a configuração DNS ainda precisam ser concluídas e verificadas na Vercel.

## Conteúdo e validação
As informações institucionais e os dados das clínicas foram compilados a partir do site público do Albany Medical Center. Os dados de localização, especialidades e convênios devem ser revisados pela administração antes da publicação definitiva. A cobertura de convênios varia de clínica para clínica. O Albany não realiza agendamentos em nome das clínicas.

## Itens pendentes antes da publicação final
- validar o conteúdo e os dados de todas as clínicas com a administração;
- completar a relação de convênios e as associações reais entre convênios, clínicas e especialidades;
- substituir eventuais imagens ilustrativas por fotos oficiais em alta resolução, se disponíveis;
- concluir implantação e domínio próprio na Vercel;
- testar os fluxos e a responsividade em dispositivos reais.
