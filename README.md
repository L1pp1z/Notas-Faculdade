Para ler o projeto de uma forma melhor utilize o modo leitura do obsidian ou simplesmente o atalho `ctrl + E` para alternar entre os modos de visualização

Utilizo as seguintes configurações no OBSIDIAN.  Temas e Plugins podem ser baixados pelo próprio OBSIDIAN
#### TEMAS:
Lumines:
`https://github.com/danielkhmara/obsidian-lumines`
NovaDust:
`https://github.com/mmartamg/novadust-obsidian`
Encore:
`https://github.com/Carbonateb/obsidian-encore-theme`
Vicious:
`https://github.com/zaheralmajed/vicious-theme-obsidian`

---
#### FONTES:
Jetbrain Nerd Font:
`https://github.com/mmartamg/novadust-obsidian`
`https://www.jetbrains.com/lp/mono/`

---
#### PLUGINS:
Code Styler: Modifica a visualização dos códigos dentro das caixas
`https://github.com/mayurankv/Obsidian-Code-Styler`

Style Settings: Ajusta as configurações dos temas
`https://github.com/obsidian-community/obsidian-style-settings`

Iconize: Permite adicionar ícones nas notas e pastas
`https://github.com/FlorianWoelki/obsidian-iconize`

Colored Text: Permite adicionar cores em textos
`https://github.com/erincayaz/obsidian-colored-text`

Multi-Column: Permite criar caixas na mesma coluna / linha com conteúdos separados
`https://github.com/ckRobinson/multi-column-markdown`

---
#### Snippets
Para centralizar as imagens dentro do obsidian você precisa criar um `.css` seguindo:

- Vá para Configurações > Aparência > Snippets de CSS e clique no ícone de pasta.
- Crie um novo arquivo (ex: centralizar-imagens.css) com o seguinte código:
```css title:Centralizar_Imagens
img {
  display: block !important;
  margin-left: auto !important;
  margin-right: auto !important;
}

.markdown-source-view.mod-cm6 .cm-content > * {
  margin: auto auto !important;
}
```
- Retorne ao Obsidian, clique no botão atualizar na seção de Snippets de CSS.
- Ative o botão ao lado do arquivo que você criou

Adicione o parâmetro na imagem: Use a sintaxe `![[nome-do-arquivo|center]]` na sua nota