# Manual do Utilizador — StudyCards

**Versão 1.1**  
**Plataformas:** iOS 18+ • macOS 16+

---

## Conteúdo

1. [Introdução](#1-introdução)
2. [Primeiros passos](#2-primeiros-passos)
3. [Organização e ordenação](#3-organização-e-ordenação)
4. [Modo de estudo](#4-modo-de-estudo)
5. [Importar e exportar](#5-importar-e-exportar)
6. [Partilhar flashcards](#6-partilhar-flashcards)
7. [Definições](#7-definições)
8. [Dicas](#8-dicas)

---

## 1. Introdução

Bem-vindo ao **StudyCards** — uma aplicação de flashcards poderosa e elegante para iOS e macOS. Crie, gere e estude os seus flashcards com suporte a fórmulas LaTeX, imagens e capacidades de importação/exportação transparentes.

![StudyCards — iOS](screenshots/ios/main.png)
![StudyCards — macOS](screenshots/macos/main.png)

**Funcionalidades principais:**

- **Grupos de flashcards:** organize os seus cartões por tema ou disciplina.
- **Flashcards completos:** cada cartão tem um frente e verso com suporte para texto, fórmulas LaTeX e imagens.
- **Reordenação manual:** arraste flashcards para alterar a sua ordem dentro de um grupo.
- **Edição de grupos:** edite ou elimine grupos a partir do menu de contexto (toque longo).
- **Ordenação e pesquisa:** ordene e pesquise grupos por nome, data ou número de flashcards.
- **Modo de estudo:** avalie o seu conhecimento com Fácil/Duvidoso/Não sabia.
- **Importação e exportação:** transfira os seus cartões através de ficheiros CSV ou JSON (com imagens base64 integradas).
- **Partilha:** envie os seus flashcards por email, WhatsApp, AirDrop e muito mais.
- **Definições personalizáveis:** aparência, idioma e ordem de estudo.
- **Design adaptável:** adapta-se automaticamente ao iPhone, iPad e Mac.

### Requisitos

- iOS 18.0 ou posterior / macOS 16.0 ou posterior.
- Ligação à internet necessária apenas para a renderização de fórmulas LaTeX (MathJax).

---

## 2. Primeiros passos

### 2.1 Criar um grupo

Os grupos ajudam-no a organizar os seus flashcards por tema, disciplina ou categoria.

**Passos:**

1. Abra o StudyCards.
2. Toque no botão **+** no ecrã principal.
3. Introduza um nome para o grupo (ex.: "Vocabulário Español", "Fórmulas de Matemática").
4. Opcionalmente, adicione uma descrição para identificar o conteúdo do grupo.
5. Toque em **Guardar** para confirmar.

![Criar grupo](screenshots/ios/create_group.png)

![Criar grupo - macOS](screenshots/macos/create_group.png)

**Dicas para organizar grupos:**

- Utilize nomes descritivos para fácil identificação.
- Considere criar grupos por disciplina, capítulo ou nível de dificuldade.
- Pode criar tantos grupos quantos precisar.

### 2.2 Editar ou eliminar um grupo

Pode editar ou eliminar um grupo diretamente a partir da lista.

**No iOS:**

1. Toque longamente no nome do grupo até aparecer o menu de contexto.
2. Selecione **Editar** para modificar o nome ou a descrição.
3. Selecione **Eliminar** para remover o grupo e todos os seus flashcards.

**No macOS:**

1. Clique com o botão direito no nome do grupo.
2. Selecione **Editar** ou **Eliminar**.

> **Aviso:** Eliminar um grupo remove permanentemente todos os seus flashcards. Certifique-se de que os exportou primeiro se precisar de uma cópia de segurança.

### 2.3 Criar um flashcard

Depois de entrar num grupo, pode começar a adicionar flashcards.

**Passos:**

1. Abra um grupo tocando nele.
2. Toque no botão **+**.
3. Introduza o texto do **frente** (a pergunta ou desafio).
4. Introduza o texto do **verso** (a resposta ou explicação).
5. Opcionalmente, adicione uma **imagem** tocando em **Selecionar Imagem**.
6. Opcionalmente, adicione uma **fórmula LaTeX** utilizando `$...$` (em linha) ou `$$...$$` (bloco).
7. Toque em **Guardar**.

![Criar flashcard](screenshots/ios/create_card.png)

![Criar flashcard - macOS](screenshots/macos/create_card.png)

### 2.4 Adicionar fórmulas LaTeX

O StudyCards suporta renderização LaTeX através do MathJax para notação matemática e científica.

| Tipo | Sintaxe | Exemplo |
|------|---------|---------|
| Em linha | `$f(x) = x^2$` | A função é $f(x) = x^2$ |
| Bloco | `$$\int_0^1 x^2 \, dx$$` | Fórmula numa linha separada |

**Exemplos de LaTeX:**

- **Equação quadrática:** `$x = \frac{-b \pm \sqrt{b^2 - 4ac}}{2a}$`
- **Teorema de Pitágoras:** `$a^2 + b^2 = c^2$`
- **Integral definida:** `$$\int_a^b f(x)\,dx = F(b) - F(a)$$`

> **Nota:** As fórmulas são renderizadas automaticamente ao guardar o cartão e durante as sessões de estudo.

### 2.5 Adicionar imagens

Pode associar imagens aos seus flashcards para aprendizagem visual.

**Passos:**

1. Ao criar ou editar um flashcard, toque em **Selecionar Imagem**.
2. Escolha tirar uma nova fotografia ou selecionar da sua biblioteca.
3. A imagem será associada ao flashcard.

![Adicionar imagem](screenshots/ios/add_image.png)

![Adicionar imagem - macOS](screenshots/macos/add_image.png)

> **Nota:** As imagens são automaticamente redimensionadas para um máximo de 1024 pixels para otimizar o armazenamento. Ao exportar como JSON, as imagens são incluídas em formato base64.

### 2.6 Eliminar um flashcard

Pode eliminar um flashcard deslizando para a esquerda.

**Passos:**

1. Na lista de flashcards, deslize o cartão para a esquerda.
2. Aparecerá um botão vermelho **Eliminar**.
3. Toque em **Eliminar** para confirmar.

![Deslizar para eliminar](screenshots/ios/swipe_delete.png)

![Deslizar para eliminar - macOS](screenshots/macos/swipe_delete.png)

> **Aviso:** A eliminação é permanente. Certifique-se de que exporta os seus cartões antes de os eliminar se não tiver uma cópia de segurança.

---

## 3. Organização e ordenação

### 3.1 Reordenar flashcards manualmente

Pode alterar a ordem dos flashcards dentro de um grupo arrastando-os.

**No iOS:**

1. Abra o grupo com os flashcards que pretende reordenar.
2. Toque em **Editar** na barra de ferramentas (canto superior esquerdo).
3. Alçadas de arrasto ⟟ aparecerão ao lado de cada flashcard.
4. Arraste o flashcard para a posição desejada.
5. Toque em **Concluído** para guardar a nova ordem.

**No macOS:**

1. Abra o grupo com os flashcards que pretende reordenar.
2. Toque no botão **Reordenar** (ícone ↕) na barra de ferramentas.
3. Arraste o flashcard para a posição desejada.
4. Toque em **Concluído** para sair do modo de reordenação.

> **Nota:** A ordem manual é preservada ao exportar e importar flashcards.

### 3.2 Ordenar grupos

Pode ordenar a lista de grupos por diferentes critérios.

**Passos:**

1. Toque no botão de ordenação (ícone ↕) na barra de ferramentas.
2. Selecione um dos critérios de ordenação:

| Critério | Descrição |
|----------|-----------|
| **Nome (A-Z)** | Ordem alfabética ascendente |
| **Nome (Z-A)** | Ordem alfabética descendente |
| **Mais recentes** | Grupos criados mais recentemente primeiro |
| **Mais antigos** | Grupos mais antigos primeiro |
| **Número de flashcards** | Grupos com mais flashcards primeiro |

> **Nota:** A ordenação aplica-se a ambas as secções **Grupos** e **Estudo**.

### 3.3 Pesquisar grupos

**No iOS:**

1. Puxe para baixo na lista de grupos para revelar a barra de pesquisa.
2. Escreva o nome do grupo que procura.

**No macOS:**

1. Utilize a barra de pesquisa no topo da barra lateral.
2. Escreva o nome do grupo que procura.

---

## 4. Modo de estudo

O modo de estudo é o coração do StudyCards. Permite-lhe rever os seus flashcards de forma interativa e avaliar o seu nível de conhecimento.

### 4.1 Iniciar uma sessão de estudo

**Passos:**

1. Selecione o separador **Estudo** na barra de navegação.
2. Encontre e selecione o grupo que pretende estudar.
3. O primeiro flashcard aparecerá no ecrã.

![Iniciar estudo](screenshots/ios/start_study.png)

![Iniciar estudo - macOS](screenshots/macos/start_study.png)

### 4.2 Navegar entre cartões

Durante uma sessão de estudo:

1. Leia o **frente** do cartão (a pergunta).
2. Pense na resposta.
3. Toque em **Mostrar Resposta** ou toque no cartão para revelar o **verso** (a resposta).
4. Avalie o seu conhecimento com um dos três botões:

| Botão | Significado | Descrição |
|-------|-------------|-----------|
| 🟢 **Fácil** | Sabia bem | O cartão será marcado como dominado. Aparecerá com menos frequência. |
| 🟡 **Duvidoso** | Lembrou-se com dificuldade | O cartão reaparecerá em breve para reforço. |
| 🔴 **Não sabia** | Não sabia | O cartão será repetido mais vezes até o aprender. |

**Atalhos de teclado (macOS):**

| Tecla | Ação |
|-------|------|
| **Espaço** | Virar o cartão |
| **1** | Avaliar como Fácil |
| **2** | Avaliar como Duvidoso |
| **3** | Avaliar como Não sabia |

![Modo de estudo](screenshots/ios/study_session.png)

![Modo de estudo - macOS](screenshots/macos/study_session.png)

### 4.3 Terminar uma sessão de estudo

Quando tiver revisto todos os cartões do grupo:

1. Aparecerá um resumo de conclusão.
2. Verá quantos cartões avaliou como *Fácil*, *Duvidoso* e *Não sabia*.
3. Toque em **Estudar Novamente** para repetir ou **Voltar aos Grupos** para sair.

![Resumo de estudo](screenshots/ios/study_summary.png)

![Resumo de estudo - macOS](screenshots/macos/study_summary.png)

---

## 5. Importar e exportar

O StudyCards permite-lhe transferir flashcards entre dispositivos ou criar cópias de segurança utilizando ficheiros CSV e JSON.

### 5.1 Exportar flashcards

**Passos:**

1. Abra o grupo que pretende exportar.
2. Toque no menu de ações e selecione **Exportar**.
3. Selecione o formato de exportação:
   - **CSV:** Formato de folha de cálculo. Ideal para abrir no Excel, Numbers, etc. Não inclui imagens.
   - **JSON:** Formato completo. Inclui texto, fórmulas LaTeX e imagens base64.
4. Escolha onde guardar o ficheiro (Ficheiros, iCloud Drive, etc.).

![Exportar](screenshots/ios/export.png)

![Exportar - macOS](screenshots/macos/export.png)

### 5.2 Estrutura do ficheiro JSON

O ficheiro JSON exportado tem a seguinte estrutura:

```json
{
  "groupName": "Vocabulário Español",
  "version": "1.0",
  "createdAt": "2026-07-12T10:30:00Z",
  "cards": [
    {
      "front": "Qual é a capital de França?",
      "back": "Paris.",
      "frontLatex": null,
      "backLatex": null,
      "difficulty": 0,
      "frontImage": "base64_encoded_string...",
      "backImage": null
    }
  ]
}
```

### 5.3 Estrutura do ficheiro CSV

O ficheiro CSV utiliza as seguintes colunas:

```csv
front,back,frontLatex,backLatex,difficulty,frontImage,backImage
"Qual é a capital de França?","Paris.","","","0","",""
```

> **Nota:** As imagens no formato CSV são exportadas como strings base64 nas colunas `frontImage` e `backImage`.

### 5.4 Importar flashcards

**Passos:**

1. Na lista de flashcards de um grupo, toque no menu de ações e selecione **Importar**.
2. Selecione um ficheiro CSV ou JSON do seu dispositivo.
3. O StudyCards importará os flashcards para o grupo atual.

![Importar](screenshots/ios/import.png)

![Importar - macOS](screenshots/macos/import.png)

> **Nota:** Se importar um ficheiro JSON com imagens base64, as imagens serão apresentadas corretamente nos flashcards.

### 5.5 Erros comuns de importação

| Erro | Causa | Solução |
|------|-------|---------|
| *Formato não reconhecido* | O ficheiro não é CSV ou JSON válido | Verifique se o ficheiro tem a extensão correta e não está corrompido |
| *Ficheiro vazio* | O ficheiro não contém cartões | Verifique se o ficheiro tem pelo menos uma linha de dados |

---

## 6. Partilhar flashcards

O StudyCards facilita a partilha de flashcards com outros utilizadores.

### 6.1 Partilhar um grupo como JSON

**Passos:**

1. Abra o grupo que pretende partilhar.
2. Toque no menu de ações e selecione **Partilhar**.
3. O menu de partilha do sistema será aberto.
4. Escolha a aplicação ou método para enviar:
   - **AirDrop** — para dispositivos Apple próximos.
   - **Mail** — envie o ficheiro JSON como anexo.
   - **WhatsApp** — envie o ficheiro JSON como documento.
   - **Mensagens** — envie por iMessage.
   - **Outras aplicações** — qualquer aplicação que aceite anexos de ficheiros.

![Partilhar](screenshots/ios/share.png)

![Partilhar - macOS](screenshots/macos/share.png)

### 6.2 Receber flashcards partilhados

Quando alguém lhe enviar um ficheiro JSON do StudyCards:

1. Abra o ficheiro no seu dispositivo.
2. Selecione **Abrir no StudyCards** ou **Importar**.
3. O grupo será adicionado automaticamente à sua coleção.

---

## 7. Definições

Personalize o StudyCards de acordo com as suas preferências.

### 7.1 Aparência

Controle o tema visual da aplicação.

| Opção | Descrição |
|-------|-----------|
| **Sistema** | Coincide automaticamente com a definição de aparência do seu dispositivo (claro ou escuro). |
| **Claro** | Utiliza sempre o modo claro. |
| **Escuro** | Utiliza sempre o modo escuro. |

**Passos:**

1. Aceda ao separador **Definições**.
2. Na secção **Aparência**, selecione uma das três opções.
3. A alteração é aplicada imediatamente.

![Definições de aparência](screenshots/ios/appearance.png)

![Definições de aparência - macOS](screenshots/macos/appearance.png)

### 7.2 Idioma

O StudyCards está disponível em 8 idiomas. Pode forçar um idioma específico ou utilizar o idioma padrão do sistema.

| Idioma | Código |
|--------|--------|
| **Sistema** | Seleciona automaticamente o idioma do dispositivo |
| Español | es |
| English | en |
| Português | pt |
| Français | fr |
| Deutsch | de |
| Italiano | it |
| 日本語 | ja |
| 中文 | zh |

**Passos:**

1. Aceda ao separador **Definições**.
2. Na secção **Idioma**, selecione o idioma desejado.
3. A alteração é aplicada imediatamente sem reiniciar.

![Definições de idioma](screenshots/ios/language.png)

![Definições de idioma - macOS](screenshots/macos/language.png)

### 7.3 Ordem de estudo

Defina a ordem padrão em que os flashcards são apresentados durante o modo de estudo.

| Opção | Descrição |
|-------|-----------|
| **Sequencial** | Os cartões são apresentados pela ordem de criação (ou ordem manual se tiver reordenado). |
| **Aleatório** | Os cartões são misturados em cada sessão. |

**Passos:**

1. Aceda ao separador **Definições**.
2. Na secção **Ordem de estudo**, selecione a sua preferência.
3. A alteração aplicar-se-á a todas as sessões de estudo futuras.

![Definições de ordem de estudo](screenshots/ios/study_order.png)

![Definições de ordem de estudo - macOS](screenshots/macos/study_order.png)

---

## 8. Dicas

### Organização

- **Crie um grupo para cada disciplina ou tema.** Isto ajudá-lo-á a encontrar rapidamente o que precisa de estudar.
- **Utilize nomes curtos e claros** para grupos e flashcards. Evite texto demasiado longo para ler no ecrã.
- **Reordene manualmente os flashcards** para colocar os mais importantes primeiro.
- **Revise os seus grupos periodicamente.** Elimine cartões que já dominou e adicione novos para acompanhar o seu progresso.

### Estudo

- **Utilize repetição espaçada.** Estude os mesmos cartões em diferentes dias para consolidar a memória a longo prazo.
- **Não ignore cartões difíceis.** Se avaliar um cartão como *Não sabia*, estude esse grupo novamente em breve.
- **Misture os modos de estudo.** Alterne entre ordem sequencial e aleatória para evitar memorizar a posição dos cartões.
- **Utilize atalhos de teclado** no macOS para estudar mais rapidamente (Espaço, 1, 2, 3).
- **Estude em sessões curtas.** 10 a 20 minutos é suficiente para uma sessão produtiva.

### Conteúdo

- **Escreva perguntas claras e concisas.** Evite ambiguidade.
- **Uma ideia por cartão.** Não sobrecarregue o frente ou verso com demasiada informação.
- **Utilize imagens.** Um diagrama ou imagem pode ser mais eficaz do que um parágrafo de texto.
- **Utilize fórmulas LaTeX** para conteúdo de matemática ou ciências. São precisas e têm um aspeto profissional.

### Cópias de segurança

- **Exporte os seus grupos regularmente.** Guarde cópias no iCloud Drive ou no seu computador.
- **Utilize o formato JSON** se quiser preservar imagens. O CSV apenas guarda texto.
- **Partilhe os seus flashcards** com colegas de estudo para colaborar nos estudos.

### Desempenho

- **Feche outras aplicações** ao estudar para que o StudyCards funcione sem interrupções.
- **Mantenha a aplicação atualizada** para ter as últimas funcionalidades e correções de erros.
- **Se as fórmulas LaTeX não renderizarem**, verifique a sua ligação à internet. O MathJax necessita de transferir recursos na primeira vez.

---

## Informações legais

- **StudyCards** é uma aplicação desenvolvida de forma independente.
- A utilização do MathJax está sujeita à sua licença Apache 2.0.
- Os seus dados são armazenados apenas no seu dispositivo. O StudyCards não recolhe nem partilha informações pessoais.

---

*Manual do Utilizador StudyCards — Versão 1.1 — Julho 2026*
