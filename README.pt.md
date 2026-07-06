# ThermalLabeler

**ThermalLabeler** é um aplicativo para Android que permite imprimir em impressoras térmicas sem depender de drivers proprietários do fabricante.

<p align="center">
  <img src="images/roll.jpg" alt="Receipt roll" width="300">
</p>

Importante: o aplicativo foi desenvolvido exclusivamente para impressoras térmicas que suportam os modos <b>TSPL</b> e/ou <b>ESC/POS</b>:
<ul>
  <li><b>TSPL</b> - usado para imprimir etiquetas autoadesivas
  <li><b>ESC/POS</b> - usado para imprimir em papel térmico em rolo (recibos, comprovantes, senhas e outros documentos)
</ul>
O aplicativo não foi desenvolvido para impressoras convencionais de escritório, jato de tinta, laser ou outros tipos de impressoras e não funciona com elas. Apenas impressoras térmicas com interface de impressão compatível com <b>TSPL</b> e/ou <b>ESC/POS</b> são suportadas.
<BR>
<BR>O aplicativo atua como uma ponte entre o Android e a impressora térmica, oferecendo controle total sobre a impressão de etiquetas e documentos em papel térmico em rolo quando as soluções padrão não funcionam ou impõem limitações. Ele resolve um problema prático: como imprimir uma etiqueta ou um documento a partir de um telefone ou tablet em uma impressora térmica compatível.
<BR>
<BR>Antes da impressão, o conteúdo do arquivo é convertido automaticamente em uma imagem rasterizada.
<BR>Ao imprimir etiquetas, a imagem rasterizada é ajustada ao tamanho real da etiqueta levando em consideração a orientação, as margens e as configurações da impressora. Ao imprimir em uma impressora de recibos, a imagem rasterizada resultante é ajustada à largura do papel.

---

## Modelos de etiquetas

O programa permite criar e salvar vários modelos de etiquetas com diferentes tamanhos e configurações de impressão.

Cada modelo contém um conjunto de propriedades:

- largura e altura da etiqueta
- espaço entre etiquetas (*gap*)
- deslocamento
- orientação e rotação
- parâmetros de alinhamento
- pré-impressão (área não imprimível)

Os modelos criados podem ser reutilizados e permitem alternar rapidamente entre diferentes tipos de etiquetas sem necessidade de reconfiguração.

---

## Impressão direta

A impressão é realizada diretamente por meio de:

- Bluetooth
- USB
- Wi-Fi

O aplicativo suporta a abertura de arquivos (PDF, HTML e imagens) diretamente pelo sistema Android.

Ao selecionar **"Abrir com"** ou **"Compartilhar"**, o arquivo é automaticamente carregado no aplicativo e preparado para impressão.

---

## Integração com o Android PrintService

O programa funciona como um Android PrintService:

- disponível na caixa de diálogo padrão **"Imprimir"**
- pode ser utilizado por qualquer aplicativo (sistemas de vendas, navegadores, visualizadores de PDF etc.)

---

## Formatos de arquivo suportados

O programa permite abrir e imprimir etiquetas a partir dos seguintes tipos de arquivo:

- **PDF** — documentos e layouts gerados por outros aplicativos ou sistemas
- **HTML** — páginas e modelos, incluindo relatórios e etiquetas de preço gerados automaticamente
- **Imagens** — PNG, JPG e outros formatos populares

---

## Histórico de impressão

O programa mantém um histórico dos trabalhos de impressão realizados.

Para cada trabalho são armazenados:

- arquivo de origem
- parâmetros de impressão

A partir do histórico, é possível reabrir um trabalho e realizar uma nova impressão sem precisar selecionar novamente o arquivo ou configurar os parâmetros.

---

## O que diferencia das soluções tradicionais

- sem emulação de A4
- sem dependência de uma única marca de impressora
- impressão precisa de etiqueta para etiqueta
- controle completo de todo o fluxo de impressão
- ideal para armazéns, lojas, logística e rotulagem

---

## Cenários típicos de uso

- impressão de etiquetas de preço e códigos de barras
- impressão de etiquetas para estoque e transporte
- impressão a partir de sistemas comerciais
- impressão a partir de aplicativos Android personalizados
