# CheckTI — Checklist inicial de suporte

Projeto de estudo para praticar HTML, CSS e JavaScript com foco em suporte técnico de computadores.

## Demonstração

Depois de ativar o GitHub Pages nas configurações deste repositório, a demonstração ficará disponível em:

https://vinicius589.github.io/CheckTI/

## O que faz

A pessoa descreve o problema com as próprias palavras. O JavaScript compara a descrição com palavras-chave e seleciona uma checklist inicial para um dos tipos de problema previstos:

- Computador que não liga
- Computador lento ou travando
- Falta de internet
- Falta de áudio
- Computador liga, mas não aparece imagem
- Aquecimento ou desligamento inesperado
- Teclado, mouse ou touchpad sem funcionar

Também é possível escolher um caso comum pelos botões. Cada etapa pode ser marcada e a página mostra o progresso da checklist.

## Tecnologias

- **HTML:** estrutura da página e formulário.
- **CSS:** aparência e adaptação para telas menores.
- **JavaScript:** leitura da descrição, identificação por palavras-chave, criação dos passos e atualização do progresso.

Não usa banco de dados, login, servidor, biblioteca externa ou API de inteligência artificial. A identificação usa regras simples e palavras-chave cadastradas no código, por isso não reconhece todas as formas de descrever um problema nem cria diagnósticos novos.

## Como executar localmente

1. Baixe ou clone este repositório.
2. Abra o arquivo `index.html` no navegador.
3. Descreva o sintoma e clique em **Montar checklist**, ou selecione um caso comum.
4. Marque cada etapa depois de realizar a verificação.

## O que estudar no código

- Como o formulário recebe a descrição.
- Como a função `normalizarTexto` trata acentos e letras maiúsculas.
- Como `identificarProblema` compara o texto com palavras-chave.
- Como o objeto `problemas` guarda os passos de cada caso.
- Como `addEventListener` reage a envios, cliques e marcações.
- Como a barra de progresso é atualizada.

## Segurança e limitações

As etapas são verificações iniciais, não um diagnóstico definitivo. Não abra a fonte de alimentação nem mexa em componentes internos com o equipamento ligado. Se houver cheiro de queimado, líquido, faíscas, cabos danificados ou aquecimento extremo, interrompa os testes e procure assistência qualificada.

## Autor

Vinicius da Motta Campos — projeto de portfólio para praticar desenvolvimento web básico.
