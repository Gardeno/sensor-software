# Developing Locally

```
virtualenv -p python3 venv
./venv/bin/pip install -r requirements.txt
cp .env.example .env 
# Edit .env file with actual values from a sensor
python main.py
```

# Deploying this software

Copy {main.py,requirements.txt,.env.example} to the `gardeno.global` repository in `src/sensor_software/executable`