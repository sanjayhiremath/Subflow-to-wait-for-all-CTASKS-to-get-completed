# Subflow-Utility
Subflow to wait for all the CTASKS to get completed

1. Developed a reusable subflow to wait until all catalog tasks are either closed complete or closed
incomplete.

2. Enabled integration of this subflow with any flow requiring catalog task completion tracking.
   
3.  Implemented logic to monitor active tasks, ensuring execution pauses until task completion
before returning a success value.

4. Designed the subflow to return a false value when no active tasks are found, improving flow
accuracy and reliability.


5.  Subflow inputs: ritm – Reference to requested item (sc_req_item)

   
6. Subflow outputs: Output – Boolean

<img width="628" height="324" alt="image" src="https://github.com/user-attachments/assets/f35ef7e1-bcb8-47d6-a0da-7fe9a612fb4e" />

Subflow Snapshot:

  <img width="375" height="379" alt="image" src="https://github.com/user-attachments/assets/84d5abeb-b620-4de6-84df-2d1d812ac854" />





