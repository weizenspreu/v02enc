# 0.2b11 (2026-02-04)

* fix check if HEADERMACKEY was derived
* fix typos throughout the code
* fix quotes in examples

# 0.2b10 (2025-12-13)

* add `v02wg-quick`

# 0.2b9 (2025-10-13)

* rename developer

# 0.2b8 (2025-06-01)

* improve syntax of Bash scripts

# 0.2b7 (2024-09-20)

* move KDF iterations into a separate constant

# 0.2b6 (2024-09-11)

* show help if no arguments are provided

# 0.2b5 (2024-09-06)

* add `-c` and `--keychain` to use hex-decoded keys from the macOS keychain

# 0.2b4 (2024-09-02)

* do not check trailing content on update

# 0.2b3 (2024-09-01)

* handle leading and trailing line breaks of armored input more properly

# 0.2b2 (2024-09-01)

* add info if handling ends before input eof
* add eof check before excessive key expansions are executed

# 0.2b1 (2024-08-31)

* increase block length to speed up encryption and decryption

# 0.2b0 (2024-08-31)

* improve the file structure to support streamed encryption
* update `ENCRYPTION.md` to reflect the updated file structure
* introduce streamed encryption
* deduplicate encryption code

# 0.2a2 (2024-08-29)

* fix message length check during update
* prevent fatal errors on empty paths
* add `v02gitdiff`
* add `v02hgdiff`
* extend `README.md` to mention the new wrappers

# 0.2a1 (2024-08-27)

* check minimum length of message earlier
* check minimum number of recipients
* check maximum number of recipients
* improve `README.md` with examples

# 0.2a0 (2024-08-25)

* improve the file structure to only use one subkey nonce
* update `ENCRYPTION.md` to reflect the updated file structure
* improve `vim02enc` to only encrypt modified temporary files

# 0.1a0 (2024-08-24)

* initial release
