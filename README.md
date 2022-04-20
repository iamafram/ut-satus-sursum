
# ut satus sursum

A program that sends you a text message when your computer starts up properly.

## Run Locally

Clone the project

```bash
  git clone https://github.com/iamafram/ut-satus-sursum
```

Install dependencies

```bash
  go get -d ut-satus-sursum
```

Go to the project directory

```bash
  cd ut-satus-sursum
```

Run the program

```bash
  go run main.go
```


## Appendix

Do not forget to set the following environment variables (export for Linux / set for Windows) :

```bash
export/set TWILIO_ACCOUNT_SID=your_twilio_account_sid
export/set TWILIO_AUTH_TOKEN=your_twilio_token
export/set TWILIO_PHONE_NUMBER=your_twilio_phone_number
export/set TO_PHONE_NUMBER=your_personal_phone_number
```

To run this program every time your machine starts up, create a rule (crontab / scheduled tasks and cron jobs).

## Authors

- [AFRAM](https://www.github.com/iamafram)

