# Detector de bordas de Canny
## Canny edge detector

Desenvolvido por John F. Canny em 1986 o detector de bordas de Canny utiliza um algoritmo multi-estágios para detectar uma ampla margem de bordas na imagem. Canny também desenvolveu uma teoria computacional sobre detecção de bordas explicando porque as técnicas funcionam.
John Canny propôs que o detector de bordas ótimo deveria respeitar os seguintes parâmetros:

-- Boa Detecção - O algoritmo deve ser capaz de identificar todas as bordas possíveis na imagem.

-- Boa Localização - As bordas encontradas devem estar o mais próximo possível das bordas da imagem original.

-- Resposta Mínima - Cada borda da imagem deve ser marcada apenas uma vez. O ruído da imagem não deve criar falsas bordas.

Para satisfazer tais condições, Canny utilizou um cálculo de variações, visando encontrar uma função que otimizasse o funcional desejado. A função ideal para o detector de Canny é descrito pela soma de quatro termos de exponenciais, que pode ser aproximada pela primeira derivada de uma gaussiana.

[Wikipédia](https://pt.wikipedia.org/wiki/Detector_de_bordas_de_Canny)

# Implementação baseada no livro: "OpenCV Android Programming By Example" de Amgad Muhammad

## Imagens do app
<a href="url"><img src="https://github.com/fabriicioa/cannyDeteccaoDeBordas/blob/master/Arquivos/img1.png" align="left" height="480" width="260" ></a>
<a href="url"><img src="https://github.com/fabriicioa/cannyDeteccaoDeBordas/blob/master/Arquivos/img2.png" align="center" height="480" width="300" ></a>
<a href="url"><img src="https://github.com/fabriicioa/cannyDeteccaoDeBordas/blob/master/Arquivos/img3.png" align="right" height="480" width="260" ></a>

## Contribua

Fique à vontade para contribuir com o projeto, toda contribuição é bem vinda. :grin:

Se você tem dúvida de como contribuir, dê uma olhada no arquivo [CONTRIBUA](https://github.com/fabriicioa/cannyDeteccaoDeBordas/blob/master/Contribuindo.pdf)

