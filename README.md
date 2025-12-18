# Sistema de Gerenciamento de Closet

![C](https://img.shields.io/badge/C-00599C?style=for-the-badge&logo=c&logoColor=white)
![Windows](https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white)
![CRUD](https://img.shields.io/badge/CRUD-Operations-green?style=for-the-badge)

Um sistema completo de gerenciamento de closet desenvolvido em **C**, permitindo organizar suas peças de roupas de forma fácil e eficiente através de uma interface interativa no console.

![C](CRUD/picture/Language.png)

## 📋 Sobre

Este projeto implementa um sistema CRUD (Create, Read, Update, Delete) para gerenciamento de peças de roupa. O sistema oferece uma interface de menu interativa com navegação por setas do teclado, permitindo adicionar, visualizar, atualizar e excluir peças do seu closet.

## ✨ Funcionalidades

- ✅ **Criar peça de roupa**: Adicione novas peças ao closet informando ID, cor, tamanho e aspecto
- ✅ **Visualizar peça**: Busque e visualize detalhes de peças cadastradas pelo ID
- ✅ **Atualizar peça**: Modifique informações de peças existentes
- ✅ **Excluir peça**: Remova peças do closet permanentemente
- ✅ **Menu interativo**: Navegação intuitiva usando setas do teclado
- ✅ **Exibição de data/hora**: Mostra data e hora atual no menu principal
- ✅ **Animações de loading**: Feedback visual durante carregamento e fechamento

## 🎯 Características Técnicas

- **Capacidade**: Suporta até 20 peças de roupa em memória
- **Interface**: Menu interativo com navegação por setas (↑↓) e Enter
- **Estrutura de dados**: Cada peça contém:
  - ID (identificador único)
  - Cor
  - Tamanho
  - Aspecto
- **Sistema operacional**: Desenvolvido para Windows (usa `conio.h` e `Windows.h`)

## 🛠️ Requisitos

- **Sistema Operacional**: Windows
- **Compilador C**: 
  - DevC++ (recomendado)
  - MinGW
  - Visual Studio
  - Qualquer compilador C compatível com Windows

## 📦 Compilação e Execução

### Método 1: Usando DevC++

1. Abra o DevC++
2. Vá em **File → Open** e selecione `CRUD/CRUD.c`
3. Pressione **F11** para compilar e executar
   - Ou vá em **Execute → Compile & Run**

### Método 2: Usando linha de comando (MinGW)

1. Abra o Prompt de Comando ou PowerShell
2. Navegue até o diretório do projeto:
   ```bash
   cd CRUD-in-C\CRUD
   ```
3. Compile o programa:
   ```bash
   gcc CRUD.c -o CRUD.exe
   ```
4. Execute:
   ```bash
   CRUD.exe
   ```

### Método 3: Usando Visual Studio

1. Abra o Visual Studio
2. Crie um novo projeto "Console Application"
3. Adicione o arquivo `CRUD.c` ao projeto
4. Compile e execute (F5)

## 🎮 Como Usar

### Navegação no Menu

- **Setas ↑↓**: Navegue entre as opções do menu
- **Enter**: Selecione a opção desejada
- **Opções disponíveis**:
  1. Create a new shirt - Adicionar nova peça
  2. Read a shirt - Visualizar peça existente
  3. Update a shirt - Atualizar peça existente
  4. Delete a shirt - Excluir peça
  5. Exit - Sair do programa

### Adicionar uma Peça

1. Selecione "Create a new shirt" no menu
2. Informe os dados solicitados:
   - **ID**: Número identificador único
   - **Color**: Cor da peça
   - **Size**: Tamanho da peça
   - **Aspect**: Aspecto/característica da peça
3. A peça será adicionada ao closet

### Visualizar uma Peça

1. Selecione "Read a shirt" no menu
2. Informe o ID da peça que deseja visualizar
3. Os detalhes da peça serão exibidos

### Atualizar uma Peça

1. Selecione "Update a shirt" no menu
2. Informe o ID da peça que deseja atualizar
3. Digite os novos dados
4. A peça será atualizada

### Excluir uma Peça

1. Selecione "Delete a shirt" no menu
2. Informe o ID da peça que deseja excluir
3. A peça será removida permanentemente

## 📁 Estrutura do Projeto

```
CRUD-in-C/
├── CRUD/
│   └── CRUD.c          # Código-fonte principal
├── README.md           # Este arquivo
└── .gitignore          # Arquivos ignorados pelo Git
```

## 💻 Código

O programa utiliza:
- **Estruturas**: `struct closet` para armazenar dados das peças
- **Funções CRUD**:
  - `createShirt()` - Criar nova peça
  - `readShirt()` - Ler peça existente
  - `updateShirt()` - Atualizar peça
  - `deleteShirt()` - Excluir peça
- **Interface**: Menu interativo com navegação por teclado
- **Bibliotecas**: 
  - `stdio.h` - Entrada/saída
  - `stdlib.h` - Funções utilitárias
  - `string.h` - Manipulação de strings
  - `time.h` - Data e hora
  - `conio.h` - Controle de console (Windows)
  - `Windows.h` - Funções do Windows

## 🔧 Limitações

- Armazena dados apenas em memória (não persiste após fechar o programa)
- Capacidade máxima de 20 peças
- Funciona apenas no Windows (depende de bibliotecas específicas)
- Não possui validação de entrada avançada

## 🚀 Melhorias Futuras

- [ ] Persistência de dados em arquivo
- [ ] Suporte multiplataforma (Linux/macOS)
- [ ] Validação de entrada mais robusta
- [ ] Listagem de todas as peças cadastradas
- [ ] Busca por outros critérios (cor, tamanho, etc.)
- [ ] Interface gráfica (GUI)
- [ ] Banco de dados para armazenamento

## 🤝 Contribuindo

Contribuições são bem-vindas! Sinta-se à vontade para:
- Reportar bugs através de issues
- Sugerir novas funcionalidades
- Enviar pull requests com melhorias
- Melhorar a documentação

## 📄 Licença

Este projeto está licenciado sob a **Licença MIT**. Veja o arquivo `LICENSE` para mais detalhes.

## 📧 Contato

Para dúvidas, sugestões ou colaborações:
- **Email**: juliocesar70777077@gmail.com

## 🙏 Agradecimentos

- Comunidade de programação C
- Desenvolvedores de ferramentas open source

---

Desenvolvido com ❤️ em C para Windows

**Aproveite o seu closet organizado!** 👔👗
