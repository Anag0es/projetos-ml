# Generative Adversarial NN para linha de roupa 👔🩳🧤
Para ampliar os conhecimentos, o projeto a seguir utiliza a *rede adversária generativa (GAN)* para explorar os diversos campos da deep learning. Nesse projeto iremos construir uma linha de roupas com o uso da GAN.

- Foi utilizado o seguinte vídeo como guia para o projeto: [vídeo](https://www.youtube.com/watch?v=AALBGpLbj6Q)

### GAN 🥇
Sendo uma arquitetura de aprendizado profundo, nela é treinada duas redes neurais que são colocadas uma contra a outra para gerar dados mais autênticos a partir de um conjunto de dados. 

- Introduzidas em 2014 por meio de um artigo de Ian Goodfellow e outros pesquisadores da universidade de Montreal;

#### Algoritmos discriminativos vs generativos
Entendendo um pouco mais do funcionamento da rede adversária é preciso saber que as redes que competem entre si tem cada uma sua função. 

- Rede Discriminativa: classificam os dados de entrada, ou seja, eles tentam prever algum rótulo ou categoria que os dados estão;
- Rede Generativa: eles fazem o contrário, ou seja, tentam prever os recursos (dados) com base nos rótulos.

Exemplo: Discriminativo tenta prever se a mensagem é ou não spam, já o Generativo tenta a partir do e-mail sendo spam qual a probabilidade do conjunto de palavras com um rótulo ou categoria.

#### Funcionamento
- A rede neural geradora analisa o conjunto de treinamento e identifica os atributos dos dados;
- A rede neural discriminadora também analisa os dados do treinamento inicial e distingue os atributos de forma independente;
- A geradora modifica alguns atributos de dados adicionando ruído (ou alterações aleatórias) a determinados atributos;
- A geradora passa os dados modificados para a discriminadora;
- A discriminadora calcula a probabilidade de que a saída gerada pertença ao conjunto de dados original;
- A discriminadora fornece algumas orientações à geradora para reduzir a randomização do vetor de ruído no próximo ciclo. [amazon](https://aws.amazon.com/pt/what-is/gan/)


A GAN é muito utilizada nos seguintes casos:
- Gerar imagens: Como a imagem criada pela Christie's, sendo um dos primeiros quadros criados por GAN. [Chritie's](https://www.theverge.com/2018/10/25/18023266/ai-art-portrait-christies-obvious-sold)
- Gerar dados para outros modelos: Aumentar os dados sintéticos, ajudando sistemas com modelos preditivos;
- Preencher informações faltantes: Dar mais precisão aos modelos preenchendo informações incompletas nos dados.


## Requisitos 📑
Ambiente de desenvolvimento: Vs Code | Jupyter | Google colab
tecnologia: Ao longo do notebook é dito quais e como devem ser instaladas

## Status do projeto 🌱
Em constante progesso...

## Contribuições 🤝
Contribuições são bem-vindas! Se você encontrar problemas, bugs ou tiver sugestões de melhorias, fique à vontade para abrir issues neste repositório. Se deseja contribuir com código, crie uma solicitação pull, e eu ficarei feliz em analisar.

## Recursos Adicionais 📚
- Passo a passo do modelo: [video](https://www.youtube.com/watch?v=AALBGpLbj6Q)
- Como funcionam as GAN: [deeplearningbook](https://www.deeplearningbook.com.br/introducao-as-redes-adversarias-generativas-gans-generative-adversarial-networks/)
- Livro MIT sobre deeplearning: [livro](https://www.deeplearningbook.org/)

## Sobre o Autor 👩‍💻
Técnica em Desenvolvimento de Sistemas, Bacharelado em Ciência da Computação 3/8. Apaixonada por tecnologia voltada para o desenvolvimento back-end e inteligência artificial. Programar é meu hobby e criar bancos de dados é minha paixão.

## Contato 📞
Você pode entrar em contato comigo
- [Linkedin](https://www.linkedin.com/in/ana-luisa-goes-barbosa/)
- Gmail: analuisa.goes2004@gmail.com
- [Instagram](https://www.instagram.com/ana_g0es/)
