# ARJimg - Compressão de Imagens
Bem-vindo ao repositório do ARJimg, um compactador de imagens eficiente desenvolvido em C++. 
Este projeto visa oferecer uma solução robusta para a compactação de imagens, facilitando a redução do tamanho de arquivos sem perda significativa de qualidade visual. 
Ideal para desenvolvedores, designers, fotógrafos e qualquer pessoa que precise otimizar o armazenamento e compartilhamento de imagens.

## Características
- **Suporte a Múltiplos Formatos:** ARJimg suporta os formatos de imagem mais comuns, incluindo JPG, PNG e GIF, proporcionando versatilidade no uso.
- **Alta Eficiência de Compactação:** Com algoritmos avançados, o ARJimg é capaz de minimizar o tamanho do arquivo mantendo a máxima qualidade visual possível.
- **Desenvolvido em C++:** Aproveita a eficiência e velocidade de processamento da linguagem C++, garantindo uma operação rápida e segura.
- **Compactação em Lote:** Oferece a capacidade de processar várias imagens simultaneamente, economizando tempo e esforço dos usuários.

## O que é Qualidade de Compressão?
A qualidade de compressão é um parâmetro que determina o equilíbrio entre o tamanho do arquivo comprimido e a fidelidade visual da imagem. Ela representa a quantidade de detalhes que serão preservados na imagem após a compressão.

## Como Funciona?
Ao comprimir uma imagem, o algoritmo de compressão reduz a quantidade de dados armazenados na imagem. Isso pode ser feito removendo detalhes menos importantes, reduzindo a precisão de certos componentes da imagem ou aplicando técnicas de compactação.

## Impacto na Qualidade Visual
- Alta Qualidade (Próximo de 100%): Quanto mais próximo de 100% for o nível de qualidade de compressão, menor será a perda de detalhes visuais. A imagem comprimida será visualmente semelhante à imagem original, mas o tamanho do arquivo será maior.
- Baixa Qualidade (Próximo de 0%): À medida que o nível de qualidade de compressão se aproxima de 0%, a perda de detalhes visuais se torna mais perceptível. A imagem comprimida terá uma qualidade inferior, com artefatos visuais e perda de nitidez, mas o tamanho do arquivo será menor.

## Escolhendo o Nível de Qualidade
A escolha do nível de qualidade de compressão depende das necessidades específicas do usuário e do contexto de uso da imagem. Para imagens onde a fidelidade visual é crucial, como fotografias de alta resolução ou imagens médicas, é recomendável usar um nível de qualidade mais alto. Por outro lado, para imagens onde o tamanho do arquivo é mais importante do que a qualidade visual, como imagens em páginas da web, um nível de qualidade mais baixo pode ser aceitável.

## Como Usar
Para usar este utilitário, siga estas etapas:

1. Baixe o executável do programa.
```bash
git clone https://github.com/acranerafael/arjimg.git .
```
2. Execute o programa em seu terminal ou prompt de comando, fornecendo o caminho para o diretório de entrada contendo as imagens que você deseja comprimir e o caminho para o diretório de saída onde as imagens comprimidas serão salvas.
```bash
./arjimg pasta_com_as_imagens pasta_que_receberá_as_novas_imagens
```
3. O programa solicitará que você insira a qualidade de compressão desejada (0-100). Você também pode simplesmente pressionar <**Enter**> para usar a qualidade padrão (70).   

## Contribuições
Queremos aprimorar o ARJimg e valorizamos suas contribuições! Se você possui ideias ou sugestões que podem aprimorar esta ferramenta, por favor, considere colaborar conosco no projeto. Apesar de o código fonte não estar aberto, seu feedback e sugestões são extremamente importantes para nós. 
Não hesite em compartilhar suas opiniões abrindo um (**issues**). Estamos ansiosos para ouvir sua opinião!

## Licença
O ARJimg é distribuído sob a **Licença Apache-2.0**, a qual permite o uso, modificação e distribuição do software de forma gratuita, tanto para fins comerciais quanto não comerciais. 
Para mais detalhes sobre a licença e permissões de uso, por favor, consulte  [Licença Apache-2.0](LICENSE).

---

*Agradecemos seu interesse no ARJimg e esperamos que a ferramenta seja de grande utilidade para seus projetos!*
