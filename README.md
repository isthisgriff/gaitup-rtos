# GaitUpRTOS



The RTOS used for GaitUp, the posture correction wearable. This OS is built using ZephyrRTOS, for the Nordic nRF52840dk



## Setup

**Clone the repo and enter it**

```

git clone git@github.com:isthisgriff/gaitup-rtos.git

cd gaitup-rtos

```

**Setup the Python virtual environment**

```

python3 -m venv .venv

```

**IMPORTANT**

*if you are on Windows, use the following command:*

```

.venv\Scripts\activate

```

*otherwise use this one:*

```

source .venv/bin/activate

```

Then proceed here - 

```

pip install -r requirements.txt

```

**Setup the Zephyr environment**

```

west init -l .

west update

```

*this might take a few minutes depending on update size*

