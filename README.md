

## *SoccerNet v3 H250*
**[Setting a baseline in long-shot and real-time player / ball detection in Football](https://ifipaiai.org/2023/)** AIAI 2023 León, Spain. 

Created by [Kostas Moutselos](mailto:kmouts@unipi.gr),
and Ilias Maglogiannis
at <a href="https://cbml.ds.unipi.gr"> CBML </a>

<img src="images/batch_500_0.jpg" alt="football match detection image" width="100%">

### Abstract
Players and ball detection are among the first required steps on a football analytics platform.
Until recently, the existing open datasets on which the evaluations of most models were based,
were not sufficient. We point out their weaknesses, and with the advent of SoccerNet v3, we
propose and deliver to the community an edited part of it, in YOLO normalized annotation format,
for the reliable evaluation of related models [https://github.com/kmouts/SoccerNet_v3_H250]. 
The code of the methods and metrics are also available so that they can be used as a
benchmark in future comparisons. The recent YOLO8n model proves better
than FootAndBall in long-shot real-time detection of the ball and players on football fields.

### Directory Structure
<img src="images/directory_structure.png" alt="Directory Structure" >

### YOLO Normalized Annotations
<img src="images/bboxes.png" alt="YOLO bboxes annotation format" >

### Annotations
Only two classes are included in the YOLO annotations: Ball (0), and Person (1).

### Citation
Please, if you use the SoccerNet v3 H250 Dataset, consider citing:

    @conference{AIAI 2023 19th International Conference on Artificial Intelligence Applications and Innovations,
    author={Konstantinos Moutselos and Ilias Maglogiannis},
    title={Setting a baseline in long-shot and real-time player & ball detection in Football},
    booktitle={Proceedings of the 19th International Conference on Artificial Intelligence Applications and Innovations},
    year={2023},
    pages={-},
    publisher={Springer},
    organization={IFIP AIAI},
    doi={},
    isbn={},
    }

### License
Our code is released under the MIT License (see LICENSE file for details).
We have added the License from SoccerNet v3.

