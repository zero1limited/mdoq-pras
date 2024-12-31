# mdoq-pras

# Installation

Add to your MDOQ PRAs script like
```bash
    "$ARGUMENT_STEP_FINAL-$ARGUMENT_COMPARISON_AHEAD")
        set -xe
        # do something
        curl -s https://raw.githubusercontent.com/zero1limited/mdoq-pras/master/entrypoint | bash
        ;;
    "$ARGUMENT_STEP_FINAL-$ARGUMENT_COMPARISON_IDENTICAL")
        set -xe
        # do something
        curl -s https://raw.githubusercontent.com/zero1limited/mdoq-pras/master/entrypoint | bash
        ;;
    "$ARGUMENT_STEP_FINAL-$ARGUMENT_COMPARISON_BEHIND")
        set -xe
        # do something
        curl -s https://raw.githubusercontent.com/zero1limited/mdoq-pras/master/entrypoint | bash
        ;;
    *)
```
Or if you want to run for all status
```bash
    "$ARGUMENT_STEP_FINAL-"*)
        set -xe
        # do something
        curl -s https://raw.githubusercontent.com/zero1limited/mdoq-pras/master/entrypoint | bash
        ;;
```

# Help
For all options available run `./entrypoint --help`

```txt
ZERO1 Common PRA's for use on MDOQ
----------------------------------
--skip-captcha              skips captcha functionality
--captcha-threshold=        change the captcha threshold (default 0.0)
--captcha-public-key=       change the public key used for captcha (default will work on MDOQ)
--captcha-private-key=      change the private key used for captcha (default will work on MDOQ)
--skip-account-sharing      skips enabling admin account sharing
--skip-disable-form-key     skips disabling admin form key
----------------------------------
see repo for more info: https://github.com/zero1limited/mdoq-pras
```