# How to set timezone to an automation test in Pytest on [LambdaTest](https://www.lambdatest.com/?utm_source=github&utm_medium=repo&utm_campaign=Pytest-timezone)

If you want to run your automation test for a particular timezone in Pytest on Lambdatest, you can use the following steps. You can refer to sample test repo [here](https://github.com/LambdaTest/pytest-selenium-sample).

# Steps:

To run your automation test for a particular timezone, you can change the timezone using the 'timezone' capability in the `conftest.py` file. For example, setting timezone to "UTC-5:00":

 ```python
capabilities = {
        "build": "Sample PY Build",
        "platformName": "Windows 11",
        "browserName": "Chrome",
        "browserVersion": "latest",
		"timezone": "UTC-05:00"
}
 ```

For the full list of available capabilities, you can refer [here](https://www.lambdatest.com/support/docs/selenium-automation-capabilities/).

## Run your test

```bash
cd tests //navigate to tests directory
python sample_todo.py
```

# Links:

[LambdaTest Community](http://community.lambdatest.com/)

