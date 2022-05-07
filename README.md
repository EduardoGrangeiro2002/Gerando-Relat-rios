## Regras de negócios ##
Somar total de horas trabalhadas em todos os anos 
Somar total de horas trabalhadas ao longo dos meses 
Somar total de horas trabalhadas ao longo dos anos 


## Relatório ##
### Entrada ###
1- Nome
2- Horas por dia
3- Dias trabalhados
4- Mês trabalhado
5- Ano trabalhado

### Saída ###
%{
  all_hours: %{
        danilo: 500,
        rafael: 854,
        ...
    },
  hours_per_month: %{
        danilo: %{
            janeiro: 40,
            fevereiro: 64,
            ...
        },
        rafael: %{
            janeiro: 52,
            fevereiro: 37,
            ...
        }
    },
  hours_per_year: %{
        danilo: %{
            2016: 276,
            2017: 412,
            ...
        },
        rafael: %{
            2016: 376,
            2017: 348,
            ...
        }
    }
}