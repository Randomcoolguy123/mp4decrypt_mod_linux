# mp4decrypt_mod_linux

Modded version of mp4decrypt from https://www.bento4.com/

## Usage

```cmd
usage: mp4decrypt [options] <input> <output>
Options are:
  --show-progress : show progress details
  --key <id>:<k>
      <id> is either a track ID in decimal or a 128-bit KID in hex,
      <k> is a 128-bit key in hex
      (several --key options can be used, one for each track or KID)
      note: for dcf files, use 1 as the track index
      note: for Marlin IPMP/ACGK, use 0 as the track ID
      note: KIDs are only applicable to some encryption methods like MPEG-CENC
  --fragments-info <filename>
      Decrypt the fragments read from <input>, with track info read
      from <filename>.
```

# Demo
![](https://i.imgur.com/CoOWCkN.png)

## Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

## Credit
All credits go to Bento4 (owner and creator of this software) and to GO3 for its modded version 
