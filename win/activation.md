# activation

## commands

run these commands as admin in `cmd.exe` as needed.

### info
```bat
# shows license info
slmgr.vbs /dlv

# shows expiry info
slmgr.vbs /xpr
```

### activate
```bat
# activate by phone call to Microsoft
slui 4

# activate with product key
slmgr.vbs /ipk <product key>
```

### reset product key
```bat
# uninstalls product key and returns to trial
slmgr.vbs /upk

# clear product key from registry
slmgr.vbs /cpky
```

## apps

- **[react.exe](https://www.d7xtech.com/free-software/react)** is a small utility for windows activation that offers options like supressing activation prompts, opening the activation window from an easy panel and checking the activation status.
