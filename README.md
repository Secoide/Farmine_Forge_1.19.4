
# FARMINE MOD

O mod é voltado nas referencias a fazendas, sendo assim ira adicionar novos animais (Animações, IA e atributos), alem de minérios, produtos e outros detalhes.

➼ _Todas as modificações **não alteram** nenhum comportamento dos animais vanila do minecraft._

<br />

## Patch update: **BEES v0.1**<img src="https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/64b6dbae-2f42-40bf-9e5b-c8f3883502f4" alt="Gif de abelha voando." width="50"/>
![Badge em Desenvolvimento](http://img.shields.io/static/v1?label=STATUS&message=EM%20DESENVOLVIMENTO&color=GREEN&style=for-the-badge)

    Primeira atualização do mod, voltado as abelhas com inumeras variedades de 
    especies e seus derivados (mel, polen, ferrao, etc).


### Funcionalidades:
  Agoras as novas abelhas adicionadas estão mais realistas, animações de voo, ferroada entre outros.
    Todas as especies são spawnadas proximo dos seus [ninhos de abelhas](https://github.com/Secoide/Farmine_Forge_1.19.4/edit/master/README.md#adicionado) refente o seu tipo (ferrão ou sem ferrão).
As abelhas e ninhos irão dropar itens de suas propriedades quando mortas e quebradas, respectivamente.

### Desenvolvimento:
- :white_check_mark: Criar modelo e animação da abelha europeia.
- :white_check_mark: Criar modelo e animação do ninho de abelha de ferrão.
- :white_check_mark: Adicionar itens e blocos, derivados das abelhas europeias.
- :construction: Adicionar abelha europeia.
- :timer_clock: Spawnar ninhos de abelha em copas de arvores (Selva e Savana). (Raridade: médeia).
- :white_check_mark: Produtos criados a partir dos itens das abelhas;
- :timer_clock: Ninhos de abelha com niveis de mel e força do enxame de abelha.
- :snowflake: Criar 3 tipos de modelo de caixa de abelha europeia (base do enxame, extensão produção do mel, caixa automatica);

>**Legenda:** 
>:timer_clock: = Em seguida |
>:construction: = Em construção |
>:white_check_mark: = Realizado |
>:snowflake:	= Parado/Sem previsão |
>:stop_sign: = Cancelado |

<br />

#### Mobs/Blocks


| Versão | Descrição | Status |
| :---: | --- | :---: | 
| 0.1 | Abelha europeia | 60% |
| 0.1 | Ninho de Abelha com ferrão | 40% |
| 0.1 | Drops e podutos | 90% |
| 0.1 | Abelha africana | 30% |
| 0.1 | Abelha jataí | 0% |
| 0.2 | Vespa asiática | 0% |
| 0.2 | Abelha Verde (RARA) | 0% |

<br /><br />

<!-- Oculto-->
<details>
<summary> (SPOILER) Adicões</summary>
  
### Drops
  ![ferrao_abelha](https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/85c35754-0f40-47af-9180-c8a040293f2f)
  ![polem](https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/7d975e8c-d9f5-444f-8aaf-fbc9f014b7b6)
  ![favo_mel_cheio](https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/c9cad012-63c6-49f3-b582-0c7dfbcda8d1)
  
### Produtos
  ![imunizante_abelha](https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/14370a84-cc72-4357-9525-cdd9d8e78975)
  ![mel](https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/3e128c6e-ef2a-4acb-b65b-ed0035075dc6)
  ![propolis](https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/81a79399-687c-46f4-80cb-29ab9dcbd69b)
  ![geleia_real](https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/e7067f6e-091c-442a-a397-f15763c6b49a)
  ![hidromel](https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/ff15823f-9f6b-46c8-bb7f-7cdb22a85188)
  
### Abelhas
> Abelha Europeia/Africana

<figure >
   <img src="https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/3ea9cff3-71f9-48e6-99a5-4c783e139476"
       alt="Uma abelha feira no blockbench com animação de parada."
       width="70">
   <img src="https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/9abd6cbb-d39f-439f-9cc7-0a4a339de6b1"
       alt="Uma abelha feira no blockbench com animação de parada."
       width="70">
  </figure>
</div>


>Ninho de abelha
<div>
  <img src="https://github.com/Secoide/Farmine_Forge_1.19.4/assets/93934823/23b63c76-0d4e-42ed-970f-dfec1349378e" width="100px" />
</div>

<br /><br />

</details>
<br />

### Fluxograma do Mod

```mermaid
flowchart TD
    A{Ninho de Abelha} --> |Machado de Quartz -> Drop: 55%| L((Cazulo da Rainha))
    A --> |Drop: 25%| C(Favo de mel cheio)
    A --> |Drop: 75%| D(Favo de mel vazio)
    E --> |Bancada| F(Própolis)
    A --> |Drop: 30%| E(Polén)
    A --> |Spawn| G((Abelhas))
    G --> |Drop: 5%| H(Ferrão) --> |Suporte de poções| J(Apitoxina)
    FA[Frasco de água] --> J
    G --> |Drop: 15%| I(Polén)
    FE1[Ferro] --> |1x| M(Caixa de abelha) --> O
    DI[Diamente] --> |1x| Q(Extensor de mel) --> |Upgrade| O
    FE2[Ferro] --> |5x| R(Sistema automatico) --> |Upgrade| O
    L --> O{Caixa de abelha com enxame}
    MA1[Madeira] --> |6x| M 
    MA2[Madeira] --> |4x| Q 
    MA3[Madeira] --> |Upgrade| R 
    D --> |1x| M
    F --> |2x| Q
```
<br /><br />


