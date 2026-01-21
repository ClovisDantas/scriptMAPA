# Instruções de Uso - RoboFinanceiro

## 📥 Arquivos de Entrada (Pasta 'entradas')
Coloque nesta pasta os extratos bancários do dia em formato PDF. O robô reconhece arquivos que contenham no nome:
*   `bb-arrec`, `bb-funseg`
*   `cef-funseg`, `cef-rest`, `res-arrec`, `res-funseg`
*   `bnb-arrec`, `bnb-funseg`
*   `bra-arrec`, `bra-funseg`
*   `rel` (Arquivos de relatório judicial)

**IMPORTANTE:** O arquivo **`Modelo.xlsx`** deve ser mantido permanentemente nesta pasta. **Nunca o apague**, pois ele serve de base para o preenchimento.

## 📤 Arquivo de Saída (Pasta 'saidas')
O resultado final será gerado nesta pasta com o nome:
*   **`Relatorio_Final.xlsx`**

**Nota:** Toda vez que o robô é executado, ele **substitui** o arquivo anterior pelo novo. Se precisar guardar o relatório de um dia específico, mova-o para outra pasta ou renomeie-o após o término.
