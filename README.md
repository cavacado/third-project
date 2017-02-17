# Handy

This is the repository of our 3rd project from WDI immersive course. This is a full-stack web application, utilising technologies from the front end (HTML,CSS,JS) and back end (ruby on rails and many other gems).

Our idea is a technological platform to connect many pairs of hands to many jobs.

The main problem that it is trying to solve is that we realised that many Contractors or Handy People are quite tech-deficient, on the mechanical skills end, they are professionals in those hard skills.

On the flip side, many Consumers (or Human Beings) are tech-savvy but unlikely to be proficient in mechanical skills.

Link to deployed heroku page is here : https://floating-retreat-48742.herokuapp.com/login

## Getting Started

Provide instructions here about how to get your project running on our local machine. Do we just need to clone and open a certain file or do we need to install anything first.

### How to Use

User Flow:
Create an account, go into the index page, there will be a handful of listings(Handy-man profiles to click on)
Click on the selected Handy-man and view his schedule. This will be displayed on the right, also you can submit a new enquiry to the handyman and you will be redirected to a chat page in order to further the enquiry.
Users can also create his/her's profile and curate it well.

Any user can become a freelancer by clicking on the button that appears on the right hand side on the nav bar.
This is distinctly similar to AirBnb's become a host button.

Freelancer Flow:
For the freelancer's part, he is able to access his own pending enquiry. He can also define his own schedule which will automatically populate his calendar via the IceCube gem. His working hours will also be reflected.

In order to further the enquiry, the freelancer can click on the pending enquiry and continue the liason with the specific user via the chat menu.
Freelancer can then accept and finalise the deal which will book a slot in his own calendar.
This will be updated accordingly via the simple calendar.

## Tests

No tests were written during the development of this program. Future collaboration efforts should include integration tests and view tests and the whole test suite.

## Live Version

Where is this deployed online (github pages, heroku etc), give us the link and any access details we need.

the website is hosted live @ this link : https://floating-retreat-48742.herokuapp.com/login

## Built With

What did you use to build it, list the technologies, plugins, gems, packages etc.

* gem 'bootstrap3-datetimepicker-rails', '~> 4.17.43'
* gem 'acts_as_bookable'
* gem "simple_calendar", "~> 2.0"
* gem 'bootstrap-sass', '~> 3.2.0'
* gem 'autoprefixer-rails'
* gem 'bootstrap_form'
* gem 'cloudinary'
* gem "httparty"
* gem 'redis'


## Workflow

Workflow was mainly the team doing a heavily modified GitFlow workflow.
2 core teams split to tackle the 2 different core functionality.
Yi Sheng and Sharona teamed up to tackle the chat and location functionality.
Andrew and Zhao Loong teamed up to tackle the booking and scheduling functionality

## Authors

Yi Sheng, Sharona, Andrew and Zhao Loong

## Further Extensions

Further extensions will make the application more mobile responsive; currently it is not. It's only desktop functional.

Currently the calendar integrated into the application is simple calendar from the simple calendar gem. It is currently more referential than responsive. A possible extension would be to integrate the calendar and schedule functionality into full calendar. There, combined with AJAX requests and other front end functionality, the calendar and schedule would be more robust.

Another extension that we could explore is that currently our location functionality is pretty parse. Searching by location could be a possible direction to take for our application.

## References and Acknowledgments:

* https://github.com/tandusrl/acts_as_bookable
* https://github.com/seejohnrun/ice_cube
* https://github.com/excid3/simple_calendar
* Action Cable
