# Planner SEDUC-CE 2026 · Filosofia

Planner em um único `index.html`, com HTML, CSS e JavaScript. Funciona no GitHub Pages e em navegadores modernos, sem instalação, dependências externas, banco de dados ou chave de API.

## Publicar no GitHub Pages

1. Abra [Settings → Pages](https://github.com/lucasonhub/StudyPlanner/settings/pages).
2. Em **Build and deployment**, selecione **Deploy from a branch**.
3. Escolha a branch **main**, a pasta **/ (root)** e clique em **Save**.
4. Aguarde a publicação. O endereço esperado é **https://lucasonhub.github.io/StudyPlanner/**. A própria tela Pages informa quando estiver disponível; o envio dos arquivos não ativa o Pages sozinho.

Para experimentar localmente, abra `index.html`. Para uma origem estável de armazenamento, use `python -m http.server 8000` nesta pasta e abra `http://localhost:8000`.

## Cronograma

- Período inicial: **30/10/2026 a 22/11/2026**, incluindo o dia da prova informado pelo usuário.
- Cargo: **Professor de Filosofia**.
- Dias regulares: **75 minutos de Filosofia + 30 minutos de conhecimentos básicos + 15 minutos de revisão**, totalizando 2 horas.
- Conhecimentos básicos: Educação Brasileira; Administração Pública; Língua Portuguesa; Leitura e Interpretação de Dados e Indicadores Educacionais.
- Minissimulados em **31/10, 07/11, 14/11 e 18/11**: 60 minutos de resolução, 40 de correção e 20 de revisão. Sugestão de 20 questões: 12 específicas e 2 de cada área básica. Não reproduzem a duração nem a distribuição completa das 80 questões da prova descrita nos PDFs.
- **20/11**: revisão final; **21/11**: até 1 hora, incluindo organização; **22/11**: checklist da prova, sem carga de estudo.
- Total inicial: **24 dias de calendário, 69 atividades e 45 horas planejadas**. As horas incluem correção, revisão e preparação.

Os seis eixos de Filosofia são emergência e especificidade; ação; colonialismo e escravismo; conhecimento científico; experiência estética; e ensino de Filosofia no Ensino Médio. Os 50 itens de Filosofia e os 77 de conhecimentos básicos aparecem nos blocos do cronograma e na consulta **Conteúdos do edital**. A contagem inclui títulos e subitens, conforme a estrutura verticalizada.

O planejamento oferece uma passagem concentrada por todos os itens no período disponível. Marcar uma atividade como concluída representa concluir o bloco previsto, sem certificar domínio de todos os seus conteúdos. Priorize dificuldades e edite as atividades conforme seu desempenho.

## Fontes do conteúdo

Foram utilizados os dois arquivos enviados pelo usuário:

- `Edital - Seduc-ce - 2026 - Verticalizado.pdf`.
- `Edital - seduc 2026 (gerais + especificas).pdf`.

Recortes: páginas impressas **2 a 4** (P1) e **12 a 13** (Filosofia). No PDF reduzido, são as páginas físicas 2 a 6. Foram corrigidas falhas de extração de letras, como “Filosof a”, preservando o conteúdo e a numeração. Os PDFs não foram adicionados ao repositório.

As fontes são versões verticalizadas e não foram autenticadas contra o edital oficial. O item 9 de Educação Brasileira traz “PNE 2026–2026”; essa referência foi preservada e sinalizada para conferência no documento oficial e nas retificações. As referências legais e a data da prova devem ser conferidas pelo candidato.

## Como usar

Selecione uma etapa e um dia. Marque atividades concluídas, use o lápis para mudar título, orientação, tipo ou duração e registre dúvidas no caderno do dia. **Só pendências** oculta atividades concluídas do dia selecionado. Os indicadores gerais usam todo o cronograma.

**Personalizar** altera cargo, início e carga diária e gera um novo plano, substituindo atividades, notas e progresso. Faça backup antes. O agrupamento detalhado do edital foi preparado para Filosofia; outros cargos recebem orientações genéricas e precisam de adaptação. Com uma data inicial diferente, os grupos começam no novo início; períodos mais curtos podem não comportar todos os conteúdos. As quatro etapas mantêm as datas de novembro previstas neste plano.

**Backup** exporta um JSON com plano, notas e progresso. **Restaurar backup** valida o arquivo e pede confirmação antes de substituir os dados atuais. **Imprimir / PDF** inclui o cronograma inteiro e as notas, mesmo quando o filtro de pendências está ativo.

O progresso usa `localStorage`: permanece neste navegador e nesta origem, sem sincronização com GitHub ou outros aparelhos. Limpar dados do navegador pode apagá-lo. Evite dados sensíveis em anotações e guarde backups; eles contêm suas notas. Nenhum progresso é enviado a um servidor. A contagem regressiva usa o fuso **America/Fortaleza**.

## Verificações

Verificado no Chromium em larguras de 1440, 390 e 320 pixels: navegação entre dias e etapas, carga horária, cobertura dos 127 itens do conteúdo, marcação e persistência após recarga, edição, filtro, personalização, exportação e restauração do backup e versão de impressão. Sem erros JavaScript nos fluxos testados.

## Se o endereço ainda não abrir

Em Settings → Pages, confirme **Deploy from a branch**, **main** e **/ (root)**, depois salve. Este repositório entrega o HTML diretamente, sem um workflow próprio do GitHub Actions. Se a origem estiver em **GitHub Actions**, altere-a para a publicação pela branch.

Acompanhe a publicação na aba [Actions](https://github.com/lucasonhub/StudyPlanner/actions): o GitHub deve criar a execução **pages build and deployment**. Aguarde a conclusão com sucesso e abra o link mostrado em Settings → Pages. Se a execução falhar, abra os detalhes do erro antes de alterar os arquivos. O endereço diferencia maiúsculas e minúsculas: use `/StudyPlanner/`.
