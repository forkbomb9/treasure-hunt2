# Treasure Hunt 2

Get 800GB free on Treasure Cloud

This is based on [xuac](https://github.com/xuac/treasure-hunt)'s original code, updated to TC's new emails.

Confirmed working on 2021/06/21.

### Get Started

1. [Fork](https://github.com/forkbomb9/treasure-hunt2/fork) the repository
2. Go to the Actions tab
3. Click on the `Hunt` workflow under `All workflows`
4. Click on the `Run Workflow ▼` dropdown
5. Enter [your referral code](https://app.treasure.cloud/settings/referrals) (part of the referral link after `...signup?code=`)
6. Click `Run Workflow`
7. When it stops, run again...

### Run Locally

These instructions are for running on Linux. You'll need NodeJS 15 or above.

1. Clone the repo

   ```sh
   git clone https://github.com/forkbomb9/treasure-hunt2.git
   cd treasure-hunt2
   ```

2. Install Dependencies

   ```sh
   yarn # or npm i
   sudo apt install -y $(cat deps.txt) # dependecies for puppeteer
   ```

3. Run

   ```sh
   yarn start [your referral code]
   # or npm run start [your referral code]
   ```

If you run it locally, you'll also see a `screenshots` folder with screenshots of all the steps for all the emails.

### Disclaimer

If/When they find out about this, they may suspend all the accounts and take away all the bonus storage. Whatever the case is, you are responsible for what happens to your account.
