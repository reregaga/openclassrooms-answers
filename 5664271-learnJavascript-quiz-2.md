[Quiz](https://openclassrooms.com/en/courses/5664271-learn-programming-with-javascript/exercises/3352)
# Check what you've learned about program logic!

## Question 1
**What is the value of  message at the end of this code snippet?
let online = true;
let message = '';

if (online) {
    message = 'User online!';
} else {
    message = 'User offline!';
}**
- [ ] ''
- [x] 'User online!'
- [ ] 'User offline!'

_The condition,online, resolves to  true. Therefore, the code in the if block is executed, while the code in the else statement is not._

## Question 2
**What is the value of  passengersBoarded  at the end of this code snippet?
let passengersBoarded = 0;

if (passengersBoarded &lt;= 10) {
    passengersBoarded += 10;
} else {
    passengersBoarded -= (passengersBoarded - 10);
}**
- [ ] 0
- [ ] -10
- [x] 10

_passengersBoarded is initialized to  0, so the code in the  if block is executed, and the code in the  else block is not._

## Question 3
**What is the value of  passengersBoarded at the end of this code snippet?
let passengersBoarded = 18;

if (passengersBoarded &lt;= 10) {
    passengersBoarded += 10;
} else {
    passengersBoarded -= (passengersBoarded - 10);
}**
- [x] 10
- [ ] 18
- [ ] 0
- [ ] 28

_This time, the code in the  else block is executed.  (passengersBoarded - 10) is 8, so you still get back to a final value of 10._

## Question 4
**What is the value of  welcomeMessage  at the end of this code snippet?
const user = {
    name: 'Will Alexander',
    nationality: 'Scottish'
    accountLevel: 'premium'
};

let welcomeMessage = '';

switch (user.accountLevel) {
    case 'Will Alexander':
        welcomeMessage = 'Hi Will!';
        break;
    case 'Scottish':
        welcomeMessage = 'Och aye the noo!';
        break;
    case 'normal':
        welcomeMessage = 'Welcome back!';
        break;
    case 'premium':
        welcomeMessage = 'Welcome power user!';
        break;
    default:
        welcomeMessage = 'Hello there!';
}**
- [ ] 'Hi Will!'
- [ ] 'Och aye the noo!'
- [x] 'Welcome power user!'
- [ ] 'Hello there!'

_The  switch  statement checks the user's  accountLevel property, which is set to  'premium', so that case is executed._

## Question 5
**What is the value of  vipStatus  at the end of this code snippet?
let vipStatus = '';

let guest = {
    name: 'Sarah Kate',
    age: 21,
    ticket: true,
    guestType: 'artist'
};

switch (guest.guestType) {
    case 'artist':
        vipStatus = 'Normal';
    case 'star':
        vipStatus = 'Important';
        break;
    case 'presidential':
        vipStatus = 'Mega-important';
        break;
    default:
        vipStatus = 'None';
}**
- [ ] 'Normal'
- [x] 'Important'
- [ ] 'Mega-important'
- [ ] 'None'

_Always remember to use  break statements where needed! The lack of  break statement in the  'artist' case makes the  switch  cascade to the following  case, which sets  vipStatus to  'Important'  before breaking out of the  switch._

## Question 6
**How many times will  'Oh hey!'  be logged to the console?
for (let i = 0; i &lt; 5; i++) {
    console.log('Oh hey!');
}**
- [ ] 4
- [x] 5
- [ ] 6

_The loop will execute 5 times, as  i  starts at zero and ends at 5._

## Question 7
**What is the value of  passengersBoarded  at the end of this code snippet?
const passengers = [
    'Will Alexander',
    'Sarah Kate',
    'Audrey Simon',
    'Tau Perkington'
];

let passengersBoarded = 10;

for (let i in passengers) {
    passengersBoarded++;
}**
- [ ] 6
- [ ] 10
- [x] 14
- [ ] 15

_passengersBoarded  starts at 10, and the loop is executed 4 times: once for each passenger. Therefore, the final answer is 14._

## Question 8
**What will the value of  vips  be at the end of this snippet?
const guests = [
    {
        name: 'Will Alexander',
        vip: false
    },
    {
        name: 'Sarah Kate',
        vip: true
    },
    {
        name: 'Audrey Simon',
        vip: true
    },
    {
        name: 'Tau Perkington',
        vip: false
    }
];

let vips = 0;
let normies = 0;

for (let guest of guests) {
    if (guest.vip) {
        vips++;
    }
}**
- [ ] 0
- [ ] 1
- [x] 2
- [ ] 4

_There will be 2  vips, as the loop is run once per guest, and checks each guest's  vip  property._

## Question 9
**How many  guestsSeated  will there be at the end of this snippet?
let guestsSeated = 5;

let seatsRemaining = 10;
let guestsRemaining = 7;

while (seatsRemaining &gt; 0 && guestsRemaining &gt; 0) {
    guestsSeated++;
    seatsRemaining--;
    guestsRemaining--;
}**
- [ ] 5
- [ ] 7
- [ ] 10
- [x] 12

_There are initially 5  guestsSeated. The loop then runs until  guestsRemaining hits zero (which it does before  seatsRemaining hits zero), adding 7 guests, giving a total of 12._