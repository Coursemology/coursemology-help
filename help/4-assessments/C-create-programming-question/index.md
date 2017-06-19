---
layout: page
permalink: /assessments/create-programming-question
title: 4c. Create a Programming Question
---

To create a programming question:
  1. Navigate to the assessment
  2. Click **New** and select **programming** in the dropdown
  3. Fill in the details (make sure you select the correct programming language!)

![4C-1]({{ site.baseurl }}/images/4C-1.gif)

To make it autograded, toggle the **Autograded** bar, and an editor should show up on screen.
  1. Write into the submission template (what the student sees)
  2. Write into the solution template (the correct solution to the question)

![4C-2]({{ site.baseurl }}/images/4C-2.gif)

Following which, you can create public and private test cases for the code by clicking **Add New Test**

Minimally, you will need to fill in the fields:
  * **Expression**
  * **Expected**

![4C-3]({{ site.baseurl }}/images/4C-3.gif)

[previous]({{ site.baseurl }}/assessments/create-question)

[next]({{ site.baseurl }}/assessments/student-instructor-view)

{% capture previous_url %} {{ site.baseurl }}/assessments/create-question {% endcapture %}
{% capture previous_title %} 4b. Create MCQ / MRQ {% endcapture %}

{% capture next_url %} {{ site.baseurl }}/assessments/student-instructor-view {% endcapture %}
{% capture next_title %} 4d. Student / Instructor's View {% endcapture %}

{% include page-nav.html %}
