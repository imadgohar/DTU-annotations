# DTU-annotations
This repository contains two annotation folders for an openly available drone captured dataset of wind turbine blades. The images can be found here https://data.mendeley.com/datasets/hd96prn3nc/2.

<h3>Annotations:</h3>

<p>Under this folder, dataset is divided into three parts  that is train, test and val.

The file names are self-explanatorty, train-1024-s refers to images that is sliced into square size of 1024 pixels. Test set has two files that is test-HR which represents the original images and test1024-s represents the sliced set.</p>

<h3>Re-annotation:</h3>

<p>Annotation process is often tedious in nature, with many challenging
decisions to make. For instance, some defects may occupy
a large area of blade surface causing bounding boxes to be
unwieldy large. Meanwhile, long and narrow components of
the WTB can result in extreme aspect ratios, i.e. boxes with a
much larger horizontal side than the vertical side and vice
versa, as exemplified in below Figure. Annotators could either
choose to keep the entire defect intact or break the defect into
smaller boxes. Such decisions are not without consequences;
small boxes are notoriously difficult to detect, as many findings
have acknowledged while boxes with extremely large
or small aspect ratios faced data scarcity for training purposes.
Therefore, it is important to explore and determine optimal
aspect ratios by assessing their class-wise performances on
benchmark datasets</p>


<p>Under this folder two sub-folders are placed with the name D2 and D3. These folders contain the re-considered annotations of the Crack category with extreme aspect ratio. For details see the paper.</p>


<h3>Extreme Aspect Ratio:</h3>

![extreme_aspect-ratios](https://user-images.githubusercontent.com/45845910/235831876-a0a045bf-f0a0-476f-94eb-d558f4e101b7.png)

<h3>Cite</h3>
If you are using these annotations in your research or considering it as base for your annotation process please cite:
<p>@article{gohar2023slice,
  title={Slice-Aided Defect Detection in Ultra High-Resolution Wind Turbine Blade Images},
  author={Gohar, Imad and Halimi, Abderrahim and See, John and Yew, Weng Kean and Yang, Cong},
  journal={Machines},
  volume={11},
  number={10},
  pages={953},
  year={2023},
  publisher={MDPI}
}</p>
