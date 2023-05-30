===============
Recurring tasks
===============

When handling a project, the same task often needs to be performed several times: for example,
weekly meetings or status reports. The **recurring tasks** feature allows you to automate the
creation of those tasks.

.. seealso::
   `Odoo Tutorials: Recurring tasks <https://www.odoo.com/slides/slide/recurring-tasks-1946>`_

Configuration
=============

To enable recurring tasks feature, go to :menuselection:`Project --> Configuration --> Settings`,
then activate :guilabel:`Recurring Tasks`, and :guilabel:`Save`.

The recurring tasks feature is now activated on all existing projects. It can be deactivated
on an individual project by clicking the ⋮ next to the project name, then going to
:menuselection:`Settings --> Settings --> Task Management` and unchecking the
:guilabel:`Recurring Tasks` checkbox.

Set up task recurrence
----------------------

In an existing task, go to the :guilabel:`Recurrent` tab, then check the :guilabel:`Recurrent` box.
A set of options allows you to configure the frequency: :guilabel:`Days`, :guilabel:`Weeks`,
:guilabel:`Months`, :guilabel:`Years`, and the number of repetitions.

.. tip::
   A new recurrence is created on the scheduled date. To see the task in your project dashboard
   before that, consider setting up the recurrence date to a day earlier.

On the scheduled recurrency date, a new task is created on your project dashboard with the following
configuration:

- :guilabel:`Stage`: first stage of the project dashboard (:guilabel:`New` or equivalent);
- :guilabel:`Name`, :guilabel:`Description`, :guilabel:`Project`, :guilabel:`Assignees`,
  :guilabel:`Customer`, :guilabel:`Tags`: copied from the original task;
- :guilabel:`Milestones`, :guilabel:`Deadline`, :guilabel:`Timesheets`, :guilabel:`Chatter`,
  :guilabel:`Activities`: those fields are not copied;
- :guilabel:`Subtasks`: copied from the original task, which becomes a parent of all the tasks in
  recurrence;
- A **smart button** on the task displays the total number of existing recurrences.

Edit or stop task recurrence
----------------------------

**To edit** the recurrence, open the task: a blue banner invites you to choose whether you wish to
apply your changes to this task only or to a sequence of tasks.

**To stop** the recurrence, open the task, then go to the :guilabel:`Recurrency` tab and deactivate
the :guilabel:`Recurrent` checkbox.
