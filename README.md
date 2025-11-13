Two React/JSX Demos with slightly different flavors (particularly how the final DOM is rendered - i.e. the last call)

One implements three counters.
The other implements three timers.

Both use useState, but the timer needs to use useEffect. If we don't use useEffect, each timer event creates a NEW TIMER! Holy exponential explosion!

Using these, try to do the following:
1. Implement a calculator (i.e. take the counter javascript and add buttons that do addition, subtraction, multiplication, and division). Use a state variable for the current value.
2. Implement a kitchen timer with variable titles (i.e. you can label each timer) and variable speeds (does it count in seconds, tenths, minutes, etc)
