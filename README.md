# BKR Matriz Mini

**Backup verificado e organização de acervos** para macOS e Windows.

Você monta o backup arrastando pastas e arquivos para um mapa. O app copia tudo, confere cada arquivo com **SHA-256** e
entrega um backup que dá para explorar, filtrar e provar. Nada é movido nem apagado na origem.

Interface em **Português do Brasil** e **inglês**, com troca de idioma ao vivo. Abre no tema claro; o tema escuro fica em
**Exibir › Tema**.

[English below](#english)

## Download

Baixe a versão mais recente em **[Releases](https://github.com/andersonguerra180/bkr_matriz_mini_Release/releases/latest)**:

| Arquivo | Sistema |
|---|---|
| `BKR-Matriz-Mini-macOS.zip` | macOS 12 ou mais novo, Apple Silicon e Intel (Universal) |
| `BKR-Matriz-Mini-Windows.zip` | Windows 10/11 x64, portátil (não precisa instalar) |

### Instalar no macOS

1. Descompacte o ZIP e arraste **BKR Matriz Mini.app** para a pasta **Aplicativos**.
2. Na primeira vez, clique com o botão direito no app e escolha **Abrir** (depois **Abrir** de novo no aviso).
   O app ainda não é notarizado pela Apple, por isso o macOS pede essa confirmação uma única vez.
3. Se aparecer *"o app está danificado"*, rode no Terminal e abra de novo:

   ```bash
   xattr -cr "/Applications/BKR Matriz Mini.app"
   ```

### Instalar no Windows

1. Descompacte o ZIP **inteiro** (não rode de dentro do ZIP).
2. Abra **BKR Matriz Mini.exe** dentro da pasta `BKR Matriz Mini`.
3. Se o SmartScreen mostrar *"O Windows protegeu o computador"*: **Mais informações › Executar assim mesmo**.
4. Para **receber do celular**, permita o app no Firewall do Windows (redes privadas).
5. Para o **ditado por voz**, permita o acesso ao microfone se o Windows pedir.
6. A pré-visualização de Word/Excel depende do Microsoft Office instalado.

## O que o app faz

**Make Backup** — monta o backup num mapa de pastas
- Arraste pastas e arquivos; crie pastas e subpastas, vários mapas e organize por regras (ano, assunto, tipo de mídia,
  mídia de origem…).
- Mescle duas pastas, com tela de conflito para arquivos de mesmo nome.
- Importe do celular pelo Wi-Fi: Galeria ou conversas do **WhatsApp**, com visualização da conversa.
- Questionário inicial e "Sobre este material" preenchem as fichas automaticamente.
- Procure duplicatas antes de gravar.
- Finalização com nome, destino e modo de organização; cópia verificada com SHA-256 e log por volume.

**Explorer** — navegue no backup pronto
- Grade e lista, busca e filtros por tipo de mídia, tipo de conteúdo, tipo de arquivo, mídia de origem, assunto e ano.
- Árvore de pastas e painel de metadados: ficha, geolocalização, notas, pessoas e tags.
- Edite, clone, exporte, envie para impressão, compacte em ZIP, aplique marca d'água em lote e publique um catálogo HTML.

**Stats** — saúde do backup: volumes, arquivos sem backup verificado, vulnerabilidades e logs por unidade.

**Tools**
- **Escanear origem:** compara um disco ou pasta com o backup e ingere só o que é novo.
- **Duplicatas:** encontra arquivos repetidos no backup inteiro ou nas pastas escolhidas.
- **OpenTimeStamps:** carimba arquivos no Bitcoin e exporta a prova (PDF ou pasta).
- **Folder Merge:** junta pastas (e `.zip`) sem sobrescrever nada, conferindo tudo com SHA-256 e gerando relatório.
- **ZIP Merge:** junta os `.zip` fragmentados do Google Drive numa pasta só.
- **Folder Compare:** compara duas pastas, diz qual é a mais atual e completa uma com a outra.

A faixa no topo mostra o modo: **EDIT MODE** (laranja, nada gravado até FAZER/ATUALIZAR BACKUP) ou **BACKUP MODE**
(verde, backup pronto, somente leitura).

---

## English

**Verified backup and collection organizer** for macOS and Windows. Drag folders and files onto a map; the app copies
everything, checks every file with **SHA-256** and delivers a backup you can browse, filter and prove. Nothing is moved
or deleted at the source. English and Brazilian Portuguese UI, light theme by default (dark in **View › Theme**).

### Download

Get the latest build from **[Releases](https://github.com/andersonguerra180/bkr_matriz_mini_Release/releases/latest)**:
`BKR-Matriz-Mini-macOS.zip` (macOS 12+, Universal) or `BKR-Matriz-Mini-Windows.zip` (Windows 10/11 x64, portable).

**macOS:** unzip, move the app to **Applications**, then right-click › **Open** the first time (the app is not notarized
yet). If macOS says the app is damaged, run `xattr -cr "/Applications/BKR Matriz Mini.app"` and open it again.

**Windows:** extract the whole ZIP and run **BKR Matriz Mini.exe**. If SmartScreen appears, click **More info › Run
anyway**. Allow it through the firewall (private networks) to receive files from your phone, and allow microphone
access for voice dictation.

### Features

- **Make Backup:** build the backup on a folder map, import from your phone over Wi-Fi (gallery or WhatsApp chats),
  find duplicates, and write a SHA-256-verified copy with a per-volume log.
- **Explorer:** grid/list, search, multi-select filters, folder tree, metadata panel, batch watermark, ZIP, print and
  HTML catalog export.
- **Stats:** backup health per volume.
- **Tools:** source scan, duplicates, OpenTimeStamps proof, Folder Merge, ZIP Merge (Google Drive split zips) and
  Folder Compare.

---

© 2026 BKR Systems. Jost font under the SIL Open Font License; built with JUCE.
