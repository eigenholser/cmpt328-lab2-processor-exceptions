Lab 2 - Processor Exceptions
============================

This lab project was developed for the Westminster College Spring 2015 CMPT328
Computer Architecture course.

This was developed using the IAR Systems Embedded Workbench. Some slight
modifications will be necessary for Keil uVision or Code Composer.

Demonstrates processor exceptions in the ARM Cortex M4F as implemented on
the TI Tiva C Series Launchpad Evaluation Kit.

The first 16 entries in the vector table are populated. Create stub exception
handlers for the processor exceptions we don't care about. This is just so
the linker has something to work with. Make it an endless loop using ``B .``
Create an exception handler ``HardFault_Handler`` for the hard fault we will
cause by attempting to write to a memory-mapped address on a clock gated
peripheral that has not yet been enabled.

The lab exercise offers some variations on this code and so there is a bit
extra in here.

