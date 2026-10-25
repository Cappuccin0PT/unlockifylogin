<div align="center">

# Unlockify.Hub

**As tuas conquistas da Xbox, Steam e RetroAchievements num só sítio — e a tua coleção de jogos físicos sempre à mão.**

Gratuita · Sem publicidade · Android e Windows · Em português de Portugal

[⬇️ Descarregar a versão mais recente](../../releases/latest)

</div>

---

## O que é

A Unlockify.Hub junta numa só app o teu progresso nas três maiores plataformas de conquistas e ajuda-te a organizar os jogos que tens em casa. Vês o que já desbloqueaste, o que falta para chegar aos 100%, lês e partilhas dicas da comunidade e tens a coleção física catalogada, com capas e estado de cada jogo.

## Funcionalidades

### 🏆 Conquistas
- **Xbox** (Xbox One, Series X|S, Xbox 360, Xbox original e PC), **Steam** e **RetroAchievements** (com modo Hardcore).
- Jogos jogados recentemente, quase completos, completos a 100% e **Mythic**.
- Raridade de cada conquista, avisos de conquistas que se podem perder (*missable*), impossíveis de obter e que precisam de jogo online.
- Conquistas secretas reveladas (pode ser desligado, para quem não quer spoilers).
- Modos de jogo de cada título: **Online**, **Co-op online** e **Co-op local**.
- Tempo de jogo de cada título.
- Página própria para cada conquista, com links para guias (TrueAchievements, YouTube, Google), as tuas notas e as dicas da comunidade.
- **Dicas da comunidade** com votos, vídeos do YouTube embebidos e moderação.
- **Perguntar à IA** (opcional): gera um guia da conquista com o teu próprio **Ollama** (no PC, na rede de casa ou Ollama Cloud) ou com a **Gemini** da Google, usando a tua chave. Os guias gerados ficam no teu aparelho e só são publicados se tu quiseres, sempre com a indicação "Gerado por IA".

### 📊 Perfil
- Estatísticas das três plataformas: conquistas, jogos, percentagem de jogos a 100%, horas jogadas e jogos mais jogados.
- Gráficos e uma **imagem para partilhar** o resumo do teu perfil.

### 📚 Minha Biblioteca (jogos físicos)
- Adiciona jogos **lendo o código de barras** com a câmara, escrevendo o código ou à mão.
- Capas automáticas (incluindo PlayStation, Nintendo e SEGA), ou foto da tua caixa.
- Estado de cada jogo: selado, completo, sem manual, só o disco/cartucho.
- Filtros por marca e consola, pesquisa e página própria de cada jogo.
- **Cópia de segurança** completa (dados e imagens) num ficheiro teu.
- **Sincronização local PC ↔ telemóvel por QR**, na rede de casa, encriptada.

### ✨ E mais
- Cartões de partilha de cada jogo.
- Game Pass (novidades e jogos a entrar) e jogos retrocompatíveis.
- Atualizações automáticas da app.

## Descarregar e instalar

Todas as versões estão em **[Releases](../../releases)**.

| Sistema | Ficheiro | Notas |
|---|---|---|
| **Android** | `.apk` | Permite "instalar apps de fontes desconhecidas" quando o Android pedir. |
| **Windows** | instalador `.exe` ou versão portátil | Na primeira vez o Windows pode mostrar um aviso do SmartScreen: "Mais informações" → "Executar mesmo assim". |

A app avisa sozinha quando há uma versão nova.

## Ligar as contas

