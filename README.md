# Return

if the robot has found food, he returns home. If there is no direction known to go home, he walks random till he tracks the base.
While returning he drops pheromones on the way. Getting to the base he drops the food and starts to search pheromones if he doesn't find for food again.
If he has nothing to track, he walks around random

## Deadlock protection
if he notices that the last 3 visited positions are equal to the current position, he turns around and walks random for 5 steps.