# 286_PublicandoAPIRESTNuvemUsandoSpringBoot3Java17Railway


Publicando Sua API REST na Nuvem Usando Spring Boot 3, Java 17 e Railway



- CONTEÚDOS
- INFORMAÇÕES

###### DESCRIÇÃO

Vamos mergulhar diretamente no universo do desenvolvimento e construir uma API REST do zero! E o melhor de tudo, faremos isso utilizando o Java 17, a versão LTS mais recente que está recheada de novidades empolgantes. Para tornar a nossa jornada ainda mais produtiva, vamos empregar o poder do Spring Boot 3, que é amplamente conhecido por potencializar a produtividade dos desenvolvedores através de sua incrível capacidade de autoconfiguração. Mas não para por aí, vamos simplificar ainda m



https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/138c435a-5be5-450b-a292-cf6ea002f54c



[**](https://web.dio.me/play)

##### Publicando Sua API REST na Nuvem Usando Spring Boot 3, Java 17 e Railway

**

[**](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/138c435a-5be5-450b-a292-cf6ea002f54c)[**](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/7dc1b5d6-8b18-4df2-98c4-15de3939f2b7)

<iframe id="ytc44" frameborder="0" allowfullscreen="1" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture; web-share" title="O Que Vamos Desenvolver Neste Lab" width="100%" height="100%" src="https://www.youtube.com/embed/xcuQ4Y4uyo4?controls=0&amp;disablekb=1&amp;enablejsapi=1&amp;fs=0&amp;iv_load_policy=3&amp;modestbranding=1&amp;showinfo=0&amp;rel=0&amp;html5=1&amp;cc_load_policy=0&amp;origin=https%3A%2F%2Fweb.dio.me&amp;widgetid=1" data-gtm-yt-inspected-18="true" style="box-sizing: inherit; max-width: none; float: none; margin: 0px; padding: 0px; border: 0px; font-style: inherit; font-variant: inherit; font-weight: inherit; font-stretch: inherit; line-height: inherit; font-family: inherit; font-optical-sizing: inherit; font-kerning: inherit; font-feature-settings: inherit; font-variation-settings: inherit; font-size: 14px; vertical-align: baseline;"></iframe>



02:32

 

04:45







normal

auto

- CONTEÚDOS
- INFORMAÇÕES

[O Que Vamos Desenvolver Neste Lab](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/138c435a-5be5-450b-a292-cf6ea002f54c)[Criação e Importação do Projeto](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/7dc1b5d6-8b18-4df2-98c4-15de3939f2b7)[Versionamento no GitHub](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/1b90b69a-9370-46d2-9869-93de18387650)[Abstração Inicial do Domínio no Figma](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/b32fd907-83ca-41be-94df-4e72de4c6778)[Diagrama de Classes com ChatGPT e Mermaid](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/b691c616-158b-4190-a441-37ed64b6190c)[Mapeamento Objeto Relacional (ORM)](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/8cbc75c7-b3da-4b64-8ed3-218b641938af)[Hotfix 'precision' e 'scale'](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/58f67227-171f-4976-a282-16bd038adb21)[Implementando a Camada de Negócio](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/52a03fbf-177e-4f95-b78b-1d57a6a392d5)[Expondo Endpoints REST e Testando a API](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/ff0d69d7-4cd5-4325-8ce1-a21afc4c7a9b)[Tratamento de Exceções em APIs REST](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/5808de33-b972-4109-a589-6dee94f5a9ec)[Provisionando o PostgreSQL (Railway) e Criando o Perfil de PRD](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/4dc5ad1f-6d76-4acf-8428-3db18d2d28e1)[Deploy da API na Nuvem (Railway)](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/a877f74a-963e-4d9d-808b-75c096a76973)[Correção de CORS e Conclusão](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/47b4db14-8628-446f-9d82-840805929619)[Desafio! Crie a Sua Própria API](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/0621f652-d5e4-4918-8a47-1d400190a344)[Entendendo o Desafio](https://web.dio.me/lab/publicando-sua-api-rest-na-nuvem-usando-spring-boot-3-java-17-e-railway/learning/ad7b622c-6ca0-4000-bf7b-2939591221ed)



# Entendendo o Desafio

**Agora é a sua hora de brilhar e construir um perfil de destaque na DIO! Explore todos os conceitos explorados até aqui e replique (ou melhore, porque não?) este projeto prático. Para isso, crie seu próprio repositório e aumente ainda mais seu portfólio de projetos no GitHub, o qual pode fazer toda diferença em suas entrevistas técnicas** 😎

Já dominamos o universo do desenvolvimento e construímos uma API REST utilizando o Java 17, a versão LTS mais recente repleta de novidades. Com o poder do Spring Boot 3, otimizamos nossa produtividade graças à sua habilidade de autoconfiguração. Além disso, facilitamos o acesso aos bancos de dados SQL com o auxílio do Spring Data JPA. Também destacamos a importância de uma documentação de API robusta e clara, utilizando o OpenAPI, ou Swagger. E com o Railway, simplificamos o Deploy de nossas soluções na nuvem. Agora, é hora de embarcar em um novo desafio e explorar um domínio de aplicação diferente, mantendo nosso foco em inovar e desenvolver soluções de alto padrão!

## **Repositórios Git**

O Git é um conceito essencial no mercado de trabalho atualmente, por isso sempre reforçamos sua importância em nossa metodologia educacional. Por isso, todo código-fonte desenvolvido durante este conteúdo foi versionado usando :

1. **[github.com/falvojr/santander-dev-week-2023](https://github.com/falvojr/santander-dev-week-2023)**: Repositório com todo o código-fonte desenvolvido neste Desafio de Projeto (Lab);
2. **[github.com/digitalinnovationone/santander-dev-week-2023-api](https://github.com/digitalinnovationone/santander-dev-week-2023-api)**: Aqui você tem acesso a uma versão mais robusta desta mesma API, com melhorias e padrões adicionais implementados. Se quiser se desafiar e buscar uma referência mais completa, este é o caminho!

Bons estudos 😉

 