| Plataforma | Como |
|---|---|
| **Xbox** | Botão **Entrar com Xbox**, através do [OpenXBL](https://xbl.io) (serviço que dá acesso aos dados da Xbox Live). |
| **Steam** | Entrar com a Steam ou indicar o teu perfil. O perfil e os detalhes dos jogos têm de estar **públicos** nas definições de privacidade da Steam. |
| **RetroAchievements** | O teu nome de utilizador e a tua chave Web API (em retroachievements.org → Settings). |

---

## 🔒 Privacidade: não ficamos com os teus dados críticos

A app foi feita para que **os dados importantes nunca saiam do teu aparelho**.

### O servidor da Unlockify.Hub **nunca** recebe nem guarda
- ❌ As **chaves e sessões** das tuas contas (OpenXBL, Steam, RetroAchievements, Gemini, Ollama).
- ❌ **Palavras-passe** — a app nunca te pede a palavra-passe da Microsoft, da Steam ou da RetroAchievements; os logins são feitos nas páginas oficiais.
- ❌ O teu **email** ou dados de **pagamento**.
- ❌ As tuas **conquistas**, **jogos**, **horas jogadas** ou **estatísticas**.
- ❌ As tuas **notas pessoais**.
- ❌ A tua **Minha Biblioteca**, fotos e cópias de segurança.

O administrador da app **não tem acesso** às tuas contas nem a nenhum destes dados.

### O que fica só no teu aparelho
As chaves das contas, as listas de jogos e conquistas, as notas, a biblioteca (com fotos e capas), as definições, os guias gerados por IA e o registo de depuração 🐞 (que só sai do aparelho se tu o partilhares). Desinstalar a app apaga tudo isto — guarda antes uma cópia da biblioteca, se quiseres.

### Pedidos feitos diretamente pelo teu aparelho
Para mostrar os teus dados, a app fala **diretamente** com os serviços, sem passar pelo nosso servidor: OpenXBL (Xbox), Steam, RetroAchievements, Microsoft Store e loja Steam (capas e modos de jogo), UPCitemdb (códigos de barras), GitHub (atualizações) e, se usares a IA, o Ollama ou a Gemini que configurares. Cada serviço tem a sua própria política de privacidade.

### O pouco que vai para o servidor (só conteúdo partilhado)
O servidor existe apenas para o conteúdo que **tu escolhes partilhar** com a comunidade:

| O quê | O que é guardado | Porquê |
|---|---|---|
| **Dicas** que publicas | O texto, os avisos (missable, impossível, servidores desligados), votos e denúncias, com a tua **gamertag** e o **ID público da conta Xbox** | Mostrar quem escreveu e travar abusos. Podes apagar as tuas dicas quando quiseres. |
| **Códigos de barras** confirmados (opcional) | Código, nome do jogo, plataforma, região e capa — com um **resumo cifrado** do endereço de rede, nunca o endereço em si | Ajudar a app a reconhecer jogos para toda a gente. Pode ser desligado na biblioteca. |
| **Pesquisa de capas** | Só o nome do jogo pesquisado | Encontrar capas (IGDB). |
| **Lista de doadores** | Nome e mensagem **públicos** do Ko-fi | Agradecer a quem apoia. Sem email nem valores. |

A gamertag e o ID da conta Xbox são informação pública da Xbox Live e só são guardados se publicares uma dica.

---

## ☕ Apoiar

A app é feita por uma pessoa, nas horas livres, e é gratuita e sem publicidade. Se te tem sido útil, podes pagar um café:

<a href="https://ko-fi.com/Q1S129EGCF" target="_blank"><img src="https://storage.ko-fi.com/cdn/kofi2.png?v=3" height="36" alt="Apoia no Ko-fi"></a>

## Avisos

- A Unlockify.Hub é um projeto independente. **Não é afiliada, patrocinada nem aprovada** pela Microsoft/Xbox, Valve/Steam, RetroAchievements, Nintendo, Sony, SEGA, Google ou Ollama. Os nomes, logótipos e imagens dos jogos pertencem aos respetivos donos.
- Os dados de conquistas dependem dos serviços de cada plataforma; quando um serviço falha ou muda, alguns dados podem ficar temporariamente indisponíveis.
- Os guias gerados por IA podem conter erros: confirma sempre antes de seguir ou publicar.

## Problemas e sugestões

Encontraste um erro? Abre um **[Issue](../../issues)** e, se puderes, junta o registo de depuração: na app, botão 🐞 → Copiar.

---

<div align="center">

Feito por **Cappuccin0PT** com ajuda de **A.I**

</div>
