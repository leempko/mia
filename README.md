# Medical Image Analysis

This is the website of the Medical Image Analysis course (NBE-E4010) taught by [Koen Van Leemput](https://users.aalto.fi/vanlek2) at Aalto University.

The teaching material used in the course consists of a tailor-made book and lecture slides:  
- book: [html](book/html/index.html) [pdf](book/mia.pdf)
- lectures:
  + Image smoothing and interpolation: [html](lecture_slides/smoothing_and_interpolation/html/index.html) [pdf](lecture_slides/smoothing_and_interpolation/smoothing_and_interpolation.pdf)
  + Coordinate systems, linear spatial transformations, landmark-based registration [html](lecture_slides/landmark_based_registration/html/index.html) [pdf](lecture_slides/landmark_based_registration/landmark_based_registration.pdf)
  + Intensity-based registration: [html](lecture_slides/intensity_based_registration/html/index.html) [pdf](lecture_slides/intensity_based_registration/intensity_based_registration.pdf)
  + Nonlinear registration: [html](lecture_slides/nonlinear_registration/html/index.html) [pdf](lecture_slides/nonlinear_registration/nonlinear_registration.pdf)
  + Model-based segmentation I: [html](lecture_slides/model_based_segmentation_I/html/index.html) [pdf](lecture_slides/model_based_segmentation_I/model_based_segmentation_I.pdf)
  + Model-based segmentation II: [html](lecture_slides/model_based_segmentation_II/html/index.html) [pdf](lecture_slides/model_based_segmentation_II/model_based_segmentation_II.pdf)
  + Neural Networks: [html](lecture_slides/neural_networks/html/index.html) [pdf](lecture_slides/neural_networks/neural_networks.pdf)

All material is available from a [git repo](https://github.com/leempko/mia/) under a [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) license, and can therefore be used freely in other courses.

## Implementation

This website contains links to the teaching material and the schedule (see below). The [MyCourses](https://mycourses.aalto.fi/course/view.php?id=44862) website will be used in conjunction for all announcements, discussion fora (one general forum and a separate forum for each exercise assignment), and exercise assignments (material, report submissions and peer grading).

The course is heavily focused on solving actual exercises in Python (six in total). These exercises can be performed in groups of max 3 students. The course grading is based mostly (80% weight) on final report scores given by the course personnel (teacher and teaching assistants), after an initial peer grading by fellow students. Participating in the peer grading is required to pass the course, and the quality of peer grading carries a weight of 10%. Each student should also participate in student presentations were submitted reports are analyzed and discussed in class (weight 10%).


## Schedule

For the fall 2024 semester, lectures will be held on Mondays 12.15–14.00 in Health Technology House, Auditorio - F239a. Exercise sessions with teaching assistants present will be held on Thursdays 12.15–14.00, first in Health Technology House, Auditorio - F239a (before the autumn break) and then in the Undergraduate Center, A-sali (Aalto-sali) - Y202a (after the autumn break).

> [!NOTE]
> No exercise sessions will be organized on Thu 5 Sep, Thu 10 Oct, Thu 21 Nov and Thu 28 Nov.

A detailed schedule is given below:

| Week |  Date | Activity | Location | Topic |  |
| --- | ---   | ---      | ---   | --- | --- |
| 1 | Mon 2 Sep | Lecture |  F239a | Introduction to the course | - slides: [pdf](lecture_slides/introduction/intro.pdf) <br/> - jupyter notebook [example](exampleNotebook.ipynb) |
| 2 | Mon 9 Sep | Lecture |  F239a | Image smoothing and interpolation | - chapter 1 in the book ([html](book/html/index.html?page=5) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/smoothing_and_interpolation/html/index.html) [pdf](lecture_slides/smoothing_and_interpolation/smoothing_and_interpolation.pdf) |
| | Thu 12 Sep | Exercise | F239a | Smoothing and interpolation | - submission deadline: Wed 25 Sep at 23:59 |
| 3 | Mon 16 Sep | Lecture |  F239a | Coordinate systems, linear spatial transformations, landmark-based registration | - sections 2.1-2.3 in the book ([html](book/html/index.html?page=19) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/landmark_based_registration/html/index.html) [pdf](lecture_slides/landmark_based_registration/landmark_based_registration.pdf) |
| | Thu 19 Sep | Exercise | F239a | Landmark-based registration | - submission deadline: Wed 2 Oct at 23:59 |
| 4 | Mon 23 Sep | Lecture |  F239a | Intensity-based registration | - section 2.4 in the book, excluding Gauss-Newton optimization ([html](book/html/index.html?page=27) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/intensity_based_registration/html/index.html) [pdf](lecture_slides/intensity_based_registration/intensity_based_registration.pdf) |
|  | Thu 26 Sep | Exercise | F239a | Mutual Information-based registration | - submission deadline: Wed 9 Oct: at 23:59 |
| 5 | Mon 30 Sep | Lecture |  F239a | Nonlinear registration | - sections 2.2.2 and 2.4 in the book, especially Gauss-Newton optimization ([html](book/html/index.html?page=25) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/nonlinear_registration/html/index.html) [pdf](lecture_slides/nonlinear_registration/nonlinear_registration.pdf) |
| | Thu 3 Oct | Exercise | F239a | Mutual Information-based registration (cont.) | - submission deadline: Wed 9 Oct: at 23:59 |
| 6 | Mon 7 Oct | Lecture |  F239a | Model-based segmentation I | - sections 3.1-3.3 in the book ([html](book/html/index.html?page=35) [pdf](book/mia.pdf)) <br/> - probability refresher: [html](lecture_slides/model_based_segmentation_I/html_refresher/index.html) [pdf](lecture_slides/model_based_segmentation_I/refresher_on_probability.pdf) <br/> - slides: [html](lecture_slides/model_based_segmentation_I/html/index.html) [pdf](lecture_slides/model_based_segmentation_I/model_based_segmentation_I.pdf) |
| 7 | Mon 21 Oct | Lecture |  F239a | Student presentations of the first three exercises | |
| | Thu 24 Oct | Exercise | Y202a | Nonlinear registration | - submission deadline: Wed 6 Nov at 23:59 |
| 8 | Mon 28 Oct | Lecture |  F239a | Model-based segmentation II | - sections 3.4-3.5 in the book ([html](book/html/index.html?page=44) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/model_based_segmentation_II/html/index.html) [pdf](lecture_slides/model_based_segmentation_II/model_based_segmentation_II.pdf)|
| | Thu 31 Oct | Exercise | Y202a | Model-based segmentation | - submission deadline: Wed 13 Nov at 23:59 |
| 9 | Mon 4 Nov | Lecture |  F239a | Neural Networks | - chapter 4 in the book ([html](book/html/index.html?page=55) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/neural_networks/html/index.html) [pdf](lecture_slides/neural_networks/neural_networks.pdf)|
| | Thu 7 Nov | Exercise | Y202a | Neural Networks | - submission deadline: Wed 20 Nov at 23:59 |
| 10 | Mon 11 Nov | Lecture |  F239a | Guest lecture Eero Salli (HUS) | |
| | Thu 14 Nov | Exercise | Y202a | Neural Networks (cont.) | - submission deadline: Wed 20 Nov at 23:59 |
| 11 | Mon 18 Nov | Lecture |  F239a | Guest lecture Aino Nieminen (Disior) | |
| 12 | Mon 25 Nov | Lecture |  F239a | Student presentations of the last three exercises | |



