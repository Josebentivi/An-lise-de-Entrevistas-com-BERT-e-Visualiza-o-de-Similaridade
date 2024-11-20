# Análise de Entrevistas com BERT, Kmeans e Visualização de Similaridade

## Integrantes

João José Cunha Melo e Sousa Bentivi - 10395405

Pedro Henrique Rocha - 10396190

Gabriel Meylan Gadelha - 10395945

Guilherme Guimarães Chiarelli - 10374662

## Descrição do Projeto

Este projeto utiliza a biblioteca BERT para realizar análise de sentimentos em entrevistas, além de calcular a similaridade semântica entre elas usando a similaridade cosseno. Os resultados são visualizados através de gráficos, incluindo histogramas de sentimentos e matrizes de calor para similaridades.

## Funcionalidades

- **Transcrição de entrevistas**: Utiliza a biblioteca Whisper para transcrever as entrevistas.
- **Análise de Sentimentos**: Identifica e classifica o sentimento predominante em cada resposta das entrevistas.
- **Cálculo de Similaridade**: Avalia a similaridade cosseno entre embeddings de entrevistas.
- **Visualização**: Gera gráficos que mostram a distribuição de sentimentos e a similaridade entre entre diversos textos.

## Motivação

Nos últimos anos, o campo do Processamento de Linguagem Natural (PLN) tem experimentado avanços significativos, impulsionados pelo desenvolvimento de modelos de aprendizado profundo. Dentre esses modelos, o BERT (Bidirectional Encoder Representations from Transformers), proposto por Devlin et al. (2018), destaca-se por sua capacidade de capturar detalhes contextuais em textos, graças à sua arquitetura baseada em transformadores. 

A análise de entrevistas é uma metodologia amplamente utilizada em pesquisas qualitativas, permitindo a coleta de dados ricos em informações sobre percepções, experiências e comportamentos humanos. No entanto, o processo de transcrição e análise manual dessas entrevistas pode ser demorado e sujeito a vieses interpretativos. Nesse contexto, a aplicação de técnicas avançadas de PLN pode otimizar esse processo, fornecendo insights mais precisos e agilizando a interpretação dos dados.

Este trabalho explora o uso da biblioteca Wisper e BERT na análise de entrevistas em língua portuguesa, visando aprimorar a extração de informações e a compreensão dos conteúdos abordados. Ao aplicar o BERT, buscamos identificar padrões semânticos e temáticos nas respostas dos entrevistados, proporcionando uma análise mais profunda e automatizada.

## Dados coletados

Foram coletadas 40 entrevistas que seram utilizadas para validação de um aplicativo chamado DreamSteps.

## Transcrição

No processo de análise de entrevistas, a transcrição precisa e eficiente dos áudios para texto é uma etapa crucial. É aqui que entra em cena o modelo Whisper, desenvolvido pela OpenAI, que oferece uma solução poderosa para a transcrição automática de áudio em texto. Whisper é um modelo de reconhecimento de voz open-source que tem demonstrado alta precisão em diversas línguas e ambientes ruidosos, tornando-o ideal para a transcrição de entrevistas conduzidas em diferentes contextos.

Ao utilizar o Whisper, o áudio das entrevistas é convertido em texto de forma rápida e precisa. Isso não só reduz consideravelmente o tempo necessário para transcrição manual, mas também minimiza os erros humanos associados a esse processo. Whisper se destaca pela sua capacidade de entender fala contínua e variabilidades de sotaque, que são comuns em entrevistas, garantindo que o output textual represente fielmente o conteúdo falado.

Uma vez que as entrevistas são transcritas com Whisper, os textos resultantes servem como input para o modelo BERT, que irá realizar a análise semântica. Com os textos transcritos, o BERT poderá aplicar técnicas de Processamento de Linguagem Natural (PLN) para identificar temas, emoções e padrões linguísticos nas respostas dos entrevistados, enriquecendo a análise qualitativa com insights que podem não ser imediatamente aparentes em uma leitura convencional.

## Tecnologias Utilizadas

- Python
- OpenAi
- Transformers (Hugging Face)
- PyTorch
- Scikit-learn
- Matplotlib
- Seaborn
- Kmeans

## Projeto

- No notebook Análise de entrevista.ipynb
