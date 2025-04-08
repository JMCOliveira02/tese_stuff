1. ModelNet
* The ModelNet40 dataset contains synthetic object point clouds. As the most widely used benchmark for point cloud analysis, ModelNet40 is popular because of its various categories, clean shapes, well-constructed dataset, etc. The original ModelNet40 consists of 12,311 CAD-generated meshes in 40 categories (such as airplane, car, plant, lamp), of which 9,843 are used for training while the rest 2,468 are reserved for testing. The corresponding point cloud data points are uniformly sampled from the mesh surfaces, and then further preprocessed by moving to the origin and scaling into a unit sphere.

2. ShapeNet
* ShapeNet is a large scale repository for 3D CAD models developed by researchers from Stanford University, Princeton University and the Toyota Technological Institute at Chicago, USA. The repository contains over 300M models with 220,000 classified into 3,135 classes arranged using WordNet hypernym-hyponym relationships. ShapeNet Parts subset contains 31,693 meshes categorised into 16 common object classes (i.e. table, chair, plane etc.). Each shapes ground truth contains 2-5 parts (with a total of 50 part classes).

3. SUN RGB-D
* The SUN RGBD dataset contains 10335 real RGB-D images of room scenes. Each RGB image has a corresponding depth and segmentation map. As many as 700 object categories are labeled. The training and testing sets contain 5285 and 5050 images, respectively.

4. S3DIS (Stanford 3D Indoor Scene Dataset (S3DIS)) 
* The Stanford 3D Indoor Scene Dataset (S3DIS) dataset contains 6 large-scale indoor areas with 271 rooms. Each point in the scene point cloud is annotated with one of the 13 semantic categories.

5. SceneNN
* SceneNN is an RGB-D scene dataset consisting of more than 100 indoor scenes. The scenes are captured at various places, e.g., offices, dormitory, classrooms, pantry, etc., from University of Massachusetts Boston and Singapore University of Technology and Design. All scenes are reconstructed into triangle meshes and have per-vertex and per-pixel annotation. The dataset is additionally enriched with fine-grained information such as axis-aligned bounding boxes, oriented bounding boxes, and object poses.



