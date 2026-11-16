# Albany Medical Center

Site institucional independente do Albany Medical Center, com identidade visual branca e vermelha, layout responsivo e páginas estáticas.

## Páginas e recursos
- index.html: página inicial com busca, 62 especialidades, clínicas em destaque, diferenciais, salas/vagas, FAQ e contato.
- clinicas.html: diretório pesquisável das 50 clínicas e serviços, com busca por nome, especialidade e localização da sala.
- convenios.html: busca nos primeiros 40 itens da listagem pública de 126 convênios; a página também direciona à lista oficial completa para conferência.
- 404.html: página personalizada para endereços não encontrados.
- favicon.svg, robots.txt e sitemap.xml para identidade e indexação.
- Logo original enviado pelo usuário e foto de fundo recortada da referência aprovada do modelo 3; ambos são carregados pelo navegador a partir dos arquivos Base64 em assets/.

## Executar localmente
Use um servidor estático local na raiz do projeto. As páginas carregam os arquivos de marca e imagem a partir de /assets/, portanto não devem ser abertas diretamente pelo protocolo file://.

## Publicação
Projeto estático, sem etapa de build e sem dependência de Supabase. A raiz do projeto é /. O domínio pretendido é albany.hoottle.com.br; a implantação e a configuração DNS ainda precisam ser concluídas e verificadas na Vercel.

## Conteúdo e validação
As informações institucionais e os dados das clínicas foram compilados a partir do site público do Albany Medical Center. A listagem de convênios apresenta os primeiros 40 de 126 planos; a relação completa e a cobertura atualizada devem ser confirmadas no site oficial. A cobertura varia de clínica para clínica. O Albany não realiza agendamentos em nome das clínicas.

## Itens pendentes antes da publicação final
- validar o conteúdo e os dados de todas as clínicas com a administração;
- completar a relação de convênios e as associações reais entre convênios, clínicas e especialidades;
- substituir eventuais imagens ilustrativas por fotos oficiais em alta resolução, se disponíveis;
- concluir implantação e domínio próprio na Vercel;
- testar os fluxos e a responsividade em dispositivos reais.
