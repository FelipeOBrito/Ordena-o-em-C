# 📊 Algoritmos de Ordenação e Manipulação de Arquivos em C

Este projeto é a resolução da **Atividade Avaliativa 3**, que integra a implementação dos principais **Algoritmos de Ordenação** com a **Manipulação de Arquivos (`.txt`)** utilizando a linguagem C. 

O programa interativo permite ao usuário gerar um arquivo com dados desordenados, escolher um método para ordená-los e exportar o resultado para um novo arquivo, além de permitir a edição dinâmica dos dados armazenados.

---

## 🚀 Funcionalidades

O programa apresenta um menu interativo com as seguintes opções:

1. **Criar arquivo de dados desordenados:** Permite ao usuário digitar uma quantidade definida de números numéricos, que são salvos no arquivo `dados.txt`.
2. **Ler, Ordenar e Salvar:** 
   - Lê os dados de `dados.txt`.
   - Oferece um submenu para o usuário escolher o algoritmo de ordenação desejado.
   - Aplica a ordenação e salva o resultado organizado no arquivo `ordenado.txt`.
3. **Alterar um valor:** Lê o arquivo original, mostra os valores e seus índices, permite alterar o valor de um índice específico e reescreve o arquivo `dados.txt`. Logo após, sugere a reordenação automática.

---

## 🧠 Algoritmos de Ordenação Implementados

O usuário pode escolher entre 5 métodos clássicos de ordenação:

- **Bubble Sort:** Compara pares adjacentes e os troca se estiverem na ordem errada (O(n²)).
- **Insertion Sort:** Constrói a matriz ordenada um item de cada vez, inserindo os elementos em suas posições corretas (O(n²)).
- **Selection Sort:** Encontra o menor elemento da lista e o move para a primeira posição, repetindo o processo (O(n²)).
- **Merge Sort:** Algoritmo *Dividir e Conquistar* que divide a lista em sublistas, ordena-as e as mescla novamente (O(n log n)).
- **Quick Sort:** Outro método *Dividir e Conquistar* que escolhe um pivô e particiona o array ao redor dele (O(n log n) na média).

---

## 📁 Estrutura de Arquivos

Ao executar o programa, os seguintes arquivos serão manipulados/criados na mesma pasta do executável:

* `main.c` (ou o nome que você der ao código fonte): Contém todo o código do programa.
* `dados.txt`: Arquivo gerado pelo programa contendo os números originais de entrada (um por linha).
* `ordenado.txt`: Arquivo gerado pelo programa contendo a lista dos números após passarem pelo algoritmo de ordenação.

---

## 🛠️ Como Compilar e Executar

### Pré-requisitos
Você precisará de um compilador C instalado em sua máquina (como o **GCC**).

### Passos:

1. **Clone o repositório:**
   ```bash
   git clone [https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git](https://github.com/SEU_USUARIO/NOME_DO_REPOSITORIO.git)
