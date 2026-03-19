# Guide-robot-Keenon
Создание программного обеспечения для робота- экскурсовода на основе робота Keenon 

## 1 PROJECTION
### We, as cool business analysts, must find out the requirements from our beloved lab owner: what are the expectations from the final product (software/functional)
* How does the tour proceed/is it controlled by a fantastic tour guide (taking into account the trajectory; there's a guide with a remote control who controls/starts the tour)
* How should the trajectory/circle be set?
* Should the audience (people) be identified?
### Find out the available software components//go to the lab to collect information (what it's written in, what it supports)
### Create a development plan: select libraries, consider that the user must be able to expand the tour program (external software, remote control, or downloading a database containing exhibits, the corresponding program (update)
PS. There must be a cool person who will update the tour program programmatically, or learn how to adapt it).
### Based on the information collected, begin developing components, testing, and gradually recording the results.
If the project is unfinished, draw up a plan for the missing developed elements (report).
### Design the results, the user's upload method

Мы вапще-то сами придумали!
## 2 RESULT Promotion
After reviewing our super-waiter's documentation, we, like responsible students, got to work on the project in the classroom lab. We managed to figure out how to create our own map, adjust it, place fences, and assign stopping points, and even launched test routes in practice. We're truly amazing—the results are available at this link:
[Video report](https://drive.google.com/drive/folders/1fNvKaHVhsuuSYGf5xpiLR8Y7fz7URTRt?usp=drive_link)

Мы вапще-то крутышки!

## 3 Guided tour
### To advance our waiter modification work, we decided to explore our super lab and create a tour of it, with corresponding text at the appropriate stops.
[Excursion text](https://github.com/Katapo13/Guide-robot-Keenon/blob/main/%D0%A2%D0%95%D0%9A%D0%A1%D0%A2%20%D0%AD%D0%9A%D0%A1%D0%9A%D0%A3%D0%A0%D0%A1%D0%98%D0%98.docx)

### Since our robot cannot reproduce text on its own, we have prepared a voiceover for the corresponding route: at the point there is a corresponding audio accompaniment
[Excursion audio](https://drive.google.com/drive/folders/1k_Q0Nts54swbHzKWSY5EaTY6Tia4i7sw?usp=sharing)

Вот такие пироги, дефчонки тащат!

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

