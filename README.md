# 📦 Product Manager - Flutter App

Este projeto Flutter é um **gerenciador de produtos**, permitindo **listar, adicionar, editar e excluir** produtos com informações associadas, como nome, preço e categorias (chips). A aplicação utiliza um banco de dados local (SQLite) para armazenamento persistente.

## 🚀 Funcionalidades

- 📋 Listagem de produtos
- ➕ Adição de novos produtos
- ✏️ Edição de produtos existentes
- ❌ Remoção de produtos
- 🔍 Visualização rápida das informações dos produtos com `Chips`
- 💾 Persistência local com SQLite

## 🗂️ Estrutura dos Arquivos

| Arquivo | Descrição |
|---------|----------|
| `main.dart` | Ponto de entrada da aplicação. Define o tema e inicializa a tela de listagem. |
| `product_list_page.dart` | Tela principal que exibe a lista de produtos com opções de editar ou excluir. |
| `product_form_page.dart` | Tela para adicionar ou editar um produto, com validação de formulário. |
| `product_database.dart` | Classe que gerencia a interação com o banco de dados SQLite: criação, inserção, atualização e exclusão de produtos. |
| `produto.model.dart` | Modelo de dados `Produto`, com métodos para conversão `Map` ↔ `Objeto`. |
| `list_item.dart` | Widget que representa um item individual na lista de produtos. |
| `chip_info.dart` | Widget personalizado para exibir informações do produto em formato de `Chip`. |
| `text_field_widget.dart` | Widget customizado para campos de texto, facilitando reutilização e padronização. |

## 🛠️ Dependências

- **Flutter SDK** (>= 3.0.0)
- `sqflite` - Para persistência local.
- `path_provider` - Para localizar diretórios no dispositivo.
- `provider` (opcional) - Caso deseje evoluir para gerenciamento de estado.

## 💻 Como Rodar

1. **Clone o repositório:**

```bash
git clone https://github.com/GustavoMascarenhasSfier/Carrinho-de-compra-completo.git
cd Carrinho-de-compra-completo
```

2. **Instale as dependências:**

```bash
flutter pub get
```

3. **Rode a aplicação:**

```bash
flutter run
```

4. **Teste:**

Abra em um emulador ou dispositivo físico. A lista de produtos começará vazia, podendo adicionar novos itens.

## 📝 Exemplo de Uso

- Clique no botão **"+"** para adicionar um produto.
- Preencha o nome, preço e categorias.
- Salve e visualize na lista.
- Edite ou exclua conforme necessidade.

## 🎯 Futuras Melhorias

- ✅ Integração com APIs externas.
- ✅ Filtros e busca de produtos.
- ✅ Validação mais robusta no formulário.
- ✅ Tema escuro.

## 👨‍💻 Autor

- Desenvolvido por [Gustavo Mascarenhas Sfier Arando]

## ⚖️ Licença

Este projeto está sob a licença MIT. Veja o arquivo `LICENSE` para mais detalhes.
