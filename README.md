# awesome-FR3-robotics

- [Robot Library](#Robot-Library)
- [Camera-to-Robot Pose Estimation](#Camera-to-Robot-Pose-Estimation)

- [Object-to-Robot Pose Estimation](#Object-to-Robot-Pose-Estimation)

- [Robot Learning](#Robot-Learning)
- [Robot Planning](#Robot-Planning)
- [Physical Human-Robot Interaction](#Physical-Human-Robot-Interaction)
- [Robot Painter](#Robot-Painter)
- [Robot Manipulation](#Robot-Manipulation)
- [Robot Grasping](#Robot-Grasping)
- [awesome-robot-groups](#awesome-robot-groups)



## Robot Library

[CVPR 2023] **PyPose: A Library for Robot Learning with Physics-based Optimization** <br>

[[arxiv](https://arxiv.org/abs/2209.15428)] [[project](https://pypose.org/)] [[docs](https://pypose.org/docs/main/index.html)] [[tutorial](https://pypose.org/tutorials/)] [[code](https://github.com/pypose/pypose)]



## Camera-to-Robot Pose Estimation

[open tool] **Robot Calibration**

[[github](https://github.com/mikeferguson/robot_calibration)]



[open tool] **easy_handeye: automated, hardware-independent Hand-Eye Calibration**

[[github](https://github.com/IFL-CAMP/easy_handeye)]



[Movelt]  [MoveIt Calibration](http://www.github.com/ros-planning/moveit_calibration)

[[docs](https://ros-planning.github.io/moveit_tutorials/doc/hand_eye_calibration/hand_eye_calibration_tutorial.html)] [[github](https://github.com/ros-planning/moveit_calibration)]



[IJATM 2022] **An overview of hand-eye calibration** <br>

*[Jianfeng Jiang](https://link.springer.com/article/10.1007/s00170-021-08233-6#auth-Jianfeng-Jiang), [Xiao Luo](https://link.springer.com/article/10.1007/s00170-021-08233-6#auth-Xiao-Luo), [Qingsheng Luo](https://link.springer.com/article/10.1007/s00170-021-08233-6#auth-Qingsheng-Luo), [Lijun Qiao](https://link.springer.com/article/10.1007/s00170-021-08233-6#auth-Lijun-Qiao), [Minghao Li](https://link.springer.com/article/10.1007/s00170-021-08233-6#auth-Minghao-Li)* <br>

[[paper](https://link.springer.com/article/10.1007/s00170-021-08233-6)] [survey]



[arxiv 2023] **RegHEC: Hand-Eye Calibration via Simultaneous Multi-view Point Clouds Registration of Arbitrary Object** <br>

*[Shiyu Xing](https://arxiv.org/search/cs?searchtype=author&query=Xing%2C+S), [Fengshui Jing](https://arxiv.org/search/cs?searchtype=author&query=Jing%2C+F), [Min Tan](https://arxiv.org/search/cs?searchtype=author&query=Tan%2C+M)* <br>

[[arxiv](https://arxiv.org/abs/2304.14092)] [[code](https://github.com/Shiyu-Xing/RegHEC)] 



[ICRA 2020] **Camera-to-Robot Pose Estimation from a Single Image** <br>

*[Timothy E. Lee](https://arxiv.org/search/cs?searchtype=author&query=Lee%2C+T+E), [Jonathan Tremblay](https://arxiv.org/search/cs?searchtype=author&query=Tremblay%2C+J), [Thang To](https://arxiv.org/search/cs?searchtype=author&query=To%2C+T), [Jia Cheng](https://arxiv.org/search/cs?searchtype=author&query=Cheng%2C+J), [Terry Mosier](https://arxiv.org/search/cs?searchtype=author&query=Mosier%2C+T), [Oliver Kroemer](https://arxiv.org/search/cs?searchtype=author&query=Kroemer%2C+O), [Dieter Fox](https://arxiv.org/search/cs?searchtype=author&query=Fox%2C+D), [Stan Birchfield](https://arxiv.org/search/cs?searchtype=author&query=Birchfield%2C+S)* <br>

[[arxiv](https://arxiv.org/abs/1911.09231)] [[project](https://research.nvidia.com/publication/2020-05_camera-robot-pose-estimation-single-image)] [[code](https://github.com/NVlabs/DREAM)] [NVIDIA, CMU]



[CVPR 2023] **[Robot Structure Prior Guided Temporal Attention for Camera-to-Robot Pose Estimation From Image Sequence](https://openaccess.thecvf.com/content/CVPR2023/html/Tian_Robot_Structure_Prior_Guided_Temporal_Attention_for_Camera-to-Robot_Pose_Estimation_CVPR_2023_paper.html)**

*[Yang Tian](https://openaccess.thecvf.com/CVPR2023#), [Jiyao Zhang](https://openaccess.thecvf.com/CVPR2023#), [Zekai Yin](https://openaccess.thecvf.com/CVPR2023#), [Hao Dong](https://openaccess.thecvf.com/CVPR2023#)* <br>

[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Tian_Robot_Structure_Prior_Guided_Temporal_Attention_for_Camera-to-Robot_Pose_Estimation_CVPR_2023_paper.pdf)] [[project](https://sites.google.com/view/sgtapose)] [[code soon]()] [CFCS, Peking University]



[CVPR 2023] **Markerless Camera-to-Robot Pose Estimation via Self-supervised Sim-to-Real Transfer** <br>

*[Jingpei Lu](https://arxiv.org/search/cs?searchtype=author&query=Lu%2C+J), [Florian Richter](https://arxiv.org/search/cs?searchtype=author&query=Richter%2C+F), [Michael C. Yip](https://arxiv.org/search/cs?searchtype=author&query=Yip%2C+M+C)* <br>

[[arxiv](https://arxiv.org/abs/2302.14332)] [[code](https://github.com/ucsdarclab/CtRNet-robot-pose-estimation)]

## Object-to-Robot Pose Estimation

[CoRL 2018] **Deep Object Pose Estimation for Semantic Robotic Grasping of Household Objects** <br>

*[Jonathan Tremblay](https://arxiv.org/search/cs?searchtype=author&query=Tremblay%2C+J), [Thang To](https://arxiv.org/search/cs?searchtype=author&query=To%2C+T), [Balakumar Sundaralingam](https://arxiv.org/search/cs?searchtype=author&query=Sundaralingam%2C+B), [Yu Xiang](https://arxiv.org/search/cs?searchtype=author&query=Xiang%2C+Y), [Dieter Fox](https://arxiv.org/search/cs?searchtype=author&query=Fox%2C+D), [Stan Birchfield](https://arxiv.org/search/cs?searchtype=author&query=Birchfield%2C+S)* <br>

[[arxiv](https://arxiv.org/abs/1809.10790)] [[project](https://research.nvidia.com/publication/2018-09_deep-object-pose-estimation-semantic-robotic-grasping-household-objects)] [[code](https://github.com/NVlabs/Deep_Object_Pose)] [[NVlabs](https://github.com/NVlabs)]



[IROS 2020] **Indirect Object-to-Robot Pose Estimation from an External Monocular RGB Camera** <br>*[Jonathan Tremblay](https://arxiv.org/search/cs?searchtype=author&query=Tremblay%2C+J), [Stephen Tyree](https://arxiv.org/search/cs?searchtype=author&query=Tyree%2C+S), [Terry Mosier](https://arxiv.org/search/cs?searchtype=author&query=Mosier%2C+T), [Stan Birchfield](https://arxiv.org/search/cs?searchtype=author&query=Birchfield%2C+S)* <br>

[[arxiv](https://arxiv.org/abs/2008.11822)] [[code](https://github.com/NVlabs/Deep_Object_Pose)] [[NVlabs](https://github.com/NVlabs)]



:fire:[CVPR 2023] **BundleSDF: Neural 6-DoF Tracking and 3D Reconstruction of Unknown Objects** <br>

*[Bowen Wen](https://research.nvidia.com/person/bowen-wen), [Jonathan Tremblay](https://research.nvidia.com/person/jonathan-tremblay), [Valts Blukis](https://research.nvidia.com/person/valts-blukis), [Stephen Tyree](https://research.nvidia.com/person/stephen-tyree), [Thomas Müller](https://research.nvidia.com/person/thomas-muller),
[Alex Evans](https://research.nvidia.com/person/alex-evans), [Dieter Fox](https://research.nvidia.com/person/dieter-fox), [Jan Kautz](https://research.nvidia.com/person/jan-kautz), [Stan Birchfield](https://research.nvidia.com/person/stan-birchfield)* <br>

[[arxiv](https://arxiv.org/abs/2303.14158)] [[project](https://bundlesdf.github.io/)] [[code soon]()] [NVIDIA]



:fire:[ECCV 2022] **ShAPO: Implicit Representations for Multi-Object Shape, Appearance, and Pose Optimization** <br>

*[Muhammad Zubair Irshad](https://arxiv.org/search/cs?searchtype=author&query=Irshad%2C+M+Z), [Sergey Zakharov](https://arxiv.org/search/cs?searchtype=author&query=Zakharov%2C+S), [Rares Ambrus](https://arxiv.org/search/cs?searchtype=author&query=Ambrus%2C+R), [Thomas Kollar](https://arxiv.org/search/cs?searchtype=author&query=Kollar%2C+T), [Zsolt Kira](https://arxiv.org/search/cs?searchtype=author&query=Kira%2C+Z), [Adrien Gaidon](https://arxiv.org/search/cs?searchtype=author&query=Gaidon%2C+A)*<br>

[[arxiv](https://arxiv.org/abs/2207.13691)] [[project](https://zubair-irshad.github.io/projects/ShAPO.html)] [[code](https://github.com/zubair-irshad/shapo)]



## Robot Learning

[ICRA 2023] **NeRF2Real: Sim2real Transfer of Vision-guided Bipedal Motion Skills using Neural Radiance Fields**<br>

*Arunkumar Byravan*, Jan Humplik*, Leonard Hasenclever*, Arthur Brussee*, Francesco Nori, Tuomas Haarnoja, Ben Moran, Steven Bohez, Fereshteh Sadeghi, Bojan Vujatovic and Nicolas Heess *<br>

[[arxiv](https://arxiv.org/abs/2210.04932)] [[project](https://sites.google.com/view/nerf2real/home)] [DeepMind]



[ICRA 2023] **Grounding Language with Visual Affordances over Unstructured Data** <br>

*[Oier Mees](https://arxiv.org/search/cs?searchtype=author&query=Mees%2C+O), [Jessica Borja-Diaz](https://arxiv.org/search/cs?searchtype=author&query=Borja-Diaz%2C+J), [Wolfram Burgard](https://arxiv.org/search/cs?searchtype=author&query=Burgard%2C+W)*<br>

[[arxiv](https://arxiv.org/abs/2210.01911)] [[project](http://hulc2.cs.uni-freiburg.de/)] [[code: soon]()]



[ICRA 2023] **Code as Policies: Language Model Programs for Embodied Control** <br>

*[Jacky Liang](https://arxiv.org/search/cs?searchtype=author&query=Liang%2C+J), [Wenlong Huang](https://arxiv.org/search/cs?searchtype=author&query=Huang%2C+W), [Fei Xia](https://arxiv.org/search/cs?searchtype=author&query=Xia%2C+F), [Peng Xu](https://arxiv.org/search/cs?searchtype=author&query=Xu%2C+P), [Karol Hausman](https://arxiv.org/search/cs?searchtype=author&query=Hausman%2C+K), [Brian Ichter](https://arxiv.org/search/cs?searchtype=author&query=Ichter%2C+B), [Pete Florence](https://arxiv.org/search/cs?searchtype=author&query=Florence%2C+P), [Andy Zeng](https://arxiv.org/search/cs?searchtype=author&query=Zeng%2C+A) <br>*

[[arxiv](https://arxiv.org/abs/2209.07753)] [[code](https://github.com/google-research/google-research/tree/master/code_as_policies)] [[project](https://code-as-policies.github.io/)] [[Robotics at Google](http://g.co/robotics)] [ICRA 2023 Outstanding Robot Learning Paper]



:fire: [RA-L 2020] **RLBench: The Robot Learning Benchmark & Learning Environment**  <br>

*[Stephen James](https://arxiv.org/search/cs?searchtype=author&query=James%2C+S), [Zicong Ma](https://arxiv.org/search/cs?searchtype=author&query=Ma%2C+Z), [David Rovick Arrojo](https://arxiv.org/search/cs?searchtype=author&query=Arrojo%2C+D+R), [Andrew J. Davison](https://arxiv.org/search/cs?searchtype=author&query=Davison%2C+A+J)* <br>

[[arxiv](https://arxiv.org/abs/1909.12271)] [[code](https://github.com/stepjam/RLBench)] [[project](https://sites.google.com/view/rlbench)] [[Dyson Robotics Lab, Imperial College London](http://www.google.com/url?q=http%3A%2F%2Fwww.imperial.ac.uk%2Fdyson-robotics-lab%2Fprojects%2Frlbench%2F&sa=D&sntz=1&usg=AOvVaw0DBha3VkgeJjnzNhGiXIrw)]



[T-RO 2021] **Constrained Probabilistic Movement Primitives for Robot Trajectory Adaptation** <br>

[[arxiv](https://arxiv.org/abs/2101.12561) [[video](https://www.youtube.com/watch?v=7UI6QX-eZ3I)] 



[ICRA 2022] **Augmenting Reinforcement Learning with Behavior Primitives for Diverse Manipulation Tasks** <br>

*[Soroush Nasiriany](https://ieeexplore.ieee.org/author/37089001338); [Huihan Liu](https://ieeexplore.ieee.org/author/37089448557); [Yuke Zhu](https://ieeexplore.ieee.org/author/37086080772)* <br>

[[paper](https://ieeexplore.ieee.org/abstract/document/9812140)] [[project](https://ut-austin-rpl.github.io/maple/)] [[code](https://github.com/UT-Austin-RPL/maple)] [ICRA 2022 Outstanding Learning Paper]



[ICLR 2023] **From Play to Policy: Conditional Behavior Generation from Uncurated Robot Data** <br>

[[arxiv](https://arxiv.org/abs/2210.10047)] [[project](https://play-to-policy.github.io/)] [[code](https://github.com/jeffacce/play-to-policy)]



[ICRA 2022] **SAGCI-System: Towards Sample-Efficient, Generalizable, Compositional, and Incremental Robot Learning** <br>

*[Jun Lv](https://ieeexplore.ieee.org/author/37089449764); [Qiaojun Yu](https://ieeexplore.ieee.org/author/37089450989); [Lin Shao](https://ieeexplore.ieee.org/author/37086423705); [Wenhai Liu](https://ieeexplore.ieee.org/author/37085683936); [Wenqiang Xu](https://ieeexplore.ieee.org/author/37088221545); [Cewu Lu](https://ieeexplore.ieee.org/author/37085483529)* <br>

[[paper](https://ieeexplore.ieee.org/document/9811859)] [[project](https://sites.google.com/view/egci)]



## Robot Planning

[ICRA 2023] **Learning-based Initialization of Trajectory Optimization for Path-following Problems of Redundant Manipulators** <br>

*Minsung Yoon, Mincheul Kang, Daehyung Park and Sung-Eui Yoon*<br>

[[paper](http://sgvr.kaist.ac.kr/~msyoon/papers/ICRA23_RLITG/ICRA23_RLITG_vCR.pdf)] [[code](https://github.com/MinsungYoon/RL-ITG)] [[project](http://sgvr.kaist.ac.kr/~msyoon/papers/ICRA23_RLITG/)] [KAIST] [ICRA 2023 Outstanding Planning Paper]



[RA-L 2020] **Object-Centric Task and Motion Planning in Dynamic Environments** <br>

*[Toki Migimatsu](https://arxiv.org/search/cs?searchtype=author&query=Migimatsu%2C+T), [Jeannette Bohg](https://arxiv.org/search/cs?searchtype=author&query=Bohg%2C+J) <br>*

[[arxiv](https://arxiv.org/abs/1911.04679)] [[code](https://github.com/tmigimatsu/logic-opt)] [[project](https://sites.google.com/stanford.edu/objectcentrictamp)]



[ICRA 2022] **Non-Gaussian Risk Bounded Trajectory Optimization for Stochastic Nonlinear Systems in Uncertain Environments** <br>

*[Weiqiao Han](https://arxiv.org/search/cs?searchtype=author&query=Han%2C+W), [Ashkan Jasour](https://arxiv.org/search/cs?searchtype=author&query=Jasour%2C+A), [Brian Williams](https://arxiv.org/search/cs?searchtype=author&query=Williams%2C+B)*<br>

[[arxiv](https://arxiv.org/abs/2203.03038)] [[code](https://github.com/jasour/non-gaussian_risk-bounded_trajopt)] [MIT] [ICRA 2022 Outstanding Planning Paper]





## Physical Human-Robot Interaction

[ICRA 2023] **Learning from Physical Human Feedback: An Object-Centric One-Shot Adaptation Method** <br>

*[Alvin Shek](https://arxiv.org/search/cs?searchtype=author&query=Shek%2C+A), [Bo Ying Su](https://arxiv.org/search/cs?searchtype=author&query=Su%2C+B+Y), [Rui Chen](https://arxiv.org/search/cs?searchtype=author&query=Chen%2C+R), [Changliu Liu](https://arxiv.org/search/cs?searchtype=author&query=Liu%2C+C)* <br>

[[arxiv](https://arxiv.org/abs/2203.04951)] [[project](https://alvinosaur.github.io/AboutMe/projects/opa/)] [[code](https://github.com/Alvinosaur/opa)] [CMU] [ICRA 2023 Outstanding Physical Human-Robot Interaction Paper]



## Robot Painter

[ICRA 2023] **FRIDA: A Collaborative Robot Painter with a Differentiable, Real2Sim2Real Planning Environment**<br>

*[Peter Schaldenbrand](https://arxiv.org/search/cs?searchtype=author&query=Schaldenbrand%2C+P), [James McCann](https://arxiv.org/search/cs?searchtype=author&query=McCann%2C+J), [Jean Oh](https://arxiv.org/search/cs?searchtype=author&query=Oh%2C+J)* <br>

[[arxiv](https://arxiv.org/abs/2210.00664)] [[project](https://pschaldenbrand.github.io/frida/)] [[code](https://github.com/cmubig/Frida)] [The Robotics Institute, Carnegie Mellon University]





## Robot Manipulation

[MIT Course] **[Robotic Manipulation](https://manipulation.csail.mit.edu/index.html) Perception, Planning, and Control** <br>

*[Russ Tedrake](http://people.csail.mit.edu/russt/)*

[[website](https://manipulation.csail.mit.edu/)]



[CVPR 2022] **Coarse-to-Fine Q-attention: Efficient Learning for Visual Robotic Manipulation via Discretisation** <br>

*Stephen James, Kentaro Wada, Tristan Laidlow, Andrew J. Davison* <br>

[[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/James_Coarse-To-Fine_Q-Attention_Efficient_Learning_for_Visual_Robotic_Manipulation_via_Discretisation_CVPR_2022_paper.pdf)] [[project](https://sites.google.com/view/c2f-q-attention)] [[code](https://github.com/stepjam/ARM)] [[Dyson Robotics Lab, Imperial College London](http://www.google.com/url?q=http%3A%2F%2Fwww.imperial.ac.uk%2Fdyson-robotics-lab%2Fprojects%2Frlbench%2F&sa=D&sntz=1&usg=AOvVaw0DBha3VkgeJjnzNhGiXIrw)]



[ICML 2023] **VIMA: General Robot Manipulation with Multimodal Prompts** <br>

*[Yunfan Jiang](https://arxiv.org/search/cs?searchtype=author&query=Jiang%2C+Y), [Agrim Gupta](https://arxiv.org/search/cs?searchtype=author&query=Gupta%2C+A), [Zichen Zhang](https://arxiv.org/search/cs?searchtype=author&query=Zhang%2C+Z), [Guanzhi Wang](https://arxiv.org/search/cs?searchtype=author&query=Wang%2C+G), [Yongqiang Dou](https://arxiv.org/search/cs?searchtype=author&query=Dou%2C+Y), [Yanjun Chen](https://arxiv.org/search/cs?searchtype=author&query=Chen%2C+Y), [Li Fei-Fei](https://arxiv.org/search/cs?searchtype=author&query=Fei-Fei%2C+L), [Anima Anandkumar](https://arxiv.org/search/cs?searchtype=author&query=Anandkumar%2C+A), [Yuke Zhu](https://arxiv.org/search/cs?searchtype=author&query=Zhu%2C+Y), [Linxi Fan](https://arxiv.org/search/cs?searchtype=author&query=Fan%2C+L)* <br>

[[arxiv](https://arxiv.org/abs/2210.03094)] [[project](https://vimalabs.github.io/)] [[code](https://github.com/vimalabs/VIMA)] [Stanford, Li Fei-Fei]



:fire: [CVPR 2022] **Coarse-to-Fine Q-attention: Efficient Learning for  Vision-based Robotic Manipulation via Discretisation** <br>

*[**Stephen James**](https://www.google.com/url?q=https%3A%2F%2Fstepjam.github.io%2F&sa=D&sntz=1&usg=AOvVaw3bf-zofRVek_dAtu3uQJ6S)	[	](https://www.google.com/url?q=https%3A%2F%2Fstepjam.github.io%2F&sa=D&sntz=1&usg=AOvVaw3bf-zofRVek_dAtu3uQJ6S)[**Kentaro Wada**](https://www.google.com/url?q=https%3A%2F%2Fwww.wkentaro.com%2F&sa=D&sntz=1&usg=AOvVaw1XHf1JYcKQoFBt42wg0aFw)[	](https://www.google.com/url?q=https%3A%2F%2Fstepjam.github.io%2F&sa=D&sntz=1&usg=AOvVaw3bf-zofRVek_dAtu3uQJ6S)[	](https://www.google.com/url?q=https%3A%2F%2Fstepjam.github.io%2F&sa=D&sntz=1&usg=AOvVaw3bf-zofRVek_dAtu3uQJ6S)[**Tristan Laidlow**](https://scholar.google.com/citations?user=bmOi48IAAAAJ&hl=en)[	](https://www.google.com/url?q=https%3A%2F%2Fwww.doc.ic.ac.uk%2F~ajd%2F&sa=D&sntz=1&usg=AOvVaw33sU2BJ5bbyvK1VANoKzwR)[	](https://www.google.com/url?q=https%3A%2F%2Fwww.doc.ic.ac.uk%2F~ajd%2F&sa=D&sntz=1&usg=AOvVaw33sU2BJ5bbyvK1VANoKzwR)[**Andrew J. Davison**](https://www.google.com/url?q=https%3A%2F%2Fwww.doc.ic.ac.uk%2F~ajd%2F&sa=D&sntz=1&usg=AOvVaw33sU2BJ5bbyvK1VANoKzwR) <br>*

[[paper](https://openaccess.thecvf.com/content/CVPR2022/papers/James_Coarse-To-Fine_Q-Attention_Efficient_Learning_for_Visual_Robotic_Manipulation_via_Discretisation_CVPR_2022_paper.pdf)] [[project](https://sites.google.com/view/c2f-q-attention)] [[code](https://github.com/stepjam/ARM)] [Dyson Robotics Lab, Imperial College London]



[RSS 2021] **Active Learning of Abstract Plan Feasibility** <br>

*[Michael Noseworthy](https://arxiv.org/search/cs?searchtype=author&query=Noseworthy%2C+M), [Caris Moses](https://arxiv.org/search/cs?searchtype=author&query=Moses%2C+C), [Isaiah Brand](https://arxiv.org/search/cs?searchtype=author&query=Brand%2C+I), [Sebastian Castro](https://arxiv.org/search/cs?searchtype=author&query=Castro%2C+S), [Leslie Kaelbling](https://arxiv.org/search/cs?searchtype=author&query=Kaelbling%2C+L), [Tomás Lozano-Pérez](https://arxiv.org/search/cs?searchtype=author&query=Lozano-Pérez%2C+T), [Nicholas Roy](https://arxiv.org/search/cs?searchtype=author&query=Roy%2C+N)* <br>

[[arxiv](https://arxiv.org/abs/2107.00683)]  [[code](https://github.com/Learning-and-Intelligent-Systems/stacking)] [[videos](https://www.youtube.com/watch?v=UF-SjGm20Mw)] [[MIT,Robust Robotics Group](https://groups.csail.mit.edu/rrg/)]



[CoRL 2020] **Learning to Compose Hierarchical Object-Centric Controllers for Robotic Manipulation** <br>

*[Mohit Sharma](https://arxiv.org/search/cs?searchtype=author&query=Sharma%2C+M), [Jacky Liang](https://arxiv.org/search/cs?searchtype=author&query=Liang%2C+J), [Jialiang Zhao](https://arxiv.org/search/cs?searchtype=author&query=Zhao%2C+J), [Alex LaGrassa](https://arxiv.org/search/cs?searchtype=author&query=LaGrassa%2C+A), [Oliver Kroemer](https://arxiv.org/search/cs?searchtype=author&query=Kroemer%2C+O)* <br>

[[arxiv](https://arxiv.org/abs/2011.04627)] [[project](https://sites.google.com/view/compositional-object-control/)] [[code](https://github.com/iamlab-cmu/hierarchical-object-controllers)]



:fire: [CoRL 2022] **RoboTube: Learning Household Manipulation from Human Videos with Simulated Twin Environments** <br>

*[haoyu Xiong](https://openreview.net/profile?id=~haoyu_Xiong2)*, [Haoyuan Fu](https://openreview.net/profile?id=~Haoyuan_Fu1)*,* [Jieyi Zhang](https://openreview.net/profile?id=~Jieyi_Zhang1)*,* [Chen Bao](https://openreview.net/profile?id=~Chen_Bao2)*,* [Qiang Zhang](https://openreview.net/profile?id=~Qiang_Zhang10)*,* [Yongxi Huang](https://openreview.net/profile?id=~Yongxi_Huang1)*,* [Wenqiang Xu](https://openreview.net/profile?id=~Wenqiang_Xu2)*,* [Animesh Garg](https://openreview.net/profile?id=~Animesh_Garg1)*,* [Cewu Lu](https://openreview.net/profile?id=~Cewu_Lu3) <br>

[[paper](https://openreview.net/pdf?id=VD0nXUG5Qk)] [[project](https://www.robotube.org/)] [[code soon]()]



## Robot Grasping

[Survey 2022] **Robotic Grasping from Classical to Modern: A Survey** <br>

*[Hanbo Zhang](https://arxiv.org/search/cs?searchtype=author&query=Zhang%2C+H), [Jian Tang](https://arxiv.org/search/cs?searchtype=author&query=Tang%2C+J), [Shiguang Sun](https://arxiv.org/search/cs?searchtype=author&query=Sun%2C+S), [Xuguang Lan](https://arxiv.org/search/cs?searchtype=author&query=Lan%2C+X)* <br>

[[arxiv](https://arxiv.org/abs/2202.03631)] [Xian JTU]



:fire: [ICRA 2022] **Unseen Object Amodal Instance Segmentation via Hierarchical Occlusion Modeling** <br>

*Seunghyeok Back, Joosoon Lee, Taewon Kim, Sangjun Noh, Raeyoung Kang, Seongho Bak, Kyoobin Lee* <br>

[[arxiv](https://arxiv.org/abs/2109.11103)] [[project](https://sites.google.com/view/uoais)] [[code](https://github.com/gist-ailab/uoais)]



:fire:[T-RO 2023] **AnyGrasp: Robust and Efficient Grasp Perception in Spatial and Temporal Domains**  <br>

*[Hao-Shu Fang](https://arxiv.org/search/cs?searchtype=author&query=Fang%2C+H), [Chenxi Wang](https://arxiv.org/search/cs?searchtype=author&query=Wang%2C+C), [Hongjie Fang](https://arxiv.org/search/cs?searchtype=author&query=Fang%2C+H), [Minghao Gou](https://arxiv.org/search/cs?searchtype=author&query=Gou%2C+M), [Jirong Liu](https://arxiv.org/search/cs?searchtype=author&query=Liu%2C+J), [Hengxu Yan](https://arxiv.org/search/cs?searchtype=author&query=Yan%2C+H), [Wenhai Liu](https://arxiv.org/search/cs?searchtype=author&query=Liu%2C+W), [Yichen Xie](https://arxiv.org/search/cs?searchtype=author&query=Xie%2C+Y), [Cewu Lu](https://arxiv.org/search/cs?searchtype=author&query=Lu%2C+C)* <br>

[[arxiv](https://arxiv.org/abs/2212.08333)] [[project](https://graspnet.net/index.html)] [[code](https://github.com/graspnet)]



[CVPR 2023] **[Learning Human-to-Robot Handovers From Point Clouds](https://openaccess.thecvf.com/content/CVPR2023/html/Christen_Learning_Human-to-Robot_Handovers_From_Point_Clouds_CVPR_2023_paper.html)** <br>

*[Sammy Christen](https://openaccess.thecvf.com/CVPR2023#), [Wei Yang](https://openaccess.thecvf.com/CVPR2023#), [Claudia Pérez-D’Arpino](https://openaccess.thecvf.com/CVPR2023#), [Otmar Hilliges](https://openaccess.thecvf.com/CVPR2023#), [Dieter Fox](https://openaccess.thecvf.com/CVPR2023#), [Yu-Wei Chao](https://openaccess.thecvf.com/CVPR2023#) <br>*

[[paper](https://openaccess.thecvf.com/content/CVPR2023/papers/Christen_Learning_Human-to-Robot_Handovers_From_Point_Clouds_CVPR_2023_paper.pdf)] [[project](https://handover-sim2real.github.io/)] [[code soon]()]



[ICCV 2021] **[Graspness Discovery in Clutters for Fast and Accurate Grasp Detection](https://openaccess.thecvf.com/content/ICCV2021/html/Wang_Graspness_Discovery_in_Clutters_for_Fast_and_Accurate_Grasp_Detection_ICCV_2021_paper.html)** <br>

*[Chenxi Wang](https://openaccess.thecvf.com/ICCV2021#), [Hao-Shu Fang](https://openaccess.thecvf.com/ICCV2021#), [Minghao Gou](https://openaccess.thecvf.com/ICCV2021#), [Hongjie Fang](https://openaccess.thecvf.com/ICCV2021#), [Jin Gao](https://openaccess.thecvf.com/ICCV2021#), [Cewu Lu](https://openaccess.thecvf.com/ICCV2021#)*

[[paper](https://openaccess.thecvf.com/content/ICCV2021/papers/Wang_Graspness_Discovery_in_Clutters_for_Fast_and_Accurate_Grasp_Detection_ICCV_2021_paper.pdf)] [[code](https://github.com/rhett-chen/graspness_implementation)]



## Visual-Tactile

### Reconstruction

[CVPR 2023] **[Visual-Tactile Sensing for In-Hand Object Reconstruction](https://openaccess.thecvf.com/content/CVPR2023/html/Xu_Visual-Tactile_Sensing_for_In-Hand_Object_Reconstruction_CVPR_2023_paper.html)** <br>

*[Wenqiang Xu](https://openaccess.thecvf.com/CVPR2023#), [Zhenjun Yu](https://openaccess.thecvf.com/CVPR2023#), [Han Xue](https://openaccess.thecvf.com/CVPR2023#), [Ruolin Ye](https://openaccess.thecvf.com/CVPR2023#), [Siqiong Yao](https://openaccess.thecvf.com/CVPR2023#), [Cewu Lu](https://openaccess.thecvf.com/CVPR2023#) <br>*

[[arxiv](https://arxiv.org/abs/2303.14498)] [[project](https://sites.google.com/view/vtaco/)] [[code](https://github.com/jeffsonyu/VTacO)]



:fire: [ICRA 2022] **ShapeMap 3-D: Efficient shape mapping through dense touch and vision** <br>

*[Sudharshan Suresh](http://www.cs.cmu.edu/~sudhars1/)  [Zilin Si](https://si-lynnn.github.io/)  [Joshua G. Mangelson](https://ece.byu.edu/directory/josh-mangelson)  [Wenzhen Yuan](http://robotouch.ri.cmu.edu/yuanwz/)  [Michael Kaess](http://www.cs.cmu.edu/~kaess/)* <br>

[[arxiv](https://arxiv.org/abs/2109.09884)] [[code](https://github.com/rpl-cmu/shape-map-3D)] [[project](http://www.cs.cmu.edu/~sudhars1/shape-map/)] [Robotics Institute, CMU]





## Human to Robot Hand Mapping

[T-RO 2023] **Human to Robot Hand Motion Mapping Methods: Review and Classification**

[[paper](https://ieeexplore.ieee.org/document/9896989)]



## awesome-robot-groups

- [The Robotics Institute, Carnegie Mellon University](https://www.ri.cmu.edu/)
- [Dyson Robotics Lab, Imperial College London](http://www.google.com/url?q=http%3A%2F%2Fwww.imperial.ac.uk%2Fdyson-robotics-lab%2Fprojects%2Frlbench%2F&sa=D&sntz=1&usg=AOvVaw0DBha3VkgeJjnzNhGiXIrw)
- [MIT MCube Lab](http://mcube.mit.edu/publications.html)

- [MIT Robotics](https://www.csail.mit.edu/research/?category=People&researchFacets=Robotics)

- [MIT, Robust Robotics Group](https://groups.csail.mit.edu/rrg/index.php)]



## awesome-papers

- RSS
- ICRA
- IROS
- CoRL
- IJRR
- TRO

