.. _Checking Student Progress and Issuing Certificates:

###############
Ending a Course
###############
.. This chapter will be renamed and expanded to include course wrap-up activities and best practices.

This topic describes how to complete several end-of-course tasks.

.. contents::
   :local:
   :depth: 1

For more information, see the following other topics about certificates.

* :ref:`Setting Up Course Certificates`
* :ref:`Reporting Certificate Data`

****************************************
Send Farewell Message
****************************************

As you prepare for the end of your course, you can send learners a :ref:`course
farewell<Course Farewell and Certificates>` email message.

*******************
Assign Final Grades
*******************

To assign a final grade to each learner enrolled in a course, you generate
grades after the course end date and time have passed. For more information,
see :ref:`Access_grades`.

The learner's final grade and the grading configuration you set in Studio
determine whether the learner has earned a certificate for the course.

******************
Issue Certificates
******************

Typically, you generate and issue certificates after the course ends. However,
for self-paced courses, you can allow your learners to request and download
on-demand certificates as soon as they have completed enough of the course
with a high enough grade to qualify for a certificate.


===================================================================
Generate Certificates for Instructor-Paced and Self-Paced Courses
===================================================================

.. only:: Partners

   To generate certificates for your course, work with your edX partner
   manager.

.. only:: Open_edX

   To generate certificates for your course, work with the administrator of
   your instance of Open edX.

====================================================
Enable On-Demand Certificates for Self-Paced Courses
====================================================

If you want your learners to be able to receive their certificates as soon as
they qualify for a certificate, you must change an LMS setting to allow
learners to request certificates, and then change a Studio setting to allow
learners to download their certificates.

.. only:: Partners

  For information about how learners request certificates, see
  :ref:`learners:SFD On Demand Certificates`.

Allow Learners to Request On-Demand Certificates
************************************************

To allow learners to request certificates, follow these steps.

#. View the live version of your course.

#. In the LMS, select **Instructor**, and then select **Certificates**.

#. Select **Enable Student-Generated Certificates**.

   When they have qualified, learners can request their certificates from the
   **Progress** page.

   To prevent learners from requesting certificates, select **Disable Student-
   Generated Certificates**.

Allow Learners to Download On-Demand Certificates Before the Course Ends
************************************************************************

Typically, learners can only download their certificates after the course ends.
To allow learners to download on-demand certificates when they qualify for
them, you must modify the **Certificates Display Behavior** advanced setting in
Studio.

#. In Studio, on the **Settings** menu, select **Advanced Settings**.

#. On the **Advanced Settings** page, locate **Certificates Display Behavior**.

#. In the **Certificates Display Behavior** field, enter ``"early_no_info"``.
   Be sure that you include the double quotation marks.

#. Select **Save Changes**.


Communicate to Learners about Requesting Certificates
*****************************************************

If your course offers on-demand certificates, we encourage you to include this
information on your course About page, on the **Home** page, and in
communication with your learners.

.. only:: Partners

   Course teams should also discuss additional self-paced settings with their
   edX partner manager during the course announcement process.
