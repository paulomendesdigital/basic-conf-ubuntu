# Basic Conf Ubuntu

## Ajustes
Baixe `ajustes`
- Em `Barra superior` selecione `Percentagem de bateria` e `Data`
- Em `Energia` desselecione `Sespender quando a tampa do notebook é fechada`
- Em `Área de trabalho` desmarque `Lixeira`

## dconf
Baixe o `Editor dconf`

### Alt+tab
- retorne a `"home"` do `dconf` e pesquise por `keybindings` e selecione a opção que contém o caminho `/org/gnome/desktop/wm/keybindings`
- em `keybindings` procure e selecione a opção `switch-applications`
- desselecione a opção `Usar o valor padrão`
- no campo `Valor personalizado` recorte o valor `'<Alt>Tab'`, retire a `,` e salve
- volte ao `keybindings`, procure e selecione a opção `switch-windows`
- desselecione a opção `Usar o valor padrão`
- no campo `Valor personalizado` cole dentro dos colchetes cole o valor `'<Alt>Tab'` e salve
- volte ao `keybindings`, procure e selecione a opção `switch-applications-backward`
- desselecione a opção `Usar o valor padrão`
- no campo `Valor personalizado` recorte o valor `'<Shift><Alt>Tab'`, retire a `,` e salve
- volte ao `keybindings`, procure e selecione a opção `switch-windows-backward`
- desselecione a opção `Usar o valor padrão`
- no campo `Valor personalizado` cole dentro dos colchetes cole o valor `'<Shift><Alt>Tab'` e salve

### Overview
- pesquise por `dash-to-dock`
- em `dash-to-dock` procure por `click-action` desmaque a opção `Usar o valor padrão` e em `Valor personalizado` selecione a opção `'minimize-or-overview'`
