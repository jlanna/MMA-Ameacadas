# Fluxograma

[Fluxo de trabalho](fluxograma.md)

```mermaid
flowchart TB
    
    %% define os recursos existentes que precisam ter seus termos levantados e compilados
    subgraph Recursos
        direction RL    
        subgraph CNCFlora
            direction TB
            rec1(IPT-DwC-A)
            rec2(Conjunto de Dados IUCN)
            rec3(WebService)
        end
        subgraph SALVE
            direction TB
            rec4(?)
        end
        subgraph Flora do Brasil
            direction TB
            rec5(IPT-DwC-A)
            rec6(WebService)
        end
        subgraph Catálogo da Fauna
            direction TB
            rec8(WebService)
        end
     end
    
    %% oficina de demanda do MMA
    2{{Oficina de Demanda do MMA/DESP}} --> 4
    
    %% geração do produto (3) 
    Recursos --> 3>Lista de Termos dos Recursos]

    %% produto (3) alimenta a oficina do MMA para critica aos termos existentes (4)
    3 --> 4{{Oficina de Critica do MMA}}

    %% a oficina (4) tem como resultado uma lista de termos acordada (6) e uma lista de termos que é demandada pelo MMA mas não está presente nos recursos (5)
    4 --> 5>Lista de termos que precisam ser sistematizados]
    4 --> 6>Lista de Termos Preliminar]

    %% a lista de termos que é demandada mas não está presente nos recursos (5)alimenta um o aprimoramento das fontes de dados (8)
    5 --> 8(Aprimoramento das fontes de dados)
    
    %% a lista de termos acordada na oficina (6) alimenta a ação de harmonização dos termos com os padrões existentes (9), na ação (7)
    6 --> 7(Harmonização com classes e termos de padrões já existentes)
    7 --> 15{{Oficina para elaborar a Lista de Termos Acordada}}
    15  --> Produto1

    %% bloco dos padrões existentes (9)
    subgraph Padrões
        direction RL
        G([Padrão IUCN])
        H([Padrão DwC e extensões])
        I([Outros padrões])
    end
    Padrões --> 7

    %% a ação de harmonização irá encontrar classes e termos demandados que não estão presentes em nenhum padrão, gerando a necessidade de sistematizar essas classes e termos em um relatório (10)
    7 --> 10>Classes e termos que não estão nos padrões considerados]

    %% o Produto1 é gerado pela compilação das classes e termos presentes nos padrões existentes e por um novo conjunto de classes e termos, não presentes nos padrões mas demandados pelo MMA
    subgraph Produto1
        11>Proposta de Padrão]
    end
    
    10 --> Produto1

    %% o Produto1 alimenta a oficina para definição dos mecanimos de publicação
    Produto1 --> 12{{Oficina de definição dos mecanismos de publicação dos dados}}

    %% ferramentas e protocolos de publicação de dados também alimenta a oficina 13
    13(Ferramentas e protocolos de publicação de dados) --> 12

    %% a oficina 13 gera a proposta de mecanismos de publicação
    subgraph Produto2
        14>Proposta de Mecanismos de Publicação]
    end
    12 --> Produto2
```

#### Legenda

```mermaid
flowchart TB

X{{Oficina}}
Y>Documento ou Relatório]
Z(Ação)
```
