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

This website only contains links to the teaching material and the schedule (see below). The [MyCourses](https://mycourses.aalto.fi/course/view.php?id=51906) website will be used for the practical implementation, such as group creation and exercise assignments (material, report submissions and peer grading) as well as announcements and discussion fora. 

Note that **this course is *not* designed to be an online course**: the primary venue to have your questions answered by the teacher and the TAs, and to get detailed feedback on your work, is to physically attend the lectures and the exercise sessions.

The course is heavily focused on solving actual exercises in NumPy/Python (six in total). These exercises will be performed in groups of max 3 students, with reports that will be both peer graded and lightly reviewed by the course personnel (teacher and TAs). 

The actual course grading will be based on a final, individual oral examination, guided by the exercise reports that your group submitted throughout the course period. Participating in the peer grading is required to pass the course, and helping to answer fellow students' questions in the discussion fora is encouraged (and will be viewed positively in the grading). 

## Schedule

For the fall 2026 semester, lectures will be held on Mondays 12.15–14.00 in U141 U3 (Undergraduate Center, Otakaari 1). Exercise sessions with teaching assistants present will be held on Tuesdays (10:15-12:00) in A123 A1 (Undergraduate Center, Otakaari 1).

> Note: no exercise sessions will be organized on Tue 17 Nov and Tue 24 Nov.


A detailed schedule is given below:

| Week |  Date | Activity | Location | Topic |  |
| --- | ---   | ---      | ---   | --- | --- |
| 1 | Mon 31 Aug | Lecture  |  U141 | Introduction | - introduction: [html](lecture_slides/introduction/html/index.html) [pdf](lecture_slides/introduction/intro.pdf) |
| 2 | Mon 7 Sep | Lecture  |  U141 | Image smoothing and interpolation | - chapter 1 in the book ([html](book/html/index.html?page=5) [pdf](book/mia.pdf)) <br/> - introduction: [html](lecture_slides/introduction/html/index.html) [pdf](lecture_slides/introduction/intro.pdf) <br/> - slides: [html](lecture_slides/smoothing_and_interpolation/html/index.html) [pdf](lecture_slides/smoothing_and_interpolation/smoothing_and_interpolation.pdf) |
|   | Tue 8 Sep | Exercise | A123 | Smoothing and interpolation | submission deadline: Fri 18 Sep at 23:59 |
| 3 | Mon 14 Sep | Lecture  |  U141 | Coordinate systems, linear spatial transformations, landmark-based registration | - sections 2.1-2.3 in the book ([html](book/html/index.html?page=19) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/landmark_based_registration/html/index.html) [pdf](lecture_slides/landmark_based_registration/landmark_based_registration.pdf) |
|   | Tue 15 Sep | Exercise | A123 | Landmark-based registration | submission deadline: Fri 25 Sep at 23:59 |
| 4 | Mon 21 Sep | Lecture  | U141 | Intensity-based registration | - section 2.4 in the book, excluding Gauss-Newton optimization ([html](book/html/index.html?page=27) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/intensity_based_registration/html/index.html) [pdf](lecture_slides/intensity_based_registration/intensity_based_registration.pdf) |
|   | Tue 22 Sep | Exercise | A123 |  Landmark-based registration (second part) | submission deadline: Fri 25 Sep at 23:59 |


| 5 | Mon 28 Sep | Lecture  |  U141 | Nonlinear registration | - sections 2.2.2 and 2.4 in the book, especially Gauss-Newton optimization ([html](book/html/index.html?page=25) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/nonlinear_registration/html/index.html) [pdf](lecture_slides/nonlinear_registration/nonlinear_registration.pdf) 
<!--
<br/> - lecture [recording](https://aalto.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=a7a1e6ac-1621-4c55-8fa5-b1fb0099319a)  
-->
|
|   | Tue 29 Sep | Exercise | A123 | Intensity-based registration | submission deadline: Fri 9 Oct at 23:59 |
| 6 | Mon 5 Oct | Lecture  |  U141 | Model-based segmentation I | - sections 3.1-3.3 in the book ([html](book/html/index.html?page=35) [pdf](book/mia.pdf)) <br/> - probability refresher: [html](lecture_slides/model_based_segmentation_I/html_refresher/index.html) [pdf](lecture_slides/model_based_segmentation_I/refresher_on_probability.pdf) <br/> - slides: [html](lecture_slides/model_based_segmentation_I/html/index.html) [pdf](lecture_slides/model_based_segmentation_I/model_based_segmentation_I.pdf) 
<!--
<br/> - lecture [recording](https://aalto.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=de8f4418-c466-482c-92f4-b20200997a94) 
-->
|
|   | Tue 6 Oct | Exercise | A123 | Nonlinear registration | submission deadline: Fri 25 Oct at 23:59 |
| 7 | Mon 19 Oct | Lecture  |  U141 | Model-based segmentation II | - sections 3.4-3.5 in the book ([html](book/html/index.html?page=44) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/model_based_segmentation_II/html/index.html) [pdf](lecture_slides/model_based_segmentation_II/model_based_segmentation_II.pdf) |
|   | Tue 20 Oct | Exercise | A123 | Model-based segmentation | submission deadline: Fri 30 Oct at 23:59 |
| 8 | Mon 26 Oct | Lecture  |  U141 | Exercise review session I | |
|   | Tue 27 Oct | Exercise | A123 | Model-based segmentation (cont.) | submission deadline: Fri 30 Oct at 23:59 |
| 9 | Mon 2 Nov | Lecture  |  U141 | Neural networks | - chapter 4 in the book ([html](book/html/index.html?page=55) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/neural_networks/html/index.html) [pdf](lecture_slides/neural_networks/neural_networks.pdf) 
<!--
<br/> - lecture [recording](https://aalto.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=0d54885a-8f21-453c-94f5-b21e00aa3756) 
-->
|
|   | Tue 3 Nov | Exercise | A123 | Neural networks | submission deadline: Fri 13 Nov at 23:59 |
| 10 | Mon 9 Nov | Lecture  |  U141 | Guest lecture | TBD |
|   | Tue 10 Nov | Exercise | A123 | Neural networks (cont.) | submission deadline: Fri 13 Nov at 23:59 |
| 11 | Mon 16 Nov | Lecture  |  U141 | Guest lecture | TBD |
|   | Tue 17 Nov | Exercise | A123 | no exercise | |
| 12 | Mon 23 Nov | Lecture  |  U141 | Exercise review session II; course wrap-up | |
|   | Tue 24 Nov | Exercise | A123 | no exercise | |
| 13 | Mon-Fri 30 Nov - 4 Dec | Oral exam |  | | |
| 14 | Mon-Fri 7-11 Dec       | Oral exam |  | | |




