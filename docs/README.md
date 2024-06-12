# Introdução
Informações de usabilidade do sistema G-mus para entendimento e criação de cenários para testes regressivos

# Acões Programáticas - APS
- Referem-se as atividades realizadas que são programadas nos Centros de Saúde relacionando programas, medicações, visitas, etc.
## Cadastros
### Parâmetros
### Rotas
### Tipo de Acompanhamento
## Movimentos
### Ações Programáticas
Lista todos pacientes que possuem registro em programas de saúde onde há necessidade de serem geradas ações de visitas, controle, receitas.
Tela:
Filtro de busca 
- Dropdown
  * Código
  * Cidadão
  * Programa
  * Ativo
  * Data de Registro
  * Data de Baixa
- Input
  Campo onde será inserido a palavra chave ou código para filtrar

Campos apresentados na lista em tela
  * Ação - traz os ícones para exclusão / edição / listar receita
  * Código - número do ID do registro do paciente em Ações Programaticas
  * Cidadão - nome + código e informações do paciente
  * Programa
  * Ativo
  * Data de Registro
  * Data da Baixa
  * Qtd. Receitas

    
![Lista Ações Programáticas](/img/movimento_acoes_progrmaticas.png ':class=sombracaixa')

Cenários para Testes de Regressão
Consulta
<table class="waffle no-grid" cellspacing= "0">
        <thead style="background-color:#B0C4DE">
                <tr>    
                        <th id="0C1" style="width:233px" class"column-headers-background">CENÁRIO</th>
                        <th id="0C2" style="width:895px" class"column-headers-background">Listar pacientes com registro em programas de saúde</th>
                </tr>
        </thead>
        <tbody>
               <tr style="height:20px;">
                        <td class="s1" dir="ltr">Dado </td>
                        <td class="s2" dir="ltr">que estou logado no sistema e na tela Movimentos>Ações Programáticas - APS>Ações Programáticas </td>
               </tr>         
               <tr style="height:20px;">
                        <td class="s1" dir="ltr">Quando</td>
                        <td class="s2" dir="ltr">Seleciono uma das opções do filtro de busca </td>
               </tr>
               <tr style="height:20px;">
                        <td class="s1" dir="ltr">E</td>
                        <td class="s2" dir="ltr">Insiro um termo de busca no campo input</td>
               </tr>
               <tr style="height:20px;">
                        <td class="s1" dir="ltr">Então</td>
                        <td class="s2" dir="ltr">a lista de pacientes que correspondem aos critérios de busca será exibida</td>
               </tr>         
        </tbody>


Edição
Exclusão
Cadastro
Listar Receitas

### 












