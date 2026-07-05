![Banner do Projeto](assets/banner_insights.png)

# Detalhamento das Análises e Principais *Insights* para o Segmento Varejo
A análise está dividida em 04 (quatro) partes:

1. Panorama geral e performance de vendas;
2. Perfil de clientes;
3. Comportamento de clientes e fidelidade;
4. Associação de categorias de produtos por cesta.

Em cada parte procura-se identificar *insights* que derivem em ações para alavancar resultado, conforme veremos a seguir.

## 🌍**Panorama geral e performance de vendas**

O foco está na análise do volume de transações e registros ao longo do tempo, geração de ranking de produtos e categorias mais frequentes e quantidade média de itens no carrinho.

### 📈 Evolução Temporal e Fluxo de Vendas
A análise do gráfico de evolução (2019-2022) revelou pontos cruciais para a estratégia da rede:

* **Estabilidade da Cesta:** A correlação direta entre o volume de itens e o fluxo de pedidos indica que o comportamento do consumidor é previsível em termos de volume por compra.
* **Alerta de Performance em 2022:** Observou-se uma retração contínua no volume de vendas a partir de Janeiro/2022, atingindo a mínima histórica em Agosto/2022. Recomenda-se cruzar esses dados com indicadores macroeconômicos ou verificar a integridade da extração de dados deste período.
* **Sazonalidade Identificada:** Picos consistentes nos meses de transição de ano, sugerindo que as campanhas de Natal e Ano Novo são os principais motores de fluxo da rede.

        💡INSIGHT 1: O supermercado tem uma forte dependência das festas de fim de ano para bater metas de volume.

        💰AÇÃO: Fortalecer campanhas de "Volta às Aulas" ou "Inverno" (junho/julho), onde o gráfico mostra vales de consumo, para equilibrar o faturamento anual.

### 🥗Ranking de categorias e produtos

Se confirma que a categoria 'Alimentos' é locomotiva do negócio, com mais de 300.000 registros.

    💡INSIGHT 2: Ela sozinha supera a soma das próximas três categorias (Higiene, Limpeza e Bebidas). 

    💰AÇÃO: As pessoas já são atraídas pelos alimentos, utilizar essa categoria como 'produto' chamariz' para aumentar vendas de outras categorias como 'Pet' ou 'Acessórios' que costumeiramente têm maior margem e volume baixo de itens vendidos.

### 🛒 Comportamento do Carrinho (Ticket Médio de Itens)
A análise da distribuição de itens por pedido revelou um perfil de consumo focado em abastecimento (maior concentração de quantidade alta de produtos no carrinho):

* **Ticket Médio Elevado:** com uma média de ~35 itens e mediana de 37, o estabelecimento se posiciona como um local de compras de reposição e não apenas conveniência.
* **Segmentação de Clientes:** A curva multimodal identifica três comportamentos distintos (10, 32 e 55 itens), permitindo estratégias de marketing diferenciadas para cada grupo.
* **Potencial de aumento de quantidade de itens vendidos:** grande volume de pedidos na faixa de 50-55.

        💡INSIGHT 3: Grande parte do volume de pedidos gira em torno de 50-55 itens, acima disso há um vale que pode ser explorado.

        💰AÇÃO: Criar campanhas de fidelidade que recompensem carrinhos acima de 60 unidades, visando aumentar o ticket médio atual de ítens.


## 👤**Perfil de clientes**
Busca aprofundar entendimento do perfil de cliente analisando-se perfil de consumo por tipo familiar, grupos que geram maior volume de vendas e comportamento de compras por gênero.

### 👨🏻‍👩🏻‍👧🏻‍👦🏻Comportamento de consumo por perfil familiar
Ele cruza as variáveis de estado civil e quantidade de filhos para mostrar onde está o maior ticket médio de itens e revela variações no volume de compra:

