
# Examples Overview

Welcome to the documentation for the Quartz Example programs. Quartz ships with 13 out-of-the-box examples that demonstrate the various features of Quartz and the Quartz API.


## [Where to Find the Examples](#ExamplesOverview-WheretoFindtheExamples)

All of the examples listed below are part of the [Quartz distribution](../downloads.adoc). Or directly from the [Quartz source code](../../distribution/examples/src/main/java/org/quartz/examples)

The quartz examples are listed under the **examples** directory under the main Quartz directory.  Under the **examples** directory, you will find an example sub-directory for each example, labeled **example1**, **example2**, **example3** etc...

Every example contains UNIX/Linux shell scripts for executing the examples as well at Windows batch files.   Additionally, every example has a readme.txt file.  Please consult this file before running the examples.

The source code for the examples are located in package **org.quartz.examples**.   Every example has its own sub-package, **org.quartz.examples.example1**, **org.quartz.examples.example2**, etc...

Here we give an overview of each example program:

## [The Examples](#ExamplesOverview-TheExamples)

<table>
  <thead>
    <tr>
    <th> Title </th>
    <th> Description </th>
    </tr>
  </thead>
  <tbody>
    <tr>
    <td>Example 1 - <a href="Example1.md">First Quartz Program</a></td>
    <td> Think of this as a "Hello World" for Quartz </td>
    </tr>
    <tr>
    <td> Example 2 - Simple Triggers </td>
    <td> Shows a dozen different ways of using Simple Triggers to schedule your jobs </td>
    </tr>
    <tr>
    <td> Example 3 - <a href="Example3.md">Cron Triggers</a> </td>
    <td> Shows how Cron Triggers can be used to schedule your job </td>
    </tr>
    <tr>
    <td> Example 4 - <a href="Example4.md">Job State and Parameters</a></td>
    <td> Demonstrates how parameters can be passed into jobs and how jobs maintain state </td>
    </tr>
    <tr>
    <td> Example 5 - <a href="Example5.md">Handling Job Misfires</a> </td>
    <td> Sometimes job will not execute when they are supposed to.  See how to handle these Misfires </td>
    </tr>
    <tr>
    <td> Example 6 - <a href="Example6.md">Dealing with Job Exceptions</a> </td>
    <td> No job is perfect.  See how you can let the scheduler know how to deal with exceptions that are thrown by your job </td>
    </tr>
    <tr>
    <td> Example 7 - Interrupting Jobs </td>
    <td> Shows how the scheduler can interrupt your jobs and how to code your jobs to deal with interruptions </td>
    </tr>
    <tr>
    <td> Example 8 - Fun with Calendars </td>
    <td> Demonstrates how a Holiday calendar can be used to exclude execution of jobs on a holiday </td>
    </tr>
    <tr>
    <td> Example 9 - Job Listeners </td>
    <td> Use job listeners to have one job trigger another job, building a simple workflow </td>
    </tr>
    <tr>
    <td> Example 10 - Using Quartz Plug-Ins </td>
    <td> Demonstrates the use of the XML Job Initialization plug-in as well as the History Logging plug-ins </td>
    </tr>
    <tr>
    <td> Example 11 - Quartz Under High Load </td>
    <td> Quartz can run a lot of jobs but see how thread pools can limit how many jobs can execute simultaneously </td>
    </tr>
    <tr>
    <td> Example 12 - Remote Job Scheduling using RMI </td>
    <td> Using Remote Method Invocation, a Quartz scheduler can be remotely scheduled by a client </td>
    </tr>
    <tr>
    <td> Example 13 - Clustered Quartz </td>
    <td> Demonstrates how Quartz can be used in a clustered environment and how Quartz can use the database to persist scheduling information </td>
    </tr>
    <tr>
    <td> Example 14 - <a href="Example14.md">Trigger Priorities</a> </td>
    <td> Demonstrates how Trigger priorities can be used to manage firing order for Triggers with the same fire time </td>
    </tr>
    <tr>
    <td> Example 15 - TC Clustered Quartz  </td>
    <td> Demonstrates how Quartz can be clustered with Terracotta, rather than with a database </td>
    </tr>
  </tbody>
</table>
