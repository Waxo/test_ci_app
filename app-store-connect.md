
# Install Codemagics CLI
```sh
pip3 install codemagic-cli-tools
```

# Set up env vars 

```sh
export APP_STORE_CONNECT_ISSUER_ID=aaaaaaaa-bbbb-cccc-dddd-eeeeeeeeeeee
export APP_STORE_CONNECT_KEY_IDENTIFIER=ABC1234567
export APP_STORE_CONNECT_PRIVATE_KEY=`cat /path/to/api/key/AuthKey_XXXYYYZZZ.p8`
```

# Get Profiles
```sh
app-store-connect list-devices
```

# Get devices ids
```sh
app-store-connect list-devices
```

# Get bundles ids
```sh
app-store-connect list-bundle-ids
```

# Admin zone be cautious, this changes stuff

## Create profiles
```sh
app-store-connect create-profile <bundle-id> --certificate-ids <cert1 cert2 ...> --device-ids <device1 device2 ...> --type <type> [--name <profile name>] 
```