* **Pico de Volume:** O perfil de clientes **Viúvos com 3 filhos** apresenta o maior ticket médio de itens (38.56), destacando-se como o segmento de maior abastecimento unitário.
* **Oportunidade em Famílias Médias:** Identificou-se um recuo no volume de itens em famílias de **Casados com 2 filhos** (34.10). Este grupo é o principal alvo para estratégias de incentivo ao aumento de cesta.
* **Consistência:** Clientes solteiros e separados demonstram baixa sensibilidade ao número de filhos no que tange ao volume do carrinho, mantendo uma média estável de ~35 itens.

        💡INSIGHT 4: Famílias de tamanho médio (casal com dois filhos) é o que apresenta o menor ticket médio de itens (34,10), é um nicho que poderá ser incentivado a crescer.

        💰AÇÃO: Criar campanhas de fidelidade que recompensem carrinhos acima de 40 unidades, visando aumentar o ticket médio atual de ítens.

### 🛍️Massa de vendas por perfil de clientes
Enquanto a análise anterior mostrava a média essa foca em mostrar o volume total de vendas, buscando elucidar 'público-alvo real':

* **Contraste entre média e volume de vendas:** na análise anterior clientes viúvos com três filhos tinham o maior ticket médio de itens, analisando-se volume total nota-se que representa apenas 2% em relação ao segmento familiar que lidera volume de compras (veremos a seguir).

* **Onde está o 'público-alvo real':** clientes sem filhos: solteiros (91.934), separados (89.425) e casados (84.479)  são os grupos que geram o maior volume bruto de itens vendidos.

        💡INSIGHT 5: Embora o ticket médio de viúvos c/ 3 filhos seja o maior, o grupo é pequeno e representa baixo resultado no volume total de vendas. Por outro lado, solteiros, divorciados e casados sem filhos têm peso significativo neste resultado, compram com maior frequência e por conveniência.

        💰AÇÃO: Focar na massa de clientes sem filhos através de: investimento em porções individuais e refeições rápidas (mix de produtos), otimizar o autoatendimento para compras pequenas.

Na etapa de conhecer os dados ao gerar estatísticas básicas para a coluna de quantidade de filhos dos clientes, já havia indicativo para este *insight* porque a moda indicou que o valor mais repetido é 'zero filhos'. Ao avaliar distribuição em quartis, Q1 (25%) e Q2 (50%, mediana) concentram esse mesmo valor, é afirmar que até a faixa de 50% é concentrada por clientes também com 'zero filhos', só irá aparecer até dois filhos a partir de Q3 (75%) e clientes com número maior de filhos é minoria absoluta.

Para finalizar a seção de conhecer perfil de clientes também foi analisado comportamento de compra por 'Gênero', entretanto, se observou que os hábitos de compras de mulheres e homens x categorias de produtos são muito parecidos, o que não gerou nenhum *insight*.

## 💎**Comportamento de clientes e fidelidade**
A análise visa detalhar informações sobre fidelização de clientes, clientes que pelo comportamento estão em risco de comprar na concorrência e oportunidades de fidelizar novos clientes.

### 🧐Quadrantes da fidelidade
Através do cruzamento de recência e frequência de compra, a análise demonstra que:
* **Alta frequência & baixa recência:** melhor quadrante, compram muito e, inclusive, recentemente.

        💰AÇÃO: Programas de fidelidade VIP e mimos para mantê-los fidelizados.

* **Alta frequência & alta recência:** clientes em risco, eram muito fiéis, mas pararam de vir comprar.

        💰AÇÃO: Campanhas com descontos agressivos.

* **Baixa frequência & baixa recência:**  novos clientes ou compradores ocasionais.

        💰AÇÃO: Incentivar a segunda e terceira compra para aumentar a frequência.

* **Baixa frequência & alta recência:** clientes perdidos, sem ações sugeridas para o momento.

### 📦Distribuição da diversidade de mix de categorias e produtos por cliente

