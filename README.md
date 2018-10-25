## Price Cap and Reference Price Auction Experiment
This experiment is an auction experiment where participants hold an object and aim to sell it to a buyer, basing their selling price on a randomly-determined private cost. 

## How to Run the Game 
1. Clone the repository at https://github.com/oTree-org/oTree, which contains the core files necessary to run experiments that are written using the oTree Python framework, into a folder on your local machine.
2. Clone this LeepsCRP repository into the aforementioned folder.
3. Modify the settings.py file and add a dictionary entry in the SESSION_CONFIGS list such that the necessary name, display_name, num_demo_participants, and app_sequence keys are included. The value for the 'name' key must be the exact name of the experiment repository, which is in this csae 'real_effort'. An example is shown below:
   
   {'name': 'LeepsCRP', 'display_name': "Price Cap and Reference Price Auction Experiment", 'num_demo_participants': 16, 'app_sequence': ['LeepsCRP']}
4. Ensure that you're in the folder that you cloned the core oTree files into. Then, type "otree devserver" into the terminal.
5. Navigate to http://localhost:8000/demo/ in your browser.
6. Click on the appropriate experiment based on what you specified this game's display name to be.
7. Click on the session-wide link to begin playing the game.
