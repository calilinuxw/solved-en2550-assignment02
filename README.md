Download Link: https://assignmentchef.com/product/solved-en2550-assignment02
<br>
Please note that you must implement the key Python functions and scripts on your own. If you copy from the Internet or others, you will not get the learning experience intended through this assignment. Based on the Jupyter notebook file and the Graffiti images carry out the following:1. Using he given code (item no. 1), experiment with various types of 2-D transformations. [1 mark]2. TransformGraffiti(https://www.robots.ox.ac.uk/~vgg/data/affine/)img1.ppmontoimg5.ppm using code in item no. 2. [2 marks]3. Itemno. 3 isformouse clickingandselectingmatchingpointsinthetwoimagestobestitched. Compute the homography using the relevant OpenCV function and carry out stitching. [3 marks]4. Item no. 4 is similar to item no. 3. Here, compute the homography using your own code and stitch the two images. [4 marks]5. BONUS:StitchimagesusingSuperGluehttps://github.com/magicleap/SuperGluePretrainedNetwork features instead of mouse-clicked points. Compute the homography though RANSAC or MSAC. Stitch more than two images using mouse-clicked points. Handle the seams. See the original paper here http://matthewalunbrown.com/papers/iccv2003.pdf. [4 marks]Upload a five-page report named as your_index_a02.pdf. Type out the index number within the file as well. Include important parts of code, results, and interpretations in the file.1en2550_lec12_alignment_assignmentFebruary 20, 20211 1. 2-D Transforms

[0 1 1 0][1 1 1 1]][[0.5000000000000001, 0.8660254037844386, 0.0], [-0.8660254037844386,0.5000000000000001, 0.0], [0.0, 0.0, 1.0]][[ 0. 0.8660254 1.3660254 0.5 0. ][ 0. 0.5 -0.3660254 -0.8660254 0. ] [ 1. 1. 1. 1. 1. ]]

2 2. Warping Using a Given Homography

[[0.66378505, 0.68003334, -31.230335], [-0.144955, 0.97128304, 148.7742], [0.00042518504, -1.3930359e-05, 1.0]]3 3. Computing the Homogrpahy Using Mouse-Clicked Points and Warping

[[273. 139.][525. 222.][643. 298.][591. 487.][378. 468.]][[219. 217.][385. 236.][468. 271.][560. 433.][469. 474.]]4 4. Computing the Homogrpahy Using Mouse-Clicked Points without OpenCV

[101. 322.][182. 142.][527. 170.][434. 305.]][[475. 150.][480. 350.][272. 255.][282. 113.] [414. 156.]] [ ]: