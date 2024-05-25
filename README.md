void listarProdutos() {
    for (int i = 0; i < numProdutos; i++) {
        printf("Produto %d:\n", i + 1);
        printf("Nome: %s\n", inventario[i].nome);
        printf("Quantidade: %d\n", inventario[i].quantidade);
        printf("Preço: %.2f\n", inventario[i].preco);
    }
}
