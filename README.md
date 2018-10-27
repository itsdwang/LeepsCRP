## Price Cap and Reference Price Auction Experiment
This experiment is an auction experiment where participants hold an object and aim to sell it to a buyer, basing their selling price on a randomly-determined private cost. 

## How to Run the Game 
1. Clone the repository at https://github.com/oTree-org/oTree, which contains the core files necessary to run experiments that are written using the oTree Python framework, into a folder on your local machine.
2. Navigate to the oTree directory.
3. Clone this LeepsCRP repository into the oTree folder
4. Run the "pip3 install -U otree" command in terminal. 
5. Modify the settings.py file and add a dictionary entry in the SESSION_CONFIGS list such that the necessary name, display_name, num_demo_participants, and app_sequence keys are included. The value for the 'name' key must be the exact name of the experiment repository, which is in this case 'LeepsCRP'. The value of the 'num_demo_participants' key must be 4. An example is shown below:
   
   {'name': 'LeepsCRP', 'display_name': "Price Cap and Reference Price Auction Experiment", 'num_demo_participants': 4, 'app_sequence': ['LeepsCRP']}
6. Ensure that you're in oTree folder. Then, type "otree devserver" into the terminal.
7. Navigate to http://localhost:8000/demo/ in your browser.
8. Click on the appropriate experiment based on what you specified this game's display name to be.
9. Click on the session-wide link to begin playing the game.
