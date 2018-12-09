
# EduMap

## Educação Inteligente para Vidas Inteligentes

#### Sobre nós
Por meio da consulta e análise de dados oficiais, tais como Censo Escolar, IDEB e Desempenho dos estudantes do ENEM, além de dados retroalimentados por estudantes do Ensino Médio de todo o Brasil, gestores das Secretarias de Educação podem embasar seus Planejamentos Estratégicos de Implementação do Novo Ensino Médio, criando currículos e ofertas de Itinerários Formativos mais condizentes com a realidade de seus estados a partir do perfil do corpo docente e dos estudantes, caminhando rumo a um projeto de educação construído colaborativa e democraticamente!
___
## Nosso site
Acesse nosso site em http://edumap.surge.sh/

---

## Informações Técnicas
### Backend 
- Jupyter script pode ser rodado em:[https://ec2-18-213-151-47.compute-1.amazonaws.com:9443/hub/login](https://ec2-18-213-151-47.compute-1.amazonaws.com:9443/hub/login): edumap_merge.ipynb dentro da pasta jupiter_scripts
- Use usuário: **g30** e  senha: **dreamed885** para fazer o login
- Fizemos 3 tabelas e estas tabelas por fim são consumidas pelo Tableout para geração dos gráficos.
- Nós criamos tabelas Hive que foram geradas através de arquivos S3 disponíveis em nosso bucket g30batalha. Tais tabelas representam nosso CSV final importado como tabela para facilidade na busca de dados.
- O portal Hue pode ser acessado em:[http://ec2-18-232-52-206.compute-1.amazonaws.com:8888/hue/](http://ec2-18-232-52-206.compute-1.amazonaws.com:8888/hue/) Usuario: g30  - Senha: Dreamed@885
- Nosso output final pode ser visualizado no S3 dentro de ***s3://g30batalha/edumap/final_output***

 ### Frontend 
- All resources related to the frontend that is exposed on http://edumap.surge.sh/ can be seen on folder **frontend**
- Decidimos usar o Tableout para visualização analitica de nossos gráficos gerados a partir de nossos dados consolidados. 

---


					EduMap
					Educação Time 1
					Hackathon Batalha de Dados 2018 - Itaú
---
