<style>
    .color-red {
        color: #ff1414;
    }
    .color-green {
        color: #00b125;
    }
    .color-blue {
        color: #0090ff;
    }
    .font-bold {
        font-weight: bold;
    }

</style>

## PRODUTOS

---

### **Descrição**

Os produtos são a peça central do negócio, eles serão para alugar;<br>
Um produto <span class="color-green">disponível</span> pode ser alugado por um cliente de cada vez;

### **Requisitos**

O sistema deve:

- permitir cadastrar produtos;
- permitir editar o registro de produtos;
- permitir excluir o registro de produtos;

### **Aributos**

- nome;
- marca;
- modelo;
- codigo de barras;
- disponibilidade (boolean);
- manutenção (boolean);

## CLIENTES

---

### **Descrição**

Os clientes vão alugar produtos por tempo determinado;<br>
Um cliente pode alugar <span class="font-bold color-blue">N</span> produtos <span class="color-green">disponíveis</span>;

### **Requisitos**

O sistema deve:

- permitir cadastrar clientes;
- permitir editar cadastro de clientes;
- permitir excluir cadastro de clientes;

## VENDEDORES

---

### **Requisitos**

### O sistema deve:

- permitir cadastrar vendedores;
- permitir editar cadastro de vendedores;
- permitir excluir cadastro de vendedores;

## ALUGUEL

---

### **Requisitos**

O sistema deve:

- permitir criar aluguel de produtos disponiveis para alugar;
- permitir editar registro de aluguel de produtos alugadas;
- permitir fazer devolução de produto para tornar a produto disponível;
- permitir registrar quem foi o vendedor que alugou o produto;
- permitir registrar quem foi o cliente que alugou o produto;
- permitir registrar a data do aluguel do produto;
- permitir registrar a data de devolução do produto;
- permitir registrar mais de um produto;
- Notificar o vencimento dos aluguéis;

## EM MANUTENÇÃO

O sistema deve:

- exibir produtos com defeito separadamente;
