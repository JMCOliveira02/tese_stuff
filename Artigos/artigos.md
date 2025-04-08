1. 3D-Aware Object Goal Navigation via Simultaneous Exploration and Identification
* Info
    * Ano: 2023
    * Publicado em: CVPR 2023 
* Links
    * https://arxiv.org/pdf/2212.00338
    * https://www.youtube.com/watch?v=cqUP9lphras&feature=youtu.be
* Notas
    * Datasets fixes com segmentação semântica indoor : MP3D e Gibson

2. Semantic Scene Completion from a Single Depth Image
* Info
    * Ano: 2017
    * Publicado em: CVPR 2017
* Links
    * https://arxiv.org/abs/1611.08974
* Notas
    * Introduz o dataset SUNCG (bem gusti indoor tudo artifical tho e está offline agora mas tem uma cópia no github)
    * input RGB-D , usa 3D CNN'S
    * talvez demasiado complexo

3. Deep Hough Voting for 3D Object Detection in Point Clouds
* Info
    * Ano: 2019
    * Publicado em: ICCV 2019
* Links
    * https://arxiv.org/abs/1904.09664
    * https://github.com/facebookresearch/votenet
* Notas
    * end-to-end 3D object detector with hough voting (para se encontrar o centro dos objetos)
    * Opera diretamente em point clouds e utiliza PointNet++ como backbone da rede neuronal
    * apenas geometria sem a parte da cor, e supera métodos anterior mesmo sem cor
    * usa os datasets ScanNet e SUN RGB-D para teste 

4. PointNet++: Deep Hierarchical Feature Learning on Point Sets in a Metric Space
* Info
    * Ano: 2017
    * Publicado em: ICCV 2019
* Links
    * https://arxiv.org/pdf/1706.02413
    * https://github.com/charlesq34/pointnet2
* Notas
    * end-to-end 3D object detector with hough voting (para se encontrar o centro dos objetos)
    * Opera diretamente em point clouds e utiliza PointNet++ como backbone da rede neuronal
    * apenas geometria sem a parte da cor, e supera métodos anterior mesmo sem cor
    * usa os datasets ScanNet e SUN RGB-D para teste 