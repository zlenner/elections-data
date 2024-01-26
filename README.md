# elections-data

Election data for every single constituency in Pakistan, including the candidates, party affiliations, and image links of their symbols.

All as JSON.

This data was extracted from ECP's image scans of Form-33's here:

**Punjab:** https://drive.google.com/drive/folders/1-Sjn24YKSR10-WmmFpWDRRO1csDe8TMj

**Sindh:** https://drive.google.com/drive/folders/1YPqxEW6Jku1D9G9GE19HqXCyF7PiO6ff

**Khyber Pakhtunkhwa:** https://drive.google.com/drive/u/0/folders/1cxPb0EYMBcrYivV3XB54bkZadsIc67uY

**Balochistan:** https://drive.google.com/drive/folders/1P4CaSxjhZIIfSxZCHdp843QNbzl7n0Lm

# symbol_file

Images for nearly all symbols have been uploaded to an R2 bucket hosted at https://symbols.azaadvote.com.

To view or download the image of any symbol, find the `symbol_file` field in the JSON and use it to construct a URL like this:

https://symbols.azaadvote.com/{symbol_file}.jpg

For example:

https://symbols.azaadvote.com/aeroplane.jpg

# Inquiries and using this data

If you need to bulk-download the symbol images or other data not in this repo, you can reach out to me on Twitter @clynergy.