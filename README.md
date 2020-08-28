Challenge 1: Using hooks, track the state of the text in the textarea on every keystroke
 
    To verify it's working, you could just console.log the state on every change

 Challenge 2:
   
    Create a function to calculate the number of separate words in the `text` state
    For now, just console.log the word count when the button gets clicked to test it out.
   
Challenge 3:
   
    a. Create state to hold the current value of the countdown timer.
       Display this time in the "Time Remaining" header
    b. Set up an effect that runs every time the `timeRemaining` changes
       The effect should wait 1 second, then decrement the `timeRemaining` by 1
 
       Hint: use `setTimeout` instead of `setInterval`. This will help you avoid
       a lot of extra work.

       Warning: there will be a bug in this, but we'll tackle that next
 
   
Challenge 4:
   
    Make it so clicking the Start button starts the timer instead of it starting on refresh
    (Hint: use a new state variable to indicate if the game should be running or not)
   
Challenge 5:
   
    When the timer reaches 0, count the number of words the user typed in
    and display it in the "Word count" section
  
