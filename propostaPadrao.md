# Proposta de Padrão

[Em construção]

---

__Classes__

| [Taxon](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#taxon) | [Distribution](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#distribuição) | [MMA](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#mma) |
|---|---|---|

---

## Taxon

| [taxonID](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#taxonID)| [reino](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#reino) | [grupo](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#grupo) | [Nome Científico](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#nome-cient%C3%ADfico) |
|---|---|---|

---

### taxonID

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_taxonID" target="_blank">https://dwc.tdwg.org/list/#dwc_taxonID</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Um identificador único permanente para o nome científico associado ao taxon.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>8fa58e08-08de-4ac1-b69c-1235340b7001</code>, <code>32567</code>, <code>https://www.gbif.org/species/212</td></tr>
    </tbody>
</table>

### reino

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_kingdom" target="_blank">https://dwc.tdwg.org/list/#dwc_kingdom</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>O nome científico completo do Reino em que o táxon é classificado.</td></tr>
        <tr><td class="theme-label">Comentários</td><td>Nas bases originais do MMA constam "Fauna" e "Flora" no domínio. Contudo, visando a compatibilidade semântica entre sistemas, sugerimos a adoção dos termos "Plantae" e "Animalia" conforme listado.</td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Plantae</code>, <code>Animalia</code>, <code>Fungi</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Plantae</td></tr>
    </tbody>
</table>

### grupo

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>O nome "informal" para o grupo de organismos em que o táxon é classificado. Neste caso, utiliza-se a classificação adotada pelo DESM/MMA de domínio fechado.</td></tr>
        <tr><td class="theme-label">Comentários</td><td>É uma definição de sub-conjuntos de taxa conforme necessidades específicas do MMA. O termo equivalente adotado "gmp:taxonomicCoverage:commonName" é indicado para nomes comuns aplicáveis, mas pode também ser uma descrição geral para grupos de organismos, se apropriados. E.g. pau-brasil ou peixes continentais.</td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Anfíbios</code>, <code>Angiospermas</code>, <code>Aves</code>, <code>Briófitas</code>, <code>Gimnospermas</code>, <code>Invertebrados Aquáticos</code>, <code>Invertebrados Terrestres</code>, <code>Mamíferos</code>, <code>Peixes Continentais</code>, <code>Peixes Marinhos</code>, <code>Pteridófitas</code>, <code>Répteis</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Aves</td></tr>
    </tbody>
</table>

### familia

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_family" target="_blank">https://dwc.tdwg.org/list/#dwc_family</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>O nome científico completo da família em que o táxon é classificado.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Nomes válidos para o rank "Família" na Flora e Funga do Brasil e Catálogo da Fauna.</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Felidae</code>, <code>Monocleaceae</td></tr>
    </tbody>
</table>

### genero

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_genus" target="_blank">https://dwc.tdwg.org/list/#dwc_genus</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>O nome científico completo do gênero em que o táxon é classificado.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Nomes válidos para o rank "Gênero" na Flora e Funga do Brasil e Catálogo da Fauna, para a "Família" correspondente.</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Hura</code>, <code>Puma</td></tr>
    </tbody>
</table>

### epitetoEspecifico

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_specificEpithet" target="_blank">https://dwc.tdwg.org/list/#dwc_specificEpithet</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>O nome do epíteto específico da espécie.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Nomes válidos para o rank "Epíteto Específico" na Flora e Funga do Brasil e Catálogo da Fauna, para o "Gênero" correspondente.</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>crepitans</code>, <code>concolor</td></tr>
    </tbody>
</table>

### epitetoInfraespecifico

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_infraspecificEpithet" target="_blank">https://dwc.tdwg.org/list/#dwc_infraspecificEpithet</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>O nome do epíteto infra específico da espécie, excluindo qualquer designação de ranque taxonômico.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Nomes válidos para o rank "Infra Espécie" na Flora e Funga do Brasil e Catálogo da Fauna, para a "Espécie" correspondente.</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>alba</td></tr>
    </tbody>
</table>

### nomeVernacular

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_vernacularName" target="_blank">https://dwc.tdwg.org/list/#dwc_vernacularName</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Nome vernacular/comum/popular popularmente dado ao táxon descrito.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>pau-brasil</td></tr>
    </tbody>
</table>

### bioma

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Bioma brasileiro em que a espécie ocorre.</td></tr>
        <tr><td class="theme-label">Comentários</td><td>Não existe um termo de domínio específico nos padrões internacionais usuais. O termo equivalente dwc apontado foi adotado conforme demandas internas dos produtores.</td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Amazônia</code>, <code>Mata Atlântica</code>, <code>Cerrado</code>, <code>Caatinga</code>, <code>Pampa</code>, <code>Pantanal</code>, <code>Marinho</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Pantanal</td></tr>
    </tbody>
</table>

### categoria

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Código da categoria de ameaça definida.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>CR</code>, <code>DD</code>, <code>EN</code>, <code>EW</code>, <code>EX</code>, <code>LC</code>, <code>NE</code>, <code>NR</code>, <code>NT</code>, <code>VU</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>CR</td></tr>
    </tbody>
</table>

### criterio

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Uma string tokenizada dos critérios de avaliação considerados na avaliação da espécie. Deve conter tokens de cada critério individual, separados por vírgula. Por exemplo: A seguinte string de critérios "B1ab(ii,iii,iv,v)+2ab(ii,iii,iv,v)" deve ser representada da seguinte forma: "B1a,B1bii,B1biii,B1biv,B1bv,B2a,B2bii,B2biii,B2biv,B2bv". A vírgula também pode ser subtituída por barra vertical "|".</td></tr>
        <tr><td class="theme-label">Comentários</td><td>Este campo tem preferência sobre "RedListCriteria.manualCriteriaString". Se ambos são fornecidos, apenas este campo é considerado.</td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>B2ab(iii)</code>, <code>A2c,B1ab(iii)+2ab(iii)</td></tr>
    </tbody>
</table>

### ameacas

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Descrição da ameaça.</td></tr>
        <tr><td class="theme-label">Comentários</td><td>Os termos equivalentes listados possuem domínios específicos que devem ser considerados para eventual mapeamento.</td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Agropecuária; Extracao Direta:Caça/Pesca; Queimadas</td></tr>
    </tbody>
</table>

### endemismo

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Endemismo para Brasil.</td></tr>
        <tr><td class="theme-label">Comentários</td><td>Os termos base listados possuem domínios específicos que devem ser considerados para eventual mapeamento. No caso do termo dwc, recomenda-se o uso de um json detalhando nome de campo e conteúdo.</td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Agropecuária; Extracao Direta:Caça/Pesca; Queimadas</td></tr>
    </tbody>
</table>

### estadoOcorrencia

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_locationID" target="_blank">https://dwc.tdwg.org/list/#dwc_locationID</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Unidades Federativas onde o táxon ocorre.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>AC</code>, <code>AL</code>, <code>AP</code>, <code>AM</code>, <code>BA</code>, <code>CE</code>, <code>ES</code>, <code>GO</code>, <code>MA</code>, <code>MT</code>, <code>MS</code>, <code>MG</code>, <code>PA</code>, <code>PB</code>, <code>PR</code>, <code>PE</code>, <code>PI</code>, <code>RJ</code>, <code>RN</code>, <code>RS</code>, <code>RO</code>, <code>RR</code>, <code>SC</code>, <code>SP</code>, <code>SE</code>, <code>TO</code>, <code>DF</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>MG, RJ</td></tr>
    </tbody>
</table>

### presenca em areas protegidas

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Presença ou ausência em áreas protegidas.</td></tr>
        <tr><td class="theme-label">Comentários</td><td>Catálogo de UCs pode ser uma fonte de dados importante para flora. Os termos equivalentes dwc:MeasurementOrFact e dwc:measurementValue devem ser usados concomitantemente, o primeiro para descrever o campo e o segundo para o valor.</td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Sim</code>, <code>Não</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Sim</td></tr>
    </tbody>
</table>

### plano de acao nacional para conservacao (pan)

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td></td></tr>
        <tr><td class="theme-label">Comentários</td><td>Os termos equivalentes listados possuem domínios específicos que devem ser considerados para eventual mapeamento.</td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### ordenamento pesqueiro

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td></td></tr>
        <tr><td class="theme-label">Comentários</td><td>Os termos equivalentes listados possuem domínios específicos que devem ser considerados para eventual mapeamento.</td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### nivel de protecao na estrategia nacional

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Os Níveis de Proteção variam de 0 a 5, em que 0 demonstra ausência de medidas de conservação e 5 demonstra que a espécie está suficientemente coberta por medidas de conservação.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### type

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>A natureza ou gênero do recurso.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### license

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Um documento legal dando permissão oficial de uso do recurso.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### ownerInstitutionCode

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>O nome (ou acrônimo) em uso pela instituição possuidora de direitos sobre o objeto ou informação referida no registro.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### rightsHolder

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Uma pessoa ou organização possuidora ou detentora de direitos sobre o recurso.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### medida: area distribuicao UC+TI+AM

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Esta medida se refere ao grau de proteção de habitat da espécie em Unidades de Conservação, Terras Indígenas e Áreas Militares. Os cálculos utilizados nesta medida consideram o grau de efetividade de cada área protegida calculado pelo SAMGe/ICMBio e o grau de sobreposição da área de ocorrência da espécie com estas áreas protegidas. Detalhes do cálculo encontram-se no documento intitulado "Descricao_metodologia_analiseefetividade_nov18".</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>0</code>, <code>1</code>, <code>2</code>, <code>3</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>2</td></tr>
    </tbody>
</table>

### peso: area distribuicao UC+TI+AM

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Peso proporcional ao potencial de contribuição da medida para melhorar o status de conservação da espécie, que para esta medida de conservação representa o valor 2,5.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>2,5</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### medida: caverna

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>As análises espaciais de ocorrência das espécies em cavernas foram descritas no item anterior. A lista das espécies ameaçadas que ocorrem em cavernas foi fornecida pelo CECAV/ICMBio.
A sugestão da reunião de especialistas foi considerar com um peso maior as cavernas classificadas como de máxima relevância. Entretanto, a ocorrência de espécies ameaçadas é um dos critérios que classifica a caverna como de máxima relevância. Portanto, todas as cavernas deste exercício são necessariamente de máxima relevância.
Devido à dificuldade de determinar a extensão das cavernas, não foi possível calcular a área de distribuição das espécies que está coberta por cavernas, e sim presença e ausência. Dessa forma, foi atribuída Classe 2 nesse critério para todas as espécies analisadas que apresentaram sobreposição com cavernas.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>2,5</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### peso: caverna

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Peso proporcional ao potencial de contribuição da medida para melhorar o status de conservação da espécie.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>2</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### medida: PAN

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>A efetividade dos PAN foi avaliada de acordo com seu grau de implementação:
• Classe 1: espécies que estão em PAN não avaliado; espécies em PAN encerrados, aguardando novo ciclo; espécies em PAN com menos de 40% de implementação;
• Classe 2: espécies que estão em PAN com grau de implementação igual ou maior que 40%;
• Classe 3: espécies em PAN encerrado que atingiu seu objetivo e não necessita de novo ciclo.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>0</code>, <code>1</code>, <code>2</code>, <code>3</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### peso_PAN

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Peso proporcional ao potencial de contribuição da medida para melhorar o status de conservação da espécie.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>2</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### medida_ordenamento pesqueiro

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>A equipe do DESP/MMA realizou um levantamento das normas de ordenamento pesqueiro vigentes, considerando também moratórias e planos de recuperação. O critério considerado foi o seguinte:
• Classe 1: espécie é indiretamente beneficiada pela medida;
• Classe 2: ordenamento direcionado às práticas que afetam diretamente as espécies
• Classe 3: moratória ou citada nominalmente no ordenamento (exclusivo exemplo portaria da moratória da Piracatinga).</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>0</code>, <code>1</code>, <code>2</code>, <code>3</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### peso_ordenamento pesqueiro

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Peso proporcional ao potencial de contribuição da medida para melhorar o status de conservação da espécie.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>1</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### medida_portaria 443

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>A Portaria MMA nº 443/2014, que estabelece a lista das espécies ameaçadas da flora, foi considerada como uma medida de conservação pelo fato de proibir coleta, corte, transporte, armazenamento, manejo, beneficiamento e comercialização das espécies listadas.
Todavia, o Art. 3° permite uma exceção para as espécies da categoria Vulnerável (VU), desde que regulamentada. As espécies madeireiras desta categoria que estão no bioma Amazônia foram regulamentadas, o que permite seu corte. Portanto, essas espécies receberam uma pontuação menor nesse critério:
• Classe 1: espécies madeireiras, da categoria VU, que ocorrem no bioma amazônico;
• Classe 2: demais espécies da flora, listadas na Portaria MMA nº 443/2014.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### peso_portaria 443

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Peso proporcional ao potencial de contribuição da medida para melhorar o status de conservação da espécie.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>2</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### medida_portaria 445

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>A inclusão da Portaria MMA n° 445/2014 segue o mesmo princípio que o da Portaria MMA nº 443/2014, considerando que a lista das espécies de peixes e invertebrados aquáticos ameaçados também oferece proteção diferenciada a estas espécies em relação às espécies não listadas considerando as restrições de uso previstas. O critério considerado foi o seguinte:
• Classe 1: espécies com interesse sócio-econômico que se beneficiariam com a Portaria MMA 445/2014.
• Classe 2: CR e EN de interesse econômico, com captura proibida.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### peso_portaria 445

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Peso proporcional ao potencial de contribuição da medida para melhorar o status de conservação da espécie.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>2</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### medida_anexo CMS

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Anexo CMS foi considerado como medida de conservação segundo o seguinte critério:
• Classe 2: espécies listadas no Anexo II da CMS;
• Classe 3: espécies listadas no Anexo I da CMS.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>0</code>, <code>2</code>, <code>3</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### peso_anexo CMS

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Peso proporcional ao potencial de contribuição da medida para melhorar o status de conservação da espécie.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>1</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### medida_anexos CITES

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Anexos da CITES foram considerados como medidas de conservação segundo o seguinte critério:
• Classe 3: espécies listadas nos Anexos da CITES.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>0</code>, <code>3</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### peso_anexos CITES

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Peso proporcional ao potencial de contribuição da medida para melhorar o status de conservação da espécie.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>1</td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>

### soma classes

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Soma dos valores (após multiplicação na coluna vizinha) relativos às medidas de conservação listadas com exceção da Portaria 445 e Anexo CMS.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td></td></tr>
        <tr><td class="theme-label">Exemplos</td><td></td></tr>
    </tbody>
</table>



## Distribuição

## MMA

## 



