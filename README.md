# Assignments for BU's DS 593

This repository contains the code for the Differential Privacy assignment in
DS 593 in Fall 2026.

See [https://ds593.babman.io/2026/assign/dp.html](https://ds593.babman.io/2026/assign/dp.html) for the assignment
handout.

#### This assignment requires Python 3.14

## Setup

```
python3.14 -m venv venv && . venv/bin/activate
pip install -r requirements.txt
```

Then create a `.env` file next to `client.py` with the server address and
password. You can find both on Piazza.

```
DP_SERVER_URL=http://<host>:3333
DP_SERVER_PASSWORD=<password>
```

`.env` is gitignored: do not commit or share it. Both values can also be set
directly in the environment, which takes precedence over `.env`.
