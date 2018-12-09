
# EduMap

## Educação Inteligente para Vidas Inteligentes

 1. Backend 
- Jupyter script pode ser rodado em:[https://ec2-18-213-151-47.compute-1.amazonaws.com:9443/hub/login](https://ec2-18-213-151-47.compute-1.amazonaws.com:9443/hub/login): edumap_merge.ipynb dentro da pasta jupiter_scripts
- Use usuário: **g30** e  senha: **dreamed885** para fazer o login

- Nós criamos tabelas Hive que foram geradas através de arquivos S3 disponíveis em nosso bucket g30batalha. Tais tabelas representam nosso CSV final importado como tabela para facilidade na busca de dados.
- O portal Hue pode ser acessado em:[http://ec2-18-232-52-206.compute-1.amazonaws.com:8888/hue/](http://ec2-18-232-52-206.compute-1.amazonaws.com:8888/hue/) Usuario: g30  - Senha: Dreamed@885


 2. Frontend 
- All resources related to the frontend that is exposed on http://edumap.surge.sh/ can be seen on folder **frontend**
- Decidimos usar o Tableout para visualização analitica de nossos gráficos gerados a partir de nossos dados consolidados. 
