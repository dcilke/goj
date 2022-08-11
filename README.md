Forked from https://cs.opensource.google/go/go/+/master:src/encoding/json/;drc=46ab7a5c4f80d912f25b6b3e1044282a2a79df8b

# Addons

### Decoder.ReadByte()

`ReadBytes()` reads a single byte from the input stream, updating the internal cursor and returning to the user. It also reset the decoders error state. The primary use case is to advance input streams which have mixed json and binary data.
