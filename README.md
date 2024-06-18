# Main idea

To write a simple 3 moving average trading strategy from close price
find the optimized parameters for this weekly filters that produce either:

- the best yields
- the least amount of loosing bets

# funny commands

## start the venv

```bash

python3 -m venv venv
source venv/bin/activate
```

## install the deps

```bash
pip install -r requirements.txt
```

```bash
python3 -m venv venv
source venv/bin/activate
pip install ipykernel
python3 -m ipykernel install --user --name=venv
pip install -r requirements.txt
```

```bash
# check which python env is being used:
which python3
# check which version of pip is being used and from where
python3 -m pip --version
# source de venv created
source venv/bin/activate
# then just install the requirements
pip install -r requirements.txt
```
