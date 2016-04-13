# Lucy Parsons Labs Fiscal Information

### About

At Lucy Parsons Labs we hold ourselves to a high standard to be as radically transparent as possible, and to do so we made a conscious decision to carry that into our finances making them 100% public. This repository will hold a public and complete copy of our finances available to anyone to review them at anytime. This repository will be updated bi-weekly with all current information on all aspects of money in and out of LPL.

Lucy Parsons Labs is a registered 501(c)3 Chicago-based non-profit collaboration between data scientists, transparency activists, and technologists which focuses on the intersection of digital rights and on-the-streets issues.

## How To View The Data

We've chosen to use [Ledger](http://www.ledger-cli.org/) which, per the website says it "is a powerful, double-entry accounting system that is accessed from the UNIX command-line." Ledger is 100% Free Software released under the BSD license, it's rather simple to use and gives us plenty to work with.

Ledger is a double-entry accounting system so there are a few things to keep in mind.

1. Income is noted as negative and highlighted as red.
2. Double-entry accounting means that all entries must balance and each entry must have a credit and a debit.

If you're ready to jump in, first, install Ledger using the instructions [here](https://github.com/ledger/ledger0).

After setting-up Ledger you will need to clone [this repo](https://github.com/lucyparsons/fiscal)(The repo you're currently viewing.)

After cloning the repo change to the directory and choose one of the files named `YYY-MM.dat` and open it using the below command.

```bash
$ ledger -f YYYY-MM.dat b
```

## How To Read The Data

Coming soon...

## A Note From The CFO

Coming soon...

## Monthly Update

If you don't want to mess around with installing Ledger and cloning the repo you can find a monthly update in this section with more information coming soon.
