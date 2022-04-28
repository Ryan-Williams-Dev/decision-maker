Decision Maker
=========

The Decision Maker is an app that allows users to create a question and collect votes from their friends. When the user creates their poll, they are sent an email with links to a voting page and a results page. Every time someone votes on their poll they are notified by email. The results page displays the options in order of the most poplular rankings. 


## Getting Started

1. Install dependencies: `npm i`
2. To receive emails, open routes/polls.js and replace all instances of "decisions.lhl@gmail.com" with your own email.  
3. Run the server: `npm run local`
4. Visit `http://localhost:8080/`


## Dependencies

- Node 10.x or above
- NPM 5.x or above
- PG 6.x
- Express
- Morgan
- Mailgun-JS

## Final Product

!["Create a poll main page"](https://github.com/rkrowchuk/decision-maker/blob/master/docs/01-DecisionMaker.jpg?raw=true)
!["Vote on your poll"](https://github.com/rkrowchuk/decision-maker/blob/master/docs/04-decisionMaker.jpg?raw=true)
!["Email sent when someone votes on your poll"](https://github.com/rkrowchuk/decision-maker/blob/master/docs/02-decisionMaker.jpg?raw=true)
!["Poll results page"](https://github.com/rkrowchuk/decision-maker/blob/master/docs/03-deicionMaker.jpg?raw=true)

## Team
Built in collaboration by [Kelsi Olstad](https://github.com/kel-si), [Ryan Williams](https://github.com/Ryan-Williams-Dev) and [Rhiannon Krowchuk](https://github.com/rkrowchuk)
