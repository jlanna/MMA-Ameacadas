# Proposta de Padrão

[Em construção]

---

__Classes__

| [Taxon](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#taxon) | [Distribution](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#distribuição) | [MMA](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#mma) |
|---|---|---|

---

## Taxon

| [taxonID](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#taxonID)| [Familia](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#familia) | [Genero](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#genero) | [Nome Científico](https://github.com/edalcin/MMA-Ameacadas/blob/main/propostaPadrao.md#nome-cient%C3%ADfico) |
|---|---|---|

---

### taxonID

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_taxonID" target="_blank">https://dwc.tdwg.org/list/#dwc_taxonID</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>Um identificador único permanente para o nome científico associado ao taxon.</td></tr>
        <tr><td class="theme-label">Comentários</td><td></td></tr>
        <tr><td class="theme-label">Domínio</td><td><code></td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>8fa58e08-08de-4ac1-b69c-1235340b7001; 32567; https://www.gbif.org/species/212</td></tr>
    </tbody>
</table>

### reino

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="https://dwc.tdwg.org/list/#dwc_kingdom" target="_blank">https://dwc.tdwg.org/list/#dwc_kingdom</a></td></tr>
        <tr><td class="theme-label">Definição</td><td>O nome científico completo do Reino em que o táxon é classificado.</td></tr>
        <tr><td class="theme-label">Comentários</td><td>Nas bases originais do MMA constam "Fauna" e "Flora" no domínio. Contudo, visando a compatibilidade semântica entre sistemas, sugerimos a adoção dos termos "Plantae" e "Animalia" conforme listado.</td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Plantae, Animalia, Fungi</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Plantae</td></tr>
    </tbody>
</table>

### grupo

<table class="table table-sm table-bordered">
    <tbody>
        <tr><td class="theme-label">identificador</td><td><a href="" target="_blank"></a></td></tr>
        <tr><td class="theme-label">Definição</td><td>O nome "informal" para o grupo de organismos em que o táxon é classificado. Neste caso, utiliza-se a classificação adotada pelo DESM/MMA de domínio fechado.</td></tr>
        <tr><td class="theme-label">Comentários</td><td>É uma definição de sub-conjuntos de taxa conforme necessidades específicas do MMA. O termo equivalente adotado "gmp:taxonomicCoverage:commonName" é indicado para nomes comuns aplicáveis, mas pode também ser uma descrição geral para grupos de organismos, se apropriados. E.g. pau-brasil ou peixes continentais.</td></tr>
        <tr><td class="theme-label">Domínio</td><td><code>Anfíbios, Angiospermas, Aves, Briófitas, Gimnospermas, Invertebrados Aquáticos, Invertebrados Terrestres, Mamíferos, Peixes Continentais, Peixes Marinhos, Pteridófitas, Répteis</td></tr>
        <tr><td class="theme-label">Exemplos</td><td><code>Aves</td></tr>
    </tbody>
</table>


### Nome Científico


## Distribuição

## MMA

## 



