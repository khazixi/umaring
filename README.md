# UMass Amherst Web Ring

This is a web ring for UMass Amherst students, alumni, and faculty.
It is a collection of personal websites, blogs, and other web pages.

## How to join
1. Add your website to the members.json and submit a pull request.
2. Once accepted make sure to add the webring to your website in some way.

### Using our script
A script has not been made yet, but will be soon.

### Using your own script
Please integrate with the following API:
`GET https://umaring.hamy.cc/:id`
This will return a JSON object with the following format:
```json
{
    "prev": {
        "id":"usera",
        "name":"User A",
        "url":"https://usera.com"
    },
    "member": {
        "id":"userb",
        "name":"User b",
        "url":"https://userb.com"
    },
    "next": {
        "id":"userc",
        "name":"User C",
        "url":"https://userc.com"
    }
}
```
Please pull the latest version of the webring at least once every 6 hours, but preferably once every hour. This will ensure that the webring is up to date.
`