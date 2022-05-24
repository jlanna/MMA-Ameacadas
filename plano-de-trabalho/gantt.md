(em atualização)

```mermaid
gantt
    %%Configuração
    dateFormat DD/MM/YY
    axisFormat  %d/%m/%y
    todayMarker on
    title Plano de Trabalho
    excludes weekends

    %%Início das Tarefas
    Elaboração plano de trabalho (P1):active, t0, 09/05/22, 15d
    Elaboração da Lista de Termos dos Recursos :t1, after t0, 10d
    Organizar a Oficina de Demanda do MMA/DESP :t2, after t0, 10d
    Oficina de Demanda do MMA/DESP :milestone, crit, m1, after t2,0d
    Compilar termos da oficina de demandas (P2) :t3, after t2, 1w
    Preparação da oficina de consolidação dos termos :t4, after t3, 10d
    Oficina para consolidação dos termos demandados e dos recursos:milestone, crit, m2, after t4, 0d
    Compilar lista de termos preliminar :t5, after t4, 1w
    Compilar lista de termos para sistematizar :t6, after t4, 1w
    Compitar lista de termos relevantes dos padrões existentes :t7, after t4, 1w
    Harmonização das listas com os padrões (P3):t8, after t5 t6 t7, 2w
    Preparação da oficina de termos acordados :t9, after t8, 10d
    Oficina de termos acordados :milestone, crit, m3, after t9, 0d
    Compilação do Produto 1 - Proposta de Padrão de Dados (P4) :t10, after t9, 2w
    Levantamento dos mecanismos de publicação :t11, after t10, 2w
    Oficina de definição dos mecanismos de publicação :milestone, crit, m4, after t11, 0d
    Compilação do Produto 2 - Proposta de mecanismos de publicação (P5) :t12, after t11, 2w
    Preparação da Reunião de apresentação dos produtos e fechamento :t13, after t12, 10d
    Reunião de apresentação dos produtos e fechamento :milestone, crit, m5, after t13, 0d
```
