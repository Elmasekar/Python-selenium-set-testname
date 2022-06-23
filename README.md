# How to set test name for automation test in Python-selenium on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Python-selenium-set-testname)

To set test name for automation test in Python-selenium on LambdaTest, the following steps can be followed. You can refer to sample test repo [here](https://github.com/LambdaTest/python-selenium-sample).

## Steps

To set test name as method name in UnitTest, the `name` attribute can be added as a capability in the desired capabilities. For example:

```python
desired_caps = {
            'LT:Options': {
                "build": "Python Demo",
                "name": "Python Demo Test",  # Change your test name here
                "platformName": "Windows 11",
                "selenium_version": "4.0.0", 
            },
            "browserName": "Chrome",
            "browserVersion": "98.0",
        }

```

### Run your test

```bash
python lambdatest.py
```

# Links:

[LambdaTest Community](http://community.lambdatest.com/)


