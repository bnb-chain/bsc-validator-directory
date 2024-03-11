# bsc-validator-directory

## What is a Validator Profile?

BNB Smart Chain validators power the blockchain network by processing transactions and signing blocks. 
Validator candidates need to get support from the delegator community to increase their total voting power. 
This repository is a place for validator candidates to give potential delegators a brief introduction to your team 
and infrastructure, and present your ecosystem contributions.


## How to change your Validator Profile

1. Fork this repository to your own GitHub account.

2. Clone the repo from your own account.

```sh
git clone git@github.com:xxxxxx/bsc-validator-directory.git
cd bsc-validator-directory/
```

3. Create a folder with the operator address of your validator, like "0x6789f6Ed99B28027B609822D434FD2B637Ed4387"

4. Create your folder: `validators/<your-operator-address>`. 
Upload your logo with file named logo.png and profile.json to previously created folder, 
and if you have done all correctly, your path should look like this `validators/0x6789f6Ed99B28027B609822D434FD2B637Ed4387/logo.png`.
Logo must have dimensions: min: 64x64 and max: 512x512

5. Change the contents and add your information as necessary.

6. Commit and push the information to your repo.

```sh
git add -A
git commit -m "Edit validator profile"
git push origin main
```

7. Under your repo page, click the “New pull request” button. Make a Pull Request with our repository with a summary of changes.

8. We will review your PR as soon as possible.


### profile.json

Registered validators (validators who have submitted a profile) can opt in to receive support by putting their contact information in `profile.json`.

```json
{
    "contact": {
        "email": "validator@example.com",
        "twitter":"exampleaccount",
        "telegram": "@validator123",
        "website": "https://www.example.com"
    },
    "notifications": {
        "email": "technicalemail@example.com"
    }
}
```
