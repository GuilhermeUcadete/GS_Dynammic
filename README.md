# Portfólio de Projetos — Knapsack 0/1

## Membros da Equipe
- **Guilherme Ulacco** RM558418
- **Matheus Hostim** RM556517
- **Eduardo Lima** RM554804

***

## Descrição do Projeto
Este projeto resolve o Problema do Portfólio de Projetos, uma variação do problema clássico da Mochila 0/1, em quatro estratégias:

1. **Estratégia Gulosa (Greedy):** Seleciona projetos pela maior relação Valor/Horas-Especialista. Não garante solução ótima.
2. **Recursiva Pura:** Explora todas as combinações possíveis, não armazena subproblemas (ineficiente para grande número de projetos).
3. **Programação Dinâmica Top-Down (Memoização):** Usa recursividade com memoização para evitar cálculos repetidos e otimizar o tempo.
4. **Programação Dinâmica Bottom-Up (Iterativo):** Preenche uma tabela de subsoluções de forma iterativa, atingindo o máximo valor de maneira eficiente.

O objetivo é selecionar o conjunto de projetos que gera o maior valor total sem ultrapassar a capacidade máxima de Horas-Especialista.

***

## Estrutura do Diretório
```text
portfolio-projetos/
├── portfolio.py        # Código-fonte com implementações e testes
└── README.md           # Este arquivo de orientações e informações
```

***

## Instruções de Uso
1. Certifique-se que possui **Python 3.x** instalado no computador.
2. No terminal, acesse o diretório do projeto e execute:
   ```sh
   python portfolio.py
   ```
3. O script mostrará os resultados das quatro abordagens, permitindo comparar o desempenho e os valores máximos em cada método. Inclui exemplos onde o método guloso não encontra a solução ótima.

***

## Requisitos e Dependências
- **Python 3.x**
- Não requer bibliotecas externas (apenas módulo `random` padrão).

***

## Observações
- O código está amplamente comentado, explicando o funcionamento, os casos base e as complexidades teóricas de cada abordagem.
- Inclui casos de teste específicos para demonstrar falhas do método guloso e como as soluções de programação dinâmica encontram o resultado ótimo.
- Caso queira adaptar para outros exemplos ou ampliar os testes, basta modificar as listas de projetos e capacidade no código-fonte.
