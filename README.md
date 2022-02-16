
<h1 align="center"> lambda :books: </h1>
<h4 align="center"> 
	🚧  Status 🚀 Em construção...  🚧
</h4>

**Serverless** são arquiteturas que nos permitem executar funções na nuvem sem necessidade de configuração do servidor.
Neste repositório será construido uma função serverless simples que manipula e otimiza imagens que foram enviadas ao Amazon S3 utilizando AWS Lambda.

## :warning: Desconstruindo mitos: :warning:
-  Mesmo o nome sendo serverless(computação sem servidor) existe servidor sim, ele só não precisa ser gerenciado, o que torna a configuração e o deploy muito mais simples;
- Você não irá ganhar performance apenas por utilizar essa arquitetura e nem terá custos mais baixos, isso depende muito do tipo de aplicação;
- Hospedar servidores HTTP completos com múltiplas responsabilidades não é o caso de uso para esse tipo de arquitetura;

## :heavy_check_mark: Vantagens do Serverless :heavy_check_mark:

- Não precisamos configurar o servidor;
- Extremamente barato;
- Escalabilidade automática
- Deploy muito simples

## :x: Desvantagens do Serverless :x:

- Execuções espaçadas criam o servidor do zero, realizando cold-starts da aplicação que podem ocasionar perda de performance momentânea;
- As funções executadas jamais podem passar de 300 segundos de execução, e se chegar perto disso o custo começa a aumentar bastante;
- O debugging e teste das funções serverless é extremamente difícil, ainda mais quando essas dependem de eventos que ocorrem em outros serviços;
- Utilizado da forma errada o custo é maior que servidores cloud comuns já que serviços serverless não são criados para aplicações com execuções constantes;

:purple_circle: Fonte : https://blog.rocketseat.com.br/serverless-nodejs-lambda/