Todos os 1.000 clientes compram exatamente as 6 categorias disponíveis, significa que o cliente não vai à loja apenas para uma 'emergência', busca para o abastecimento completo. Isso gera risco do cliente levar essa busca de abastecimento completo em outro estabelecimento, é algo que pode ser monitorado pela análise anterior.

Então, a análise aprofundou para mix de produtos por cliente, medindo quantos itens diferentes (SKUs) cada cliente já comprou ao longo de todo o período analisado:

* **60% dos clientes compra todo o mix de produtos da loja:** indica que o estabelecimento tem um público fiel que consome praticamente todo o catálogo de Alimentos, Higiene e Limpeza.

        💡INSIGHT 6: A grande maioria dos clientes (mais de 600) já comprou quase todos os itens disponíveis no seu mix principal.

        💰AÇÃO: como os cientes já exploram quase todo catálogo atual introduzir novidades no mix de produtos, oferecer clube de assinatura 'cestas prontas' personalizadas e incentivo às categorias como Pet e Acessórios.

## 🔗**Associação de categorias de produtos por cesta**
A partir da análise da correlação se busca mostrar qual a probabilidade de duas categorias de produtos serem compradas juntas na mesma transação, o que levou aos seguintes resultados:
* **A maior correlação está entre HIGIENE e LIMPEZA:** 

        💡INSIGHT 7: Comportamento de compra de clientes para manutenção do lar. O cliente que repõe o sabão em pó tende a repor também o shampoo ou sabonete.

        💰AÇÃO: No layout da loja, essas seções devem ser vizinhas e ter promoções do tipo 'Leve um item de limpeza e ganhe desconto em um de higiene' para aumentar conversão.

* **Seguida de perto por Bebidas e Pets:** 

        💡INSIGHT 8: Pode indicar um perfil de cliente que busca conveniência para momentos de lazer ou rotina em casa (bebida para o dono, item para o pet).

        💰AÇÃO: Testar uma ´'Ilha de Conveniência' que coloque petiscos para pets próximos à seção de bebidas (cervejas/refrigerantes), facilitando a jornada desse cliente ou ilha de bebidas no setor Pet.

* **Alimentos tem as correlações mais baixas com quase todas as categorias:** 

        💡INSIGHT 9: O cliente vem buscar o alimento independente do resto. No entanto, ela não 'puxa' as outras categorias naturalmente na mesma proporção que Higiene puxa Limpeza.

        💰AÇÃO: Como Alimentos é a âncora e atrai o cliente até à loja, buscar aumentar conversão em outras categorias com incentivos/descontos.


## ✅Conclusões Finais
A análise dos dados de varejo (2019-2022) permitiu identificar que o supermercado possui uma base de clientes fiel e com alta exploração do mix de produtos. Para a próxima fase estratégica recomenda-se:

**Foco no público de volume**: direcionar esforços de conveniência e agilidade para o público sem filhos (Solteiros/Separados).

**Expansão de cesta**: utilizar a força da categoria 'Alimentos' para alavancar categorias que costumam ter maior margem (Pet e Acessórios), explorando as correlações identificadas na matriz de afinidade.

**Recuperação de clientes**: ações imediatas de reativação para o grupo de 'alta frequência e alta recência'.

**Crescimento por inovação**: a base fiel já consome quase todo o mix atual, o crescimento de ticket médio virá da introdução de novos SKUs (novidades) e serviços personalizados, como clubes de assinatura.

Para finalizar, ressalta-se que a inclusão futura de indicadores de margem financeira, ações promocionais e rupturas de estoque é fundamental para distinguir o crescimento orgânico de picos sazonais e garantir que a estratégia de volume esteja alinhada à lucratividade real da operação.

**🏁 Fim da Análise** Obrigada por visitar este projeto!  
Desenvolvido por **Adriana Shinoda** | Programa SCTEC | 2026