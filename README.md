# Tradução PT-BR - The Turing Test

Tradução para Português do Brasil (PT-BR) das legendas/diálogos do jogo **The Turing Test**.

---

## 🎯 Status do Projeto

- [x] **`subtitles.csv` (Legendas e Diálogos):** 100% Traduzido, revisado e testado.
- [x] **`credits.csv` (Créditos):** 100% Traduzido, revisado e testado.
- [ ] **`translations.csv` (Menu / Interface):** Incluído no repositório para testes, mas **não funcional** no jogo final até o momento.

---

## 📂 Diretório de Instalação

Para aplicar a tradução, os arquivos `.csv` extraídos devem ser copiados para a pasta **`CSV`** do jogo, dependendo do seu sistema operacional:

### 🐧 Linux (Nativo / Proton / Steam Deck)
```
~/.steam/root/steamapps/common/The Turing Test/TheTuringTest/TextContent/CSV/
```
(Nota: O caminho pode variar dependendo da sua biblioteca Steam ou distribuição, como no Bazzite/Flatpak).

### 🪟 Windows
```
C:\Program Files (x86)\Steam\steamapps\common\The Turing Test\TheTuringTest\TextContent/CSV/
```
**Dica no Windows/Linux:** Você pode encontrar a pasta rapidamente abrindo a Steam, clicando com o botão direito em The Turing Test > Gerenciar > Navegar pelos arquivos locais e depois acessando a pasta TheTuringTest/TextContent/CSV/.

## ⚙️ Instruções de Instalação
1. Acesse a aba Releases na lateral direita deste repositório e baixe o arquivo .zip mais recente.

2. Extraia o conteúdo do arquivo comprimido.

3. Copie os arquivos .csv e cole dentro da pasta TextContent/CSV/ do jogo, substituindo os arquivos originais (recomenda-se fazer um backup dos originais antes).

4. Inicie o jogo e certifique-se de que as Legendas estejam ativadas nas configurações de vídeo.

## 🔍 Processo de Tradução e Qualidade
A tradução foi gerada com auxílio de Inteligência Artificial e passou por uma etapa de refinamento estruturado:

- **Validação Estrutural:** Checagem linha a linha para garantir que as chaves de texto e o formato dos arquivos .csv fossem mantidos intactos.

- **Adaptação Contextual:** Polimento nos diálogos para remover construções ríspidas ou traduções literais, buscando manter a fluidez e o tom natural das conversas em português.

## 🛠️ Notas Técnicas e Limitações (Menu Principal)
Durante os testes práticos no jogo, a substituição do arquivo translations.csv não alterou os elementos textuais da interface do menu principal (como Settings, New Game, etc.), que continuam sendo exibidos em inglês.

- **Comportamento Observado:** O executável do jogo não aplica as alterações feitas no translations.csv para a interface principal em runtime.

- **Hipótese Técnica:** É possível que as strings do menu estejam contidas ou sobrescritas diretamente dentro dos assets empacotados da Unreal Engine 4 (.uasset / .pak), exigindo extração e reempacotamento via ferramentas de modding avançadas (como FModel, UAssetGUI ou UABE).

🤝 **Contribuições:** Se você possui experiência em modding de Unreal Engine 4 e souber como contornar essa limitação para traduzir a UI, sinta-se à vontade para abrir uma Issue ou submeter um Pull Request.
