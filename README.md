# Pipeline Automation

This repository was created to test Github custom actions.

## Actions

### test-action

This is a test action

#### Inputs
1) `who-to-greet` The name of the person to greet. Default `"World"` **(required)**.

#### Outputs
1) `time` The time we greeted you.

#### Requires
* Secret A
* Secret B
* Env variable who-to-greet
* Env variable Y

#### Example
uses: actions/hello-world-docker-action@v2
with:
  who-to-greet: 'Mona the Octocat'
