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

This website contains links to the teaching material and the schedule (see below). The [MyCourses](https://mycourses.aalto.fi/user/index.php?id=49017) website will be used only for organizational purposes, such as group creation and exercise assignments (material, report submissions and peer grading). 

Note that **this course is *not* designed to be an online course**: the primary venue to have your questions answered by the teacher and the TAs, and to get regular feedback on your work, is to physically attend the lectures and the exercise sessions. A dedicated Zulip course chat (link in MyCourses, login with Aalto account) will be used for important announcements, and for asking questions not yet answered during the lectures or exercise sessions.

The course is heavily focused on solving actual exercises in NumPy/Python (five in total, each split into an initial "easy" and a subsequent "difficult" part). These exercises will be performed in groups of 2 students. The course grading is based mainly on report scores given by the course personnel (teacher and teaching assistants), after an initial peer grading by fellow students for the "difficult" parts of the exercises. 

Participating in the peer grading is required to pass the course, and helping to answer fellow students' questions in the Zulip chat is encouraged (and will be viewed positively in the grading). Each student should also participate in student presentations where the submitted solutions to the "difficult" parts of the exercises are analyzed and discussed in class.


## Schedule

For the fall 2025 semester, lectures will be held on Thursdays 12.15–14.00 in Health Technology House, Auditorio - F239a. Exercise sessions with teaching assistants present will be held immediately following the lectures (14:15-16:00) in Nanotalo room 228.

> Note: no exercise sessions will be organized on Thu 20 Nov and Thu 27 Nov.


A detailed schedule is given below:

| Week |  Date | Activity | Location | Topic |  |
| --- | ---   | ---      | ---   | --- | --- |
| 1 | Thu 4 Sep | Lecture  |  F239a | Introduction; Image smoothing and interpolation | - chapter 1 in the book ([html](book/html/index.html?page=5) [pdf](book/mia.pdf)) <br/> - introduction: [html](lecture_slides/introduction/html/index.html) [pdf](lecture_slides/introduction/intro.pdf) <br/> - slides: [html](lecture_slides/smoothing_and_interpolation/html/index.html) [pdf](lecture_slides/smoothing_and_interpolation/smoothing_and_interpolation.pdf) <br/> - lecture [recording](https://aalto.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=a7f7f745-90fc-4d09-9d99-b1e600985360) |
|   | Thu 4 Sep | Exercise | Nanotalo 228 | Smoothing and interpolation (first part) | submission deadline: Wed 10 Sep at 23:59 |
| 2 | Thu 11 Sep | Lecture  |  F239a | Coordinate systems, linear spatial transformations, landmark-based registration | - sections 2.1-2.3 in the book ([html](book/html/index.html?page=19) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/landmark_based_registration/html/index.html) [pdf](lecture_slides/landmark_based_registration/landmark_based_registration.pdf) <br/> - lecture [recording](https://aalto.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=1ba65dbd-ff20-4358-9a7a-b1ed0098c11d)  |
|   | Thu 11 Sep | Exercise | Nanotalo 228 | Smoothing and interpolation (second part) | submission deadline: Wed 17 Sep at 23:59 |
| 3 | Thu 18 Sep | Lecture  |  F239a | Intensity-based registration | - section 2.4 in the book, excluding Gauss-Newton optimization ([html](book/html/index.html?page=27) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/intensity_based_registration/html/index.html) [pdf](lecture_slides/intensity_based_registration/intensity_based_registration.pdf) <br/> - lecture [recording](https://aalto.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=59da6aba-ad83-4838-9577-b1f40099b4f9) |
|   | Thu 18 Sep | Exercise | Nanotalo 228 | Linear registration (first part) | submission deadline: Wed 24 Sep at 23:59 |
| 4 | Thu 25 Sep | Lecture  |  F239a | Student presentation: smoothing and interpolation exercise | |
|   | Thu 25 Sep | Exercise | Nanotalo 228 |  Linear registration (second part) | submission deadline: Wed 1 Oct at 23:59 |
| 5 | Thu 2 Oct | Lecture  |  F239a | Nonlinear registration | - sections 2.2.2 and 2.4 in the book, especially Gauss-Newton optimization ([html](book/html/index.html?page=25) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/nonlinear_registration/html/index.html) [pdf](lecture_slides/nonlinear_registration/nonlinear_registration.pdf) <br/> - lecture [recording](https://aalto.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=a7a1e6ac-1621-4c55-8fa5-b1fb0099319a)  |
|   | Thu 2 Oct | Exercise | Nanotalo 228 | Nonlinear registration (first part) | submission deadline: Wed 8 Oct at 23:59 |
| 6 | Thu 9 Oct | Lecture  |  F239a | Student presentation: Linear registration exercise; Model-based segmentation I | - sections 3.1-3.3 in the book ([html](book/html/index.html?page=35) [pdf](book/mia.pdf)) <br/> - probability refresher: [html](lecture_slides/model_based_segmentation_I/html_refresher/index.html) [pdf](lecture_slides/model_based_segmentation_I/refresher_on_probability.pdf) <br/> - slides: [html](lecture_slides/model_based_segmentation_I/html/index.html) [pdf](lecture_slides/model_based_segmentation_I/model_based_segmentation_I.pdf) <br/> - lecture [recording](https://aalto.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=de8f4418-c466-482c-92f4-b20200997a94) |
|   | Thu 9 Oct | Exercise | Nanotalo 228 | Nonlinear registration (second part) | submission deadline: Wed 22 Oct at 23:59 |
| 7 | Thu 23 Oct | Lecture  |  F239a | Model-based segmentation II | - sections 3.4-3.5 in the book ([html](book/html/index.html?page=44) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/model_based_segmentation_II/html/index.html) [pdf](lecture_slides/model_based_segmentation_II/model_based_segmentation_II.pdf) |
|   | Thu 23 Oct | Exercise | Nanotalo 228 | Model-based segmentation (first part) | submission deadline: Wed 29 Oct at 23:59 |
| 8 | Thu 30 Oct | Lecture  |  F239a | Student presentation: Nonlinear registration exercise | |
|   | Thu 30 Oct | Exercise | Nanotalo 228 | Model-based segmentation (second part) | submission deadline: Wed 5 Nov at 23:59 |
| 9 | Thu 6 Nov | Lecture  |  F239a | Neural networks | - chapter 4 in the book ([html](book/html/index.html?page=55) [pdf](book/mia.pdf)) <br/> - slides: [html](lecture_slides/neural_networks/html/index.html) [pdf](lecture_slides/neural_networks/neural_networks.pdf) <br/> - lecture [recording](https://aalto.cloud.panopto.eu/Panopto/Pages/Viewer.aspx?id=0d54885a-8f21-453c-94f5-b21e00aa3756) |
|   | Thu 6 Nov | Exercise | Nanotalo 228 | Neural networks (first part) | submission deadline: Wed 12 Nov at 23:59 |
| 10 | Thu 13 Nov | Lecture  |  F239a | Student presentation: Model-based segmentation exercise | |
|   | Thu 13 Nov | Exercise | Nanotalo 228 | Neural networks (second part) | submission deadline: Wed 19 Nov at 23:59 |
| 11 | Thu 20 Nov | Lecture  |  F239a | Guest lecture | Hannu Laaksonen, Varian (Siemens Healthineers) |
| 12 | Thu 27 Nov | Lecture  |  F239a | Student presentation: Neural networks exercise. Course wrap-up | |



