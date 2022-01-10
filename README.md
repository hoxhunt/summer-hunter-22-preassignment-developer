The dictator of Snakeworld Ssamantha Snek has received all the accounts and passwords for the inhabitants of Snakeworld. Instead of responsibly removing the leaked data, she'd like to use this opportunity for punishing snakes with bad password hygiene. Ssamantha knows that it's dangerous to use the same password in several services - if one service is breached an attacker can now access all services with a shared password.

Ssamantha would like you to find the number of users who have reused any password in 3 or more services. Ssamantha tells you that she will remove all data and secure the breach if you help her, so you reluctantly agree.

Your puzzle input contains an array of data in the format: `["service:email:password"]`. Your job is to find return the amount of users that have used any password more than twice.

In the following example:

```
aol:juliuss@snek.com:123password
yahoo:juliuss@snek.com:verystrongpasswordtoobaditsyahoo
netflix:juliuss@snek.com:123password
google:juliuss@snek.com:123password
aol:juliuss@snek.com:catfish
google:markuss@snek.com:catfish
yahoo:markuss@snek.com:catfish
```

Juliuss has reused the password `123password` in 3 services, so you should count him. Markuss, however has only reused the password `catfish` in two services, so you don't need to count him. The answer here would therefore be 1.

We are looking for clean and readable code, so don't return a one-liner regex for this ;). We'll grade your assignment with the following model:

- Code quality (clean, maintainable, readable) 3p
- Answer is correct 1p
- Code is returned correctly 1p

We don't expect you to use a long time on this exercise. If we decide to move on with you, there will be a more thorough take-home assignment to complete before the interview.

You may use a tooling library like lodash or ramda if you wish.

Once you are done, return your index file as an **unlisted and syntax highlighted** [pastebin](https://pastebin.com) link, and reply the link to the hiring manager.

Good luck!

P.S. Never use the same password in more than two services. We recommend using two-factor authentification when possible, and a password manager with generated passwords for your services. If you are in a real life situation like this, report Ssamantha to the authorities and delete the credentials.
