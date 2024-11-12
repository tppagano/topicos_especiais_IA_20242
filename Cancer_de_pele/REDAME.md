# Conjunto de Dados HAM10000: Imagens Dermatoscópicas para Diagnóstico de Lesões Cutâneas

O conjunto de dados HAM10000 ("Human Against Machine with 10000 training images") oferece uma ampla coleção de imagens dermatoscópicas para apoiar pesquisas de diagnóstico automatizado de lesões de pele. Esse conjunto foi criado para superar desafios relacionados ao tamanho reduzido e à falta de diversidade dos dados disponíveis na área, reunindo 10.015 imagens de diferentes populações e utilizando diversas modalidades de aquisição.

### Principais Características
- **Quantidade de Imagens**: 10.015 imagens dermatoscópicas para treinamento, representando uma diversidade de lesões cutâneas.
- **Categorias Diagnósticas**: Inclui todos os principais tipos de lesões pigmentadas, como:
  - Ceratoses actínicas e carcinoma intraepitelial (akiec)
  - Carcinoma basocelular (bcc)
  - Lesões benignas semelhantes a ceratoses (bkl)
  - Dermatofibroma (df)
  - Melanoma (mel)
  - Nevos melanocíticos (nv)
  - Lesões vasculares (vasc)
- **Validação**: Mais de 50% dos diagnósticos confirmados por histopatologia; os demais foram verificados por exames de acompanhamento, consenso de especialistas ou microscopia confocal.
- **Metadados**: Lesões com múltiplas imagens podem ser rastreadas pela coluna `lesion_id` no arquivo `HAM10000_metadata`.

### Uso
Este conjunto de dados é destinado a fins acadêmicos e ao treinamento de modelos de aprendizado de máquina na área de dermatologia. 
