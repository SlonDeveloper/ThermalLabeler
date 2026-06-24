# ThermalLabeler

**ThermalLabeler** é um utilitário para impressão de etiquetas em impressoras térmicas a partir do Android, sem dependência de um fabricante específico e sem necessidade de drivers proprietários.

Importante: o aplicativo foi desenvolvido exclusivamente para uso com impressoras térmicas de etiquetas que suportam o modo TSPL.  
O programa não foi projetado para impressoras de escritório comuns, jato de tinta, laser, impressoras de recibos ou outros tipos de impressoras e não funciona com elas.  
Se a sua impressora não for destinada à impressão em etiquetas autoadesivas ou não oferecer suporte à linguagem de comandos TSPL, o aplicativo não poderá realizar a impressão.

O programa atua como uma ponte entre o Android e a impressora térmica, oferecendo controle total sobre a impressão de etiquetas onde as soluções padrão não funcionam ou impõem limitações.

O aplicativo resolve uma necessidade prática:  
como imprimir uma etiqueta a partir de um telefone ou tablet em uma impressora térmica comum no modo TSPL.

Antes da impressão, o conteúdo do arquivo é automaticamente convertido em um layout rasterizado, dimensionado para o tamanho real da etiqueta e preparado de acordo com a orientação, margens e parâmetros da impressora.

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
