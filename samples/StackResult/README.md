StackResult
===========

This sample models a stack, in a different style than the *Stack*
sample.

The contents are:

- *Stack*: model program.  Here, the return value of the *Pop* action
  is modeled in the action as a return value, not an argument.  As a
  result, its enabling condition *PopEnabled* cannot constrain the
  return value.  However, the *Pop* action itself determines the
  correct return value.

- *test*: like in *Stack* sample

- *Filter3*, *StackDepthTen*: configurations that define *StateFilters* that limit
   stack depth

- *StackOneScenario*: scenario machine that limits actions to
   particular argument values

- *test_graphics*: similar to *Stack* sample

- *fsmpy*, *svg*: FSMs and graphics files generated by the graphics
   test scripts

View the generated graphics files in a browser.  They are similar to
the *Stack* sample.  

- compare *Stack3FSM.svg* to *StackFSM.svg* to see the effect of
  limiting exploration with a *StateFilter*, compared to the *pmt -m*
  option.

This sample does not include a stepper.


Revised Mar 2013