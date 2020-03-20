# kelbM_identity
* [Esx_identity](https://github.com/ESX-Org/esx_identity) which I modified with css3

# Preview
![](https://imgur.com/fLgq968)

## Requirements
* Dependencies For Full Functionality
  * [esx_skin](https://github.com/ESX-Org/esx_skin)
  * [esx_policejob](https://github.com/ESX-Org/esx_policejob)
  * [esx_society](https://github.com/ESX-Org/esx_society)
  
  ## Installation
- Import `kelbM_identity.sql` in your database
- Add this to your `server.cfg`:

```
ensure kelbM_identity
```

- If you are using esx_policejob or esx_society, you need to enable the following in the scripts' `config.lua`:
```Config.EnableESXIdentity          = true```

### Commands
```
/register
/charlist
/charselect(1,2,3)
/chardel(1,2,3)
```
