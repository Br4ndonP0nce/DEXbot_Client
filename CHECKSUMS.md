# Version Checksums

A checksum is a technique used to determine the authenticity of data by running a value through a hashing algorithm. If you havent installed DEXbot yet, you can [download the client application or compile from the source code](https://github.com/DEXbotLLC/DEXbot_Client/wiki/2.-Installation).

a are established by the running a checksum validator on the binary file generated from the downloaded source code. After compiling a binary from the source code, or downloading the binary directly in [Releases](../../releases), open a terminal prompt, navigate to the folder containing the binary file, and run the following command to display the checksum of the DEXbot client application

<br>
<br>

**After downloading the application, it is very important to check the checksum of the binary before running it.** This ensures that the code you have compiled is safe and not has not been changed. Navigate to the folder with the compiled DEXbot application and run the following command.

<br>

| Operating System | Command |
| --------| ------------ |
|   MacOS/Linux   | `sha256sum dexbot`   |
|   Windows  | `certutil -hashfile dexbot SHA256`   |

<br>
<br>

Once you have the checksum value, you will need to verify that it is the correct value. Compare your value to the matching official version checksum below. 

<br>

## Release Date / Checksums

| Version | Release Date | Currently Supported| Checksum             | Change Log     |
| --------| ------------ | ------------------ | -------------------- | ---------------|
| 1.0     | 12-31-2021   | :white_check_mark: |`xxxxWILL_UPDATExxxx` | [Changes](../../blob/main/CHANGELOG.md#100) |
