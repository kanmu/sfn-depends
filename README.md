# sfn-depends

## Usage

```
Usage: sfn-depends [OPTION] STATE_MACHINE_ARN...
  -period string
    	period
  -version
    	print version and exit
```

```sh
$ sfn-depends -period 1d cron-test
validate cron-test
state machine is successfully completed.
```
