# Guide-robot-Keenon
Создание программного обеспечения для робота- экскурсовода на основе робота Keenon 

## 4 Robot's modes
After the tour is complete, we need to select a convenient mode: the robot has several delivery modes, and not all of them are suitable for us. We'll conduct a comparative analysis of the modes for further implementation.

### Delivery Mode
Delivery Mode is the primary mode for transporting items. A route is created, and orders are delivered along it.
We select pickup points for the "dining table." Pickup is done by "pickup and collect" (saying, "Here's your food, please take it"). Diners acknowledge receipt, and the server either returns to the pickup point or moves on to the next table. Regarding sound: each table *CANNOT* have its own sound; the sound can only be changed during service.

### Birthday Mode
Birthday Mode is a mode for creating a festive atmosphere. Includes music, animation, and on-screen greetings.
In the actual mode, we play a *SINGLE* sound for congratulations with a picture of a cake. In our case, we need at least the ability to play multiple sounds.

### Greeting Mode
Greeting Mode is a meeting and communication mode. The robot greets and accompanies guests. *If in practice the chosen accompaniment route can be operated with several sounds, then this can be worked with* "Click on the greeting, and the greeting route will be displayed. The robot will greet guests along the specified route." (If there's only one greeting, this option is also not suitable.) 

### Dish Return Mode
Immediately missed: the functionality does not allow for the task to be implemented immediately.

### Promotion Mode
Promotion Mode is an advertising display mode. Promotional videos and information are displayed on the screen.
You can create a promotional route that will become a tour: point - voiceover, you can also play around with the media.

### Of the modes considered, only two can be retained for further development: greeting and promotion. All that remains is to put them all into practice.

Мы ввопще-та молодцы, вот так вот:)
