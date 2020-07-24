# COMP790: (Deep) Learning with Limited Labeled Data (DL3D)

Instructor: [Colin Raffel](http://colinraffel.com)  
Meeting time: Mondays and Wednesdays, 2:40-3:55pm

"Deep learning" has produced dramatic advances across a wide variety of domains, including computer vision, natural language processing, speech recognition, and beyond.
Applying deep learning typically involves training a model using a large labeled dataset.
The reliance on a labeled data can be an issue, particularly in applications where labeling involves paying a human expert.
However, there have been many recent advances that substantially mitigate the need for labeled data.
In this course, we'll read and discuss the papers proposing these methods, with a particular focus on semi-supervised and transfer learning methods applied to computer vision and natural language processing.

The structure of this course and some of the materials are based on [Alec Jacobson](http://www.cs.toronto.edu/~jacobson/)'s [CSC2521](https://github.com/alecjacobson/seminar-on-geometry-and-animation) course at the University of Toronto.

## Prerequisites

Students must have experience with machine learning (preferably deep learning), including the necessary mathematical background (linear algebra and statistics) as well as the ability to implement machine learning algorithms.
Before taking the class, you should be able to read a recent machine learning conference paper and come away with a decent understanding of the basic concepts and ideas proposed in the paper (but not necessarily a deep, perfect understanding of every last detail).

## Course Structure

This class is mainly a paper-reading seminar covering recent important papers on the subject of (deep) learning from limited labels.
There will also be an open-ended final project that will involve extending some of the papers we read in the class through additional experiments and a short write-up.

### Readings

For much of the semester, each class will involve the presentation and discussion of one paper.
Before each class, everyone is required to have read the paper.
Students will be divided into two groups.
One group of students will present on Mondays and the other on Wednesdays.
In a given class session, students in the presenting group will each be given a rotating role (described below).
This role defines the lens through which they read the paper and determines what they prepare for the group in-class discussion.
Students in the non-presenting group are also required to read the paper, complete a quick exercise (described below), and come to class ready to discuss.
All students will obtain a thorough understanding of the chosen papers and will develop their paper reading, literature review, and prototyping skills.

#### Presentation roles

This seminar is organized around the different "roles" students play each week:
Reviewer, Archaeologist, Researcher, Practitioner, Hacker, and Private Investigator.

  - **Reviewer:** Complete a full---critical but not necessarily negative---review of the paper. Follow the [guidelines for NeurIPS reviewers](https://nips.cc/Conferences/2020/PaperInformation/ReviewerGuidelines) and in particular answer all of the questions under "Review Content".
  - **Archaeologist:** Determine where this paper sits in the context of previous and subsequent work. Find and report on one prior paper that substantially influenced the current paper and one newer paper that cites this current paper.
  - **Researcher:** Propose an imaginary follow-up project -- not just based on the current but only possible due to the existence and success of the current paper.
  - **Practitioner:** Propose a new application for the method in the paper (not already discussed in class), and discuss at least one positive and negative impact of this application.
  - **Hacker:** Implement a small part of the paper on a small dataset or toy problem. Prepare to share the core code of the algorithm to the class.
  - **Private Investigator:** Find out background information on one of the paper authors. Where have they worked? What did they study? What previous projects might have led to working on this one? What do you think motivated them to work on this project? Feel free to contact the authors, but remember to be courteous, polite, and on-topic. Write that you're in Prof. Raffel's seminar and include a link to this page.

#### Non-presenter assignment

If you aren't in the presenting group during a given class period, please come to class with:
  1. A new title for the paper and/or a new name for the algorithm it proposes
  1. At least one question about the paper (either something you're confused about or something you'd like to hear discussed more)
  
### Final Project

All students in the class will write a "mini-paper" as a final project.
The paper should extend one or more papers we covered in the class.
Students should write code and carry out additional experiments and then write up the results in a standard conference paper format.

Students are welcome to work in groups on the final project.
I will expect a group of two students to put twice as much work into the final project than for a sole-author project, and similarly for larger groups.
I'd encourage students to not work alone and I won't allow groups with five or more people without special permission.
Students in groups are required to include a "contributions" paragraph in their paper that concretely lists each author's contributions.
The maximum paper length for a given final project write-up is `3 + n_students` *not including references or the contributions paragraph*, where `n_students` is the number of people in the group that worked on the project.

All groups will be required to submit a project proposal by the start of class on October 19th.
The project proposal is a single-paragraph description of what you intend to do (experiments, datasets, methods, etc.)
Groups will present their final projects during the final exam period.
All students in each group are required to present some material during the final presentation.

## Schedule

We will choose the specific list of papers that we will read based on popular vote in the first week of class.
You can view the list of papers that we will choose from [here](https://github.com/craffel/dl3d-seminar/blob/master/paper-list.md).
I will fill in the schedule with the papers we've chosen once we've voted.

| Date | Content |
|----|----|
| Mon, 8/10 | Course introduction, logistics, and background lecture |
| Wed, 8/12 | Course introduction continued |
| Mon, 8/17 | Paper discussion |
| Wed, 8/19 | Paper discussion |
| Mon, 8/24 | Paper discussion |
| Wed, 8/26 | Paper discussion |
| Mon, 8/31 | Paper discussion |
| Wed, 9/2 | Paper discussion |
| Mon, 9/7 | No class (labor day) |
| Wed, 9/9 | Paper discussion |
| Mon, 9/14 | Paper discussion |
| Wed, 9/16 | Paper discussion |
| Mon, 9/21 | Paper discussion |
| Wed, 9/23 | Paper discussion |
| Mon, 9/28 | Paper discussion |
| Wed, 9/30 | Paper discussion |
| Mon, 10/5 | Paper discussion |
| Wed, 10/7 | Paper discussion |
| Mon, 10/12 | Paper discussion |
| Wed, 10/14 | Paper discussion |
| Mon, 10/19 | Project proposals due, paper discussion |
| Wed, 10/21 | Paper discussion |
| Mon, 10/26 | Paper discussion |
| Wed, 10/28 | Paper discussion |
| Mon, 11/2 | Paper discussion |
| Wed, 11/4 | Paper discussion |
| Mon, 11/9 | Paper discussion |
| Wed, 11/11 | Guest lecture |
| Mon, 11/16 | Guest lecture |
| Final exam slot | Final project presentations |

## Grading

  1. **Readings**, 60 points: There will be 24 papers, and each student will be in the presenting role for 12 and the non-presenting role for the other 12. You can earn up to 4 points each time you present for completing the assignment for your role and presenting it to the class. When you aren't presenting, you can earn up to 1 point by completing the non-presenting assignment and by participating in the class through live discussion and questions.
  1. **Final Project**, 40 points: This grade will be divided into the following categories:
      - Proposal: 5 points.
      - Novelty: 5 points; your project should propose something new (either a new application, method, or perspective).
      - Writing: 10 points; your paper should be readable and complete and situate its self appropriately among related work. You should use the format and style of a standard machine learning conference paper.
      - Presentation: 10 points; your final project presentation should be clear and provide a solid picture of what you did.
      - Code: 10 points; the code you write and submit for your final project should allow for complete reproduction of your results and be well-documented.
  
## Attendance, late work, and the honor code

If you miss a class without completing the corresponding assignment, you'll get a zero for that session.
If you miss a class where you are in a "presenting" role for that session, you're still expected to create the presentation for that role.
You'll also be responsible for finding someone else to present it.
If you miss a class where you'd be in a "non-presenting" role, to get full credit for that session you need to complete the non-presenting assignment and let me know a day in advance.
If you complete the non-presenting assignment but miss class, you'll receive at most half credit for that session.

There's really no way to accept late work for the readings since it's vital that we're all reading the same papers at the same time.
I also can't accept the final project after the scheduled final exam slot since you need to present it then.

All students are expected to follow the guidelines of the [UNC honor code](http://honor.unc.edu).
In the context of this class, it is particularly important that you cite the source of different ideas, facts, or methods and do not claim someone else's work as your own.
If you are unsure about which actions violate that honor code, feel free to ask me.

## Conduct

I ask that we all follow the [NeurIPS Code of Conduct](https://nips.cc/public/CodeOfConduct) and the [Recurse Center Social Rules](https://www.recurse.com/social-rules).
Since this is a discussion class, it's especially important that we respect everyone's perspective and input.
In particular, I value the perspectives of individuals from all backgrounds reflecting the diversity of our students.
I broadly define diversity to include race, gender identity, national origin, ethnicity, religion, social class, age, sexual orientation, political background, and physical and learning ability.
I will strive to make this classroom an inclusive space for all students.
Please let me know if there is anything I can do to improve.

Acts of discrimination, harassment, interpersonal (relationship) violence, sexual violence, sexual exploitation, stalking, and related retaliation are prohibited at UNC-Chapel Hill.
If you have experienced these types of conduct, you are encouraged to report the incident and seek resources on campus or in the community.
Please contact the Director of Title IX Compliance/Title IX Coordinator (Adrienne Allison, adrienne.allison@unc.edu), Report and Response Coordinators (Ew Quimbaya-Winship, eqw@unc.edu; Rebecca Gibson, rmgibson@unc.edu; Kathryn Winn kmwinn@unc.edu), Counseling and Psychological Services (CAPs) (confidential) in Campus Health Services at (919) 966-3658, or the Gender Violence Services Coordinators (confidential) (Cassidy Johnson, cassidyjohnson@unc.edu; Holly Lovern, holly.lovern@unc.edu) to discuss your specific needs.
Additional resources are available at http://safe.unc.edu.

## Resources

The University of North Carolina at Chapel Hill facilitates the implementation of reasonable accommodations, including resources and services, for students with disabilities, chronic medical conditions, a temporary disability or pregnancy complications resulting in difficulties with accessing learning opportunities.
All accommodations are coordinated through the Accessibility Resources and Service Office. See the ARS Website for contact information: https://ars.unc.edu or email ars@unc.edu.
Relevant policy documents as they relate to registration and accommodations determinations and the student registration form are available on the ARS website under the About ARS tab.

CAPS is strongly committed to addressing the mental health needs of a diverse student body through timely access to consultation and connection to clinically appropriate services, whether for short or long-term needs. Go to their [website](https://caps.unc.edu/) or visit their facilities on the third floor of the Campus Health Services building for a walk-in evaluation to learn more.

## Changes

I reserve the right to make changes to the syllabus, including project due dates and test dates.
These changes will be announced as early as possible.

