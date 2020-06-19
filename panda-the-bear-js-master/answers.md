#### Answer 1
let profileImage = document.querySelector('.profile-image');
profileImage.src = "https://placebear.com/400/400";

#### Answer 2
let sky = document.querySelector('.photography');
sky.src = "http://placekitten.com/325/225";

#### Answer 3
let name = document.querySelector('h1.highlight');
name.innerText = 'Ari Drookman the Bear';

#### Answer 4
let suitcase = document.querySelector('div#employment .info-title');
suitcase.innerText = 'Hobbies';

#### Answer 5
let color = document.body
color.style.backgroundColor = "Black"

#### Answer 6
var elements = document.querySelectorAll('.highlight');
elements.forEach(x => x.style.backgroundColor = "rgb(252, 54, 64)"); 

#### Answer 7
let fontChange = document.querySelector('h1');
fontChange.style.fontFamily = "monospace";

#### Answer 8
iconColours = document.querySelectorAll('.action-icon-bg');
iconColours.forEach(x => x.style.backgroundColor = "rgb(151, 2, 10)");

#### Answer 9
let enterName = document.querySelector('.contact-info#name');
enterName.placeholder = "Identify yourself!";

#### Answer 10
var enterMessage = document.querySelector('#message');
enterMessage.placeholder = "State your business!";

#### Answer 11
enterName.value = "Your nemesis"

#### Answer 12
var enterEmail = document.querySelector('.contact-info#email');
enterEmail.value = "koalathebear@gmail.com";

#### Answer 13
var submit = document.querySelector('#submit');
submit.value = "En garde!";

#### Answer 14
submit.disabled = true;

#### Answer 15
var info = document.querySelector('.bio-info');
info.hidden = true